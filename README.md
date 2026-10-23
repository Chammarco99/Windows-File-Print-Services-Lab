# Windows File & Print Services Lab

## Project Overview

This project demonstrates the deployment, configuration, and troubleshooting of Windows File and Print Services in a simulated enterprise environment using Windows Server 2022 and Windows 10.

The lab builds upon an existing Active Directory environment to implement secure departmental file sharing, role-based access control, SMB authentication, and a centrally managed shared printer.

The project also demonstrates practical troubleshooting, network connectivity testing, and validation of user access permissions.

## Lab Objectives

- Configure secure SMB file shares for six business departments.
- Implement role-based access control using Active Directory security groups.
- Configure NTFS and SMB share permissions following the principle of least privilege.
- Validate authorised access and prevent unauthorised access to departmental resources.
- Install and configure the Windows Server Print Services role.
- Deploy a shared printer accessible from a Windows client.
- Test virtual print output without requiring physical printer hardware.
- Troubleshoot authentication, networking, and printing issues.

## Lab Environment

| Component | Configuration |
|---|---|
| Hypervisor | Oracle VirtualBox |
| Domain Controller / File & Print Server | Windows Server 2022 (DC01) |
| Client | Windows 10 Home (PC01) |
| Active Directory Domain | Marcotech.ltd |
| Server IP Address | 192.168.10.10 |
| Network | VirtualBox Internal Network (AD-LAB) |
| Departments | Sales, HR, Finance, IT, Management, Operations |
| Print Driver | Generic / Text Only |

**Note:** Windows 10 Home cannot join an Active Directory domain. The client accessed domain resources using explicitly supplied domain credentials.
