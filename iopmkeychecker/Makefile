TARGET := iphone:clang:latest:7.0

include $(THEOS)/makefiles/common.mk

TOOL_NAME = IOPMKeyChecker

IOPMKeyChecker_FILES = main.m
IOPMKeyChecker_CFLAGS = -fobjc-arc
IOPMKeyChecker_CODESIGN_FLAGS = -Sentitlements.plist
IOPMKeyChecker_INSTALL_PATH = /usr/local/bin

include $(THEOS_MAKE_PATH)/tool.mk
