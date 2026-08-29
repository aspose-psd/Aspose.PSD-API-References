---
title: "Clase LayerMaskDataFull"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull class. Define la clase LayerMaskDataFull que contiene información sobre los datos de la máscara en la capa del archivo PSD cuando la capa tiene tanto máscaras de capa como vectoriales. De lo contrario se utiliza LayerMaskDataShort. ImageData contiene la máscara raster y la máscara vector rasterizada combinadas. La longitud de los bytes de ImageData debe ser igual a las propiedades MaskRectangle.Width  MaskRectangle.Height."
type: docs
weight: 2450
url: /es/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
{{< psd/tize >}}
## LayerMaskDataFull class

Define la clase LayerMaskDataFull que contiene información sobre los datos de la máscara en la capa del archivo PSD cuando la capa tiene tanto máscaras de capa como vectoriales. De lo contrario, se utiliza un [`LayerMaskDataShort`](../layermaskdatashort/). ImageData contiene la máscara raster y la máscara vector rasterizada combinadas. La longitud de los bytes de ImageData debe ser igual a las propiedades MaskRectangle.Width * MaskRectangle.Height.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Obtiene o establece el color de fondo. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Obtiene o establece la posición inferior de la máscara de capa. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Obtiene el tamaño de los datos de la máscara de capa. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Obtiene o establece el color predeterminado. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Obtiene o establece la posición inferior de la máscara raster contenedora en la capa de imagen PSD. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Obtiene o establece la posición izquierda de la máscara raster contenedora en la capa del archivo PSD. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Obtiene o establece la posición derecha de la máscara raster contenedora en la capa del archivo PSD. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Obtiene o establece la posición superior de la máscara raster contenedora en la capa de imagen PSD. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Obtiene o establece los indicadores de la máscara de capa. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Obtiene o establece los datos de la máscara de capa (o la máscara combinada / final si hay una máscara vector) en el archivo PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Obtiene o establece la posición izquierda de la máscara de capa. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Obtiene o establece el [`Rectangle`](../../aspose.psd/rectangle/) de la máscara de capa en el archivo PSD. Toma las propiedades izquierda, derecha, superior e inferior y crea un [`Rectangle`](../../aspose.psd/rectangle/). |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Obtiene o establece los indicadores de la máscara de capa que se usan para la máscara de usuario / raster. Para la máscara vectorial se utiliza la propiedad Flags. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Obtiene o establece la posición derecha de la máscara de capa. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Obtiene o establece la posición superior de la máscara de capa. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Obtiene o establece los datos de la máscara de usuario (raster) de una capa en el archivo PSD. (Hay una máscara vector rasterizada en la propiedad MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Obtiene o establece el rectángulo de la máscara de usuario (contenedor) en la capa de imagen PSD. |

### Ver también

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


