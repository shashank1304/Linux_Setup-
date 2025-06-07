# Linux_Setup
# 🐧 Kali Linux Setup on Windows using VirtualBox

This guide provides step-by-step instructions to install and set up **Kali Linux** on a **Windows** system using **Oracle VirtualBox**. Perfect for beginners in cybersecurity or anyone wanting a safe Linux testing environment.

---

## 📋 Prerequisites

- Windows 10/11 system with administrative privileges
- Stable internet connection
- Minimum 4 GB RAM (8 GB recommended)
- 7-Zip File Manager (for extracting compressed files)

---

## 🚀 Setup Steps

### ✅ Step 1: Download Required Tools

1. **VirtualBox**:  
   [https://www.virtualbox.org](https://www.virtualbox.org)

2. **7-Zip File Manager**:  
   [https://www.7-zip.org](https://www.7-zip.org)

3. **Kali Linux VirtualBox Image**:  
   Go to [https://www.kali.org/get-kali/](https://www.kali.org/get-kali/)  
   ➤ Select **Virtual Machines**  
   ➤ Download the **VirtualBox** image

---

### 💾 Step 2: Install Software

1. Run the downloaded **VirtualBox installer** and complete the setup.
2. Install **7-Zip** for extracting `.7z` files.
3. Use 7-Zip to extract the downloaded **Kali Linux .7z** archive.

---

### 🛠️ Step 3: Import Kali Linux into VirtualBox

1. Launch **VirtualBox Manager**.
2. Go to `File > Import Appliance`.
3. Browse and select the extracted `.ova` file.
4. Click **Next**, then **Import**.

---

### ▶️ Step 4: Start Kali Linux

1. After importing, select the Kali VM in VirtualBox.
2. Click **Start**.
3. When prompted, enter:
   - **Username**: `kali`  
   - **Password**: `kali`

---

## ✅ Post-Setup (Recommended)

- Run updates:
  ```bash
  sudo apt update && sudo apt upgrade -y
