# SnowHaze Windows VPN Client Installer and Packages Config

This repository hosts the installer files for the Windows VPN client for SnowHaze VPN. The installer files are only needed for distributing the VPN client, but not for building it from source. Check [this repository](https://github.com/snowhaze/desktop-vpn-client) for the client's source code. 

SnowHaze is on a mission to protect your online privacy. Hide your true IP address, encrypt your traffic, and change your virtual location with SnowHaze VPN. Our Zero-Knowledge Auth protocol uses asymmetric encryption and random tokens to provide the first anonymous VPN authorization. From registration, over payment, up to usage, every step is designed for privacy.

SnowHaze also offers other products for privacy protection such as the SnowHaze iOS browser & VPN client and the SnowHaze Firefox extension. More details about SnowHaze and Zero-Knowledge Auth can be found on the [SnowHaze website](https://snowhaze.com/).

Get the SnowHaze Firefox extension for free from [Mozilla](https://addons.mozilla.org/en-US/firefox/addon/snowhaze/).

Get SnowHaze on iOS for free from the [App Store](https://snowhaze.com/download).

## License

This Installer and Packages Config is licensed under the GPL v3 license.

Disclaimer: The GPL license is *not* a free license and GPL licensed software is *not* free software. The GPL license restricts your rights to use software heavily. It is designed specifically to be incompatible with many other licenses and because of this we are bound to use the GPL license. Since the GPL license confines you to the GPL ecosystem, it contradicts the very essence of free software and thus we do not endorse it.

## Getting Started

This repository contains only the config files to create the SnowHaze VPN Installer for Windows. The easiest way to get the SnowHaze VPN client itself is to download it from [our website](https://snowhaze.com/en/download.html#get-vpn-client).

To create the SnowHaze VPN Installer perform the following steps:

1. Clone this repository

2. Add to the folder `\packages\ch.illotros.snowhazevpn` a folder with the name '\data'. In this newly created folder `\packages\ch.illotros.snowhazevpn\data` add the binary of the SnowHaze VPN client. Be aware that you have to add the build of the SnowHaze VPN client. The build instructions you can find in the [SnowHaze VPN client repository](https://github.com/snowhaze/desktop-vpn-client).

3. Run the following command:
`binarycreator.exe -c \config\config.xml -p \packages SnowHazeVPNInstaller`

The `binarycreator.exe` is part of the Qt Installer Framework. The path relative to the Qt installation folder is usually the following (This example uses the QtInstallerFramework version 3.2):
	`Qt\Tools\QtInstallerFramework\3.2\bin\binarycreator.exe`

## Versioning

This is not our working repository and we only push versions to this repository that will be released.


## Contributing

Please get in touch with us if you would like to contribute to any of our projects. We would love to have you on board with us! As this is not our working repository, we cannot accept pull-requests on this repository.

## Support

Do not hesitate to [contact us](https://snowhaze.com/en/support-contact.html) if you have any questions.


## Authors

SnowHaze was created by Illotros GmbH, all rights reserved.
