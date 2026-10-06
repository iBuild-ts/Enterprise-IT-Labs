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
