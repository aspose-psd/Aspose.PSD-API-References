---
title: Enum DataRecoveryMode
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.DataRecoveryMode enum. The data recovery mode
type: docs
weight: 740
url: /net/aspose.psd/datarecoverymode/
---
{{< psd/tize >}}
## DataRecoveryMode enumeration

The data recovery mode.

```csharp
public enum DataRecoveryMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No data recovery is implied. Whenever the file format has some corrupted data the appropriate exception is thrown. |
| ConsistentRecover | `1` | The consistent recovery mode tries to recover all data as long as corruption does not break the file format and allows correct further processing. |
| MaximalRecover | `2` | The maximal recovery mode recovers all data even if the file format has corrupted structure and further processing may yield unattended effects. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


