---
title: Class RasterImage
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.RasterImage klas. Vertegenwoordigt een rasterafbeelding die grafische rasterbewerkingen ondersteunt.
type: docs
weight: 5320
url: /nl/net/aspose.psd/rasterimage/
---
## RasterImage class

Vertegenwoordigt een rasterafbeelding die grafische rasterbewerkingen ondersteunt.

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Haalt of stelt een waarde in die aangeeft of het palet automatisch wordt aangepast. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Haalt of stelt een waarde in voor de achtergrondkleur. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Haalt het aantal beeldbits per pixel op. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Haalt de afbeeldingsgrenzen op. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Haalt de hint voor de buffergrootte op of stelt deze in, de maximale toegestane grootte voor alle interne buffers. |
| [Container](../../aspose.psd/image/container/) { get; } | Krijgt de[`Image`](../image/) container. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Haalt de gegevensstroom van het object op. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Krijgt een waarde van bestandsformaat |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | Krijgt een waarde die aangeeft of deze instantie alfa heeft. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of de afbeelding een achtergrondkleur heeft. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Krijgt een waarde die aangeeft of de afbeelding een transparante kleur heeft. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Haalt de afbeeldingshoogte op. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Haalt of stelt de horizontale resolutie, in pixels per inch, hiervan in`RasterImage` . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Krijgt dekking van deze afbeelding. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Haalt of stelt de interruptmonitor in. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Krijgt een waarde die aangeeft of de gegevens van het object momenteel in de cache zijn opgeslagen en dat er geen gegevens moeten worden gelezen. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Krijgt een waarde die aangeeft of het laden van onbewerkte gegevens beschikbaar is. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Haalt of stelt het kleurenpalet in. Het kleurenpalet wordt niet gebruikt wanneer pixels direct worden weergegeven. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of de afbeeldingscomponenten vooraf moeten worden vermenigvuldigd. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Haalt de aangepaste kleuromzetter op of stelt deze in |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Haalt het ruwe gegevensformaat op. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Haalt de huidige instellingen voor onbewerkte gegevens op. Merk op dat wanneer u deze instellingen gebruikt, de gegevens worden geladen zonder conversie. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Haalt de fallback-index op of stelt deze in om te gebruiken wanneer de paletindex buiten de grenzen ligt |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Haalt de geïndexeerde kleuromzetter op of stelt deze in |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Krijgt de onbewerkte regelgrootte in bytes. |
| [Size](../../aspose.psd/image/size/) { get; } | Haalt de afbeeldingsgrootte op. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Krijgt de transparante kleur van de afbeelding. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of de XMP-metagegevens moeten worden bijgewerkt. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of het laden van onbewerkte gegevens moet worden gebruikt wanneer het laden van onbewerkte gegevens beschikbaar is. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Hiermee wordt de verticale resolutie, in pixels per inch, hiervan opgehaald of ingesteld`RasterImage` . |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Haalt de beeldbreedte op. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Haalt de XMP-metadata op of stelt deze in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.psd/rasterimage/adjustbrightness/)(int) | Aanpassing van een helderheid voor afbeelding. |
| virtual [AdjustContrast](../../aspose.psd/rasterimage/adjustcontrast/)(float) | Afbeelding contrasterend |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma)(float) | Gammacorrectie van een afbeelding. |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma_1)(float, float, float) | Gammacorrectie van een afbeelding. |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley)(double) | Binarisatie van een afbeelding met behulp van Bradley's adaptieve drempelwaarde-algoritme met behulp van de integrale afbeeldingsdrempelwaarde |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley_1)(double, int) | Binarisatie van een afbeelding met behulp van Bradley's adaptieve drempelwaarde-algoritme met behulp van de integrale afbeeldingsdrempelwaarde |
| virtual [BinarizeFixed](../../aspose.psd/rasterimage/binarizefixed/)(byte) | Binarisatie van een afbeelding met vooraf gedefinieerde drempel |
| virtual [BinarizeOtsu](../../aspose.psd/rasterimage/binarizeotsu/)() | Binarisatie van een afbeelding met Otsu-drempels |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Cache de gegevens op en zorgt ervoor dat er geen aanvullende gegevens worden geladen vanaf de onderliggende gegevens[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bepaalt of de afbeelding kan worden opgeslagen in de opgegeven bestandsindeling die wordt weergegeven door de doorgegeven opslagopties. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop)(Rectangle) | Snijdt de opgegeven rechthoek bij. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop_1)(int, int, int, int) | Afbeelding bijsnijden met verschuivingen. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |
| [Dither](../../aspose.psd/rasterimage/dither/#dither)(DitheringMethod, int) | Voert dithering uit op de huidige afbeelding. |
| abstract [Dither](../../aspose.psd/rasterimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Voert dithering uit op de huidige afbeelding. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtert de opgegeven rechthoek. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Krijgt een afbeelding 32-bits ARGB-pixel. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Hiermee krijgt u de standaard 32-bits ARGB-pixelarray. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Krijgt de standaardopties. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Haalt de standaard pixelarray op met gedeeltelijke pixellader. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata)(Rectangle, RawDataSettings) | Haalt de standaard onbewerkte gegevensarray op. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Haalt de standaard onbewerkte gegevensarray op met behulp van een gedeeltelijke pixellader. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Haalt de datum en tijd op waarop de bronafbeelding voor het laatst is gewijzigd. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Krijgt de opties op basis van de originele bestandsinstellingen. Dit kan handig zijn om de bitdiepte en andere parameters van de originele afbeelding ongewijzigd te laten. Als we bijvoorbeeld een zwart-wit PNG-afbeelding laden met 1 bit per pixel en sla het op met the [`Save`](../datastreamsupporter/save/) methode, wordt de uitgevoerde PNG-afbeelding met 8-bits per pixel geproduceerd. Om dit te voorkomen en PNG-afbeelding met 1-bits per pixel op te slaan, gebruikt u deze methode om overeenkomstige opslagopties te krijgen en deze door te geven aan de[`Save`](../image/save/)methode als de tweede parameter. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Krijgt een beeldpixel. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Hiermee wordt de schuine hoek bepaald. Deze methode is van toepassing op gescande tekstdocumenten, om de schuine hoek tijdens het scannen te bepalen. |
| virtual [Grayscale](../../aspose.psd/rasterimage/grayscale/)() | Transformatie van een afbeelding naar zijn grijswaardenweergave |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Laadt 32-bits ARGB-pixels. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Laadt 64-bits ARGB-pixels. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Laadt pixels in CMYK-formaat. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Laadt 32-bits ARGB-pixels gedeeltelijk per pakket. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Laadt pixels gedeeltelijk per pakket. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Laadt pixels. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Laadt onbewerkte gegevens. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Laadt onbewerkte gegevens. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle)() | Normaliseert de hoek. Deze methode is van toepassing op gescande tekstdocumenten om de scheve scan te verwijderen. Deze methode gebruikt[`GetSkewAngle`](./getskewangle/) En[`Rotate`](./rotate/) methoden. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle_1)(bool, Color) | Normaliseert de hoek. Deze methode is van toepassing op gescande tekstdocumenten om de scheve scan te verwijderen. Deze methode gebruikt[`GetSkewAngle`](./getskewangle/) En[`Rotate`](./rotate/) methoden. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Leest de hele scanlijn volgens de opgegeven scanlijnindex. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Leest de hele scanlijn volgens de opgegeven scanlijnindex. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor)(Color, byte, Color) | Vervangt de ene kleur door de andere met toegestaan verschil en behoudt de oorspronkelijke alfawaarde om vloeiende randen te voorkomen. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor_1)(int, byte, int) | Vervangt de ene kleur door de andere met toegestaan verschil en behoudt de oorspronkelijke alfawaarde om vloeiende randen te voorkomen. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors)(Color) | Vervangt alle niet-transparante kleuren door nieuwe kleuren en behoudt de oorspronkelijke alfawaarde om vloeiende randen te besparen. Opmerking: als u het gebruikt op afbeeldingen zonder transparantie, worden alle kleuren vervangen door een enkele kleur. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Vervangt alle niet-transparante kleuren door nieuwe kleuren en behoudt de oorspronkelijke alfawaarde om vloeiende randen te besparen. Opmerking: als u het gebruikt op afbeeldingen zonder transparantie, worden alle kleuren vervangen door een enkele kleur. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Wijzigt de grootte van de afbeelding. De standaardLeftTopToLeftTopwordt gebruikt. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_1)(int, int, ImageResizeSettings) | Pas de grootte van de afbeelding aan met uitgebreide opties. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_2)(int, int, ResizeType) | Pas de grootte van de afbeelding aan. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Pas de hoogte proportioneel aan. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Pas de hoogte proportioneel aan. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Pas de hoogte proportioneel aan. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Pas de breedte proportioneel aan. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Pas de breedte proportioneel aan. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Pas de breedte proportioneel aan. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate)(float) | Afbeelding roteren rond het midden. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate_1)(float, bool, Color) | Afbeelding roteren rond het midden. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Roteert, spiegelt of roteert en spiegelt de afbeelding. |
| [Save](../../aspose.psd/image/save/)() | Slaat de afbeeldingsgegevens op in de onderliggende stream. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Slaat de gegevens van het object op in de opgegeven stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Slaat de objectgegevens op naar de opgegeven bestandslocatie. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Slaat de afbeeldingsgegevens op in de opgegeven stream in de opgegeven bestandsindeling volgens de opslagopties. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Slaat de objectgegevens op naar de opgegeven bestandslocatie. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties. |
| override [Save](../../aspose.psd/rasterimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Slaat de afbeeldingsgegevens op in de opgegeven stream in de opgegeven bestandsindeling volgens de opslagopties. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Slaat de 32-bits ARGB-pixels op. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Slaat de pixels op. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Slaat de pixels op. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Slaat de onbewerkte gegevens op. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Stelt een afbeelding 32-bits ARGB-pixel in voor de opgegeven positie. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Stelt het afbeeldingspalet in. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Stelt een afbeeldingspixel in voor de opgegeven positie. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Stelt de resolutie hiervoor in`RasterImage` . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Converteert rasterafbeelding naar de bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Schrijft de hele scanlijn naar de opgegeven scanlijnindex. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Schrijft de hele scanlijn naar de opgegeven scanlijnindex. |

### Voorbeelden

Dit voorbeeld laat zien hoe Pixel-informatie in een array van typekleur wordt geladen, de array wordt gemanipuleerd en teruggezet naar de afbeelding. Om deze bewerkingen uit te voeren, maakt dit voorbeeld een nieuw afbeeldingsbestand (in PSD-indeling) met behulp van het MemoryStream-object.

```csharp
[C#]

//Maak een exemplaar van MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    // Maak een instantie van PsdOptions en stel de verschillende eigenschappen in, inclusief de eigenschap Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Maak een exemplaar van Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        // Haal de pixels van de afbeelding op door het gebied op te geven als afbeeldingsgrens
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Loop over de array en stel de kleur in van de alternatieve geïndexeerde pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                // Stel de geïndexeerde pixelkleur in op geel
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                // Stel de geïndexeerde pixelkleur in op blauw
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        // Pas de pixelwijzigingen toe op de afbeelding
        image.SavePixels(image.Bounds, pixels);

        // sla alle veranderingen op.
        image.Save();
    }

    // Schrijf MemoryStream naar bestand
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Zie ook

* class [Image](../image/)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader/)
* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


