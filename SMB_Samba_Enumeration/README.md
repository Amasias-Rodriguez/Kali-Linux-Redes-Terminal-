--- Samba Enumeration ---
# Capture [identsmb.png]
- Identifying an active SMB (SERVER MESSAGE BLOCK).
- Using scripts (smb-enum-shares) (smb-enum-users)
# Capture [shared.png]
- Connect to the shared resource using: smbcliente//192.168.56.103/tmp -N
- smbclient = SMB Linux client
- 192.168.56.103/tmp = the shared resource we found.
- -N = it tells to not use credentials (anonimous access) 
