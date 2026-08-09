---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Aspose.PSD for .NET API 参考"
description: "RawColorHelper 方法。创建每通道 8 位的 ARGB 颜色"
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

创建每通道 8 位的 ARGB 颜色。

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | 字节 | Alpha 分量值 (0-255)。 |
| r | 字节 | 红色分量值 (0-255)。 |
| g | 字节 | 绿色分量值 (0-255)。 |
| b | 字节 | 蓝色分量值 (0-255)。 |

### 返回值

一个新的 [`RawColor`](../../rawcolor/) 实例，表示 ARGB 颜色。

## 备注

颜色分量按以下顺序打包到 32 位整数中：Alpha（位 24-31）、红色（位 16-23）、绿色（位 8-15）以及蓝色（位 0-7）。

### 另请参阅

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

从 Drawing.Color 创建每通道 8 位的 ARGB 颜色

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| drawingColor | 颜色 | 该 System.Drawing Color |

### 返回值

一个新的 [`RawColor`](../../rawcolor/) 实例，表示 ARGB 颜色。

## 备注

颜色分量按以下顺序打包到 32 位整数中：Alpha（位 24-31）、红色（位 16-23）、绿色（位 8-15）以及蓝色（位 0-7）。

### 另请参阅

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


