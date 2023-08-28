# CSZ CMS XSS in install page
**Software link**: CSZ CMS [https://www.cszcms.com/]

**Version**: 1.3.0

**@author**: Alejandro Amorín

**Description**: CSZ CMS 1.3.0 and below is affected by a Cross-site scripting (XSS) vulnerability in install/index.php that allows remote attackers to inject arbitrary web script or HTML via the 'Database Username' or 'Database Host' parameters.

## POC

When performing the installation and selecting the database to install the appliance, the 'Database Username' and the 'Database Host' fields are affected by the injection of arbitrary code:

![xss1](https://github.com/al3zx/csz_cms_1_3_0_xss_in_install_page/assets/20266218/eda959a1-88ed-43a5-a766-622e38d92377)

![xss2](https://github.com/al3zx/csz_cms_1_3_0_xss_in_install_page/assets/20266218/2d537363-34a4-4208-8063-c591fb84fc7b)

![xss3](https://github.com/al3zx/csz_cms_1_3_0_xss_in_install_page/assets/20266218/95a3286d-7816-4291-9163-fd02d23dc38e)

![xss4](https://github.com/al3zx/csz_cms_1_3_0_xss_in_install_page/assets/20266218/553f4697-086a-4532-83ed-0dfbe132aa82)
