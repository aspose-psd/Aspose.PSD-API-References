---
title: RawColorHelper.CreateCmyk8BitColor
second_title: Aspose.PSD for .NET API Reference
description: RawColorHelper method. Creates an 8bit per channel CMYK color
type: docs
weight: 50
url: /net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

Creates an 8-bit per channel CMYK color.

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| Parameter | Type | Description |
| --- | --- | --- |
| c | Byte | The cyan component value (0-255). |
| m | Byte | The magenta component value (0-255). |
| y | Byte | The yellow component value (0-255). |
| k | Byte | The key (black) component value (0-255). |

### Return Value

A new [`RawColor`](../../rawcolor/) instance representing the CMYK color.

## Remarks

The color components are packed into a 32-bit integer in the order: cyan (bits 24-31), magenta (bits 16-23), yellow (bits 8-15), and key/black (bits 0-7).

### See Also

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


