# Data Security, ITAR and EAR Compliance

Export Controlled Research includes information that is regulated for reasons of national security, foreign policy, anti-terrorism, or non-proliferation. The *International Traffic in Arms Regulations (ITAR)* and *Export Administration Regulations (EAR)* govern this data type. Current law requires that this data be stored in the U.S and that only authorized U.S. persons be allowed access to it.

Export Controls are federal laws that govern how technology, technical data, technical assistance, and items or materials (from software to satellites and more) are physically or electronically exported, shipped, transmitted, transferred, or shared from the U.S. to foreign countries, persons, or entities.

Protecting sensitive data is a shared responsibility. You are responsible for ensuring that your use of permitted services complies with laws, regulations, and policies where applicable.

## Data Types Included in EAR and ITAR Scope
* Data at Rest (Laptops, desktops, USB Devices, Offsite Backup, Databases, etc.)
* Data in Motion (Emails, File Transfers, Web Traffic, etc.)
* Data in Use (SharePoint, Private Cloud, File & Application Servers, Database, etc.)

## Working with Export-Controlled Data

#### Access Controls
* Do not access export-controlled information from shared, public computers such as kiosk-type computers in libraries, hotels, and business centers, or from computers that have no local access control.

* Do not post export-controlled information on public websites or websites that rely solely on IP addresses for access control.  Instead, secure access using individually-assigned accounts requiring username/password, user certificates, or other user-specific authentication methods.

* Protect export-controlled information by at least one physical and one logical barrier (e.g. locked container or room and login and password) when not under direct individual control.

#### Transmission of ITAR covered data
* Do not transmit or email Controlled Information unencrypted. An alternative to email is to put the files in a secure location (e.g. AWS GovCloud) and send an authenticated link in a message to whomever needs access to the file.

* Wireless network access to Controlled Information must be encrypted using, e.g., WPA2 Enterprise wireless network encryption or VPN.

* Do not transmit data over a non-Atomos, open, community, coffee shop, or library wi-fi network without the use of a VPN.

#### Laptops
The data must be stored on a Atomos Space-owned and managed single-user laptop device using whole disk encryption (e.g. FileVault2 for Mac, BitLocker for Windows, LUKS for Linux) with a unique decryption passphrase known only to the device's authorized primary user.

#### Storing ITAR covered data
Export-controlled data is stored only on devices listed in the IT Security Plan.

If the export-controlled data cannot be encrypted at rest using an electronic barrier, a physical barrier must be implemented (e.g. locked rack, storage safe, etc.).

## Permitted Storage Resources

*Amazon Web Services - Government Cloud*
AWS-GovCloud provides variety of cloud-based infrastructure services (storage, database, computing) and is physically located in the United States and is staffed by U.S. persons, which makes it compliant with Export Control regulations such as ITAR and EAR.

## Traveling with Export-Controlled Data
You may not travel outside of the United States with your Atomos Nuclear and Space provided laptop, tablets, phone, or any other associated technology. Doing so puts our hard work at risk and potentially puts you in breach of International Arms Treaties and Federal Law.

Should you need to travel internationally for work, please engage your manager or leadership to form an appropriate strategy that provides you access to the data you need while maintaining compliance with any governing policy or laws.

## Laws/Regulations/Policies
[U.S. Department of Commerce, Bureau of Industry and Security Commerce Control List](https://www.bis.doc.gov/index.php/regulations/commerce-control-list-ccl)
