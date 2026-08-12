---
title: "Klass SmartObjectLayer"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartObjects.SmartObjectLayer class. Definierar SmartObjectLayer-klassen som innehåller inbäddade eller länkade smarta objekt i PSD-filen eller i den externa filen. Med Smart Objects kan du utföra icke-förstörande transformationer. Du kan skala, rotera, skeva, förvränga, perspektivtransformera eller vrida ett lager utan att förlora originalbilddata eller kvalitet eftersom transformationerna inte påverkar originaldata. Arbeta med vektordata såsom vektorillustrationer från Illustrator som annars skulle rasteriseras. Utför icke-förstörande filtrering. Du kan när som helst redigera filter som applicerats på Smart Objects. Redigera ett Smart Object och uppdatera automatiskt alla dess länkade instanser. Applicera en lagermask som antingen är länkad eller olänkad till Smart Object-lagret. Prova olika designer med lågupplösta platshållarbilder som du senare ersätter med slutversioner. I Adobe Photoshop kan du bädda in innehållet i en bild i ett PSD-dokument. Mer information finns här https//helpx.adobe.com/photoshop/using/createsmartobjects.html Ett lager med ett inbäddat smart objekt innehåller placerade PlLd- och SoLd-resurser med egenskaper för smarta objekt. PlLd-resursen kan stå ensam för PSD-versioner äldre än 10. Dessa resurser innehåller UniqueId för LiFdDataSource i den globala Lnk2Resource med det inbäddade filnamnet och andra parametrar, inklusive det inbäddade filinnehållet i originalformat som en byte-array"
type: docs
weight: 3910
url: /sv/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---
{{< psd/tize >}}
## SmartObjectLayer class

