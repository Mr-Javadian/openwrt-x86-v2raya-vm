# OpenWRT x86 with v2rayA - Virtual Appliance

## Overview
This repository contains a preconfigured OpenWRT VM image (x86 architecture) with:
- v2rayA proxy management pre-installed
- Storage expanded to 8GB
- VMware compatibility

Key Features:
✅ OpenWRT x86 (customized build)
✅ v2rayA pre-installed & configured
✅ 8GB storage allocation
✅ VMware-optimized virtual hardware
✅ Minimal resource footprint

Usage:

Download the VM image

Import into VMware/ESXi

Power on and customize network settings

Access v2rayA dashboard at http://[IP]:2017

Recommended System:
• 1 vCPU | 512MB RAM | 8GB storage


## Quick Start
1. Clone/download this repository
2. Import `.ova`/`.vmx` to VMware Workstation/ESXi
3. Default credentials: `root`/Pass: 37131111]

## Customization
After deployment:
- Change default passwords
- Update v2ray subscriptions
- Adjust network interfaces via LuCI (`http://[IP]`)

## Security Note
This image contains default configurations - harden your setup before production use.

