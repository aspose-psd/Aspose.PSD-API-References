---
title: "ImageExtensions.ToGdiImage"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo ImageExtensions. Converte l'Image nella Image"
type: docs
weight: 10
url: /it/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Converte l'Image nella Image.

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| immagine | Immagine | L'Image da convertire. |

### Valore di ritorno

L'Image convertita.

## Osservazioni

Attenzione, l'immagine GDI potrebbe avere limiti inferiori rispetto a *image*. Per ottenere tutte le parti dell'immagine utilizzare un metodo di estensione più sicuro, ToGdiImageFull.

### Vedi anche

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


