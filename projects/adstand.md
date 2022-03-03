---
description: ADStand is a set of scripts for setting up a Active Directory test stand.
---

# ADStand

## About

ADStand is a set of scripts for setting up a Active Directory test stand.

#### InitAD.ps1

* create domain test.local with Administrator password Qwerty12345

#### InitTESTOrganization.ps1

* add users, computers and groups
* add service account (Kerberoast, AS-REP roasting)

#### RemoveTESTOrganization.ps1

* this script deletes everything that was added through the script InitTESTOrganization.ps1

Tested on Windows Server Standard 2016

Change the "$CountUser" parameter value if you want add more users.

If you want to install on a different version of the system then change the "$DomainMode" parameter value in the script to the appropriate ones:

* Windows Server 2003: 2 or Win2003
* Windows Server 2008: 3 or Win2008
* Windows Server 2008 R2: 4 or Win2008R2
* Windows Server 2012: 5 or Win2012
* Windows Server 2012 R2: 6 or Win2012R2
* Windows Server 2016: 7 or WinThreshold

## Usage

Example: `.\InitAD.ps1` or `powershell .\InitAD.ps1`

{% embed url="https://github.com/Ping-P0ng/ADStand" %}
