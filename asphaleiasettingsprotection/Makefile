INSTALL_TARGET_PROCESSES = Preferences

include $(THEOS)/makefiles/common.mk

TWEAK_NAME = AsphaleiaSettingsProtection
AsphaleiaSettingsProtection_FILES = Tweak.xm
AsphaleiaSettingsProtection_FRAMEWORKS = UIKit
AsphaleiaSettingsProtection_CFLAGS = -fobjc-arc -O2
AsphaleiaSettingsProtection_LDFLAGS = -L"../.theos/obj/debug"
AsphaleiaSettingsProtection_LIBRARIES = asphaleiaui

include $(THEOS_MAKE_PATH)/tweak.mk
