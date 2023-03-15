---
title: Class LayerMaskDataFull
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull clase. Define la clase LayerMaskDataFull que contiene información sobre los datos de máscara en el archivo PSD layer cuando la capa tiene máscaras de capa y vectoriales. De lo contrario unLayerMaskDataShort se usa. ImageData contiene la máscara de trama y la máscara vectorial rasterizada combinadas. La longitud de bytes de ImageData debe ser igual a las propiedades MaskRectangle.Width  MaskRectangle.Height.
type: docs
weight: 2250
url: /es/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

Define la clase LayerMaskDataFull que contiene información sobre los datos de máscara en el archivo PSD layer cuando la capa tiene máscaras de capa y vectoriales. De lo contrario, un[`LayerMaskDataShort`](../layermaskdatashort/) se usa. ImageData contiene la máscara de trama y la máscara vectorial rasterizada combinadas. La longitud de bytes de ImageData debe ser igual a las propiedades MaskRectangle.Width * MaskRectangle.Height.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Obtiene o establece el color de fondo. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Obtiene o establece la posición de la máscara de la capa inferior. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Obtiene el tamaño de los datos de máscara de máscara de capa. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Obtiene o establece el color predeterminado. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Obtiene o establece la posición de la máscara de trama inferior envolvente en la capa de imagen PSD. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Obtiene o establece la posición de la máscara ráster izquierda envolvente en la capa del archivo PSD. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Obtiene o establece la posición de la máscara ráster derecha envolvente en la capa del archivo PSD. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Obtiene o establece la posición superior envolvente de la máscara ráster en la capa de imagen PSD. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Obtiene o establece los indicadores de máscara de capa. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Obtiene o establece los datos de la máscara de capa (o la máscara combinada/final si hay una máscara vectorial) en el archivo PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Obtiene o establece la posición de la máscara de capa izquierda. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Obtiene o establece la máscara[`Rectangle`](../../aspose.psd/rectangle/)de la máscara de capa en el archivo PSD. Toma las propiedades izquierda, derecha, superior e inferior y crea[`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Obtiene o establece los indicadores de máscara de capa que se utilizan para la máscara de usuario/ráster. Para máscara vectorial se utiliza la propiedad Flags. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Obtiene o establece la posición correcta de la máscara de capa. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Obtiene o establece la posición de la máscara de capa superior. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Obtiene o establece los datos de máscara de usuario (ráster) de una capa en el archivo PSD. (Hay una máscara vectorial calificada en la propiedad MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Obtiene o establece el rectángulo de máscara de usuario (que lo encierra) en la capa de imagen PSD.. |

### Ver también

* class [LayerMaskData](../layermaskdata/)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* asamblea [Aspose.PSD](../../)


