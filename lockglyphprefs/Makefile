include $(THEOS)/makefiles/common.mk

BUNDLE_NAME = LockGlyphPrefs
LockGlyphPrefs_FILES = LockGlyphPrefs.mm
LockGlyphPrefs_INSTALL_PATH = /Library/PreferenceBundles
LockGlyphPrefs_FRAMEWORKS = UIKit CoreGraphics QuartzCore
LockGlyphPrefs_PRIVATE_FRAMEWORKS = Preferences
LockGlyphPrefs_LIBRARIES = colorpicker

include $(THEOS_MAKE_PATH)/bundle.mk

internal-stage::
	$(ECHO_NOTHING)mkdir -p $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences$(ECHO_END)
	$(ECHO_NOTHING)cp entry.plist $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences/LockGlyphPrefs.plist$(ECHO_END)
