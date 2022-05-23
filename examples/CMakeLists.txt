build_lib_example(
    NAME xgpon-example
    SOURCE_FILES xgpon-dba-udp-test.cc
    
    LIBRARIES_TO_LINK ${libxgpon}
                      ${libinternet}
                      ${libapplications}
                      ${libpoint-to-point}

)

