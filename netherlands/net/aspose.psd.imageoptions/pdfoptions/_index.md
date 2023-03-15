---
title: Class PdfOptions
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.ImageOptions.PdfOptions klas. De PDFopties.
type: docs
weight: 4870
url: /nl/net/aspose.psd.imageoptions/pdfoptions/
---
## PdfOptions class

De PDF-opties.

```csharp
public class PdfOptions : ImageOptionsBase
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PdfOptions](pdfoptions/)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Haalt de hint voor de buffergrootte op of stelt deze in, de maximale toegestane grootte voor alle interne buffers. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Haalt het standaardvervangende lettertype op of stelt het in (lettertype dat zal worden gebruikt om tekst te tekenen bij het exporteren naar raster, als het bestaande laaglettertype in het PSD-bestand niet in het systeem wordt gepresenteerd). Om de juiste naam van het standaardlettertype te gebruiken, kan het volgende codefragment worden gebruikt : System.Drawing.Text.InstalledFontCollection col = nieuw System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = nieuwe PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | De opties voor meerdere pagina's |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize/) { get; set; } | Hiermee wordt de grootte van de pagina opgehaald of ingesteld. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Haalt of stelt het kleurenpalet in. |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions/) { get; set; } | De PDF-kernopties |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | Haalt of stelt metadata in voor document. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Haalt de voortgangsgebeurtenishandler op of stelt deze in. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Haalt of stelt de resolutie-instellingen in. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Haalt of stelt de bron in om een afbeelding in te maken. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Haalt of stelt de vectorrasteropties in. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Haalt de XMP-metagegevenscontainer op of stelt deze in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Kloont deze instantie. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |

### Voorbeelden

Het volgende voorbeeld laat zien hoe u Adobe Illustrator-bestanden kunt exporteren naar PDF-indeling in Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Het volgende voorbeeld laat zien dat AsposePSD ondersteuning biedt voor het exporteren van PSB-bestanden naar een PSD-indeling.

```csharp
[C#]

// Ondersteuning voor het opslaan van PSB als PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

De volgende code slaat PsdImage op als PDF-document met selecteerbare tekst.

```csharp
[C#]

// PSD opslaan in PDF biedt geen selecteerbare tekst
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Het volgende voorbeeld demonstreert de ondersteuning van het exporteren van PsdImage naar PDF-indeling.

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

### Zie ook

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* naamruimte [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* montage [Aspose.PSD](../../)