Definierar klassen SmartObjectLayer som innehåller inbäddade i PSD-filen eller länkade smarta objekt i den externa filen. Med Smart Objects kan du: Utföra icke-destruktiva transformationer. Du kan skala, rotera, skeva, förvränga, perspektivtransformera eller vrida ett lager utan att förlora originalbilddata eller kvalitet eftersom transformationerna inte påverkar originaldata. Arbeta med vektordata, såsom vektorillustrationer från Illustrator, som annars skulle rasteriseras. Utföra icke-destruktiv filtrering. Du kan redigera filter som tillämpas på Smart Objects när som helst. Redigera ett Smart Object och automatiskt uppdatera alla dess länkade instanser. Applicera en lagermask som är antingen länkad eller olänkad till Smart Object-lagret. Prova olika designer med lågupplösta platshållarbilder som du senare ersätter med slutversioner. I Adobe Photoshop kan du bädda in innehållet i en bild i ett PSD-dokument. Mer information finns här: [https://helpx.adobe.com/photoshop/using/create-smart-objects.html](https://helpx.adobe.com/photoshop/using/create-smart-objects.html) Ett lager med ett inbäddat smart objekt innehåller placerade (PlLd) och SoLd-resurser med smarta objekt‑egenskaper. PlLd-resursen kan stå ensam för PSD-versioner äldre än 10. Dessa resurser innehåller UniqueId för LiFdDataSource i den globala Lnk2Resource med det inbäddade filnamnet och andra parametrar, inklusive det inbäddade filinnehållet i originalformat som en byte‑array.

```csharp
public class SmartObjectLayer : Layer
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SmartObjectLayer](smartobjectlayer/)(Stream) | Initierar en ny instans av `SmartObjectLayer`-klassen. |

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
| [Contents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/) { get; set; } | Hämtar eller anger innehållet i smartobjektlagret. Det inbäddade smartobjektets innehåll är den inbäddade råa bildfilen: [`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) och dess egenskaper. Det länkade smartobjektets innehåll är det råa innehållet i den länkade bildfilen om den är tillgänglig samt dess egenskaper: [`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). Vi stöder inte inläsning från Adobe™ Photoshop™ ™ Graphics Library när [`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) är sant. För vanliga länkar använder vi först [`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) för att söka efter filen relativt till källbildens sökväg SourceImagePath; om den inte finns söker vi på [`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/), annars letar vi efter länken i samma katalog där vår bild finns: SourceImagePath. |
| [ContentsBounds](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentsbounds/) { get; set; } | Hämtar eller anger gränserna för smartobjektets innehåll. |
| [ContentsSource](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentssource/) { get; set; } | Hämtar eller anger källan för smartobjektets innehåll. |
| [ContentType](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contenttype/) { get; } | Hämtar typen av smartobjektlagrets innehåll. Det inbäddade smartobjektets innehåll är den inbäddade råa bildfilen: [`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/). Det länkade smartobjektets innehåll är det råa innehållet i den länkade bildfilen om den är tillgänglig: [`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). Vi stöder inte inläsning från Adobe™ Photoshop™ ™ Graphics Library när [`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) är sant. För vanliga länkar använder vi först [`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) för att söka efter filen relativt till källbildens sökväg SourceImagePath; om den inte finns söker vi på [`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/), annars letar vi efter länken i samma katalog där vår bild finns: SourceImagePath. |
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
| [SmartFilters](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartfilters/) { get; } | Hämtar de smarta filtren. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartobjectprovider/) { get; } | Hämtar den smarta objektleverantören. |
| virtual [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Hämtar eller anger den övre lagerpositionen. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Hämtar bildens transparenta färg. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Hämtar ett värde som indikerar om bildpaletten används. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna [`RasterImage`](../../aspose.psd/rasterimage/). |
| [WarpSettings](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/warpsettings/) { get; set; } | Den hämtar eller anger Warp-parametrar som sattes eller hämtades från resurs (standard) |
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
| [ConvertToLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/converttolinked/)(string) | Konverterar detta inbäddade smarta objekt till ett länkat smart objekt. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Beskär bilden. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Beskär bild med förskjutningar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Utför dithering på den aktuella bilden. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Utför dithering på den aktuella bilden. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Ritar bilden på lagret. |
| [DuplicateLayer](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/)() | Skapar ett nytt smart objekt-lager genom att kopiera detta. Observera att för inbäddade smarta objekt delas den inbäddade bilden. Om du vill kopiera den inbäddade bilden, använd metoden [`NewSmartObjectViaCopy`](./newsmartobjectviacopy/). |
| [EmbedLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/embedlinked/)() | Bäddar in det länkade smarta objektet i detta lager. |
| [ExportContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/)(string) | Exporterar det inbäddade eller länkade innehållet till en fil. |
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
| [LoadContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/)(LoadOptions) | Hämtar det inbäddade eller länkade bildinnehållet i smartobjektlagret. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Laddar 32-bitars ARGB‑pixlar delvis i paket. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Laddar pixlar delvis i paket. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Laddar pixlar. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | Slår samman lagret med angivet lager. |
| [NewSmartObjectViaCopy](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/)() | Skapar ett nytt smartobjektlager genom att kopiera detta. Reproducerar `Layer -> Smart Objects -> New Smart Object via Copy`‑funktionaliteten i Adobe Photoshop. Observera att den endast är aktiverad för inbäddade smarta objekt eftersom den inbäddade bilden också kopieras. Om du vill dela den inbäddade bilden, använd metoden [`DuplicateLayer`](./duplicatelayer/). |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning. Metoden använder [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) och [`Rotate`](../../aspose.psd/rasterimage/rotate/)‑metoderna. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning. Metoden använder [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) och [`Rotate`](../../aspose.psd/rasterimage/rotate/)‑metoderna. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [RelinkToFile](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/relinktofile/)(string) | Återlänkar det länkade smarta objektet till en ny fil. Det behövs inte att anropa metoden UpdateModifiedContent efteråt. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents)(Image) | Ersätter innehållet i det smarta objektet som är inbäddat i smartobjektlagret. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_2)(string) | Ersätter innehållet med en fil. Det behövs inte att anropa metoden UpdateModifiedContent efteråt. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_1)(Image, ResolutionSetting) | Ersätter innehållet i det smarta objektet som är inbäddat i smartobjektlagret. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_5)(string, bool) | Ersätter innehållet med en fil. Det behövs inte att anropa metoden UpdateModifiedContent efteråt. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_3)(string, ResolutionSetting) | Ersätter innehållet med en fil. Det behövs inte att anropa metoden UpdateModifiedContent efteråt. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_4)(string, ResolutionSetting, bool) | Ersätter innehållet med en fil. Det behövs inte att anropa metoden UpdateModifiedContent efteråt. |
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
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Sparar objektets data till den angivna strömmen. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Sparar objektets data till den angivna filplatsen. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen. |
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
| [UpdateModifiedContent](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/updatemodifiedcontent/)() | Uppdaterar smarta objektlagrets bildcache med det modifierade innehållet. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |

## Exempel

Följande kod demonstrerar stöd för inbäddade smarta objekt.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Detta exempel visar hur man ändrar smarta objektlagret i PSD-filen och exporterar/uppdaterar smarta objektets ursprungliga inbäddade innehåll.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Låt oss exportera den inbäddade smarta objektbilden från PSD:s smarta objektlager
        smartObjectLayer.ExportContents(exportPath);

        // Låt oss kontrollera om den ursprungliga bilden har sparats korrekt
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Låt oss invertera den ursprungliga smarta objektbilden
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Låt oss ersätta den inbäddade smarta objektbilden i PSD-lagret
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Låt oss kontrollera om den uppdaterade bilden har sparats korrekt
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Se även

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../../aspose.psd.fileformats.psd/smartobjectprovider/)
* class [LinkDataSource](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../)


