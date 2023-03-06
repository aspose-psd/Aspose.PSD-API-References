---
title: Class AiImage
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Ai.AiImage klas. De Adobe Illustrator AI Image
type: docs
weight: 1260
url: /nl/net/aspose.psd.fileformats.ai/aiimage/
---
## AiImage class

De Adobe Illustrator (AI) Image

```csharp
public sealed class AiImage : Image
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [AiImage](aiimage/)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Haalt of stelt een waarde in die aangeeft of het palet automatisch wordt aangepast. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Haalt of stelt een waarde in voor de achtergrondkleur. |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | Haalt het aantal beeldbits per pixel op. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Haalt de afbeeldingsgrenzen op. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Haalt de hint voor de buffergrootte op of stelt deze in, de maximale toegestane grootte voor alle interne buffers. |
| [Container](../../aspose.psd/image/container/) { get; } | Krijgt de[`Image`](../../aspose.psd/image/) container. |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | Haalt de gegevenssectie op. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Haalt de gegevensstroom van het object op. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | Krijgt een waarde van bestandsformaat |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | Krijgt de afrondingssectie. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of de afbeelding een achtergrondkleur heeft. |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | Haalt de kop op. |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | Haalt de afbeeldingshoogte op. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Haalt of stelt de interruptmonitor in. |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | Krijgt een waarde die aangeeft of de gegevens van het object momenteel in de cache zijn opgeslagen en dat er geen gegevens moeten worden gelezen. |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | Haalt de laagsecties op. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Haalt of stelt het kleurenpalet in. Het kleurenpalet wordt niet gebruikt wanneer pixels direct worden weergegeven. |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | Krijgt de installatiesectie. |
| [Size](../../aspose.psd/image/size/) { get; } | Haalt de afbeeldingsgrootte op. |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | Krijgt de versie van Adobe Illustrator format |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | Haalt de beeldbreedte op. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | Voegt de AI-laagsectie toe. |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | Cache de gegevens op en zorgt ervoor dat er geen aanvullende gegevens worden geladen vanaf de onderliggende gegevens[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bepaalt of de afbeelding kan worden opgeslagen in de opgegeven bestandsindeling die wordt weergegeven door de doorgegeven opslagopties. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Krijgt de standaardopties. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Krijgt de opties op basis van de originele bestandsinstellingen. Dit kan handig zijn om de bitdiepte en andere parameters van de originele afbeelding ongewijzigd te laten. Als we bijvoorbeeld een zwart-wit PNG-afbeelding laden met 1 bit per pixel en sla het op met the [`Save`](../../aspose.psd/datastreamsupporter/save/) methode, wordt de uitgevoerde PNG-afbeelding met 8-bits per pixel geproduceerd. Om dit te voorkomen en PNG-afbeelding met 1-bits per pixel op te slaan, gebruikt u deze methode om overeenkomstige opslagopties te krijgen en deze door te geven aan de[`Save`](../../aspose.psd/image/save/)methode als de tweede parameter. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Wijzigt de grootte van de afbeelding. De standaardLeftTopToLeftTopwordt gebruikt. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | Pas de grootte van de afbeelding aan. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | Pas de grootte van de afbeelding aan. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Pas de hoogte proportioneel aan. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Pas de hoogte proportioneel aan. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Pas de hoogte proportioneel aan. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Pas de breedte proportioneel aan. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Pas de breedte proportioneel aan. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Pas de breedte proportioneel aan. |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | Roteert, spiegelt of roteert en spiegelt de afbeelding. |
| [Save](../../aspose.psd/image/save/)() | Slaat de afbeeldingsgegevens op in de onderliggende stream. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Slaat de gegevens van het object op in de opgegeven stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Slaat de objectgegevens op naar de opgegeven bestandslocatie. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Slaat de afbeeldingsgegevens op in de opgegeven stream in de opgegeven bestandsindeling volgens de opslagopties. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Slaat de objectgegevens op naar de opgegeven bestandslocatie. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Slaat de afbeeldingsgegevens op in de opgegeven stream in de opgegeven bestandsindeling volgens de opslagopties. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties. |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | Stelt het afbeeldingspalet in. |

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

Het volgende voorbeeld laat zien hoe u een AI-bestand kunt exporteren naar PSD- en PNG-indeling in Aspose.PSD

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Het volgende voorbeeld demonstreert de ondersteuning van het exporterende Ai-formaat naar PSD-, PNG-, JPG-, GIF- en TIF-formaten.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### Zie ook

* class [Image](../../aspose.psd/image/)
* naamruimte [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* montage [Aspose.PSD](../../)


