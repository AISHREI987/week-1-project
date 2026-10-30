# Week 1 – Cybersecurity Lab Setup
## Networkwalks Cybersecurity Program | Batch B0864

### Project Overview
This project documents the Week 1 lab setup for the Networkwalks Cybersecurity Program. The objective was to configure Kali Linux in Oracle VirtualBox and establish the required network and host-to-VM sharing settings.

### System Configuration

| Component | Configuration |
|---|---|
| Virtualization Software | Oracle VirtualBox |
| Attacking Machine | Kali Linux 2026.3 |
| Network Mode | NAT Network |
| NAT Network Name | NatNetwork |
| Network Subnet | `10.0.0.0/24` |
| Kali Linux IP Address | `10.0.0.2/24` |
| Default Gateway | `10.0.0.1` |
| DNS Servers | `10.0.0.1`, `8.8.8.8` |
| Shared Folder Name | `downloads` |
| Shared Folder Mount Point | `/downloads` |

### Tasks Completed

- Installed Oracle VirtualBox.
- Downloaded and configured Kali Linux 2026.3.
- Created a NAT Network named `NatNetwork`.
- Configured the NAT Network subnet as `10.0.0.0/24`.
- Assigned a static IP address to Kali Linux: `10.0.0.2/24`.
- Configured the default gateway and DNS.
- Verified internet connectivity.
- Enabled Shared Clipboard (Bidirectional).
- Enabled Drag and Drop (Bidirectional).
- Configured a shared folder between the host machine and Kali Linux.
- Verified access to the shared folder at `/downloads`.

### Network Verification

The following command was used to verify the Kali Linux IP configuration:

```bash
ip a
```

Internet connectivity was tested using:

```bash
ping google.com
```

Shared folder access was checked using:

```bash
ls /downloads
```

### Shared Folder Configuration

| Setting | Value |
|---|---|
| Folder Name | `downloads` |
| Mount Point | `/downloads` |
| Auto-mount | Enabled |
| Read-only | Disabled |

### Screenshots

Add your actual project screenshots in a folder named `Screenshots` and include them here.

Suggested screenshots:

1. VirtualBox NAT Network configuration.
2. Kali Linux IP address (`10.0.0.2/24`).
3. Internet connectivity test.
4. Shared folder configuration.
5. Shared folder contents.
6. VirtualBox snapshot (after creating it).

Example Markdown:

```markdown
![Kali IP Configuration](Screenshots/kali-ip.png)
```

### Learning Outcomes

- Learned to configure Kali Linux in VirtualBox.
- Understood NAT Network configuration.
- Practiced static IP configuration using NetworkManager.
- Verified internet connectivity.
- Configured host-to-VM file sharing.
- Enabled clipboard and drag-and-drop integration.

### Acknowledgement

Special thanks to **Waqas Karim (CCIE)** and the **Networkwalks Team** for their guidance and support throughout this learning process.

---

**Program:** Networkwalks Cybersecurity Program  
**Batch:** B0864  
**Week:** 01  
**Project:** WK1-PM1

