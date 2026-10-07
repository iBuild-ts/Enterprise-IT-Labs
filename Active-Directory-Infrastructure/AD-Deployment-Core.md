Active Directory Domain Controller Infrastructure Build

Project Overview
>>Successfully deployed and configured a localized corporate enterprise identity provider infrastructure environment utilizing a Windows Server 2025 Standard Evaluation hypervisor machine instance.

#Technical Tasks Accomplished
*>> Static Network Hardening: Migrated the core network host link away from dynamic DHCP leases to a static IPv4 layer assignment (`10.0.2.15`), binding the loopback address (`127.0.0.1`) as the primary localized authority name resolution framework provider.
* > Forest Domain Promotion: Orchestrated the implementation of the `Active Directory Domain Services (AD DS)` system role, promoting the underlying system kernel to an authoritative root forest infrastructure domain tagged as `enterprise.local`.
* > Workforce Directory Architecture: Engineered a structured departmental hierarchy tree layout isolating organizational units (OUs) for executive parent oversight (`Enterprise-HQ`) along with localized operations blocks (`Sales`, `HR`, `IT`, `Finance`).
* > Identity Management & Access Governance: Executed automated user credential generation patterns via PowerShell framework instances, generated distinct network global Security Groups (`SG-Finance-Access`), and established security rules mapping role-based access variables.

# Verification Logs & Commands
* Base TCP/IP verification command executed: `ipconfig /all`
* System Administrative Directory Management framework used: Active Directory Users and Computers (ADUC)

  
# Operational Identity & Access Management (IAM) Work Logs

#Ticket 1: Active Directory User Bulk Provisioning
* >> Incident Description: New hire onboarding request for structural corporate departments.
* >> Action Taken: Leveraged administrative PowerShell terminal instances to bulk-provision user accounts matching corporate directory naming conventions, automatically appending organizational unit attributes and mapping target department trees.
* >> Target Accounts: `John Doe` (Sales), `Jane Smith` (HR), `Alex Tech` (IT), `Bob Rich` (Finance).

# Ticket 2: Global Security Group Implementation & Access Mapping
* >> Incident Description: Grant dedicated storage permission vectors for the Finance department division.
* >> Action Taken: Engineered a brand-new global Active Directory Security Group named `SG-Finance-Access` inside the target department OU. Staged access parameter bounds and successfully appended user account `brich` into the group container.
* >> Verification: Confirmed group inheritance strings via account object structural properties.

# Ticket 3: Administrative Password Override & Governance Enforcement
* Incident Description: Sales department user account credential lockout / recovery protocol execution.
* Action Taken: Located user account object `jdoe` within the Sales organizational unit. Initiated a standard administrative password reset protocol bypass, assigned a baseline temporary onboarding passphrase, and enforced corporate security policy controls by toggling the flag: `User must change password at next logon`.

# Network Infrastructure Engineering & Policy Deployment (Day 3 Log)

# Task 1: Cross-Virtual Machine Switching Network Binds
* >> Staging Actions: Reconfigured network link adapters within the virtualization hypervisor matrix, migrating both the Windows Server 2025 Domain Controller (`10.0.2.15`) and the Windows 11 Workstation client away from general NAT layers onto a unified isolated Internal Network switch named `Corporate-Switch`. 
* >> Client IP Engineering: Hard-coded a static corporate interface subnet profile on the Windows 11 endpoint client workstation assigning an IP of `10.0.2.50`, a subnet allocation mask of `255.255.255.0`, and manually bound the server link location as the exclusive target authoritative Preferred DNS provider.
* >> Troubleshooting Logs: Successfully diagnostic traced local packet drops via ICMP ping verifications and administrative namespace queries (`nslookup`).

# Task 2: Active Directory Domain Integration & Token Handshake
* >> Workstation Deployment: Initialized legacy system parameter assignments (`sysdm.cpl`) on the client container to migrate the node out of default isolated computer Workgroups. 
* >> Authentication Handshake: Negotiated an encrypted domain registration challenge handshake utilizing explicit target forest path routing parameters (`ENTERPRISE\Administrator`). Pushed the client machine configuration directly into the network directory trees and enforced a full workstation hardware initialization loop.
* >> Onboarding Validation: Successfully initialized a distinct domain user profile workspace (`atech`) mapped against active directory schemas and validated forced onboarding credential safety requirements.

# Task 3: Group Policy Object (GPO) Deployment & Workspace Hardening
* >> Infrastructure Rule Architecture: Engineered a customized system governance container profile titled `GPO-Restrict-ControlPanel` natively within the Group Policy Management Console.
* >> Registry Lockdown Parameter: Configured structural administrative registry system constraints to shift parameter state values for `Prohibit access to Control Panel and PC settings` to an explicit state of **Enabled**.
* >> Target Delivery Execution: Bound the GPO container layer directly to the departmental Organizational Unit (`OU=IT,OU=Enterprise-HQ`) containing targeted user object definitions.
* >> Client Verification Matrix: Executed an explicit system policy pull via `gpupdate /force` terminal commands, successfully verifying that the endpoint system dropped access and triggered programmatic cancellation alerts when attempting execution blocks.


# Automated Identity Pipelines & Network Storage Provisioning (Day 4 Log)

# Task 1: Granular Network Storage Architecture & Permissions Hardening
* >> Storage Matrix Creation: Hard-coded a physical network file storage environment named `CompanyData` directly within the system partition root (`C:\CompanyData`) of the Windows Server Domain Controller.
* >> Access Control & Governance Hardening:** Implemented a split identity access governance configuration. Exposed general Share Permissions wide to `Everyone` (Full Control) while hard-coding highly restrictive **NTFS Security Permissions** [INDEX]. Disabled system directory inheritance mappings, removed default standard local `Users` strings, and explicitly injected granular **Modify** permissions for the custom global security department group (`SG-Finance-Access`) [INDEX].

# Task 2: PowerShell Multi-Department Identity Automation Pipeline
* >> Scripted Automation Loop: Designed and natively executed a programmatic workforce deployment loop script inside Windows PowerShell ISE [INDEX]. 
* >> Database Expansion: Leveraged calculation algorithms (`for` loops and array cycling bounds) to programmatically provision **20 unique employee user account objects** across the active directory network schema [INDEX]. 
* >> Target Delivery Layout: Distributed accounts (`emp1` through `emp20`) evenly across dedicated target organizational unit paths (`Sales`, `HR`, `IT`, `Finance`), automatically mapping user principal configurations (`@enterprise.local`) and enforcing system safety parameters (`User must change password at next logon`) [INDEX].

# Task 3: Group Policy Network Drive Mapping & Endpoint Enforcement
* >> Infrastructure Preference Configuration: Engineered a centralized workstation resource distribution policy container titled `GPO-Map-NetworkDrives` inside the Group Policy Management Console [INDEX].
* >> Remote Path Routing: Configured a native Drive Map preference parameter utilizing **Update** execution mechanics to bind the remote storage network share path (`\\10.0.2.15\CompanyData`) directly onto endpoint file allocation layers [INDEX].
* >> Workstation Verification Check: Assigned the policy structure directly onto the root forest domain target tree link (`enterprise.local`) [INDEX]. Executed an administrative `gpupdate /force` terminal command on the domain-joined Windows 11 client machine, successfully verifying that the network stack dynamically mounted the storage target under the **`Z:` drive** environment interface [INDEX].

