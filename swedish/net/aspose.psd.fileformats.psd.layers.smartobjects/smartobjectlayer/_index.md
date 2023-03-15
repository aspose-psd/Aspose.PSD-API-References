---
title: Class SmartObjectLayer
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.SmartObjects.SmartObjectLayer klass. Definierar SmartObjectLayerklassen som innehåller inbäddade i PSDfilen eller länkade smarta objekt i den externa filen. Med Smart Objects kan du Utföra oförstörande transformationer. Du kan skala rotera snedställa förvränga perspektivomvandla eller förvränga ett lager utan att förlora originalbilddata eller kvalitet eftersom omvandlingarna inte påverkar originaldata. Arbeta med vektordata som vektorgrafik från Illustrator som annars skulle rasteriseras. Utför oförstörande filtrering. Du kan redigera filter som tillämpas på smarta objekt när som helst. Redigera ett smart objekt och uppdatera alla dess länkade instanser automatiskt. Använd en lagermask som antingen är länkad eller olänkad till smarta objektlagret. Prova olika designs med låg platshållarbilder med upplösning som du senare ersätter med slutgiltiga versioner. I Adobe Photoshop kan du bädda in innehållet i en bild i ett PSDdokument. Mer information finns härhttps//helpx.adobe.com/photoshop/using/createsmartobjects.html Ett lager med ett inbäddat smart objekt innehåller placerade PlLd och SoLdresurser med smarta objektegenskaper. PlLdresursen kan vara ensam för PSDversioner äldre än 10. Dessa resurser innehåller UniqueId för LiFdDataSource i den globala Lnkbed2Resourcen med embedded. filnamn och andra parametrar inklusive det inbäddade filinnehållet i originalformatet som en bytearray.
type: docs
weight: 3490
url: /sv/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---
## SmartObjectLayer class

