# Generated from warnings.pro.

#####################################################################
## warnings Binary:
#####################################################################

add_qt_executable(warnings
    NO_INSTALL # special case
    OUTPUT_DIRECTORY ${CMAKE_CURRENT_BINARY_DIR} # special case
    SOURCES
        tst_warnings.cpp
    PUBLIC_LIBRARIES
        Qt::Test
)

## Scopes:
#####################################################################

# special case begin
qt_apply_testlib_coverage_options(warnings)
# special case end
