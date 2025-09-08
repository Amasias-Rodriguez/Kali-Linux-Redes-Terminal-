--- Brute Force ---
- First we create an user file and a password file with nano user.txt and pass.txt
# Capture [hydra.png]
- Using Hydra against the SMB with command: hydra -L users.txt -P pass.txt 192.168.56.103 smb
- -L users.txt users list
- -P pass.txt passwords list
- 192.168.56.103 Metasploit IP
- smb = main protocol
