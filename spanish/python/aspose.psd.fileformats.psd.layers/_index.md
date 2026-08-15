---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /es/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **Class** | **Descripción** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | Clase de capa de mesa de trabajo. |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | El rango de mezcla. |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | La información del canal. |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | La sección de máscara de capa global. |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | Interfaz base para la configuración de relleno |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | El cargador de recursos de capa. |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | Describe las propiedades de la capa Shape. |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | La capa psd. |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | Los datos de rangos de fusión de capa. |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Clase de capa de grupo |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | Calculadora de hash para capas PSD. Puede usarse para encontrar capas iguales o diferentes en distintos archivos PSD. |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | Define la clase base LayerMaskData que contiene información sobre los datos de máscara de capa en el archivo PSD.<br/>            Puede ayudar a modificar archivos Adobe® Photoshop® programáticamente y automatizar la edición del formato PSD.<br/>            Si la capa tiene solo una máscara raster, ImageData contiene los bytes de datos de la máscara raster.<br/>            Si la capa tiene solo una máscara vector, ImageData contiene los bytes de datos de la máscara vector rasterizada (en caché).<br/>            Si la capa tiene tanto máscaras de capa como vector, ImageData contiene la máscara raster y la máscara vector rasterizada combinadas.<br/>            La longitud en bytes de [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) debe ser igual a Ancho * Alto de las propiedades [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/).<br/>            Observe que simplemente eliminar / agregar / actualizar el LayerMaskData no es suficiente para guardar correctamente<br/>            porque los canales no se actualizan; aunque puede proporcionar un renderizado correcto.<br/>            Se debe usar el método [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) para eso. |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | Define la clase LayerMaskDataFull que contiene información sobre los datos de máscara en la capa del archivo PSD<br/>            cuando la capa tiene tanto máscaras de capa como vector. De lo contrario, se usa un [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/).<br/>            ImageData contiene la máscara raster y la máscara vector rasterizada combinadas.<br/>            La longitud en bytes de ImageData debe ser igual a las propiedades MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | Define la clase LayerMaskDataShort que contiene información sobre los datos de máscara en la capa del archivo PSD<br/>            cuando la capa tiene solo una máscara raster o vector, pero no ambas. De lo contrario, se usa un [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/).<br/>            Si la capa tiene solo una máscara raster, ImageData contiene los bytes de datos de la máscara raster.<br/>            Si la capa tiene solo una máscara vector, ImageData contiene los bytes de datos de la máscara vector rasterizada (en caché).<br/>            La longitud en bytes de [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) debe ser igual a Ancho * Alto de las propiedades [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/). |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | Representa información de capa. |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | Define el registro de recursos de capa para la carga de archivos PSD. |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | Clase de administrador de capas vinculadas. |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | La capa divisor de sección para marcar los límites de la carpeta (grupo de capas). |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Capa Shape. Encapsula la lógica de trabajo con la capa Shape y los recursos relacionados. |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Clase de capa de texto |
## **Enumerations**
| **Enumeration** | **Descripción** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | Los indicadores de capa |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | Los indicadores de máscara de capa |
