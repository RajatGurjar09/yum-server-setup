yum-server-setup
Local YUM server setup using FTP and createrepo on CentOS

Local YUM Server Setup using FTP

- OS: CentOS/RHEL
- Server: vsftpd
- Tools: createrepo, mount ISO

Steps:
1. Mounted CentOS ISO to /mnt
2. Created repo using createrepo
3. Installed vsftpd and configured anonymous FTP access
4. Client system configured to use this repo

Result:
- Successfully installed packages on client without internet

