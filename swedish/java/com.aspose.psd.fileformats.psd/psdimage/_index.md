---
title: "PsdImage"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar PsdImage-klassen som ger möjlighet att läsa in, redigera och spara PSD-filer samt uppdatera egenskaper, lägga till vattenstämplar, utföra grafikoperationer eller konvertera ett filformat till ett annat."
type: docs
weight: 14
url: /sv/java/com.aspose.psd.fileformats.psd/psdimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage)
```
public final class PsdImage extends RasterCachedImage
```

Definierar PsdImage-klassen som ger möjlighet att läsa in, redigera och spara PSD-filer samt uppdatera egenskaper, lägga till vattenstämplar, utföra grafikoperationer eller konvertera ett filformat till ett annat. Aspose.PSD stöder import som ett lager och export till följande format: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb samt export till Pdf med markerbar text.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PsdImage(String path)](#PsdImage-java.lang.String-) | Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) från angiven sökväg från rasterbild (inte psd-bild i sökvägen). |
| [PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.lang.String-short-short-short-int-short-) | Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) från angiven sökväg från rasterbild (inte psd-bild i sökvägen) med konstruktörsparametrar. |
| [PsdImage(InputStream stream)](#PsdImage-java.io.InputStream-) | Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) från angiven sökväg från rasterbild (inte psd-bild i ström). |
| [PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.io.InputStream-short-short-short-int-short-) | Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) från angiven sökväg från rasterbild (inte psd-bild i ström) med konstruktörsparametrar. |
| [PsdImage(RasterImage rasterImage)](#PsdImage-com.aspose.psd.RasterImage-) | Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) från befintlig rasterbild (inte psd-bild) med RGB-färgläge, 4 kanaler, 8 bitar/kanal och utan komprimering. |
| [PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-) | Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) från befintlig rasterbild (inte psd-bild) med konstruktörsparametrar. |
| [PsdImage(int width, int height)](#PsdImage-int-int-) | Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) med angiven bredd och höjd. |
| [PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-) | Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) med angiven bredd, höjd, palett, färgläge, antal kanaler och kanalernas bitlängd samt angivna komprimeringslägesparametrar. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DefaultStubEncodingName_internalized](#DefaultStubEncodingName-internalized) | Standardkodningsnamnet |
| [DefaultVersion](#DefaultVersion) | Standard‑PSD‑versionen. |
| [OnCreate_internalized](#OnCreate-internalized) | Uppstår när bilden har laddats |
| [OnLoad_internalized](#OnLoad-internalized) | Uppstår när bilden har laddats av createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Uppstår när bilden har laddats eller sparats |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Uppstår när kredit har använts |
| [SyncLayersRoot_internalized](#SyncLayersRoot-internalized) | Objektet som kan användas för att synkronisera åtkomst till lagren. |
| [horizontalResolution](#horizontalResolution) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addBlackWhiteAdjustmentLayer()](#addBlackWhiteAdjustmentLayer--) | Lägger till justeringslagret svart‑vit. |
| [addBrightnessContrastAdjustmentLayer(int brightness, int contrast)](#addBrightnessContrastAdjustmentLayer-int-int-) | Lägger till justeringslagret för ljusstyrka/kontrast. |
| [addChannelMixerAdjustmentLayer()](#addChannelMixerAdjustmentLayer--) | Lägger till justeringslagret kanalblandare med standardparametrar |
| [addColorBalanceAdjustmentLayer()](#addColorBalanceAdjustmentLayer--) | Lägger till justeringslagret färgbalans. |
| [addCurvesAdjustmentLayer()](#addCurvesAdjustmentLayer--) | Lägger till justeringslagret Kurvor. |
| [addExposureAdjustmentLayer()](#addExposureAdjustmentLayer--) |  |
| [addExposureAdjustmentLayer(float exposure)](#addExposureAdjustmentLayer-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset)](#addExposureAdjustmentLayer-float-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)](#addExposureAdjustmentLayer-float-float-float-) | Lägger till justeringslagret exponering. |
| [addGradientMapAdjustmentLayer()](#addGradientMapAdjustmentLayer--) | Lägger till GradientMap Adjustment layer. |
| [addHueSaturationAdjustmentLayer()](#addHueSaturationAdjustmentLayer--) | Lägger till nyans/mättnad-justeringslagret. |
| [addInvertAdjustmentLayer()](#addInvertAdjustmentLayer--) | Lägger till ett inverteringsjusteringslager. |
| [addLayer(Layer layer)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Lägger till lagret. |
| [addLayerGroup(String groupName, int index, boolean startBehaviour)](#addLayerGroup-java.lang.String-int-boolean-) | Lägger till lagergruppen. |
| [addLayer_internalized(Layer layer, int index)](#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-) | Lägger till lagret på indexet. |
| [addLevelsAdjustmentLayer()](#addLevelsAdjustmentLayer--) | Lägger till Levels-justeringslagret. |
| [addPhotoFilterLayer(Color color)](#addPhotoFilterLayer-com.aspose.psd.Color-) | Lägger till fotofilterlagret. |
| [addPosterizeAdjustmentLayer()](#addPosterizeAdjustmentLayer--) | Lägger till Posterize Adjustment layer. |
| [addRegularLayer()](#addRegularLayer--) | Lägger till ett nytt vanligt lager. |
| [addSelectiveColorAdjustmentLayer()](#addSelectiveColorAdjustmentLayer--) | Lägger till selektiv färgjusteringslagret. |
| [addShapeLayer()](#addShapeLayer--) | Lägg till tomt Shape-lager. |
| [addTextLayer(String text, Rectangle rect)](#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-) | Lägger till ett nytt Text-lager. |
| [addThresholdAdjustmentLayer()](#addThresholdAdjustmentLayer--) | Lägger till Threshold-justeringslagret. |
| [addVibranceAdjustmentLayer()](#addVibranceAdjustmentLayer--) | Lägger till Vibrance-justeringslagret. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Justering av ljusstyrka för bild. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Bildkontrast |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gamma-korrigering av en bild. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma-korrigering av en bild. |
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
| [convert(PsdOptions newOptions)](#convert-com.aspose.psd.imageoptions.PsdOptions-) | Konverterar detta bildformat till det som anges i alternativ. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Konverterar till aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Skapar en ny bild med de angivna create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Skapar en ny bild med de angivna bilderna som sidor |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Skapar en ny bild med de angivna bilderna som sidor. |
| [createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-) | Skapar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-) |  |
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filtrerar den angivna rektangeln. |
| [flattenImage()](#flattenImage--) | Plattar till alla lager. |
| [getActiveLayer()](#getActiveLayer--) | Hämtar eller anger det aktiva lagret. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Hämtar en bildpixel i 32-bit ARGB. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Hämtar ett värde som indikerar om paletten justeras automatiskt. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar eller anger ett värde för bakgrundsfärgen. |
| [getBackgroundContents_internalized()](#getBackgroundContents-internalized--) | Hämtar eller anger bakgrundens färg. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Hämtar bitarna per kanal. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [getBounds()](#getBounds--) | Hämtar bildens gränser. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Hämtar en ledtråd för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [getChannelsCount()](#getChannelsCount--) | Hämtar antalet PSD-kanaler. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Hämtar eller anger CMYK-färgprofilen för CMYK PSD-bilder. |
| [getColorMode()](#getColorMode--) | Hämtar eller anger färgläget. |
| [getCompression()](#getCompression--) | Hämtar komprimeringsmetoden. |
| [getContainer()](#getContainer--) | Hämtar  Image  behållaren. |
| [getCurrentOptions_internalized()](#getCurrentOptions-internalized--) | Hämtar de aktuella bildalternativen. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Hämtar objektets datastream. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Hämtar den djupt justerade paletten. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Hämtar standard 32-bit ARGB-pixelarrayen. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Hämtar standardalternativen. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Hämtar standardpixelarrayen med partiell pixel‑läsare. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Hämtar standardrådataarrayen med partiell pixel‑läsare. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Hämtar standardrådataarrayen. |
| [getDefaultReplacementFont_internalized()](#getDefaultReplacementFont-internalized--) | Hämtar eller anger standardteckensnittet för ersättning. |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getFileFormat()](#getFileFormat--) | Hämtar ett värde för filformat |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Hämtar filformatet. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Hämtar filformatet. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Hämtar filformatet. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Hämtar rektangeln som passar den aktuella bilden. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Hämtar rektangeln som passar den aktuella bilden. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Hämtar palett från format‑specifika platser |
| [getGlobalAngle()](#getGlobalAngle--) | Hämtar eller anger den globala vinkeln. |
| [getGlobalLayerMaskInfo()](#getGlobalLayerMaskInfo--) | Hämtar den globala lagermaskinformationen. |
| [getGlobalLayerResources()](#getGlobalLayerResources--) | Hämtar eller anger de globala lagerresurserna. |
| [getGrayColorProfile()](#getGrayColorProfile--) | Hämtar eller anger GRAY (monokrom) färgprofilen för gråskaliga PSD-bilder. |
| [getHeight()](#getHeight--) | Hämtar bildens höjd. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för denna [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getImageLayers_internalized()](#getImageLayers-internalized--) | Hämtar eller anger PSD-lagren. |
| [getImageOpacity()](#getImageOpacity--) | Hämtar opaciteten för denna bild. |
| [getImageResources()](#getImageResources--) | Hämtar eller anger PSD-bildresurserna. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Hämtar den interna datatransformern. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Hämtar avbrotts­övervakaren. |
| [getLayerAndMask_internalized()](#getLayerAndMask-internalized--) | Hämtar lagret och masken. |
| [getLayers()](#getLayers--) | Hämtar eller anger PSD-lagren. |
| [getLinkedLayersManager()](#getLinkedLayersManager--) | Hämtar hanteraren för länkade lager. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Hämtar eller anger maximal tillåten allokering för partiell roterings‑sparning. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Hämtar minneshanteraren. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Hämtar datum och tid då resursbilden senast ändrades. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
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
| [getPsdHeader_internalized()](#getPsdHeader-internalized--) | Hämtar eller anger PSD-huvudet. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Hämtar eller anger den anpassade färgkonverteraren |
| [getRawDataFormat()](#getRawDataFormat--) | Hämtar det råa dataformatet. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Hämtar eller anger reservindexen att använda när palettindexet är utanför gränserna |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Hämtar eller anger den indexerade färgkonverteraren |
| [getRawLineSize()](#getRawLineSize--) | Hämtar den råa radstorleken i byte. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Hämtar eller anger RGB-färgprofilen för CMYK PSD-bilder. |
| [getRotateMode()](#getRotateMode--) | Hämtar eller anger roteringsläget. |
| [getSize()](#getSize--) | Hämtar bildens storlek. |
| [getSkewAngle()](#getSkewAngle--) | Hämtar snedvinkeln. |
| [getSmartObjectProvider()](#getSmartObjectProvider--) | Hämtar leverantören för smarta objekt. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Hämtar filsökvägen till källbilden om den finns. |
| [getSyncExclusiveOperation_internalized()](#getSyncExclusiveOperation-internalized--) |  |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Hämtar synkroniseringsroten. |
| [getTimeline()](#getTimeline--) | Hämtar tidslinjen ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) för denna [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getTransparentColor()](#getTransparentColor--) | Hämtar bildens transparenta färg. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Hämtar eller anger ett värde som indikerar om XMP‑metadata ska uppdateras. |
| [getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)](#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-) | Hämtar uppdaterade resurser med ett helt nytt resursblock. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Hämtar ett värde som indikerar om objektet använder minnesoptimeringsstrategi |
| [getUseRawData()](#getUseRawData--) | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Hämtar den använda paletten. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Hämtar venture-licensen. |
| [getVersion()](#getVersion--) | Hämtar eller anger versionen. |
| [getVerticalResolution()](#getVerticalResolution--) | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getWidth()](#getWidth--) | Hämtar bildens bredd. |
| [getXmpData()](#getXmpData--) | Hämtar eller anger XMP-metadata. |
| [grayscale()](#grayscale--) | Transformation av en bild till dess gråskalerepresentation |
| [hasAlpha()](#hasAlpha--) | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna RasterImage. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Hämtar ett värde som indikerar om bilden har bakgrundsfärg. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Hämtar eller anger ett värde som indikerar om detta bildobjekt har ändrats efter inläsning. |
| [hasTransparencyData()](#hasTransparencyData--) | Hämtar eller anger ett värde som indikerar om den första alfakanalen innehåller transparensdata för det sammanslagna resultatet när lagringsdata specificeras. |
| [hasTransparentColor()](#hasTransparentColor--) | Hämtar ett värde som indikerar om bilden har transparent färg. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Hämtar eller anger det maximala värdet för framsteg |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Anger framstegen. |
| [insertLayerAfter_internalized(Layer layer, Layer layerToInsert)](#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Infogar lagret efter det angivna lagret med alla förberedelser. |
| [isCached()](#isCached--) | Hämtar ett värde som indikerar om bilddata för närvarande är cachad. |
| [isFlatten()](#isFlatten--) | Hämtar ett värde som indikerar om PSD-bilden är platt. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Hämtar ett värde som indikerar om rådatainläsning är tillgänglig. |
| [isUsePalette()](#isUsePalette--) | Hämtar ett värde som indikerar om bildpaletten används. |
| [isUsePhotoshopCompatibilityMode_internalized()](#isUsePhotoshopCompatibilityMode-internalized--) |  |
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
| [mergeLayers(Layer bottomLayer, Layer topLayer)](#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Slår ihop lagren. |
| [normalizeAngle()](#normalizeAngle--) | Normaliserar vinkeln. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normaliserar vinkeln. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Anropas när behållaren för denna [Image](../../com.aspose.psd/image) har satts. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [removeGlobalTextEngineResource_internalized()](#removeGlobalTextEngineResource-internalized--) | Tar bort den globala textmotormaterialet – Metoden används för vissa textlagrade PSD-filer som inte kan öppnas i Adobe Photoshop efter bearbetning (i huvudsak för textlager relaterade till saknade typsnitt). |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Ändrar storlek på bilden. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Ändrar storlek på bilden. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändrar storlek på bilden. |
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
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Sparar objektets data till den angivna strömmen. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
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
| [saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)](#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---) | Sparar bilddata till den angivna strömmen med de angivna sparalternativen och gränserna. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [setActiveLayer(Layer value)](#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Hämtar eller anger det aktiva lagret. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Ställer in en bilds 32-bitars ARGB-pixel för den angivna positionen. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Ställer in ett värde som indikerar om paletten ska justeras automatiskt. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Hämtar eller anger ett värde för bakgrundsfärgen. |
| [setBackgroundContents_internalized(RawColor value)](#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Hämtar eller anger bakgrundens färg. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ställer in en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Hämtar eller anger CMYK-färgprofilen för CMYK PSD-bilder. |
| [setColorMode(short value)](#setColorMode-short-) | Hämtar eller anger färgläget. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Ställer in Image-behållaren. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Ställer in dataläsaren direkt. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Ställer in objektets datastream. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Ställer in paletten på format-specifika platser |
| [setGlobalAngle(int value)](#setGlobalAngle-int-) | Den globala vinkeln. |
| [setGlobalLayerResources(LayerResource[] value)](#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Hämtar eller anger de globala lagerresurserna. |
| [setGrayColorProfile(StreamSource value)](#setGrayColorProfile-com.aspose.psd.sources.StreamSource-) | GRAY (monokrom) färgprofilen för gråskaliga PSD-bilder. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för denna [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Ställer in ett värde som indikerar om [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Hämtar eller anger ett värde som indikerar om detta bildobjekt har ändrats efter inläsning. |
| [setImageResources(ResourceBlock[] value)](#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Hämtar eller anger PSD-bildresurserna. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Ställer in den inre datatransformern. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Ställer in avbrottsmotorn. |
| [setLayers(Layer[] value)](#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | Hämtar eller anger PSD-lagren. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Hämtar eller anger maximal tillåten allokering för partiell roterings‑sparning. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Ställer in minneshanteraren. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ställer in färgpaletten. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Ställer in bildpaletten. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Ställer in en bildpixel för den angivna positionen. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Hämtar eller anger ett värde som indikerar om bildkomponenterna måste vara förmultiplicerade. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Hämtar eller anger den anpassade färgkonverteraren |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Hämtar eller anger reservindexen att använda när palettindexet är utanför gränserna |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Hämtar eller anger den indexerade färgkonverteraren |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Anger upplösningen för denna [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Hämtar eller anger RGB-färgprofilen för CMYK PSD-bilder. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Hämtar eller anger roteringsläget. |
| [setTransparencyData(boolean value)](#setTransparencyData-boolean-) | Hämtar eller anger ett värde som indikerar om den första alfakanalen innehåller transparensdata för det sammanslagna resultatet när lagringsdata specificeras. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Hämtar ett värde som indikerar om bilden har transparent färg. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Hämtar bildens transparenta färg. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Hämtar eller anger ett värde som indikerar om XMP‑metadata ska uppdateras. |
| [setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)](#setUsePhotoshopCompatibilityMode-internalized-boolean-) |  |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Ställer in venture-licensen. |
| [setVersion(int value)](#setVersion-int-) | Hämtar eller anger versionen. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Hämtar eller anger XMP-metadata. |
| [toBitmap()](#toBitmap--) | Konverterar rasterbild till bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Skriver hela skanningsraden till det angivna skanningsradindexet. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Skriver hela skanningsraden till det angivna skanningsradindexet. |
### PsdImage(String path) {#PsdImage-java.lang.String-}
```
public PsdImage(String path)
```


Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) från angiven sökväg för rasterbild (inte psd-bild i sökvägen). Används för att initiera psd-bild med standardparametrar - Färgläge - rgb, 4 kanaler, 8 bitar per kanal, Komprimering - Raw.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen för att läsa in pixel- och palettdata från och initiera med. |

### PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.lang.String-short-short-short-int-short-}
```
public PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) från angiven sökväg från rasterbild (inte psd-bild i sökvägen) med konstruktörsparametrar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen för att läsa in pixel- och palettdata från och initiera med. |
| colorMode | short | Färgläget. |
| channelBitDepth | short | PSD-bitdjupet per kanal. |
| channels | short | Antalet PSD-kanaler. |
| psdVersion | int | PSD-versionen. |
| compression | short | Komprimeringen att använda. |

### PsdImage(InputStream stream) {#PsdImage-java.io.InputStream-}
```
public PsdImage(InputStream stream)
```


Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) från angiven sökväg för rasterbild (inte psd-bild i ström). Används för att initiera psd-bild med standardparametrar - Färgläge - rgb, 4 kanaler, 8 bitar per kanal, Komprimering - Raw.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Strömmen för att läsa in pixel- och palettdata från och initiera med. |

### PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.io.InputStream-short-short-short-int-short-}
```
public PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) från angiven sökväg från rasterbild (inte psd-bild i ström) med konstruktörsparametrar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Strömmen för att läsa in pixel- och palettdata från och initiera med. |
| colorMode | short | Färgläget. |
| channelBitDepth | short | PSD-bitdjupet per kanal. |
| channels | short | Antalet PSD-kanaler. |
| psdVersion | int | PSD-versionen. |
| compression | short | Komprimeringen att använda. |

### PsdImage(RasterImage rasterImage) {#PsdImage-com.aspose.psd.RasterImage-}
```
public PsdImage(RasterImage rasterImage)
```


Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) från befintlig rasterbild (inte psd-bild) med RGB-färgläge, 4 kanaler, 8 bitar/kanal och utan komprimering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Bilden för att läsa in pixel- och palettdata från och initiera med. |

### PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-}
```
public PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) från befintlig rasterbild (inte psd-bild) med konstruktörsparametrar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Bilden för att läsa in pixel- och palettdata från och initiera med. |
| colorMode | short | Färgläget. |
| channelBitDepth | short | PSD-bitdjupet per kanal. |
| channels | short | Antalet PSD-kanaler. |
| psdVersion | int | PSD-versionen. |
| compression | short | Komprimeringen att använda. |

### PsdImage(int width, int height) {#PsdImage-int-int-}
```
public PsdImage(int width, int height)
```


Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) med angiven bredd och höjd. Används för att initiera en tom psd-bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bildens bredd. |
| höjd | int | Bildens höjd. |

### PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-}
```
public PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initierar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) med angiven bredd, höjd, paletter, färgläge, kanalantal och kanalernas bitlängd samt angivna komprimeringslägesparametrar. Används för att initiera en tom psd-bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bildens bredd. |
| höjd | int | Bildens höjd. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Färgpaletten. |
| colorMode | short | Färgläget. |
| channelBitDepth | short | PSD-bitdjupet per kanal. |
| channels | short | Antalet PSD-kanaler. |
| psdVersion | int | PSD-versionen. |
| compression | short | Komprimeringen att använda. |

### DefaultStubEncodingName_internalized {#DefaultStubEncodingName-internalized}
```
public static final String DefaultStubEncodingName_internalized
```


Standardkodningsnamnet

### DefaultVersion {#DefaultVersion}
```
public static final int DefaultVersion
```


Standard‑PSD‑versionen.

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

### SyncLayersRoot_internalized {#SyncLayersRoot-internalized}
```
public final Object SyncLayersRoot_internalized
```


Objektet som kan användas för att synkronisera åtkomst till lagren.

### horizontalResolution {#horizontalResolution}
```
public double horizontalResolution
```


### addBlackWhiteAdjustmentLayer() {#addBlackWhiteAdjustmentLayer--}
```
public final BlackWhiteAdjustmentLayer addBlackWhiteAdjustmentLayer()
```


Lägger till justeringslagret svart‑vit.

**Returns:**
[BlackWhiteAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer) - The created black white adjustment layer.
### addBrightnessContrastAdjustmentLayer(int brightness, int contrast) {#addBrightnessContrastAdjustmentLayer-int-int-}
```
public final BrightnessContrastLayer addBrightnessContrastAdjustmentLayer(int brightness, int contrast)
```


Lägger till justeringslagret för ljusstyrka/kontrast.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ljusstyrka | int | Ljusstyrkan. |
| kontrast | int | Kontrasten. |

**Returns:**
[BrightnessContrastLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer) - Created brightness/contrast layer
### addChannelMixerAdjustmentLayer() {#addChannelMixerAdjustmentLayer--}
```
public final ChannelMixerLayer addChannelMixerAdjustmentLayer()
```


Lägger till justeringslagret kanalblandare med standardparametrar

**Returns:**
[ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) - Added Channel Mixer Layer
### addColorBalanceAdjustmentLayer() {#addColorBalanceAdjustmentLayer--}
```
public final ColorBalanceAdjustmentLayer addColorBalanceAdjustmentLayer()
```


Lägger till justeringslagret färgbalans.

**Returns:**
[ColorBalanceAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer) - A newly created color balance layer.
### addCurvesAdjustmentLayer() {#addCurvesAdjustmentLayer--}
```
public final CurvesLayer addCurvesAdjustmentLayer()
```


Lägger till justeringslagret Kurvor.

**Returns:**
[CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) - Created [CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) Layer
### addExposureAdjustmentLayer() {#addExposureAdjustmentLayer--}
```
public final ExposureLayer addExposureAdjustmentLayer()
```




**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure) {#addExposureAdjustmentLayer-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exposure | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset) {#addExposureAdjustmentLayer-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exposure | float |  |
| offset | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection) {#addExposureAdjustmentLayer-float-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)
```


Lägger till justeringslagret exponering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exposure | float | Exponeringen. |
| offset | float | Förskjutningen. |
| gammaCorrection | float | Gamma-korrektionen. |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer) - Created Exposure Adjustment Layer
### addGradientMapAdjustmentLayer() {#addGradientMapAdjustmentLayer--}
```
public final GradientMapLayer addGradientMapAdjustmentLayer()
```


Lägger till GradientMap Adjustment layer.

**Returns:**
[GradientMapLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer) - GradientMap instance.
### addHueSaturationAdjustmentLayer() {#addHueSaturationAdjustmentLayer--}
```
public final HueSaturationLayer addHueSaturationAdjustmentLayer()
```


Lägger till nyans/mättnad-justeringslagret.

**Returns:**
[HueSaturationLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer) - A newly created hue/saturation layer.
### addInvertAdjustmentLayer() {#addInvertAdjustmentLayer--}
```
public final InvertAdjustmentLayer addInvertAdjustmentLayer()
```


Lägger till ett inverteringsjusteringslager.

**Returns:**
[InvertAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer) - The created invert layer
### addLayer(Layer layer) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void addLayer(Layer layer)
```


Lägger till lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lagret. |

### addLayerGroup(String groupName, int index, boolean startBehaviour) {#addLayerGroup-java.lang.String-int-boolean-}
```
public final LayerGroup addLayerGroup(String groupName, int index, boolean startBehaviour)
```


Lägger till lagergruppen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| groupName | java.lang.String | Namn på gruppen. |
| index | int | Indexet för lagret att infoga efter. |
| startBehaviour | boolean | om den är inställd på  true  [start behaviour] kommer gruppen att vara i öppet läge vid start, annars i minimerat läge. |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - Opening group layer
### addLayer_internalized(Layer layer, int index) {#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-}
```
public void addLayer_internalized(Layer layer, int index)
```


Lägger till lagret på indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lagret. |
| index | int | Indexet. |

### addLevelsAdjustmentLayer() {#addLevelsAdjustmentLayer--}
```
public final LevelsLayer addLevelsAdjustmentLayer()
```


Lägger till Levels-justeringslagret.

**Returns:**
[LevelsLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer) - A newly created Levels layer
### addPhotoFilterLayer(Color color) {#addPhotoFilterLayer-com.aspose.psd.Color-}
```
public final PhotoFilterLayer addPhotoFilterLayer(Color color)
```


Lägger till fotofilterlagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Färgen. |

**Returns:**
[PhotoFilterLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer) - Created PhotoFilter Layer
### addPosterizeAdjustmentLayer() {#addPosterizeAdjustmentLayer--}
```
public final PosterizeLayer addPosterizeAdjustmentLayer()
```


Lägger till Posterize Adjustment layer.

**Returns:**
[PosterizeLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer) - PosterizeLayer instance.
### addRegularLayer() {#addRegularLayer--}
```
public final Layer addRegularLayer()
```


Lägger till ett nytt vanligt lager.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Created regular layer.
### addSelectiveColorAdjustmentLayer() {#addSelectiveColorAdjustmentLayer--}
```
public final SelectiveColorLayer addSelectiveColorAdjustmentLayer()
```


Lägger till selektiv färgjusteringslagret.

**Returns:**
[SelectiveColorLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer) - The created selective color adjustment layer.
### addShapeLayer() {#addShapeLayer--}
```
public final ShapeLayer addShapeLayer()
```


Lägg till ett tomt Shape-lager. Utan banor. De bör läggas till i shape-lagret innan sparning.

**Returns:**
[ShapeLayer](../../com.aspose.psd.fileformats.psd.layers/shapelayer) - ShapeLayer instance.
### addTextLayer(String text, Rectangle rect) {#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-}
```
public final TextLayer addTextLayer(String text, Rectangle rect)
```


Lägger till ett nytt Text-lager.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Lagrets text. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Lagrets rektangel. |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - Created text layer.
### addThresholdAdjustmentLayer() {#addThresholdAdjustmentLayer--}
```
public final ThresholdLayer addThresholdAdjustmentLayer()
```


Lägger till Threshold-justeringslagret.

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer) - The created Threshold adjustment layer.
### addVibranceAdjustmentLayer() {#addVibranceAdjustmentLayer--}
```
public final VibranceLayer addVibranceAdjustmentLayer()
```


Lägger till Vibrance-justeringslagret.

**Returns:**
[VibranceLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer) - A newly created Vibrance layer.
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

### convert(PsdOptions newOptions) {#convert-com.aspose.psd.imageoptions.PsdOptions-}
```
public final void convert(PsdOptions newOptions)
```


Konverterar detta bildformat till det som anges i alternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newOptions | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | De nya alternativen. |

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
### createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-}
```
public static PsdImage createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)
```


Skapar en ny instans av klassen [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | PSD-huvudet. |
| colorData | com.aspose.internal.fileformats.psd.sections.ColorData | Färgdatan. |
| imageResources | com.aspose.internal.fileformats.psd.sections.ImageResources | Bildresurserna. |
| layerAndMaskInfo | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo | Lagrets och maskens information. |
| imageData | com.aspose.internal.fileformats.psd.sections.ImageData | Bilddata. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Färgpaletten. |
| version | int | PSD-versionen. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |
| noLayerLoad | boolean | Ingen lagerladdning |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) - Returns the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.
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
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static PsdImage create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-}
```
public static PsdImage create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| colorMode | short |  |
| channelBitDepth | short |  |
| channels | short |  |
| psdVersion | int |  |
| compression | short |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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

### flattenImage() {#flattenImage--}
```
public final void flattenImage()
```


Plattar till alla lager.

### getActiveLayer() {#getActiveLayer--}
```
public final Layer getActiveLayer()
```


Hämtar eller anger det aktiva lagret.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
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
### getBackgroundContents_internalized() {#getBackgroundContents-internalized--}
```
public final RawColor getBackgroundContents_internalized()
```


Hämtar eller anger bakgrundsfärgen. Den kan ses under transparenta objekt.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBitsPerChannel() {#getBitsPerChannel--}
```
public final int getBitsPerChannel()
```


Hämtar bitarna per kanal.

Värde: Bitarna per kanal.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

Värde: Antalet bildbitar per pixel.

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
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Hämtar antalet PSD-kanaler.

Värde: Antalet PSD-kanaler.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmykColorProfile() {#getCmykColorProfile--}
```
public final StreamSource getCmykColorProfile()
```


Hämtar eller anger CMYK-färgprofilen för CMYK PSD-bilder. Måste vara i par med RgbColorProfile för korrekt färgkonvertering.

Värde: CMYK-färgprofilen.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Hämtar eller anger färgläget.

Värde: Färgläget.

**Returns:**
short
### getCompression() {#getCompression--}
```
public final short getCompression()
```


Hämtar komprimeringsmetoden.

Värde: Komprimeringen.

**Returns:**
short
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Hämtar  Image  behållaren.

Värde: Bildbehållaren.

Om den här egenskapen inte är null indikerar det att bilden är inbäddad i en annan bild.

**Returns:**
[Image](../../com.aspose.psd/image)
### getCurrentOptions_internalized() {#getCurrentOptions-internalized--}
```
public final PsdOptions getCurrentOptions_internalized()
```


Hämtar de aktuella bildalternativen.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) - Current options for PSD image
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
### getDefaultReplacementFont_internalized() {#getDefaultReplacementFont-internalized--}
```
public final String getDefaultReplacementFont_internalized()
```


Hämtar eller anger standardersättningsfonten. Om ersättningsfonten är angiven kommer den att användas för rendering. Vi behöver den här metoden för internt stöd.

**Returns:**
java.lang.String - Namnet på ersättningsfonten
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean -  true  om frigjord; annars,  false .
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
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Hämtar palett från format‑specifika platser

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGlobalAngle() {#getGlobalAngle--}
```
public final int getGlobalAngle()
```


Hämtar eller anger den globala vinkeln.

**Returns:**
int
### getGlobalLayerMaskInfo() {#getGlobalLayerMaskInfo--}
```
public final GlobalLayerMaskInfo getGlobalLayerMaskInfo()
```


Hämtar den globala lagermaskinformationen.

**Returns:**
[GlobalLayerMaskInfo](../../com.aspose.psd.fileformats.psd.layers/globallayermaskinfo)
### getGlobalLayerResources() {#getGlobalLayerResources--}
```
public final LayerResource[] getGlobalLayerResources()
```


Hämtar eller anger de globala lagerresurserna.

Värde: De globala lagerresurserna.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getGrayColorProfile() {#getGrayColorProfile--}
```
public final StreamSource getGrayColorProfile()
```


Hämtar eller anger GRAY (monokrom) färgprofilen för gråskaliga PSD-bilder.

Värde: GRÅ (monokrom) färgprofil.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
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


Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för denna [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
double
### getImageLayers_internalized() {#getImageLayers-internalized--}
```
public final Layer[] getImageLayers_internalized()
```


Hämtar eller anger PSD-lagren.

Värde: PSD-lagren.

--------------------

Observera att om det inte finns några lager kommer annan relaterad information i lager- och maskinformationsektionen inte att bevaras (lagermasker, resurser osv).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Hämtar opaciteten för denna bild.

**Returns:**
float - Opacitetsvärdet mellan 0,0 (fullt transparent) och 1,0 (fullt ogenomskinligt).
### getImageResources() {#getImageResources--}
```
public final ResourceBlock[] getImageResources()
```


Hämtar eller anger PSD-bildresurserna.

Värde: PSD-bildresurserna.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


Hämtar den interna datatransformern.

Värde: Den inre datatransformern.

**Returns:**
com.aspose.internal.IInnerDataTransformer - den inre datatransformern.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Hämtar avbrotts­övervakaren.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerAndMask_internalized() {#getLayerAndMask-internalized--}
```
public final LayerAndMaskInfo getLayerAndMask_internalized()
```


Hämtar lagret och masken.

Värde: Lagret och masken.

**Returns:**
com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo
### getLayers() {#getLayers--}
```
public final Layer[] getLayers()
```


Hämtar eller anger PSD-lagren.

Värde: PSD-lagren.

--------------------

Observera att om det inte finns några lager kommer annan relaterad information i lager- och maskinformationsektionen inte att bevaras (lagermasker, resurser osv).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getLinkedLayersManager() {#getLinkedLayersManager--}
```
public final LinkedLayersManager getLinkedLayersManager()
```


Hämtar hanteraren för länkade lager.

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
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
### getPsdHeader_internalized() {#getPsdHeader-internalized--}
```
public final PsdHeader getPsdHeader_internalized()
```


Hämtar eller anger PSD-huvudet.

Värde: PSD-huvudet.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
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

Värde: Det råa dataformatet.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
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
### getRgbColorProfile() {#getRgbColorProfile--}
```
public final StreamSource getRgbColorProfile()
```


Hämtar eller anger RGB-färgprofilen för CMYK PSD-bilder. Måste vara i par med CmykColorProfile för korrekt färgkonvertering.

Värde: RGB-färgprofilen.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Hämtar eller anger roteringsläget.

**Returns:**
int - Rotationsläget.
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
### getSmartObjectProvider() {#getSmartObjectProvider--}
```
public final SmartObjectProvider getSmartObjectProvider()
```


Hämtar leverantören för smarta objekt.

Värde: Smartobjektleverantören.

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Hämtar filsökvägen för källbilden om den finns. Returnerar en tom sträng om källsökvägen inte kan hittas.

**Returns:**
java.lang.String - Filsökvägen för källbilden.
### getSyncExclusiveOperation_internalized() {#getSyncExclusiveOperation-internalized--}
```
public Object getSyncExclusiveOperation_internalized()
```




**Returns:**
java.lang.Object
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Hämtar synkroniseringsroten.

Värde: Synkroniseringsroten.

**Returns:**
java.lang.Object
### getTimeline() {#getTimeline--}
```
public Timeline getTimeline()
```


Hämtar tidslinjen ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) för denna [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
[Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Hämtar bildens transparenta färg.

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Hämtar eller anger ett värde som indikerar om XMP‑metadata ska uppdateras.

**Returns:**
boolean -  true  om XMP-metadata uppdateras; annars  false .
### getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates) {#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-}
```
public static ResourceBlock[] getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)
```


Hämtar uppdaterade resurser med ett helt nytt resursblock.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resources | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) | Resurserna. |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | Resursen att lägga till i befintliga resurser. |
| removeDuplicates | boolean | om den är satt till  true  tas resurser med identiska ID:n bort. |

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[] - Returnerar en array med uppdaterade resursblock.
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
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Hämtar eller anger versionen.

Värde: Versionen.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
double
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

Värde: XMP-metadata.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation av en bild till dess gråskalerepresentation

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna RasterImage.

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

Värde:  true  om detta objekt har ändrat bilden; annars,  false .

**Returns:**
boolean
### hasTransparencyData() {#hasTransparencyData--}
```
public final boolean hasTransparencyData()
```


Hämtar eller anger ett värde som indikerar om den första alfakanalen innehåller transparensdata för det sammanslagna resultatet när lagringsdata specificeras.

Värde:  true  om den första alfakanalen innehåller transparensdata för det sammanslagna resultatet när lagringsdata specificeras; annars,  false .

**Returns:**
boolean
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Hämtar ett värde som indikerar om bilden har transparent färg.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### insertLayerAfter_internalized(Layer layer, Layer layerToInsert) {#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void insertLayerAfter_internalized(Layer layer, Layer layerToInsert)
```


Infogar lagret efter det angivna lagret med alla förberedelser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lagret. |
| layerToInsert | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lagret att infoga. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Hämtar ett värde som indikerar om bilddata för närvarande är cachad.

**Returns:**
boolean -  true  om bilddata är cachad; annars  false .
### isFlatten() {#isFlatten--}
```
public final boolean isFlatten()
```


Hämtar ett värde som indikerar om PSD-bilden är platt.

Värde:  true  om detta objekt är plattat; annars,  false .

**Returns:**
boolean
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
### isUsePhotoshopCompatibilityMode_internalized() {#isUsePhotoshopCompatibilityMode-internalized--}
```
public boolean isUsePhotoshopCompatibilityMode_internalized()
```




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
### mergeLayers(Layer bottomLayer, Layer topLayer) {#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final Layer mergeLayers(Layer bottomLayer, Layer topLayer)
```


Slår ihop lagren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bottomLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Det nedre lagret. |
| topLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Det översta lagret. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Bottom layer after the merge
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


Anropas när behållaren för denna [Image](../../com.aspose.psd/image) har satts.

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
### removeGlobalTextEngineResource_internalized() {#removeGlobalTextEngineResource-internalized--}
```
public final void removeGlobalTextEngineResource_internalized()
```


Tar bort den globala textmotornresursen - Metoden används för vissa textlagrade psd-filer som inte kan öppnas i Adobe Photoshop efter bearbetning (i huvudsak för textlager med saknade teckensnitt). Efter att ha använt detta alternativ måste användaren göra följande i den öppnade Photoshop-filen: Meny \"Text\" -> \"Processa saknade teckensnitt\". Efter den operationen kommer all text att visas igen. Observera att denna operation kan orsaka vissa slutgiltiga layoutändringar.

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


Ändrar storlek på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typ av storleksändring. |

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

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Strömmen att spara bildens data till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Sparalternativen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Destinationens bildgränsrektangel. Ställ in den tomma rektangeln för att använda källgränserna. |

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

### saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport) {#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)
```


Sparar bilddata till den angivna strömmen med de angivna sparalternativen och gränserna. Exporterar valfritt endast de angivna lagren för förhandsgranskning av rendering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Strömmen som bilddata ska sparas till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Sparaalternativen att använda. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Destinationens bildgränsrektangel. Sätt till  Rectangle.Empty  för att använda källans gränser. |
| layersToExport | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | De specifika lagren att exportera. Ett  null  värde indikerar standardbeteende med alla lager. |

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

### setActiveLayer(Layer value) {#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void setActiveLayer(Layer value)
```


Hämtar eller anger det aktiva lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

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

### setBackgroundContents_internalized(RawColor value) {#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents_internalized(RawColor value)
```


Hämtar eller anger bakgrundsfärgen. Den kan ses under transparenta objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setCmykColorProfile(StreamSource value)
```


Hämtar eller anger CMYK-färgprofilen för CMYK PSD-bilder. Måste vara i par med RgbColorProfile för korrekt färgkonvertering.

Värde: CMYK-färgprofilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Hämtar eller anger färgläget.

Värde: Färgläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

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
### setGlobalAngle(int value) {#setGlobalAngle-int-}
```
public final void setGlobalAngle(int value)
```


Den globala vinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setGlobalLayerResources(LayerResource[] value) {#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setGlobalLayerResources(LayerResource[] value)
```


Hämtar eller anger de globala lagerresurserna.

Värde: De globala lagerresurserna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setGrayColorProfile(StreamSource value) {#setGrayColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setGrayColorProfile(StreamSource value)
```


GRAY (monokrom) färgprofilen för gråskaliga PSD-bilder.

Värde: GRÅ (monokrom) färgprofil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för denna [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

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

### setImageResources(ResourceBlock[] value) {#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setImageResources(ResourceBlock[] value)
```


Hämtar eller anger PSD-bildresurserna.

Värde: PSD-bildresurserna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Ställer in avbrottsmotorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | avbrottsövervakaren. |

### setLayers(Layer[] value) {#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void setLayers(Layer[] value)
```


Hämtar eller anger PSD-lagren.

Värde: PSD-lagren.

--------------------

Observera att om det inte finns några lager kommer annan relaterad information i lager- och maskinformationsektionen inte att bevaras (lagermasker, resurser osv).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

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


Anger upplösningen för denna [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dpiX | double | Den horisontella upplösningen, i punkter per tum, för  RasterImage . |
| dpiY | double | Den vertikala upplösningen, i punkter per tum, för  RasterImage . |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setRgbColorProfile(StreamSource value)
```


Hämtar eller anger RGB-färgprofilen för CMYK PSD-bilder. Måste vara i par med CmykColorProfile för korrekt färgkonvertering.

Värde: RGB-färgprofilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Hämtar eller anger roteringsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Rotationsläget. |

### setTransparencyData(boolean value) {#setTransparencyData-boolean-}
```
public final void setTransparencyData(boolean value)
```


Hämtar eller anger ett värde som indikerar om den första alfakanalen innehåller transparensdata för det sammanslagna resultatet när lagringsdata specificeras.

Värde:  true  om den första alfakanalen innehåller transparensdata för det sammanslagna resultatet när lagringsdata specificeras; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

### setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized) {#setUsePhotoshopCompatibilityMode-internalized-boolean-}
```
public void setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| usePhotoshopCompatibilityMode_internalized | boolean |  |

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


Ställer in venture-licensen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ventureLicense | java.lang.Object | Venture‑licensen. |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Hämtar eller anger versionen.

Värde: Versionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Hämtar eller anger XMP-metadata.

Värde: XMP-metadata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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

