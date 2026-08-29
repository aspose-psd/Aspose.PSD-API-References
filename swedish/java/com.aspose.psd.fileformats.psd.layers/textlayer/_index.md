---
title: "TextLayer"
second_title: "Aspose.PSD för Java API-referens"
description: "Textlagerklassen"
type: docs
weight: 30
url: /sv/java/com.aspose.psd.fileformats.psd.layers/textlayer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage), [com.aspose.psd.fileformats.psd.layers.Layer](../../com.aspose.psd.fileformats.psd.layers/layer)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.psd.layers.ITypeToolResourceOperable
```
public class TextLayer extends Layer implements ITypeToolResourceOperable
```

Textlagerklassen
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BlendSignature](#BlendSignature) | Representerar signatur för blandningsläge. |
| [LayerHeaderSize](#LayerHeaderSize) | Storleken på lagerhuvudet. |
| [OnCreate_internalized](#OnCreate-internalized) | Uppstår när bilden har laddats |
| [OnLoad_internalized](#OnLoad-internalized) | Uppstår när bilden har laddats av createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Uppstår när bilden har laddats eller sparats |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Uppstår när kredit har använts |
| [resources_internalized](#resources-internalized) | Resurserna |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [<T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)](#-T-tryGetResource-internalized-java.lang.Class-T--T---) | Hämtar resursen som är associerad med den angivna typen. |
| [addLayerMask(LayerMaskData layerMask)](#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Lägger till masken till det aktuella lagret. |
| [addResource_internalized(LayerResource resource)](#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Lägger till resursen. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Justering av ljusstyrka för bild. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Bildkontrast |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gamma-korrigering av en bild. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma-korrigering av en bild. |
| [applyLayerMask()](#applyLayerMask--) | Applicerar lagermasken på lagret och tar sedan bort masken. |
| [applyLayerState_internalized(LayerState layerState)](#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-) | Tillämpar lagerstilsinställningen från indata [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) till den aktuella [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) instansen. |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | Påbörjar storleksändringsprocessen. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildströskling |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildströskling |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisering av en bild med fördefinierad tröskel. |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisering av en bild med Otsu-tröskling |
| [cacheData()](#cacheData--) | Cachar data och säkerställer att ingen ytterligare datainläsning kommer att utföras från den underliggande DataStreamSupporter.DataStreamContainer. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna loadOptions. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Bestämmer om bilden kan läsas in från den angivna filsökvägen. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna open options. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de medföljande save options. |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Konverterar till aps. |
| [correctFontSize_internalized(float newSize, double yyTransform)](#correctFontSize-internalized-float-double-) | Korrigerar teckensnittets storlek |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Skapar en ny bild med de angivna create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Skapar en ny bild med de angivna bilderna som sidor |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Skapar en ny bild med de angivna bilderna som sidor. |
| [createInstance_internalized()](#createInstance-internalized--) | Skapar en ny instans av klassen [TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer). |
| [createInstance_internalized(PsdHeader header, IColorPalette palette)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-) | Skapar en ny instans av klassen [TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer). |
| [createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) | Skapar den nya instansen av klassen [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [createLayerState_internalized()](#createLayerState-internalized--) | Skapar den nya [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instansen baserat på aktuella [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) värden. |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(PsdHeader header, IColorPalette colorPalette, LayerAndMaskInfo layerAndMaskInfo, LayerResource[] resources)](#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.psd.fileformats.psd.layers.LayerResource---) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Beskär bilden. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Beskär bilden med förskjutningar. |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Utför dithering på den aktuella bilden. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Utför dithering på den aktuella bilden. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | Beskär bilden. |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | Ändrar storlek på bilden. |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | Roterar, vänder eller roterar och vänder bilden. |
| [drawImage(Point location, RasterImage image)](#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-) | Ritar bilden på lagret. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna objektet är lika med denna instans. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filtrerar den angivna rektangeln. |
| [findAssignableResource_internalized(System.Type type)](#findAssignableResource-internalized-com.aspose.ms.System.Type-) | Hittar den tilldelningsbara resursen. |
| [findPattResource_internalized()](#findPattResource-internalized--) | Hittar den  PattResource |
| [findResource_internalized(int typeToolKey)](#findResource-internalized-int-) | Hittar resursen efter unik nyckel. |
| [getAbsoluteBounds_internalized()](#getAbsoluteBounds-internalized--) | Hämtar eller anger de absoluta gränserna. |
| [getAllowWarpRepaint_internalized()](#getAllowWarpRepaint-internalized--) | Den hämtar eller anger render warp eller använder PS-bild |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Hämtar en bildpixel i 32-bit ARGB. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Hämtar ett värde som indikerar om paletten justeras automatiskt. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar eller anger ett värde för bakgrundsfärgen. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [getBlendClippedElements()](#getBlendClippedElements--) | Hämtar eller anger blandningen av det beskurna elementet. |
| [getBlendModeKey()](#getBlendModeKey--) | Hämtar eller anger nyckeln för blandningsläget. |
| [getBlendModeSignature()](#getBlendModeSignature--) | Hämtar signaturen för blandningsläget. |
| [getBlendingOptions()](#getBlendingOptions--) | Hämtar blandningsalternativen. |
| [getBottom()](#getBottom--) | Hämtar eller anger positionen för det nedre lagret. |
| [getBounds()](#getBounds--) | Hämtar bildens gränser. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Hämtar en ledtråd för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [getBytesPerRowForFullMask_internalized(int bitDepth)](#getBytesPerRowForFullMask-internalized-int-) | Hämtar antalet byte per rad för full maskläge. |
| [getBytesPerRowForMask_internalized(int bitDepth)](#getBytesPerRowForMask-internalized-int-) | Hämtar antalet byte per rad. |
| [getBytesPerRow_internalized(int bitDepth)](#getBytesPerRow-internalized-int-) | Hämtar antalet byte per rad. |
| [getChannelInformation()](#getChannelInformation--) | Hämtar eller anger kanalinformationen. |
| [getChannelsCount()](#getChannelsCount--) | Hämtar lagrets kanalantal. |
| [getClass()](#getClass--) |  |
| [getClipping()](#getClipping--) | Hämtar eller anger lagrets beskärning. |
| [getContainer()](#getContainer--) | Hämtar  Image  behållaren. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Hämtar objektets datastream. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Hämtar den djupt justerade paletten. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Hämtar standard 32-bit ARGB-pixelarrayen. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Hämtar standardalternativen. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Hämtar standardpixelarrayen med partiell pixel‑läsare. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Hämtar standardrådataarrayen med partiell pixel‑läsare. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Hämtar standardrådataarrayen. |
| [getDisplayName()](#getDisplayName--) | Hämtar lagrets visningsnamn. |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getEngineData_internalized()](#getEngineData-internalized--) | Hämtar motorens data. |
| [getExtraLength()](#getExtraLength--) | Hämtar lagrets extra informationslängd i byte. |
| [getFileFormat()](#getFileFormat--) | Hämtar ett värde för filformat |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Hämtar filformatet. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Hämtar filformatet. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Hämtar filformatet. |
| [getFillOpacity()](#getFillOpacity--) | Hämtar eller anger fyllningsopaciteten. |
| [getFiller()](#getFiller--) | Hämtar eller anger lagrets fyllnad. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Hämtar rektangeln som passar den aktuella bilden. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Hämtar rektangeln som passar den aktuella bilden. |
| [getFlags()](#getFlags--) | Hämtar eller anger lagrets flaggor. |
| [getFoldersHierarchy_internalized()](#getFoldersHierarchy-internalized--) | Hämtar listan över [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) mapphierarkin för det aktuella lagret. |
| [getFont()](#getFont--) | Hämtar teckensnittet. |
| [getFonts()](#getFonts--) | Hämtar teckensnittssamlingen för textlagret. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Hämtar palett från format‑specifika platser |
| [getGUID_internalized()](#getGUID-internalized--) | Hämtar det unika identifieraren för detta Layer‑instans. |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getHeight()](#getHeight--) | Hämtar bildens höjd. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för detta RasterImage. |
| [getImageOpacity()](#getImageOpacity--) | Hämtar opaciteten för denna bild. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Hämtar den interna datatransformern. |
| [getInnerText()](#getInnerText--) | Hämtar lagrets text |
| [getInterruptMonitor()](#getInterruptMonitor--) | Hämtar avbrotts­övervakaren. |
| [getLayerBlendingRangesData()](#getLayerBlendingRangesData--) | Hämtar eller anger data för lagerblandningsintervall. |
| [getLayerCreationDateTime()](#getLayerCreationDateTime--) | Hämtar eller anger lagerns skapelsedatum och -tid. |
| [getLayerCreationDateTime_internalized()](#getLayerCreationDateTime-internalized--) |  |
| [getLayerLock()](#getLayerLock--) | Hämtar eller anger låsning av lagret. |
| [getLayerMaskData()](#getLayerMaskData--) | Hämtar eller anger data för lagermasken. |
| [getLayerOptions()](#getLayerOptions--) | Hämtar lageralternativen. |
| [getLayerPalette_internalized()](#getLayerPalette-internalized--) | Hämtar eller anger lagerpaletten. |
| [getLayerType_internalized()](#getLayerType-internalized--) | Hämtar lagrets typ. |
| [getLeft()](#getLeft--) | Hämtar eller anger lagrets vänstra position. |
| [getLength()](#getLength--) | Hämtar lagrets totala längd i byte. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Hämtar eller anger maximal tillåten allokering för partiell roterings‑sparning. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Hämtar minneshanteraren. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Hämtar datum och tid då resursbilden senast ändrades. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getName()](#getName--) | Hämtar eller anger lagrets namn. |
| [getOpacity()](#getOpacity--) | Hämtar eller anger lagrets opacitet. |
| [getOpacityTotal_internalized()](#getOpacityTotal-internalized--) | Hämtar den totala opaciteten. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämtar alternativen baserat på de ursprungliga filinställningarna. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Hämtar den målbara bilden. |
| [getPalette()](#getPalette--) | Hämtar färgpaletten. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Hämtar en bildpixel. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Hämtar eller anger ett värde som indikerar om bildkomponenterna måste vara förmultiplicerade. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Skapar den privata teckensnittscachen. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Hämtar information om progress‑händelsehanteraren. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Hämtar information om progress‑händelsehanteraren. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Hämtar en proportionell höjd. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Hämtar en proportionell bredd. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Hämtar eller anger den anpassade färgkonverteraren |
| [getRawDataFormat()](#getRawDataFormat--) | Hämtar det råa dataformatet. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Hämtar eller anger reservindexen att använda när palettindexet är utanför gränserna |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Hämtar eller anger den indexerade färgkonverteraren |
| [getRawLineSize()](#getRawLineSize--) | Hämtar den råa radstorleken i byte. |
| [getResourceProcessor_internalized()](#getResourceProcessor-internalized--) | Hämtar eller anger resursprocessorn. |
| [getResources()](#getResources--) | Hämtar eller anger lagerresurserna. |
| [getRight()](#getRight--) | Hämtar eller anger den högra lagerpositionen. |
| [getRotateMode()](#getRotateMode--) | Hämtar eller anger roteringsläget. |
| [getSheetColorHighlight()](#getSheetColorHighlight--) | Hämtar eller anger den dekorativa bladfärgens markering i lagerlistan |
| [getSize()](#getSize--) | Hämtar bildens storlek. |
| [getSkewAngle()](#getSkewAngle--) | Hämtar snedvinkeln. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Hämtar filsökvägen till källbilden om den finns. |
| [getStringFormat_internalized()](#getStringFormat-internalized--) | Hämtar strängformatet. |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Hämtar synkroniseringsroten. |
| [getText()](#getText--) | Hämtar texten. |
| [getTextBoundBox()](#getTextBoundBox--) | Hämtar eller anger textens avgränsningsruta. |
| [getTextColor()](#getTextColor--) | Hämtar textens färg. |
| [getTextData()](#getTextData--) | Hämtar textens delar. |
| [getTop()](#getTop--) | Hämtar eller anger den övre lagerpositionen. |
| [getTransformMatrix()](#getTransformMatrix--) | Hämtar eller anger transformationsmatrisen |
| [getTransparentColor()](#getTransparentColor--) | Hämtar bildens transparenta färg. |
| [getTyShResourceIfExists_internalized()](#getTyShResourceIfExists-internalized--) | Söker och hämtar [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource)-resursen från [TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer). |
| [getUpdateXmpData()](#getUpdateXmpData--) | Hämtar eller anger ett värde som indikerar om XMP‑metadata ska uppdateras. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Hämtar ett värde som indikerar om objektet använder minnesoptimeringsstrategi |
| [getUseRawData()](#getUseRawData--) | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Hämtar den använda paletten. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Hämtar venture-licensen. |
| [getVerticalResolution()](#getVerticalResolution--) | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna RasterImage. |
| [getWarpProvider_internalized()](#getWarpProvider-internalized--) | Den hämtar funktioner som hjälper med warp |
| [getWarpSettings()](#getWarpSettings--) | Den hämtar eller anger Warp-parametrar som sattes eller hämtades från resursen (standard) |
| [getWasChanged_internalized()](#getWasChanged-internalized--) | Hämtar eller anger ett värde som indikerar om [was changed]. |
| [getWidth()](#getWidth--) | Hämtar bildens bredd. |
| [getXmpData()](#getXmpData--) | Hämtar eller anger XMP-metadata. |
| [grayscale()](#grayscale--) | Transformation av en bild till dess gråskalerepresentation |
| [hasAlpha()](#hasAlpha--) | Hämtar ett värde som indikerar om detta objekt har alfa. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Hämtar ett värde som indikerar om bilden har bakgrundsfärg. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Hämtar eller anger ett värde som indikerar om detta bildobjekt har ändrats efter inläsning. |
| [hasTransparentColor()](#hasTransparentColor--) | Hämtar ett värde som indikerar om bilden har transparent färg. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för den här instansen. |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Hämtar eller anger det maximala värdet för framsteg |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Anger framstegen. |
| [insertResource_internalized(int index, LayerResource resource)](#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Infoga en resurs i samlingen Resources. |
| [isCached()](#isCached--) | Hämtar ett värde som indikerar om bilddata för närvarande är cachad. |
| [isFontAvailable_internalized(Font font, GetPrivateFontCache getPrivateFontCache)](#isFontAvailable-internalized-com.aspose.psd.Font-com.aspose.internal.GetPrivateFontCache-) | Bestämmer om [is font available] [det angivna teckensnittet]. |
| [isLayerValid_internalized()](#isLayerValid-internalized--) | Detekterar om lagret är giltigt för att sparas till en fil. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Hämtar ett värde som indikerar om rådatainläsning är tillgänglig. |
| [isUsePalette()](#isUsePalette--) | Hämtar ett värde som indikerar om bildpaletten används. |
| [isVisible()](#isVisible--) | Hämtar eller anger ett värde som indikerar om lagret är synligt |
| [isVisibleInGroup()](#isVisibleInGroup--) | Hämtar ett värde som indikerar om detta objekt är synligt i grupp (Om lagret inte är i en grupp betyder det rotgrupp). |
| [load(InputStream stream)](#load-java.io.InputStream-) | Laddar en ny bild från den angivna strömmen. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Laddar en ny bild från den angivna strömmen. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Laddar en ny bild från den angivna strömmen. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Laddar en ny bild från den angivna strömmen. |
| [load(String filePath)](#load-java.lang.String-) | Laddar en ny bild från den angivna filen. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Laddar en ny bild från den angivna filen. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | Laddar 32-bitars ARGB-pixlar. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | Laddar 64-bitars ARGB-pixlar. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | Laddar pixlar i CMYK-format. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | Laddar pixlar i CMYK-format. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Laddar 32-bitars ARGB-pixlar partiellt i paket. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Laddar pixlar partiellt i paket. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | Laddar pixlar. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Laddar rå bilddata med hjälp av den partiella bearbetningsmekanismen. |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Laddar rå data. |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Laddar en ny bild från den angivna strömmen. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Laddar en ny bild från den angivna strömmen. |
| [mergeLayerTo(Layer layerToMergeInto)](#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-) | Slår samman lagret med angivet lager |
| [normalizeAngle()](#normalizeAngle--) | Normaliserar vinkeln. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normaliserar vinkeln. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Anropa när behållaren för denna Image har ställts in. |
| [preprocessFont_internalized(Font font, float newSize, double yyTransform)](#preprocessFont-internalized-com.aspose.psd.Font-float-double-) | Förbehandlar teckensnittet. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [removeResource_internalized(LayerResource resource)](#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Tar bort resursen. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [replaceFontWithDefault_internalized(Font font, String defaultFontName)](#replaceFontWithDefault-internalized-com.aspose.psd.Font-java.lang.String-) | Ersätter teckensnittet med standard. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Ändrar storlek på bilden. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Ändrar storlek på bilden. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändrar storlek på bilden. |
| [resizeChannelsData_internalized(Rectangle rect)](#resizeChannelsData-internalized-com.aspose.psd.Rectangle-) | Ändrar storlek på kanalernas data |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Ändrar höjden proportionellt. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Ändrar höjden proportionellt. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ändrar höjden proportionellt. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Ändrar bredden proportionellt. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Ändrar bredden proportionellt. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ändrar bredden proportionellt. |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | Ändrar lagrets storlek med den angivna inversa skalan. |
| [rotate(float angle)](#rotate-float-) | Rotera bilden runt centrum. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Rotera bilden runt centrum. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | Sparar bilddata till den underliggande strömmen. |
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Sparar objektets data till den angivna strömmen. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Sparar objektets data till den angivna strömmen. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save(String filePath)](#save-java.lang.String-) | Sparar objektets data till den angivna filplatsen. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Sparar objektets data till den angivna filplatsen. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | Sparar de 32‑bitars ARGB‑pixlarna. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | Sparar pixlarna. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | Sparar pixlarna. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | Sparar pixlarna. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Sparar rådata. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)](#save-internalized-com.aspose.psd.StreamContainer-int-int-) | Sparar data till den angivna strömbehållaren. |
| [setAbsoluteBounds_internalized(Rectangle value)](#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-) | Hämtar eller anger de absoluta gränserna. |
| [setAllowWarpRepaint_internalized(boolean value)](#setAllowWarpRepaint-internalized-boolean-) | Den hämtar eller anger render warp eller använder PS-bild |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Ställer in en bilds 32-bitars ARGB-pixel för den angivna positionen. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Ställer in ett värde som indikerar om paletten ska justeras automatiskt. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Hämtar eller anger ett värde för bakgrundsfärgen. |
| [setBlendClippedElements(boolean value)](#setBlendClippedElements-boolean-) | Hämtar eller anger blandningen av det beskurna elementet. |
| [setBlendModeKey(long value)](#setBlendModeKey-long-) | Hämtar eller anger nyckeln för blandningsläget. |
| [setBottom(int value)](#setBottom-int-) | Hämtar eller anger positionen för det nedre lagret. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ställer in en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [setChannelInformation(ChannelInformation[] value)](#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Hämtar eller anger kanalinformationen. |
| [setClipping(byte value)](#setClipping-byte-) | Hämtar eller anger lagrets beskärning. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Ställer in Image-behållaren. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Ställer in dataläsaren direkt. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Ställer in objektets datastream. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Hämtar eller anger visningsnamnet för lagret. |
| [setFillOpacity(int value)](#setFillOpacity-int-) | Hämtar fyllnadens opacitet. |
| [setFiller(byte value)](#setFiller-byte-) | Hämtar eller anger lagrets fyllnad. |
| [setFlags(byte value)](#setFlags-byte-) | Hämtar eller anger lagrets flaggor. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Ställer in paletten på format-specifika platser |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för detta RasterImage. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Ställer in ett värde som indikerar om [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Hämtar eller anger ett värde som indikerar om detta bildobjekt har ändrats efter inläsning. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Ställer in den inre datatransformern. |
| [setInnerText(String value)](#setInnerText-java.lang.String-) | Hämtar lagrets text |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Ställer in avbrottsmotorn. |
| [setLayerBlendingRangesData(LayerBlendingRangesData value)](#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-) | Hämtar eller anger data för lagerblandningsintervall. |
| [setLayerCreationDateTime(Date value)](#setLayerCreationDateTime-java.util.Date-) | Hämtar eller anger lagerns skapelsedatum och -tid. |
| [setLayerCreationDateTime_internalized(System.DateTime value)](#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-) |  |
| [setLayerLock(int value)](#setLayerLock-int-) | Hämtar eller anger lagrets lås (Observera att om flaggan LayerFlags.TransparencyProtected är satt så kommer den att skrivas över av lagrets låsflagga. |
| [setLayerMaskData(LayerMaskData value)](#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Hämtar eller anger data för lagermasken. |
| [setLayerPalette_internalized(IColorPalette value)](#setLayerPalette-internalized-com.aspose.psd.IColorPalette-) | Hämtar eller anger lagerpaletten. |
| [setLeft(int value)](#setLeft-int-) | Hämtar eller anger lagrets vänstra position. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Hämtar eller anger maximal tillåten allokering för partiell roterings‑sparning. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Ställer in minneshanteraren. |
| [setName(String name)](#setName-java.lang.String-) | Ställer in lagrets namn. |
| [setName_internalized(String value)](#setName-internalized-java.lang.String-) | Hämtar eller anger lagrets namn. |
| [setOpacity(byte value)](#setOpacity-byte-) | Hämtar eller anger lagrets opacitet. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ställer in färgpaletten. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Ställer in bildpaletten. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Ställer in en bildpixel för den angivna positionen. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Hämtar eller anger ett värde som indikerar om bildkomponenterna måste vara förmultiplicerade. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Hämtar eller anger den anpassade färgkonverteraren |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Hämtar eller anger reservindexen att använda när palettindexet är utanför gränserna |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Hämtar eller anger den indexerade färgkonverteraren |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Ställer in upplösningen för detta RasterImage. |
| [setResourceProcessor_internalized(TypeToolResourceProcessor value)](#setResourceProcessor-internalized-com.aspose.internal.fileformats.psd.layers.TypeToolResourceProcessor-) | Hämtar eller anger resursprocessorn. |
| [setResources(LayerResource[] value)](#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Hämtar eller anger lagerresurserna. |
| [setRight(int value)](#setRight-int-) | Hämtar eller anger den högra lagerpositionen. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Hämtar eller anger roteringsläget. |
| [setSheetColorHighlight(short value)](#setSheetColorHighlight-short-) | Hämtar eller anger den dekorativa bladfärgens markering i lagerlistan |
| [setTextBoundBox(RectangleF value)](#setTextBoundBox-com.aspose.psd.RectangleF-) | Hämtar eller anger textens avgränsningsruta. |
| [setTop(int value)](#setTop-int-) | Hämtar eller anger den övre lagerpositionen. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Hämtar eller anger transformationsmatrisen |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Hämtar ett värde som indikerar om bilden har transparent färg. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Hämtar bildens transparenta färg. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Hämtar eller anger ett värde som indikerar om XMP‑metadata ska uppdateras. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Alla Aspose‑produkter bör implementera den här metoden. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna RasterImage. |
| [setVisible(boolean value)](#setVisible-boolean-) | Hämtar eller anger ett värde som indikerar om lagret är synligt |
| [setWarpSettings(WarpSettings value)](#setWarpSettings-com.aspose.psd.fileformats.psd.layers.warp.structs.WarpSettings-) | Den hämtar eller anger Warp-parametrar som sattes eller hämtades från resursen (standard) |
| [setWasChanged_internalized(boolean value)](#setWasChanged-internalized-boolean-) | Hämtar eller anger ett värde som indikerar om [was changed]. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Hämtar eller anger XMP-metadata. |
| [shallowCopy()](#shallowCopy--) | Skapar en ytlig kopia av det aktuella lagret. |
| [toBitmap()](#toBitmap--) | Konverterar rasterbild till bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [updateBlendingOptions_internalized(PattResource pattResource)](#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Uppdaterar blandningsalternativen efter att lager‑ eller globala resurser har ändrats. |
| [updateBounds_internalized(RectangleF absoluteTextBounds, RectangleF inBoxTextBounds)](#updateBounds-internalized-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Uppdaterar gränserna för [TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) i resurserna. |
| [updateText(String text)](#updateText-java.lang.String-) | Uppdaterar texten. |
| [updateText(String text, Color color)](#updateText-java.lang.String-com.aspose.psd.Color-) | Uppdaterar texten. |
| [updateText(String text, Point leftTopCoordinate)](#updateText-java.lang.String-com.aspose.psd.Point-) | Uppdaterar texten. |
| [updateText(String text, Point leftTopCoordinate, Color color)](#updateText-java.lang.String-com.aspose.psd.Point-com.aspose.psd.Color-) | Uppdaterar texten. |
| [updateText(String text, Point leftTopCoordinate, float fontSize)](#updateText-java.lang.String-com.aspose.psd.Point-float-) | Uppdaterar texten. |
| [updateText(String text, Point leftTopCoordinate, float fontSize, Color color)](#updateText-java.lang.String-com.aspose.psd.Point-float-com.aspose.psd.Color-) | Uppdaterar texten. |
| [updateText(String text, float fontSize)](#updateText-java.lang.String-float-) | Uppdaterar texten. |
| [updateText(String text, float fontSize, Color color)](#updateText-java.lang.String-float-com.aspose.psd.Color-) | Uppdaterar texten. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Skriver hela skanningsraden till det angivna skanningsradindexet. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Skriver hela skanningsraden till det angivna skanningsradindexet. |
### BlendSignature {#BlendSignature}
```
public static final int BlendSignature
```


Representerar signatur för blandningsläge.

### LayerHeaderSize {#LayerHeaderSize}
```
public static final int LayerHeaderSize
```


Storleken på lagerhuvudet.

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Uppstår när bilden har laddats

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Uppstår när bilden har laddats av createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Uppstår när bilden har laddats eller sparats

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Uppstår när kredit har använts

### resources_internalized {#resources-internalized}
```
public ResourceNest resources_internalized
```


Resurserna

### <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource) {#-T-tryGetResource-internalized-java.lang.Class-T--T---}
```
public final boolean <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)
```


Hämtar resursen som är associerad med den angivna typen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | resource | T[] | När denna metod returnerar, innehåller resursen som är associerad med den angivna nyckeltypen, om nyckeln hittas; annars returneras null. |

T : Nyckeltypen för värdet som ska hämtas. |

**Returns:**
boolean -   om den innehåller en resurs med den angivna typen; annars,  .
### addLayerMask(LayerMaskData layerMask) {#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void addLayerMask(LayerMaskData layerMask)
```


Lägger till masken till det aktuella lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layerMask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Lagermasken. |

### addResource_internalized(LayerResource resource) {#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void addResource_internalized(LayerResource resource)
```


Lägger till resursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | Resursen. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Justering av ljusstyrka för bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ljusstyrka | int | Ljusstyrkevärde. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Bildkontrast

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kontrast | float | Kontrastvärde (i intervallet [-100; 100]) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Gamma-korrigering av en bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | float | Gamma för röd, grön och blå kanalkoefficient |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gamma-korrigering av en bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gammaRed | float | Gamma för röd kanal koefficient |
| gammaGreen | float | Gamma för grön kanal koefficient |
| gammaBlue | float | Gamma för blå kanal koefficient |

### applyLayerMask() {#applyLayerMask--}
```
public final void applyLayerMask()
```


Applicerar lagermasken på lagret och tar sedan bort masken.

### applyLayerState_internalized(LayerState layerState) {#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-}
```
public final void applyLayerState_internalized(LayerState layerState)
```


Tillämpar lagerstilsinställningen från indata [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) till den aktuella [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layerState | [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) | Lagerstatusen med ny stil. |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


Påbörjar storleksändringsprocessen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bildbredden. |
| newHeight | int | Den nya bildhöjden. |

**Returns:**
com.aspose.internal.IResizeController - Resizerkontrollen.
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildströskling

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightnessDifference | double | Ljusstyrkeskillnaden mellan pixeln och genomsnittet av ett s x s fönster av pixlar centrerade kring denna pixel. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildströskling

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightnessDifference | double | Ljusstyrkeskillnaden mellan pixeln och genomsnittet av ett s x s fönster av pixlar centrerade kring denna pixel. |
| windowSize | int | Storleken på ett s x s fönster av pixlar centrerade kring denna pixel |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarisering av en bild med fördefinierad tröskel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln, tilldelas värdet 255, annars 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarisering av en bild med Otsu-tröskling

### cacheData() {#cacheData--}
```
public void cacheData()
```


Cachar data och säkerställer att ingen ytterligare datainläsning kommer att utföras från den underliggande DataStreamSupporter.DataStreamContainer.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Bestämmer om bilden kan läsas in från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Strömmen att läsa från. |

**Returns:**
boolean -  true  om bilden kan läsas från den angivna strömmen; annars,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna loadOptions.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Strömmen att läsa från. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns:**
boolean -  true  om bilden kan läsas från den angivna strömmen; annars,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Bestämmer om bilden kan läsas in från den angivna filsökvägen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen. |

**Returns:**
boolean -  true  om bilden kan läsas från den angivna filen; annars,  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna open options.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns:**
boolean -  true  om bilden kan läsas från den angivna filen; annars,  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de medföljande save options.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Sparaalternativen att använda. |

**Returns:**
boolean -  true  om bilden kan sparas till det angivna filformatet som representeras av de överförda sparaalternativen; annars,  false .
### close() {#close--}
```
public void close()
```


Implementerar Closable‑gränssnittet och kan användas i try‑with‑resources‑satsen sedan JDK 1.7. Denna metod anropar helt enkelt dispose‑metoden.

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


Konverterar till aps.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Alternativen. |
| mode | int | Läget. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Klippningsrektangeln. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - APS‑sidan.
### correctFontSize_internalized(float newSize, double yyTransform) {#correctFontSize-internalized-float-double-}
```
public static float correctFontSize_internalized(float newSize, double yyTransform)
```


Korrigerar teckensnittets storlek

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newSize | float | Ny teckenstorlek |
| yyTransform | double | 'yy' Transform-matrisparameter |

**Returns:**
float - Korrigerad storlek
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Skapar en ny bild med de angivna create options.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Bildalternativen. |
| bredd | int | Bredden. |
| höjd | int | Höjden. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Skapar en ny bild med de angivna bilderna som sidor

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Bilderna. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Skapar en ny bild med de angivna bilderna som sidor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Bilderna. |
| disposeImages | boolean | om inställd på true [avyttra bilder]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createInstance_internalized() {#createInstance-internalized--}
```
public static TextLayer createInstance_internalized()
```


Skapar en ny instans av klassen [TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer).

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - New Text Layer
### createInstance_internalized(PsdHeader header, IColorPalette palette) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-}
```
public static TextLayer createInstance_internalized(PsdHeader header, IColorPalette palette)
```


Skapar en ny instans av klassen [TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rubrik | com.aspose.internal.fileformats.psd.sections.PsdHeader | Rubriken. |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Paletten. |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - Returns the new instance of the [TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) class.
### createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static Layer createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)
```


Skapar den nya instansen av klassen [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rubrik | com.aspose.internal.fileformats.psd.sections.PsdHeader | Rubriken. |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Paletten. |
| linkedLayersRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry | Den LinkedLayersRegistry. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Returns the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class.
### createLayerState_internalized() {#createLayerState-internalized--}
```
public final LayerState createLayerState_internalized()
```


Skapar den nya [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instansen baserat på aktuella [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) värden.

**Returns:**
[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) - The new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resizer | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| bredd | int |  |
| höjd | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(PsdHeader header, IColorPalette colorPalette, LayerAndMaskInfo layerAndMaskInfo, LayerResource[] resources) {#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public static TextLayer create_internalized(PsdHeader header, IColorPalette colorPalette, LayerAndMaskInfo layerAndMaskInfo, LayerResource[] resources)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rubrik | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |
| layerAndMaskInfo | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |
| resources | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer)
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Layer create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beskär bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Beskär bilden med förskjutningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftShift | int | Den vänstra förskjutningen. |
| rightShift | int | Den högra förskjutningen. |
| topShift | int | Den övre förskjutningen. |
| bottomShift | int | Den nedre förskjutningen. |

### dispose() {#dispose--}
```
public final void dispose()
```


Frigör den aktuella instansen.

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Utför dithering på den aktuella bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ditheringMethod | int | Dithermetoden. |
| bitsCount | int | Det slutliga bitantalet för dithering. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Utför dithering på den aktuella bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ditheringMethod | int | Dithermetoden. |
| bitsCount | int | Det slutliga bitantalet för dithering. |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Den anpassade paletten för dithering. |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


Beskär bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln. |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändrar storlek på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Inställningarna för storleksändring. |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float |  |
| resizeProportionally | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


Roterar, vänder eller roterar och vänder bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | Rotations- och vändningstypen. |

### drawImage(Point location, RasterImage image) {#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-}
```
public final void drawImage(Point location, RasterImage image)
```


Ritar bilden på lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | Platsen. |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Bilden. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna objektet är lika med denna instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att jämföra med den här instansen. |

**Returns:**
boolean -  true  om det angivna objektet är lika med den här instansen; annars,  false .
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtrerar den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln. |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | Alternativen. |

### findAssignableResource_internalized(System.Type type) {#findAssignableResource-internalized-com.aspose.ms.System.Type-}
```
public final LayerResource findAssignableResource_internalized(System.Type type)
```


Hittar den tilldelningsbara resursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | com.aspose.ms.System.Type | Typen. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - 
### findPattResource_internalized() {#findPattResource-internalized--}
```
public final PattResource findPattResource_internalized()
```


Hittar den  PattResource

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - The found resource or null
### findResource_internalized(int typeToolKey) {#findResource-internalized-int-}
```
public final LayerResource findResource_internalized(int typeToolKey)
```


Hittar resursen efter unik nyckel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeToolKey | int | Typverktygets nyckel. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - Found resource or null
### getAbsoluteBounds_internalized() {#getAbsoluteBounds-internalized--}
```
public final Rectangle getAbsoluteBounds_internalized()
```


Hämtar eller anger de absoluta gränserna.

Värde: De absoluta gränserna.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getAllowWarpRepaint_internalized() {#getAllowWarpRepaint-internalized--}
```
public final boolean getAllowWarpRepaint_internalized()
```


Den hämtar eller anger render warp eller använder PS-bild

**Returns:**
boolean
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Hämtar en bildpixel i 32-bit ARGB.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Pixelns x‑position. |
| y | int | Pixelns y‑position. |

**Returns:**
int - Den 32‑bitars ARGB‑pixel för den angivna platsen.
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Hämtar ett värde som indikerar om paletten justeras automatiskt.

**Returns:**
boolean -  true  om automatisk justering av palett är aktiverad; annars,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar eller anger ett värde för bakgrundsfärgen.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

Värde: Antalet bildbitar per pixel.

**Returns:**
int
### getBlendClippedElements() {#getBlendClippedElements--}
```
public final boolean getBlendClippedElements()
```


Hämtar eller anger blandningen av det beskurna elementet.

Värde: Blandning av klippt element.

**Returns:**
boolean
### getBlendModeKey() {#getBlendModeKey--}
```
public long getBlendModeKey()
```


Hämtar eller anger nyckeln för blandningsläget.

Värde: Nyckeln för blandningsläget.

**Returns:**
long
### getBlendModeSignature() {#getBlendModeSignature--}
```
public final int getBlendModeSignature()
```


Hämtar signaturen för blandningsläget.

Värde: Signaturen för blandningsläget.

**Returns:**
int
### getBlendingOptions() {#getBlendingOptions--}
```
public final BlendingOptions getBlendingOptions()
```


Hämtar blandningsalternativen.

Värde: Blandningsalternativen.

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
### getBottom() {#getBottom--}
```
public int getBottom()
```


Hämtar eller anger positionen för det nedre lagret.

Värde: Positionen för det nedre lagret.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar bildens gränser.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Hämtar en ledtråd för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Tips om buffertstorlek, i megabyte. Icke‑positivt värde betyder ingen minnesbegränsning för interna buffertar.

**Returns:**
int - tips om buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.
### getBytesPerRowForFullMask_internalized(int bitDepth) {#getBytesPerRowForFullMask-internalized-int-}
```
public final int getBytesPerRowForFullMask_internalized(int bitDepth)
```


Hämtar antalet byte per rad för full maskläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitDepth | int | Bitdjupet. |

**Returns:**
int - Antal byte som behövs för att lagra 1 rad
### getBytesPerRowForMask_internalized(int bitDepth) {#getBytesPerRowForMask-internalized-int-}
```
public final int getBytesPerRowForMask_internalized(int bitDepth)
```


Hämtar antalet byte per rad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitDepth | int | Bitdjupet. |

**Returns:**
int - Antal byte som behövs för att lagra 1 rad
### getBytesPerRow_internalized(int bitDepth) {#getBytesPerRow-internalized-int-}
```
public final int getBytesPerRow_internalized(int bitDepth)
```


Hämtar antalet byte per rad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitDepth | int | Bitdjupet. |

**Returns:**
int - Antal byte som behövs för att lagra 1 rad
### getChannelInformation() {#getChannelInformation--}
```
public final ChannelInformation[] getChannelInformation()
```


Hämtar eller anger kanalinformationen.

Värde: Kanalinformationen.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Hämtar lagrets kanalantal.

Värde: Antalet kanaler i lagret.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClipping() {#getClipping--}
```
public final byte getClipping()
```


Hämtar eller anger lagerklippning. 0 = bas, 1 = icke‑bas.

Värde: Lagerklippning.

**Returns:**
byte
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Hämtar  Image  behållaren.

Värde: Bildbehållaren.

Om den här egenskapen inte är null indikerar det att bilden är inbäddad i en annan bild.

**Returns:**
[Image](../../com.aspose.psd/image)
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Hämtar objektets datastream.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Hämtar den djupt justerade paletten.

**Returns:**
boolean - Den djupa justeringspaletten.
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Hämtar standard 32-bit ARGB-pixelarrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln för att hämta pixlar för. |

**Returns:**
int[] - Standardpixelarrayen.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Hämtar standardalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | java.lang.Object[] | Argumenten. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Hämtar standardpixelarrayen med partiell pixel‑läsare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln för att hämta pixlar för. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Den partiella pixelinläsaren. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Hämtar standardrådataarrayen med partiell pixel‑läsare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln för att hämta pixlar för. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Den partiella rådatainläsaren. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Inställningarna för rådata. |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Hämtar standardrådataarrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln för att hämta rådata för. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Inställningarna för rådata. |

**Returns:**
byte[] - Standardrådataarrayen.
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Hämtar lagrets visningsnamn.

Värde: Visningsnamnet för lagret.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean -  true  om frigjord; annars,  false .
### getEngineData_internalized() {#getEngineData-internalized--}
```
public final EngineData getEngineData_internalized()
```


Hämtar motorens data.

Värde: Motorinformationen.

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.tyshresource.EngineData
### getExtraLength() {#getExtraLength--}
```
public final int getExtraLength()
```


Hämtar lagrets extra informationslängd i byte.

Värde: Extra lagers längd.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämtar ett värde för filformat

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Hämtar filformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Strömmen. |

--------------------

Den bestämda filformatet betyder inte att den angivna bilden kan laddas. Använd en av CanLoad-metodens överlagringar för att avgöra om strömmen kan laddas. |

**Returns:**
long - Det bestämda filformatet.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Hämtar filformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | java.io.InputStream | Strömmen. |

Den bestämda filformatet betyder inte att den angivna bilden kan laddas. Använd en av CanLoad-metodens överlagringar för att avgöra om strömmen kan laddas. |

**Returns:**
long - Det bestämda filformatet.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Hämtar filformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filvägen. |

Det bestämda filformatet betyder inte att den angivna bilden kan laddas. Använd en av CanLoad-metodens överlagringar för att avgöra om filen kan laddas. |

**Returns:**
long - Det bestämda filformatet.
### getFillOpacity() {#getFillOpacity--}
```
public final int getFillOpacity()
```


Hämtar eller anger fyllningsopaciteten.

**Returns:**
int
### getFiller() {#getFiller--}
```
public final byte getFiller()
```


Hämtar eller anger lagrets fyllnad.

Värde: Lagrets fyllare.

**Returns:**
byte
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Hämtar rektangeln som passar den aktuella bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln för att få en passande rektangel för. |
| bredd | int | Objektets bredd. |
| höjd | int | Objektets höjd. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Hämtar rektangeln som passar den aktuella bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln för att få en passande rektangel för. |
| pixlar | int[] | De 32-bitars ARGB-pixlarna. |
| bredd | int | Objektets bredd. |
| höjd | int | Objektets höjd. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Hämtar eller anger lagerflaggorna. bit 0 = transparensskyddad; bit 1 = synlig; bit 2 = föråldrad; bit 3 = 1 för Photoshop 5.0 och senare, anger om bit 4 har användbar information; bit 4 = pixeldata irrelevant för dokumentets utseende.

Värde: Lagerflaggorna.

**Returns:**
byte
### getFoldersHierarchy_internalized() {#getFoldersHierarchy-internalized--}
```
public final System.Collections.Generic.List<Layer> getFoldersHierarchy_internalized()
```


Hämtar listan över [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) mapphierarkin för det aktuella lagret.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.Layer> - Returnerar listan av [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) mapphierarkin för aktuellt lager.
### getFont() {#getFont--}
```
public final Font getFont()
```


Hämtar teckensnittet.

Värde: Typsnittet.

**Returns:**
[Font](../../com.aspose.psd/font)
### getFonts() {#getFonts--}
```
public final TextFontInfo[] getFonts()
```


Hämtar teckensnittssamlingen för textlagret.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.TextFontInfo[] - Teckensnittssamlingen för textlagret.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Hämtar palett från format‑specifika platser

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGUID_internalized() {#getGUID-internalized--}
```
public final String getGUID_internalized()
```


Hämtar det unika identifieraren för detta Layer‑instans.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Hämtar eller anger rubriken.

Värde: Headern.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar bildens höjd.

Värde: Bildens höjd.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för detta RasterImage.

**Returns:**
double - Den horisontella upplösningen.

Obs! Som standard är detta värde alltid 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Hämtar opaciteten för denna bild.

**Returns:**
float - Opacitetsvärdet mellan 0,0 (fullt transparent) och 1,0 (fullt ogenomskinligt).
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


Hämtar den interna datatransformern.

Värde: Den inre datatransformern.

**Returns:**
com.aspose.internal.IInnerDataTransformer - den inre datatransformern.
### getInnerText() {#getInnerText--}
```
public final String getInnerText()
```


Hämtar lagrets text

Värde: Texten.

**Returns:**
java.lang.String
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Hämtar avbrotts­övervakaren.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerBlendingRangesData() {#getLayerBlendingRangesData--}
```
public final LayerBlendingRangesData getLayerBlendingRangesData()
```


Hämtar eller anger data för lagerblandningsintervall.

Värde: Lagerblandningsområdens data.

**Returns:**
[LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata)
### getLayerCreationDateTime() {#getLayerCreationDateTime--}
```
public final Date getLayerCreationDateTime()
```


Hämtar eller anger lagerns skapelsedatum och -tid.

Värde: Lagrets skapelsedatum och tid. Om det inte finns någon data om skapelsedatumet returneras Unix-tidens första epok.

**Returns:**
java.util.Date
### getLayerCreationDateTime_internalized() {#getLayerCreationDateTime-internalized--}
```
public final System.DateTime getLayerCreationDateTime_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getLayerLock() {#getLayerLock--}
```
public final int getLayerLock()
```


Hämtar eller anger lagerlåset. Observera att om flaggan LayerFlags.TransparencyProtected är satt kommer den att skrivas över av lagerlåsflaggan. För att returnera flaggan LayerFlags.TransparencyProtected måste du tillämpa lageralternativet layer.Flags |= LayerFlags.TransparencyProtected

Värde: Lagerlåset.

**Returns:**
int
### getLayerMaskData() {#getLayerMaskData--}
```
public final LayerMaskData getLayerMaskData()
```


Hämtar eller anger data för lagermasken.

Värde: Lagermaskens data.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
### getLayerOptions() {#getLayerOptions--}
```
public final PsdOptions getLayerOptions()
```


Hämtar lageralternativen.

Värde: Lageralternativen.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)
### getLayerPalette_internalized() {#getLayerPalette-internalized--}
```
public final IColorPalette getLayerPalette_internalized()
```


Hämtar eller anger lagerpaletten.

Värde: Lagerpaletten.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getLayerType_internalized() {#getLayerType-internalized--}
```
public byte getLayerType_internalized()
```


Hämtar lagrets typ.

Värde: Lagrets typ.

**Returns:**
byte
### getLeft() {#getLeft--}
```
public int getLeft()
```


Hämtar eller anger lagrets vänstra position.

Värde: Vänstra lagerpositionen.

**Returns:**
int
### getLength() {#getLength--}
```
public final long getLength()
```


Hämtar lagrets totala längd i byte.

**Returns:**
long
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


Hämtar eller anger maximal tillåten allokering för partiell roterings‑sparning.

**Returns:**
int - Max tillåten allokering för partiell roteringssparning.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Hämtar minneshanteraren.

Värde: Minneshanteraren.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - minneshanteraren.
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Hämtar datum och tid då resursbilden senast ändrades.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| useDefault | boolean | om den är inställd på  true  använder informationen från FileInfo som standardvärde. |

**Returns:**
java.util.Date - Datum och tid då resursbilden senast ändrades.
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getName() {#getName--}
```
public final String getName()
```


Hämtar eller anger lagrets namn.

Värde: Lagernamnet.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Hämtar eller anger lageropaciteten. 0 = transparent, 255 = ogenomskinlig.

Värde: Lageropaciteten.

**Returns:**
byte
### getOpacityTotal_internalized() {#getOpacityTotal-internalized--}
```
public final byte getOpacityTotal_internalized()
```


Hämtar den totala opaciteten. Den totala opaciteten är multiplikationen av Lageropaciteten och Lagerfyllningsopaciteten. Den används för lagerblandning.

Värde: Den totala opaciteten.

**Returns:**
byte
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara användbart för att behålla bitdjup och andra parametrar för den ursprungliga bilden oförändrade. Till exempel, om vi laddar en svart-vit PNG-bild med 1 bit per pixel och sedan sparar den med metoden  DataStreamSupporter.Save(string) , kommer den resulterande PNG-bilden med 8 bit per pixel att skapas. För att undvika detta och spara PNG-bilden med 1 bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem till metoden  Image.Save(string, ImageOptionsBase)  som den andra parametern.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Hämtar den målbara bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Hämtar färgpaletten. Färgpaletten används inte när pixlar representeras direkt.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Hämtar en bildpixel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Pixelns x‑position. |
| y | int | Pixelns y‑position. |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Hämtar eller anger ett värde som indikerar om bildkomponenterna måste vara förmultiplicerade.

**Returns:**
boolean -  true  om bildkomponenterna måste vara förmultiplikerade; annars,  false .
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Skapar den privata teckensnittscachen.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - Den privata teckensnittscachen.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Hämtar information om progress‑händelsehanteraren.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Hämtar information om progress‑händelsehanteraren.

Värde: Information om händelsehanteraren för framsteg.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Hämtar en proportionell höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden. |
| höjd | int | Höjden. |
| newWidth | int | Den nya bredden. |

**Returns:**
int - Den proportionella höjden.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Hämtar en proportionell bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden. |
| höjd | int | Höjden. |
| newHeight | int | Den nya höjden. |

**Returns:**
int - Den proportionella bredden.
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Hämtar eller anger den anpassade färgkonverteraren

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Hämtar det råa dataformatet.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Hämtar de aktuella rådatainställningarna. Observera att när dessa inställningar används laddas data utan konvertering.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Hämtar eller anger reservindexen att använda när palettindexet är utanför gränserna

**Returns:**
int - Reservindexet att använda när palettindexet är utanför gränserna
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Hämtar eller anger den indexerade färgkonverteraren

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Hämtar den råa radstorleken i byte.

**Returns:**
int - Rålinjestorleken i byte.
### getResourceProcessor_internalized() {#getResourceProcessor-internalized--}
```
public final TypeToolResourceProcessor getResourceProcessor_internalized()
```


Hämtar eller anger resursprocessorn.

Värde: Resursprocessorn.

**Returns:**
com.aspose.internal.fileformats.psd.layers.TypeToolResourceProcessor
### getResources() {#getResources--}
```
public final LayerResource[] getResources()
```


Hämtar eller anger lagerresurserna.

Värde: Lagerresurserna.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getRight() {#getRight--}
```
public int getRight()
```


Hämtar eller anger den högra lagerpositionen.

Värde: Den högra lagerpositionen.

**Returns:**
int
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Hämtar eller anger roteringsläget.

**Returns:**
int - Rotationsläget.
### getSheetColorHighlight() {#getSheetColorHighlight--}
```
public final short getSheetColorHighlight()
```


Hämtar eller anger den dekorativa bladfärgens markering i lagerlistan

Värde: Markering av bladfärgen.

**Returns:**
short
### getSize() {#getSize--}
```
public Size getSize()
```


Hämtar bildens storlek.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Hämtar snedvinkeln. Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning.

**Returns:**
float - Snedvinkeln i grader.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Hämtar filsökvägen för källbilden om den finns. Returnerar en tom sträng om källsökvägen inte kan hittas.

**Returns:**
java.lang.String - Filsökvägen för källbilden.
### getStringFormat_internalized() {#getStringFormat-internalized--}
```
public final StringFormat getStringFormat_internalized()
```


Hämtar strängformatet.

Värde: Strängformatet.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat)
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Hämtar synkroniseringsroten.

Värde: Synkroniseringsroten.

**Returns:**
java.lang.Object
### getText() {#getText--}
```
public final String getText()
```


Hämtar texten.

Värde: Texten.

**Returns:**
java.lang.String
### getTextBoundBox() {#getTextBoundBox--}
```
public final RectangleF getTextBoundBox()
```


Hämtar eller anger textens avgränsningsruta.

Värde: Textens begränsningsruta.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getTextColor() {#getTextColor--}
```
public final Color getTextColor()
```


Hämtar textens färg.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTextData() {#getTextData--}
```
public final IText getTextData()
```


Hämtar textens delar.

**Returns:**
[IText](../../com.aspose.psd.fileformats.psd.layers.text/itext) - 
### getTop() {#getTop--}
```
public int getTop()
```


Hämtar eller anger den övre lagerpositionen.

Värde: Den övre lagerpositionen.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Hämtar eller anger transformationsmatrisen

Värde: Transformationsmatrisen

**Returns:**
double[]
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Hämtar bildens transparenta färg.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTyShResourceIfExists_internalized() {#getTyShResourceIfExists-internalized--}
```
public final TypeToolInfo6Resource getTyShResourceIfExists_internalized()
```


Söker och hämtar [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource)-resursen från [TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer).

**Returns:**
[TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource) - Returns the [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource) resource from the [TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer).
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Hämtar eller anger ett värde som indikerar om XMP‑metadata ska uppdateras.

**Returns:**
boolean -  true  om XMP-metadata uppdateras; annars  false .
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Hämtar ett värde som indikerar om objektet använder minnesoptimeringsstrategi

Värde:  true  om objektet använder minnesoptimeringsstrategi; annars  false .

**Returns:**
boolean - ett värde som indikerar om objektet använder minnesoptimeringsstrategi
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig.

**Returns:**
boolean -  true  om rådata laddas när rådata laddning är tillgänglig; annars  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


Hämtar den använda paletten.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Hämtar venture-licensen.

**Returns:**
java.lang.Object - Venture-licensen som objekt.
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna RasterImage.

**Returns:**
double - Den vertikala upplösningen.

Obs! Som standard är detta värde alltid 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
### getWarpProvider_internalized() {#getWarpProvider-internalized--}
```
public final TextLayerWarpProvider getWarpProvider_internalized()
```


Den hämtar funktioner som hjälper med warp

**Returns:**
com.aspose.internal.fileformats.psd.layers.warp.TextLayerWarpProvider
### getWarpSettings() {#getWarpSettings--}
```
public final WarpSettings getWarpSettings()
```


Den hämtar eller anger Warp-parametrar som sattes eller hämtades från resursen (standard)

**Returns:**
[WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings)
### getWasChanged_internalized() {#getWasChanged-internalized--}
```
public final boolean getWasChanged_internalized()
```


Hämtar eller anger ett värde som indikerar om [was changed].

Värde:  true  om [was changed]; annars,  false .

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bildens bredd.

Värde: Bildens bredd.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Hämtar eller anger XMP-metadata.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation av en bild till dess gråskalerepresentation

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Hämtar ett värde som indikerar om detta objekt har alfa.

Värde:  true  om detta objekt har alfa; annars  false .

**Returns:**
boolean
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Hämtar ett värde som indikerar om bilden har bakgrundsfärg.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Hämtar eller anger ett värde som indikerar om detta bildobjekt har ändrats efter inläsning.

**Returns:**
boolean -  true  om detta objekt har bildändring; annars  false .
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Hämtar ett värde som indikerar om bilden har transparent färg.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för den här instansen.

**Returns:**
int - En hashkod för den här instansen, lämplig för användning i hash‑algoritmer och datastrukturer som en hashtabell.
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


Hämtar eller anger det maximala värdet för framsteg

Värde: Maximalt värde för framsteg

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Anger framstegen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### insertResource_internalized(int index, LayerResource resource) {#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void insertResource_internalized(int index, LayerResource resource)
```


Infoga en resurs i samlingen Resources.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för resursen som ska infogas. |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | Resursen som ska infogas. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Hämtar ett värde som indikerar om bilddata för närvarande är cachad.

**Returns:**
boolean -  true  om bilddata är cachad; annars  false .
### isFontAvailable_internalized(Font font, GetPrivateFontCache getPrivateFontCache) {#isFontAvailable-internalized-com.aspose.psd.Font-com.aspose.internal.GetPrivateFontCache-}
```
public static boolean isFontAvailable_internalized(Font font, GetPrivateFontCache getPrivateFontCache)
```


Bestämmer om [is font available] [det angivna teckensnittet].

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | Teckensnittet. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
boolean - Sant om teckensnittet är tillgängligt
### isLayerValid_internalized() {#isLayerValid-internalized--}
```
public boolean isLayerValid_internalized()
```


Detekterar om lagret är giltigt för att sparas till en fil.

**Returns:**
boolean -
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Hämtar ett värde som indikerar om rådatainläsning är tillgänglig.

**Returns:**
boolean -  true  om denna rådata laddning är tillgänglig; annars  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Hämtar ett värde som indikerar om bildpaletten används.

Värde:  true  om paletten används i bilden; annars  false .

**Returns:**
boolean - ett värde som indikerar om bildpaletten används.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Hämtar eller anger ett värde som indikerar om lagret är synligt

Värde:  true  om detta objekt är synligt; annars  false .

**Returns:**
boolean
### isVisibleInGroup() {#isVisibleInGroup--}
```
public boolean isVisibleInGroup()
```


Hämtar ett värde som indikerar om detta objekt är synligt i grupp (Om lagret inte är i en grupp betyder det rotgrupp).

Värde:  true  om detta objekt är synligt i gruppen; annars,  false .

**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Strömmen att läsa bilden från. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Strömmen att läsa bilden från. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att läsa bilden från. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att läsa bilden från. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Laddar en ny bild från den angivna filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att läsa bilden från. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Laddar en ny bild från den angivna filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att läsa bilden från. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Laddar 32-bitars ARGB-pixlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln att läsa pixlar från. |

**Returns:**
int[] - Den laddade 32-bitars ARGB-pixelarrayen.
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


Laddar 64-bitars ARGB-pixlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln att läsa pixlar från. |

**Returns:**
long[] - Den laddade 64-bitars ARGB-pixelarrayen.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Laddar pixlar i CMYK-format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln att läsa pixlar från. |

**Returns:**
int[] - De laddade CMYK-pixlarna presenteras som 32-bitars heltalsvärden.
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


Laddar pixlar i CMYK-format. Denna metod är föråldrad. Använd den mer effektiva metoden  loadCmyk32Pixels(Rectangle)  istället.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln att läsa pixlar från. |

**Returns:**
com.aspose.psd.CmykColor[] - Den laddade CMYK-pixelarrayen.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Laddar 32-bitars ARGB-pixlar partiellt i paket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Den önskade rektangeln. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Den 32-bitars ARGB-pixelinläsaren. |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Laddar pixlar partiellt i paket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Den önskade rektangeln. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | Pixelinläsaren. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Laddar pixlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln att läsa pixlar från. |

**Returns:**
com.aspose.psd.Color[] - Den laddade pixelarrayen.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Laddar rå bilddata med hjälp av den partiella bearbetningsmekanismen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Det önskade rektangulära området i bilden att läsa data från. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Inställningarna för rådata. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Rådatainläsaren. |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Laddar rå data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln att läsa rådata från. |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | Målbildernas gränser. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Rådatainställningarna att använda för laddade data. Observera att om data inte är i det angivna formatet kommer datakonvertering att utföras. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Rådatainläsaren. |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Strömmen att läsa bilden från. |
| startPosition | long | Startpositionen att läsa bilden från. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Strömmen att läsa bilden från. |
| startPosition | long | Startpositionen att läsa bilden från. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### mergeLayerTo(Layer layerToMergeInto) {#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public void mergeLayerTo(Layer layerToMergeInto)
```


Slår samman lagret med angivet lager

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layerToMergeInto | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lagret att slå samman med. |

### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning. Metoden använder [.getSkewAngle](../../null/\#getSkewAngle) och [.rotate(float)](../../null/\#rotate-float-) metoder.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning. Metoden använder [.getSkewAngle](../../null/\#getSkewAngle) och [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-) metoder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resizeProportionally | boolean | om den är inställd på true kommer bildens storlek att ändras enligt roterad rektangel (hörnpunkter) projektioner, annars lämnas dimensionerna orörda och endast bildens innehåll roteras. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Färgen på bakgrunden. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


Anropa när behållaren för denna Image har ställts in.

### preprocessFont_internalized(Font font, float newSize, double yyTransform) {#preprocessFont-internalized-com.aspose.psd.Font-float-double-}
```
public Font preprocessFont_internalized(Font font, float newSize, double yyTransform)
```


Förbehandlar teckensnittet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | Teckensnittet. |
| newSize | float | Ny teckenstorlek |
| yyTransform | double | 'yy' Transform-matrisparameter |

**Returns:**
[Font](../../com.aspose.psd/font) - \{@link \#\#Aspose\#PSD\} instance based on resolved font info
### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Läser hela skanningslinjen med det angivna skanningslinjeindexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scanLineIndex | int | Nollbaserat index för skanningslinjen. |

**Returns:**
int[] – Array med 32‑bit ARGB‑färgvärden för skanningslinjen.
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Läser hela skanningslinjen med det angivna skanningslinjeindexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scanLineIndex | int | Nollbaserat index för skanningslinjen. |

**Returns:**
com.aspose.psd.Color[] – Array med pixel‑färgvärden för skanningslinjen.
### removeResource_internalized(LayerResource resource) {#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void removeResource_internalized(LayerResource resource)
```


Tar bort resursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | Resursen. |

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | Gammal färg som ska ersättas. |
| oldColorDiff | byte | Tillåten skillnad i den gamla färgen för att kunna bredda den ersatta färgtonen. |
| newColor | [Color](../../com.aspose.psd/color) | Ny färg att ersätta den gamla färgen med. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldColorArgb | int | ARGB‑värde för den gamla färgen som ska ersättas. |
| oldColorDiff | byte | Tillåten skillnad i den gamla färgen för att kunna bredda den ersatta färgtonen. |
| newColorArgb | int | ARGB‑värde för den nya färgen som ersätter den gamla färgen. |

### replaceFontWithDefault_internalized(Font font, String defaultFontName) {#replaceFontWithDefault-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static Font replaceFontWithDefault_internalized(Font font, String defaultFontName)
```


Ersätter teckensnittet med standard.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | Teckensnittet. |
| defaultFontName | java.lang.String | Standardnamn för teckensnittet. |

**Returns:**
[Font](../../com.aspose.psd/font) - New font
### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Ersätter alla icke‑transparenta färger med den nya färgen och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Obs: om du använder den på bilder utan transparens kommer alla färger att ersättas med en enda.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | Ny färg att ersätta icke‑transparenta färger med. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Ersätter alla icke‑transparenta färger med den nya färgen och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Obs: om du använder den på bilder utan transparens kommer alla färger att ersättas med en enda.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorArgb | int | ARGB‑värde för den nya färgen som ersätter icke‑transparenta färger. |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Ändrar bildens storlek. Standardvärdet ResizeType.LeftTopToLeftTop används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändrar storlek på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Inställningarna för storleksändring. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ändrar bildens storlek. Standardvärdet ResizeType.LeftTopToLeftTop används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändringstransformation  ResizeType |

### resizeChannelsData_internalized(Rectangle rect) {#resizeChannelsData-internalized-com.aspose.psd.Rectangle-}
```
public void resizeChannelsData_internalized(Rectangle rect)
```


Ändrar storlek på kanalernas data

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Ändrar höjden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Ändrar höjden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Inställningarna för bildstorleksändring. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Ändrar höjden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typ av skalning. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Ändrar bredden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Ändrar bredden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Inställningarna för bildstorleksändring. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ändrar bredden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| resizeType | int | Typ av skalning. |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


Skalar om lagret med den angivna inversa skalan. (ny bredd = gammal bredd / skala; ny höjd = gammal höjd / skala)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleX | double | Skala X. |
| scaleY | double | Skala Y. |
| resizeType | int | Typ av skalning. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Rotera bilden runt centrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Rotera bilden runt centrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resizeProportionally | boolean | om den är inställd på true kommer bildens storlek att ändras enligt roterad rektangel (hörnpunkter) projektioner, annars lämnas dimensionerna orörda och endast bildens innehåll roteras. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Färgen på bakgrunden. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Roterar, vänder eller roterar och vänder bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


Sparar bilddata till den underliggande strömmen.

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Sparar objektets data till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Strömmen att spara objektets data till. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Strömmen att spara bildens data till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Sparalternativen. |

### save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dstStream | java.io.OutputStream | Strömmen att spara bildens data till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Sparalternativen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Målbildernas avgränsningsrektangel. Ställ in den tomma rektangeln för att använda källans avgränsningar. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Sparar objektets data till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Strömmen att spara objektets data till. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att spara bildens data till. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Alternativen. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att spara bildens data till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Sparalternativen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Målbildernas avgränsningsrektangel. Ställ in den tomma rektangeln för att använda källans avgränsningar. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Sparar objektets data till den angivna filplatsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att spara objektets data till. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Sparar objektets data till den angivna filplatsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att spara objektets data till. |
| overWrite | boolean | Om den är satt till  true  skrivs filens innehåll över, annars kommer data att läggas till. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Alternativen. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Alternativen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Målbildernas avgränsningsrektangel. Ställ in den tomma rektangeln för att använda källans avgränsningar. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Sparar de 32‑bitars ARGB‑pixlarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln att spara pixlar till. |
| pixlar | int[] | 32-bitars ARGB-pixelarrayen. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Sparar pixlarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln att spara pixlar till. |
| pixlar | int[] | CMYK-pixlarna presenterade som 32-bitars heltalsvärden. |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Sparar pixlarna. Denna metod är föråldrad. Använd den mer effektiva metoden  saveCmyk32Pixels(Rectangle, int[])  istället.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln att spara pixlar till. |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK-pixelarrayen. |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Sparar pixlarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln att spara pixlar till. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Pixelarrayen. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Sparar rådata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Rådata. |
| dataOffset | int | Det startande rådataoffsetet. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rådatarektangeln. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Rådatainställningarna som datan är i. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Strömmen att spara bildens data till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Sparalternativen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Destinationens bildgränsrektangel. Ställ in den tomma rektangeln för att använda källgränserna. |

### save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth) {#save-internalized-com.aspose.psd.StreamContainer-int-int-}
```
public final void save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)
```


Sparar data till den angivna strömbehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
| psdVersion | int | PSD-versionen. |
| bitDepth | int | Bitdjupet. |

### setAbsoluteBounds_internalized(Rectangle value) {#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setAbsoluteBounds_internalized(Rectangle value)
```


Hämtar eller anger de absoluta gränserna.

Värde: De absoluta gränserna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setAllowWarpRepaint_internalized(boolean value) {#setAllowWarpRepaint-internalized-boolean-}
```
public final void setAllowWarpRepaint_internalized(boolean value)
```


Den hämtar eller anger render warp eller använder PS-bild

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Ställer in en bilds 32-bitars ARGB-pixel för den angivna positionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Pixelns x‑position. |
| y | int | Pixelns y‑position. |
| argb32Color | int | Den 32-bitars ARGB-pixeln för den angivna positionen. |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Ställer in ett värde som indikerar om paletten ska justeras automatiskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true om automatisk justering av palett är aktiverad; annars false. |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Hämtar eller anger ett värde för bakgrundsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBlendClippedElements(boolean value) {#setBlendClippedElements-boolean-}
```
public final void setBlendClippedElements(boolean value)
```


Hämtar eller anger blandningen av det beskurna elementet.

Värde: Blandning av klippt element.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setBlendModeKey(long value) {#setBlendModeKey-long-}
```
public void setBlendModeKey(long value)
```


Hämtar eller anger nyckeln för blandningsläget.

Värde: Nyckeln för blandningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Hämtar eller anger positionen för det nedre lagret.

Värde: Positionen för det nedre lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Ställer in en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Tips om buffertstorlek, i megabyte. Icke‑positivt värde betyder ingen minnesbegränsning för interna buffertar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Buffertstorleksindikationen som definierar maximal tillåten storlek för alla interna buffertar. |

### setChannelInformation(ChannelInformation[] value) {#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public final void setChannelInformation(ChannelInformation[] value)
```


Hämtar eller anger kanalinformationen.

Värde: Kanalinformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) |  |

### setClipping(byte value) {#setClipping-byte-}
```
public final void setClipping(byte value)
```


Hämtar eller anger lagerklippning. 0 = bas, 1 = icke‑bas.

Värde: Lagerklippning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Ställer in Image-behållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Bildbehållaren. |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


Ställer in dataläsaren direkt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | Data‑laddaren. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Ställer in objektets datastream.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Objektets datastream. |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Hämtar eller anger visningsnamnet för lagret.

Värde: Visningsnamnet för lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFillOpacity(int value) {#setFillOpacity-int-}
```
public final void setFillOpacity(int value)
```


Hämtar fyllnadens opacitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setFiller(byte value) {#setFiller-byte-}
```
public final void setFiller(byte value)
```


Hämtar eller anger lagrets fyllnad.

Värde: Lagrets fyllare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Hämtar eller anger lagerflaggorna. bit 0 = transparensskyddad; bit 1 = synlig; bit 2 = föråldrad; bit 3 = 1 för Photoshop 5.0 och senare, anger om bit 4 har användbar information; bit 4 = pixeldata irrelevant för dokumentets utseende.

Värde: Lagerflaggorna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


Ställer in paletten på format-specifika platser

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Ny 32-bitars ARGB-palett. |

**Returns:**
boolean
### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Hämtar eller anger rubriken.

Värde: Headern.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för detta RasterImage.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Den horisontella upplösningen. |

Obs! Som standard är detta värde alltid 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Ställer in ett värde som indikerar om [ignore after save].

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true om [ignore after save]; annars false. |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta bildobjekt har ändrats efter inläsning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true om detta objekt har ändrat bilden; annars false. |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


Ställer in den inre datatransformern.

Värde: Den inre datatransformern.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.IInnerDataTransformer | den inre datatransformern. |

### setInnerText(String value) {#setInnerText-java.lang.String-}
```
public final void setInnerText(String value)
```


Hämtar lagrets text

Värde: Texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Ställer in avbrottsmotorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | avbrottsövervakaren. |

### setLayerBlendingRangesData(LayerBlendingRangesData value) {#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-}
```
public final void setLayerBlendingRangesData(LayerBlendingRangesData value)
```


Hämtar eller anger data för lagerblandningsintervall.

Värde: Lagerblandningsområdens data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata) |  |

### setLayerCreationDateTime(Date value) {#setLayerCreationDateTime-java.util.Date-}
```
public final void setLayerCreationDateTime(Date value)
```


Hämtar eller anger lagerns skapelsedatum och -tid.

Värde: Lagrets skapelsedatum och tid. Om det inte finns någon data om skapelsedatumet returneras Unix-tidens första epok.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### setLayerCreationDateTime_internalized(System.DateTime value) {#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-}
```
public final void setLayerCreationDateTime_internalized(System.DateTime value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.ms.System.DateTime |  |

### setLayerLock(int value) {#setLayerLock-int-}
```
public final void setLayerLock(int value)
```


Hämtar eller anger lagerlås (Obs! Om flaggan LayerFlags.TransparencyProtected är satt kommer den att skrivas över av lagerlås‑flaggan. För att återge LayerFlags.TransparencyProtected‑flaggan måste du tillämpa lageralternativet layer.Flags |= LayerFlags.TransparencyProtected

Värde: Lagerlåset.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setLayerMaskData(LayerMaskData value) {#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void setLayerMaskData(LayerMaskData value)
```


Hämtar eller anger data för lagermasken.

Värde: Lagermaskens data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) |  |

### setLayerPalette_internalized(IColorPalette value) {#setLayerPalette-internalized-com.aspose.psd.IColorPalette-}
```
public final void setLayerPalette_internalized(IColorPalette value)
```


Hämtar eller anger lagerpaletten.

Värde: Lagerpaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Hämtar eller anger lagrets vänstra position.

Värde: Vänstra lagerpositionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


Hämtar eller anger maximal tillåten allokering för partiell roterings‑sparning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Den maximalt tillåtna allokeringen för partiell roteringssparning. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Ställer in minneshanteraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | Minneshanteraren. |
| needDispose | boolean | om den är inställd på  true  [need dispose]. |

### setName(String name) {#setName-java.lang.String-}
```
public final void setName(String name)
```


Ställer in lagrets namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Lagrets namn. |

### setName_internalized(String value) {#setName-internalized-java.lang.String-}
```
public final void setName_internalized(String value)
```


Hämtar eller anger lagrets namn.

Värde: Lagernamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Hämtar eller anger lageropaciteten. 0 = transparent, 255 = ogenomskinlig.

Värde: Lageropaciteten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Färgpaletten. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Ställer in bildpaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Paletten att ställa in. |
| updateColors | boolean | om den är inställd på  true  uppdateras färgerna enligt den nya paletten; annars förblir färgindex oförändrade. Observera att oförändrade index kan få bilden att krascha vid inläsning om vissa index saknar motsvarande palettposter. |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


Ställer in en bildpixel för den angivna positionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Pixelns x‑position. |
| y | int | Pixelns y‑position. |
| color | [Color](../../com.aspose.psd/color) | Pixelns färg för den angivna positionen. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Hämtar eller anger ett värde som indikerar om bildkomponenterna måste vara förmultiplicerade.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true  om bildkomponenterna måste vara förmultiplicerade; annars,  false . |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Hämtar eller anger den anpassade färgkonverteraren

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | Den anpassade färgkonverteraren |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Hämtar eller anger reservindexen att använda när palettindexet är utanför gränserna

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Reservindexet att använda när palettindexet är utanför gränserna |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Hämtar eller anger den indexerade färgkonverteraren

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | Den indexerade färgkonverteraren |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Ställer in upplösningen för detta RasterImage.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dpiX | double | Den horisontella upplösningen, i punkter per tum, för  RasterImage . |
| dpiY | double | Den vertikala upplösningen, i punkter per tum, för  RasterImage . |

### setResourceProcessor_internalized(TypeToolResourceProcessor value) {#setResourceProcessor-internalized-com.aspose.internal.fileformats.psd.layers.TypeToolResourceProcessor-}
```
public final void setResourceProcessor_internalized(TypeToolResourceProcessor value)
```


Hämtar eller anger resursprocessorn.

Värde: Resursprocessorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.fileformats.psd.layers.TypeToolResourceProcessor |  |

### setResources(LayerResource[] value) {#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setResources(LayerResource[] value)
```


Hämtar eller anger lagerresurserna.

Värde: Lagerresurserna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Hämtar eller anger den högra lagerpositionen.

Värde: Den högra lagerpositionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Hämtar eller anger roteringsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Rotationsläget. |

### setSheetColorHighlight(short value) {#setSheetColorHighlight-short-}
```
public final void setSheetColorHighlight(short value)
```


Hämtar eller anger den dekorativa bladfärgens markering i lagerlistan

Värde: Markering av bladfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setTextBoundBox(RectangleF value) {#setTextBoundBox-com.aspose.psd.RectangleF-}
```
public final void setTextBoundBox(RectangleF value)
```


Hämtar eller anger textens avgränsningsruta.

Värde: Textens begränsningsruta.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Hämtar eller anger den övre lagerpositionen.

Värde: Den övre lagerpositionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


Hämtar eller anger transformationsmatrisen

Värde: Transformationsmatrisen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Hämtar ett värde som indikerar om bilden har transparent färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


Hämtar bildens transparenta färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Hämtar eller anger ett värde som indikerar om XMP‑metadata ska uppdateras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true  om XMP-metadata uppdateras; annars,  false . |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true  om rådatainläsning används när rådatainläsning är tillgänglig.; annars,  false . |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Alla Aspose-produkter bör implementera denna metod. Den kallas av en GroupDocs-produkt för att indikera om GroupDocs själv är licensierad eller inte och ange ett anpassat vattenmärke. När GroupDocs är licensierat ska detta dokumentinstans också bete sig som licensierat även om Aspose-produkten inte är licensierad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ventureLicense | java.lang.Object | license |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna RasterImage.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Den vertikala upplösningen. |

Obs! Som standard är detta värde alltid 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop. |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Hämtar eller anger ett värde som indikerar om lagret är synligt

Värde:  true  om detta objekt är synligt; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setWarpSettings(WarpSettings value) {#setWarpSettings-com.aspose.psd.fileformats.psd.layers.warp.structs.WarpSettings-}
```
public final void setWarpSettings(WarpSettings value)
```


Den hämtar eller anger Warp-parametrar som sattes eller hämtades från resursen (standard)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) |  |

### setWasChanged_internalized(boolean value) {#setWasChanged-internalized-boolean-}
```
public final void setWasChanged_internalized(boolean value)
```


Hämtar eller anger ett värde som indikerar om [was changed].

Värde:  true  om [was changed]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Hämtar eller anger XMP-metadata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP-metadata. |

### shallowCopy() {#shallowCopy--}
```
public final Layer shallowCopy()
```


Skapar en ytlig kopia av det aktuella lagret. Vänligen   för förklaring.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - A shallow copy of the current Layer.
### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Konverterar rasterbild till bitmap.

**Returns:**
java.awt.image.BufferedImage - Bitmappen
### toBitmap_internalized() {#toBitmap-internalized--}
```
public System.Drawing.Bitmap toBitmap_internalized()
```




**Returns:**
com.aspose.ms.System.Drawing.Bitmap
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateBlendingOptions_internalized(PattResource pattResource) {#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateBlendingOptions_internalized(PattResource pattResource)
```


Uppdaterar blandningsalternativen efter att lager‑ eller globala resurser har ändrats.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) |  |

### updateBounds_internalized(RectangleF absoluteTextBounds, RectangleF inBoxTextBounds) {#updateBounds-internalized-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public final void updateBounds_internalized(RectangleF absoluteTextBounds, RectangleF inBoxTextBounds)
```


Uppdaterar gränserna för [TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) i resurserna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteTextBounds | [RectangleF](../../com.aspose.psd/rectanglef) | Den absoluta positionen och storleken på texten. |
| inBoxTextBounds | [RectangleF](../../com.aspose.psd/rectanglef) | Positionen och storleken på texten relativt till textBoxen. |

### updateText(String text) {#updateText-java.lang.String-}
```
public final void updateText(String text)
```


Uppdaterar texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Textvärdet. |

### updateText(String text, Color color) {#updateText-java.lang.String-com.aspose.psd.Color-}
```
public final void updateText(String text, Color color)
```


Uppdaterar texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Textvärdet. |
| color | [Color](../../com.aspose.psd/color) | Färgvärdet. |

### updateText(String text, Point leftTopCoordinate) {#updateText-java.lang.String-com.aspose.psd.Point-}
```
public final void updateText(String text, Point leftTopCoordinate)
```


Uppdaterar texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Textvärdet. |
| leftTopCoordinate | [Point](../../com.aspose.psd/point) | Den övre vänstra koordinaten. |

### updateText(String text, Point leftTopCoordinate, Color color) {#updateText-java.lang.String-com.aspose.psd.Point-com.aspose.psd.Color-}
```
public final void updateText(String text, Point leftTopCoordinate, Color color)
```


Uppdaterar texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Textvärdet. |
| leftTopCoordinate | [Point](../../com.aspose.psd/point) | Den övre vänstra koordinaten. |
| color | [Color](../../com.aspose.psd/color) | Färgvärdet. |

### updateText(String text, Point leftTopCoordinate, float fontSize) {#updateText-java.lang.String-com.aspose.psd.Point-float-}
```
public final void updateText(String text, Point leftTopCoordinate, float fontSize)
```


Uppdaterar texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Textvärdet. |
| leftTopCoordinate | [Point](../../com.aspose.psd/point) | Den övre vänstra koordinaten. |
| fontSize | float | Storlek på typsnittet. |

### updateText(String text, Point leftTopCoordinate, float fontSize, Color color) {#updateText-java.lang.String-com.aspose.psd.Point-float-com.aspose.psd.Color-}
```
public final void updateText(String text, Point leftTopCoordinate, float fontSize, Color color)
```


Uppdaterar texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Textvärdet. |
| leftTopCoordinate | [Point](../../com.aspose.psd/point) | Den övre vänstra koordinaten. |
| fontSize | float | Storlek på typsnittet. |
| color | [Color](../../com.aspose.psd/color) | Färgvärdet. |

### updateText(String text, float fontSize) {#updateText-java.lang.String-float-}
```
public final void updateText(String text, float fontSize)
```


Uppdaterar texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Textvärdet. |
| fontSize | float | Storlek på typsnittet. |

### updateText(String text, float fontSize, Color color) {#updateText-java.lang.String-float-com.aspose.psd.Color-}
```
public final void updateText(String text, float fontSize, Color color)
```


Uppdaterar texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Textvärdet. |
| fontSize | float | Storlek på typsnittet. |
| color | [Color](../../com.aspose.psd/color) | Färgvärdet. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Skriver hela skanningsraden till det angivna skanningsradindexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scanLineIndex | int | Nollbaserat index för skanningslinjen. |
| argb32Pixels | int[] | 32-bit ARGB-färgarray att skriva. |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Skriver hela skanningsraden till det angivna skanningsradindexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scanLineIndex | int | Nollbaserat index för skanningslinjen. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Pixel-färgarray att skriva. |

