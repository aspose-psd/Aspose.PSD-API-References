---
title: RawColorHelper.CreateArgb16BitColor
second_title: Aspose.PSD for .NET API Reference
description: RawColorHelper method. Creates a 16bit per channel ARGB color
type: docs
weight: 20
url: /net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

Creates a 16-bit per channel ARGB color.

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| Parameter | Type | Description |
| --- | --- | --- |
| a | UInt16 | The alpha component value (0-65535). |
| r | UInt16 | The red component value (0-65535). |
| g | UInt16 | The green component value (0-65535). |
| b | UInt16 | The blue component value (0-65535). |

### Return Value

A new [`RawColor`](../../rawcolor/) instance representing the ARGB color.

## Remarks

The color components are packed into a 64-bit integer in the order: alpha (bits 48-63), red (bits 32-47), green (bits 16-31), and blue (bits 0-15).

### See Also

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


