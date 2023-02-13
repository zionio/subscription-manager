# subscription-manager

RPMs and dependencies built with Oracle Linux 8 from [https://github.com/candlepin/subscription-manager](https://github.com/candlepin/subscription-manager)

## Description

My personal repository for [subscription-manager](https://github.com/candlepin/subscription-manager) packages, simply built with [tito](https://github.com/rpm-software-management/tito) and Oracle Linux 8, to work with my Satellite platform.

The Software and related documentation are provided “AS IS” and without any warranty of any kind.

## Tested on

* Oracle Linux 8.6, 8.7
* Red Hat Satellite 6.5

## Usage

Add my [public repo](https://packagecloud.io/zionio/subscription-manager)

```bash
curl -s https://packagecloud.io/install/repositories/zionio/subscription-manager/script.rpm.sh | bash
```

and install

```bash
dnf install -y subscription-manager
```

or download [latest build](https://github.com/zionio/subscription-manager/releases) here.

## Source

[Subscription-manager](https://github.com/candlepin/subscription-manager)  
[Tito](https://github.com/rpm-software-management/tito)
