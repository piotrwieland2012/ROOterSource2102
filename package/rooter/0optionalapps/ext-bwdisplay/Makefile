#Owned by DairyMan@Whirlpool
#
#Copyright GNU act.
include $(TOPDIR)/rules.mk

PKG_NAME:=ext-bwdisplay
PKG_VERSION:=1.000
PKG_RELEASE:=1

PKG_MAINTAINER:=Created by DM/makefile by Cobia@whirlpool
include $(INCLUDE_DIR)/package.mk

define Package/ext-bwdisplay
  SECTION:=utils
  CATEGORY:=ROOter
  SUBMENU:=Optional Applications
  TITLE:=Added scripts for Login display
  PKGARCH:=all
endef

define Package/ext-bwdisplay/description
  Added scripts for Login display
endef


define Build/Compile
endef

define Package/ext-bwdisplay/install
	$(CP) ./files/* $(1)/


endef

$(eval $(call BuildPackage,ext-bwdisplay))
