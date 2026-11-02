# Screenshot Evidence Folder

Save genuine screenshots from your own virtual machines in this folder.
Do not create or alter terminal output to make a failed test appear
successful.

Suggested evidence filenames:

1.  `01_vm_settings.png` - VM name, CPU, RAM, storage, and network mode.
2.  `02_ubuntu_storage.png` - installer storage summary or documented
    partition layout.
3.  `03_login.png` - successful console login.
4.  `04_hostname.png` - `hostname` command and output.
5.  `05_ip_addr.png` - relevant network interface and assigned IP
    address.
6.  `06_ping_google.png` - `ping -c 4 google.com` output, or a
    documented failure if ICMP is blocked.
7.  `07_apt_update_upgrade.png` - package update and upgrade output.
8.  `08_ssh_status.png` - `systemctl status ssh` showing the actual
    service state.
9.  `09_windows_server_install.png` - Windows Server Evaluation
    installation screen.
10. `10_windows_server_login.png` - successful Windows Server login.

Capture readable evidence with the command and result visible. Do not
include passwords, private keys, recovery codes, or other secrets.
Update `README.md` and the result tables to match the actual evidence.
