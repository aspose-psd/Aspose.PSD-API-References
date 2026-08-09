---
title: "ImageExtensions.ToGdiImage"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode ImageExtensions. Convertit l'Image en Image"
type: docs
weight: 10
url: /fr/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Convertit l'Image en Image.

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| image | Image | L'Image à convertir. |

### Valeur de retour

L'Image convertie.

## Remarques

Attention, l'image GDI peut avoir des limites inférieures à celles de *image*. Pour obtenir toutes les parties de l'image, utilisez la méthode d'extension plus sûre ToGdiImageFull.

### Voir aussi

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


