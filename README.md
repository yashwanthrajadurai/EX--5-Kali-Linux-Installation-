# Installing Kali Linux on VirtualBox

## Objective:
Install and configure Kali Linux in Oracle VM VirtualBox.

## Pre-requisites:
- A system with Oracle VM VirtualBox installed.
- At least 4 GB RAM and 20 GB free disk space.
- Kali Linux ISO image, which can be downloaded from the official website.

---

## Step-by-Step Installation Guide:

### Step 1: Download Kali Linux ISO
1. Go to the [Kali Linux download page](https://www.kali.org/downloads/).
2. Download the Kali Linux ISO file.
   - Choose between **32-bit** or **64-bit** depending on your system (most systems are 64-bit).
   - Download the **Installer version** for a full installation.

---

### Step 2: Open Oracle VM VirtualBox
1. Launch VirtualBox on your computer.

![image](https://github.com/user-attachments/assets/c4f19c7f-4ac7-44b3-a36a-d3106b7f3449)


---

### Step 3: Create a New Virtual Machine
1. In VirtualBox, click on the **New** button to create a new virtual machine.
2. Name and Type Settings:
   - **Name**: Give a name like "Kali Linux".
   - **Type**: Select **Linux**.
   - **Version**: Select **Debian (64-bit)** or **Debian (32-bit)** depending on the ISO version you downloaded.
3. Click **Next** to proceed.

---

### Step 4: Allocate Memory (RAM)
1. Choose how much RAM to allocate to your virtual machine.
   - Recommended: At least 2 GB (2048 MB) for Kali Linux, or 4 GB if possible.
2. Click **Next**.

---

### Step 5: Create a Virtual Hard Disk
1. Select **Create a virtual hard disk now**.
2. Click **Create**.

---

### Step 6: Select Hard Disk File Type
1. Choose **VDI (VirtualBox Disk Image)**.
2. Click **Next**.

---

### Step 7: Storage on Physical Hard Disk
1. Select **Dynamically allocated** (so the disk will grow as needed).
2. Click **Next**.

---

### Step 8: Allocate Storage Space
1. Set the hard disk size. Kali Linux requires at least 20 GB of storage.
   - You can increase this if you plan to install many additional tools later.
2. Click **Create**.

---

### Step 9: Configure Kali Linux ISO
1. Select the VM from the list in VirtualBox and click **Settings**.
2. Navigate to **Storage** from the side menu.
3. Under **Controller: IDE**, click the **Empty** CD icon.
4. On the right, click the **CD** icon next to **Optical Drive** and choose **Choose a disk file...**.
5. Locate and select the Kali Linux ISO you downloaded.
6. Click **OK**.

---

### Step 10: Start the Virtual Machine
1. In VirtualBox, click **Start** to boot up your Kali Linux virtual machine.

![image](https://github.com/user-attachments/assets/a9e0eb66-b872-4bc5-b4cc-fb6f1ae33c57)


---

### Step 11: Begin Kali Linux Installation
1. The VM will now boot from the ISO. You’ll see a boot menu.
   - Select **Graphical Install** and press **Enter**.

![image](https://github.com/user-attachments/assets/78e3d1cd-0555-433c-be26-008f79b590a0)


---

### Step 12: Select Language and Region
1. Choose your language, location, and keyboard layout.
   - These can be configured to your preference.
2. Click **Continue** after each selection.

---

### Step 13: Configure the Network
1. You’ll be prompted to configure the network.
   - Enter a **hostname** for your system (e.g., kali).
   - You can leave the **domain name** empty if you don’t need to set up a domain.

---

### Step 14: Set Up Users and Passwords
1. Create a **root password** for the administrator account.
   - Choose a strong password and re-enter it for confirmation.

---

### Step 15: Partition Disks
1. Choose **Guided - use entire disk** for simplicity (recommended for beginners).
2. Select the virtual disk you created earlier.
3. Choose **All files in one partition**.
4. Finish partitioning and confirm to write the changes to disk.

---

### Step 16: Install the System
1. The installer will now copy files and install Kali Linux. This may take several minutes.

---

### Step 17: Install GRUB Bootloader
1. When prompted to install the GRUB bootloader, choose **Yes**.
2. Select the virtual hard disk as the location to install GRUB.

---

### Step 18: Complete Installation
1. After the installation is complete, click **Continue** to reboot the virtual machine.

---

### Step 19: Login to Kali Linux
1. Once the machine reboots, you’ll be presented with a login screen.
2. Log in using the **root account** and the password you set earlier.


![image](https://github.com/user-attachments/assets/2cb7bacb-b34d-46b8-b97a-489c2fb78d75)

---

## Result:

   Kali linux has been successfully installed in the virtualbox.

