# AWS-EC2-VPN-setup

# AWS EC2 OpenVPN Setup

A comprehensive guide for setting up a secure OpenVPN server on AWS EC2 instances using OpenVPN Access Server.


## Overview

This repository documents the complete process of setting up a secure OpenVPN server on AWS EC2. It includes detailed visual guides with 16 screenshots, configuration examples, security best practices, and comprehensive troubleshooting documentation.

### Key Features

- ✅ **OpenVPN Access Server** - Professional-grade VPN solution
- ✅ **AWS EC2 Deployment** - Cloud-based infrastructure
- ✅ **Full Encryption** - TLS 1.2+ with SECP384r1
- ✅ **Easy Management** - Web-based admin interface
- ✅ **Multi-User Support** - Multiple VPN user accounts
- ✅ **DNS Protection** - Routing through VPN server
- ✅ **Access Control** - Granular permission management

## Quick Start

```bash
# 1. Visit Admin Portal
https://YOUR_PUBLIC_IP:943/admin/

# 2. Login
Username: openvpn
Password: Your password

# 3. Download OpenVPN Connect
Admin Portal → Connect a Device → Download

# 4. Create VPN User
Admin Portal → Users → Add User

# 5. Connect to VPN
OpenVPN Connect → Import Profile → Connect
```

**Verify it's working:**
Visit https://whatismyipaddress.com - should show your VPN server's IP

## Project Status

✅ **Complete and Operational**
- EC2 instance deployed
- OpenVPN configured and running
- Admin portal functional
- VPN client successfully tested
- All documentation created

## Your Setup Summary

| Component | Value |
|-----------|-------|
| Instance Name | Bashirat VPN server |
| Instance Type | t3.micro |
| Region | ap-southeast-2 (Sydney) |
| Public IP | 13.211.163.205 |
| Admin URL | https://13.211.163.205:943/admin/ |
| VPN Port | 443 (TCP) |
| Encryption | SECP384r1 + TLS 1.2+ |
| Status | ✅ Running & Verified |

---