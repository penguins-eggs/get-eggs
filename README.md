# Install eggs from the repository:

**Get-eggs**: The get-eggs script is designed to add the "penguins-eggs" package repository and configure it on Arch, Debian, Devuan, Ubuntu, or their derivatives. Here's a breakdown of what it does on different distributions:

**Arch:** The script will add the AUR (Arch User Repository) repository, which is referred to as "addaura" in the original naming. This allows you to install the "penguins-eggs" package from the AUR.

**Debian family:** On Debian-based distributions like Debian itself, Ubuntu, and their derivatives, the script will add a PPA (Personal Package Archive) for the "penguins-eggs" package. This enables you to install "penguins-eggs" using the package management system specific to that distribution.

On Arch, it will add an AUR repository - from that the original name [addaura](./documentation/NAMING.md) - on the Debian family, it will add a PPA for penguins-eggs.

To get a completely customized distro like Colibri, starting from an original ISO, read [HOWTO](./documentation/HOWTO.md).

# USAGE
The provided usage instructions explain how to use the get-eggs script. Here are the steps:
1. Clone the get-eggs repository by running the following command:
* `git clone https://github.com/pieroproietti/get-eggs`
2. Change into the cloned directory:
* `cd get-eggs`
3. Execute the script with root privileges by running the following command:
* `sudo chmod +x ./get-eggs.sh`  
* `sudo ./get-eggs.sh`
or
* `sudo bash get-eggs.sh`
4. Finally check and use it:
sudo eggs status

# Fork it!
This is a short and simple script, you are encouraged to fork the code and adapt it to your needs. The get-eggs script is designed to be short and simple, and you are encouraged to fork the code and adapt it to suit your specific needs. When you fork a repository, you create your own copy of the codebase that you can modify, enhance, or customize as per your requirements.

# Note
To create a naked Ubuntu I start from the server version, install it normally, and after I remove the packages cloud-install and needrestart.

#The note explains the process of creating a "naked" Ubuntu installation. Here are the steps involved:

Start with the server version of Ubuntu: Begin the installation process using the server version of Ubuntu. The server version typically provides a minimal installation without any graphical user interface (GUI). This allows for a more streamlined and customizable setup.

Perform a normal installation: Proceed with the installation process as you would with any regular Ubuntu installation. Follow the prompts, configure the necessary settings, and complete the installation.
Remove the packages cloud-install and needrestart: After the installation is complete, remove the packages named "cloud-install" and "needrestart" from the system. These packages may have been installed as part of the default installation but are not required for a "naked" Ubuntu setup.
By following these steps, you can create a "naked" Ubuntu installation that starts from the server version, goes through a standard installation process, and then removes the "cloud-install" and "needrestart" packages.
Remember to exercise caution when removing packages from your system, as it may affect the functionality or stability of your Ubuntu installation.