Definierar SmartObjectLayer-klassen som innehåller inbäddade i PSD-filen eller länkade smarta objekt i den externa filen. Med Smart Objects kan du: Utföra oförstörande transformationer. Du kan skala, rotera, snedställa, förvränga, perspektivomvandla eller förvränga ett lager utan att förlora originalbilddata eller kvalitet eftersom omvandlingarna inte påverkar originaldata. Arbeta med vektordata, som vektorgrafik från Illustrator, som annars skulle rasteriseras. Utför oförstörande filtrering. Du kan redigera filter som tillämpas på smarta objekt när som helst. Redigera ett smart objekt och uppdatera alla dess länkade instanser automatiskt. Använd en lagermask som antingen är länkad eller olänkad till smarta objektlagret. Prova olika designs med låg- platshållarbilder med upplösning som du senare ersätter med slutgiltiga versioner. I Adobe� Photoshop� kan du bädda in innehållet i en bild i ett PSD-dokument. Mer information finns här:[https://helpx.adobe.com/photoshop/using/create-smart-objects.html](https://helpx.adobe.com/photoshop/using/create-smart-objects.html) Ett lager med ett inbäddat smart objekt innehåller placerade (PlLd) och SoLd-resurser med smarta objektegenskaper. PlLd-resursen kan vara ensam för PSD-versioner äldre än 10. Dessa resurser innehåller UniqueId för LiFdDataSource i den globala Lnkbed2Resourcen med embedded. filnamn och andra parametrar, inklusive det inbäddade filinnehållet i originalformatet som en byte-array.

```csharp
public class SmartObjectLayer : Layer
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten för automatisk justering. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Hämtar eller ställer in ett värde för bakgrundsfärgen. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Hämtar bildbitar per pixelantal. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Får blandningsalternativen. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Hämtar eller ställer in blandningslägestangenten. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Får blandningslägessignaturen. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Hämtar eller ställer in bottenskiktets position. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Får bildens gränser. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Hämtar eller ställer in kanalinformationen. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Hämtar lagrets kanaler. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Hämtar eller ställer in lagerklippningen. 0 = bas, 1 = icke-bas. |
| [Container](../../aspose.psd/image/container/) { get; } | Får[`Image`](../../aspose.psd/image/) container. |
| [Contents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/) { get; set; } | Hämtar eller ställer in innehållet i lagret för smarta objekt. Innehållet för det inbäddade smarta objektet är den inbäddade råbildsfilen:[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) och dess egenskaper. Det länkade smarta objektets innehåll är råinnehållet i den länkade bildfilen om den är tillgänglig och dess egenskaper:[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . Vi stöder inte laddning från Adobe� Photoshop� �� Graphics Library när[`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) är sant. För vanliga länkfiler använder vi först[`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) för att leta efter filen relativ till källbildens sökvägSourceImagePath , om den inte är tillgänglig tittar vi på[`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , om inte så letar vi efter länkfilen i samma katalog där vår bild är:SourceImagePath . |
| [ContentsBounds](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentsbounds/) { get; set; } | Hämtar eller ställer in gränserna för innehållet i smarta objekt. |
| [ContentsSource](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentssource/) { get; set; } | Hämtar eller ställer in det smarta objektets innehålls källa. |
| [ContentType](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contenttype/) { get; } | Hämtar typen av innehåll i lagret för smarta objekt. Innehållet i det inbäddade smarta objektet är den inbäddade råbildsfilen:[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) . Det länkade smarta objektets innehåll är råinnehållet i den länkade bildfilen om den är tillgänglig:[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . Vi stöder inte laddning från Adobe� Photoshop� �� Graphics Library när[`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) är sant. För vanliga länkfiler använder vi först[`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) för att leta efter filen relativ till källbildens sökvägSourceImagePath , om den inte är tillgänglig tittar vi på[`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , om inte så letar vi efter länkfilen i samma katalog där vår bild är:SourceImagePath . |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Hämtar objektets dataström. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Hämtar eller ställer in visningsnamnet för lagret. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Får lagret extra informationslängd i byte. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Får värdet filformat |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Hämtar eller ställer in lagerfyllmedlet. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Hämtar eller ställer in fyllningsopaciteten. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Hämtar eller ställer in lagerflaggorna. bit 0 = transparensskyddad; bit 1 = synlig; bit 2 = föråldrad; bit 3 = 1 för Photoshop 5.0 och senare, talar om om bit 4_x00 har användbar information; pixeldata irrelevant för dokumentets utseende. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Får ett värde som indikerar om denna instans har alpha. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Hämtar eller ställer in ett värde som anger om bilden har bakgrundsfärg. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Får ett värde som indikerar om bilden har transparent färg. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Hämtar bildhöjden. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Hämtar eller ställer in den horisontella upplösningen, i pixlar per tum, för detta[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Får opacitet för denna bild. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Hämtar eller ställer in avbrottsmonitorn. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Får ett värde som indikerar om bilddata är cachad för närvarande. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Får ett värde som anger om rådataladdning är tillgänglig. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Hämtar eller ställer in ett värde som anger om lagret är synligt |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Får ett värde som indikerar om denna instans är synlig i gruppen (om lagret inte är i gruppen betyder det rotgrupp). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Hämtar eller ställer in data för lagerblandningsintervall. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Hämtar eller ställer in datum för skapande av lagret. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Hämtar eller ställer in lagerlåset. Observera att om flaggan LayerFlags.TransparencyProtected är inställd kommer den att skrivas över av lagerlåsflaggan. För att returnera LayerFlags.TransparencyProtected-flaggan måste ansöka om lageralternativet layer.Flags &#x7C;= Layer0Flags_TransparencyProtected_TransparencyProtected.TransparencyProtected. |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Hämtar eller ställer in lagermaskdata. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Hämtar lageralternativen. |
| [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Hämtar eller ställer in vänster lagerposition. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Får den totala lagerlängden i byte. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Hämtar eller ställer in lagernamnet. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Hämtar eller ställer in lagrets opacitet. 0 = transparent, 255 = ogenomskinlig. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Hämtar eller ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Hämtar eller ställer in ett värde som anger om bildkomponenterna måste förmultipliceras. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Hämtar eller ställer in den anpassade färgomvandlaren |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Hämtar rådataformatet. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Hämtar aktuella rådatainställningar. Observera att när du använder dessa inställningar laddas data utan konvertering. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Hämtar eller ställer in reservindex som ska användas när palettindex är utanför gränserna |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Hämtar eller ställer in den indexerade färgomvandlaren |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Hämtar den rå radstorleken i byte. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Hämtar eller ställer in lagerresurserna. |
| [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Får eller ställer in rätt lagerposition. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Hämtar eller ställer in den dekorativa arkets färgmarkering i lagerlistan |
| [Size](../../aspose.psd/image/size/) { get; } | Hämtar bildstorleken. |
| [SmartFilters](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartfilters/) { get; } | Får de smarta filtren. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartobjectprovider/) { get; } | Får leverantören av smarta objekt. |
| [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Hämtar eller ställer in det översta lagrets position. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Får bilden genomskinlig färg. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Hämtar eller ställer in ett värde som anger om XMP-metadata ska uppdateras. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Hämtar eller ställer in ett värde som anger om rådataladdning ska användas när rådataladdningen är tillgänglig. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Hämtar eller ställer in den vertikala upplösningen, i pixlar per tum, för detta[`RasterImage`](../../aspose.psd/rasterimage/) . |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Hämtar bildens bredd. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Hämtar eller ställer in XMP-metadata. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Lägger till masken i nuvarande lager. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Justera en ljusstyrka för bilden. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Bild kontrasterande |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Gamma-korrigering av en bild. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Gamma-korrigering av en bild. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildströskelvärde |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildströskelvärde |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarisering av en bild med fördefinierad tröskel |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarisering av en bild med Otsu thresholding |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Cachelagrar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från det underliggande[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bestämmer om bilden kan sparas i det angivna filformatet som representeras av de godkända sparalternativen. |
| [ConvertToLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/converttolinked/)(string) | Konverterar detta inbäddade smarta objekt till ett länkat smart objekt. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Beskär bilden. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Beskär bilden med skiftningar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Utför dithering på den aktuella bilden. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Utför dithering på den aktuella bilden. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Ritar bilden på lager. |
| [DuplicateLayer](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/)() | Skapar ett nytt smart objektlager genom att kopiera detta. Observera att för inbäddade smarta objekt delas den inbäddade bilden. Om du vill kopiera den inbäddade bilden använd[`NewSmartObjectViaCopy`](./newsmartobjectviacopy/) metod. |
| [EmbedLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/embedlinked/)() | Bäddar in det länkade smarta objektet i detta lager. |
| [ExportContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/)(string) | Exporterar det inbäddade eller länkade innehållet till en fil. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtrerar den angivna rektangeln. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Får en bild 32-bitars ARGB-pixel. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Hämtar standard 32-bitars ARGB-pixelmatrisen. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Hämtar standardalternativen. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Hämtar standardpixelmatrisen med partial pixel loader. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Hämtar standardinställningen för rådata. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Hämtar den förinställda rådatamatrisen med hjälp av partial pixel loader. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Returnerar en hash-kod för denna instans. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Hämtar datum och tid då resursbilden senast ändrades. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av [`Save`](../../aspose.psd/datastreamsupporter/save/) metod, kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till[`Save`](../../aspose.psd/image/save/)metod som den andra parametern. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Får en bildpixel. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Hämtar skevningsvinkeln. Denna metod är tillämplig på skannade textdokument, för att bestämma snedställningsvinkeln vid skanning. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Transformation av en bild till dess gråskalerepresentation |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Laddar 32-bitars ARGB-pixlar. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Laddar 64-bitars ARGB-pixlar. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Laddar pixlar i CMYK-format. |
| [LoadContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/)(LoadOptions) | Hämtar det inbäddade eller länkade bildinnehållet i det smarta objektlagret. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Laddar 32-bitars ARGB-pixlar delvis i paket. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Laddar pixlar delvis i paket. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Laddar pixlar. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | Slår ihop lagret till specificerat lager |
| [NewSmartObjectViaCopy](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/)() | Skapar ett nytt smart objektlager genom att kopiera detta. Återskapar funktionen `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` i Adobe� Photoshop�. Observera att det endast är aktiverat för inbäddade smarta objekt eftersom den inbäddade bilden kopieras också. Om du vill dela den inbäddade bilden använd[`DuplicateLayer`](./duplicatelayer/) metod. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med den skeva skanningen. Denna metod använder[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) och[`Rotate`](../../aspose.psd/rasterimage/rotate/) metoder. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med den skeva skanningen. Denna metod använder[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) och[`Rotate`](../../aspose.psd/rasterimage/rotate/) metoder. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [RelinkToFile](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/relinktofile/)(string) | Återlänkar det länkade smarta objektet till en ny fil. Det finns ingen anledning att anropa UpdateModifiedContent-metoden efteråt. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Ersätter en färg mot en annan med tillåten skillnad och bevarar det ursprungliga alfavärdet för att spara jämna kanter. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Ersätter en färg mot en annan med tillåten skillnad och bevarar det ursprungliga alfavärdet för att spara jämna kanter. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents)(Image) | Ersätter det smarta objektinnehållet som är inbäddat i det smarta objektlagret. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_2)(string) | Ersätter innehållet med en fil. Det finns ingen anledning att anropa metoden UpdateModifiedContent efteråt. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_1)(Image, ResolutionSetting) | Ersätter det smarta objektinnehållet som är inbäddat i det smarta objektlagret. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_3)(string, ResolutionSetting) | Ersätter innehållet med en fil. Det finns ingen anledning att anropa metoden UpdateModifiedContent efteråt. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Ersätter alla icke-transparenta färger med ny färg och bevarar det ursprungliga alfavärdet för att spara jämna kanter. Obs: om du använder det på bilder utan genomskinlighet kommer alla färger att ersättas med en enda. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Ersätter alla icke-transparenta färger med ny färg och bevarar det ursprungliga alfavärdet för att spara jämna kanter. Obs: om du använder det på bilder utan genomskinlighet kommer alla färger att ersättas med en enda. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ändrar storleken på bilden. StandardenLeftTopToLeftTopanvänds. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Ändrar storlek på bilden. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Ändrar storlek på bilden. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ändrar storleken på höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Ändrar storleken på höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Ändrar storleken på höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Ändrar storleken på bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Ändrar storleken på bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Rotera bilden runt mitten. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Rotera bilden runt mitten. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Roterar, vänder eller roterar och vänder bilden. |
| [Save](../../aspose.psd/image/save/)() | Sparar bilddata till den underliggande strömmen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Sparar objektets data till den angivna strömmen. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Sparar objektets data till den angivna filplatsen. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Sparar 32-bitars ARGB-pixlar. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Sparar pixlarna. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Sparar pixlarna. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Sparar rådata. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Ställer in en 32-bitars ARGB-pixel för den angivna positionen. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Ställer in bildpaletten. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Ställer in en bildpixel för den angivna positionen. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Ställer in upplösningen för detta[`RasterImage`](../../aspose.psd/rasterimage/) . |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Skapar en ytlig kopia av det aktuella lagret. Vänligen[https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) för förklaring. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Konverterar rasterbilden till bitmappen. |
| [UpdateModifiedContent](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/updatemodifiedcontent/)() | Uppdaterar bildcachen för smarta objektlager med det ändrade innehållet. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |

### Exempel

Följande kod visar stödet för Embedded Smart-objekt.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Det här exemplet visar hur man ändrar det smarta objektlagret i PSD-filen och exporterar / uppdaterar det ursprungliga inbäddade innehållet för smarta objekt.
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

        // Låt oss exportera den inbäddade smarta objektbilden från PSD-smarta objektlagret
        smartObjectLayer.ExportContents(exportPath);

        // Låt oss kontrollera om originalbilden är korrekt sparad
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

        // Låt oss kontrollera om den uppdaterade bilden sparas korrekt
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Se även

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../../aspose.psd.fileformats.psd/smartobjectprovider/)
* class [LinkDataSource](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../aspose.psd.fileformats.psd.layers.smartobjects/)
* hopsättning [Aspose.PSD](../../)


