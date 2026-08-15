---
title: "LayerMaskDataFull Sınıfı"
type: docs
weight: 980
url: /tr/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | LayerMaskDataFull sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| background_color | byte | r/w | Arka plan rengini alır veya ayarlar. |
| alt | int | r/w | Alt katman maskesi konumunu alır veya ayarlar. |
| data_size | int | r | Katman maskesi veri boyutunu alır. |
| default_color | byte | r/w | Varsayılan rengi alır veya ayarlar. |
| enclosing_bottom | int | r/w | PSD görüntü katmanındaki kapsayan alt raster maske konumunu alır veya ayarlar. |
| enclosing_left | int | r/w | PSD dosya katmanındaki kapsayan sol raster maske konumunu alır veya ayarlar. |
| enclosing_right | int | r/w | PSD dosya katmanındaki kapsayan sağ raster maske konumunu alır veya ayarlar. |
| enclosing_top | int | r/w | PSD görüntü katmanındaki raster maskenin kapsayan üst konumunu alır veya ayarlar. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Katman maskesi bayraklarını alır veya ayarlar. |
| image_data | byte | r/w | PSD dosyasındaki katman maskesi verisini (veya bir vektör maskesi varsa birleşik / son maskeyi) alır veya ayarlar. |
| sol | int | r/w | Sol katman maskesi konumunu alır veya ayarlar. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD dosyasındaki katman maskesinin maske [Rectangle](/psd/python-net/aspose.psd/rectangle/) öğesini alır veya ayarlar.<br/>            Sol, sağ, üst ve alt özelliklerini alır ve [Rectangle](/psd/python-net/aspose.psd/rectangle/) oluşturur. |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Kullanıcı / raster maskesi için kullanılan katman maskesi bayraklarını alır veya ayarlar. Vektör maskesi için Flags özelliği kullanılır. |
| sağ | int | r/w | Sağ katman maskesi konumunu alır veya ayarlar. |
| üst | int | r/w | Üst katman maskesi konumunu alır veya ayarlar. |
| user_mask_data | byte | r/w | PSD dosyasındaki bir katmanın kullanıcı (raster) maske verisini alır veya ayarlar. (MaskData özelliğinde rasterleştirilmiş bir vektör maske vardır). |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD görüntü katmanındaki kullanıcı maskesinin (çevreleyen) dikdörtgenini alır veya ayarlar.. |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

LayerMaskDataFull sınıfının yeni bir örneğini başlatır

