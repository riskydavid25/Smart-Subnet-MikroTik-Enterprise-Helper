# Smart-Subnet-MikroTik-Enterprise-Helper
Kalkulator subnet, VLSM, perencana IP publik, IPAM overlap checker, dan generator konfigurasi MikroTik (satu file `index.html`, tanpa backend).

## Update
- **Firewall baseline**: interface list LAN/WAN, chain `input`/`forward` default-deny dari WAN, opsi isolasi antar-subnet, proteksi open-resolver DNS.
- **DHCP reserved range**: N IP awal tiap subnet dikeluarkan dari pool (static/gateway/server).
- **/31 (RFC 3021)** untuk link P2P (baris berawalan `P2P`/`PTP`/`Link` di Sizing).
- **Klasifikasi IP**: RFC 1918, CGNAT, dokumentasi, link-local, multicast, publik.
- **Tab IP Publik**: mode routed/on-link, NAT pool, DMZ, link P2P ISP, script RouterOS.
- **Tab Overlap/IPAM**: deteksi tabrakan CIDR dan daftar blok kosong di blok induk.
