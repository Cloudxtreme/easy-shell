This project will let linux users easily configure built-in features like routing, iptables, interfaces and policy routing in the same fashion as juniper routers does. It will in future support all the famous daemons as well,

few of the daemons like apache. bind etc. few of the examples are given below.

show commands:

user@hostname> show hostname, show interface terse, show ntp associations, show route (a new interface to iproute2)

it will support autocomplete and '?' for displaying help feature.

configuration:
e.g,
set system host-name
set int eth0 inet address 192.168.0.1/24
set routing-options static route 192.168/24 next-hop x.x.x.x

In the future it ll also support common daemons like apache, bind,

BIND sample: set services dns sample.com MX 192.168.1.1