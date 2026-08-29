---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Aspose.PSD for .NET API 参考"
description: "RawColorHelper 方法。创建每通道 8 位的 CMYK 颜色"
type: docs
weight: 50
url: /zh/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

创建每通道 8 位的 CMYK 颜色。

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | 字节 | Cyan 组件的值 (0-255)。 |
| m | 字节 | Magenta 组件的值 (0-255)。 |
| y | 字节 | Yellow 组件的值 (0-255)。 |
| k | 字节 | Key（黑色）组件的值 (0-255)。 |

### 返回值

一个新的 [`RawColor`](../../rawcolor/) 实例，表示 CMYK 颜色。

## 备注

颜色组件按以下顺序打包到 32 位整数中：cyan（第 24-31 位），magenta（第 16-23 位），yellow（第 8-15 位），以及 key/black（第 0-7 位）。

### 另请参阅

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


