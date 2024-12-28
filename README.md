# Pterodactyl-Installation-Update-Script-theme
✨All Major Operating Systems

Installation script:
`bash <(curl -sSL https://raw.githubusercontent.com/9fdxh42-koq/Pteroq-Manufacturing/refs/heads/main/install.sh)`

# custom hosting pages

| dark      | light     |
|------------|-------------|
| <img src="https://i.imgur.com/ZGNMlfN.png"> | <img src="https://i.imgur.com/a2FUPov.png"> |

`>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>> contact me  on discord healer#0001<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<`

What does this script do?
As the title says, it will install & upgrade the Pterodactyl Panel (https://pterodactyl.io) for you!

My goal is to make the script as configurable as possible, to support as many operating systems as possible and to use the latest software on the market. Right now it will install:

The Latest Panel and Wings(NextGen Daemon) Are recommended,
However you still have the option of using the old daemon and panel </br>
You also get 
The latest phpMyAdmin, and </br>
Fonix's themes

The script also uses the latest dependencies (MariaDB 10.4, PHP 7.3, NodeJS 10) for its installation.

To enhance the security of the installation, the script will also enable https, block unused ports and add IPtables rules to protect your server by default.

What operating systems are supported?
All major operating systems are supported!

This includes:

Ubuntu: 20.04, 18.04, 16.04
Debian: 10, 9
Fedora: 32, 31
CentOS: 8, 7
RHEL: 8
If you want any other OS, contact me and I might add them for a small price :love:

What installation options do I have?
You have the option to

Only install the panel
Only install the daemon
Install both the daemon and panel
Install the standalone SFTP server (after the daemon has been installed & configured)
Install phpMyAdmin (after the panel has been installed)
Install standalone database hosts (on nodes that don't have the panel installed)
You can also choose between Nginx and Apache2 as your web server.
Fonix theme options are also availble!

In case you forget your MariaDB root password, there is also an option to reset it.

What am I protected from?

SSH Bruteforce
Port Scanning
Bad/Suspicious Packets

What prerequisites do I need?
As the pterodactyl daemon requires docker, you will need a VPS with hardware virtualization or Dedicated Server if you want to install it. OpenVZ, LXC and Virtuozzo are not supported. Please consult with your host to see if their OpenVZ/LXC servers can run docker or not.

Supported Virtualizations:

KVM
Hyper-V
Xen-HVM
OpenVZ 7

The script will generate an SSL to secure both the daemon and panel, therefore you would need a domain to use it. You can get a free domain here: https://www.freenom.com/en/index.html?lang=en

# Supported Operating System
| Operating System  | Version | Supported            | Recommended        | Notes                                |
| ----------------- | ------- | -------------------- | ------------------ | ------------------------------------ |
| Ubuntu            | 20.04   | :heavy_check_mark:   | :heavy_check_mark: |                                      |
|                   | 18.04   | :heavy_check_mark:   | :heavy_check_mark: |                                      |
| Debian            | 10      | :heavy_check_mark:   | :heavy_check_mark: |                                      |
| CentOS            | Stream  | :heavy_check_mark:   | :heavy_check_mark: |                                      |
|                   | 8       | :heavy_check_mark:   | :heavy_check_mark: |                                      |
| RHEL              | 8       | :heavy_check_mark:   | :red_circle:       |                                      |
| Fedora            | 33      | :heavy_check_mark:   | :heavy_check_mark: |                                      |
|                   | 32      | :heavy_check_mark:   | :heavy_check_mark: |                                      |
