---
title: "RawColorHelper.CreateArgb16BitColor"
second_title: "Aspose.PSD for .NET API 参考"
description: "RawColorHelper 方法。创建每通道 16 位的 ARGB 颜色"
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

创建每通道 16 位的 ARGB 颜色。

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | UInt16 | Alpha 组件的值 (0-65535)。 |
| r | UInt16 | Red 组件的值 (0-65535)。 |
| g | UInt16 | Green 组件的值 (0-65535)。 |
| b | UInt16 | Blue 组件的值 (0-65535)。 |

### 返回值

一个新的 [`RawColor`](../../rawcolor/) 实例，表示 ARGB 颜色。

## 备注

颜色组件按以下顺序打包到 64 位整数中：alpha（第 48-63 位），red（第 32-47 位），green（第 16-31 位），以及 blue（第 0-15 位）。

### 另请参阅

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


