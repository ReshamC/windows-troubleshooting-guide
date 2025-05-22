
# 🪟 Windows Troubleshooting Guide

This is a quick-reference guide I created based on my hands-on experience in IT Support, especially during my internship at **Data Vision Australia**.

It includes steps to resolve common Windows issues and useful commands/scripts for daily support tasks.

---

## 🔧 Common Issues & Fixes

### 1. PC is Slow
- Check Task Manager for high-usage apps
- Clear temporary files:  
  `Win + R → %temp% → Delete all`
- Run Disk Cleanup & Defragmentation

### 2. Internet Not Working
- Run `ipconfig /release` and `ipconfig /renew`
- Reset DNS:  
  `ipconfig /flushdns`
- Check Ethernet/Wi-Fi drivers in Device Manager

### 3. Windows Update Fails
- Use `sfc /scannow` in Command Prompt
- Restart Windows Update Service:
