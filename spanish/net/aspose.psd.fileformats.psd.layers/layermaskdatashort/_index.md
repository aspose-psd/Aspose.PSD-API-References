---
title: "Clase LayerMaskDataShort"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort. Define la clase LayerMaskDataShort que contiene información sobre los datos de máscara en la capa del archivo PSD cuando la capa tiene solo una máscara raster o vectorial pero no ambas. De lo contrario se usa una LayerMaskDataFull. Si la capa tiene solo una máscara raster, ImageData contiene los bytes de datos de la máscara raster. Si la capa tiene solo una máscara vectorial, ImageData contiene los bytes de datos de la máscara vectorial rasterizados en caché. La longitud de los bytes de ImageData debe ser igual al ancho y alto de las propiedades MaskRectangle."
type: docs
weight: 2460
url: /es/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

Define la clase LayerMaskDataShort que contiene información sobre los datos de máscara en la capa del archivo PSD cuando la capa tiene solo una máscara raster o vectorial pero no ambas. De lo contrario, se usa una [`LayerMaskDataFull`](../layermaskdatafull/). Si la capa tiene solo una máscara raster, ImageData contiene los bytes de datos de la máscara raster. Si la capa tiene solo una máscara vectorial, ImageData contiene los bytes de datos de la máscara vectorial rasterizados (en caché). La longitud de los bytes de [`ImageData`](../layermaskdata/imagedata/) debe ser igual al ancho * alto de las propiedades [`MaskRectangle`](../layermaskdata/maskrectangle/).

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Inicializa una nueva instancia de la clase `LayerMaskDataShort`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Obtiene o establece la posición inferior de la máscara de capa. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Obtiene el tamaño de los datos de la máscara de capa. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Obtiene o establece el color predeterminado. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Obtiene o establece los indicadores de la máscara de capa. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Obtiene o establece los datos de la máscara de capa (o la máscara combinada / final si hay una máscara vector) en el archivo PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Obtiene o establece la posición izquierda de la máscara de capa. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Obtiene o establece el [`Rectangle`](../../aspose.psd/rectangle/) de la máscara de capa en el archivo PSD. Toma las propiedades izquierda, derecha, superior e inferior y crea un [`Rectangle`](../../aspose.psd/rectangle/). |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Obtiene o establece el relleno de la máscara de capa. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Obtiene o establece la posición derecha de la máscara de capa. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Obtiene o establece la posición superior de la máscara de capa. |

### Ver también

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


