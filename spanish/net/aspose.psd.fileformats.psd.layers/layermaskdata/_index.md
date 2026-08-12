---
title: "Clase LayerMaskData"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData class. Define la clase base LayerMaskData que contiene información sobre los datos de la máscara de capa en el archivo PSD. Puede ayudar a modificar archivos Adobe Photoshop programáticamente y automatizar la edición del formato PSD. Si la capa tiene solo una máscara raster, ImageData contiene los bytes de datos de la máscara raster. Si la capa tiene solo una máscara vector, ImageData contiene los bytes de datos en caché rasterizados de la máscara vector. Si la capa tiene tanto máscaras de capa como vectoriales, ImageData contiene la máscara raster y la máscara vector rasterizada combinadas. La longitud de los bytes de ImageData debe ser igual al ancho y alto de las propiedades MaskRectangle. Observe que simplemente eliminar / agregar / actualizar el LayerMaskData no es suficiente para guardar correctamente porque los canales no se actualizan, aunque puede proporcionar un renderizado correcto. El método AddLayerMask debe usarse para eso."
type: docs
weight: 2440
url: /es/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

Define la clase base LayerMaskData que contiene información sobre los datos de la máscara de capa en el archivo PSD. Puede ayudar a modificar archivos Adobe® Photoshop® programáticamente y automatizar la edición del formato PSD. Si la capa tiene solo una máscara raster, ImageData contiene los bytes de datos de la máscara raster. Si la capa tiene solo una máscara vector, ImageData contiene los bytes de datos rasterizados (en caché) de la máscara vector. Si la capa tiene tanto máscaras de capa como vectoriales, ImageData contiene la máscara raster y la máscara vector rasterizada combinadas. Los bytes de [`ImageData`](./imagedata/) deben tener una longitud igual al Ancho * Alto de las propiedades [`MaskRectangle`](./maskrectangle/). Observe que simplemente eliminar / agregar / actualizar el LayerMaskData no es suficiente para guardar correctamente porque los canales no se actualizan; aunque puede proporcionar un renderizado correcto. El método [`AddLayerMask`](../layer/addlayermask/) debe usarse para eso.

```csharp
public abstract class LayerMaskData
```

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
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Obtiene o establece la posición derecha de la máscara de capa. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Obtiene o establece la posición superior de la máscara de capa. |

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


