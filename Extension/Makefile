TWEAK_NAME = IconSupport

IconSupport_OBJCC_FILES = IconSupport.mm IconSupportClassic.mm ISIconSupport.mm ISAlertItem.mm ISLayoutRepairedAlertItem.mm ISStaleFileAlertItem.mm Preferences.mm
IconSupport_FRAMEWORKS = UIKit CoreGraphics
IconSupport_OBJCCFLAGS = -DAPP_ID=\"$(APP_ID)\" -I ../Common -include Headers.h -include Firmware.h -fvisibility=hidden

include ../theos/makefiles/common.mk
include ../theos/makefiles/tweak.mk
