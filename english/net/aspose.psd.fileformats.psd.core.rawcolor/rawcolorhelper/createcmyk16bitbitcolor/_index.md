---
title: RawColorHelper.CreateCmyk16BitBitColor
second_title: Aspose.PSD for .NET API Reference
description: RawColorHelper method. Creates a 16bit per channel CMYK color
type: docs
weight: 40
url: /net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

Creates a 16-bit per channel CMYK color.

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| Parameter | Type | Description |
| --- | --- | --- |
| c | UInt16 | The cyan component value (0-65535). |
| m | UInt16 | The magenta component value (0-65535). |
| y | UInt16 | The yellow component value (0-65535). |
| k | UInt16 | The key (black) component value (0-65535). |

### Return Value

A new [`RawColor`](../../rawcolor/) instance representing the CMYK color.

## Remarks

The color components are packed into a 64-bit integer in the order: cyan (bits 48-63), magenta (bits 32-47), yellow (bits 16-31), and key/black (bits 0-15).

### See Also

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


