check_smart
===========

Nagios plugin to check the smart status of all hard drives.

sudo
===========

	# cat /etc/sudoers
	nagios ALL = NOPASSWD: /usr/sbin/smartctl
