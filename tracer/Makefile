#TARGET = iphone:6.1
#ARCHS = armv7
include theos/makefiles/common.mk

TWEAK_NAME = introspy
introspy_FILES = Tweak.xmi CallTracer.m hooks/CommonDigestHooks.m hooks/LibCHooks.m hooks/KeychainHooks.m hooks/DelegateProxies.m PlistObjectConverter.m hooks/CommonKeyDerivationHooks.m CallStackInspector.m SQLiteStorage.m hooks/SecurityHooks.m hooks/CommonCryptorHooks.m hooks/CommonHMACHooks.m
introspy_LIBRARIES = sqlite3 

introspy_FRAMEWORKS = UIKit, Foundation, Security
include $(THEOS_MAKE_PATH)/tweak.mk
