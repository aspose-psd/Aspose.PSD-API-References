---
title: "ImageExtensions.ToGdiImage"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método ImageExtensions. Convierte la Imagen a la Imagen"
type: docs
weight: 10
url: /es/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Convierte la Image a la Image.

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | Image | La Image a convertir. |

### Valor devuelto

La Image convertida.

## Observaciones

Advertencia, la imagen GDI puede obtener límites inferiores a los que tiene *image*. Para obtener todas las partes de la imagen use un método de extensión más seguro ToGdiImageFull.

### Ver también

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


