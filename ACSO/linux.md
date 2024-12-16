# Linux 
You'll need a Virtualization App. Recommended are [VirtualBox](https://www.virtualbox.org/wiki/Linux_Downloads), [VMWare Workstation](https://www.dropbox.com/scl/fi/bvjzkphurv3apw6i1arcd/VMware-Workstation-Full-17.6.1-24319023.x86_64.bundle?rlkey=hhu25h1wtzd4xuenof460znoo&st=fxtdsme5&dl=1), [Virtual Machine Manager](https://virt-manager.org/download.html)

### Windows Installation Instructions
1. Download the ISO.
2. Open the chosen Virtualization App.
3. Create a new VM, selecting the ISO and making sure the *Operating System* is set to Windows 10.
3.1. If you are using VirtualBox, please change the Unattended Install *Username and Password*. You can use *localhost* as a placeholder for **Hostname**.
4. Next, assign the VM *up to half* of your computer's RAM and CPU cores.
5. When selecting Hard Disk options, only ensure the size is at least 50 GB.
6. Verify all of the settings are correct and hit *Finish* to start the VM.
7. Hit any key to start the Windows Installation and follow the on-screen instructions.
8. Please Install *Guest Additions* in VirtualBox and *Spice Guest Tools* in VMM to make the experience better.
9. After Windows is installed, scroll down to *Post-Install guidelines*

# *Post-Install guidelines*
You will need to activate Windows:
1. Open a new PowerShell prompt.
2. Run `irm https://get.activated.win | iex` in the PS.
3. Tap *1* to go through HWID activation.

* To install VS, you can log into any chat platform in a browser on the VM, and use the links at the beginning of this message. I personally recommend VS 2019.
* * After launching the installer, you may need to press *Next / Continue* once before it actually starts.
* * When asked to select components, scroll down and select **Desktop development with C++**
