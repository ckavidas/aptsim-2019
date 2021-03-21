## APT Simulator Events (In chronological order)

___


1. wmic process call create cmd.exe (testing logging)
2. Antivirus exceptions in the registry
3. creating a c.\tmp dir
4. using curl to access well known C2 addresses
5. DNS cache entries for well known c2 servers
6. Using certutil to drop a cactustorch shellcode launcher 
7. Using malicious user agents to access web sites
8. dropping a powershell netcat alternative into the APT dir
9. Using WMIBackdoor to contact a C2 in certain intervals
10. Dumping LSASS memory with ProcDump
11. Dropping a custom mimikatz build into the APT dir
12. Executing mimikatz to get it into memory and saving the output to out.tmp
13. Running Invoke-Mimikatz. downloading from github run from memory
14. Activating guest user account
15. Adding guest user to local admins
16. Placing a svchost.exe into c.\users\public
17. running the file
18. Using certutil to drop a cactustorch shellcode launcher injecting bind shell (port 1234 tcp) into rundll32.exe
19. Dropping obfuscated rar file with jpg extension
20. Executing nbtscan
21. various recon commands
22. dropping a modified psexec into the apt dir
23. dropping a remote execution tool into the apt dir
24. registering mimikatz in at job
25. registering a malicious run key
26. creating a scheduled task via xml using powershell script
27. registering mimikatz in scheduled task
28. sethc backdoor
29. UserInitMprLogonScript persistence
30. Dropping web shell in new www directory
31. Using WMI backdoor to kill local procexp64 when it starts
