---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Aspose.PSD for .NET API 参考"
description: "RawColorHelper 方法。创建每通道 16 位的 CMYK 颜色"
type: docs
weight: 40
url: /zh/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

创建每通道 16 位的 CMYK 颜色。

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | UInt16 | 青色分量值 (0-65535)。 |
| m | UInt16 | 品红分量值 (0-65535)。 |
| y | UInt16 | 黄色分量值 (0-65535)。 |
| k | UInt16 | 键（黑）分量值 (0-65535)。 |

### 返回值

一个新的 [`RawColor`](../../rawcolor/) 实例，表示 CMYK 颜色。

## 备注

颜色分量按以下顺序打包到 64 位整数中：青色（位 48-63）、品红（位 32-47）、黄色（位 16-31）以及键/黑色（位 0-15）。

### 另请参阅

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


