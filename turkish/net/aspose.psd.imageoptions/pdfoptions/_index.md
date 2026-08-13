---
title: "Sınıf PdfOptions"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ImageOptions.PdfOptions sınıfı. PDF seçenekleri"
type: docs
weight: 5390
url: /tr/net/aspose.psd.imageoptions/pdfoptions/
---
{{< psd/tize >}}
## PdfOptions class

PDF seçenekleri.

```csharp
public class PdfOptions : ImageOptionsBase
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PdfOptions](pdfoptions/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Varsayılan yedekleme yazı tipini alır veya ayarlar (rastera dışa aktarırken metin çizerken kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Tam çerçeve olup olduğunu gösteren bir değeri alır veya ayarlar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Çok sayfalı seçenekler |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize/) { get; set; } | Sayfanın boyutunu alır veya ayarlar. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Renk paletini alır veya ayarlar. |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions/) { get; set; } | PDF çekirdek seçenekleri |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | Belge için üst verileri alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Bu örneği klonlar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |

## Örnekler

Aşağıdaki örnek, Adobe Illustrator dosyalarını Aspose.PSD içinde PDF formatına nasıl dışa aktarabileceğinizi gösterir.

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Aşağıdaki örnek, AsposePSD'nin PSB dosyalarını PSD formatına dışa aktarmayı desteklediğini gösterir.

```csharp
[C#]

// PSB'yi PDF olarak kaydetmeyi destekle
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Aşağıdaki kod, PsdImage'ı seçilebilir metin içeren PDF belgesi olarak kaydeder.

```csharp
[C#]

// PSD'yi PDF olarak kaydetmek seçilebilir metin sağlamaz
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Aşağıdaki örnek, PsdImage'ın Pdf formatına dışa aktarım desteğini gösterir.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"1.psd",
    @"little.psb",
    @"psb3.psb",
    @"inRgb16.psd",
    @"ALotOfElementTypes.psd",
    @"ColorOverlayAndShadowAndMask.psd",
    @"ThreeRegularLayersSemiTransparent.psd"
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string sourceFileName = sourcesFiles[i];
    using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
    {
        string outFileName = "PsdToPdf" + i + ".pdf";
        image.Save(outFileName, new PdfOptions());
    }
}
```

### Ayrıca Bakınız

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


