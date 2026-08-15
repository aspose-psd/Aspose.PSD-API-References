---
title: "CmxRasterizationOptions Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.psd.imageoptions/cmxrasterizationoptions/
---

**Summary:** the CMX exporter options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.CmxRasterizationOptions

**Inheritance:** VectorRasterizationOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [CmxRasterizationOptions()](#CmxRasterizationOptions__1) | CmxRasterizationOptions sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Arka plan rengini alır veya ayarlar. |
| border_x | float | r/w | X kenarını alır veya ayarlar. |
| border_y | float | r/w | Y kenarını alır veya ayarlar. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| center_drawing | bool | r/w | Orta çizim olup olmadığını gösteren değeri alır veya ayarlar. |
| default_replacement_font | string | r/w | Varsayılan değiştirme yazı tipini alır veya ayarlar (rastera dışa aktarırken metin çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa).<br/>            Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| draw_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Ön plan rengini alır veya ayarlar. |
| full_frame | bool | r/w | Tam çerçeve olup olduğunu gösteren bir değeri alır veya ayarlar. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Çok sayfalı seçenekler |
| page_height | float | r/w | Sayfa yüksekliğini alır veya ayarlar. |
| page_size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Sayfa boyutunu alır veya ayarlar. |
| page_width | float | r/w | Sayfa genişliğini alır veya ayarlar. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Renk paletini alır veya ayarlar. |
| positioning | [PositioningTypes](/psd/python-net/aspose.psd.imageoptions/positioningtypes) | r/w | Konumlandırmayı alır veya ayarlar. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Yumuşatma modunu alır veya ayarlar. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Metin renderleme ipucunu alır veya ayarlar. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP meta veri konteynerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneği klonlar. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Kopyalar. |


### Constructor: CmxRasterizationOptions() {#CmxRasterizationOptions__1}


```
 CmxRasterizationOptions() 
```

CmxRasterizationOptions sınıfının yeni bir örneğini başlatır.

### Method: clone() {#clone__1}


```
 clone() 
```

Bu örneği klonlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Bu örneğin yüzeysel bir kopyasını döndürür. |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Kopyalar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | vektör rasterleştirme seçenekleri. |

