# Umbraco Package Actions #

----------

**Collection of useful package actions for Umbraco package devs**

![](logo.png)

[![Build status](https://ci.appveyor.com/api/projects/status/njlw9k7crcaq2uhw?svg=true)](https://ci.appveyor.com/project/TimGeyssens/umbracopagenotfoundmanager)

# Overview #
## Transform Config ##
Uses xdt to transform config and xml files so this can be used for a lot of things like adding app settings to the web.config, adding entries to other config files, updates attributes... You need to specify source file you wish to update and the xdt file that will be used for the tranformation

    <Action 
		runat="install" undo="false" alias="Nibble.TransformConfig" 
		file="~/config/embeddedmedia.config" 
		xdtfile="~/app_plugins/temp/embeddedmedia.xdt"></Action>

### Test site ###
Backoffice credentials: 
- tim@nibble.be / password


