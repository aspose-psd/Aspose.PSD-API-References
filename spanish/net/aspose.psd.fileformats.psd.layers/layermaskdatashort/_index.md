---
title: Class LayerMaskDataShort
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort clase. Define la clase LayerMaskDataShort que contiene información sobre los datos de máscara en el archivo PSD layer cuando la capa solo tiene una máscara ráster o vectorial pero no ambas. De lo contrario unLayerMaskDataFull se utiliza. Si la capa solo tiene una máscara de trama ImageData contiene los bytes de datos de la máscara de trama. Si la capa solo tiene una máscara vectorial ImageData contiene los bytes de datos rasterizados almacenados en caché de la máscara de vector. ImageDatala longitud de bytes debe ser igual Ancho  Altura deMaskRectangle propiedades.
type: docs
weight: 2260
url: /es/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

Define la clase LayerMaskDataShort que contiene información sobre los datos de máscara en el archivo PSD layer cuando la capa solo tiene una máscara ráster o vectorial, pero no ambas. De lo contrario, un[`LayerMaskDataFull`](../layermaskdatafull/) se utiliza. Si la capa solo tiene una máscara de trama, ImageData contiene los bytes de datos de la máscara de trama. Si la capa solo tiene una máscara vectorial, ImageData contiene los bytes de datos rasterizados (almacenados en caché) de la máscara de vector. [`ImageData`](../layermaskdata/imagedata/)la longitud de bytes debe ser igual Ancho * Altura de[`MaskRectangle`](../layermaskdata/maskrectangle/) propiedades.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Obtiene o establece la posición de la máscara de la capa inferior. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Obtiene el tamaño de los datos de máscara de máscara de capa. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Obtiene o establece el color predeterminado. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Obtiene o establece los indicadores de máscara de capa. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Obtiene o establece los datos de la máscara de capa (o la máscara combinada/final si hay una máscara vectorial) en el archivo PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Obtiene o establece la posición de la máscara de capa izquierda. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Obtiene o establece la máscara[`Rectangle`](../../aspose.psd/rectangle/)de la máscara de capa en el archivo PSD. Toma las propiedades izquierda, derecha, superior e inferior y crea[`Rectangle`](../../aspose.psd/rectangle/) |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Obtiene o establece el relleno de la máscara de capa. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Obtiene o establece la posición correcta de la máscara de capa. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Obtiene o establece la posición de la máscara de capa superior. |

### Ver también

* class [LayerMaskData](../layermaskdata/)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* asamblea [Aspose.PSD](../../)


