---
title: "PattResourceData.SetPattern"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método PattResourceData. Establece el búfer de píxeles del patrón y el tamaño objetivo, actualiza Width / Height y almacena los datos para guardarlos usando el modo de compresión predeterminado 0."
type: docs
weight: 110
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/setpattern/
---
{{< psd/tize >}}
## PattResourceData.SetPattern method

Establece el búfer de píxeles del patrón y el tamaño objetivo, actualiza [`Width`](../width/) / [`Height`](../height/), y almacena los datos para guardarlos usando el modo de compresión predeterminado (0).

```csharp
public void SetPattern(int[] pixels, Rectangle bounds)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | Int32[] | Píxeles de 32 bits en formato `0xAARRGGBB`. |
| límites | Rectangle | Límites de píxeles del patrón. |

### Excepciones

| excepción | condición |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | La longitud del arreglo de píxeles debe ser igual al área de los límites. |

### Ver también

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [PattResourceData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


