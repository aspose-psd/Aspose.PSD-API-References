---
title: Class PdfOptions
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.ImageOptions.PdfOptions klass. PDFalternativen.
type: docs
weight: 4870
url: /sv/net/aspose.psd.imageoptions/pdfoptions/
---
## PdfOptions class

PDF-alternativen.

```csharp
public class PdfOptions : ImageOptionsBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfOptions](pdfoptions/)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Hämtar eller ställer in standardersättningsteckensnittet (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagerteckensnitt i PSD-filen inte presenteras i systemet). För att ta korrekt namn på standardteckensnitt kan nästa kodavsnitt användas : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familjer = col.Families; sträng defaultFontName = familjer[0]. PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Alternativen för flera sidor |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize/) { get; set; } | Hämtar eller ställer in storleken på sidan. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions/) { get; set; } | PDF-kärnalternativen |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | Hämtar eller ställer in metadata för dokument. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Hämtar eller ställer in XMP-metadatabehållaren. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonar den här instansen. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |

### Exempel

Följande exempel visar hur du kan exportera Adobe Illustrator-filer till PDF-format i Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Följande exempel visar att AsposePSD stöder PSB-filer som exporteras till ett PSD-format.

```csharp
[C#]

// Stöd för att spara PSB som PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Följande kod sparar PsdImage som PDF-dokument med valbar text.

```csharp
[C#]

// Att spara PSD i PDF ger inte valbar text
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Följande exempel visar stödet för att exportera PsdImage till Pdf-format.

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

### Se även

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namnutrymme [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* hopsättning [Aspose.PSD](../../)


