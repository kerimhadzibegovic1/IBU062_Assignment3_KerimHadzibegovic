UPDATED MD FILE

I used the following commands to set up DHCP on the routers LCI:

For the first switch

ip dhcp pool Switch1
network 168.90.0.0 255.255.0.0
default-router 168.90.0.1


For the second switch

ip dhcp pool Switch2
network 210.3.14.0 255.255.255.0  
default-router 210.3.14.1  
