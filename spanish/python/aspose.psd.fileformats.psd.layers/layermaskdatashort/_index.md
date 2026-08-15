---
title: "Clase LayerMaskDataShort"
type: docs
weight: 990
url: /es/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Summary:** Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer<br/>            when the layer has only raster or vector mask but not both. Otherwise, a [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) is used.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataShort

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LayerMaskDataShort()](#LayerMaskDataShort__1) | Inicializa una nueva instancia de la clase LayerMaskDataShort |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| inferior | int | r/w | Obtiene o establece la posición inferior de la máscara de capa. |
| data_size | int | r | Obtiene el tamaño de los datos de la máscara de capa. |
| default_color | byte | r/w | Obtiene o establece el color predeterminado. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Obtiene o establece las banderas de la máscara de capa. |
| image_data | byte | r/w | Obtiene o establece los datos de la máscara de capa (o la máscara combinada / final si hay una máscara vectorial) en el archivo PSD. |
| left | int | r/w | Obtiene o establece la posición izquierda de la máscara de capa. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Obtiene o establece la máscara [Rectangle](/psd/python-net/aspose.psd/rectangle/) de la máscara de capa en el archivo PSD.<br/>            Toma las propiedades izquierda, derecha, superior e inferior y crea [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| padding | short | r/w | Obtiene o establece el relleno de la máscara de capa. |
| right | int | r/w | Obtiene o establece la posición derecha de la máscara de capa. |
| top | int | r/w | Obtiene o establece la posición superior de la máscara de capa. |


### Constructor: LayerMaskDataShort() {#LayerMaskDataShort__1}


```
 LayerMaskDataShort() 
```

Inicializa una nueva instancia de la clase LayerMaskDataShort

