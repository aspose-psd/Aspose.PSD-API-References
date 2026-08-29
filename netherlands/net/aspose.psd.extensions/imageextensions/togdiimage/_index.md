---
title: "ImageExtensions.ToGdiImage"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "ImageExtensions-methode. Converteert de Image naar de Image"
type: docs
weight: 10
url: /nl/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Converteert de Image naar de Image.

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| afbeelding | Afbeelding | De Image om te converteren. |

### Retourwaarde

De geconverteerde Image.

## Opmerkingen

Waarschuwing, de GDI-afbeelding kan lagere grenzen hebben dan *image* heeft. Om alle delen van de afbeelding te krijgen, gebruik de veiligere extensiemethode ToGdiImageFull.

### Zie ook

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


