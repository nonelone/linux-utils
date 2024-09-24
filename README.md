# Linux-utils
### A set of simple utilities to help with troubleshooting, aimed at new users
This repository currently contains:

 - catcord: utility that formats output of commands and copies it to the clipboard to easily share logs on discord
 - installer: a small script that adds utilities to the PATH

All scripts are written in **bash** and should work out of the box on most distributions.

## Usage
1. Navigate to directory that you want the utilities to be installed (for examle .local/bin)
2. Clone the repository with `git clone https://github.com/nonelone/linux-utils`
3. Add execution permission for the installer script with `chmod +x installer`
4. Run the installer script with `./installer`

After that, the install folder containing all the utilities will be added to path and after refreshing the Shell - for example by opening a new terminal window - will be avaliable to use across your system.
