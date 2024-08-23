## Overview

I used the Chris Titus Tech Winutil tool to create a Microwin ISO file. This tool allows you to customize a legitimate Windows 11 ISO, removing unnecessary appx packages, configuring a local account, and implementing other tweaks. This is ideal for personal use or testing, though for Commercial or Enterprise environments, an unattended installation may be preferred.

The process was carried out on a Linux host, where I first created a standard Windows 11 virtual machine (VM) using a regular ISO, then proceeded to build and test the debloated Microwin VM. The customization has also been successfully tested on two separate laptops, demonstrating its versatility.

I will continue to use this setup in the future. The VM is configured with 4 vCPUs and 8GB of memory and is performing exceptionally well. It's great to have Windows running efficiently within a Linux environment.
## Resources

- [ChrisTitusTech/winutil: Chris Titus Tech's Windows Utility - Install Programs, Tweaks, Fixes, and Updates (github.com)](https://github.com/ChrisTitusTech/winutil)
- [Download Windows 11 (microsoft.com)](https://www.microsoft.com/software-download/windows11)
- [Finishing Microwin (youtube.com)](https://www.youtube.com/watch?v=dasD8fLcMWE&t=7079s)
## What You Will Need

- A Windows or Linux machine to create the images
- Microwin ISO (to be created)
- Windows 11 ISO (official download)
- Chris Titus Tech Winutil tool
- A storage location for the ISOs and VMs (e.g., NAS or external drive)

### Step-by-Step Guide to Creating the Microwin ISO

1. **Download the Windows 11 ISO:**
   - Visit the official Microsoft website to download the latest Windows 11 ISO [here](https://www.microsoft.com/software-download/windows11).
   
2. **Run the Chris Titus Tech Winutil Tool:**
   - Clone or download the Winutil repository from [GitHub](https://github.com/ChrisTitusTech/winutil).
   - Follow the installation instructions provided on the repository page to run the tool on your Windows VM.

3. **Select Microwin Options:**
   - Open the Winutil tool and navigate to the Microwin customization options.
   - Choose the features you want to remove or retain, such as appx packages, telemetry services, and pre-installed applications.
   - Configure the system to create a local account during setup.

4. **Create the Microwin ISO:**
   - After selecting your customization options, initiate the process to create the Microwin ISO.
   - The tool will modify the Windows 11 ISO based on your selections and output a new, customized ISO file.

5. **Test the Microwin ISO:**
   - Use the newly created ISO to install Windows in a VM or on a physical machine.
   - Verify that the system boots correctly and that all customizations have been applied as intended.

### Post-Setup Steps

6. **Apply Windows Updates:**
   - After installation, connect to the internet and apply the latest Windows updates to ensure your system is secure and up-to-date.

7. **Open Winutil (shortcut created by Microwin):**
   - Access Winutil from the desktop or start menu. The tool should be pre-installed as part of the Microwin setup.

8. **Apply Winutil Apps:**
   - Use the Winutil tool to install any additional applications or utilities you may need. This could include productivity tools, system utilities, or any other software.

9. **Apply Winutil Tweaks:**
   - Finally, apply any additional tweaks offered by Winutil. These could include performance enhancements, privacy adjustments, or visual customizations.

By following these steps, you should have a streamlined and efficient Windows 11 setup that is well-suited for testing or personal use within a VM or physical hardware environment.
