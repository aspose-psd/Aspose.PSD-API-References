---
title: "LayerMaskDataShort Класс"
type: docs
weight: 990
url: /ru/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Summary:** Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer<br/>            when the layer has only raster or vector mask but not both. Otherwise, a [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) is used.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataShort

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [LayerMaskDataShort()](#LayerMaskDataShort__1) | Инициализирует новый экземпляр класса LayerMaskDataShort. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| bottom | int | r/w | Получает или задает положение нижней маски слоя. |
| data_size | int | r | Получает размер данных маски слоя. |
| default_color | байт | r/w | Получает или задает цвет по умолчанию. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Получает или задает флаги маски слоя. |
| image_data | байт | r/w | Получает или задает данные маски слоя (или объединённую/конечную маску, если существует векторная маска) в файле PSD. |
| слева | int | r/w | Получает или задает положение левой маски слоя. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Получает или задает маску [Rectangle](/psd/python-net/aspose.psd/rectangle/) маски слоя в файле PSD.<br/>            Он принимает свойства left, right, top и bottom и создаёт [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| padding | short | r/w | Получает или задает отступ маски слоя. |
| справа | int | r/w | Получает или задает положение правой маски слоя. |
| верх | int | r/w | Получает или задает положение верхней маски слоя. |


### Constructor: LayerMaskDataShort() {#LayerMaskDataShort__1}


```
 LayerMaskDataShort() 
```

Инициализирует новый экземпляр класса LayerMaskDataShort.

