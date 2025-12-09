### 2. Installing and Booting Linux
![Picture of a USB drive being plugged into a computer](https://images.pexels.com/photos/20123833/pexels-photo-20123833.jpeg?cs=srgb&dl=pexels-stitch-20123833.jpg&fm=jpg)
This section includes a step-by-step guide on how to install Linux Ubuntu. You will learn how to flash an OS to a USB Drive, how to select a boot drive, and Linux set up instructions. Please read the warnings about installing a new OS for the first time.

!!! warning
    - **File loss**:
        When installing a new OS, all existing data on your computer is overwritten by the new OS. If you have any important files on your computer, be sure to back up everything on something like an external drive or the cloud.
    - **App Compatibility**:
        There are many apps compatible with Windows that aren't compatible with Linux. If there are apps that you absolutely need on Linux, be sure to research their compatibility.
    - **Driver Compatibility**:
        Linux almost always has open source drivers compatible with your hardware, but sometimes less essential hardware like certain WiFi cards or Bluetooth don't have support. Be sure to check if you're worried about more niche hardware.

#### 2.1 Flashing Linux to a USB Drive
**Make sure to have your USB drive plugged into your computer.** In this section you will download Ubuntu and an OS flasher, and use the flasher to make your USB drive into an Ubuntu bootdrive.

1. Visit https://ubuntu.com/desktop.
2. Click **Download Ubuntu Desktop** in the left corner of the screen and wait for the download to complete. (you can ignore the newletter sign up)
3. Visit https://etcher.balena.io/.
4. Click **Download Etcher** in the middle of the screen and wait for the download to complete.
5. Click on the .exe file for etcher to open the flashing application.
6. Click the **Flash from File** button, and select the Ubuntu download from earlier.
7. Click **Select a Drive**, and select your USB drive. Press select.
8. Press **Flash** and wait for the OS to flash to your drive.

#### 2.2 Selecting a Boot Drive
**Make sure your boot drive is plugged in.** In this section you will learn how to enter your computer's BIOS to select your Ubuntu bootdrive to reboot your computer in Ubuntu.
- Each computer has a key that boots them into its BIOS. This key is dictated by either the brand of your computer or your motherboard manufacturer if your computer doesn't have a brand. For most computers the BIOS button is either ``F2``, ``F10``, ``esc``, or ``delete``.

1. Shut down your computer.
2. Power on your computer and rapidly press your BIOS key. (common BIOS keys listed above)
!!! info
    Each computer's BIOS is different, if you are having trouble finding your boot order settings, please reference the BIOS information for your computer or motherboard's brand online.
3. Navigate to your **Boot Order** configuration. (Will usually be under a tab or section titled **Boot**)
4. Select your boot drive as first priority.
5. Reboot your computer. Your boot drive's grub menu should appear.
6. Using the arrow keys, navigate to **Try or Install Ubuntu** if not already selected, and press enter.
7. Wait for Ubuntu to boot up.

#### 2.2 Installer Prompts
Most of the installer prompts are straight forward for an experienced Windows user. In this section we will only go over installer prompts that are important or confusing, in the order they appear. All other prompts don't matter or are preference based.

1. Connect to the internet
    - It's not necessary, but we reccomend connecting to the internet so Ubuntu can automatically install drivers for your hardware. This will save you time after the installation completes.

!!! warning
    By selecting **install Ubuntu** in the next installer prompt, your Windows OS and all its files will be permanently deleted.
2. What do you want to do with Ubuntu?
    - Ubuntu gives you the option to install or try Ubuntu. If you are unsure about Ubuntu, select **Try Ubuntu** and then install later when you're ready. Note that it will run slow on try Ubuntu, since the OS is operating off your boot drive rather than your computer.
3. What apps would you like to install to start with?
    - As a Windows user, many of your essential office apps come with your installation. Because of this, we reccomend choosing **Extended selection**, which will install a few helpful office apps and utilities with your installation.
4. Install reccommended proprietary software?
    - Check both of these boxes. This will install open source drivers compatible with your hardware. 
5. How do you want to install Ubuntu?
    - Select **Erase disk and install Ubuntu**.
6. At the last prompt window, press **Install** and then in the next window **Restart Now**. Wait for the installation to finish and Ubuntu to boot back up.
7. Navigate through the final installer prompts, the choices aren't important.
