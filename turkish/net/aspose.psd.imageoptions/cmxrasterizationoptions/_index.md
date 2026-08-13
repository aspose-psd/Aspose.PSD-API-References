---
title: "Sınıf CmxRasterizationOptions"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ImageOptions.CmxRasterizationOptions sınıfı. CMX dışa aktarıcı seçenekleri"
type: docs
weight: 5320
url: /tr/net/aspose.psd.imageoptions/cmxrasterizationoptions/
---
{{< psd/tize >}}
## CmxRasterizationOptions class

CMX dışa aktarıcı seçenekleri.

```csharp
public class CmxRasterizationOptions : VectorRasterizationOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [CmxRasterizationOptions](cmxrasterizationoptions/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BackgroundColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | Alır veya ayarlar bir arka plan rengini. |
| [BorderX](../../aspose.psd.imageoptions/vectorrasterizationoptions/borderx/) { get; set; } | Alır veya ayarlar kenar X'i. |
| [BorderY](../../aspose.psd.imageoptions/vectorrasterizationoptions/bordery/) { get; set; } | Alır veya ayarlar kenar Y'yi. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [CenterDrawing](../../aspose.psd.imageoptions/vectorrasterizationoptions/centerdrawing/) { get; set; } | Alır veya ayarlar merkez çizim olup olmadığını gösteren bir değeri. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Varsayılan yedekleme yazı tipini alır veya ayarlar (rastera dışa aktarırken metin çizerken kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [DrawColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | Alır veya ayarlar bir ön plan rengini. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Tam çerçeve olup olduğunu gösteren bir değeri alır veya ayarlar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Çok sayfalı seçenekler |
| [PageHeight](../../aspose.psd.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | Alır veya ayarlar sayfa yüksekliğini. |
| [PageSize](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | Alır veya ayarlar sayfa boyutunu. |
| [PageWidth](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | Alır veya ayarlar sayfa genişliğini. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Renk paletini alır veya ayarlar. |
| [Positioning](../../aspose.psd.imageoptions/cmxrasterizationoptions/positioning/) { get; set; } | Alır veya ayarlar konumlandırmayı. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [SmoothingMode](../../aspose.psd.imageoptions/vectorrasterizationoptions/smoothingmode/) { get; set; } | Alır veya ayarlar yumuşatma modunu. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| [TextRenderingHint](../../aspose.psd.imageoptions/vectorrasterizationoptions/textrenderinghint/) { get; set; } | Alır veya ayarlar metin renderleme ipucunu. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Bu örneği klonlar. |
| [CopyTo](../../aspose.psd.imageoptions/vectorrasterizationoptions/copyto/)(VectorRasterizationOptions) | Kopyalar hedefe. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |

### Ayrıca Bakınız

* class [VectorRasterizationOptions](../vectorrasterizationoptions/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


