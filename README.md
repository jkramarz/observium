observium
=========

Patches for Observium.org used in August Witkowski High School in Cracow before change to Check MK.

Most of them has been merged to upstream, but some are just hacks for old or low budget hardware compatibility.
* catos-ifAlias.diff - repairs ifAlias value on Cisco Catalyst 3500 running CatOS on Supervisor II
* ipmi-units.diff - repairs units  when using iLO's IPMI on HP ML350
* nut.diff - NUT UPS monitoring over SNMP
* syslog.diff - repairs log parsing when using NTsyslog on Windows or Cisco WAP200 access points
* userbean.diff - adds OpenVZ pooling 