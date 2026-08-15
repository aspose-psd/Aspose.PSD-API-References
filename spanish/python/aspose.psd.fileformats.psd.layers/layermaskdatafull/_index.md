---
title: "Clase LayerMaskDataFull"
type: docs
weight: 980
url: /es/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | Inicializa una nueva instancia de la clase LayerMaskDataFull |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| background_color | byte | r/w | Obtiene o establece el color de fondo. |
| inferior | int | r/w | Obtiene o establece la posición inferior de la máscara de capa. |
| data_size | int | r | Obtiene el tamaño de los datos de la máscara de capa. |
| default_color | byte | r/w | Obtiene o establece el color predeterminado. |
| enclosing_bottom | int | r/w | Obtiene o establece la posición inferior del contorno de la máscara raster en la capa de imagen PSD. |
| enclosing_left | int | r/w | Obtiene o establece la posición izquierda del contorno de la máscara raster en la capa del archivo PSD. |
| enclosing_right | int | r/w | Obtiene o establece la posición derecha del contorno de la máscara raster en la capa del archivo PSD. |
| enclosing_top | int | r/w | Obtiene o establece la posición superior del contorno de la máscara raster en la capa de imagen PSD. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Obtiene o establece las banderas de la máscara de capa. |
| image_data | byte | r/w | Obtiene o establece los datos de la máscara de capa (o la máscara combinada / final si hay una máscara vectorial) en el archivo PSD. |
| left | int | r/w | Obtiene o establece la posición izquierda de la máscara de capa. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Obtiene o establece la máscara [Rectangle](/psd/python-net/aspose.psd/rectangle/) de la máscara de capa en el archivo PSD.<br/>            Toma las propiedades izquierda, derecha, superior e inferior y crea [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Obtiene o establece los indicadores de máscara de capa que se utilizan para la máscara de usuario / raster. Para la máscara vectorial se usa la propiedad Flags. |
| right | int | r/w | Obtiene o establece la posición derecha de la máscara de capa. |
| top | int | r/w | Obtiene o establece la posición superior de la máscara de capa. |
| user_mask_data | byte | r/w | Obtiene o establece los datos de máscara de usuario (raster) de una capa en el archivo PSD. (Existe una máscara vectorial rasterizada en la propiedad MaskData). |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Obtiene o establece el rectángulo de la máscara de usuario (envolvente) en la capa de imagen PSD. |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

Inicializa una nueva instancia de la clase LayerMaskDataFull

