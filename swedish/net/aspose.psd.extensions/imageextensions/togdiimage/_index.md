---
title: "ImageExtensions.ToGdiImage"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ImageExtensions‑metod. Konverterar Image till Image"
type: docs
weight: 10
url: /sv/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Konverterar Image till Image.

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | Image | Den Image att konvertera. |

### Returvärde

Den konverterade Image.

## Anmärkningar

Varning, GDI‑bilden kan få lägre gränser än *image* har. För att få alla delar av bilden använd en säkrare extensionsmetod ToGdiImageFull.

### Se även

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


