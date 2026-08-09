---
title: "枚举 DataRecoveryMode"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.DataRecoveryMode 枚举。数据恢复模式。"
type: docs
weight: 740
url: /zh/net/aspose.psd/datarecoverymode/
---
{{< psd/tize >}}
## DataRecoveryMode enumeration

数据恢复模式。

```csharp
public enum DataRecoveryMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 不暗示数据恢复。每当文件格式出现损坏数据时，将抛出相应的异常。 |
| ConsistentRecover | `1` | 一致恢复模式会尝试恢复所有数据，只要损坏未破坏文件格式并允许正确的后续处理。 |
| MaximalRecover | `2` | 最大恢复模式即使文件格式结构已损坏，也会恢复所有数据，进一步处理可能会产生未预期的效果。 |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


