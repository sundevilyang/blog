---
authors:
- cunnie
categories:
- Logging & Metrics
- FreeNAS
date: 2019-05-25T17:16:22Z
draft: true
short: |
  By upgrading our iSCSI-based NAS server from 1 GbE to 10 GbE, we
  increased the write throughput four-fold and the read throughput three-fold
title: "A High-performing Mid-range NAS Server, Part 3: 10 GbE tuning"
---

| Component  | 10 GbE<br />(new, 2019) | 1 GbE<br />(old, 2104) |
|---|---|---|
| Motherboard | $820 1 × [Supermicro X10SDV-8C-TLN4F+ Mini-ITX 35W 8-Core Intel Xeon D-1537](https://www.supermicro.com/products/motherboard/Xeon/D/X10SDV-8C-TLN4F_.cfm) | $375 1 × [Supermicro A1SAi-2750F Mini-ITX 20W 8-Core Intel C2750](https://www.supermicro.com/products/motherboard/Atom/X10/A1SAi-2750F.cfm) |
| RAM | $1,336 4 × D760R Samsung DDR4-2666 32GB ECC Registered | $372 4 × Kingston KVR13LSE9/8 8GB ECC SODIMM |
| HBA | (same HBA) | $238 1 × [LSI SAS 9211-8i 6Gb/s SAS Host Bus Adapter](https://docs.broadcom.com/docs/12352062) |
| Disk | (same Disk) | $1,190 7 × Seagate 4TB NAS HDD ST4000VN000 |
| Power Supply | (same Power Supply) | $110 1 × [Corsair HX650 650 watt power supply](https://www.corsair.com/us/en/Categories/Products/Power-Supply-Units/hx-series-config/p/CP-9020030-NA) |
| Ethernet Switch | $589 1 × [QNAP QSW-1208-8C 12-port 10GbE unmanaged switch](https://www.qnap.com/en-us/product/qsw-1208-8c) | $18 1 × [TP-Link 8-Port Gigabit Desktop Switch TLSG1008D](https://www.tp-link.com/us/home-networking/8-port-switch/tl-sg1008d/) |
| SFP+ Modules | $79 2 × [Ubiquiti UF-MM-10G U Fiber SFP+ Module 2-pack](https://store.ui.com/collections/all/products/uf-mm-10g-20-20-pack) | N/A |

## References

- [A High-performing Mid-range NAS Server, Part 1: Initial Set-up and Testing](https://content.pivotal.io/blog/a-high-performing-mid-range-nas-server)
- [A High-performing Mid-range NAS Server, Part 2: Performance Tuning for iSCSI](https://content.pivotal.io/blog/a-high-performing-mid-range-nas-server-part-2-performance-tuning-for-iscsi)
