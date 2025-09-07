# Trying an exploit against a vulnerable service (FTP, Telnet, Samba)
# Capture [open.png]
- Opening Metasploit with msfconsole.
# Capture [expl.png]
- Using command "search type:exploit name:ftp in order to find an exploit in Metasploit.
- search = Looking modules inside Metasploit
- type:exploit = Limit the search to only exploits
- name:ftp = Filter to search just exploits related with FTP (vulnerable services)
# Capture [shell.png]
- Opening a remote shell in Metasploit using command:
  use exploit/unix/ftp/vsftpd_234_backdoor

