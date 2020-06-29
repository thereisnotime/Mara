# Mara Windows

### Description ###
Windows distribution for penetration testing that can be booted in live mode (in RAM). Will contain most of the tools from Kali, Parrot, Paladin OS, Tails, BlackArch, Blackbox and Commando VM with additional custom tools/scripts and more.

* NOTE: This is project is WIP. Initial version will be uploaded when all of the basic features from the todo are done. You can contact me if you want to participate in the development/testing process.
 
### Inspiration ###
All current supported penetration testing distributions, be Linux or Windows based are lacking sufficient tooling for Cloud and AD penetration testing/assesment/reconnaissance/auditing. The goal of project Mara is to cover all the paradigms of the other distributions and also provide new features on top of that. A lot of tools on other distributions are redundant and do not need to cause clutter, this will be optimized in Mara. There ae really nice new scripts/tools that are missing from other distributions but can brin a lot of value for red teams.

### Roadmap ###
1. Create a basic PoC iso for live bootable WinPE environment.
2. Add support for VM booting and generic drivers for different hardware.
3. Integrate most common languages, redistributables, package and version managers for wider range of software support.
4. Integrate the most used scripts and binaries used tools for red teaming.
5. Integrate custom scripts and binaries for red teaming.
6. Integrate clients for different services/protocols/servers.
7. Separate the iso per flavors for different purposes - TBD (privacy and anonymity, offensive security, digital forensics and data recovery).

### Todo v1.0 ###
- [x] Support for legacy boot from ISO file.
- [x] Load everything in RAM for better performance (requires more RAM).
- [x] Load only the main modules in RAM (less performance).
- [x] Integrate ADSL/PPPoE/Dialup/Ethernet/Generic Wi-Fi drivers and software for wide range of network support.
- [x] Integrate tools to be able to reset/change credentials of local users in Windows installations.
- [X] Integrate keyboard layout switcher.
- [X] Integrate generic drivers for USB HWPnP, PnpUtil etc.
- [X] Integrate resolution switcher for generic monitors.
- [X] Integrate a stable PDF reader.
- [X] Integrate a 2FA authorization software.
- [X] Integrate browser: Firefox.
- [X] Integrate Windows steps recorder.
- [X] Integrate advanced partition manager.
- [X] Intgrate 7Zip for all archival needs.
- [X] Integrate Explorer++.
- [X] Integrate DISM++ and SFC.
- [X] Integrate EasyMBR2GPT.
- [X] Integrate PowerShell.
- [X] Integrate ease of access tools.
- [X] Integrate HDClone.
- [X] Integrate Agent Ransack for fast search.
- [X] Integrate WinNTSetup.
- [X] Integrate PE Network Manager.
- [X] Integrate browser: Firefox.
- [X] Integrate KeyStore Explorer for all certificate/keys related purposes.
- [ ] Integrate browser: Chrome.
- [ ] Integrate Java version and package managers.
- [ ] Integrate Node version and package managers.
- [ ] Integrate Python version and package managers.
- [ ] Integrate Go version and package managers.
- [ ] Integrate Rust version and package managers.
- [ ] Integrate RDP/SSH/X/VNC clients.
- [ ] Integrate PowerShell Core.
- [ ] Integrate Git and Git Bash.
- [ ] Integrate FTP/SFTP/FTPS/S3/Azure clients.
- [ ] Integrate remote access clients (TeamViewer/LogMeIn/Ammy etc.).
- [ ] Support for UEFI/GPT boot.
- [ ] Options in the boot menu to select boot type and add parameters.
- [ ] Add a lot more missing todos from the Trello board.

### Screenshots ###
![Screenshot1](/Screenshots/Screenshot_1.png?raw=true "Boot in VMWare Workstation.")
![Screenshot2](/Screenshots/Screenshot_2.png?raw=true "Boot menu.")
![Screenshot3](/Screenshots/Screenshot_3.png?raw=true "Boot in Oracle Virtualbox.")

### Installation ###
Standard iso burning or copying with Rufus, Easy2Boot or your favorite tool.

### Requirements ###
Too soon to give details. Currently 2GB of RAM is a must, but I am working on solving this.

### Compatability ###
Legacy boot.
UEFI boot.
