# Generated from lib.pro.

#####################################################################
## mylib Generic Library:
#####################################################################

add_cmake_library(mylib
    SHARED
    INSTALL_DIRECTORY "${INSTALL_TESTSDIR}/tst_qlibrary"
    OUTPUT_DIRECTORY "${CMAKE_CURRENT_BINARY_DIR}/../"
    SOURCES
        mylib.c
    PUBLIC_LIBRARIES
        Qt::Core
)

# special case begin
set_target_properties(mylib PROPERTIES
    VERSION 1.0.0
    SOVERSION 1
    C_VISIBILITY_PRESET "default"
    CXX_VISIBILITY_PRESET "default"
)
# special case end

#### Keys ignored in scope 1:.:.:lib.pro:<TRUE>:
# INSTALLS = "target"
# TEMPLATE = "lib"
# target.path = "$$[QT_INSTALL_TESTS]/tst_qlibrary"

## Scopes:
#####################################################################

extend_target(mylib CONDITION MSVC
    DEFINES
        WIN32_MSVC
)

#### Keys ignored in scope 4:.:.:lib.pro:(CMAKE_BUILD_TYPE STREQUAL Debug):
# DESTDIR = "../debug/"

#### Keys ignored in scope 5:.:.:lib.pro:else:
# DESTDIR = "../release/"
