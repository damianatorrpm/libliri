liri_add_qml_plugin(liridevice
    MODULE_PATH
        "Liri/Device"
    VERSION
        "1.0"
    SOURCES
        plugin.cpp
    QML_FILES
        qmldir
    DEFINES
        QT_NO_CAST_FROM_ASCII
        QT_NO_FOREACH
    PUBLIC_LIBRARIES
        Liri::LocalDevice
)
