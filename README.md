# MeshRouting

* https://downloads.open-mesh.org/batman/papers/Improving%20BATMAN%20Routing%20Stability%20and%20Performance.pdf 
* Thesis describing and enforcing Routing algorith. Only thing still vaugue is how TQ is actually calculated. I think it is a simple add one and shift for the sliding window, but there is also another factor called HOP_PENALTY
* http://eprints.biblio.unitn.it/2269/1/report.pdf
* Another thesis -- describing roaming and client announcement


http://wiki.prplfoundation.org/wiki/Building_OpenWrt  -- qemu build
https://www.open-mesh.org/projects/open-mesh/wiki/Emulation -- batman-adv emulation
scapy -- python making raw packets
arduino ethernet library
http://docs.battlemesh.org/index.html

# Specific BATMAN-adv notes
B.A.T.M.A.N. can be treated as distance-vector despite it is based on periodic
source initiated flooding of OGMs to propagate routing table updates. This
particularity does not modify the protocol classification, as in any case the routing
algorithm used is the Bellman Ford one -- find reference


# Telemetry things. 

https://pixhawk.org/peripherals/onboard_computers/start -- remote processor 
http://www.ebay.com/sch/i.html?_odkw=915mhz+telemetry&_osacat=0&_from=R40&_trksid=p2045573.m570.l1313.TR12.TRC2.A0.H0.Xpixhawk.TRS0&_nkw=pixhawk&_sacat=0 -- places to buy kits
http://www.hoperf.com/upload/docs/data_link/HM-TRP.pdf
http://rctimer.com/product-817.html
