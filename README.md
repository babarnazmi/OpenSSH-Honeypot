OpenSSH-Honeypot
================

Windows based OpenSSH Honeypot (for logging password attempts)



  * Just Install WinSSH setup from this project : https://github.com/babarnazmi/WinSSH
  * Download sshd.exe from downloads of this project and replace it with original in "/usr/sbin/sshd.exe" ("c:\program files\OpenSSH\usr\sbin\")
  * Restart "OpenSSH Server" service (From Services or from command : net stop "OpenSSH Server", net start "openssh server"
  * All login attempt will be saved in "/var/log/sshd_login" inside OpenSSH Server installation path ("c:\program files\OpenSSH\var\log\")
  * That's it.

