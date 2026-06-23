---
title: RawColorHelper.CreateArgb8BitColor
second_title: Aspose.PSD for .NET API Reference
description: RawColorHelper method. Creates an 8bit per channel ARGB color
type: docs
weight: 30
url: /net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

Creates an 8-bit per channel ARGB color.

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| Parameter | Type | Description |
| --- | --- | --- |
| a | Byte | The alpha component value (0-255). |
| r | Byte | The red component value (0-255). |
| g | Byte | The green component value (0-255). |
| b | Byte | The blue component value (0-255). |

### Return Value

A new [`RawColor`](../../rawcolor/) instance representing the ARGB color.

## Remarks

The color components are packed into a 32-bit integer in the order: alpha (bits 24-31), red (bits 16-23), green (bits 8-15), and blue (bits 0-7).

### See Also

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

Creates an 8-bit per channel ARGB color from Drawing.Color

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| drawingColor | Color | The System.Drawing Color |

### Return Value

A new [`RawColor`](../../rawcolor/) instance representing the ARGB color.

## Remarks

The color components are packed into a 32-bit integer in the order: alpha (bits 24-31), red (bits 16-23), green (bits 8-15), and blue (bits 0-7).

### See Also

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


