# CSZ CMS XSS in install page
**Software link**: CSZ CMS [https://www.cszcms.com/]
**Version**: 1.3.0

**@author**: Alejandro Amorín

**Description**: CSZ CMS 1.3.0 and below is affected by a Cross-site scripting (XSS) vulnerability in install/index.php that allows remote remote attackers to inject arbitrary web script or HTML via the 'Database Username' or 'Database Host' parameters.

## POC

When performing the installation and selecting the database to install the appliance, the 'Database Username' and the 'Database Host' fields are affected by the injection of arbitrary code:

![xss1](https://github.com/al3zx/csz_cms_1_3_0_xss_in_install_page/assets/20266218/ebe056f7-5bc9-4d10-96a6-3e1a930d3d42)

![xss2](https://github.com/al3zx/csz_cms_1_3_0_xss_in_install_page/assets/20266218/acf57ff8-4394-4101-ae88-2a26d711d89c)

![xss3](https://github.com/al3zx/csz_cms_1_3_0_xss_in_install_page/assets/20266218/49bfc80a-1296-4ef0-a346-33c123781a0e)

![xss4](https://github.com/al3zx/csz_cms_1_3_0_xss_in_install_page/assets/20266218/44d5e52a-fadc-4d00-b04a-10f6bea62bbd)
