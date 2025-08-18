include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-design-config
PKG_VERSION:=1.0
PKG_RELEASE:=20250813

PKG_MAINTAINER:=Ashley Lee (code@emtips.net)

LUCI_TITLE:=LuCI app for Design theme configuration
LUCI_PKGARCH:=all
LUCI_DEPENDS:=+luci-theme-design

define Package/$(PKG_NAME)/conffiles
/etc/config/design
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
