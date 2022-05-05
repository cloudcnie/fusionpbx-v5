What is [FusionPBX](https://www.fusionpbx.com/)?
--------------------------------------

[FusionPBX](https://www.fusionpbx.com/) can be used as a single or domain based multi-tenant PBX, carrier grade switch, call center server, fax server, VoIP server, voicemail server, conference server, voice application server, multi-tenant appliance framework and more. [FreeSWITCH™](https://freeswitch.com) is a highly scalable, multi-threaded, multi-platform communication platform. 

It provides the functionality your business needs and brings carrier grade switching, and corporate-level phone system features to small, medium, and large businesses. Read more at [FusionPBX](https://www.fusionpbx.com/). [Please visit our youtube channel](https://www.youtube.com/FusionPBX)

In addition to providing all of the usual PBX functionality, FusionPBX allows you to configure:

- Multi-Tenant
- Unlimited Extensions
- Voicemail-to-Email
- Device Provisioning
- Music on Hold
- Call Parking
- Automatic Call Distribution
- Interactive Voice Response
- Ring Groups
- Find Me / Follow Me
- Hot desking
- High Availability and Redundancy
- Dialplan Programming that allow nearly endless possibilities
- [Many other Features](https://docs.fusionpbx.com/en/latest/features/features.html)

Software Requirements
--------------------------------------

- FusionPBX will run on Debian 9 & 10, Ubuntu 18.04 LTS, FreeBSD 10 & 11, CentOS, and more.
- [FusionPBX Installer](https://www.fusionpbx.com/download.php)

How to Install FusionPBX
----------------------------
* As root do the following:

Debian Install
```
wget -O - https://raw.githubusercontent.com/fusionpbx/fusionpbx-install.sh/master/debian/pre-install.sh | sh;
cd /usr/src/fusionpbx-install.sh/debian && ./install.sh
```

Ubuntu Install
```
wget -O - https://raw.githubusercontent.com/fusionpbx/fusionpbx-install.sh/master/ubuntu/pre-install.sh | sh;
cd /usr/src/fusionpbx-install.sh/ubuntu && ./install.sh
```

FreeBSD Install
```
pkg install --yes git
cd /usr/src && git clone https://github.com/fusionpbx/fusionpbx-install.sh.git
cd /usr/src/fusionpbx-install.sh/freebsd && ./install.sh
```

CentOS Install
```
yum install wget
wget -O - https://raw.githubusercontent.com/fusionpbx/fusionpbx-install.sh/master/centos/pre-install.sh | sh
cd /usr/src/fusionpbx-install.sh/centos && ./install.sh
```

This install script is designed to be an fast, simple, and in a modular way to install FusionPBX. Start with a minimal install of Debian 10 with SSH enabled. Run the following commands under root. The script installs FusionPBX, FreeSWITCH release package and its dependencies, IPTables, Fail2ban, NGINX, PHP FPM and PostgreSQL.

Some installations require special considerations. Visit https://github.com/fusionpbx/fusionpbx-install.sh readme section for more details.

### ISSUES
If you find a bug sign up for an account on [www.fusionpbx.com](https://www.fusionpbx.com) to report the issue.

---

<a href="url"><img src="https://www.fusionpbx.com/app/account/resources/images/member_emblem_xl_blue.png" align="center" height="350" width="240" ></a>

