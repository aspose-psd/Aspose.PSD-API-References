---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Referencia de API de Aspose.PSD para .NET
description: El espacio de nombres contiene capas de formato de archivo PSD.
type: docs
weight: 210
url: /es/net/aspose.psd.fileformats.psd.layers/
---
El espacio de nombres contiene capas de formato de archivo PSD.

## Clases

| Clase | Descripción |
| --- | --- |
| [BlendRange](./blendrange/) | El rango de mezcla. |
| [ChannelInformation](./channelinformation/) | La información del canal. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | La sección de máscara de capa global. |
| [Layer](./layer/) | La capa psd. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Los rangos de fusión de capas data. |
| [LayerGroup](./layergroup/) | Clase de capa de grupo |
| [LayerHashCalculator](./layerhashcalculator/) | Calculadora hash para capas PSD. Se puede usar para encontrar capas iguales o diferentes en diferentes archivos PSD |
| [LayerMaskData](./layermaskdata/) | Define la clase base LayerMaskData que contiene información sobre los datos de la máscara de capa en el archivo PSD. Puede ayudar a modificar los archivos de Adobe® Photoshop® mediante programación y automatizar la edición del formato PSD. Si la capa solo tiene una máscara ráster, ImageData contiene el ráster bytes de datos de máscara. Si la capa solo tiene una máscara vectorial, ImageData contiene los bytes de datos rasterizados (almacenados en caché) de la máscara vectorial. Si la capa tiene máscaras de capa y vectoriales, ImageData contiene la máscara ráster y la máscara vectorial rasterizada combinadas. El[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)la longitud de bytes debe ser igual Ancho * Altura de[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properties. Tenga en cuenta que simplemente eliminar/agregar/actualizar LayerMaskData no es suficiente para guardar correctamente porque los canales no se actualizan; aunque puede proporcionar una representación correcta. El[`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) se debe usar el método para eso. |
| [LayerMaskDataFull](./layermaskdatafull/) | Define la clase LayerMaskDataFull que contiene información sobre los datos de máscara en el archivo PSD layer cuando la capa tiene máscaras de capa y vectoriales. De lo contrario, un[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) se usa. ImageData contiene la máscara de trama y la máscara vectorial rasterizada combinadas. La longitud de bytes de ImageData debe ser igual a las propiedades MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](./layermaskdatashort/) | Define la clase LayerMaskDataShort que contiene información sobre los datos de máscara en el archivo PSD layer cuando la capa solo tiene una máscara ráster o vectorial, pero no ambas. De lo contrario, un[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) se utiliza. Si la capa solo tiene una máscara de trama, ImageData contiene los bytes de datos de la máscara de trama. Si la capa solo tiene una máscara vectorial, ImageData contiene los bytes de datos rasterizados (almacenados en caché) de la máscara de vector. [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)la longitud de bytes debe ser igual Ancho * Altura de[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) propiedades. |
| [LayerResource](./layerresource/) | Representa información de la capa. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Definir el registro de recursos de capa para la carga de archivos PSD. |
| [LinkedLayersManager](./linkedlayersmanager/) | Clase de administrador de capas enlazadas. |
| [SectionDividerLayer](./sectiondividerlayer/) | La capa divisoria de sección para marcar los límites de la carpeta (grupo de capas). |
| [TextLayer](./textlayer/) | La clase de capa de texto |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Interfaz base para configuración de relleno |
| [ILayerResourceLoader](./ilayerresourceloader/) | El cargador de recursos de capa. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [LayerFlags](./layerflags/) | La capa flags |
| [LayerMaskFlags](./layermaskflags/) | La máscara de capa flags |


