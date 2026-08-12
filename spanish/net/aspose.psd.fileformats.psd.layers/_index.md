---
title: "Aspose.PSD.FileFormats.Psd.Layers"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "El espacio de nombres contiene capas del formato de archivo PSD."
type: docs
weight: 230
url: /es/net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
El espacio de nombres contiene capas del formato de archivo PSD.

## Clases

| Clase | Descripción |
| --- | --- |
| [ArtboardLayer](./artboardlayer/) | La clase de capa de mesa de trabajo. |
| [BlendRange](./blendrange/) | El rango de mezcla. |
| [ChannelInformation](./channelinformation/) | La información del canal. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | La sección global de máscara de capa. |
| [Layer](./layer/) | La capa psd. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Los datos de rangos de fusión de capa. |
| [LayerGroup](./layergroup/) | Clase de capa de grupo |
| [LayerHashCalculator](./layerhashcalculator/) | Calculadora de hash para capas PSD. Puede usarse para encontrar capas iguales o diferentes en distintos archivos PSD |
| [LayerMaskData](./layermaskdata/) | Define la clase base LayerMaskData que contiene información sobre los datos de máscara de capa en el archivo PSD. Puede ayudar a modificar archivos Adobe® Photoshop® programáticamente y automatizar la edición del formato PSD. Si la capa tiene solo una máscara raster, el ImageData contiene los bytes de datos de la máscara raster. Si la capa tiene solo una máscara vector, el ImageData contiene los bytes de datos de la máscara vector rasterizada (en caché). Si la capa tiene tanto máscaras de capa como vectoriales, el ImageData contiene la máscara raster y la máscara vector rasterizada combinadas. La longitud en bytes del [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) debe ser igual a Ancho * Alto de las propiedades de [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/). Observe que simplemente eliminar / agregar / actualizar el LayerMaskData no es suficiente para guardar correctamente porque los canales no se actualizan; aunque puede proporcionar un renderizado correcto. El método [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) debe usarse para ello. |
| [LayerMaskDataFull](./layermaskdatafull/) | Define la clase LayerMaskDataFull que contiene información sobre los datos de máscara en la capa del archivo PSD cuando la capa tiene tanto máscaras de capa como vectoriales. De lo contrario, se utiliza un [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/). El ImageData contiene la máscara raster y la máscara vector rasterizada combinadas. La longitud en bytes del ImageData debe ser igual a las propiedades MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](./layermaskdatashort/) | Define la clase LayerMaskDataShort que contiene información sobre los datos de máscara en la capa del archivo PSD cuando la capa tiene solo una máscara raster o vectorial pero no ambas. De lo contrario, se utiliza un [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/). Si la capa tiene solo una máscara raster, el ImageData contiene los bytes de datos de la máscara raster. Si la capa tiene solo una máscara vector, el ImageData contiene los bytes de datos de la máscara vector rasterizada (en caché). La longitud en bytes del [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) debe ser igual a Ancho * Alto de las propiedades de [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/). |
| [LayerResource](./layerresource/) | Representa información de capa. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Define el registro de recursos de capa para la carga de archivos PSD. |
| [LinkedLayersManager](./linkedlayersmanager/) | Clase de gestor de capas vinculadas. |
| [SectionDividerLayer](./sectiondividerlayer/) | La capa divisor de sección para marcar los límites de la carpeta (grupo de capas). |
| [ShapeLayer](./shapelayer/) | Capa de forma. Encapsula la lógica de trabajo con la capa Shape y los recursos relacionados. |
| [TextLayer](./textlayer/) | Clase de capa de texto |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Interfaz base para la configuración de relleno |
| [ILayerResourceLoader](./ilayerresourceloader/) | El cargador de recursos de capa. |
| [IShapeLayer](./ishapelayer/) | Describe las propiedades de la capa Shape. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [LayerFlags](./layerflags/) | Las banderas de capa. |
| [LayerMaskFlags](./layermaskflags/) | Las banderas de máscara de capa. |


