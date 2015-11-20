# PAM oxD

> This is in planning stage and is a placeholder repository until development starts

A Linux PAM module to provide authentication services using oxD.

## Prerequisites

PAM oxD is written in Python hence requires pam-python.

```
$ sudo apt-get install libpam-python libpam0g-dev
```

All the commuication happens through the oxD server and the oxd-python library. Refer to [oxd-python](https://github.com/GluuFederation/oxd-python) readme to setup oxd-python.

```
$ sudo apt-get install gluu-oxd-server
```

## Development

```
$ git clone https://github.com/GluuFederation/pam_oxd.git
$ virtualenv env
$ source env/bin/activate
```
