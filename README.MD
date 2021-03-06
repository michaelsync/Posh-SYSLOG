# Posh-SYSLOG

## Description

A module for sending SYSLOG messages from PowerShell.

The module supports RFC5424 and RFC3164, and can send messages via TCP and UDP.

Authored by Kieran Jacobsen

## Installing

The easiest way to get Posh-SYSLOG is using the [PowerShell Gallery](https://powershellgallery.com/packages/Posh-SYSLOG/)!

### Inspecting the module

Best practice is that you inspect modules prior to installing them. You can do this by saving the module to a local path:

``` PowerShell
PS> Save-Module -Name Posh-SYSLOG -Path <path>
```

### Installing the module

Once you trust a module, you can install it using:

``` PowerShell
PS> Install-Module -Name Posh-SYSLOG
```

### Updating Posh-SYSLOG

Once installed from the PowerShell Gallery, you can update it using:

``` PowerShell
PS> Update-Module -Name Posh-SYSLOG
```

### Removing Posh-SYSLOG

To remove Posh-SYSLOG:

``` PowerShell
PS> Uninstall-Module -Name Posh-SYSLOG
```

## License

Posh-SYSLOG is provided under the [MIT license](LICENSE.MD).