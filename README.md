# Comparison of Windows Versions

This information was pulled using ***SERVER_EVAL_x64FRE_en-us.iso*** (MD5:E7908933449613EDC97E1B11180429D1) from [Windows Server 2022 | Microsoft Evaluation Center](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2022) using VMs with the same specs, 6GB RAM, 50GB Disk (on SSD), and a single CPU core.

fresh install no config changes comparison
| | Server 2022 | Server 2022 (Desktop Experience) |
| --- | --- | --- |
| VHD Size | 6.12 GB | 9.47 GB |
| Processes | 76 | 122 |
| Installed Services | 115 | 207 |
| Running Services| 57 | 84 |

### Services
| Service | DisplayName | Server 2022 | Server 2022 (Desktop Experience) |
| --- | --- | --- | --- |
| AJRouter | AllJoyn Router Service || ✔ |
| ALG | Application Layer Gateway Service  || ✔ |
| AppIDSvc | Application Identity | ✔ | ✔ |
| Appinfo | Application Information || ✔ |
| AppMgmt | Application Management | ✔ | ✔ |
| AppReadiness | App Readiness | ✔ | ✔ |
| AppVClient | Microsoft App-V Client || ✔ |
| AppXSvc | AppX Deployment Service (AppXSVC) | ✔ | ✔ |
| AudioEndpointBu... | Windows Audio Endpoint Builder || ✔ |
| Audiosrv | Windows Audio || ✔ |
| AxInstSV | ActiveX Installer (AxInstSV) || ✔ |
| BFE | Base Filtering Engine | ✔ | ✔ |
| BITS | Background Intelligent Transfer Ser... | ✔ | ✔ |
| BrokerInfrastru... | Background Tasks Infrastructure Ser... || ✔ |
| bthserv | Bluetooth Support Service || ✔ |
| camsvc | Capability Access Manager Service || ✔ |
| CaptureService_... | CaptureService_11021f || ✔ |
| cbdhsvc_11021f | Clipboard User Service_11021f || ✔ |
| CDPSvc | Connected Devices Platform Service || ✔ |
| CDPUserSvc_11021f | Connected Devices Platform User Ser... || ✔ |
| CertPropSvc | Certificate Propagation | ✔ | ✔ |
| ClipSVC | Client License Service (ClipSVC) | ✔ | ✔ |
| COMSysApp | COM+ System Application | ✔ | ✔ |
| ConsentUxUserSv... | ConsentUX User Service_11021f || ✔ |
| CoreMessagingRe... | CoreMessaging | ✔ | ✔ |
| CredentialEnrol... | CredentialEnrollmentManagerUserSvc_... || ✔ |
| CryptSvc | Cryptographic Services | ✔ | ✔ |
| CscService | Offline Files || ✔ |
| DcomLaunch | DCOM Server Process Launcher | ✔ | ✔ |
| defragsvc | Optimize drives | ✔ | ✔ |
| DeviceAssociati... | DeviceAssociationBroker_11021f || ✔ |
| DeviceAssociati... | Device Association Service || ✔ |
| DeviceInstall | Device Install Service | ✔ | ✔ |
| DevicePickerUse... | DevicePicker_11021f || ✔ |
| DevicesFlowUser... | DevicesFlow_11021f || ✔ |
| DevQueryBroker | DevQuery Background Discovery Broker || ✔ |
| Dhcp | DHCP Client | ✔ | ✔ |
| diagnosticshub.... | Microsoft (R) Diagnostics Hub Stand... | ✔ | ✔ |
| DiagTrack | Connected User Experiences and Tele... | ✔ | ✔ |
| DispBrokerDeskt... | Display Policy Service || ✔ |
| DmEnrollmentSvc | Device Management Enrollment Service || ✔ |
| dmwappushservice | Device Management Wireless Applicat... || ✔ |
| Dnscache | DNS Client | ✔ | ✔ |
| DoSvc | Delivery Optimization | ✔ | ✔ |
| dot3svc | Wired AutoConfig || ✔ |
| DPS | Diagnostic Policy Service | ✔ | ✔ |
| DsmSvc | Device Setup Manager || ✔ |
| DsSvc | Data Sharing Service || ✔ |
| EapHost | Extensible Authentication Protocol | ✔ | ✔ |
| edgeupdate | Microsoft Edge Update Service (edge... || ✔ |
| edgeupdatem | Microsoft Edge Update Service (edge... || ✔ |
| EFS | Encrypting File System (EFS) | ✔ | ✔ |
| embeddedmode | Embedded Mode || ✔ |
| EntAppSvc | Enterprise App Management Service || ✔ |
| EventLog | Windows Event Log | ✔ | ✔ |
| EventSystem | COM+ Event System | ✔ | ✔ |
| fdPHost | Function Discovery Provider Host || ✔ |
| FDResPub | Function Discovery Resource Publica... || ✔ |
| FontCache | Windows Font Cache Service || ✔ |
| FrameServer | Windows Camera Frame Server || ✔ |
| FrameServerMonitor | Windows Camera Frame Server Monitor || ✔ |
| gpsvc | Group Policy Client | ✔ | ✔ |
| GraphicsPerfSvc | GraphicsPerfSvc || ✔ |
| hidserv | Human Interface Device Service | ✔ | ✔ |
| HvHost | HV Host Service | ✔ | ✔ |
| IKEEXT | IKE and AuthIP IPsec Keying Modules | ✔ | ✔ |
| InstallService | Microsoft Store Install Service || ✔ |
| iphlpsvc | IP Helper | ✔ | ✔ |
| KeyIso | CNG Key Isolation | ✔ | ✔ |
| KPSSVC | KDC Proxy Server service (KPS) | ✔ | ✔ |
| KtmRm | KtmRm for Distributed Transaction C... | ✔ | ✔ |
| LanmanServer | Server | ✔ | ✔ |
| LanmanWorkstation | Workstation | ✔ | ✔ |
| lfsvc | Geolocation Service || ✔ |
| LicenseManager | Windows License Manager Service || ✔ |
| lltdsvc | Link-Layer Topology Discovery Mapper | ✔ | ✔ |
| lmhosts | TCP/IP NetBIOS Helper | ✔ | ✔ |
| LSM | Local Session Manager | ✔ | ✔ |
| MapsBroker | Downloaded Maps Manager || ✔ |
| McpManagementSe... | McpManagementService || ✔ |
| MicrosoftEdgeEl... | Microsoft Edge Elevation Service (M... || ✔ |
| mpssvc | Windows Defender Firewall | ✔ | ✔ |
| MSDTC | Distributed Transaction Coordinator | ✔ | ✔ |
| MSiSCSI | Microsoft iSCSI Initiator Service | ✔ | ✔ |
| msiserver | Windows Installer | ✔ | ✔ |
| NcaSvc | Network Connectivity Assistant | ✔ | ✔ |
| NcbService | Network Connection Broker || ✔ |
| Netlogon | Netlogon | ✔ | ✔ |
| Netman | Network Connections || ✔ |
| netprofm | Network List Service | ✔ | ✔ |
| NetSetupSvc | Network Setup Service | ✔ | ✔ |
| NetTcpPortSharing | Net.Tcp Port Sharing Service | ✔ | ✔ |
| NgcCtnrSvc | Microsoft Passport Container || ✔ |
| NgcSvc | Microsoft Passport || ✔ |
| NlaSvc | Network Location Awareness | ✔ | ✔ |
| nsi | Network Store Interface Service | ✔ | ✔ |
| PcaSvc | Program Compatibility Assistant Ser... || ✔ |
| PerfHost | Performance Counter DLL Host | ✔ | ✔ |
| PimIndexMainten... | Contact Data_11021f || ✔ |
| pla | Performance Logs & Alerts | ✔ | ✔ |
| PlugPlay | Plug and Play | ✔ | ✔ |
| PolicyAgent | IPsec Policy Agent | ✔ | ✔ |
| Power | Power | ✔ | ✔ |
| PrintNotify | Printer Extensions and Notifications || ✔ |
| PrintWorkflowUs... | PrintWorkflow_11021f || ✔ |
| ProfSvc | User Profile Service | ✔ | ✔ |
| PushToInstall | Windows PushToInstall Service || ✔ |
| QWAVE | Quality Windows Audio Video Experience || ✔ |
| RasAuto | Remote Access Auto Connection Manager || ✔ |
| RasMan | Remote Access Connection Manager | ✔ | ✔ |
| RemoteAccess | Routing and Remote Access | ✔ | ✔ |
| RemoteRegistry | Remote Registry | ✔ | ✔ |
| RmSvc | Radio Management Service || ✔ |
| RpcEptMapper | RPC Endpoint Mapper | ✔ | ✔ |
| RpcLocator | Remote Procedure Call (RPC) Locator || ✔ |
| RpcSs | Remote Procedure Call (RPC) | ✔ | ✔ |
| RSoPProv | Resultant Set of Policy Provider | ✔ | ✔ |
| sacsvr | Special Administration Console Helper | ✔ | ✔ |
| SamSs | Security Accounts Manager | ✔ | ✔ |
| SCardSvr | Smart Card | ✔ | ✔ |
| ScDeviceEnum | Smart Card Device Enumeration Service | ✔ | ✔ |
| Schedule | Task Scheduler | ✔ | ✔ |
| SCPolicySvc | Smart Card Removal Policy | ✔ | ✔ |
| seclogon | Secondary Logon | ✔ | ✔ |
| SecurityHealthS... | Windows Security Service || ✔ |
| SEMgrSvc | Payments and NFC/SE Manager || ✔ |
| SENS | System Event Notification Service | ✔ | ✔ |
| Sense | Windows Defender Advanced Threat Pr... | ✔ | ✔ |
| SensorDataService | Sensor Data Service || ✔ |
| SensorService | Sensor Service || ✔ |
| SensrSvc | Sensor Monitoring Service || ✔ |
| SessionEnv | Remote Desktop Configuration | ✔ | ✔ |
| SgrmBroker | System Guard Runtime Monitor Broker | ✔ | ✔ |
| SharedAccess | Internet Connection Sharing (ICS) | ✔ | ✔ |
| ShellHWDetection | Shell Hardware Detection || ✔ |
| shpamsvc | Shared PC Account Manager || ✔ |
| smphost | Microsoft Storage Spaces SMP | ✔ | ✔ |
| SNMPTRAP | SNMP Trap | ✔ | ✔ |
| Spooler | Print Spooler || ✔ |
| sppsvc | Software Protection | ✔ | ✔ |
| SSDPSRV | SSDP Discovery || ✔ |
| ssh-agent | OpenSSH Authentication Agent | ✔ | ✔ |
| SstpSvc | Secure Socket Tunneling Protocol Se... | ✔ | ✔ |
| StateRepository | State Repository Service | ✔ | ✔ |
| StiSvc | Windows Image Acquisition (WIA) || ✔ |
| StorSvc | Storage Service || ✔ |
| svsvc | Spot Verifier | ✔ | ✔ |
| swprv | Microsoft Software Shadow Copy Prov... | ✔ | ✔ |
| SysMain | SysMain | ✔ | ✔ |
| SystemEventsBroker | System Events Broker | ✔ | ✔ |
| TabletInputService | Touch Keyboard and Handwriting Pane... || ✔ |
| tapisrv | Telephony || ✔ |
| TermService | Remote Desktop Services | ✔ | ✔ |
| Themes | Themes || ✔ |
| TieringEngineSe... | Storage Tiers Management | ✔ | ✔ |
| TimeBrokerSvc | Time Broker | ✔ | ✔ |
| TokenBroker | Web Account Manager || ✔ |
| TrkWks | Distributed Link Tracking Client || ✔ |
| TrustedInstaller | Windows Modules Installer | ✔ | ✔ |
| tzautoupdate | Auto Time Zone Updater || ✔ |
| UALSVC | User Access Logging Service | ✔ | ✔ |
| UdkUserSvc_11021f | Udk User Service_11021f || ✔ |
| UevAgentService | User Experience Virtualization Service || ✔ |
| UmRdpService | Remote Desktop Services UserMode Po... | ✔ | ✔ |
| UnistoreSvc_11021f | User Data Storage_11021f || ✔ |
| upnphost | UPnP Device Host || ✔ |
| UserDataSvc_11021f | User Data Access_11021f || ✔ |
| UserManager | User Manager | ✔ | ✔ |
| UsoSvc | Update Orchestrator Service | ✔ | ✔ |
| VaultSvc | Credential Manager | ✔ | ✔ |
| vds | Virtual Disk | ✔ | ✔ |
| vmicguestinterface | Hyper-V Guest Service Interface | ✔ | ✔ |
| vmicheartbeat | Hyper-V Heartbeat Service | ✔ | ✔ |
| vmickvpexchange | Hyper-V Data Exchange Service | ✔ | ✔ |
| vmicshutdown | Hyper-V Guest Shutdown Service | ✔ | ✔ |
| vmictimesync | Hyper-V Time Synchronization Service | ✔ | ✔ |
| vmicvmsession | Hyper-V PowerShell Direct Service | ✔ | ✔ |
| vmicvss | Hyper-V Volume Shadow Copy Requestor | ✔ | ✔ |
| VSS | Volume Shadow Copy | ✔ | ✔ |
| W32Time | Windows Time | ✔ | ✔ |
| WaaSMedicSvc | Windows Update Medic Service | ✔ | ✔ |
| WalletService | WalletService || ✔ |
| WarpJITSvc | Warp JIT Service || ✔ |
| WbioSrvc | Windows Biometric Service || ✔ |
| Wcmsvc | Windows Connection Manager || ✔ |
| WdiServiceHost | Diagnostic Service Host | ✔ | ✔ |
| WdiSystemHost | Diagnostic System Host | ✔ | ✔ |
| WdNisSvc | Microsoft Defender Antivirus Networ... | ✔ | ✔ |
| Wecsvc | Windows Event Collector | ✔ | ✔ |
| WEPHOSTSVC | Windows Encryption Provider Host Se... || ✔ |
| wercplsupport | Problem Reports Control Panel Support || ✔ |
| WerSvc | Windows Error Reporting Service | ✔ | ✔ |
| WiaRpc | Still Image Acquisition Events || ✔ |
| WinDefend | Microsoft Defender Antivirus Service | ✔ | ✔ |
| WinHttpAutoProx... | WinHTTP Web Proxy Auto-Discovery Se... | ✔ | ✔ |
| Winmgmt | Windows Management Instrumentation | ✔ | ✔ |
| WinRM | Windows Remote Management (WS-Manag... | ✔ | ✔ |
| wisvc | Windows Insider Service | ✔ | ✔ |
| wlidsvc | Microsoft Account Sign-in Assistant || ✔ |
| WLMS | Windows Licensing Monitoring Service | ✔ | ✔ |
| wmiApSrv | WMI Performance Adapter | ✔ | ✔ |
| WMPNetworkSvc | Windows Media Player Network Sharin... || ✔ |
| WPDBusEnum | Portable Device Enumerator Service || ✔ |
| WpnService | Windows Push Notifications System S... || ✔ |
| WpnUserService_... | Windows Push Notifications User Ser... || ✔ |
| WSearch | Windows Search || ✔ |
| wuauserv | Windows Update | ✔ | ✔ |
