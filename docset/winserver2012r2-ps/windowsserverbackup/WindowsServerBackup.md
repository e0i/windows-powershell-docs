---
author: andreabarr
description: 
Download Help Link: https://aka.ms/winsvr-2012r2-pshelp
Help Version: 4.0.4.0
Locale: en-US
manager: jasgro
Module Guid: d27a5d7a-8b1d-4b0a-809d-65ef33ee2f2d
Module Name: WindowsServerBackup
ms.author: v-anbarr
ms.date: 10/30/2017
ms.prod: powershell
ms.reviewer: brianlic
ms.technology: powershell
ms.topic: reference
title: WindowsServerBackup
---

# WindowsServerBackup Module
## Description
This reference provides cmdlet descriptions and syntax for all Windows Server Backup cmdlets. It lists the cmdlets in alphabetical order based on the verb at the beginning of the cmdlet.

## WindowsServerBackup Cmdlets
### [Add-WBBackupTarget](./Add-WBBackupTarget.md)
Adds a backup target to a backup policy.

### [Add-WBBareMetalRecovery](./Add-WBBareMetalRecovery.md)
Adds items to a backup policy so that backups that use the policy can perform bare metal recoveries.

### [Add-WBFileSpec](./Add-WBFileSpec.md)
Adds a backup file specification to a backup policy.

### [Add-WBSystemState](./Add-WBSystemState.md)
Adds the system state components to the backup policy.

### [Add-WBVirtualMachine](./Add-WBVirtualMachine.md)
Adds a list of virtual machines to the backup policy.

### [Add-WBVolume](./Add-WBVolume.md)
Adds the list of source volumes to the backup policy.

### [Get-WBBackupSet](./Get-WBBackupSet.md)
Gets backups for a server from a location that you specify.

### [Get-WBBackupTarget](./Get-WBBackupTarget.md)
Gets backup storage locations that you specified as part of a backup policy.

### [Get-WBBackupVolumeBrowsePath](./Get-WBBackupVolumeBrowsePath.md)
Mounts a volume inside a backup so that you can browse the files on the volume.

### [Get-WBBareMetalRecovery](./Get-WBBareMetalRecovery.md)
Indicates whether or not a backup policy can perform bare metal recoveries from backups.

### [Get-WBDisk](./Get-WBDisk.md)
Gets a list of internal and external disks that are online for the local computer.

### [Get-WBFileSpec](./Get-WBFileSpec.md)
Gets the list of backup file specifications associated with a backup policy.

### [Get-WBJob](./Get-WBJob.md)
Gets the current backup operation.

### [Get-WBPerformanceConfiguration](./Get-WBPerformanceConfiguration.md)
Retrieves the current volume backup performance settings.

### [Get-WBPolicy](./Get-WBPolicy.md)
Retrieves the current backup policy for the computer.

### [Get-WBSchedule](./Get-WBSchedule.md)
Retrieves the current schedule for backups.

### [Get-WBSummary](./Get-WBSummary.md)
Retrieves the history of backup operations on the computer.

### [Get-WBSystemState](./Get-WBSystemState.md)
Gets a Boolean value that indicates whether system state recovery was added to the backup policy.

### [Get-WBVirtualMachine](./Get-WBVirtualMachine.md)
Gets all virtual machines and components from the backup policy.

### [Get-WBVolume](./Get-WBVolume.md)
Retrieves a list of volumes.

### [Get-WBVssBackupOption](./Get-WBVssBackupOption.md)
Retrieves a VSS setting from the backup policy.

### [New-WBBackupTarget](./New-WBBackupTarget.md)
Creates a backup target object.

### [New-WBFileSpec](./New-WBFileSpec.md)
Creates a backup file specification.

### [New-WBPolicy](./New-WBPolicy.md)
Creates a backup policy object.

### [Remove-WBBackupSet](./Remove-WBBackupSet.md)
Deletes backups from a target catalog, a system catalog, or both.

### [Remove-WBBackupTarget](./Remove-WBBackupTarget.md)
Removes backup storage locations from a backup policy.

### [Remove-WBBareMetalRecovery](./Remove-WBBareMetalRecovery.md)
Removes a request to include items that implement bare metal recovery from the current backup policy.

### [Remove-WBCatalog](./Remove-WBCatalog.md)
Removes the backup catalog from the local computer.

### [Remove-WBFileSpec](./Remove-WBFileSpec.md)
Removes a backup file specification from a backup policy.

### [Remove-WBPolicy](./Remove-WBPolicy.md)
Removes the backup policy.

### [Remove-WBSystemState](./Remove-WBSystemState.md)
Removes the system state components from the backup policy.

### [Remove-WBVirtualMachine](./Remove-WBVirtualMachine.md)
Removes the list of virtual machines from the backup policy.

### [Remove-WBVolume](./Remove-WBVolume.md)
Removes the volume from the backup policy.

### [Restore-WBCatalog](./Restore-WBCatalog.md)
Recovers a backup catalog for the local computer from a storage location.

### [Resume-WBBackup](./Resume-WBBackup.md)
Resumes a backup operation to a removable device after you add media to the device.

### [Resume-WBVolumeRecovery](./Resume-WBVolumeRecovery.md)
Resumes a volume recovery operation from a removable device and specific media.

### [Set-WBPerformanceConfiguration](./Set-WBPerformanceConfiguration.md)
Sets the current volume backup performance settings.

### [Set-WBPolicy](./Set-WBPolicy.md)
Sets the backup policy for scheduled backups.

### [Set-WBSchedule](./Set-WBSchedule.md)
Sets the current schedule for backups.

### [Set-WBVssBackupOption](./Set-WBVssBackupOption.md)
Sets a value that determines the VSS setting in the backup policy.

### [Start-WBApplicationRecovery](./Start-WBApplicationRecovery.md)
Starts an application recovery operation.

### [Start-WBBackup](./Start-WBBackup.md)
Starts a one-time backup operation.

### [Start-WBFileRecovery](./Start-WBFileRecovery.md)
Starts a file recovery operation.

### [Start-WBHyperVRecovery](./Start-WBHyperVRecovery.md)
Starts recovery of a hv_win8_2 virtual machine.

### [Start-WBSystemStateRecovery](./Start-WBSystemStateRecovery.md)
Starts a system state recovery operation.

### [Start-WBVolumeRecovery](./Start-WBVolumeRecovery.md)
Starts a volume recovery operation.

### [Stop-WBJob](./Stop-WBJob.md)
Stops the current backup or recovery job.

