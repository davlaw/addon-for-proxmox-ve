# addon-for-proxmox-ve
Addon For Proxmox VE for extra management and quicker operation

## Extra Packages 
updated via 01-extra-packages.sh for easy management & troubleshooting
 - Git tool
 - MC File-Manager and Editor
 - VIM Editor
 - SSHFS to mount file-system over ssh for config-backups.
 - screen tool for background terminal session work
 - ethtool to check ethernet
 - iptraf for bandwidth and traffic monitoring
 - elinks for console browsing
 - net-tools, old style tools like ifconfig
 - php-cli, for easy and fast scripting tools
 - sendemail, a command line smtp sendemail
 - dos2unix, a command line tool to change MS-Windows/DOS copy paste content to Unix Format , i.e. without Ctrl-M char.
 - dnsutils, dig like too for DNS troubleshooting

## extra bash script and tools
updated via 02-update-bash-tools.sh For better console performance
- interactive shell like RHEL/CentOS
- rc.local setup , in case to work out something after bootup.
- vim config update for copy-paste via console , by disabling visual feature.
- Perl Cpan auto-commit for cpan use.
- SSH keeplive update to avoid quick disconnection

## locales setup to en_US.UTF-8
updated via 04-set-locales.sh in case you want en_US.UTF-8
- LC_TYPE
- LC_LANG
- LC_ALL



