---
title: "Класс LayerMaskDataFull"
type: docs
weight: 980
url: /ru/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | Инициализирует новый экземпляр класса LayerMaskDataFull. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| background_color | байт | r/w | Получает или задает цвет фона. |
| bottom | int | r/w | Получает или задает положение нижней маски слоя. |
| data_size | int | r | Получает размер данных маски слоя. |
| default_color | байт | r/w | Получает или задает цвет по умолчанию. |
| enclosing_bottom | int | r/w | Получает или задает положение нижней ограничивающей растровой маски в слое изображения PSD. |
| enclosing_left | int | r/w | Получает или задает положение левой ограничивающей растровой маски в слое файла PSD. |
| enclosing_right | int | r/w | Получает или задает положение правой ограничивающей растровой маски в слое файла PSD. |
| enclosing_top | int | r/w | Получает или задает положение верхней ограничивающей растровой маски в слое изображения PSD. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Получает или задает флаги маски слоя. |
| image_data | байт | r/w | Получает или задает данные маски слоя (или объединённую/конечную маску, если существует векторная маска) в файле PSD. |
| слева | int | r/w | Получает или задает положение левой маски слоя. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Получает или задает маску [Rectangle](/psd/python-net/aspose.psd/rectangle/) маски слоя в файле PSD.<br/>            Он принимает свойства left, right, top и bottom и создаёт [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Получает или задает флаги маски слоя, которые используются для пользовательской / растровой маски. Для векторной маски используется свойство Flags. |
| справа | int | r/w | Получает или задает положение правой маски слоя. |
| верх | int | r/w | Получает или задает положение верхней маски слоя. |
| user_mask_data | байт | r/w | Получает или задает данные пользовательской (растровой) маски слоя в файле PSD. (В свойстве MaskData находится растеризованная векторная маска). |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Получает или задает прямоугольник пользовательской (ограничивающей) маски в слое изображения PSD. |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

Инициализирует новый экземпляр класса LayerMaskDataFull.

