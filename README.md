# Test1
Frst REP for testing.

auto eth2 eth3 team1
iface team1 inet static
address 10.43.137.14
netmask 255.255.255.192
gateway 10.43.137.1
bond_mode balance-alb
bond_miimon 100
bond_downdelay 200
bond_updelay 200
slaves eth2 eth3
