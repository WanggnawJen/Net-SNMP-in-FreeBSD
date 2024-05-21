Test your snmp v3 configuration
==================================

snmpwalk  -v3  -l authPriv  -u  roUser1  -a SHA  -A snmpauth  -x AES  -X snmpencr   192.168.147.124   iso.3.6.1.2.1.25.1.1.0

