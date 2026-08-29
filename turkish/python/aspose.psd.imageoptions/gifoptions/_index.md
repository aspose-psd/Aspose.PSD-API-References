---
title: "GifOptions Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Yeni bir [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) sınıfı örneği başlatır. |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Yeni bir [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| background_color_index | byte | r/w | GIF arka plan renk indeksini alır veya ayarlar. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| color_resolution | byte | r/w | GIF renk çözünürlüğünü alır veya ayarlar. |
| default_replacement_font | string | r/w | Varsayılan değiştirme yazı tipini alır veya ayarlar (rastera dışa aktarırken metin çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa).<br/>            Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| do_palette_correction | bool | r/w | Palet düzeltmesinin uygulanıp uygulanmadığını gösteren bir değeri alır veya ayarlar. |
| full_frame | bool | r/w | Tam çerçeve olup olduğunu gösteren bir değeri alır veya ayarlar. |
| has_trailer | bool | r/w | GIF'in trailer içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| interlaced | bool | r/w | Görüntünün taramalı olması gerekiyorsa doğru. |
| is_palette_sorted | bool | r/w | Palet girişlerinin sıralanıp sıralanmadığını gösteren bir değeri alır veya ayarlar. |
| max_diff | int | r/w | İzin verilen maksimum piksel farkını alır veya ayarlar. Sıfırdan büyükse kayıplı sıkıştırma kullanılacaktır.<br/>            Optimum kayıplı sıkıştırma için önerilen değer 80'dir. 30 çok hafif sıkıştırma, 200 ise ağırdır.<br/>            Sadece az kayıp olduğunda en iyi çalışır ve sıkıştırma algoritmasının sınırlamaları nedeniyle çok yüksek kayıp seviyeleri fazla kazanç sağlamaz.<br/>            İzin verilen değer aralığı [0, 1000]'dir. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Çok sayfalı seçenekler |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Renk paletini alır veya ayarlar. |
| pixel_aspect_ratio | byte | r/w | GIF piksel en-boy oranını alır veya ayarlar. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP meta veri konteynerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneği klonlar. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Yeni bir [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) sınıfı örneği başlatır.

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Yeni bir [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | GIF Seçenekleri. |

### Method: clone() {#clone__1}


```
 clone() 
```

Bu örneği klonlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Bu örneğin yüzeysel bir kopyasını döndürür. |


