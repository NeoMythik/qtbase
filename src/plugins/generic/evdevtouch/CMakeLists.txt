# Generated from evdevtouch.pro.

#####################################################################
## QEvdevTouchScreenPlugin Plugin:
#####################################################################

qt_add_plugin(QEvdevTouchScreenPlugin
    OUTPUT_NAME qevdevtouchplugin
    TYPE generic
    SOURCES
        main.cpp
    PUBLIC_LIBRARIES
        Qt::Core
        Qt::CorePrivate
        Qt::Gui
        Qt::GuiPrivate
        Qt::InputSupportPrivate
)

#### Keys ignored in scope 1:.:.:evdevtouch.pro:<TRUE>:
# OTHER_FILES = "evdevtouch.json"
# PLUGIN_EXTENDS = "-"
