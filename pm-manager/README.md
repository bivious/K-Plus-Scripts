### Introduction

Welcome this is an alpha package for the PM Manager Addon.

The PM Manager is a user manageable global private message blocker for KVIrc.
The PM Manager has a simple UI to whitelist users temporarily or permanently, or
via a simple context menu entry.

The PM Manager notifies you and blocked users of any blocked PMs by default and
allows you in addition to the pre-configured default message, to configure your
own personalized notification message to send to users instead.

### Todo

* Package as a native KVIrc addon for single file destribution.
* Bump version to beta at some stage? 

### Install

Once you have extracted the package.
* Via the scripting Menu Entry and select `Execute Script`
* Via ```Ctrl+Shift+X``` navigate to location you extracted the addon
  then select the ```install.kvs`` file and click open.

You should see the following lines:

```
Attempting to register addon "PM Manager" with version 1.0.0
Addon successfully registered
PM Manager Addon Version - 1.0.0  Initialization Complete.
```

### Uninstall
Use the `Manage Addons` under Settings menu entry in KVIrc to remove the PM Manager.

### Screenshots

##### PM Manager -  Main Dialog
![pm-manager-main-dialog](./pmm-help/images/pmmanager.png "PM Manager - Main Dialog")

##### PM Manager - Options Setup Dialog
![pm-manager-options-setup-dialog](./pmm-help/images/pmsetup.png "PM Manager - Options Setup Dialog")

### Usage

It has 2 popup menus, just right-click in channel or right-click on user-name or
in query window to target user that you initiate.

The in channel context menu entry is for PM Manager controls.
The username/query context menu entry allows whitelist temporary/permanent users.

### License

[![PM Manager GPLv2+](https://img.shields.io/badge/%20%20PM_Manager%20%20-%20GPLv2+%20-blue.svg)](LICENCE)
