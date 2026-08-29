---
title: "Klass Layer"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.Layer klass. PSD‑lagret"
type: docs
weight: 2270
url: /sv/net/aspose.psd.fileformats.psd.layers/layer/
---
{{< psd/tize >}}
## Layer class

PSD‑lagret.

```csharp
public class Layer : RasterCachedImage
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Layer](layer/#constructor)() | Initierar en ny instans av klassen `Layer`. Konstruktor för lat initiering. |
| [Layer](layer/#constructor_3)(Stream) | Initierar en ny instans av klassen `Layer`. |
| [Layer](layer/#constructor_1)(RasterImage, bool) | Initierar en ny instans av klassen `Layer`. |
| [Layer](layer/#constructor_2)(Rectangle, byte[], byte[], byte[], string) | Initierar en ny instans av klassen `Layer` från byte‑arrayer. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Hämtar eller anger ett värde som indikerar om paletten justeras automatiskt. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Hämtar eller anger ett värde för bakgrundsfärgen. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Hämtar antalet bildbitar per pixel. |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers/layer/blendclippedelements/) { get; set; } | Hämtar eller anger blandningen av det beskurna elementet. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Hämtar blandningsalternativen. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Hämtar eller anger nyckeln för blandningsläget. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Hämtar blandningslägets signatur. |
| virtual [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Hämtar eller anger positionen för det nedre lagret. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Hämtar bildens gränser. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Hämtar eller anger en hint för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Hämtar eller anger kanalinformationen. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Hämtar lagrets kanalantal. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Hämtar eller anger lagrets beskärning. 0 = bas, 1 = icke-bas. |
| [Container](../../aspose.psd/image/container/) { get; } | Hämtar [`Image`](../../aspose.psd/image/) behållaren. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Hämtar objektets datastream. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Hämtar eller anger lagrets visningsnamn. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Hämtar lagrets extra informationslängd i byte. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Hämtar ett värde för filformatet |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Hämtar eller anger lagrets fyllning. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Hämtar eller anger fyllnadens opacitet. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Hämtar eller anger lagerflaggorna. bit 0 = transparensskyddad; bit 1 = synlig; bit 2 = föråldrad; bit 3 = 1 för Photoshop 5.0 och senare, anger om bit 4 har användbar information; bit 4 = pixeldatan är irrelevant för dokumentets utseende. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Hämtar ett värde som indikerar om detta objekt har alfa. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Hämtar ett värde som indikerar om bilden har transparent färg. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Hämtar bildens höjd. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för denna [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Hämtar opaciteten för denna bild. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Hämtar eller anger avbrottsmotorn. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Hämtar ett värde som indikerar om bilddata för närvarande är cachad. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Hämtar ett värde som indikerar om inläsning av rådata är tillgänglig. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Hämtar eller anger ett värde som indikerar om lagret är synligt |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Hämtar ett värde som indikerar om detta objekt är synligt i grupp(Om lagret inte är i en grupp betyder det rotgrupp). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Hämtar eller anger data för lagerblandningsintervall. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Hämtar eller anger lagrets skapelsedatum och tid. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Hämtar eller anger lagerlåsningen. Observera att om flaggan LayerFlags.TransparencyProtected är satt så kommer den att skrivas över av lagerlåsflagg. För att återge flaggan LayerFlags.TransparencyProtected måste du tillämpa lageralternativet layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Hämtar eller anger lagermaskdata. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Hämtar lageralternativen. |
| virtual [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Hämtar eller anger lagrets vänstra position. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Hämtar lagrets totala längd i byte. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Hämtar eller anger lagrets namn. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Hämtar eller anger lagrets opacitet. 0 = transparent, 255 = ogenomskinlig. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Hämtar eller anger ett värde som indikerar om bildkomponenterna måste vara förmultiplicerade. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Hämtar eller anger den anpassade färgkonverteraren |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Hämtar rådataformatet. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Hämtar de aktuella rådatainställningarna. Observera att när dessa inställningar används laddas data utan konvertering. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Hämtar eller anger reservindexet som ska användas när palettindexet är utanför gränserna |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Hämtar eller anger den indexerade färgkonverteraren |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Hämtar den råa radstorleken i byte. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Hämtar eller anger lagerresurserna. |
| virtual [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Hämtar eller anger den högra lagerpositionen. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Hämtar eller anger dekorativt bladfärgsmarkering i lagrens lista |
| [Size](../../aspose.psd/image/size/) { get; } | Hämtar bildstorleken. |
| virtual [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Hämtar eller anger den övre lagerpositionen. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Hämtar bildens transparenta färg. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Hämtar ett värde som indikerar om bildpaletten används. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna [`RasterImage`](../../aspose.psd/rasterimage/). |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Hämtar bildbredden. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Hämtar eller anger XMP-metadata. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Lägger till masken till det aktuella lagret. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Justering av bildens ljusstyrka. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Bildkontrast |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Gamma-korrigering av en bild. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Gamma-korrigering av en bild. |
| [ApplyLayerMask](../../aspose.psd.fileformats.psd.layers/layer/applylayermask/)() | Applicerar lagermasken på lagret, och tar sedan bort masken. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarisering av en bild med fördefinierad tröskel |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarisering av en bild med Otsu-tröskelvärde |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de överförda sparalternativen. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Beskär bilden. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Beskär bild med förskjutningar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Utför dithering på den aktuella bilden. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Utför dithering på den aktuella bilden. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Ritar bilden på lagret. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtrerar den angivna rektangeln. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Hämtar en bildpixel i 32-bitars ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Hämtar standardarrayen för 32-bitars ARGB-pixlar. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Hämtar standardalternativen. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Hämtar standardpixelarrayen med hjälp av partiell pixel‑laddare. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Hämtar standardarrayen för rådata. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Hämtar standardarrayen för rådata med hjälp av partiell pixel‑laddare. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Returnerar en hashkod för denna instans. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Hämtar datum och tid då resursbilden senast ändrades. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara användbart för att behålla bitdjup och andra parametrar för den ursprungliga bilden oförändrade. Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med metoden [`Save`](../../aspose.psd/datastreamsupporter/save/), kommer en PNG‑utdata med 8 bitar per pixel att skapas. För att undvika detta och spara PNG‑bilden med 1 bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem till metoden [`Save`](../../aspose.psd/image/save/) som den andra parametern. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Hämtar en bildpixel. Prestandavarning: Undvik att använda denna metod för att iterera över alla bildpixlar eftersom det kan leda till betydande prestandaproblem. För mer effektiv pixelmanipulation, använd metoden `LoadArgb32Pixels` för att hämta hela pixelarrayen samtidigt. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Hämtar snedvinkeln. Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Transformation av en bild till dess gråskalerepresentation |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Laddar 32-bitars ARGB‑pixlar. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Laddar 64-bitars ARGB‑pixlar. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Laddar pixlar i CMYK-format. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Laddar pixlar i CMYK-format. Denna metod är föråldrad. Använd den mer effektiva metoden [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Laddar 32-bitars ARGB‑pixlar delvis i paket. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Laddar pixlar delvis i paket. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Laddar pixlar. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | Slår samman lagret med angivet lager. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning. Metoden använder [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) och [`Rotate`](../../aspose.psd/rasterimage/rotate/)‑metoderna. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning. Metoden använder [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) och [`Rotate`](../../aspose.psd/rasterimage/rotate/)‑metoderna. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ändrar bildens storlek. Standardvärdet NearestNeighbourResample används. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Ändrar bildens storlek. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Ändrar bildens storlek. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ändrar höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Ändrar höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Ändrar höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Ändrar bredden proportionellt. Standardvärdet NearestNeighbourResample används. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Ändrar bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Ändrar bredden proportionellt. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Rotera bilden kring centrum. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Rotera bilden kring centrum. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Rotera, vänd eller rotera och vänd bilden. |
| [Save](../../aspose.psd/image/save/)() | Sparar bilddata till den underliggande strömmen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/#save_1)(Stream) | Sparar objektets data till den angivna strömmen. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Sparar objektets data till den angivna filplatsen. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/#save_7)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/#save_5)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/#save_6)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Sparar de 32-bitars ARGB-pixlarna. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Sparar pixlarna. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Sparar pixlarna. Den här metoden är föråldrad. Använd den mer effektiva [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) metoden. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Sparar pixlarna. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Sparar rådata. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Ställer in en 32-bitars ARGB-pixel för bilden på den angivna positionen. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Ställer in bildpaletten. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Ställer in en bildpixel för den angivna positionen. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Ställer in upplösningen för denna [`RasterImage`](../../aspose.psd/rasterimage/). |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Skapar en ytlig kopia av det aktuella lagret. Se [https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) för förklaring. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Konverterar rasterbild till bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [BlendSignature](../../aspose.psd.fileformats.psd.layers/layer/blendsignature/) | Representerar signatur för blandningsläge. |
| const [LayerHeaderSize](../../aspose.psd.fileformats.psd.layers/layer/layerheadersize/) | Lagrets rubrikstorlek. |

### Se även

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


