<img src="https://i.imgur.com/IfsTVAq.png" height="150" title="HackintoshLogo">

# Hackintosh Z690

**Current macOS version:** 13.2.1 (22D68)

**Current OC version:** OpenCore 0.9.0

## Specs

**CPU:** Intel Core i7-13700KF

**Cooling:**

- NZXT Kraken Z73 360mm
- 3x Noctua NF-F12 Chromax 120mm

**Motherboard:** Gigabyte Z690 AORUS ELITE DDR4

**GPU:** Powercolor RX 6800 Red Devil Edition 16GB (Navi 21, works natively)

**WiFi/Bluetooth:** Broadcom BCM94360CS with PCIe adapter (works natively)

**Ethernet:** Realtek RTL8125B 2.5 Gigabit Ethernet

**RAM:** 32GB @ 3600 MHz DDR4 (XMP works)

**NVME SSD:**

- 1TB WD Black SN850X Gen. 4
- 1TB Samsung 980 PRO Gen. 4

**Power Supply:** Corsair RM1000x

**PC Case:** Lian Li O11 Dynamic Razer Edition

**Display**: Gigabyte M32UC (capped to 120Hz via DP on macOS, HDR works)

**SMBIOS**: iMacPro1,1

## Changelog

### Sleep / Wake Problems (March 20 2023)

- Disconnected NZXT AIO pump's internal USB port (pump will default to silent profile)
- Mapped Bluetooth card PCIe adapter's USB connector as internal
- 4K monitor black screen on wake due to AGDC preferences (patch applied)

## Benchmarks

### GeekBench (March 20 2023)

- [CPU benchmark](https://browser.geekbench.com/v6/cpu/616566)
- [GPU benchmark - Metal](https://browser.geekbench.com/v6/compute/224580)
- [GPU benchmark - OpenCL](https://browser.geekbench.com/v6/compute/224581)
