all:
	@true

UNITSDIR ?= /usr/lib/systemd/user

install:
	install -m 0755 -D qubes-domu-dbus-notification-daemon \
		$(DESTDIR)/usr/lib/qubes/qubes-domu-dbus-notification-daemon
	install -m 0644 -D qubes-tray-notification.service \
		$(DESTDIR)$(UNITSDIR)/qubes-tray-notification.service
	install -m 0644 -D org.freedesktop.qubes.Notifications.service \
		$(DESTDIR)/usr/share/dbus-1/services/org.freedesktop.qubes.Notifications.service
