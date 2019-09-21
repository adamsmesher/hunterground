# ATT&CK Tactic & Technique Matrix
| initial-access | execution | persistence | privilege-escalation | defense-evasion | credential-access | discovery | lateral-movement | collection | exfiltration | command-and-control |
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Drive-by Compromise  | AppleScript | .bash_profile and .bashrc | Access Token Manipulation | Access Token Manipulation | Account Manipulation | Account Discovery | AppleScript | Audio Capture | Automated Exfiltration  | Commonly Used Port  |
| Exploit Public-Facing Application  | CMSTP | Accessibility Features | Accessibility Features | BITS Jobs | Bash History | Application Window Discovery | Application Deployment Software  | Automated Collection | Data Compressed | Communication Through Removable Media  |
| External Remote Services  | Command-Line Interface | Account Manipulation | AppCert DLLs  | Binary Padding | Brute Force | Browser Bookmark Discovery | Distributed Component Object Model  | Clipboard Data | Data Encrypted | Connection Proxy |
| Hardware Additions  | Compiled HTML File | AppCert DLLs  | AppInit DLLs | Bypass User Account Control | Credential Dumping | Domain Trust Discovery | Exploitation of Remote Services  | Data Staged | Data Transfer Size Limits | Custom Command and Control Protocol  |
| Replication Through Removable Media  | Control Panel Items | AppInit DLLs | Application Shimming | CMSTP | Credentials in Files | File and Directory Discovery | Logon Scripts | Data from Information Repositories  | Exfiltration Over Alternative Protocol | Custom Cryptographic Protocol  |
| Spearphishing Attachment | Dynamic Data Exchange | Application Shimming | Bypass User Account Control | Clear Command History | Credentials in Registry | Network Service Scanning | Pass the Hash | Data from Local System | Exfiltration Over Command and Control Channel  | Data Encoding |
| Spearphishing Link  | Execution through API  | Authentication Package  | DLL Search Order Hijacking | Code Signing  | Exploitation for Credential Access  | Network Share Discovery | Pass the Ticket | Data from Network Shared Drive  | Exfiltration Over Other Network Medium  | Data Obfuscation  |
| Spearphishing via Service  | Execution through Module Load  | BITS Jobs | Dylib Hijacking  | Compile After Delivery  | Forced Authentication  | Network Sniffing | Remote Desktop Protocol | Data from Removable Media  | Exfiltration Over Physical Medium  | Domain Fronting  |
| Supply Chain Compromise  | Exploitation for Client Execution  | Bootkit  | Exploitation for Privilege Escalation  | Compiled HTML File | Hooking | Password Policy Discovery | Remote File Copy | Email Collection | Scheduled Transfer  | Domain Generation Algorithms  |
| Trusted Relationship  | Graphical User Interface  | Browser Extensions | Extra Window Memory Injection  | Component Firmware  | Input Capture | Peripheral Device Discovery  | Remote Services  | Input Capture |  | Fallback Channels  |
| Valid Accounts  | InstallUtil | Change Default File Association | File System Permissions Weakness  | Component Object Model Hijacking | Input Prompt | Permission Groups Discovery | Replication Through Removable Media  | Man in the Browser  |  | Multi-Stage Channels  |
|  | LSASS Driver  | Component Firmware  | Hooking | Control Panel Items | Kerberoasting  | Process Discovery | SSH Hijacking  | Screen Capture |  | Multi-hop Proxy  |
|  | Launchctl | Component Object Model Hijacking | Image File Execution Options Injection | DCShadow | Keychain | Query Registry | Shared Webroot  | Video Capture  |  | Multiband Communication  |
|  | Local Job Scheduling | Create Account | Launch Daemon | DLL Search Order Hijacking | LLMNR/NBT-NS Poisoning and Relay  | Remote System Discovery | Taint Shared Content  |  |  | Multilayer Encryption  |
|  | Mshta | DLL Search Order Hijacking | New Service | DLL Side-Loading  | Network Sniffing | Security Software Discovery | Third-party Software  |  |  | Port Knocking  |
|  | PowerShell | Dylib Hijacking  | Path Interception  | Deobfuscate/Decode Files or Information | Password Filter DLL | System Information Discovery | Windows Admin Shares |  |  | Remote Access Tools  |
|  | Regsvcs/Regasm | External Remote Services  | Plist Modification | Disabling Security Tools | Private Keys | System Network Configuration Discovery | Windows Remote Management |  |  | Remote File Copy |
|  | Regsvr32 | File System Permissions Weakness  | Port Monitors  | Execution Guardrails  | Securityd Memory  | System Network Connections Discovery |  |  |  | Standard Application Layer Protocol |
|  | Rundll32 | Hidden Files and Directories | Process Injection | Exploitation for Defense Evasion  | Two-Factor Authentication Interception  | System Owner/User Discovery |  |  |  | Standard Cryptographic Protocol  |
|  | Scheduled Task | Hooking | SID-History Injection  | Extra Window Memory Injection  |  | System Service Discovery |  |  |  | Standard Non-Application Layer Protocol  |
|  | Scripting | Hypervisor | Scheduled Task | File Deletion |  | System Time Discovery |  |  |  | Uncommonly Used Port |
|  | Service Execution | Image File Execution Options Injection | Service Registry Permissions Weakness  | File Permissions Modification |  | Virtualization/Sandbox Evasion  |  |  |  | Web Service  |
|  | Signed Binary Proxy Execution | Kernel Modules and Extensions  | Setuid and Setgid | File System Logical Offsets  |  |  |  |  |  |  |
|  | Signed Script Proxy Execution | LC_LOAD_DYLIB Addition  | Startup Items | Gatekeeper Bypass |  |  |  |  |  |  |
|  | Source | LSASS Driver  | Sudo | Group Policy Modification  |  |  |  |  |  |  |
|  | Space after Filename | Launch Agent | Sudo Caching | HISTCONTROL |  |  |  |  |  |  |
|  | Third-party Software  | Launch Daemon | Valid Accounts  | Hidden Files and Directories |  |  |  |  |  |  |
|  | Trap | Launchctl | Web Shell | Hidden Users |  |  |  |  |  |  |
|  | Trusted Developer Utilities | Local Job Scheduling |  | Hidden Window  |  |  |  |  |  |  |
|  | User Execution  | Login Item  |  | Image File Execution Options Injection |  |  |  |  |  |  |
|  | Windows Management Instrumentation | Logon Scripts |  | Indicator Blocking  |  |  |  |  |  |  |
|  | Windows Remote Management | Modify Existing Service |  | Indicator Removal from Tools  |  |  |  |  |  |  |
|  | XSL Script Processing | Netsh Helper DLL |  | Indicator Removal on Host |  |  |  |  |  |  |
|  |  | New Service |  | Indirect Command Execution |  |  |  |  |  |  |
|  |  | Office Application Startup |  | Install Root Certificate |  |  |  |  |  |  |
|  |  | Path Interception  |  | InstallUtil |  |  |  |  |  |  |
|  |  | Plist Modification |  | LC_MAIN Hijacking  |  |  |  |  |  |  |
|  |  | Port Knocking  |  | Launchctl |  |  |  |  |  |  |
|  |  | Port Monitors  |  | Masquerading |  |  |  |  |  |  |
|  |  | Rc.common |  | Modify Registry |  |  |  |  |  |  |
|  |  | Re-opened Applications |  | Mshta |  |  |  |  |  |  |
|  |  | Redundant Access  |  | NTFS File Attributes |  |  |  |  |  |  |
|  |  | Registry Run Keys / Startup Folder |  | Network Share Connection Removal |  |  |  |  |  |  |
|  |  | SIP and Trust Provider Hijacking  |  | Obfuscated Files or Information |  |  |  |  |  |  |
|  |  | Scheduled Task |  | Plist Modification |  |  |  |  |  |  |
|  |  | Screensaver |  | Port Knocking  |  |  |  |  |  |  |
|  |  | Security Support Provider |  | Process Doppelgänging  |  |  |  |  |  |  |
|  |  | Service Registry Permissions Weakness  |  | Process Hollowing  |  |  |  |  |  |  |
|  |  | Setuid and Setgid |  | Process Injection |  |  |  |  |  |  |
|  |  | Shortcut Modification  |  | Redundant Access  |  |  |  |  |  |  |
|  |  | Startup Items |  | Regsvcs/Regasm |  |  |  |  |  |  |
|  |  | System Firmware  |  | Regsvr32 |  |  |  |  |  |  |
|  |  | Systemd Service |  | Rootkit |  |  |  |  |  |  |
|  |  | Time Providers  |  | Rundll32 |  |  |  |  |  |  |
|  |  | Trap |  | SIP and Trust Provider Hijacking  |  |  |  |  |  |  |
|  |  | Valid Accounts  |  | Scripting |  |  |  |  |  |  |
|  |  | Web Shell |  | Signed Binary Proxy Execution |  |  |  |  |  |  |
|  |  | Windows Management Instrumentation Event Subscription |  | Signed Script Proxy Execution |  |  |  |  |  |  |
|  |  | Winlogon Helper DLL |  | Software Packing  |  |  |  |  |  |  |
|  |  |  |  | Space after Filename |  |  |  |  |  |  |
|  |  |  |  | Template Injection  |  |  |  |  |  |  |
|  |  |  |  | Timestomp |  |  |  |  |  |  |
|  |  |  |  | Trusted Developer Utilities |  |  |  |  |  |  |
|  |  |  |  | Valid Accounts  |  |  |  |  |  |  |
|  |  |  |  | Virtualization/Sandbox Evasion  |  |  |  |  |  |  |
|  |  |  |  | Web Service  |  |  |  |  |  |  |
|  |  |  |  | XSL Script Processing |  |  |  |  |  |  |