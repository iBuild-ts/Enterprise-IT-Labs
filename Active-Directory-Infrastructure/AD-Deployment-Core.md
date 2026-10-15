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



# Microsoft 365 Cloud Enterprise Architecture & Security Hardening (Day 5 Log)

# Task 1: Corporate Microsoft 365 Tenant Provisioning & Licensing Matrix
* >> Infrastructure Deployment: Engineered a live enterprise-tier software-as-a-service cloud tenant infrastructure network space under the custom identity suffix registration: `SteveTechSolutions.onmicrosoft.com` [INDEX].
* >> Cloud-Native Provisioning: Bypassed programmatic vendor sign-in boundaries to establish full Global Administrator privileges [INDEX]. Provisioned cloud-native remote user identity records natively inside the Microsoft 365 Admin Center (`zmusa`) [INDEX], executing proper corporate configuration patterns and assigning complete asset licensing distributions for **Microsoft 365 Business Premium** [INDEX].

# Task 2: Delegated Corporate Shared Mailbox Implementation
* >> Queue Configuration: Architected an isolated customer-facing support communications portal box matching the enterprise address path: `support@SteveTechSolutions.onmicrosoft.com` [INDEX].
* >> Access Permission Mapping: Appended granular administrative group security delegates to the container, mapping explicit **Read and Manage** permissions alongside secure **Send As** cryptographic authorization privileges to user record `Zainab Musa` to optimize decentralized remote helpdesk flows [INDEX].

# Task 3: Identity Governance & Global Perimeter Hardening
* >> Portal Management: Accessed advanced cloud directory controls natively via the Microsoft Entra ID Admin Center console hub (`://microsoft.com`) [INDEX].
* >> Security Defaults Enforcement: Conducted an infrastructure security audit within global tenant properties, programmatically enforcing the activation of **Security Defaults** to **Enabled** [INDEX]. This policy configuration hard-locks modern authentication patterns, completely blocks legacy brute-force authentication streams, and forces automated Multi-Factor Authentication (MFA) application registration enforcement globally across all network identities [INDEX].

# Enterprise Endpoint Governance & Cloud Policy Engineering (Day 7 Log)

# Task 1: MDM Automation Gateway Configuration
* >> Tenant Initialization: Access the global Microsoft Intune Admin Center control console to configure automatic Mobile Device Management (MDM) enrollment scopes. 
* >> Scope Optimization: Programmatically shifted the MDM user target framework parameters from 'None' to 'All', guaranteeing immediate cloud certificate onboarding hooks for all system identities.

# Task 2: Advanced Cloud-Native Endpoint Hardening Profile
* >> Compliance Architecture: Architected an isolated Windows 10/11 system configuration configuration model blueprint titled `GPO-Cloud-WorkplaceHardening` leveraging the native Intune Device Restrictions framework.
* >> Peripheral Access Governance: Enforced deep kernel-level data protections by hard-coding a strict 'Block' parameter against all Removable Storage devices, immediately neutralizing USB flash drive read/write vectors to block local malicious data exfiltration.
* >> Fleet Assignment Routing: Linked the resulting device restriction matrices across the absolute global tenant landscape, ensuring automated over-the-air policy pushes to the entire active remote device tree.


# Automated Cloud Software Distribution & Zero-Trust Compliance Engineering (Day 8 Log)

# Task 1: Line-of-Business (LOB) Silent Software Packaging & Distribution
* >> Infrastructure Delivery: Bypassed visual store repository synchronization delays by engineering a manual enterprise software delivery workflow within the Microsoft Intune App deployment plane.
* >> Binary Packaging: Imported a standalone Microsoft Installer (MSI) enterprise architecture package (`GoogleChromeStandaloneEnterprise64.msi`) directly into the secure tenant data container space.
* >> Deployment Enforcement: Hard-coded the application parameters under a strict 'Required' workforce assignment matrix, forcing automated background, silent installation loops across the entire global device tree without requiring local administrator user privileges.

# Task 2: Endpoint Compliance Architecture & Zero-Trust Parameter Hardening
* >> Identity Protection Policy: Architected and compiled a comprehensive Windows 10/11 system configuration compliance profile container titled `COMP-Cloud-IdentityBaseline` natively inside the global Intune engine.
* >> Security Matrix Hardening: Configured ironclad System Security rules enforcing an 8-character minimum password length limitation restricted explicitly to Alphanumeric complexity formats to completely eliminate weak local device PIN sequences.
* >> Hardware Firewall Verification: Hard-coded strict endpoint network perimeter validations by requiring an active system firewall status check; non-compliant devices immediately trigger penalty-box token drops, terminating real-time corporate file session keys over the web connection.

  

