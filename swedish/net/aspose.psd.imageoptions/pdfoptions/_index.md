---
title: "Klass PdfOptions"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.ImageOptions.PdfOptions klass. PDF‑alternativen"
type: docs
weight: 5360
url: /sv/net/aspose.psd.imageoptions/pdfoptions/
---
{{< psd/tize >}}
## PdfOptions class

PDF-alternativen.

```csharp
public class PdfOptions : ImageOptionsBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfOptions](pdfoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Hämtar eller anger en hint för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD‑filen inte finns i systemet). För att få rätt namn på standardfonten kan följande kodsnutt användas: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Hämtar eller anger ett värde som indikerar om [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Alternativen för flersidiga |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize/) { get; set; } | Hämtar eller anger sidans storlek. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Hämtar eller anger färgpaletten. |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions/) { get; set; } | PDF‑kärnalternativen |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | Hämtar eller anger metadata för dokumentet. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Hämtar eller anger händelsehanteraren för framsteg. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Hämtar eller anger upplösningsinställningarna. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Hämtar eller anger källan för att skapa bilden i. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Hämtar eller anger vektor‑rasteriseringsalternativen. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Hämtar eller anger XMP-metadatabehållaren. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonar detta objekt. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |

## Exempel

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

Följande exempel visar att AsposePSD stöder PSB-filer som exporteras till PSD-format.

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

Följande kod sparar PsdImage som PDF-dokument med markerbar text.

```csharp
[C#]

// Att spara PSD till PDF ger ingen markerbar text
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
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


