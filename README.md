# VANET-Simulation-in-MATLAB

Originally reactive protocols were not design for the characteristic of highly mobility during route discovery. Due to dynamically modification to the VANET this changes very often due to breakdown which causing excessive broadcasting and flooding the entire network in order for new routes to be discovered. In additional, the initial of routing need some time and this latency can easily change everything. Due to these reasons, the typical reactive protocols, in their current format, do not totally appropriate for time critical applications such as cooperative collision avoidance (CCA). The Cooperative Collision Avoidance is an important class of safety applications in VANETs, which aims at offering earlier warning to drivers using vehicle-to-vehicle (V2V) communication [13].
Ad Hoc On Demand Distance Vector (AODV) is an reactive routing protocolwhich capable of both unicast and multicast. In AODV, like all reactive protocols,topology information is only transmitted by nodes on-demand. When source hassomething to send then initially it propagates RREQ message which is forwarded byintermediate node until destination is reached. A route reply message is unicastedback to the source if the receiver is either the node using the requested address, or ithas a valid route to the requested address.

This repository provides a MATLAB simulaiton of VANET enviornment and rsults comparison in terms of throughput, packet drop ratio etc.