# macOS

* [Windows 11 IoT Enterprise LTSC **ARM64**](https://drive.massgrave.dev/en-us_windows_11_iot_enterprise_ltsc_2024_arm64_dvd_ec517836.iso)
* [Parallels Desktop 19](https://www.dropbox.com/scl/fi/8z9k4ls8tb0fip0d9uxy4/Parallels-Desktop-19.zip?rlkey=zqerof8lbktd6eqm41y9sv687&st=8xz973ue&dl=0)

-# ARM64 Windows has a builtin compatibility layer for x86/x64 apps.

## Start up your computer in macOS Recovery  
1. On your Mac, choose :apple: menu  > *Shut Down*.  
2. Wait for your Mac to shut down completely.  
3. Press and hold the power button on your Mac until the system volume and the Options button appear.  
4. Click the Options button, then click Continue.  
5. If asked, select a volume to recover, then click Next.  
6. Select an administrator account, then click Next.  
7. Enter the password for the administrator account, then click Continue.  
8. Wait until the Recovery app appears in the *Menu bar*.  

## Disable SIP (System Integrity Protection) ¹
1. Open *Utilies Menu > Terminal*.  
2. Run `csrutil disable`.
3. After it's successful, restart the computer.

## Installing Parallels
1. Unpack the archive, open the DMG file and drag it into the Applications folder.
2. From the *Crack* folder, run *Install_Patch.command* and then *Launch_Parallels.command*
• You'll be using *Launch_Parallels.command* to launch Parallels from now on.

## Installing Windows:

1. Launch Parallels Desktop as specified above and choose *File > New*.
2. Prepare your ISO and click *Install Windows or another OS from a DVD or image file*.
3. When prompted, select the ISO and if you want Parallels Desktop to install Windows automatically, click Continue and proceed with step 4.
•  If you want to install Windows manually, select *Install operating system manually* in the left bottom corner of the window, click *Continue*, and jump to step 5.
4. Skip the License Key input – we'll pirate it after installation – and from the *Edition* dropdown, select **Windows 11 IoT Enterprise LTSC**.
5. Choose *Development* or similar when asked what you'll use the VM for.
6. If you want to pre-set things like how much memory Windows uses or whether it starts automatically when you open Parallels Desktop, select *Customize settings before installation*. You can also adjust these settings after the operating system is installed.
7. Click Create and wait for the Assistant to install Windows.

:warning: The first time you start Windows, *Parallels Tools* are installed to allow seamless operation between Windows and macOS. Once they are installed, you're prompted to restart Windows.

:information_source: When you install Windows, Parallels Desktop creates an administrator account with a blank password. Once the installation is complete, it is recommended that you change this password.

## Once finished, 
Go to [this message](https://discord.com/channels/1265665660755640444/1265669018212241469/1310203871423107142), choose a Visual Studio version and scroll to **Post-Install Guidelines**

-# ¹ Disabling SIP is not recommended in general, but we need to do this to run the crack
