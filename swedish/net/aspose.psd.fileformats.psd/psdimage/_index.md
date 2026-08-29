---
title: "Klass PsdImage"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.PsdImage-klass. Definierar PsdImage-klassen som ger möjlighet att läsa, redigera och spara PSD‑filer samt att uppdatera egenskaper, lägga till vattenstämplar, utföra grafikoperationer eller konvertera ett filformat till ett annat. Aspose.PSD stöder import som ett lager och export till följande format: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb samt export till Pdf med markerbar text."
type: docs
weight: 4050
url: /sv/net/aspose.psd.fileformats.psd/psdimage/
---
{{< psd/tize >}}
## PsdImage class

Definierar klassen PsdImage som ger möjlighet att läsa in, redigera och spara PSD‑filer samt uppdatera egenskaper, lägga till vattenstämplar, utföra grafikoperationer eller konvertera ett filformat till ett annat. Aspose.PSD stöder import som ett lager och export till följande format: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb samt export till Pdf med markerbar text.

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | Initierar en ny instans av `PsdImage`-klassen från en befintlig rasterbild (inte psd‑bild) med RGB-färgläge, 4 kanaler, 8 bitar/kanal och utan komprimering. |
| [PsdImage](psdimage/#constructor_4)(Stream) | Initierar en ny instans av `PsdImage`-klassen från angiven sökväg för rasterbild (inte psd‑bild i ström). Används för att initiera psd‑bild med standardparametrar – färgläge – rgb, 4 kanaler, 8 bitar per kanal, komprimering – Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | Initierar en ny instans av `PsdImage`-klassen från angiven sökväg för rasterbild (inte psd‑bild i sökväg). Används för att initiera psd‑bild med standardparametrar – färgläge – rgb, 4 kanaler, 8 bitar per kanal, komprimering – Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | Initierar en ny instans av `PsdImage`-klassen med angiven bredd och höjd. Används för att initiera en tom psd‑bild. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Initierar en ny instans av `PsdImage`-klassen från en befintlig rasterbild (inte psd‑bild) med konstruktörsparametrar. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Initierar en ny instans av `PsdImage`-klassen från angiven sökväg för rasterbild (inte psd‑bild i ström) med konstruktörsparametrar. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Initierar en ny instans av `PsdImage`-klassen från angiven sökväg för rasterbild (inte psd‑bild i sökväg) med konstruktörsparametrar. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Initierar en ny instans av `PsdImage`-klassen med angiven bredd, höjd, palett, färgläge, kanalantal och kanalernas bitlängd samt angivna komprimeringslägesparametrar. Används för att initiera en tom psd‑bild. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | Hämtar eller anger det aktiva lagret. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Hämtar eller anger ett värde som indikerar om paletten justeras automatiskt. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Hämtar eller anger ett värde för bakgrundsfärgen. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | Hämtar bitarna per kanal. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | Hämtar antalet bildbitar per pixel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Hämtar bildens gränser. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Hämtar eller anger en hint för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | Hämtar antalet PSD‑kanaler. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | Hämtar eller anger CMYK-färgprofilen för CMYK PSD‑bilder. Måste vara i par med RgbColorProfile för korrekt färgkonvertering. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | Hämtar eller anger färgläget. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | Hämtar komprimeringsmetoden. |
| [Container](../../aspose.psd/image/container/) { get; } | Hämtar [`Image`](../../aspose.psd/image/) behållaren. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Hämtar objektets datastream. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | Hämtar ett värde för filformatet |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | Hämtar eller anger den globala vinkeln. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | Hämtar information om den globala lagermasken. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | Hämtar eller anger de globala lagerresurserna. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | Hämtar eller anger GRAY (monokrom) färgprofil för Gråskala PSD-bilder. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | Hämtar eller anger ett värde som indikerar om den första alfakanalen innehåller transparensdata för det sammanslagna resultatet när lagerdata specificeras. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Hämtar ett värde som indikerar om bilden har transparent färg. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | Hämtar bildens höjd. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för denna `PsdImage`. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Hämtar opaciteten för denna bild. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | Hämtar eller anger PSD-bildresurserna. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Hämtar eller anger avbrottsmotorn. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Hämtar ett värde som indikerar om bilddata för närvarande är cachad. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | Hämtar ett värde som indikerar om PSD-bilden är platt. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Hämtar ett värde som indikerar om inläsning av rådata är tillgänglig. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | Hämtar eller anger PSD-lagren. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | Hämtar den länkade lagerhanteraren. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Hämtar eller anger ett värde som indikerar om bildkomponenterna måste vara förmultiplicerade. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Hämtar eller anger den anpassade färgkonverteraren |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | Hämtar rådataformatet. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Hämtar de aktuella rådatainställningarna. Observera att när dessa inställningar används laddas data utan konvertering. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Hämtar eller anger reservindexet som ska användas när palettindexet är utanför gränserna |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Hämtar eller anger den indexerade färgkonverteraren |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Hämtar den råa radstorleken i byte. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | Hämtar eller anger RGB-färgprofilen för CMYK PSD-bilder. Måste vara i par med CmykColorProfile för korrekt färgkonvertering. |
| [Size](../../aspose.psd/image/size/) { get; } | Hämtar bildstorleken. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | Hämtar den smarta objektleverantören. |
| [Timeline](../../aspose.psd.fileformats.psd/psdimage/timeline/) { get; } | Hämtar [`Timeline`](./timeline/) för denna `PsdImage`. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Hämtar bildens transparenta färg. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Hämtar ett värde som indikerar om bildpaletten används. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | Hämtar eller anger versionen. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna `PsdImage`. |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | Hämtar bildbredden. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | Hämtar eller anger XMP-metadata. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | Lägger till svartvita justeringslagret. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | Lägger till ljusstyrka/kontrast-justeringslagret. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | Lägger till kanalblandare-justeringslagret med standardparametrar |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | Lägger till färgbalans-justeringslagret. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | Lägger till Kurvor-justeringslagret. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | Lägger till exponering-justeringslagret. |
| [AddGradientMapAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/)() | Lägger till GradientMap-justeringslagret |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | Lägger till nyans/mättnad-justeringslagret. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | Lägger till ett inverteringsjusteringslager. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | Lägger till lagret. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | Lägger till lagergruppen. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | Lägger till Nivåer-justeringslagret. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | Lägger till fotofilterlagret. |
| [AddPosterizeAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/)() | Lägger till Posterize-justeringslagret. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | Lägger till ett nytt vanligt lager. |
| [AddSelectiveColorAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addselectivecoloradjustmentlayer/)() | Lägger till det selektiva färgjusteringslagret. |
| [AddShapeLayer](../../aspose.psd.fileformats.psd/psdimage/addshapelayer/)() | Lägg till ett tomt Shape‑lager. Utan banor. De bör läggas till i Shape‑lagret innan sparning. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | Lägger till ett nytt Text‑lager. |
| [AddThresholdAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/)() | Lägger till Threshold‑justeringslagret. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | Lägger till Vibrance‑justeringslagret. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | Justering av bildens ljusstyrka. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | Bildkontrast |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | Gamma-korrigering av en bild. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | Gamma-korrigering av en bild. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | Binarisering av en bild med fördefinierad tröskel |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Binarisering av en bild med Otsu-tröskelvärde |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de överförda sparalternativen. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | Konverterar detta bildformat till det som anges i alternativ. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | Beskär bilden. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Beskär bild med förskjutningar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Utför dithering på den aktuella bilden. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Utför dithering på den aktuella bilden. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | Filtrerar den angivna rektangeln. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | Plattar till alla lager. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Hämtar en bildpixel i 32-bitars ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Hämtar standardarrayen för 32-bitars ARGB-pixlar. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Hämtar standardalternativen. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Hämtar standardpixelarrayen med hjälp av partiell pixel‑laddare. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Hämtar standardarrayen för rådata. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Hämtar standardarrayen för rådata med hjälp av partiell pixel‑laddare. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Hämtar datum och tid då resursbilden senast ändrades. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara användbart för att behålla bitdjup och andra parametrar för den ursprungliga bilden oförändrade. Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med metoden [`Save`](../../aspose.psd/datastreamsupporter/save/), kommer en PNG‑utdata med 8 bitar per pixel att skapas. För att undvika detta och spara PNG‑bilden med 1 bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem till metoden [`Save`](../../aspose.psd/image/save/) som den andra parametern. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Hämtar en bildpixel. Prestandavarning: Undvik att använda denna metod för att iterera över alla bildpixlar eftersom det kan leda till betydande prestandaproblem. För mer effektiv pixelmanipulation, använd metoden `LoadArgb32Pixels` för att hämta hela pixelarrayen samtidigt. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Hämtar snedvinkeln. Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | Transformation av en bild till dess gråskalerepresentation |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Laddar 32-bitars ARGB‑pixlar. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Laddar 64-bitars ARGB‑pixlar. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Laddar pixlar i CMYK-format. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Laddar pixlar i CMYK-format. Denna metod är föråldrad. Använd den mer effektiva metoden [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Laddar 32-bitars ARGB‑pixlar delvis i paket. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Laddar pixlar delvis i paket. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Laddar pixlar. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | Slår ihop lagren. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning. Metoden använder [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) och [`Rotate`](../../aspose.psd/rasterimage/rotate/)‑metoderna. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning. Metoden använder [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) och [`Rotate`](../../aspose.psd/rasterimage/rotate/)‑metoderna. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ändrar bildens storlek. Standardvärdet NearestNeighbourResample används. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Ändrar bildens storlek. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Ändrar bildens storlek. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ändrar höjden proportionellt. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Ändrar höjden proportionellt. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Ändrar höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Ändrar bredden proportionellt. Standardvärdet NearestNeighbourResample används. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Ändrar bredden proportionellt. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Ändrar bredden proportionellt. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | Rotera bilden kring centrum. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | Rotera bilden kring centrum. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Rotera, vänd eller rotera och vänd bilden. |
| [Save](../../aspose.psd/image/save/)() | Sparar bilddata till den underliggande strömmen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Sparar objektets data till den angivna strömmen. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Sparar objektets data till den angivna filplatsen. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Sparar de 32-bitars ARGB-pixlarna. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Sparar pixlarna. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Sparar pixlarna. Den här metoden är föråldrad. Använd den mer effektiva [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) metoden. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Sparar pixlarna. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Sparar rådata. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Ställer in en 32-bitars ARGB-pixel för bilden på den angivna positionen. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Ställer in bildpaletten. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Ställer in en bildpixel för den angivna positionen. |
| override [SetResolution](../../aspose.psd.fileformats.psd/psdimage/setresolution/)(double, double) | Ställer in upplösningen för detta `PsdImage`. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Konverterar rasterbild till bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | Standard‑PSD‑versionen. |

## Exempel

Följande kod demonstrerar möjligheten att rotera bilden med ett specifikt vinkelvärde.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Rotering av hela bilden
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

// Rotering av lager
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

### Se även

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


