AUTOMAKE_OPTIONS=foreign subdir-objects
AM_CFLAGS = -I$(abs_top_srcdir)/include $(CODE_COVERAGE_CFLAGS)
noinst_LTLIBRARIES = libplatform.la
libplatform_la_SOURCES = linux/linux_events.c \
linux/linux_keyboard.c \
linux/linux_display.c \
linux/linux_mouse.c \
linux/linux_x11events.c \
linux/linux_x11mouse.c \
linux/linux_x11keyboard.c \
linux/linux_x11display.c \
linux/linux_ime.c \
linux/linux_fbdisplay.c \
windows/windows_events.c \
windows/windows_keyboard.c \
windows/windows_display.c \
windows/windows_mouse.c \
windows/windows_ime.c

EXTRA_DIST = windows/pch.cpp \
windows/pch.h \
windows/uwp_app.cpp \
windows/uwp_app.h \
windows/uwp_input.cpp \
windows/uwp_input.h \
windows/uwp_main.cpp \
windows/uwp_main.h \
windows/uwp_renderer.cpp \
windows/uwp_renderer.h \
windows/Common/DeviceResources.cpp \
windows/Common/DeviceResources.h \
windows/Common/StepTimer.h \
windows/Common/DirectXHelper.h
