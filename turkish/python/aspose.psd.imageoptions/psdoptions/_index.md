---
title: "PsdOptions Sınıfı"
type: docs
weight: 100
url: /tr/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Yeni bir [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) sınıfı örneği başlatır. |
| [PsdOptions(image)](#PsdOptions_image_2) | Yeni bir [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) sınıfı örneği başlatır. |
| [PsdOptions(options)](#PsdOptions_options_3) | Yeni bir [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Arka plan rengini alır veya ayarlar.<br/>            Şeffaf nesnelerin altında görülebilir. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| channel_bits_count | short | r/w | Renk kanalı başına bit sayısını alır veya ayarlar. |
| channels_count | short | r/w | Renk kanallarının sayısını alır veya ayarlar. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | psd renk modunu alır veya ayarlar. |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | psd sıkıştırma yöntemini alır veya ayarlar. |
| default_replacement_font | string | r/w | Varsayılan değiştirme yazı tipini alır veya ayarlar (rastera dışa aktarırken metin çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa).<br/>            Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| full_frame | bool | r/w | Tam çerçeve olup olduğunu gösteren bir değeri alır veya ayarlar. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Çok sayfalı seçenekler |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Renk paletini alır veya ayarlar. |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | Dosya formatı sürümünü alır veya ayarlar. PSD veya PSB olabilir. |
| refresh_image_preview_data | bool | r/w | Bir değerin [refresh image preview data] gösterip göstermediğini alır veya ayarlar - başka PSD görüntüleyicileriyle uyumluluğu en üst düzeye çıkarmak için kullanılan seçenek.<br/>            Lütfen, metin katmanlarının nihai düzene çizilmesinin Compact Framework platformu için desteklenmediğini unutmayın. |
| remove_global_text_engine_resource | bool | r/w | Bir değerin - Global metin motoru kaynağını kaldır - gösterip göstermediğini alır veya ayarlar - İşlemden sonra Adobe Photoshop'ta açılamayan bazı metin katmanlı psd dosyaları için kullanılır (çoğunlukla eksik yazı tiplerine bağlı metin katmanları).<br/>            Bu seçeneği kullandıktan sonra, kullanıcı Photoshop'ta açılan dosyada şu adımları yapmalıdır: Menü "Text" -> "Process absent fonts". Bu işlemden sonra tüm metin tekrar görünecektir.<br/>            Lütfen, bu işlemin bazı nihai düzen değişikliklerine neden olabileceğini unutmayın. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | psd kaynaklarını alır veya ayarlar. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| update_metadata | bool | r/w | Bir değerin [update metadata] gösterip göstermediğini alır veya ayarlar.<br/>            Değer doğru ise, görüntü kaydedilirken meta veriler güncellenecektir. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| version | int | r/w | psd dosya sürümünü alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP veri kapsayıcısını al veya ayarla |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneği klonlar. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Yeni bir [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) sınıfı örneği başlatır.

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

Yeni bir [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | Görsel. |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

Yeni bir [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | Seçenekler. |

### Method: clone() {#clone__1}


```
 clone() 
```

Bu örneği klonlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Bu örneğin yüzeysel bir kopyasını döndürür. |


