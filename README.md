# Ex. No: 6 – Use Sleuth Kit to Analyze Digital Evidence

## Description

The Sleuth Kit (TSK) is a collection of command-line tools that allow you to analyze disk images and recover digital evidence. Here's a step-by-step guide to using Sleuth Kit on a Windows machine to analyze digital evidence.

---

# Step 1: Install Sleuth Kit

## 1. Download Sleuth Kit

- Visit the official Sleuth Kit website or the provided Google Drive link:
  
  https://drive.google.com/drive/u/1/folders/1iISFY7Tqn2L7AjQGhg8yJ8kixc_xTU-v

- Download the latest version for Windows.

## 2. Install Sleuth Kit

- Run the installer and follow the instructions to install Sleuth Kit on your Windows machine.
<img width="602" height="244" alt="image" src="https://github.com/user-attachments/assets/857a15ee-caf3-4f2f-b305-11c6a3a89fd1" />

The downloaded Sleuth Kit directory contains folders and files such as:

- `bin`
- `lib`
- `licenses`
- `README`
- `README-win32`

---

# Step 2: Acquire the Disk Image

Before analysis, you need a disk image of the evidence. This can be an image of a hard drive, memory card, or any other storage device.


## 1. Create Disk Image

- Use a tool like **FTK Imager** or `dd` to create a bit-by-bit copy of the storage device.
- Ensure the image is in a format supported by Sleuth Kit, such as:
  - `.dd`
  - `.raw`
  - `.img`
  - `.E01`

### Download the Required Evidence Files

Download the following files from the provided Google Drive:

1. `4Dell Latitude CPi.E01`
2.  <img width="602" height="70" alt="image" src="https://github.com/user-attachments/assets/f477e528-55dd-46ad-8673-60885117bece" />

3. `4Dell Latitude CPi.E02`

The disk image files are stored in the Downloads directory.

---

# Step 3: Mount the Disk Image (Optional)

Mounting the disk image makes it easier to analyze the file system.

## 1. Mount the Image

- You can use a tool like **OSFMount** to mount the image as a virtual drive on your Windows system.
- This step is optional but helps with navigating the file system easily.

---

# Step 4: Analyze the File System

Use Sleuth Kit tools to analyze the file system and locate evidence.
<img width="602" height="142" alt="image" src="https://github.com/user-attachments/assets/854af927-6f2a-4094-bccc-b8ed75839eea" />

## 1. Navigate to the Sleuth Kit Directory

- Open the **Command Prompt**.
- Navigate to the directory where Sleuth Kit is installed.
<img width="601" height="205" alt="image" src="https://github.com/user-attachments/assets/d46a71c0-38ef-4d94-bff0-b8fbdfc54056" />

Example:

```cmd
cd C:\Users\chaithu\Downloads\sleuthkit-4.14.0-win32\sleuthkit-4.14.0-win32\bin