# Cloud Business Continuity & Disaster Recovery Infrastructure (Day 9 Log)

# Task 1: Recovery Services Vault (RSV) Provisioning
* >> Storage Architecture: Deployed a centralized cloud-native Recovery Services Vault titled `RSV-Corporate-Backups` nested within the unified `RG-Cloud-Infrastructure` parent resource container group.
* >> Redundancy Optimization: Handled cost mitigation and credit boundaries by programmatically shifting the backup storage fabric from Geo-redundant (GRS) to Locally-redundant (LRS) while maintaining identical hands-on deployment matrices.

# Task 2: Automated Retention Lifecycle & Standalone Policy Engineering
* >> Data Protection Blueprint: Engineered an automated server lifecycle backup track policy container designated as `BKPOL-Cloud-ServerDaily` leveraging the modern Enhanced policy framework engine.
* >> Frequency & Recovery Windows: Hard-coded a precise daily snapshot execution schedule timed at 11:00 PM W. Central Africa Standard Time to eliminate production bandwidth constraints, pairing it with an ironclad 30-day retention range lifecycle to defend against persistent ransomware vectors.
* >> Architecture Bypass Integration: Successfully executed an engineering workaround by decoupling the policy from deployment wizard resource locks and deploying the framework standalone directly inside the vault's master schema data rows.



# Cloud Infrastructure Observability & Real-Time Security Alert Engineering (Day 10 Log)

# Task 1: Telemetry Core Namespace Integration
* **Governance Calibration:** Investigated and resolved localized core engine namespace platform validation blocks. 
* **Resource Provider Activation:** Used deep platform directory settings to forcefully register the `microsoft.insights` telemetry cluster at the root subscription layer, unblocking advanced diagnostic infrastructure capabilities across the tenant.

# Task 2: Centralized Notification Infrastructure Configuration
* >> Action Group Staging: Engineered a multi-channel cloud communication pipeline container designated as `AG-Corporate-ITOps` nested within the unified `RG-Cloud-Infrastructure` parent wrapper group.
* >> Routing Telemetry Mechanics: Hard-coded dedicated global operational parameters (`ITOpsAlerts`) pairing automated multi-tenant system signals with direct SMS and enterprise email forwarding touchpoints.

# Task 3: Zero-Trust Activity Log Deletion Sentinel Policy
* >> Alert Rule Construction: Compiled an automated structural activity monitoring policy framework titled `ALERT-Cloud-ServerProtection` targeting the `Microsoft.Compute/virtualMachines` asset tree.
* >> Security Threat Mitigation: Configured real-time system listeners to track destructive operational signals (`Delete Virtual Machine`); unauthorized administrative destructive cycles immediately force automated alerts to active engineer consoles to prevent data asset liquidation.



# Enterprise Linux System Architecture & Shell Environment Customization (Day 11 Log)

# Task 1: Headless Linux Filesystem Mapping & Audit Operations
* >> Distribution Verification: Accessed an enterprise-hardened cloud compute shell instance to audit local system metadata configuration configurations (`/etc/os-release`), identifying a production **Microsoft Azure Linux 3.0 (CBL-Mariner)** distribution tier runtime.
* >> Diagnostic Telemetry Extraction: Traversed complex system logs within the `/var/log` core cluster space to analyze background infrastructure log queues (`audit`, `journal`, and `cloudshell_env.json`).

# Task 2: Command-Line File Manipulation & Automation Script Rules
* >> Directory Provisioning: Structured a dedicated server infrastructure folder repository tracking mechanism labeled `CorporateData` inside the home profile hierarchy space.
* >> Terminal Content Packaging: Deployed an interactive terminal text utility editor (Nano) to construct an assets inventory manifest matrix (`inventory.txt`) natively with zero desktop graphical tools.
* >> Shell Profile Calibration: Customized persistent user environment scripts (`~/.bashrc`) by programmatically appending a custom command-line alias shortcut rule (`gotodata`), establishing seamless workspace navigation automation across remote terminal sessions.
