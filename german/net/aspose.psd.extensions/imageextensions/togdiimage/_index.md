---
title: "ImageExtensions.ToGdiImage"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ImageExtensions-Methode. Konvertiert das Image in das Image."
type: docs
weight: 10
url: /de/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Konvertiert das Image in das Image.

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | Image | Das Image zum Konvertieren. |

### Rückgabewert

Das konvertierte Image.

## Hinweise

Warnung, das GDI-Image kann geringere Grenzen haben als *image* hat. Um alle Teile des Images zu erhalten, verwenden Sie die sicherere Erweiterungsmethode ToGdiImageFull.

### Siehe auch

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


