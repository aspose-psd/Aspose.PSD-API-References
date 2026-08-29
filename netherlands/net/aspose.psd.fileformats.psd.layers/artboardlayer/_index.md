---
title: "Klasse ArtboardLayer"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.ArtboardLayer klasse. De artboard-laagklasse"
type: docs
weight: 1990
url: /nl/net/aspose.psd.fileformats.psd.layers/artboardlayer/
---
{{< psd/tize >}}
## ArtboardLayer class

De artboard-laagklasse.

```csharp
public sealed class ArtboardLayer : LayerGroup
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Haalt of stelt een waarde in die aangeeft of de palette automatisch wordt aangepast. |
| override [BackgroundColor](../../aspose.psd.fileformats.psd.layers/artboardlayer/backgroundcolor/) { get; set; } | Haalt of stelt de artboard-achtergrondkleur in. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Haalt het aantal bits per pixel van de afbeelding op. |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers/layer/blendclippedelements/) { get; set; } | Haalt of stelt de mengmodus van het bijgesneden element in. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Haalt de mengopties op. |
| override [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layergroup/blendmodekey/) { get; set; } | Haalt of stelt de blend mode key in. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Haalt de blend-modus handtekening op. |
| override [Bottom](../../aspose.psd.fileformats.psd.layers/artboardlayer/bottom/) { get; set; } |  |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Haalt de afbeeldinggrenzen op. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Geeft of stelt de buffergroottehint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Haalt of stelt de kanaalinformatie in. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Haalt het aantal kanalen van de laag op. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Haalt of stelt de laagclip in. 0 = basis, 1 = niet-basis. |
| [Container](../../aspose.psd/image/container/) { get; } | Haalt de [`Image`](../../aspose.psd/image/) container op. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Haalt de gegevensstroom van het object op. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Haalt of stelt de weergavenaam van de laag in. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Haalt de lengte van extra laaginformatie op in bytes. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Haalt een bestandsformaatwaarde op. |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Haalt of stelt de laagvuller in. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Haalt of stelt de vulopaciteit in. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Haalt of stelt de laagvlaggen in. bit 0 = transparantie beschermd; bit 1 = zichtbaar; bit 2 = verouderd; bit 3 = 1 voor Photoshop 5.0 en later, geeft aan of bit 4 nuttige informatie bevat; bit 4 = pixelgegevens irrelevant voor het uiterlijk van het document. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Haalt een waarde op die aangeeft of deze instantie een alfa-kanaal heeft. |
| override [HasBackgroundColor](../../aspose.psd.fileformats.psd.layers/artboardlayer/hasbackgroundcolor/) { get; } | Haalt of stelt een waarde in die aangeeft of `ArtboardLayer` de achtergrondkleur heeft. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Haalt een waarde op die aangeeft of de afbeelding een transparante kleur heeft. |
| override [Height](../../aspose.psd.fileformats.psd.layers/artboardlayer/height/) { get; } |  |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Haalt of stelt de horizontale resolutie, in pixels per inch, van deze [`RasterImage`](../../aspose.psd/rasterimage/) in. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Haalt de opaciteit van deze afbeelding op. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Haalt of stelt de interruptmonitor in. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Haalt een waarde op die aangeeft of afbeeldingsgegevens momenteel in de cache staan. |
| [IsOpen](../../aspose.psd.fileformats.psd.layers/layergroup/isopen/) { get; set; } | Haalt of stelt in of de map geopend is; indien ingesteld op `true` zal de groep bij opstarten in de geopende toestand zijn, anders in geminimaliseerde toestand. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Haalt een waarde op die aangeeft of het laden van ruwe gegevens beschikbaar is. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of de laag zichtbaar is |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Haalt een waarde op die aangeeft of deze instantie zichtbaar is in de groep (Als de laag niet in een groep zit, betekent dit de hoofdgroep). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Haalt de gegevens van de laagmengbereiken op of stelt deze in. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Haalt de aanmaakdatum en -tijd van de laag op of stelt deze in. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Haalt de vergrendeling van de laag op of stelt deze in. Merk op dat als de vlag LayerFlags.TransparencyProtected is ingesteld, deze wordt overschreven door de vergrendelingsvlag van de laag. Om de vlag LayerFlags.TransparencyProtected terug te geven, moet de laagoptie layer.Flags &#x7C;= LayerFlags.TransparencyProtected worden toegepast |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Haalt de maskergegevens van de laag op of stelt deze in. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Haalt de laagopties op. |
| [Layers](../../aspose.psd.fileformats.psd.layers/layergroup/layers/) { get; } | Haalt de lagen op in de laaggroep |
| override [Left](../../aspose.psd.fileformats.psd.layers/artboardlayer/left/) { get; set; } |  |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Haalt de totale laaglengte in bytes op. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Haalt de laagnaam op of stelt deze in. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Haalt de laagopaciteit op of stelt deze in. 0 = transparant, 255 = ondoorzichtig. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Haalt het kleurenpalet op of stelt dit in. Het kleurenpalet wordt niet gebruikt wanneer pixels direct worden weergegeven. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of de afbeeldingscomponenten voorvermenigvuldigd moeten worden. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Haalt de aangepaste kleuromschakelaar op of stelt deze in. |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Haalt het ruwe gegevensformaat op. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Haalt de huidige ruwe gegevensinstellingen op. Merk op dat bij het gebruik van deze instellingen de gegevens zonder conversie worden geladen. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Haalt de fallback-index op of stelt deze in die moet worden gebruikt wanneer de paletindex buiten de grenzen valt |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Haalt de geïndexeerde kleuromschakelaar op of stelt deze in |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Haalt de ruwe regelgrootte in bytes op. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Haalt de laagbronnen op of stelt deze in. |
| override [Right](../../aspose.psd.fileformats.psd.layers/artboardlayer/right/) { get; set; } |  |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Haalt de decoratieve bladkleurmarkering in de lagenlijst op of stelt deze in |
| [Size](../../aspose.psd/image/size/) { get; } | Haalt de afbeeldingsgrootte op. |
| override [Top](../../aspose.psd.fileformats.psd.layers/artboardlayer/top/) { get; set; } |  |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Haalt de transparante kleur van de afbeelding op. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of de XMP-metadata moet worden bijgewerkt. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Haalt een waarde op die aangeeft of het afbeeldingspalet wordt gebruikt. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Haalt een waarde op of stelt deze in die aangeeft of ruwe gegevens moeten worden geladen wanneer het laden van ruwe gegevens beschikbaar is. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Haalt de verticale resolutie, in pixels per inch, van deze [`RasterImage`](../../aspose.psd/rasterimage/) op of stelt deze in. |
| override [Width](../../aspose.psd.fileformats.psd.layers/artboardlayer/width/) { get; } |  |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Haalt de XMP-metadata op of stelt deze in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.psd.layers/layergroup/addlayer/)(Layer) | Voegt de laag toe aan de laaggroep. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/)(string, int) | Voegt de laaggroep toe. |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Voegt het masker toe aan de huidige laag. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Past de helderheid van de afbeelding aan. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Afbeeldingscontrast |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Gamma-correctie van een afbeelding. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Gamma-correctie van een afbeelding. |
| [ApplyLayerMask](../../aspose.psd.fileformats.psd.layers/layer/applylayermask/)() | Past het laagmasker toe op de laag en verwijdert vervolgens het masker. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Binarisatie van een afbeelding met behulp van Bradleys adaptieve drempelalgoritme met integrale afbeeldingsdrempeling. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Binarisatie van een afbeelding met behulp van Bradleys adaptieve drempelalgoritme met integrale afbeeldingsdrempeling. |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarisatie van een afbeelding met een vooraf gedefinieerde drempel. |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarisatie van een afbeelding met Otsu-drempeling. |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Cachet de gegevens en zorgt ervoor dat er geen extra gegevens worden geladen vanuit de onderliggende [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bepaalt of de afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt vertegenwoordigd door de meegegeven opslagopties. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Bijsnijden van de afbeelding. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Afbeelding bijsnijden met verschuivingen. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Disposeert de huidige instantie. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Voert dithering uit op de huidige afbeelding. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Voert dithering uit op de huidige afbeelding. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Tekent de afbeelding op de laag. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtert de opgegeven rechthoek. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Haalt een 32-bit ARGB-pixel van de afbeelding op. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Haalt de standaard 32-bit ARGB-pixelarray op. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Haalt de standaardopties op. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Haalt de standaardpixelarray op met behulp van de gedeeltelijke pixelloader. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Haalt de standaard ruwe gegevensarray op. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Haalt de standaard ruwe gegevensarray op met behulp van de gedeeltelijke pixelloader. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Retourneert een hashcode voor deze instantie. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Haalt de datum en tijd op waarop de bronafbeelding voor het laatst is gewijzigd. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Haalt de opties op op basis van de oorspronkelijke bestandsinstellingen. Dit kan handig zijn om de bitsdiepte en andere parameters van de oorspronkelijke afbeelding ongewijzigd te houden. Bijvoorbeeld, als we een zwart-wit PNG-afbeelding met 1 bit per pixel laden en deze vervolgens opslaan met de [`Save`](../../aspose.psd/datastreamsupporter/save/) methode, wordt een PNG-afbeelding met 8-bit per pixel gegenereerd. Om dit te voorkomen en een PNG-afbeelding met 1-bit per pixel op te slaan, gebruik deze methode om de bijbehorende opslagopties te verkrijgen en geef ze door aan de [`Save`](../../aspose.psd/image/save/) methode als tweede parameter. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Haalt een afbeeldingspixel op. Prestatiewaarschuwing: Vermijd het gebruik van deze methode om over alle afbeeldingspixels te itereren, omdat dit kan leiden tot aanzienlijke prestatieproblemen. Voor efficiëntere pixelmanipulatie, gebruik de `LoadArgb32Pixels` methode om de volledige pixelarray in één keer op te halen. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Haalt de scheefstandhoek op. Deze methode is toepasbaar op gescande tekstdocumenten om de scheefstandhoek bij het scannen te bepalen. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Transformatie van een afbeelding naar zijn grijswaardenrepresentatie |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Laadt 32-bit ARGB-pixels. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Laadt 64-bit ARGB-pixels. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Laadt pixels in CMYK-formaat. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Laadt pixels in CMYK-formaat. Deze methode is verouderd. Gebruik alstublieft de effectievere [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/) methode. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Laadt 32-bit ARGB-pixels gedeeltelijk per pakketten. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Laadt pixels gedeeltelijk per pakketten. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Laadt pixels. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Laadt ruwe gegevens. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Laadt ruwe gegevens. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | Voegt de laag samen met de opgegeven laag |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normaliseert de hoek. Deze methode is toepasbaar op gescande tekstdocumenten om een scheve scan te verwijderen. Deze methode gebruikt de [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) en [`Rotate`](../../aspose.psd/rasterimage/rotate/) methoden. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normaliseert de hoek. Deze methode is toepasbaar op gescande tekstdocumenten om een scheve scan te verwijderen. Deze methode gebruikt de [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) en [`Rotate`](../../aspose.psd/rasterimage/rotate/) methoden. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Leest de volledige scanlijn op basis van de opgegeven scanlijnindex. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Leest de volledige scanlijn op basis van de opgegeven scanlijnindex. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfa-waarde om vloeiende randen te behouden. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfa-waarde om vloeiende randen te behouden. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Vervangt alle niet-transparante kleuren door een nieuwe kleur en behoudt de oorspronkelijke alfa-waarde om vloeiende randen te behouden. Opmerking: als je het toepast op afbeeldingen zonder transparantie, worden alle kleuren vervangen door één enkele kleur. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Vervangt alle niet-transparante kleuren door een nieuwe kleur en behoudt de oorspronkelijke alfa-waarde om vloeiende randen te behouden. Opmerking: als je het toepast op afbeeldingen zonder transparantie, worden alle kleuren vervangen door één enkele kleur. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Wijzigt de grootte van de afbeelding. De standaard NearestNeighbourResample wordt gebruikt. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Wijzigt de grootte van de afbeelding. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Wijzigt de grootte van de afbeelding. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Wijzigt de hoogte proportioneel. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Wijzigt de hoogte proportioneel. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Wijzigt de hoogte proportioneel. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Wijzigt de breedte proportioneel. De standaard NearestNeighbourResample wordt gebruikt. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Wijzigt de breedte proportioneel. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Wijzigt de breedte proportioneel. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Roteer de afbeelding rond het centrum. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Roteer de afbeelding rond het centrum. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Roteert, spiegelt of roteert en spiegelt de afbeelding. |
| [Save](../../aspose.psd/image/save/)() | Slaat de afbeeldingsgegevens op in de onderliggende stream. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Slaat de gegevens van het object op in de opgegeven stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Slaat de 32-bit ARGB-pixels op. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Slaat de pixels op. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Slaat de pixels op. Deze methode is verouderd. Gebruik alstublieft de meer effectieve [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) methode. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Slaat de pixels op. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Slaat de ruwe gegevens op. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Stelt een 32-bit ARGB-pixel van de afbeelding in voor de opgegeven positie. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Stelt het kleurenpalet van de afbeelding in. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Stelt een afbeeldingspixel in voor de opgegeven positie. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Stelt de resolutie in voor deze [`RasterImage`](../../aspose.psd/rasterimage/). |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Maakt een ondiepe kopie van de huidige laag. Zie [https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) voor uitleg. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Converteert rasterafbeelding naar de bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Schrijft de volledige scanregel naar de opgegeven scanregelindex. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Schrijft de volledige scanregel naar de opgegeven scanregelindex. |

## Voorbeelden

De volgende code demonstreert de ondersteuning voor het exporteren van ArtboardLayer als afzonderlijke afbeeldingen en als één afbeelding.

```csharp
[C#]

string srcFile = "artboard2.psd";

string outFilePng0 = "art0.png";
string outFilePng1 = "art1.png";
string outFilePng2 = "art2.png";
string outFilePng3 = "art3.png";

using (var psdImage = (PsdImage)Image.Load(srcFile))
{
    ArtboardLayer art1 = (ArtboardLayer)psdImage.Layers[4];
    ArtboardLayer art2 = (ArtboardLayer)psdImage.Layers[9];
    ArtboardLayer art3 = (ArtboardLayer)psdImage.Layers[14];

    var pngSaveOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
    art1.Save(outFilePng1, pngSaveOptions);
    art2.Save(outFilePng2, pngSaveOptions);
    art3.Save(outFilePng3, pngSaveOptions);

    psdImage.Save(outFilePng0, pngSaveOptions);
}
```

### Zie ook

* class [LayerGroup](../layergroup/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


