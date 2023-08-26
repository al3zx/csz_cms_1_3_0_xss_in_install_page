# CSZ CMS XSS in install page

## Author: Alejandro Amorín

**Software link**: CSZ CMS [https://www.cszcms.com/]
**Version**: 1.3.0

**Description**: CSZ CMS 1.3.0 is affected by a cross-site scripting (XSS) feature that allows attackers to execute arbitrary web scripts or HTML via a crafted payload entered in the installation page in 'Database Username' and 'Database Host' fields.

## POC

When performing the installation and selecting the database to install the appliance, the 'Database Username' and the 'Database Host' fields are affected by the injection of arbitrary code:





