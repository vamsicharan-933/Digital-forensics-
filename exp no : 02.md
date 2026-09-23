# Experiment No. 2: Recover Deleted or Damaged Files Using TestDisk

## Aim

To recover a deleted or missing partition and restore access to the files using TestDisk.

## Software Used

- TestDisk 7.3-WIP
- Windows Operating System
- USB Pendrive
- NTFS File System

## Introduction

TestDisk is a free and open-source data recovery utility used to recover lost partitions, repair damaged partition structures, and restore access to files from storage devices.

In this experiment, a 4 GB partition named `Testing` was created on a USB pendrive. The partition was deleted to simulate data loss. TestDisk was then used to analyse the USB pendrive, locate the deleted partition, verify the files stored in it, and restore the partition structure.

## Procedure

### Step 1: Open TestDisk

Open `testdisk_win.exe` with administrator privileges.

TestDisk displays information about the data recovery utility and provides options for creating or appending a log file.

Select:

`Create`

and press **Enter** to create a new log file.
<img width="1523" height="1032" alt="screenshot" src="https://github.com/user-attachments/assets/d833891c-611a-484d-9b58-cad2fcce62ee" />



**Observation:** TestDisk was successfully started and the option to create a new log file was selected.

---

### Step 2: Select the USB Pendrive

TestDisk displays all detected physical storage devices.

The USB pendrive was identified as:

- PhysicalDrive1
- 125 GB / 117 GiB
- USB DISK 2.0

Select the USB pendrive and choose:

`Proceed`

<img width="1564" height="1006" alt="screenshot" src="https://github.com/user-attachments/assets/cd42f0e4-bcff-48e4-abcc-cec9151c5a94" />



**Observation:** The 117 GB USB pendrive was correctly identified and selected for the recovery process.

---

### Step 3: Analyse the Disk

After selecting the USB pendrive, TestDisk displays the main menu.

The available options include:

- Analyse
- Advanced
- Geometry
- Options
- MBR Code
- Delete
- Quit

Select:

`Analyse`

to analyse the current partition structure and search for lost partitions.

<img width="1560" height="1008" alt="nbbvv" src="https://github.com/user-attachments/assets/e5af179c-9cee-484b-b806-b41478fbc825" />

**Observation:** The Analyse option was selected to search for the deleted partition.

---

### Step 4: Perform Quick Search

TestDisk displays the current partition structure of the USB pendrive.

The existing `SARATH'S` partition is displayed.

Select:

`Quick Search`

and press **Enter**.

<img width="1546" height="1017" alt="screenshot Image 2026-09-23 at 10 24 47 PM" src="https://github.com/user-attachments/assets/a333126d-a79a-445f-b798-4a41ffb635e4" />



**Observation:** TestDisk started searching for lost or deleted partitions.

---

### Step 5: Verify the Deleted Partition

TestDisk detects the deleted `Testing` partition.

Select the `Testing` partition and press:

`P`

The `P` option is used to list the files stored in the selected partition.

<img width="1545" height="1018" alt="screenshot Image 2026-09-23 at 10 37 27 PM" src="https://github.com/user-attachments/assets/21e284bf-e804-4918-86f5-083ccb289b63" />



**Observation:** TestDisk successfully displayed the files from the deleted `Testing` partition. The displayed files included images and screenshots that were previously stored in the partition.

Examples of detected files include:

- `1.jpg`
- `2345.jpg`
- `Screenshot 2026-09-07 203856.png`
- `WIN_20250914_21_21_06_Pro.jpg`
- `WIN_20251207_20_53_37_Pro.jpg`
- `WIN_20251208_13_29_03_Pro.jpg`

This confirms that the deleted partition and its file system data were successfully detected.

Press `q` to return to the partition list.

---

### Step 6: Confirm the Recovered Partition

After returning to the partition list, TestDisk displays both the deleted `Testing` partition and the existing `SARATH'S` partition.

The detected partition structure is:

- `Testing` – approximately 4 GB
- `SARATH'S` – approximately 113 GB

The screen displays:

`Structure: Ok.`

<img width="1559" height="1009" alt="screenshot Image 2026-09-23 at 10 24 48 PM" src="https://github.com/user-attachments/assets/d814380b-4ebf-43c9-9012-c18c23a88e2a" />


**Observation:** The deleted `Testing` partition was successfully detected and the partition structure was reported as OK.

Press **Enter** to continue.

---

### Step 7: Write the Recovered Partition Structure

TestDisk provides the:

`Write`

option to save the detected partition structure to the USB pendrive.

<img width="1543" height="1019" alt="screenshot Image 2026-09-23 at 10 24 53 PM" src="https://github.com/user-attachments/assets/4f7c5962-5395-4f78-b642-0aaf8b5871fe" />



Select:

`Write`

and press **Enter**.

Confirm the operation when TestDisk asks for confirmation.

**Observation:** The recovered partition structure was selected to be written back to the USB pendrive.

---

## Result

The deleted 4 GB `Testing` partition was successfully detected using TestDisk. The files stored in the deleted partition were successfully displayed using the `P` option, confirming that the partition data was recoverable.

The recovered partition structure was then selected using the `Write` option.

## Conclusion

The experiment successfully demonstrated the recovery of a deleted partition using TestDisk. The USB pendrive was analysed, the deleted `Testing` partition was located using Quick Search, the files were verified using the `P` option, and the recovered partition structure was selected for writing back to the storage device.
