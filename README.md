Multi-Area OSPF
## Overview
Multi-area OSPF lab with 6 Cisco c7200 routers across 3 areas (Area 0, 1, 2)
on EVE-NG Community Edition running on Proxmox VE.

## Topology
Area 1 (R1, R2-ABR, R3-ABR) → Area 0 (R4-ABR) → Area 2 (R5-ABR, R6)

## Skills Demonstrated
- Multi-area OSPF design and ABR configuration
- Inter-area routing verification (O IA routes)
- DR/BDR elimination using point-to-point network type
- Real-world troubleshooting: duplex mismatch, network type mismatch
- OSPF LSA types (Type 1, 2, 3)

## Files
- `configs/` — running configs for all 6 routers
- `screenshots/` — EVE-NG topology and verification outputs  
- `OSPF-MultiArea-Lab-Report.pdf` — full lab documentation

## Verification
All 6 routers achieved FULL adjacency. End-to-end ping verified
from R1 (Area 1) to R6 (Area 2) across all three areas.