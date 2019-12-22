MPLS VPNs (EVPN, L3VPN)
Segment-Routing (on IOS-XR, IOS-XE)
• EVPN: Multi-homed, Single homed, p2p (VPWS)
• L3VPN: BGP
• IGP: IS-IS (Using Segment-Routing instead of LDP for MPLS Label Distribution)
• 4 PE-Routers (1 XRv9000, 3 CSR1000v) two of them are also Route-Reflectors (SP-XRv-3, SP-CSR-4)
• 2 P-Routers (XRv)
• 11 CE-Devices (IOL L3, IOL L2)
• BGP AFs: L2VPN EVPN, VPNv4 Unicast
• Images: XRv9000 7.0.1, XRv 6.1.3, CSR1000v 16.12.01a, IOL L3 15.7, IOL L2 15.2
• XRv9k 7.0.1 still does not support L2VPN Forwarding (Creation of Bridge-Domains)
• • It took me 12 hours to build and configure this lab!
• Using the awesome emulator EVE-NG Pro
☆ More Screenshots: https://lnkd.in/ddstrWg

* MPLS VPN Labs, Created by Navid Yahyapour (NMAXi)
Lab file URL:
  https://drive.google.com/open?id=1OMsHLT3YrZSjk-uAQjpqcA9Uh319tDpE
! You can only import it into EVE-NG Pro (not the Community edition)  

You can also find configuration files on my GitHub page:
  https://github.com/nmaxi
  
*** My LinkedIn profile: https://www.linkedin.com/in/navid-yahyapour/ ***