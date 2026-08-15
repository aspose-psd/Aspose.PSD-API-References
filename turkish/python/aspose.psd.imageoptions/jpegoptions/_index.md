---
title: "JpegOptions Sınıfı"
type: docs
weight: 60
url: /tr/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Yeni bir [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) sınıfı örneği başlatır. |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Yeni bir [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| bits_per_channel | byte | r/w | Kayıpsız jpeg görüntüsü için kanal başına bit sayısını alır veya ayarlar. Şu anda kanal başına 2 ile 8 bit arasında desteklenmektedir. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK jpeg görüntüleri için hedef CMYK renk profili. Görüntüleri kaydetmek için kullanın. Doğru renk dönüşümü için RGBColorProfile ile eşleşmelidir. |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | jpeg görüntüsü için renk tipini alır veya ayarlar. |
| yorum | string | r/w | jpeg dosya yorumunu alır veya ayarlar. |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | sıkıştırma tipini alır veya ayarlar. |
| default_memory_allocation_limit | int | r/w | varsayılan bellek tahsis sınırını alır veya ayarlar. |
| default_replacement_font | string | r/w | Varsayılan değiştirme yazı tipini alır veya ayarlar (rastera dışa aktarırken metin çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa).<br/>            Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | exif veri kapsayıcısını al veya ayarla |
| full_frame | bool | r/w | Tam çerçeve olup olduğunu gösteren bir değeri alır veya ayarlar. |
| horizontal_sampling | byte | r/w | her bileşen için yatay alt örneklemeleri alır veya ayarlar. |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | jfif'i alır veya ayarlar. |
| jpeg_ls_allowed_lossy_error | int | r/w | JPEG-LS yakın kayıpsız kodlama için fark sınırını (JPEG-LS spesifikasyonundaki NEAR parametresi) alır veya ayarlar. |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | JPEG-LS ara katman modunu alır veya ayarlar. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | JPEG-LS ön ayar parametrelerini alır veya ayarlar. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Çok sayfalı seçenekler |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Renk paletini alır veya ayarlar. |
| preblend_alpha_if_present | bool | r/w | Alfa kanalı mevcutsa kırmızı, yeşil ve mavi bileşenlerin bir arka plan rengiyle karıştırılıp karıştırılmayacağını gösteren bir değeri alır veya ayarlar. |
| quality | int | r/w | görüntü kalitesini alır veya ayarlar. |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | RD optimizasyon ayarlarını alır veya ayarlar. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | çözünürlük birimini alır veya ayarlar. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK jpeg görüntüleri için hedef RGB renk profili. Görüntüleri kaydetmek için kullanın. Doğru renk dönüşümü için CMYKColorProfile ile eşleşmelidir. |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | 8-bit bir değeri n-bit bir değere sığdırmak için örnek yuvarlama modunu alır veya ayarlar. <see cref=\"P:JpegOptions.BitsPerChannel\" /> |
| scaled_quality | int | r | Ölçeklenmiş kalite. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| vertical_sampling | byte | r/w | Her bileşen için dikey alt örneklemeleri alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP meta veri konteynerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneği klonlar. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Yeni bir [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) sınıfı örneği başlatır.

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Yeni bir [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | JPEG seçenekleri. |

### Method: clone() {#clone__1}


```
 clone() 
```

Bu örneği klonlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Bu örneğin yüzeysel bir kopyasını döndürür. |


