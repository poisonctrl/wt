IF(INSTALL_EXTENSIONLESS_HEADERS)
  INSTALL_FILES(/include/Wt/Json "^[^.]+([.][^C~])?$")
ELSE(INSTALL_EXTENSIONLESS_HEADERS)
  INSTALL_FILES(/include/Wt/Json "^[^.]+[.]h$")
ENDIF(INSTALL_EXTENSIONLESS_HEADERS)
