# 🔐 Ex.No.1 – Evidence Acquisition Using AccessData FTK Imager

## 📌 Experiment Details

| Field | Details |
|---|---|
| **Course** | Digital Forensics Lab |
| **Experiment No.** | 1 |
| **Experiment Name** | Evidence Acquisition Using AccessData FTK Imager |
| **Academic Year** | 2024–2025 |

---

## 🎯 Aim

To acquire volatile and non-volatile digital evidence using
**AccessData FTK Imager** while maintaining the integrity of the
original evidence.

---

## 🛠️ Software Used

- AccessData FTK Imager
- Windows Operating System

---

## 📚 Types of Evidence Acquisition

FTK Imager can acquire two major types of evidence:

1. **Volatile Memory**
   - RAM
   - Pagefile

2. **Non-Volatile Memory**
   - Hard Disk
   - Partitions
   - Disk Images
   - Folder Contents
   - CDs/DVDs

---

# 💾 1. Acquiring Volatile Memory

Volatile memory acquisition collects the contents of the computer's
RAM for forensic analysis.

### Steps

1. Open **FTK Imager**.
2. Select **Capture Memory**.
3. Choose the destination folder.
4. Select required options:
   - Pagefile
   - AD1 file
5. Start the memory acquisition.
6. Wait until the acquisition is completed.
7. The acquired memory is saved with the `.mem` extension.

---

## 📄 Pagefile

The `pagefile.sys` file is used by Windows when the physical RAM
capacity is exceeded. It may contain valuable forensic information.

---

## 📦 AD1 File

AD1 is an FTK Imager image file that can be created for later forensic
analysis.

---

# 💽 2. Acquiring Non-Volatile Memory

FTK Imager can create a disk image of non-volatile evidence.

### Steps

1. Open **FTK Imager**.
2. Select **Create Disk Image**.
3. Select the required source.
4. Choose the source type.
5. Select the required drive.
6. Click **Finish**.
7. Enter the case details.
8. Select the destination folder.
9. Enter the image file name.
10. Select the image fragment size.
11. Enable **Verify images after they are created**.
12. Click **Start**.
13. Verify the generated hash values.

---

# 🔍 Disk Image Formats

| Format | Description |
|---|---|
| **Raw (DD)** | Common forensic image format without headers or metadata |
| **SMART** | Image format designed for Linux file systems |
| **E01** | Compressed forensic image format containing case information |
| **AFF** | Advanced Forensic Format designed to avoid proprietary limitations |

---

# 🗂️ Image Fragment Size

The **Image Fragment Size (MB)** option divides an image into multiple
files.

- Fragment size greater than `0` → Multiple image fragments
- Fragment size `0` → Single image file

---

# 🔐 Image Verification

The **Verify images after they are created** option verifies the hash
values after image creation.

This helps ensure the integrity of the acquired forensic evidence.

---

# 🔄 Workflow


Verify Hash Values
  ↓
Evidence Acquisition Completed
<img width="500" height="472" alt="Screenshot  2026-08-26 at 10 24 48 AM" src="https://github.com/user-attachments/assets/dba6ebbb-876e-44cf-bb45-143919e1d9ea" />
<img width="505" height="390" alt="Screenshot 2026-08-26 at 10 24 49 AM" src="https://github.com/user-attachments/assets/78b92b34-ac8b-42b4-b08b-d7f89e37caa0" />
<img width="1437" height="1094" alt="Screenshot  2026-08-26 at 10 43 45 AM" src="https://github.com/user-attachments/assets/e52923b4-9e6e-4a4a-953f-aa82f0e0c3a4" />
<img width="585" height="428" alt="Screenshot 2026-08-26 at 10 24 49 AM (1)" src="https://github.com/user-attachments/assets/878191a3-fe71-498c-b012-f9169c971013" />
<img width="575" height="426" alt="Screenshot  2026-08-26 at 10 24 50 AM" src="https://github.com/user-attachments/assets/0e7b7201-74b6-4da4-80bd-d5f840bc8428" />
<img width="395" height="347" alt="Screenshot  2026-08-26 at 10 24 50 AM (1)" src="https://github.com/user-attachments/assets/b7dddbaa-6ed7-4a70-bb92-91fae488e2ec" />
<img width="465" height="355" alt="Screenshot  2026-08-26 at 10 24 50 AM (2)" src="https://github.com/user-attachments/assets/e55e7901-d229-4124-bf22-4d285e5f8ad2" />
<img width="1313" height="1198" alt="Screenshot  2026-08-26 at 10 43 46 AM" src="https://github.com/user-attachments/assets/5f3d3865-3ba2-4e47-8574-383f7abb3ff4" />
<img width="470" height="355" alt="Screenshot  2026-08-26 at 10 24 52 AM" src="https://github.com/user-attachments/assets/092e8d93-4795-4c37-8c25-bb417484a3b9" />








