---
title: doWipeProtectedMethod method of the MDM_RemoteWipe class
description: Triggers the device to start the remote wipe on the device, and fully clean the internal drive. In some device configurations, this command might leave the device unable to boot.
keywords:
- doWipeProtectedMethod method
- doWipeProtectedMethod method, MDM_RemoteWipe class
- MDM_RemoteWipe class, doWipeProtectedMethod method
topic_type:
- apiref
api_name:
- MDM_RemoteWipe.doWipeProtectedMethod
api_location:
- DMWmiBridgeProv.dll
api_type:
- COM
ms.topic: reference
ms.date: 09/17/2021
---

# doWipeProtectedMethod method of the MDM_RemoteWipe class

Triggers the device to start the remote wipe on the device, and fully clean the internal drive. In some device configurations, this command might leave the device unable to boot. Also see [doWipePersistProvisionedDataMethod](/windows/client-management/mdm/remotewipe-csp).

## Syntax

```mof
uint32 doWipeProtectedMethod(
  [in] string param
);
```

## Parameters

<dl> <dt>

*param* \[in\]
</dt> <dd></dd> </dl>

## Requirements

| Requirement | Value |
|-------------------------------------|------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 10 \[desktop apps only\]<br/>                                                    |
| Minimum supported server<br/> | None supported<br/>                                                                      |
| Namespace<br/>                | Root\\CIMv2\\MDM\\DMMap<br/>                                                             |
| MOF<br/>                      | <dl> <dt>DMWmiBridgeProv.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>DMWmiBridgeProv.dll</dt> </dl> |

## See also

<dl> <dt>

[**MDM\_RemoteWipe**](mdm-remotewipe.md)
</dt> <dt>

[Using PowerShell scripting with the WMI Bridge Provider](/windows/client-management/mdm/using-powershell-scripting-with-the-wmi-bridge-provider)
</dt> </dl>
