# 01 Installing the Domain Controller

1. Use `SConfig` to:
    - Change the hostname
    - Change the IP address to static
    - Chang the DNS server to our own IP address

2. Install the Active Directory Windows Feature

```shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
```