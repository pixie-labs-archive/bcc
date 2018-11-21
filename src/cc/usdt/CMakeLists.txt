add_library(usdt-static STATIC usdt_args.cc usdt.cc)
install(TARGETS usdt-static ARCHIVE DESTINATION ${CMAKE_INSTALL_LIBDIR})
