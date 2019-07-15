# Data Security, ITAR and EAR Compliance

Export Controlled Research includes information that is regulated for reasons of national security, foreign policy, anti-terrorism, or non-proliferation. The *International Traffic in Arms Regulations (ITAR)* and *Export Administration Regulations (EAR)* govern this data type. Current law requires that this data be stored in the U.S and that only authorized U.S. persons be allowed access to it.

Export Controls are federal laws that govern how technology, technical data, technical assistance, and items or materials (from software to satellites and more) are physically or electronically exported, shipped, transmitted, transferred, or shared from the U.S. to foreign countries, persons, or entities.

Protecting sensitive data is a shared responsibility. You are responsible for ensuring that your use of permitted services complies with laws, regulations, and policies where applicable.

## Data Types Included in EAR and ITAR Scope
* Data at Rest (Laptops, desktops, USB Devices, Offsite Backup, Databases, etc.)
* Data in Motion (Emails, File Transfers, Web Traffic, etc.)
* Data in Use (SharePoint, Private Cloud, File & Application Servers, Database, etc.)

## Working with Data

#### Access Controls
* Do not access export-controlled information from shared, public computers such as kiosk-type computers in libraries, hotels, and business centers, or from computers that have no local access control.

* Do not post export-controlled information on public websites or websites that rely solely on IP addresses for access control.  Instead, secure access using individually-assigned accounts requiring username/password, user certificates, or other user-specific authentication methods.

* Protect export-controlled information by at least one physical and one logical barrier (e.g. locked container or room and login and password) when not under direct individual control.


#### Transmission of ITAR covered data
* Do not transmit or email Controlled Information unencrypted. An alternative to email is to put the files in a secure location (e.g. SFTP site) and send an authenticated link in a message to whomever needs access to the file (as specified in the TCP).

* Wireless network access to Controlled Information must be encrypted using, e.g., WPA2 Enterprise wireless network encryption or VPN.

#### Laptops
The data must be stored on a Atomos Space-owned and managed single-user laptop device using whole disk encryption (e.g. FileVault2 for Mac, BitLocker for Windows, LUKS for Linux) with a unique decryption passphrase known only to the device's authorized primary user.

#### Storing ITAR covered data
Export-controlled data is stored only on devices listed in the IT Security Plan.

If the export-controlled data cannot be encrypted at rest using an electronic barrier, a physical barrier must be implemented (e.g. locked rack, storage safe, etc.).

## Permitted Resources

*Amazon Web Services - Government Cloud*
AWS-GovCloud provides variety of cloud-based infrastructure services (storage, database, computing) and is physically located in the United States and is staffed by U.S. persons, which makes it compliant with Export Control regulations such as ITAR and EAR.

## Laws/Regulations/Policies
[U.S. Department of Commerce, Bureau of Industry and Security Commerce Control List](https://www.bis.doc.gov/index.php/regulations/commerce-control-list-ccl)
