# Generated from wayland-egl.pro.

#####################################################################
## QWaylandEglClientBufferIntegrationPlugin Plugin:
#####################################################################

qt_add_plugin(QWaylandEglClientBufferIntegrationPlugin
    OUTPUT_NAME qt-wayland-compositor-wayland-egl
    TYPE wayland-graphics-integration-server
    SOURCES
        ../../../../hardwareintegration/compositor/wayland-egl/waylandeglclientbufferintegration.cpp ../../../../hardwareintegration/compositor/wayland-egl/waylandeglclientbufferintegration.h
        main.cpp
    INCLUDE_DIRECTORIES
        ../../../../hardwareintegration/compositor/wayland-egl
    LIBRARIES
        EGL::EGL
        Wayland::Egl
        Wayland::Server
    PUBLIC_LIBRARIES
        Qt::CorePrivate
        Qt::EglSupportPrivate
        Qt::GuiPrivate
        Qt::WaylandCompositor
        Qt::WaylandCompositorPrivate
)

#### Keys ignored in scope 1:.:.:wayland-egl.pro:<TRUE>:
# OTHER_FILES = "wayland-egl.json"
