---
title: Class PdfOptions
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.ImageOptions.PdfOptions sınıf. PDF seçenekleri.
type: docs
weight: 4870
url: /tr/net/aspose.psd.imageoptions/pdfoptions/
---
## PdfOptions class

PDF seçenekleri.

```csharp
public class PdfOptions : ImageOptionsBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfOptions](pdfoptions/)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyutu tanımlayan arabellek boyutu ipucunu alır veya ayarlar. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Varsayılan yedek yazı tipini alır veya ayarlar (PSD dosyasındaki mevcut katman yazı tipi sistemde sunulmuyorsa, taramaya dışa aktarırken metin çizmek için kullanılacak yazı tipi). Varsayılan yazı tipinin uygun adını almak için bir sonraki kod parçacığı kullanılabilir : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familys = col.Families; string defaultFontName = familys[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [tam çerçeve]. olup olmadığını gösteren bir değer alır veya ayarlar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Çok sayfalı seçenekler |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize/) { get; set; } | Sayfanın boyutunu alır veya ayarlar. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Renk paletini alır veya ayarlar. |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions/) { get; set; } | PDF çekirdek seçenekleri |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | Document. için meta verileri alır veya ayarlar |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | . içinde görüntü oluşturmak için kaynağı alır veya ayarlar |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Vektör tarama seçeneklerini alır veya ayarlar. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Bu örneği klonlar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |

### Örnekler

Aşağıdaki örnek, Adobe Illustrator dosyalarını Aspose.PSD'de PDF formatına nasıl aktarabileceğinizi göstermektedir.

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Aşağıdaki örnek, AsposePSD'nin PSB dosyalarının bir PSD formatına dışa aktarılmasını desteklediğini göstermektedir.

```csharp
[C#]

// PSB'yi PDF olarak kaydetme desteği
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Aşağıdaki kod, PsdImage'ı seçilebilir metinle PDF belgesi olarak kaydediyor.

```csharp
[C#]

// PSD'yi PDF'ye kaydetmek, seçilebilir metin sağlamaz
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Aşağıdaki örnek, PsdImage'ı Pdf formatına dışa aktarma desteğini göstermektedir.

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

### Ayrıca bakınız

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* ad alanı [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* toplantı [Aspose.PSD](../../)


