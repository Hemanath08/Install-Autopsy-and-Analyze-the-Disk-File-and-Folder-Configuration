# Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration
## AIM:
To install Autopsy on Kali Linux and analyze disk images, files, and folder configurations for digital forensic purposes.

# DESIGN STEPS:
# Step 1: Install VirtualBox
🔗
Installation Steps:
1.Download the Windows hosts .exe file from the official VirtualBox website.
2.Run the installer and follow the on-screen instructions.
3.Once installed, launch VirtualBox to verify the installation.

# Step 2: Install Kali Linux on VirtualBox
🔗 Download Kali Linux VM: Click Here

Installation Steps:
1.Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).
2.Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM.
3.Go to Settings > Storage, click Empty under Controller: IDE.
4.Select Graphical Install, follow the prompts to set language, location, username, and password.
5.Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.

# Step 3: Install Autopsy (GUI-based Forensic Tool)
🔗 Download Autopsy: Click Here

Installation Steps:
Download the Autopsy Windows Installer from the official website.
Extract the ZIP file and open the bin folder.
Run autopsy.exe and set up a new forensic case for analysis.

# Step 4: Install Sleuth Kit (CLI-based Forensic Tools)
🔗 Download Sleuth Kit: Click Here

Installation Steps:
1.Download the Windows ZIP package from the official website.
2.Extract the ZIP folder and move it to a suitable directory (e.g., C:\sleuthkit).
3.Add the bin folder to Windows PATH:
4.Open Control Panel → System → Advanced System Settings.
5.Click Environment Variables → Edit Path.
6.Add the Sleuth Kit bin folder path and save changes.
7.Verify installation by running:
```
fls -version
```
# Step 5: Create & Configure a Virtual Hard Disk (VHD) in Windows
1.Press Win + X, Select Disk Management.
2.Click Action > Create VHD.
3.Choose a location and set a disk size (e.g., 10GB+).
4.Select Fixed Size or Dynamically Expanding and click OK.
5.In Disk Management, find your new disk (marked as "Not Initialized") -> Right-click the new disk → Initialize Disk → Select MBR.
6.Right-click Unallocated Space → New Simple Volume → Format the disk -> Click next → Finish.

## OUTPUT:
## VIRTUAL BOX:

![Screenshot 2025-04-25 090257](https://github.com/user-attachments/assets/d991fb24-c8d9-4ae7-ab53-0461ff515377)

## VIRTUAL MACHIN(KALI LINUX):

![Screenshot 2025-04-25 090849](https://github.com/user-attachments/assets/b6783b5a-110d-4295-9947-a88b98e53332)

## AUTOPSY:

![Screenshot 2025-04-25 090938](https://github.com/user-attachments/assets/d2be5693-ff2b-4c52-8c35-382ccae92138)

## SLEUTH KIT:

![WhatsApp Image 2025-04-25 at 03 44 29_788b2086](https://github.com/user-attachments/assets/3b1a068c-aa6b-41a8-9d1f-766e135da179)

## Creation of virtual hard disk:

![Screenshot 2025-04-25 085204](https://github.com/user-attachments/assets/5227bc71-083b-47fc-9cb3-ad201505759c)

## OS Account:
![Screenshot 2025-04-25 100050](https://github.com/user-attachments/assets/559c5cdb-de9c-4d6f-bb71-8b4db4026e12)

## Generate Report:
![Screenshot 2025-04-25 100139](https://github.com/user-attachments/assets/0fc02744-7cba-4f4c-bcda-28fe4c9d2c86)

![Screenshot 2025-04-25 100147](https://github.com/user-attachments/assets/fcc3d2bd-368a-41f6-af81-dced31871585)

![Screenshot 2025-04-25 100156](https://github.com/user-attachments/assets/96177be8-ba76-4a29-8fbc-354d37549b74)

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
