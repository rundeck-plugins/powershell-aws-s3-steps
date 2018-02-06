# AWS S3 Powershell plugin

Powershell wrapper around AWS S3 SDK to expose subcommands as node steps.

## Build

Run gradle build to build the zip file

## Install

Copy the zip file to the %RDECK_BASE\libext folder

## Requierments

This plugin needs that AWS SDK for Powershell to be installed on the Rundeck Server and the remote nodes. To install AWS SDK for Powershell you can:

* Use the MSI installer: [https://aws.amazon.com/powershell](https://aws.amazon.com/powershell/)
* Install the module on a Powershell console: `Install-Module -Name AWSPowerShell` 

Further information about the AWS SDK: 
[https://docs.aws.amazon.com/powershell/latest/userguide/pstools-getting-set-up-windows.html](https://docs.aws.amazon.com/powershell/latest/userguide/pstools-getting-set-up-windows.html)
