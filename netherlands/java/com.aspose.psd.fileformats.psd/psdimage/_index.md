---
title: "PsdImage"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Definieert de PsdImage‑klasse die de mogelijkheid biedt om PSD‑bestanden te laden, te bewerken en op te slaan, evenals eigenschappen bij te werken, watermerken toe te voegen, grafische bewerkingen uit te voeren of een bestandsformaat naar een ander te converteren."
type: docs
weight: 14
url: /nl/java/com.aspose.psd.fileformats.psd/psdimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage)
```
public final class PsdImage extends RasterCachedImage
```

Definieert de PsdImage‑klasse die de mogelijkheid biedt om PSD‑bestanden te laden, te bewerken en op te slaan, evenals eigenschappen bij te werken, watermerken toe te voegen, grafische bewerkingen uit te voeren of een bestandsformaat naar een ander te converteren. Aspose.PSD ondersteunt import als een laag en export naar de volgende formaten: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb, evenals export naar Pdf met selecteerbare tekst.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PsdImage(String path)](#PsdImage-java.lang.String-) | Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in het pad). |
| [PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.lang.String-short-short-short-int-short-) | Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in het pad) met constructor‑parameters. |
| [PsdImage(InputStream stream)](#PsdImage-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in de stream). |
| [PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.io.InputStream-short-short-short-int-short-) | Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in de stream) met constructor‑parameters. |
| [PsdImage(RasterImage rasterImage)](#PsdImage-com.aspose.psd.RasterImage-) | Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-klasse vanaf een bestaande rasterafbeelding (geen psd‑afbeelding) met RGB‑kleurmodus, 4 kanalen, 8 bit/kanaal en zonder compressie. |
| [PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-) | Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-klasse vanaf een bestaande rasterafbeelding (geen psd‑afbeelding) met constructor‑parameters. |
| [PsdImage(int width, int height)](#PsdImage-int-int-) | Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-klasse met opgegeven breedte en hoogte. |
| [PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-) | Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-klasse met opgegeven breedte, hoogte, palet, kleurmodus, aantal kanalen en bitdiepte per kanaal, en met opgegeven compressiemodusparameters. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [DefaultStubEncodingName_internalized](#DefaultStubEncodingName-internalized) | De standaardcoderingsnaam |
| [DefaultVersion](#DefaultVersion) | De standaard PSD‑versie. |
| [OnCreate_internalized](#OnCreate-internalized) | Treedt op wanneer afbeelding werd geladen |
| [OnLoad_internalized](#OnLoad-internalized) | Treedt op wanneer afbeelding werd geladen door createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Treedt op wanneer afbeelding werd geladen of opgeslagen |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Treedt op wanneer krediet werd gebruikt |
| [SyncLayersRoot_internalized](#SyncLayersRoot-internalized) | Het object dat kan worden gebruikt om de toegang tot de lagen te synchroniseren. |
| [horizontalResolution](#horizontalResolution) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addBlackWhiteAdjustmentLayer()](#addBlackWhiteAdjustmentLayer--) | Voegt de zwart‑wit‑aanpassingslaag toe. |
| [addBrightnessContrastAdjustmentLayer(int brightness, int contrast)](#addBrightnessContrastAdjustmentLayer-int-int-) | Voegt de helderheid/contrast‑aanpassingslaag toe. |
| [addChannelMixerAdjustmentLayer()](#addChannelMixerAdjustmentLayer--) | Voegt de kanaalmixer‑aanpassingslaag toe met standaardparameters |
| [addColorBalanceAdjustmentLayer()](#addColorBalanceAdjustmentLayer--) | Voegt de kleurbalans‑aanpassingslaag toe. |
| [addCurvesAdjustmentLayer()](#addCurvesAdjustmentLayer--) | Voegt de Curves Adjustment layer toe. |
| [addExposureAdjustmentLayer()](#addExposureAdjustmentLayer--) |  |
| [addExposureAdjustmentLayer(float exposure)](#addExposureAdjustmentLayer-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset)](#addExposureAdjustmentLayer-float-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)](#addExposureAdjustmentLayer-float-float-float-) | Voegt de exposure adjustment layer toe. |
| [addGradientMapAdjustmentLayer()](#addGradientMapAdjustmentLayer--) | Voegt de GradientMap Adjustment layer toe. |
| [addHueSaturationAdjustmentLayer()](#addHueSaturationAdjustmentLayer--) | Voegt de hue/saturation adjustment layer toe. |
| [addInvertAdjustmentLayer()](#addInvertAdjustmentLayer--) | Voegt een invert adjustment layer toe. |
| [addLayer(Layer layer)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Voegt de laag toe. |
| [addLayerGroup(String groupName, int index, boolean startBehaviour)](#addLayerGroup-java.lang.String-int-boolean-) | Voegt de laaggroep toe. |
| [addLayer_internalized(Layer layer, int index)](#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-) | Voegt de laag toe op de index. |
| [addLevelsAdjustmentLayer()](#addLevelsAdjustmentLayer--) | Voegt de Levels adjustment layer toe. |
| [addPhotoFilterLayer(Color color)](#addPhotoFilterLayer-com.aspose.psd.Color-) | Voegt de photofilter layer toe. |
| [addPosterizeAdjustmentLayer()](#addPosterizeAdjustmentLayer--) | Voegt de Posterize Adjustment layer toe. |
| [addRegularLayer()](#addRegularLayer--) | Voegt een nieuwe reguliere laag toe. |
| [addSelectiveColorAdjustmentLayer()](#addSelectiveColorAdjustmentLayer--) | Voegt de selective color adjustment layer toe. |
| [addShapeLayer()](#addShapeLayer--) | Voeg een lege Shape layer toe. |
| [addTextLayer(String text, Rectangle rect)](#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-) | Voegt een nieuwe Text layer toe. |
| [addThresholdAdjustmentLayer()](#addThresholdAdjustmentLayer--) | Voegt de Threshold adjustment layer toe. |
| [addVibranceAdjustmentLayer()](#addVibranceAdjustmentLayer--) | Voegt de Vibrance adjustment layer toe. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Aanpassing van de helderheid voor een afbeelding. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Beeldcontrast |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gamma-correctie van een afbeelding. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma-correctie van een afbeelding. |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | Begint het schaalaanpassingsproces. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarisatie van een afbeelding met behulp van Bradley's adaptieve drempelalgoritme met integrale afbeeldingdrempel. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisatie van een afbeelding met behulp van Bradley's adaptieve drempelalgoritme met integrale afbeeldingdrempel. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisatie van een afbeelding met vooraf gedefinieerde drempel. |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisatie van een afbeelding met Otsu-drempel. |
| [cacheData()](#cacheData--) | Cachet de gegevens en zorgt ervoor dat er geen extra gegevens worden geladen vanuit de onderliggende DataStreamSupporter.DataStreamContainer. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Bepaalt of een afbeelding kan worden geladen vanuit de opgegeven stream. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Bepaalt of een afbeelding kan worden geladen vanuit de opgegeven stream en eventueel met de opgegeven loadOptions. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Bepaalt of een afbeelding kan worden geladen vanaf het opgegeven bestandspad. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Bepaalt of een afbeelding kan worden geladen vanaf het opgegeven bestandspad en eventueel met de opgegeven open options. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Bepaalt of een afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt weergegeven door de meegegeven save options. |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [convert(PsdOptions newOptions)](#convert-com.aspose.psd.imageoptions.PsdOptions-) | Converteert dit afbeeldingsformaat naar het formaat dat is opgegeven in de opties. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Converteert naar aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Maakt een nieuwe afbeelding aan met de opgegeven create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Maakt een nieuwe afbeelding aan met de opgegeven afbeeldingen als pagina's. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Maakt een nieuwe afbeelding aan met de opgegeven afbeeldingen als pagina's. |
| [createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-) | Maakt een nieuwe instantie van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) klasse aan. |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Afbeelding bijsnijden. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Afbeelding bijsnijden met verschuivingen. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Voert dithering uit op de huidige afbeelding. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Voert dithering uit op de huidige afbeelding. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | Afbeelding bijsnijden. |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | Wijzigt de grootte van de afbeelding. |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | Roteert, spiegelt of roteert en spiegelt de afbeelding. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filtert de opgegeven rechthoek. |
| [flattenImage()](#flattenImage--) | Vlak alle lagen af. |
| [getActiveLayer()](#getActiveLayer--) | Haalt de actieve laag op of stelt deze in. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Haalt een 32-bit ARGB-pixel van de afbeelding op. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Haalt een waarde op die aangeeft of het palet automatisch wordt aangepast. |
| [getBackgroundColor()](#getBackgroundColor--) | Haalt op of stelt een waarde voor de achtergrondkleur in. |
| [getBackgroundContents_internalized()](#getBackgroundContents-internalized--) | Haalt de achtergrondkleur op of stelt deze in. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Haalt het aantal bits per kanaal op. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Haalt het aantal bits per pixel van de afbeelding op. |
| [getBounds()](#getBounds--) | Haalt de grenzen van de afbeelding op. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Haalt de buffer‑groottehint op, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [getChannelsCount()](#getChannelsCount--) | Haalt het aantal PSD-kanalen op. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Haalt het CMYK-kleurprofiel op of stelt dit in voor CMYK PSD-afbeeldingen. |
| [getColorMode()](#getColorMode--) | Haalt de kleermodus op of stelt deze in. |
| [getCompression()](#getCompression--) | Haalt de compressiemethode op. |
| [getContainer()](#getContainer--) | Haalt de Image-container op. |
| [getCurrentOptions_internalized()](#getCurrentOptions-internalized--) | Haalt de huidige afbeeldingopties op. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Haalt de gegevensstroom van het object op. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Haalt het diep aangepast palet op. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Haalt de standaard 32-bit ARGB-pixelarray op. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Haalt de standaardopties op. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Haalt de standaard pixelarray op met behulp van een gedeeltelijke pixelloader. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Haalt de standaard ruwe gegevensarray op met behulp van een gedeeltelijke pixelloader. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Haalt de standaard ruwe gegevensarray op. |
| [getDefaultReplacementFont_internalized()](#getDefaultReplacementFont-internalized--) | Haalt of stelt het standaard vervangingslettertype in. |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getFileFormat()](#getFileFormat--) | Haalt een waarde van bestandsformaat op |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Haalt het bestandsformaat op. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Haalt het bestandsformaat op. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Haalt het bestandsformaat op. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Haalt palet op van formatspecifieke locaties |
| [getGlobalAngle()](#getGlobalAngle--) | Haalt op of stelt de globale hoek in. |
| [getGlobalLayerMaskInfo()](#getGlobalLayerMaskInfo--) | Haalt de globale laagmaskerinformatie op. |
| [getGlobalLayerResources()](#getGlobalLayerResources--) | Haalt of stelt de globale laagresources in. |
| [getGrayColorProfile()](#getGrayColorProfile--) | Haalt of stelt het GRAY (monochroom) kleurprofiel in voor Grayscale PSD-afbeeldingen. |
| [getHeight()](#getHeight--) | Haalt de afbeeldingshoogte op. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Haalt of stelt de horizontale resolutie, in pixels per inch, van deze [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) in. |
| [getImageLayers_internalized()](#getImageLayers-internalized--) | Haalt of stelt de PSD-lagen in. |
| [getImageOpacity()](#getImageOpacity--) | Haalt de dekking op van deze afbeelding. |
| [getImageResources()](#getImageResources--) | Haalt of stelt de PSD-afbeeldingsresources in. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Haalt de interne data‑transformator op. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Haalt de interrupt‑monitor op. |
| [getLayerAndMask_internalized()](#getLayerAndMask-internalized--) | Haalt de laag en het masker op. |
| [getLayers()](#getLayers--) | Haalt of stelt de PSD-lagen in. |
| [getLinkedLayersManager()](#getLinkedLayersManager--) | Haalt de gekoppelde lagenbeheerder op. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Haalt op of stelt de maximaal toegestane toewijzing voor gedeeltelijke rotatie‑opslaan in. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Haalt de geheugenbeheerder op. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Haalt de datum en tijd op waarop de resource‑afbeelding voor het laatst is gewijzigd. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getOriginalOptions()](#getOriginalOptions--) | Haalt de opties op op basis van de oorspronkelijke bestandsinstellingen. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Haalt de schilderbare afbeelding op. |
| [getPalette()](#getPalette--) | Haalt het kleurenpalet op. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Haalt een afbeeldingspixel op. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Haalt een waarde op of stelt deze in die aangeeft of de afbeeldingscomponenten moeten worden voorvermenigvuldigd. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Maakt de private lettertypecache aan. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Haalt de informatie van de voortgangs‑eventhandler op. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Haalt de informatie van de voortgangs‑eventhandler op. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Haalt een proportionele hoogte op. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Haalt een proportionele breedte op. |
| [getPsdHeader_internalized()](#getPsdHeader-internalized--) | Haalt of stelt de PSD-header in. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Haalt de aangepaste kleurconverter op of stelt deze in |
| [getRawDataFormat()](#getRawDataFormat--) | Haalt het ruwe gegevensformaat op. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Haalt de fallback‑index op of stelt deze in die moet worden gebruikt wanneer de paletindex buiten bereik is |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Haalt de geïndexeerde kleurconverter op of stelt deze in |
| [getRawLineSize()](#getRawLineSize--) | Haalt de ruwe regelgrootte in bytes op. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Haalt of stelt het RGB-kleurprofiel in voor CMYK PSD-afbeeldingen. |
| [getRotateMode()](#getRotateMode--) | Haalt de rotatiemodus op of stelt deze in. |
| [getSize()](#getSize--) | Haalt de afbeeldingsgrootte op. |
| [getSkewAngle()](#getSkewAngle--) | Haalt de scheefstandhoek op. |
| [getSmartObjectProvider()](#getSmartObjectProvider--) | Haalt de smart object-provider op. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Haalt het bestandspad van de bronafbeelding op als deze bestaat. |
| [getSyncExclusiveOperation_internalized()](#getSyncExclusiveOperation-internalized--) |  |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Haalt de synchronisatiewortel op. |
| [getTimeline()](#getTimeline--) | Haalt de Tijdlijn ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) van deze [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getTransparentColor()](#getTransparentColor--) | Haalt de transparante kleur van de afbeelding op. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Haalt een waarde op of stelt deze in die aangeeft of de XMP‑metadata moet worden bijgewerkt. |
| [getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)](#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-) | Haalt bijgewerkte resources op met een gloednieuwe resourceblok. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Haalt een waarde op die aangeeft of het object een geheugenoptimalisatiestrategie gebruikt |
| [getUseRawData()](#getUseRawData--) | Haalt op of stelt een waarde in die aangeeft of ruwe gegevensladen moet worden gebruikt wanneer ruwe gegevensladen beschikbaar is. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Haalt de gebruikte palet op. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Haalt de venture-licentie op. |
| [getVersion()](#getVersion--) | Haalt of stelt de versie in. |
| [getVerticalResolution()](#getVerticalResolution--) | Haalt of stelt de verticale resolutie, in pixels per inch, van deze [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) in. |
| [getWidth()](#getWidth--) | Haalt de breedte van de afbeelding op. |
| [getXmpData()](#getXmpData--) | Haalt op of stelt de XMP-metadata in. |
| [grayscale()](#grayscale--) | Transformatie van een afbeelding naar zijn grijswaardenrepresentatie |
| [hasAlpha()](#hasAlpha--) | Haalt op of stelt de verticale resolutie, in pixels per inch, van deze RasterImage in. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Haalt een waarde op die aangeeft of de afbeelding een achtergrondkleur heeft. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Haalt op of stelt een waarde in die aangeeft of deze afbeelding-instantie is gewijzigd na het laden. |
| [hasTransparencyData()](#hasTransparencyData--) | Haalt of stelt een waarde in die aangeeft of het eerste alfakanaal de transparantiedata bevat voor het samengevoegde resultaat bij het specificeren van laaggegevens. |
| [hasTransparentColor()](#hasTransparentColor--) | Haalt een waarde op die aangeeft of de afbeelding een transparante kleur heeft. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Haalt op of stelt de maximale voortgangswaarde in |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Geeft de voortgang aan. |
| [insertLayerAfter_internalized(Layer layer, Layer layerToInsert)](#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Voegt de laag in na de opgegeven laag met alle voorbereidingen |
| [isCached()](#isCached--) | Haalt een waarde op die aangeeft of afbeeldingsgegevens momenteel in de cache staan. |
| [isFlatten()](#isFlatten--) | Haalt een waarde op die aangeeft of de PSD-afbeelding is afgevlakt. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Haalt een waarde op die aangeeft of ruwe gegevensladen beschikbaar is. |
| [isUsePalette()](#isUsePalette--) | Haalt een waarde op die aangeeft of de afbeeldingspalet wordt gebruikt. |
| [isUsePhotoshopCompatibilityMode_internalized()](#isUsePhotoshopCompatibilityMode-internalized--) |  |
| [load(InputStream stream)](#load-java.io.InputStream-) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| [load(String filePath)](#load-java.lang.String-) | Laadt een nieuwe afbeelding van het opgegeven bestand. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Laadt een nieuwe afbeelding van het opgegeven bestand. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | Laadt 32-bit ARGB-pixels. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | Laadt 64-bit ARGB-pixels. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | Laadt pixels in CMYK-formaat. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | Laadt pixels in CMYK-formaat. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Laadt 32-bit ARGB-pixels gedeeltelijk per pakketten. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Laadt pixels gedeeltelijk per pakketten. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | Laadt pixels. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Laadt ruwe afbeeldingsgegevens met behulp van het gedeeltelijke verwerkingsmechanisme. |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Laadt ruwe gegevens. |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| [mergeLayers(Layer bottomLayer, Layer topLayer)](#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Voegt de lagen samen. |
| [normalizeAngle()](#normalizeAngle--) | Normaliseert de hoek. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normaliseert de hoek. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Wordt aangeroepen wanneer de container van deze [Image](../../com.aspose.psd/image) is ingesteld. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Leest de volledige scanlijn op basis van de opgegeven scanlijnindex. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Leest de volledige scanlijn op basis van de opgegeven scanlijnindex. |
| [removeGlobalTextEngineResource_internalized()](#removeGlobalTextEngineResource-internalized--) | Verwijdert de globale tekstengine-resource - Methode wordt gebruikt voor sommige tekst-gearmeerde PSD-bestanden die na verwerking niet kunnen worden geopend in Adobe Photoshop (voornamelijk voor tekstlagen gerelateerd aan ontbrekende lettertypen). |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Vervangt alle niet-transparante kleuren door een nieuwe kleur en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Vervangt alle niet-transparante kleuren door een nieuwe kleur en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Wijzigt de grootte van de afbeelding. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Wijzigt de grootte van de afbeelding. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Wijzigt de grootte van de afbeelding. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Wijzigt de hoogte proportioneel. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Wijzigt de hoogte proportioneel. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Wijzigt de hoogte proportioneel. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Wijzigt de breedte proportioneel. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Wijzigt de breedte proportioneel. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Wijzigt de breedte proportioneel. |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | Wijzigt de grootte van de laag met de opgegeven inverse schaal. |
| [rotate(float angle)](#rotate-float-) | Roteer de afbeelding rond het midden. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Roteer de afbeelding rond het midden. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | Slaat de afbeeldingsgegevens op in de onderliggende stream. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Slaat de gegevens van het object op in de opgegeven stream. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Slaat de gegevens van het object op in de opgegeven stream. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(String filePath)](#save-java.lang.String-) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | Slaat de 32-bit ARGB-pixels op. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | Slaat de pixels op. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | Slaat de pixels op. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | Slaat de pixels op. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Slaat de ruwe gegevens op. |
| [saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)](#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---) | Slaat de afbeeldingsgegevens op in de opgegeven stream met behulp van de opgegeven opslagopties en grenzen. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [setActiveLayer(Layer value)](#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Haalt de actieve laag op of stelt deze in. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Stelt een afbeelding 32-bit ARGB-pixel in voor de opgegeven positie. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Stelt een waarde in die aangeeft of de palet automatisch wordt aangepast. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Haalt op of stelt een waarde in die aangeeft of de afbeelding een achtergrondkleur heeft. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Haalt op of stelt een waarde voor de achtergrondkleur in. |
| [setBackgroundContents_internalized(RawColor value)](#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Haalt de achtergrondkleur op of stelt deze in. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Stelt de buffergroottehint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Haalt het CMYK-kleurprofiel op of stelt dit in voor CMYK PSD-afbeeldingen. |
| [setColorMode(short value)](#setColorMode-short-) | Haalt de kleermodus op of stelt deze in. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Stelt de  Image  container in. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Stelt de data loader direct in. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Stelt de gegevensstroom van het object in. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Stelt palette in op formaat‑specifieke plaatsen |
| [setGlobalAngle(int value)](#setGlobalAngle-int-) | De globale hoek. |
| [setGlobalLayerResources(LayerResource[] value)](#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Haalt of stelt de globale laagresources in. |
| [setGrayColorProfile(StreamSource value)](#setGrayColorProfile-com.aspose.psd.sources.StreamSource-) | Het GRAY (monochroom) kleurprofiel voor Grayscale PSD-afbeeldingen. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Haalt of stelt de horizontale resolutie, in pixels per inch, van deze [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) in. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Stelt een waarde in die aangeeft of [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze afbeelding-instantie is gewijzigd na het laden. |
| [setImageResources(ResourceBlock[] value)](#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Haalt of stelt de PSD-afbeeldingsresources in. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Stelt de interne data transformer in. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Stelt de interrupt monitor in. |
| [setLayers(Layer[] value)](#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | Haalt of stelt de PSD-lagen in. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Haalt op of stelt de maximaal toegestane toewijzing voor gedeeltelijke rotatie‑opslaan in. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Stelt de geheugenbeheerder in. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Stelt het kleurenpalet in. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Stelt het afbeeldingspalet in. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Stelt een afbeeldingspixel in voor de opgegeven positie. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of de afbeeldingscomponenten moeten worden voorvermenigvuldigd. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Haalt de aangepaste kleurconverter op of stelt deze in |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Haalt de fallback‑index op of stelt deze in die moet worden gebruikt wanneer de paletindex buiten bereik is |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Haalt de geïndexeerde kleurconverter op of stelt deze in |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Stelt de resolutie in voor deze [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Haalt of stelt het RGB-kleurprofiel in voor CMYK PSD-afbeeldingen. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Haalt de rotatiemodus op of stelt deze in. |
| [setTransparencyData(boolean value)](#setTransparencyData-boolean-) | Haalt of stelt een waarde in die aangeeft of het eerste alfakanaal de transparantiedata bevat voor het samengevoegde resultaat bij het specificeren van laaggegevens. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Haalt een waarde op die aangeeft of de afbeelding een transparante kleur heeft. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Haalt de transparante kleur van de afbeelding op. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of de XMP‑metadata moet worden bijgewerkt. |
| [setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)](#setUsePhotoshopCompatibilityMode-internalized-boolean-) |  |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Haalt op of stelt een waarde in die aangeeft of ruwe gegevensladen moet worden gebruikt wanneer ruwe gegevensladen beschikbaar is. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Stelt de venture-licentie in. |
| [setVersion(int value)](#setVersion-int-) | Haalt of stelt de versie in. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Haalt of stelt de verticale resolutie, in pixels per inch, van deze [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) in. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Haalt op of stelt de XMP-metadata in. |
| [toBitmap()](#toBitmap--) | Converteert rasterafbeelding naar de bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Schrijft de volledige scanlijn naar de opgegeven scanlijnindex. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Schrijft de volledige scanlijn naar de opgegeven scanlijnindex. |
### PsdImage(String path) {#PsdImage-java.lang.String-}
```
public PsdImage(String path)
```


Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) klasse vanuit een opgegeven pad van een rasterafbeelding (geen psd-afbeelding in het pad). Wordt gebruikt om een psd-afbeelding te initialiseren met standaardparameters - Kleermodus - rgb, 4 kanalen, 8 bit per kanaal, Compressie - Raw.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | java.lang.String | Het pad om pixel- en paletgegevens van te laden en mee te initialiseren. |

### PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.lang.String-short-short-short-int-short-}
```
public PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in het pad) met constructor‑parameters.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | java.lang.String | Het pad om pixel- en paletgegevens van te laden en mee te initialiseren. |
| colorMode | short | De kleurmodus. |
| channelBitDepth | short | De PSD-bitdiepte per kanaal. |
| channels | short | Het aantal PSD-kanalen. |
| psdVersion | int | De PSD-versie. |
| compression | short | De compressie om te gebruiken. |

### PsdImage(InputStream stream) {#PsdImage-java.io.InputStream-}
```
public PsdImage(InputStream stream)
```


Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) klasse vanuit een opgegeven pad van een rasterafbeelding (geen psd-afbeelding in de stream). Wordt gebruikt om een psd-afbeelding te initialiseren met standaardparameters - Kleermodus - rgb, 4 kanalen, 8 bit per kanaal, Compressie - Raw.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De stream om pixel- en paletgegevens van te laden en mee te initialiseren. |

### PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.io.InputStream-short-short-short-int-short-}
```
public PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in de stream) met constructor‑parameters.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De stream om pixel- en paletgegevens van te laden en mee te initialiseren. |
| colorMode | short | De kleurmodus. |
| channelBitDepth | short | De PSD-bitdiepte per kanaal. |
| channels | short | Het aantal PSD-kanalen. |
| psdVersion | int | De PSD-versie. |
| compression | short | De compressie om te gebruiken. |

### PsdImage(RasterImage rasterImage) {#PsdImage-com.aspose.psd.RasterImage-}
```
public PsdImage(RasterImage rasterImage)
```


Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-klasse vanaf een bestaande rasterafbeelding (geen psd‑afbeelding) met RGB‑kleurmodus, 4 kanalen, 8 bit/kanaal en zonder compressie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | De afbeelding om pixel- en paletgegevens van te laden en mee te initialiseren. |

### PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-}
```
public PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-klasse vanaf een bestaande rasterafbeelding (geen psd‑afbeelding) met constructor‑parameters.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | De afbeelding om pixel- en paletgegevens van te laden en mee te initialiseren. |
| colorMode | short | De kleurmodus. |
| channelBitDepth | short | De PSD-bitdiepte per kanaal. |
| channels | short | Het aantal PSD-kanalen. |
| psdVersion | int | De PSD-versie. |
| compression | short | De compressie om te gebruiken. |

### PsdImage(int width, int height) {#PsdImage-int-int-}
```
public PsdImage(int width, int height)
```


Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) klasse met opgegeven breedte en hoogte. Wordt gebruikt om een lege psd-afbeelding te initialiseren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| breedte | int | De breedte van de afbeelding. |
| hoogte | int | De hoogte van de afbeelding. |

### PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-}
```
public PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initialiseert een nieuw exemplaar van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) klasse met opgegeven breedte, hoogte, paletter, kleermodus, kanaaltelling en kanaalbitlengte en opgegeven compressiemodusparameters. Wordt gebruikt om een lege psd-afbeelding te initialiseren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| breedte | int | De breedte van de afbeelding. |
| hoogte | int | De hoogte van de afbeelding. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het kleurenpalet. |
| colorMode | short | De kleurmodus. |
| channelBitDepth | short | De PSD-bitdiepte per kanaal. |
| channels | short | Het aantal PSD-kanalen. |
| psdVersion | int | De PSD-versie. |
| compression | short | De compressie om te gebruiken. |

### DefaultStubEncodingName_internalized {#DefaultStubEncodingName-internalized}
```
public static final String DefaultStubEncodingName_internalized
```


De standaardcoderingsnaam

### DefaultVersion {#DefaultVersion}
```
public static final int DefaultVersion
```


De standaard PSD‑versie.

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Treedt op wanneer afbeelding werd geladen

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Treedt op wanneer afbeelding werd geladen door createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Treedt op wanneer afbeelding werd geladen of opgeslagen

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Treedt op wanneer krediet werd gebruikt

### SyncLayersRoot_internalized {#SyncLayersRoot-internalized}
```
public final Object SyncLayersRoot_internalized
```


Het object dat kan worden gebruikt om de toegang tot de lagen te synchroniseren.

### horizontalResolution {#horizontalResolution}
```
public double horizontalResolution
```


### addBlackWhiteAdjustmentLayer() {#addBlackWhiteAdjustmentLayer--}
```
public final BlackWhiteAdjustmentLayer addBlackWhiteAdjustmentLayer()
```


Voegt de zwart‑wit‑aanpassingslaag toe.

**Returns:**
[BlackWhiteAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer) - The created black white adjustment layer.
### addBrightnessContrastAdjustmentLayer(int brightness, int contrast) {#addBrightnessContrastAdjustmentLayer-int-int-}
```
public final BrightnessContrastLayer addBrightnessContrastAdjustmentLayer(int brightness, int contrast)
```


Voegt de helderheid/contrast‑aanpassingslaag toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| helderheid | int | De helderheid. |
| contrast | int | Het contrast. |

**Returns:**
[BrightnessContrastLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer) - Created brightness/contrast layer
### addChannelMixerAdjustmentLayer() {#addChannelMixerAdjustmentLayer--}
```
public final ChannelMixerLayer addChannelMixerAdjustmentLayer()
```


Voegt de kanaalmixer‑aanpassingslaag toe met standaardparameters

**Returns:**
[ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) - Added Channel Mixer Layer
### addColorBalanceAdjustmentLayer() {#addColorBalanceAdjustmentLayer--}
```
public final ColorBalanceAdjustmentLayer addColorBalanceAdjustmentLayer()
```


Voegt de kleurbalans‑aanpassingslaag toe.

**Returns:**
[ColorBalanceAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer) - A newly created color balance layer.
### addCurvesAdjustmentLayer() {#addCurvesAdjustmentLayer--}
```
public final CurvesLayer addCurvesAdjustmentLayer()
```


Voegt de Curves Adjustment layer toe.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| exposure | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset) {#addExposureAdjustmentLayer-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| exposure | float |  |
| offset | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection) {#addExposureAdjustmentLayer-float-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)
```


Voegt de exposure adjustment layer toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| exposure | float | De belichting. |
| offset | float | De offset. |
| gammaCorrection | float | De gamma-correctie. |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer) - Created Exposure Adjustment Layer
### addGradientMapAdjustmentLayer() {#addGradientMapAdjustmentLayer--}
```
public final GradientMapLayer addGradientMapAdjustmentLayer()
```


Voegt de GradientMap Adjustment layer toe.

**Returns:**
[GradientMapLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer) - GradientMap instance.
### addHueSaturationAdjustmentLayer() {#addHueSaturationAdjustmentLayer--}
```
public final HueSaturationLayer addHueSaturationAdjustmentLayer()
```


Voegt de hue/saturation adjustment layer toe.

**Returns:**
[HueSaturationLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer) - A newly created hue/saturation layer.
### addInvertAdjustmentLayer() {#addInvertAdjustmentLayer--}
```
public final InvertAdjustmentLayer addInvertAdjustmentLayer()
```


Voegt een invert adjustment layer toe.

**Returns:**
[InvertAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer) - The created invert layer
### addLayer(Layer layer) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void addLayer(Layer layer)
```


Voegt de laag toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | De laag. |

### addLayerGroup(String groupName, int index, boolean startBehaviour) {#addLayerGroup-java.lang.String-int-boolean-}
```
public final LayerGroup addLayerGroup(String groupName, int index, boolean startBehaviour)
```


Voegt de laaggroep toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| groupName | java.lang.String | Naam van de groep. |
| index | int | De index van de laag waarna ingevoegd moet worden. |
| startBehaviour | boolean | als ingesteld op  true  [start behaviour] zal de groep bij het opstarten in de geopende toestand zijn, anders in geminimaliseerde toestand. |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - Opening group layer
### addLayer_internalized(Layer layer, int index) {#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-}
```
public void addLayer_internalized(Layer layer, int index)
```


Voegt de laag toe op de index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | De laag. |
| index | int | De index. |

### addLevelsAdjustmentLayer() {#addLevelsAdjustmentLayer--}
```
public final LevelsLayer addLevelsAdjustmentLayer()
```


Voegt de Levels adjustment layer toe.

**Returns:**
[LevelsLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer) - A newly created Levels layer
### addPhotoFilterLayer(Color color) {#addPhotoFilterLayer-com.aspose.psd.Color-}
```
public final PhotoFilterLayer addPhotoFilterLayer(Color color)
```


Voegt de photofilter layer toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | De kleur. |

**Returns:**
[PhotoFilterLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer) - Created PhotoFilter Layer
### addPosterizeAdjustmentLayer() {#addPosterizeAdjustmentLayer--}
```
public final PosterizeLayer addPosterizeAdjustmentLayer()
```


Voegt de Posterize Adjustment layer toe.

**Returns:**
[PosterizeLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer) - PosterizeLayer instance.
### addRegularLayer() {#addRegularLayer--}
```
public final Layer addRegularLayer()
```


Voegt een nieuwe reguliere laag toe.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Created regular layer.
### addSelectiveColorAdjustmentLayer() {#addSelectiveColorAdjustmentLayer--}
```
public final SelectiveColorLayer addSelectiveColorAdjustmentLayer()
```


Voegt de selective color adjustment layer toe.

**Returns:**
[SelectiveColorLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer) - The created selective color adjustment layer.
### addShapeLayer() {#addShapeLayer--}
```
public final ShapeLayer addShapeLayer()
```


Voeg een lege Shape-laag toe. Zonder paden. Ze moeten aan de shape-laag worden toegevoegd vóór het opslaan.

**Returns:**
[ShapeLayer](../../com.aspose.psd.fileformats.psd.layers/shapelayer) - ShapeLayer instance.
### addTextLayer(String text, Rectangle rect) {#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-}
```
public final TextLayer addTextLayer(String text, Rectangle rect)
```


Voegt een nieuwe Text layer toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tekst | java.lang.String | De tekst van de laag. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek van de laag. |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - Created text layer.
### addThresholdAdjustmentLayer() {#addThresholdAdjustmentLayer--}
```
public final ThresholdLayer addThresholdAdjustmentLayer()
```


Voegt de Threshold adjustment layer toe.

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer) - The created Threshold adjustment layer.
### addVibranceAdjustmentLayer() {#addVibranceAdjustmentLayer--}
```
public final VibranceLayer addVibranceAdjustmentLayer()
```


Voegt de Vibrance adjustment layer toe.

**Returns:**
[VibranceLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer) - A newly created Vibrance layer.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Aanpassing van de helderheid voor een afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| helderheid | int | Helderheidswaarde. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Beeldcontrast

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| contrast | float | Contrastwaarde (in bereik [-100; 100]) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Gamma-correctie van een afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gamma | float | Gamma-coëfficiënt voor rode, groene en blauwe kanalen |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gamma-correctie van een afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gammaRed | float | Gamma-coëfficiënt voor het rode kanaal |
| gammaGreen | float | Gamma-coëfficiënt voor het groene kanaal |
| gammaBlue | float | Gamma-coëfficiënt voor het blauwe kanaal |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


Begint het schaalaanpassingsproces.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe afbeeldingsbreedte. |
| newHeight | int | De nieuwe afbeeldingshoogte. |

**Returns:**
com.aspose.internal.IResizeController - De resize controller.
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarisatie van een afbeelding met behulp van Bradley's adaptieve drempelalgoritme met integrale afbeeldingdrempel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brightnessDifference | double | Het helderheidsverschil tussen de pixel en het gemiddelde van een s x s venster van pixels gecentreerd rond deze pixel. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarisatie van een afbeelding met behulp van Bradley's adaptieve drempelalgoritme met integrale afbeeldingdrempel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brightnessDifference | double | Het helderheidsverschil tussen de pixel en het gemiddelde van een s x s venster van pixels gecentreerd rond deze pixel. |
| windowSize | int | De grootte van een s x s venster van pixels gecentreerd rond deze pixel |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarisatie van een afbeelding met vooraf gedefinieerde drempel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threshold | byte | Drempelwaarde. Als de overeenkomstige grijze waarde van een pixel groter is dan de drempel, wordt een waarde van 255 aan deze toegewezen, anders 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarisatie van een afbeelding met Otsu-drempel.

### cacheData() {#cacheData--}
```
public void cacheData()
```


Cachet de gegevens en zorgt ervoor dat er geen extra gegevens worden geladen vanuit de onderliggende DataStreamSupporter.DataStreamContainer.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Bepaalt of een afbeelding kan worden geladen vanuit de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De stream om van te laden. |

**Returns:**
boolean -  true  als de afbeelding kan worden geladen van de opgegeven stream; anders,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Bepaalt of een afbeelding kan worden geladen vanuit de opgegeven stream en eventueel met de opgegeven loadOptions.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De stream om van te laden. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

**Returns:**
boolean -  true  als de afbeelding kan worden geladen van de opgegeven stream; anders,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Bepaalt of een afbeelding kan worden geladen vanaf het opgegeven bestandspad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad. |

**Returns:**
boolean -  true  als de afbeelding kan worden geladen van het opgegeven bestand; anders,  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Bepaalt of een afbeelding kan worden geladen vanaf het opgegeven bestandspad en eventueel met de opgegeven open options.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

**Returns:**
boolean -  true  als de afbeelding kan worden geladen van het opgegeven bestand; anders,  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Bepaalt of een afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt weergegeven door de meegegeven save options.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De te gebruiken opslagopties. |

**Returns:**
boolean -  true  als de afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt weergegeven door de meegegeven opslagopties; anders,  false .
### close() {#close--}
```
public void close()
```


Implementeert de Closable-interface en kan worden gebruikt in de try-with-resources-instructie sinds JDK 1.7. Deze methode roept simpelweg de dispose-methode aan.

### convert(PsdOptions newOptions) {#convert-com.aspose.psd.imageoptions.PsdOptions-}
```
public final void convert(PsdOptions newOptions)
```


Converteert dit afbeeldingsformaat naar het formaat dat is opgegeven in de opties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newOptions | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | De nieuwe opties. |

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


Converteert naar aps.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opties. |
| mode | int | De modus. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De kniprechthoek. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - De APS-pagina.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Maakt een nieuwe afbeelding aan met de opgegeven create options.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De afbeeldingsopties. |
| breedte | int | De breedte. |
| hoogte | int | De hoogte. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Maakt een nieuwe afbeelding aan met de opgegeven afbeeldingen als pagina's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | De afbeeldingen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Maakt een nieuwe afbeelding aan met de opgegeven afbeeldingen als pagina's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | De afbeeldingen. |
| disposeImages | boolean | indien ingesteld op true [dispose images]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-}
```
public static PsdImage createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)
```


Maakt een nieuwe instantie van de [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) klasse aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | De PSD-header. |
| colorData | com.aspose.internal.fileformats.psd.sections.ColorData | De kleurgegevens. |
| imageResources | com.aspose.internal.fileformats.psd.sections.ImageResources | De afbeeldingsbronnen. |
| layerAndMaskInfo | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo | De laag- en maskerinformatie. |
| imageData | com.aspose.internal.fileformats.psd.sections.ImageData | De afbeeldingsgegevens. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het kleurenpalet. |
| version | int | De PSD-versie. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |
| noLayerLoad | boolean | Geen laag laden |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) - Returns the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resizer | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| breedte | int |  |
| hoogte | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static PsdImage create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-}
```
public static PsdImage create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Afbeelding bijsnijden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Afbeelding bijsnijden met verschuivingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| leftShift | int | De linkerschuif. |
| rightShift | int | De rechterverschuiving. |
| topShift | int | De bovenverschuiving. |
| bottomShift | int | De onderverschuiving. |

### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert de huidige instantie.

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Voert dithering uit op de huidige afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ditheringMethod | int | De ditheringsmethode. |
| bitsCount | int | Het uiteindelijke aantal bits voor dithering. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Voert dithering uit op de huidige afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ditheringMethod | int | De ditheringsmethode. |
| bitsCount | int | Het uiteindelijke aantal bits voor dithering. |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het aangepaste palet voor dithering. |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


Afbeelding bijsnijden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek. |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


Wijzigt de grootte van de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe breedte. |
| newHeight | int | De nieuwe hoogte. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | De instellingen voor grootte wijzigen. |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | float |  |
| resizeProportionally | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


Roteert, spiegelt of roteert en spiegelt de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rotateFlipType | int | Het type rotatie en omkering. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtert de opgegeven rechthoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek. |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | De opties. |

### flattenImage() {#flattenImage--}
```
public final void flattenImage()
```


Vlak alle lagen af.

### getActiveLayer() {#getActiveLayer--}
```
public final Layer getActiveLayer()
```


Haalt de actieve laag op of stelt deze in.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Haalt een 32-bit ARGB-pixel van de afbeelding op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De pixel x locatie. |
| y | int | De pixel y locatie. |

**Returns:**
int - De 32‑bit ARGB-pixel voor de opgegeven locatie.
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Haalt een waarde op die aangeeft of het palet automatisch wordt aangepast.

**Returns:**
boolean -  true  als automatische paletaanpassing is ingeschakeld; anders,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Haalt op of stelt een waarde voor de achtergrondkleur in.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBackgroundContents_internalized() {#getBackgroundContents-internalized--}
```
public final RawColor getBackgroundContents_internalized()
```


Haalt of stelt de achtergrondkleur in. Deze kan worden gezien onder transparante objecten.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBitsPerChannel() {#getBitsPerChannel--}
```
public final int getBitsPerChannel()
```


Haalt het aantal bits per kanaal op.

Waarde: Het aantal bits per kanaal.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Haalt het aantal bits per pixel van de afbeelding op.

Waarde: Het aantal bits per pixel van de afbeelding.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Haalt de grenzen van de afbeelding op.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Haalt de buffer‑groottehint op, die de maximaal toegestane grootte voor alle interne buffers definieert.

Waarde: De buffer‑grootte hint, in megabytes. Een niet‑positieve waarde betekent geen geheugenlimiet voor interne buffers

**Returns:**
int - de buffer‑grootte hint die de maximaal toegestane grootte voor alle interne buffers definieert.
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Haalt het aantal PSD-kanalen op.

Waarde: Het aantal PSD-kanalen.

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


Haalt op of stelt het CMYK-kleurprofiel in voor CMYK PSD-afbeeldingen. Moet in combinatie met RgbColorProfile staan voor correcte kleurconversie.

Waarde: Het CMYK-kleurprofiel.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Haalt de kleermodus op of stelt deze in.

Waarde: De kleurmodus.

**Returns:**
short
### getCompression() {#getCompression--}
```
public final short getCompression()
```


Haalt de compressiemethode op.

Waarde: De compressie.

**Returns:**
short
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Haalt de Image-container op.

Waarde: De  Image  container.

Als deze eigenschap niet null is, geeft dit aan dat de afbeelding zich binnen een andere afbeelding bevindt.

**Returns:**
[Image](../../com.aspose.psd/image)
### getCurrentOptions_internalized() {#getCurrentOptions-internalized--}
```
public final PsdOptions getCurrentOptions_internalized()
```


Haalt de huidige afbeeldingopties op.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) - Current options for PSD image
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Haalt de gegevensstroom van het object op.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Haalt het diep aangepast palet op.

**Returns:**
boolean - Het diep aanpassen van het palet.
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Haalt de standaard 32-bit ARGB-pixelarray op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek waarvoor pixels worden opgehaald. |

**Returns:**
int[] - De standaard pixelarray.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Haalt de standaardopties op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | java.lang.Object[] | De argumenten. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Haalt de standaard pixelarray op met behulp van een gedeeltelijke pixelloader.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek waarvoor pixels worden opgehaald. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | De gedeeltelijke pixelloader. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Haalt de standaard ruwe gegevensarray op met behulp van een gedeeltelijke pixelloader.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek waarvoor pixels worden opgehaald. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | De gedeeltelijke ruwe gegevensloader. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | De instellingen voor ruwe gegevens. |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Haalt de standaard ruwe gegevensarray op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek waarvoor ruwe gegevens worden opgehaald. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | De instellingen voor ruwe gegevens. |

**Returns:**
byte[] - De standaard ruwe gegevensarray.
### getDefaultReplacementFont_internalized() {#getDefaultReplacementFont-internalized--}
```
public final String getDefaultReplacementFont_internalized()
```


Haalt op of stelt het standaard vervangingslettertype in. Als het vervangingslettertype is ingesteld, wordt het gebruikt voor weergave. We hebben deze methode nodig voor interne ondersteuning.

**Returns:**
java.lang.String - De naam van het vervangingslettertype
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Haalt een waarde op die aangeeft of deze instantie is vrijgegeven.

**Returns:**
boolean -  true  als vrijgegeven; anders,  false .
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Haalt een waarde van bestandsformaat op

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Haalt het bestandsformaat op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | De stream. |

--------------------

Het bepaalde bestandsformaat betekent niet dat de opgegeven afbeelding geladen kan worden. Gebruik een van de overloads van de CanLoad-methode om te bepalen of de stream geladen kan worden. |

**Returns:**
long - Het bepaalde bestandsformaat.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Haalt het bestandsformaat op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stream | java.io.InputStream | De stream. |

Het bepaalde bestandsformaat betekent niet dat de opgegeven afbeelding geladen kan worden. Gebruik een van de overloads van de CanLoad-methode om te bepalen of de stream geladen kan worden. |

**Returns:**
long - Het bepaalde bestandsformaat.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Haalt het bestandsformaat op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad. |

Het bepaalde bestandsformaat betekent niet dat de opgegeven afbeelding geladen kan worden. Gebruik een van de overloads van de CanLoad-methode om te bepalen of het bestand geladen kan worden. |

**Returns:**
long - Het bepaalde bestandsformaat.
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Haalt het rechthoek op dat past bij de huidige afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek waarvoor een passende rechthoek moet worden verkregen. |
| breedte | int | De breedte van het object. |
| hoogte | int | De hoogte van het object. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Haalt het rechthoek op dat past bij de huidige afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek waarvoor een passende rechthoek moet worden verkregen. |
| pixels | int[] | De 32-bit ARGB-pixels. |
| breedte | int | De breedte van het object. |
| hoogte | int | De hoogte van het object. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Haalt palet op van formatspecifieke locaties

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGlobalAngle() {#getGlobalAngle--}
```
public final int getGlobalAngle()
```


Haalt op of stelt de globale hoek in.

**Returns:**
int
### getGlobalLayerMaskInfo() {#getGlobalLayerMaskInfo--}
```
public final GlobalLayerMaskInfo getGlobalLayerMaskInfo()
```


Haalt de globale laagmaskerinformatie op.

**Returns:**
[GlobalLayerMaskInfo](../../com.aspose.psd.fileformats.psd.layers/globallayermaskinfo)
### getGlobalLayerResources() {#getGlobalLayerResources--}
```
public final LayerResource[] getGlobalLayerResources()
```


Haalt of stelt de globale laagresources in.

Waarde: De globale laagresources.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getGrayColorProfile() {#getGrayColorProfile--}
```
public final StreamSource getGrayColorProfile()
```


Haalt of stelt het GRAY (monochroom) kleurprofiel in voor Grayscale PSD-afbeeldingen.

Waarde: Het GRAY (monochroom) kleurprofiel.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Haalt de afbeeldingshoogte op.

Waarde: de afbeeldingshoogte.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Haalt of stelt de horizontale resolutie, in pixels per inch, van deze [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) in.

**Returns:**
double
### getImageLayers_internalized() {#getImageLayers-internalized--}
```
public final Layer[] getImageLayers_internalized()
```


Haalt of stelt de PSD-lagen in.

Waarde: De PSD-lagen.

--------------------

Let op dat als er geen lagen zijn, de andere gerelateerde informatie binnen de sectie laag- en maskerinformatie niet wordt bewaard (laagmaskers, resources enzovoort).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Haalt de dekking op van deze afbeelding.

**Returns:**
float - De opaciteitswaarde tussen 0,0 (volledig transparant) en 1,0 (volledig ondoorzichtig).
### getImageResources() {#getImageResources--}
```
public final ResourceBlock[] getImageResources()
```


Haalt of stelt de PSD-afbeeldingsresources in.

Waarde: De PSD-afbeeldingsresources.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


Haalt de interne data‑transformator op.

Waarde: de innerlijke datatransformator.

**Returns:**
com.aspose.internal.IInnerDataTransformer - de innerlijke datatransformator.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Haalt de interrupt‑monitor op.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerAndMask_internalized() {#getLayerAndMask-internalized--}
```
public final LayerAndMaskInfo getLayerAndMask_internalized()
```


Haalt de laag en het masker op.

Waarde: De laag en het masker.

**Returns:**
com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo
### getLayers() {#getLayers--}
```
public final Layer[] getLayers()
```


Haalt of stelt de PSD-lagen in.

Waarde: De PSD-lagen.

--------------------

Let op dat als er geen lagen zijn, de andere gerelateerde informatie binnen de sectie laag- en maskerinformatie niet wordt bewaard (laagmaskers, resources enzovoort).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getLinkedLayersManager() {#getLinkedLayersManager--}
```
public final LinkedLayersManager getLinkedLayersManager()
```


Haalt de gekoppelde lagenbeheerder op.

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


Haalt op of stelt de maximaal toegestane toewijzing voor gedeeltelijke rotatie‑opslaan in.

**Returns:**
int - De maximaal toegestane toewijzing voor gedeeltelijke rotatie-opslag.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Haalt de geheugenbeheerder op.

Waarde: De geheugenbeheerder.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - de geheugenbeheerder.
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Haalt de datum en tijd op waarop de resource‑afbeelding voor het laatst is gewijzigd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| useDefault | boolean | indien ingesteld op  true  wordt de informatie uit FileInfo gebruikt als standaardwaarde. |

**Returns:**
java.util.Date - De datum en tijd waarop de bronafbeelding voor het laatst is gewijzigd.
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Haalt de opties op op basis van de oorspronkelijke bestandsinstellingen. Dit kan handig zijn om de bitsdiepte en andere parameters van de oorspronkelijke afbeelding ongewijzigd te houden. Bijvoorbeeld, als we een zwart-wit PNG-afbeelding met 1 bit per pixel laden en deze vervolgens opslaan met de  `DataStreamSupporter.Save(string)`  methode, wordt een PNG-afbeelding met 8-bit per pixel geproduceerd. Om dit te voorkomen en een PNG-afbeelding met 1-bit per pixel op te slaan, gebruik deze methode om de bijbehorende opslagopties te verkrijgen en geef ze door aan de  `Image.Save(string, ImageOptionsBase)`  methode als tweede parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Haalt de schilderbare afbeelding op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Haalt het kleurenpalet op. Het kleurenpalet wordt niet gebruikt wanneer pixels direct worden weergegeven.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Haalt een afbeeldingspixel op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De pixel x locatie. |
| y | int | De pixel y locatie. |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Haalt een waarde op of stelt deze in die aangeeft of de afbeeldingscomponenten moeten worden voorvermenigvuldigd.

**Returns:**
boolean -  true  als de beeldcomponenten moeten worden voorvermenigvuldigd; anders,  false .
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Maakt de private lettertypecache aan.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - De private lettertypecache.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Haalt de informatie van de voortgangs‑eventhandler op.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Haalt de informatie van de voortgangs‑eventhandler op.

Waarde: De informatie over de voortgangs‑eventhandler.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Haalt een proportionele hoogte op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| breedte | int | De breedte. |
| hoogte | int | De hoogte. |
| newWidth | int | De nieuwe breedte. |

**Returns:**
int - De proportionele hoogte.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Haalt een proportionele breedte op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| breedte | int | De breedte. |
| hoogte | int | De hoogte. |
| newHeight | int | De nieuwe hoogte. |

**Returns:**
int - De proportionele breedte.
### getPsdHeader_internalized() {#getPsdHeader-internalized--}
```
public final PsdHeader getPsdHeader_internalized()
```


Haalt of stelt de PSD-header in.

Waarde: De PSD-header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Haalt de aangepaste kleurconverter op of stelt deze in

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Haalt het ruwe gegevensformaat op.

Waarde: Het ruwe gegevensformaat.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Haalt de huidige ruwe gegevensinstellingen op. Let op: bij gebruik van deze instellingen worden de gegevens geladen zonder conversie.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Haalt de fallback‑index op of stelt deze in die moet worden gebruikt wanneer de paletindex buiten bereik is

**Returns:**
int - De fallback‑index die moet worden gebruikt wanneer de paletindex buiten de grenzen valt
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Haalt de geïndexeerde kleurconverter op of stelt deze in

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Haalt de ruwe regelgrootte in bytes op.

**Returns:**
int - De ruwe regelgrootte in bytes.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public final StreamSource getRgbColorProfile()
```


Haalt op of stelt het RGB-kleurprofiel in voor CMYK PSD-afbeeldingen. Moet in combinatie met CmykColorProfile staan voor correcte kleurconversie.

Waarde: Het RGB-kleurprofiel.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Haalt de rotatiemodus op of stelt deze in.

**Returns:**
int - De rotatiemodus.
### getSize() {#getSize--}
```
public Size getSize()
```


Haalt de afbeeldingsgrootte op.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Haalt de scheefhoek op. Deze methode is toepasbaar op gescande tekstdocumenten, om de scheefhoek te bepalen bij het scannen.

**Returns:**
float - De scheefhoek, in graden.
### getSmartObjectProvider() {#getSmartObjectProvider--}
```
public final SmartObjectProvider getSmartObjectProvider()
```


Haalt de smart object-provider op.

Waarde: De smart object provider.

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Haalt het bestandspad van de bronafbeelding op als deze bestaat. Retourneert een lege string als het bronpad niet kan worden gevonden.

**Returns:**
java.lang.String - Het bestandspad van de bronafbeelding.
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


Haalt de synchronisatiewortel op.

Waarde: De synchronisatiewortel.

**Returns:**
java.lang.Object
### getTimeline() {#getTimeline--}
```
public Timeline getTimeline()
```


Haalt de Tijdlijn ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) van deze [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
[Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Haalt de transparante kleur van de afbeelding op.

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Haalt een waarde op of stelt deze in die aangeeft of de XMP‑metadata moet worden bijgewerkt.

**Returns:**
boolean -  true  als de XMP-metadata wordt bijgewerkt; anders,  false .
### getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates) {#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-}
```
public static ResourceBlock[] getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)
```


Haalt bijgewerkte resources op met een gloednieuwe resourceblok.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resources | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) | De resources. |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | De resource om toe te voegen aan bestaande resources. |
| removeDuplicates | boolean | indien ingesteld op  true  verwijdert resources met identieke ID's. |

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[] - Retourneert een array met bijgewerkte resourceblokken.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Haalt een waarde op die aangeeft of het object een geheugenoptimalisatiestrategie gebruikt

Waarde:  true  als het object een geheugenoptimalisatiestrategie gebruikt; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of het object een geheugenoptimalisatiestrategie gebruikt
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Haalt op of stelt een waarde in die aangeeft of ruwe gegevensladen moet worden gebruikt wanneer ruwe gegevensladen beschikbaar is.

**Returns:**
boolean -  true  als ruwe gegevens worden geladen wanneer het laden van ruwe gegevens beschikbaar is.; anders,  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


Haalt de gebruikte palet op.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Haalt de venture-licentie op.

**Returns:**
java.lang.Object - De venture-licentie als object.
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Haalt of stelt de versie in.

Waarde: De versie.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Haalt of stelt de verticale resolutie, in pixels per inch, van deze [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) in.

**Returns:**
double
### getWidth() {#getWidth--}
```
public int getWidth()
```


Haalt de breedte van de afbeelding op.

Waarde: De afbeeldingsbreedte.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Haalt op of stelt de XMP-metadata in.

Waarde: De XMP-metadata.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformatie van een afbeelding naar zijn grijswaardenrepresentatie

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Haalt op of stelt de verticale resolutie, in pixels per inch, van deze RasterImage in.

Waarde:  true  als deze instantie alfa heeft; anders,  false .

**Returns:**
boolean
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Haalt een waarde op die aangeeft of de afbeelding een achtergrondkleur heeft.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Haalt op of stelt een waarde in die aangeeft of deze afbeelding-instantie is gewijzigd na het laden.

Waarde:  true  als deze instantie een gewijzigde afbeelding heeft; anders,  false .

**Returns:**
boolean
### hasTransparencyData() {#hasTransparencyData--}
```
public final boolean hasTransparencyData()
```


Haalt of stelt een waarde in die aangeeft of het eerste alfakanaal de transparantiedata bevat voor het samengevoegde resultaat bij het specificeren van laaggegevens.

Waarde:  true  als het eerste alfakanaal de transparantiedata bevat voor het samengevoegde resultaat bij het specificeren van laaggegevens; anders,  false .

**Returns:**
boolean
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Haalt een waarde op die aangeeft of de afbeelding een transparante kleur heeft.

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


Haalt op of stelt de maximale voortgangswaarde in

Waarde: De maximale voortgangswaarde

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Geeft de voortgang aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### insertLayerAfter_internalized(Layer layer, Layer layerToInsert) {#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void insertLayerAfter_internalized(Layer layer, Layer layerToInsert)
```


Voegt de laag in na de opgegeven laag met alle voorbereidingen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | De laag. |
| layerToInsert | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | De laag om in te voegen. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Haalt een waarde op die aangeeft of afbeeldingsgegevens momenteel in de cache staan.

**Returns:**
boolean -  true  als afbeeldingsgegevens in de cache staan; anders,  false .
### isFlatten() {#isFlatten--}
```
public final boolean isFlatten()
```


Haalt een waarde op die aangeeft of de PSD-afbeelding is afgevlakt.

Waarde:  true  als deze instantie is afgevlakt; anders,  false .

**Returns:**
boolean
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Haalt een waarde op die aangeeft of ruwe gegevensladen beschikbaar is.

**Returns:**
boolean -  true  als dit laden van ruwe gegevens beschikbaar is; anders,  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Haalt een waarde op die aangeeft of de afbeeldingspalet wordt gebruikt.

Waarde:  true  als het palet in de afbeelding wordt gebruikt; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of het afbeeldingspalet wordt gebruikt.
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


Laadt een nieuwe afbeelding van de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De stream om de afbeelding van te laden. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Laadt een nieuwe afbeelding van de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De stream om de afbeelding van te laden. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Laadt een nieuwe afbeelding van de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestand | java.io.RandomAccessFile | Het bestand om de afbeelding van te laden. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Laadt een nieuwe afbeelding van de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestand | java.io.RandomAccessFile | Het bestand om de afbeelding van te laden. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Laadt een nieuwe afbeelding van het opgegeven bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om de afbeelding van te laden. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Laadt een nieuwe afbeelding van het opgegeven bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om de afbeelding van te laden. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Laadt 32-bit ARGB-pixels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek om pixels van te laden. |

**Returns:**
int[] - De geladen 32-bit ARGB-pixelarray.
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


Laadt 64-bit ARGB-pixels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek om pixels van te laden. |

**Returns:**
long[] - De geladen 64-bit ARGB-pixelarray.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Laadt pixels in CMYK-formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek om pixels van te laden. |

**Returns:**
int[] - De geladen CMYK-pixels gepresenteerd als 32-bit integerwaarden.
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


Laadt pixels in CMYK-indeling. Deze methode is verouderd. Gebruik alstublieft de effectievere methode loadCmyk32Pixels(Rectangle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek om pixels van te laden. |

**Returns:**
com.aspose.psd.CmykColor[] - De geladen CMYK-pixelarray.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Laadt 32-bit ARGB-pixels gedeeltelijk per pakketten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De gewenste rechthoek. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | De 32-bit ARGB-pixelloader. |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Laadt pixels gedeeltelijk per pakketten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De gewenste rechthoek. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | De pixelloader. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Laadt pixels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek om pixels van te laden. |

**Returns:**
com.aspose.psd.Color[] - De geladen pixelarray.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Laadt ruwe afbeeldingsgegevens met behulp van het gedeeltelijke verwerkingsmechanisme.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Het gewenste rechthoekige gebied van de afbeelding om gegevens van te laden. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | De instellingen voor ruwe gegevens. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | De ruwe-gegevensloader. |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Laadt ruwe gegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek om ruwe gegevens van te laden. |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | De bestemmingsafbeeldingsgrenzen. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | De ruwe-gegevensinstellingen die gebruikt moeten worden voor geladen gegevens. Opmerking: als gegevens niet in het opgegeven formaat zijn, wordt gegevensconversie uitgevoerd. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | De ruwe-gegevensloader. |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Laadt een nieuwe afbeelding van de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | De stream om de afbeelding van te laden. |
| startPosition | long | De startpositie om de afbeelding van te laden. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Laadt een nieuwe afbeelding van de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | De stream om de afbeelding van te laden. |
| startPosition | long | De startpositie om de afbeelding van te laden. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### mergeLayers(Layer bottomLayer, Layer topLayer) {#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final Layer mergeLayers(Layer bottomLayer, Layer topLayer)
```


Voegt de lagen samen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bottomLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | De onderste laag. |
| topLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | De bovenste laag. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Bottom layer after the merge
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Normaliseert de hoek. Deze methode is toepasbaar op gescande tekstdocumenten om de scheve scan te verwijderen. Deze methode gebruikt [.getSkewAngle](../../null/\#getSkewAngle) en [.rotate(float)](../../null/\#rotate-float-) methoden.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normaliseert de hoek. Deze methode is toepasbaar op gescande tekstdocumenten om de scheve scan te verwijderen. Deze methode gebruikt [.getSkewAngle](../../null/\#getSkewAngle) en [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-) methoden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resizeProportionally | boolean | indien ingesteld op true wordt de grootte van uw afbeelding aangepast volgens de projecties van het geroteerde rechthoek (hoekpunten); in het andere geval blijven de afmetingen ongewijzigd en wordt alleen de interne afbeeldinginhoud geroteerd. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Kleur van de achtergrond. |

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


Wordt aangeroepen wanneer de container van deze [Image](../../com.aspose.psd/image) is ingesteld.

### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Leest de volledige scanlijn op basis van de opgegeven scanlijnindex.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scanLineIndex | int | Nulgebaseerde index van de scanlijn. |

**Returns:**
int[] - De scanlijn 32‑bit ARGB-kleurwaardenarray.
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Leest de volledige scanlijn op basis van de opgegeven scanlijnindex.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scanLineIndex | int | Nulgebaseerde index van de scanlijn. |

**Returns:**
com.aspose.psd.Color[] - De scanlijn pixelkleurwaardenarray.
### removeGlobalTextEngineResource_internalized() {#removeGlobalTextEngineResource-internalized--}
```
public final void removeGlobalTextEngineResource_internalized()
```


Verwijdert de globale tekstengine-resource - Methode wordt gebruikt voor sommige tekstgelaagde PSD-bestanden die na verwerking niet kunnen worden geopend in Adobe Photoshop (voornamelijk voor ontbrekende lettertype-tekstlagen). Na het gebruiken van deze optie moet de gebruiker het volgende doen in het geopende Photoshop‑bestand: Menu "Text" -> "Process absent fonts". Na die bewerking zal alle tekst weer verschijnen. Houd er rekening mee dat deze bewerking enkele uiteindelijke lay-outwijzigingen kan veroorzaken.

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | Oude kleur die vervangen moet worden. |
| oldColorDiff | byte | Toegestane afwijking in de oude kleur om de vervangen kleurtint te kunnen verbreden. |
| newColor | [Color](../../com.aspose.psd/color) | Nieuwe kleur om de oude kleur mee te vervangen. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oldColorArgb | int | Oude kleur ARGB-waarde die vervangen moet worden. |
| oldColorDiff | byte | Toegestane afwijking in de oude kleur om de vervangen kleurtint te kunnen verbreden. |
| newColorArgb | int | Nieuwe kleur ARGB-waarde om de oude kleur mee te vervangen. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Vervangt alle niet-transparante kleuren door de nieuwe kleur en behoudt de oorspronkelijke alfa‑waarde om gladde randen te behouden. Opmerking: als u het gebruikt op afbeeldingen zonder transparantie, worden alle kleuren vervangen door één enkele kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | Nieuwe kleur om niet‑transparante kleuren mee te vervangen. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Vervangt alle niet-transparante kleuren door de nieuwe kleur en behoudt de oorspronkelijke alfa‑waarde om gladde randen te behouden. Opmerking: als u het gebruikt op afbeeldingen zonder transparantie, worden alle kleuren vervangen door één enkele kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorArgb | int | Nieuwe kleur ARGB-waarde om niet‑transparante kleuren mee te vervangen. |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Wijzigt de grootte van de afbeelding. De standaard  ResizeType.LeftTopToLeftTop  wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe breedte. |
| newHeight | int | De nieuwe hoogte. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Wijzigt de grootte van de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe breedte. |
| newHeight | int | De nieuwe hoogte. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | De instellingen voor grootte wijzigen. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Wijzigt de grootte van de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe breedte. |
| newHeight | int | De nieuwe hoogte. |
| resizeType | int | Het resize‑type. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Wijzigt de hoogte proportioneel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newHeight | int | De nieuwe hoogte. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Wijzigt de hoogte proportioneel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newHeight | int | De nieuwe hoogte. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | De instellingen voor het wijzigen van de afbeeldinggrootte. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Wijzigt de hoogte proportioneel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newHeight | int | De nieuwe hoogte. |
| resizeType | int | Type van de grootteaanpassing. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Wijzigt de breedte proportioneel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe breedte. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Wijzigt de breedte proportioneel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe breedte. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | De instellingen voor het wijzigen van de afbeeldinggrootte. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Wijzigt de breedte proportioneel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe breedte. |
| resizeType | int | Type van de grootteaanpassing. |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


Wijzigt de laag met de opgegeven inverse schaal. (nieuwe breedte = oude breedte / schaal; nieuwe hoogte = oude hoogte / schaal)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scaleX | double | De schaal X. |
| scaleY | double | De schaal Y. |
| resizeType | int | Type van de grootteaanpassing. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Roteer de afbeelding rond het midden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | float | De rotatiehoek in graden. Positieve waarden roteren met de klok mee. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Roteer de afbeelding rond het midden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | float | De rotatiehoek in graden. Positieve waarden roteren met de klok mee. |
| resizeProportionally | boolean | indien ingesteld op true wordt de grootte van uw afbeelding aangepast volgens de projecties van het geroteerde rechthoek (hoekpunten); in het andere geval blijven de afmetingen ongewijzigd en wordt alleen de interne afbeeldinginhoud geroteerd. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Kleur van de achtergrond. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Roteert, spiegelt of roteert en spiegelt de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


Slaat de afbeeldingsgegevens op in de onderliggende stream.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Slaat de gegevens van het object op in de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | De stream om de gegevens van het object op te slaan. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | De stream om de gegevens van de afbeelding op te slaan. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opslagopties. |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | De stream om de gegevens van de afbeelding op te slaan. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opslagopties. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek met de grenzen van de bestemmingsafbeelding. Stel de lege rechthoek in om de brongrenzen te gebruiken. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Slaat de gegevens van het object op in de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestand | java.io.RandomAccessFile | De stream om de gegevens van het object op te slaan. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestand | java.io.RandomAccessFile | Het bestand om de gegevens van de afbeelding op te slaan. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opties. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestand | java.io.RandomAccessFile | Het bestand om de gegevens van de afbeelding op te slaan. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opslagopties. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek met de grenzen van de doelafbeelding. Stel de lege rechthoek in om de brongrenzen te gebruiken. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om de gegevens van het object op te slaan. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om de gegevens van het object op te slaan. |
| overWrite | boolean | indien ingesteld op  true  wordt de bestandsinhoud overschreven, anders wordt toegevoegd. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opties. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opties. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek met de grenzen van de doelafbeelding. Stel de lege rechthoek in om de brongrenzen te gebruiken. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Slaat de 32-bit ARGB-pixels op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek om pixels in op te slaan. |
| pixels | int[] | De 32-bits ARGB-pixelarray. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Slaat de pixels op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek om pixels in op te slaan. |
| pixels | int[] | De CMYK-pixels gepresenteerd als 32-bits gehele getallen. |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Slaat de pixels op. Deze methode is verouderd. Gebruik a.u.b. de effectievere  saveCmyk32Pixels(Rectangle, int[])  methode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek om pixels in op te slaan. |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | De CMYK-pixelarray. |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Slaat de pixels op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek om pixels in op te slaan. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | De pixelarray. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Slaat de ruwe gegevens op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | byte[] | De ruwe gegevens. |
| dataOffset | int | De startoffset van de ruwe gegevens. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek van de ruwe gegevens. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | De instellingen van de ruwe gegevens waarin de data zich bevindt. |

### saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport) {#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)
```


Slaat de afbeeldingsgegevens op in de opgegeven stream met behulp van de opgegeven opslagopties en grenzen. Exporteert optioneel alleen de opgegeven lagen voor weergave‑preview.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | De stream waarin de afbeeldingsgegevens worden opgeslagen. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De te gebruiken opslagopties. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek met de grenzen van de doelafbeelding. Stel in op  Rectangle.Empty  om de brongrenzen te gebruiken. |
| layersToExport | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | De specifieke lagen om te exporteren. Een  null  waarde geeft het standaardgedrag met alle lagen aan. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | De stream om de gegevens van de afbeelding op te slaan. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opslagopties. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek met de grenzen van de bestemmingsafbeelding. Stel de lege rechthoek in om de brongrenzen te gebruiken. |

### setActiveLayer(Layer value) {#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void setActiveLayer(Layer value)
```


Haalt de actieve laag op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Stelt een afbeelding 32-bit ARGB-pixel in voor de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De pixel x locatie. |
| y | int | De pixel y locatie. |
| argb32Color | int | De 32-bits ARGB-pixel voor de opgegeven positie. |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Stelt een waarde in die aangeeft of de palet automatisch wordt aangepast.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true als automatische paletaanpassing is ingeschakeld; anders false. |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of de afbeelding een achtergrondkleur heeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Haalt op of stelt een waarde voor de achtergrondkleur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBackgroundContents_internalized(RawColor value) {#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents_internalized(RawColor value)
```


Haalt of stelt de achtergrondkleur in. Deze kan worden gezien onder transparante objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Stelt de buffergroottehint in, die de maximaal toegestane grootte voor alle interne buffers definieert.

Waarde: De buffer‑grootte hint, in megabytes. Een niet‑positieve waarde betekent geen geheugenlimiet voor interne buffers

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | de buffergroottehint die de maximaal toegestane grootte voor alle interne buffers definieert. |

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setCmykColorProfile(StreamSource value)
```


Haalt op of stelt het CMYK-kleurprofiel in voor CMYK PSD-afbeeldingen. Moet in combinatie met RgbColorProfile staan voor correcte kleurconversie.

Waarde: Het CMYK-kleurprofiel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Haalt de kleermodus op of stelt deze in.

Waarde: De kleurmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Stelt de  Image  container in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | De Image-container. |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


Stelt de data loader direct in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | De gegevenslader. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Stelt de gegevensstroom van het object in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | De gegevensstroom van het object. |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


Stelt palette in op formaat‑specifieke plaatsen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Nieuw 32-bits ARGB-palet. |

**Returns:**
boolean
### setGlobalAngle(int value) {#setGlobalAngle-int-}
```
public final void setGlobalAngle(int value)
```


De globale hoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setGlobalLayerResources(LayerResource[] value) {#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setGlobalLayerResources(LayerResource[] value)
```


Haalt of stelt de globale laagresources in.

Waarde: De globale laagresources.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setGrayColorProfile(StreamSource value) {#setGrayColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setGrayColorProfile(StreamSource value)
```


Het GRAY (monochroom) kleurprofiel voor Grayscale PSD-afbeeldingen.

Waarde: Het GRAY (monochroom) kleurprofiel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Haalt of stelt de horizontale resolutie, in pixels per inch, van deze [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Stelt een waarde in die aangeeft of [ignore after save].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true als [ignore after save]; anders false. |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze afbeelding-instantie is gewijzigd na het laden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true als deze instantie een gewijzigde afbeelding heeft; anders false. |

### setImageResources(ResourceBlock[] value) {#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setImageResources(ResourceBlock[] value)
```


Haalt of stelt de PSD-afbeeldingsresources in.

Waarde: De PSD-afbeeldingsresources.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


Stelt de interne data transformer in.

Waarde: de innerlijke datatransformator.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.internal.IInnerDataTransformer | de interne gegevensomzetter. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Stelt de interrupt monitor in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | de onderbrekingsmonitor. |

### setLayers(Layer[] value) {#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void setLayers(Layer[] value)
```


Haalt of stelt de PSD-lagen in.

Waarde: De PSD-lagen.

--------------------

Let op dat als er geen lagen zijn, de andere gerelateerde informatie binnen de sectie laag- en maskerinformatie niet wordt bewaard (laagmaskers, resources enzovoort).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


Haalt op of stelt de maximaal toegestane toewijzing voor gedeeltelijke rotatie‑opslaan in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De maximaal toegestane toewijzing voor gedeeltelijke rotatie-opslag. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Stelt de geheugenbeheerder in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | De geheugenbeheerder. |
| needDispose | boolean | indien ingesteld op  true  [need dispose]. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Stelt het kleurenpalet in. Het kleurenpalet wordt niet gebruikt wanneer pixels direct worden weergegeven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het kleurenpalet. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Stelt het afbeeldingspalet in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het in te stellen palet. |
| updateColors | boolean | indien ingesteld op  true  worden kleuren bijgewerkt volgens het nieuwe palet; anders blijven kleurindexen ongewijzigd. Merk op dat ongewijzigde indexen de afbeelding kunnen laten crashen bij het laden als sommige indexen geen overeenkomstige paletinvoer hebben. |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


Stelt een afbeeldingspixel in voor de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De pixel x locatie. |
| y | int | De pixel y locatie. |
| color | [Color](../../com.aspose.psd/color) | De pixelkleur voor de opgegeven positie. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of de afbeeldingscomponenten moeten worden voorvermenigvuldigd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true  als de beeldcomponenten moeten worden voorvermenigvuldigd; anders,  false . |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Haalt de aangepaste kleurconverter op of stelt deze in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | De aangepaste kleurconverter |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Haalt de fallback‑index op of stelt deze in die moet worden gebruikt wanneer de paletindex buiten bereik is

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De fallback-index om te gebruiken wanneer de paletindex buiten de grenzen valt |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Haalt de geïndexeerde kleurconverter op of stelt deze in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | De geïndexeerde kleurconverter |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Stelt de resolutie in voor deze [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dpiX | double | De horizontale resolutie, in dots per inch, van de  RasterImage . |
| dpiY | double | De verticale resolutie, in dots per inch, van de  RasterImage . |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setRgbColorProfile(StreamSource value)
```


Haalt op of stelt het RGB-kleurprofiel in voor CMYK PSD-afbeeldingen. Moet in combinatie met CmykColorProfile staan voor correcte kleurconversie.

Waarde: Het RGB-kleurprofiel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Haalt de rotatiemodus op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De rotatiemodus. |

### setTransparencyData(boolean value) {#setTransparencyData-boolean-}
```
public final void setTransparencyData(boolean value)
```


Haalt of stelt een waarde in die aangeeft of het eerste alfakanaal de transparantiedata bevat voor het samengevoegde resultaat bij het specificeren van laaggegevens.

Waarde:  true  als het eerste alfakanaal de transparantiedata bevat voor het samengevoegde resultaat bij het specificeren van laaggegevens; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Haalt een waarde op die aangeeft of de afbeelding een transparante kleur heeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


Haalt de transparante kleur van de afbeelding op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of de XMP‑metadata moet worden bijgewerkt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true  als de XMP-metadata wordt bijgewerkt; anders,  false . |

### setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized) {#setUsePhotoshopCompatibilityMode-internalized-boolean-}
```
public void setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| usePhotoshopCompatibilityMode_internalized | boolean |  |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of ruwe gegevensladen moet worden gebruikt wanneer ruwe gegevensladen beschikbaar is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true  als ruwe gegevensladen wordt gebruikt wanneer ruwe gegevensladen beschikbaar is.; anders,  false . |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Stelt de venture-licentie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ventureLicense | java.lang.Object | De venture-licentie. |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Haalt of stelt de versie in.

Waarde: De versie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Haalt of stelt de verticale resolutie, in pixels per inch, van deze [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Haalt op of stelt de XMP-metadata in.

Waarde: De XMP-metadata.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Converteert rasterafbeelding naar de bitmap.

**Returns:**
java.awt.image.BufferedImage - De bitmap
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Schrijft de volledige scanlijn naar de opgegeven scanlijnindex.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scanLineIndex | int | Nulgebaseerde index van de scanlijn. |
| argb32Pixels | int[] | De 32-bit ARGB-kleurenarray om te schrijven. |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Schrijft de volledige scanlijn naar de opgegeven scanlijnindex.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scanLineIndex | int | Nulgebaseerde index van de scanlijn. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | De pixelkleurenarray om te schrijven. |

