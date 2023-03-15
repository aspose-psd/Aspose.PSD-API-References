---
title: Class PsdImage
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.PsdImage klas. Definieert de PsdImageklasse die de mogelijkheid biedt om PSDbestanden te laden te bewerken en op te slaan evenals eigenschappen bij te werken watermerken toe te voegen grafische bewerkingen uit te voeren of de ene bestandsindeling naar de andere te converteren. Aspose.PSD ondersteunt importeren als een laag en exporteren naar de volgende formaten Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb samen met export naar Pdf met selecteerbare tekst
type: docs
weight: 3590
url: /nl/net/aspose.psd.fileformats.psd/psdimage/
---
## PsdImage class

Definieert de PsdImage-klasse die de mogelijkheid biedt om PSD-bestanden te laden, te bewerken en op te slaan, evenals eigenschappen bij te werken, watermerken toe te voegen, grafische bewerkingen uit te voeren of de ene bestandsindeling naar de andere te converteren. Aspose.PSD ondersteunt importeren als een laag en exporteren naar de volgende formaten: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb samen met export naar Pdf met selecteerbare tekst

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | Initialiseert een nieuw exemplaar van het`PsdImage`klasse van bestaande rasterafbeelding (geen psd-afbeelding) met RGB-kleurmodus met 4 kanalen 8 bit/kanaal en geen compressie. |
| [PsdImage](psdimage/#constructor_4)(Stream) | Initialiseert een nieuw exemplaar van het`PsdImage` klasse van opgegeven pad van rasterafbeelding (geen psd-afbeelding in stream). Gebruikt om psd-afbeelding te initialiseren met standaardparameters - Kleurmodus - RGB, 4 kanalen, 8 bit per kanaal, Compressie - Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | Initialiseert een nieuw exemplaar van het`PsdImage` klasse van opgegeven pad van rasterafbeelding (geen psd-afbeelding in pad). Gebruikt om psd-afbeelding te initialiseren met standaardparameters - Kleurmodus - RGB, 4 kanalen, 8 bit per kanaal, Compressie - Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | Initialiseert een nieuw exemplaar van het`PsdImage` klasse met gespecificeerde breedte en hoogte. Gebruikt om lege psd-afbeelding te initialiseren. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Initialiseert een nieuw exemplaar van het`PsdImage` klasse van bestaande rasterafbeelding (geen psd-afbeelding) met constructorparameters. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Initialiseert een nieuw exemplaar van het`PsdImage` klasse van opgegeven pad van rasterafbeelding (geen psd-afbeelding in stream) met constructorparameters. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Initialiseert een nieuw exemplaar van het`PsdImage` klasse van opgegeven pad van rasterafbeelding (geen psd-afbeelding in pad) met constructorparameters. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Initialiseert een nieuw exemplaar van het`PsdImage` klasse met gespecificeerde breedte, hoogte, paletter, kleurmodus, aantal kanalen en kanaalbitlengte en gespecificeerde parameters voor compressiemodus. Gebruikt om lege psd-afbeelding te initialiseren. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | Haalt of stelt de actieve laag in. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Haalt of stelt een waarde in die aangeeft of het palet automatisch wordt aangepast. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Haalt of stelt een waarde in voor de achtergrondkleur. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | Haalt de bits per kanaal op. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | Haalt het aantal beeldbits per pixel op. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Haalt de afbeeldingsgrenzen op. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Haalt de hint voor de buffergrootte op of stelt deze in, de maximale toegestane grootte voor alle interne buffers. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | Haalt het aantal PSD-kanalen op. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | Hiermee wordt het CMYK-kleurprofiel voor CMYK PSD-afbeeldingen opgehaald of ingesteld. Moet gekoppeld zijn aan RgbColorProfile voor correcte kleurconversie. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | Krijgt of stelt de kleurmodus in. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | Haalt de compressiemethode op. |
| [Container](../../aspose.psd/image/container/) { get; } | Krijgt de[`Image`](../../aspose.psd/image/) container. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Haalt de gegevensstroom van het object op. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | Krijgt een waarde van bestandsformaat |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | Haalt of stelt de globale hoek in. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | Krijgt de globale laagmaskerinfo. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | Haalt of stelt de globale laagbronnen in. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | Hiermee wordt het GRIJZE (monochroom) kleurprofiel voor PSD-afbeeldingen in grijstinten opgehaald of ingesteld. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | Hiermee wordt de verticale resolutie, in pixels per inch, hiervan opgehaald of ingesteld[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of de afbeelding een achtergrondkleur heeft. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | Haalt of stelt een waarde in die aangeeft of het eerste alfakanaal de transparantiegegevens voor het samengevoegde resultaat bevat bij het specificeren van laaggegevens. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Krijgt een waarde die aangeeft of de afbeelding een transparante kleur heeft. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | Haalt de afbeeldingshoogte op. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | Haalt of stelt de horizontale resolutie, in pixels per inch, hiervan in`PsdImage` . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Krijgt dekking van deze afbeelding. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | Haalt of stelt de PSD-afbeeldingsbronnen in. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Haalt of stelt de interruptmonitor in. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Krijgt een waarde die aangeeft of afbeeldingsgegevens momenteel in de cache zijn opgeslagen. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | Krijgt een waarde die aangeeft of psd-afbeelding afgevlakt is. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Krijgt een waarde die aangeeft of het laden van onbewerkte gegevens beschikbaar is. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | Haalt of stelt de PSD-lagen in. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | Haalt de gekoppelde lagenmanager op. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Haalt of stelt het kleurenpalet in. Het kleurenpalet wordt niet gebruikt wanneer pixels direct worden weergegeven. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of de afbeeldingscomponenten vooraf moeten worden vermenigvuldigd. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Haalt de aangepaste kleuromzetter op of stelt deze in |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | Haalt het ruwe gegevensformaat op. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Haalt de huidige instellingen voor onbewerkte gegevens op. Merk op dat wanneer u deze instellingen gebruikt, de gegevens worden geladen zonder conversie. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Haalt de fallback-index op of stelt deze in om te gebruiken wanneer de paletindex buiten de grenzen ligt |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Haalt de geïndexeerde kleuromzetter op of stelt deze in |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Krijgt de onbewerkte regelgrootte in bytes. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | Hiermee wordt het RGB-kleurprofiel voor CMYK PSD-afbeeldingen opgehaald of ingesteld. Moet gekoppeld zijn aan CmykColorProfile voor correcte kleurconversie. |
| [Size](../../aspose.psd/image/size/) { get; } | Haalt de afbeeldingsgrootte op. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | Haalt de slimme objectprovider op. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Krijgt de transparante kleur van de afbeelding. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of de XMP-metagegevens moeten worden bijgewerkt. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of het laden van onbewerkte gegevens moet worden gebruikt wanneer het laden van onbewerkte gegevens beschikbaar is. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | Haalt of stelt de versie in. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | Hiermee wordt de verticale resolutie, in pixels per inch, hiervan opgehaald of ingesteld`PsdImage` . |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | Haalt de beeldbreedte op. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | Haalt de XMP-metadata op of stelt deze in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | Voegt de zwart-witte aanpassingslaag toe. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | Voegt de aanpassingslaag voor helderheid/contrast toe. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | Voegt de aanpassingslaag van de kanaalmixer toe met standaardparameters |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | Voegt de aanpassingslaag voor de kleurbalans toe. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | Voegt de aanpassingslaag Curven toe. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | Voegt de belichtingsaanpassingslaag toe. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | Voegt de aanpassingslaag voor tint/verzadiging toe. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | Voegt een omgekeerde aanpassingslaag toe. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | Voegt de laag toe. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | Voegt de laaggroep toe. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | Voegt de aanpassingslaag Niveaus toe. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | Voegt de PhotoFilter-laag toe. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | Voegt een nieuwe reguliere laag toe. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | Voegt een nieuwe tekstlaag toe. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | Voegt de aanpassingslaag Levendigheid toe. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | Aanpassing van een helderheid voor afbeelding. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | Afbeelding contrasterend |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | Gammacorrectie van een afbeelding. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | Gammacorrectie van een afbeelding. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Binarisatie van een afbeelding met behulp van Bradley's adaptieve drempelwaarde-algoritme met behulp van de integrale afbeeldingsdrempelwaarde |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Binarisatie van een afbeelding met behulp van Bradley's adaptieve drempelwaarde-algoritme met behulp van de integrale afbeeldingsdrempelwaarde |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | Binarisatie van een afbeelding met vooraf gedefinieerde drempel |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Binarisatie van een afbeelding met Otsu-drempels |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Cache de gegevens op en zorgt ervoor dat er geen aanvullende gegevens worden geladen vanaf de onderliggende gegevens[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bepaalt of de afbeelding kan worden opgeslagen in de opgegeven bestandsindeling die wordt weergegeven door de doorgegeven opslagopties. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | Converteert deze afbeeldingsindeling naar de indeling die is opgegeven in opties. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | De afbeelding bijsnijden. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Afbeelding bijsnijden met verschuivingen. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Voert dithering uit op de huidige afbeelding. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Voert dithering uit op de huidige afbeelding. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | Filtert de opgegeven rechthoek. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | Maakt alle lagen plat. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Krijgt een afbeelding 32-bits ARGB-pixel. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Hiermee krijgt u de standaard 32-bits ARGB-pixelarray. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Krijgt de standaardopties. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Haalt de standaard pixelarray op met gedeeltelijke pixellader. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Haalt de standaard onbewerkte gegevensarray op. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Haalt de standaard onbewerkte gegevensarray op met behulp van een gedeeltelijke pixellader. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Haalt de datum en tijd op waarop de bronafbeelding voor het laatst is gewijzigd. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Krijgt de opties op basis van de originele bestandsinstellingen. Dit kan handig zijn om de bitdiepte en andere parameters van de originele afbeelding ongewijzigd te laten. Als we bijvoorbeeld een zwart-wit PNG-afbeelding laden met 1 bit per pixel en sla het op met the [`Save`](../../aspose.psd/datastreamsupporter/save/) methode, wordt de uitgevoerde PNG-afbeelding met 8-bits per pixel geproduceerd. Om dit te voorkomen en PNG-afbeelding met 1-bits per pixel op te slaan, gebruikt u deze methode om overeenkomstige opslagopties te krijgen en deze door te geven aan de[`Save`](../../aspose.psd/image/save/)methode als de tweede parameter. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Krijgt een beeldpixel. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Hiermee wordt de schuine hoek bepaald. Deze methode is van toepassing op gescande tekstdocumenten, om de schuine hoek tijdens het scannen te bepalen. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | Transformatie van een afbeelding naar zijn grijswaardenweergave |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Laadt 32-bits ARGB-pixels. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Laadt 64-bits ARGB-pixels. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Laadt pixels in CMYK-formaat. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Laadt 32-bits ARGB-pixels gedeeltelijk per pakket. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Laadt pixels gedeeltelijk per pakket. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Laadt pixels. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Laadt onbewerkte gegevens. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Laadt onbewerkte gegevens. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | Voegt de lagen samen. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normaliseert de hoek. Deze methode is van toepassing op gescande tekstdocumenten om de scheve scan te verwijderen. Deze methode gebruikt[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) En[`Rotate`](../../aspose.psd/rasterimage/rotate/) methoden. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normaliseert de hoek. Deze methode is van toepassing op gescande tekstdocumenten om de scheve scan te verwijderen. Deze methode gebruikt[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) En[`Rotate`](../../aspose.psd/rasterimage/rotate/) methoden. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Leest de hele scanlijn volgens de opgegeven scanlijnindex. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Leest de hele scanlijn volgens de opgegeven scanlijnindex. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Vervangt de ene kleur door de andere met toegestaan verschil en behoudt de oorspronkelijke alfawaarde om vloeiende randen te voorkomen. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | Vervangt de ene kleur door de andere met toegestaan verschil en behoudt de oorspronkelijke alfawaarde om vloeiende randen te voorkomen. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Vervangt alle niet-transparante kleuren door nieuwe kleuren en behoudt de oorspronkelijke alfawaarde om vloeiende randen te besparen. Opmerking: als u het gebruikt op afbeeldingen zonder transparantie, worden alle kleuren vervangen door een enkele kleur. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Vervangt alle niet-transparante kleuren door nieuwe kleuren en behoudt de oorspronkelijke alfawaarde om vloeiende randen te besparen. Opmerking: als u het gebruikt op afbeeldingen zonder transparantie, worden alle kleuren vervangen door een enkele kleur. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Wijzigt de grootte van de afbeelding. De standaardLeftTopToLeftTopwordt gebruikt. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Pas de grootte van de afbeelding aan. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Pas de grootte van de afbeelding aan. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Pas de hoogte proportioneel aan. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Pas de hoogte proportioneel aan. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Pas de hoogte proportioneel aan. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Pas de breedte proportioneel aan. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Pas de breedte proportioneel aan. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Pas de breedte proportioneel aan. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | Afbeelding roteren rond het midden. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | Afbeelding roteren rond het midden. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Roteert, spiegelt of roteert en spiegelt de afbeelding. |
| [Save](../../aspose.psd/image/save/)() | Slaat de afbeeldingsgegevens op in de onderliggende stream. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Slaat de gegevens van het object op in de opgegeven stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Slaat de objectgegevens op naar de opgegeven bestandslocatie. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Slaat de afbeeldingsgegevens op in de opgegeven stream in de opgegeven bestandsindeling volgens de opslagopties. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Slaat de objectgegevens op naar de opgegeven bestandslocatie. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Slaat de afbeeldingsgegevens op in de opgegeven stream in de opgegeven bestandsindeling volgens de opslagopties. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Slaat de 32-bits ARGB-pixels op. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Slaat de pixels op. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Slaat de pixels op. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Slaat de onbewerkte gegevens op. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Stelt een afbeelding 32-bits ARGB-pixel in voor de opgegeven positie. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Stelt het afbeeldingspalet in. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Stelt een afbeeldingspixel in voor de opgegeven positie. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Stelt de resolutie hiervoor in[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Converteert rasterafbeelding naar de bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Schrijft de hele scanlijn naar de opgegeven scanlijnindex. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Schrijft de hele scanlijn naar de opgegeven scanlijnindex. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | De standaard PSD-versie. |

### Voorbeelden

De volgende code demonstreert de mogelijkheid om de afbeelding te roteren met een specifieke hoekwaarde.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Gehele afbeelding roterend
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Lagen roteren
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Zie ook

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* naamruimte [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* montage [Aspose.PSD](../../)


