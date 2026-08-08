---
title: "Layer"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De PSD-laag."
type: docs
weight: 16
url: /nl/java/com.aspose.psd.fileformats.psd.layers/layer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage)

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Layer extends RasterCachedImage implements Cloneable
```

De PSD-laag.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Layer()](#Layer--) | Initialiseert een nieuw exemplaar van de klasse [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [Layer(RasterImage image)](#Layer-com.aspose.psd.RasterImage-) |  |
| [Layer(RasterImage image, boolean disposeImage)](#Layer-com.aspose.psd.RasterImage-boolean-) | Initialiseert een nieuw exemplaar van de klasse [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [Layer(InputStream stream)](#Layer-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de klasse [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, String name)](#Layer-com.aspose.psd.Rectangle-byte---byte---byte---java.lang.String-) | Initialiseert een nieuw exemplaar van de klasse [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) vanuit byte‑arrays. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [BlendSignature](#BlendSignature) | Geeft de blend-modus handtekening weer. |
| [LayerHeaderSize](#LayerHeaderSize) | De grootte van de laagheader. |
| [OnCreate_internalized](#OnCreate-internalized) | Treedt op wanneer afbeelding werd geladen |
| [OnLoad_internalized](#OnLoad-internalized) | Treedt op wanneer afbeelding werd geladen door createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Treedt op wanneer afbeelding werd geladen of opgeslagen |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Treedt op wanneer krediet werd gebruikt |
| [resources_internalized](#resources-internalized) | De bronnen |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [<T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)](#-T-tryGetResource-internalized-java.lang.Class-T--T---) | Haalt de resource op die is gekoppeld aan het opgegeven type. |
| [addLayerMask(LayerMaskData layerMask)](#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Voegt het masker toe aan de huidige laag. |
| [addResource_internalized(LayerResource resource)](#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Voegt de resource toe. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Aanpassing van de helderheid voor een afbeelding. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Beeldcontrast |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gamma-correctie van een afbeelding. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma-correctie van een afbeelding. |
| [applyLayerMask()](#applyLayerMask--) | Past het laagmasker toe op de laag, en verwijdert vervolgens het masker. |
| [applyLayerState_internalized(LayerState layerState)](#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-) | Past de laagstijlinstelling van de invoer [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) toe op de huidige [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) instantie. |
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
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Converteert naar aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Maakt een nieuwe afbeelding aan met de opgegeven create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Maakt een nieuwe afbeelding aan met de opgegeven afbeeldingen als pagina's. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Maakt een nieuwe afbeelding aan met de opgegeven afbeeldingen als pagina's. |
| [createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) | Maakt een nieuw exemplaar van de [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) klasse aan. |
| [createLayerState_internalized()](#createLayerState-internalized--) | Maakt de nieuwe [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instantie op basis van de huidige [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) waarden. |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
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
| [drawImage(Point location, RasterImage image)](#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-) | Tekent de afbeelding op de laag. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of het opgegeven Object gelijk is aan deze instantie. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filtert de opgegeven rechthoek. |
| [findAssignableResource_internalized(System.Type type)](#findAssignableResource-internalized-com.aspose.ms.System.Type-) | Vindt de toewijsbare bron. |
| [findPattResource_internalized()](#findPattResource-internalized--) | Vindt de  PattResource |
| [findResource_internalized(int typeToolKey)](#findResource-internalized-int-) | Vindt de bron op unieke sleutel. |
| [getAbsoluteBounds_internalized()](#getAbsoluteBounds-internalized--) | Haalt op of stelt de absolute grenzen in. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Haalt een 32-bit ARGB-pixel van de afbeelding op. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Haalt een waarde op die aangeeft of het palet automatisch wordt aangepast. |
| [getBackgroundColor()](#getBackgroundColor--) | Haalt op of stelt een waarde voor de achtergrondkleur in. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Haalt het aantal bits per pixel van de afbeelding op. |
| [getBlendClippedElements()](#getBlendClippedElements--) | Haalt op of stelt de menging van het bijgesneden element in. |
| [getBlendModeKey()](#getBlendModeKey--) | Haalt op of stelt de sleutel van de mengmodus in. |
| [getBlendModeSignature()](#getBlendModeSignature--) | Haalt de handtekening van de mengmodus op. |
| [getBlendingOptions()](#getBlendingOptions--) | Haalt de mengopties op. |
| [getBottom()](#getBottom--) | Haalt op of stelt de positie van de onderste laag in. |
| [getBounds()](#getBounds--) | Haalt de grenzen van de afbeelding op. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Haalt de buffer‑groottehint op, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [getBytesPerRowForFullMask_internalized(int bitDepth)](#getBytesPerRowForFullMask-internalized-int-) | Haalt de bytes per rij op voor volledige maskermodus. |
| [getBytesPerRowForMask_internalized(int bitDepth)](#getBytesPerRowForMask-internalized-int-) | Haalt de bytes per rij op. |
| [getBytesPerRow_internalized(int bitDepth)](#getBytesPerRow-internalized-int-) | Haalt de bytes per rij op. |
| [getChannelInformation()](#getChannelInformation--) | Haalt de kanaalinformatie op of stelt deze in. |
| [getChannelsCount()](#getChannelsCount--) | Haalt het aantal kanalen van de laag op. |
| [getClass()](#getClass--) |  |
| [getClipping()](#getClipping--) | Haalt de laagknipping op of stelt deze in. |
| [getContainer()](#getContainer--) | Haalt de Image-container op. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Haalt de gegevensstroom van het object op. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Haalt het diep aangepast palet op. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Haalt de standaard 32-bit ARGB-pixelarray op. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Haalt de standaardopties op. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Haalt de standaard pixelarray op met behulp van een gedeeltelijke pixelloader. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Haalt de standaard ruwe gegevensarray op met behulp van een gedeeltelijke pixelloader. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Haalt de standaard ruwe gegevensarray op. |
| [getDisplayName()](#getDisplayName--) | Haalt de weergavenaam van de laag op. |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getExtraLength()](#getExtraLength--) | Haalt de extra informatielengte van de laag in bytes op. |
| [getFileFormat()](#getFileFormat--) | Haalt een waarde van bestandsformaat op |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Haalt het bestandsformaat op. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Haalt het bestandsformaat op. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Haalt het bestandsformaat op. |
| [getFillOpacity()](#getFillOpacity--) | Haalt de vulopaciteit op of stelt deze in. |
| [getFiller()](#getFiller--) | Haalt de laagvuller op of stelt deze in. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [getFlags()](#getFlags--) | Haalt de laagvlaggen op of stelt deze in. |
| [getFoldersHierarchy_internalized()](#getFoldersHierarchy-internalized--) | Haalt de lijst op van de mappenhiërarchie van [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) van de huidige laag. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Haalt palet op van formatspecifieke locaties |
| [getGUID_internalized()](#getGUID-internalized--) | Haalt de unieke identifier op van deze Layer‑instantie. |
| [getHeader_internalized()](#getHeader-internalized--) | Haalt op of stelt de header in. |
| [getHeight()](#getHeight--) | Haalt de afbeeldingshoogte op. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Haalt op of stelt de horizontale resolutie, in pixels per inch, van deze  RasterImage . |
| [getImageOpacity()](#getImageOpacity--) | Haalt de dekking op van deze afbeelding. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Haalt de interne data‑transformator op. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Haalt de interrupt‑monitor op. |
| [getLayerBlendingRangesData()](#getLayerBlendingRangesData--) | Haalt op of stelt de laag‑blending‑bereiken‑gegevens in. |
| [getLayerCreationDateTime()](#getLayerCreationDateTime--) | Haalt op of stelt de aanmaakdatum‑tijd van de laag in. |
| [getLayerCreationDateTime_internalized()](#getLayerCreationDateTime-internalized--) |  |
| [getLayerLock()](#getLayerLock--) | Haalt op of stelt de laagvergrendeling in. |
| [getLayerMaskData()](#getLayerMaskData--) | Haalt op of stelt de laagmaskergegevens in. |
| [getLayerOptions()](#getLayerOptions--) | Haalt de laagopties op. |
| [getLayerPalette_internalized()](#getLayerPalette-internalized--) | Haalt op of stelt het laagpalet in. |
| [getLayerType_internalized()](#getLayerType-internalized--) | Haalt het type van de laag op. |
| [getLeft()](#getLeft--) | Haalt op of stelt de linkse laagpositie in. |
| [getLength()](#getLength--) | Haalt de totale laaglengte in bytes op. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Haalt op of stelt de maximaal toegestane toewijzing voor gedeeltelijke rotatie‑opslaan in. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Haalt de geheugenbeheerder op. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Haalt de datum en tijd op waarop de resource‑afbeelding voor het laatst is gewijzigd. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getName()](#getName--) | Haalt op of stelt de laagnaam in. |
| [getOpacity()](#getOpacity--) | Haalt op of stelt de laagdekking in. |
| [getOpacityTotal_internalized()](#getOpacityTotal-internalized--) | Haalt de totale dekking op. |
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
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Haalt de aangepaste kleurconverter op of stelt deze in |
| [getRawDataFormat()](#getRawDataFormat--) | Haalt het ruwe gegevensformaat op. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Haalt de fallback‑index op of stelt deze in die moet worden gebruikt wanneer de paletindex buiten bereik is |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Haalt de geïndexeerde kleurconverter op of stelt deze in |
| [getRawLineSize()](#getRawLineSize--) | Haalt de ruwe regelgrootte in bytes op. |
| [getResources()](#getResources--) | Haalt de laagbronnen op of stelt deze in. |
| [getRight()](#getRight--) | Haalt de positie van de rechterlaag op of stelt deze in. |
| [getRotateMode()](#getRotateMode--) | Haalt de rotatiemodus op of stelt deze in. |
| [getSheetColorHighlight()](#getSheetColorHighlight--) | Haalt de decoratieve bladkleurmarkering in de lagenlijst op of stelt deze in |
| [getSize()](#getSize--) | Haalt de afbeeldingsgrootte op. |
| [getSkewAngle()](#getSkewAngle--) | Haalt de scheefstandhoek op. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Haalt het bestandspad van de bronafbeelding op als deze bestaat. |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Haalt de synchronisatiewortel op. |
| [getTop()](#getTop--) | Haalt de positie van de bovenste laag op of stelt deze in. |
| [getTransparentColor()](#getTransparentColor--) | Haalt de transparante kleur van de afbeelding op. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Haalt een waarde op of stelt deze in die aangeeft of de XMP‑metadata moet worden bijgewerkt. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Haalt een waarde op die aangeeft of het object een geheugenoptimalisatiestrategie gebruikt |
| [getUseRawData()](#getUseRawData--) | Haalt op of stelt een waarde in die aangeeft of ruwe gegevensladen moet worden gebruikt wanneer ruwe gegevensladen beschikbaar is. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Haalt de gebruikte palet op. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Haalt de venture-licentie op. |
| [getVerticalResolution()](#getVerticalResolution--) | Haalt op of stelt de verticale resolutie, in pixels per inch, van deze RasterImage in. |
| [getWidth()](#getWidth--) | Haalt de breedte van de afbeelding op. |
| [getXmpData()](#getXmpData--) | Haalt op of stelt de XMP-metadata in. |
| [grayscale()](#grayscale--) | Transformatie van een afbeelding naar zijn grijswaardenrepresentatie |
| [hasAlpha()](#hasAlpha--) | Haalt een waarde op die aangeeft of deze instantie alfa heeft. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Haalt een waarde op die aangeeft of de afbeelding een achtergrondkleur heeft. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Haalt op of stelt een waarde in die aangeeft of deze afbeelding-instantie is gewijzigd na het laden. |
| [hasTransparentColor()](#hasTransparentColor--) | Haalt een waarde op die aangeeft of de afbeelding een transparante kleur heeft. |
| [hashCode()](#hashCode--) | Retourneert een hashcode voor dit exemplaar. |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Haalt op of stelt de maximale voortgangswaarde in |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Geeft de voortgang aan. |
| [insertResource_internalized(int index, LayerResource resource)](#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Voeg een bron toe aan de Resources-collectie. |
| [isCached()](#isCached--) | Haalt een waarde op die aangeeft of afbeeldingsgegevens momenteel in de cache staan. |
| [isLayerValid_internalized()](#isLayerValid-internalized--) | Detecteert of de laag geldig is voor opslaan naar een bestand. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Haalt een waarde op die aangeeft of ruwe gegevensladen beschikbaar is. |
| [isUsePalette()](#isUsePalette--) | Haalt een waarde op die aangeeft of de afbeeldingspalet wordt gebruikt. |
| [isVisible()](#isVisible--) | Haalt op of stelt een waarde in die aangeeft of de laag zichtbaar is |
| [isVisibleInGroup()](#isVisibleInGroup--) | Haalt een waarde op die aangeeft of deze instantie zichtbaar is in groep (Als de laag niet in een groep zit, betekent dit de hoofdgroep). |
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
| [mergeLayerTo(Layer layerToMergeInto)](#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-) | Voegt de laag samen met de opgegeven laag |
| [normalizeAngle()](#normalizeAngle--) | Normaliseert de hoek. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normaliseert de hoek. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Roep aan wanneer de container van deze  Image  is ingesteld. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Leest de volledige scanlijn op basis van de opgegeven scanlijnindex. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Leest de volledige scanlijn op basis van de opgegeven scanlijnindex. |
| [removeResource_internalized(LayerResource resource)](#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Verwijdert de bron. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Vervangt alle niet-transparante kleuren door een nieuwe kleur en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Vervangt alle niet-transparante kleuren door een nieuwe kleur en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Wijzigt de grootte van de afbeelding. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Wijzigt de grootte van de afbeelding. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Wijzigt de grootte van de afbeelding. |
| [resizeChannelsData_internalized(Rectangle rect)](#resizeChannelsData-internalized-com.aspose.psd.Rectangle-) | Wijzigt de grootte van de kanaalgegevens |
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
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Slaat de gegevens van het object op in de opgegeven stream. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)](#save-internalized-com.aspose.psd.StreamContainer-int-int-) | Slaat gegevens op in de opgegeven streamcontainer. |
| [setAbsoluteBounds_internalized(Rectangle value)](#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-) | Haalt op of stelt de absolute grenzen in. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Stelt een afbeelding 32-bit ARGB-pixel in voor de opgegeven positie. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Stelt een waarde in die aangeeft of de palet automatisch wordt aangepast. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Haalt op of stelt een waarde in die aangeeft of de afbeelding een achtergrondkleur heeft. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Haalt op of stelt een waarde voor de achtergrondkleur in. |
| [setBlendClippedElements(boolean value)](#setBlendClippedElements-boolean-) | Haalt op of stelt de menging van het bijgesneden element in. |
| [setBlendModeKey(long value)](#setBlendModeKey-long-) | Haalt op of stelt de sleutel van de mengmodus in. |
| [setBottom(int value)](#setBottom-int-) | Haalt op of stelt de positie van de onderste laag in. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Stelt de buffergroottehint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [setChannelInformation(ChannelInformation[] value)](#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Haalt de kanaalinformatie op of stelt deze in. |
| [setClipping(byte value)](#setClipping-byte-) | Haalt de laagknipping op of stelt deze in. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Stelt de  Image  container in. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Stelt de data loader direct in. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Stelt de gegevensstroom van het object in. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Haalt op of stelt de weergavenaam van de laag in. |
| [setFillOpacity(int value)](#setFillOpacity-int-) | Haalt de vulopaciteit op. |
| [setFiller(byte value)](#setFiller-byte-) | Haalt de laagvuller op of stelt deze in. |
| [setFlags(byte value)](#setFlags-byte-) | Haalt de laagvlaggen op of stelt deze in. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Stelt palette in op formaat‑specifieke plaatsen |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Haalt op of stelt de header in. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Haalt op of stelt de horizontale resolutie, in pixels per inch, van deze  RasterImage . |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Stelt een waarde in die aangeeft of [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze afbeelding-instantie is gewijzigd na het laden. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Stelt de interne data transformer in. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Stelt de interrupt monitor in. |
| [setLayerBlendingRangesData(LayerBlendingRangesData value)](#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-) | Haalt op of stelt de laag‑blending‑bereiken‑gegevens in. |
| [setLayerCreationDateTime(Date value)](#setLayerCreationDateTime-java.util.Date-) | Haalt op of stelt de aanmaakdatum‑tijd van de laag in. |
| [setLayerCreationDateTime_internalized(System.DateTime value)](#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-) |  |
| [setLayerLock(int value)](#setLayerLock-int-) | Haalt op of stelt de laagvergrendeling in (Let op dat als de vlag LayerFlags.TransparencyProtected is ingesteld, deze wordt overschreven door de laagvergrendelingsvlag. |
| [setLayerMaskData(LayerMaskData value)](#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Haalt op of stelt de laagmaskergegevens in. |
| [setLayerPalette_internalized(IColorPalette value)](#setLayerPalette-internalized-com.aspose.psd.IColorPalette-) | Haalt op of stelt het laagpalet in. |
| [setLeft(int value)](#setLeft-int-) | Haalt op of stelt de linkse laagpositie in. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Haalt op of stelt de maximaal toegestane toewijzing voor gedeeltelijke rotatie‑opslaan in. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Stelt de geheugenbeheerder in. |
| [setName(String name)](#setName-java.lang.String-) | Stelt de laagnaam in. |
| [setName_internalized(String value)](#setName-internalized-java.lang.String-) | Haalt op of stelt de laagnaam in. |
| [setOpacity(byte value)](#setOpacity-byte-) | Haalt op of stelt de laagdekking in. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Stelt het kleurenpalet in. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Stelt het afbeeldingspalet in. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Stelt een afbeeldingspixel in voor de opgegeven positie. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of de afbeeldingscomponenten moeten worden voorvermenigvuldigd. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Haalt de aangepaste kleurconverter op of stelt deze in |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Haalt de fallback‑index op of stelt deze in die moet worden gebruikt wanneer de paletindex buiten bereik is |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Haalt de geïndexeerde kleurconverter op of stelt deze in |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Stelt de resolutie in voor deze  RasterImage . |
| [setResources(LayerResource[] value)](#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Haalt de laagbronnen op of stelt deze in. |
| [setRight(int value)](#setRight-int-) | Haalt de positie van de rechterlaag op of stelt deze in. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Haalt de rotatiemodus op of stelt deze in. |
| [setSheetColorHighlight(short value)](#setSheetColorHighlight-short-) | Haalt de decoratieve bladkleurmarkering in de lagenlijst op of stelt deze in |
| [setTop(int value)](#setTop-int-) | Haalt de positie van de bovenste laag op of stelt deze in. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Haalt een waarde op die aangeeft of de afbeelding een transparante kleur heeft. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Haalt de transparante kleur van de afbeelding op. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of de XMP‑metadata moet worden bijgewerkt. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Haalt op of stelt een waarde in die aangeeft of ruwe gegevensladen moet worden gebruikt wanneer ruwe gegevensladen beschikbaar is. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Alle Aspose-producten moeten deze methode implementeren. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Haalt op of stelt de verticale resolutie, in pixels per inch, van deze RasterImage in. |
| [setVisible(boolean value)](#setVisible-boolean-) | Haalt op of stelt een waarde in die aangeeft of de laag zichtbaar is |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Haalt op of stelt de XMP-metadata in. |
| [shallowCopy()](#shallowCopy--) | Maakt een ondiepe kopie van de huidige Layer. |
| [toBitmap()](#toBitmap--) | Converteert rasterafbeelding naar de bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [updateBlendingOptions_internalized(PattResource pattResource)](#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Werkt de mengopties bij nadat de laag of globale bronnen zijn gewijzigd. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Schrijft de volledige scanlijn naar de opgegeven scanlijnindex. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Schrijft de volledige scanlijn naar de opgegeven scanlijnindex. |
### Layer() {#Layer--}
```
public Layer()
```


Initialiseert een nieuw exemplaar van de klasse [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). Constructor voor lui initialisatie.

### Layer(RasterImage image) {#Layer-com.aspose.psd.RasterImage-}
```
public Layer(RasterImage image)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) |  |

### Layer(RasterImage image, boolean disposeImage) {#Layer-com.aspose.psd.RasterImage-boolean-}
```
public Layer(RasterImage image, boolean disposeImage)
```


Initialiseert een nieuw exemplaar van de klasse [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | De afbeelding. |
| disposeImage | boolean | indien ingesteld op  true  [dispose image]. |

### Layer(InputStream stream) {#Layer-java.io.InputStream-}
```
public Layer(InputStream stream)
```


Initialiseert een nieuw exemplaar van de klasse [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De afbeeldingsstroom |

### Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, String name) {#Layer-com.aspose.psd.Rectangle-byte---byte---byte---java.lang.String-}
```
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, String name)
```


Initialiseert een nieuw exemplaar van de klasse [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) vanuit byte‑arrays.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | De laaggrenzen. |
| redBytes | byte[] | De rode bytes. |
| greenBytes | byte[] | De groene bytes. |
| blueBytes | byte[] | De blauwe bytes. |
| naam | java.lang.String | De laagnaam. |

### BlendSignature {#BlendSignature}
```
public static final int BlendSignature
```


Geeft de blend-modus handtekening weer.

### LayerHeaderSize {#LayerHeaderSize}
```
public static final int LayerHeaderSize
```


De grootte van de laagheader.

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

### resources_internalized {#resources-internalized}
```
public ResourceNest resources_internalized
```


De bronnen

### <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource) {#-T-tryGetResource-internalized-java.lang.Class-T--T---}
```
public final boolean <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)
```


Haalt de resource op die is gekoppeld aan het opgegeven type.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | resource | T[] | Wanneer deze methode terugkeert, bevat deze de resource die geassocieerd is met het opgegeven sleuteltype, als de sleutel wordt gevonden; anders wordt null geretourneerd. |

T : Het sleuteltype van de op te halen waarde. |

**Returns:**
boolean -   als er een resource met het opgegeven type aanwezig is; anders,  .
### addLayerMask(LayerMaskData layerMask) {#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void addLayerMask(LayerMaskData layerMask)
```


Voegt het masker toe aan de huidige laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layerMask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Het laagmasker. |

### addResource_internalized(LayerResource resource) {#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void addResource_internalized(LayerResource resource)
```


Voegt de resource toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | De resource. |

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

### applyLayerMask() {#applyLayerMask--}
```
public final void applyLayerMask()
```


Past het laagmasker toe op de laag, en verwijdert vervolgens het masker.

### applyLayerState_internalized(LayerState layerState) {#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-}
```
public final void applyLayerState_internalized(LayerState layerState)
```


Past de laagstijlinstelling van de invoer [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) toe op de huidige [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layerState | [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) | De laagstatus met nieuwe stijl. |

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
### createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static Layer createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)
```


Maakt een nieuw exemplaar van de [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) klasse aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| koptekst | com.aspose.internal.fileformats.psd.sections.PsdHeader | De koptekst. |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het palet. |
| linkedLayersRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry | De LinkedLayersRegistry. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Returns the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class.
### createLayerState_internalized() {#createLayerState-internalized--}
```
public final LayerState createLayerState_internalized()
```


Maakt de nieuwe [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instantie op basis van de huidige [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) waarden.

**Returns:**
[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) - The new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values.
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
public static Layer create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
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

### drawImage(Point location, RasterImage image) {#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-}
```
public final void drawImage(Point location, RasterImage image)
```


Tekent de afbeelding op de laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | De locatie. |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | De afbeelding. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of het opgegeven Object gelijk is aan deze instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te vergelijken met deze instantie. |

**Returns:**
boolean - true als het opgegeven Object gelijk is aan deze instantie; anders false.
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

### findAssignableResource_internalized(System.Type type) {#findAssignableResource-internalized-com.aspose.ms.System.Type-}
```
public final LayerResource findAssignableResource_internalized(System.Type type)
```


Vindt de toewijsbare bron.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | com.aspose.ms.System.Type | Het type. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - 
### findPattResource_internalized() {#findPattResource-internalized--}
```
public final PattResource findPattResource_internalized()
```


Vindt de  PattResource

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - The found resource or null
### findResource_internalized(int typeToolKey) {#findResource-internalized-int-}
```
public final LayerResource findResource_internalized(int typeToolKey)
```


Vindt de bron op unieke sleutel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeToolKey | int | De typegereedschapssleutel. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - Found resource or null
### getAbsoluteBounds_internalized() {#getAbsoluteBounds-internalized--}
```
public final Rectangle getAbsoluteBounds_internalized()
```


Haalt op of stelt de absolute grenzen in.

Waarde: De absolute grenzen.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Haalt het aantal bits per pixel van de afbeelding op.

Waarde: Het aantal bits per pixel van de afbeelding.

**Returns:**
int
### getBlendClippedElements() {#getBlendClippedElements--}
```
public final boolean getBlendClippedElements()
```


Haalt op of stelt de menging van het bijgesneden element in.

Waarde: Het mengen van het bijgesneden element.

**Returns:**
boolean
### getBlendModeKey() {#getBlendModeKey--}
```
public long getBlendModeKey()
```


Haalt op of stelt de sleutel van de mengmodus in.

Waarde: De blend-modus sleutel.

**Returns:**
long
### getBlendModeSignature() {#getBlendModeSignature--}
```
public final int getBlendModeSignature()
```


Haalt de handtekening van de mengmodus op.

Waarde: De blend-modus handtekening.

**Returns:**
int
### getBlendingOptions() {#getBlendingOptions--}
```
public final BlendingOptions getBlendingOptions()
```


Haalt de mengopties op.

Waarde: De mengopties.

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
### getBottom() {#getBottom--}
```
public int getBottom()
```


Haalt op of stelt de positie van de onderste laag in.

Waarde: De positie van de onderste laag.

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
### getBytesPerRowForFullMask_internalized(int bitDepth) {#getBytesPerRowForFullMask-internalized-int-}
```
public final int getBytesPerRowForFullMask_internalized(int bitDepth)
```


Haalt de bytes per rij op voor volledige maskermodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitDepth | int | De bitsdiepte. |

**Returns:**
int - Bytes nodig voor het opslaan van 1 rij
### getBytesPerRowForMask_internalized(int bitDepth) {#getBytesPerRowForMask-internalized-int-}
```
public final int getBytesPerRowForMask_internalized(int bitDepth)
```


Haalt de bytes per rij op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitDepth | int | De bitsdiepte. |

**Returns:**
int - Bytes nodig voor het opslaan van 1 rij
### getBytesPerRow_internalized(int bitDepth) {#getBytesPerRow-internalized-int-}
```
public final int getBytesPerRow_internalized(int bitDepth)
```


Haalt de bytes per rij op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitDepth | int | De bitsdiepte. |

**Returns:**
int - Bytes nodig voor het opslaan van 1 rij
### getChannelInformation() {#getChannelInformation--}
```
public final ChannelInformation[] getChannelInformation()
```


Haalt de kanaalinformatie op of stelt deze in.

Waarde: De kanaalinformatie.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Haalt het aantal kanalen van de laag op.

Waarde: Het aantal kanalen van de laag.

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


Haalt of stelt de laag‑clipping in. 0 = basis, 1 = niet‑basis.

Waarde: De laag‑clipping.

**Returns:**
byte
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Haalt de Image-container op.

Waarde: De  Image  container.

Als deze eigenschap niet null is, geeft dit aan dat de afbeelding zich binnen een andere afbeelding bevindt.

**Returns:**
[Image](../../com.aspose.psd/image)
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
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Haalt de weergavenaam van de laag op.

Waarde: De weergavenaam van de laag.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Haalt een waarde op die aangeeft of deze instantie is vrijgegeven.

**Returns:**
boolean -  true  als vrijgegeven; anders,  false .
### getExtraLength() {#getExtraLength--}
```
public final int getExtraLength()
```


Haalt de extra informatielengte van de laag in bytes op.

Waarde: De extra laaglengte.

**Returns:**
int
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
### getFillOpacity() {#getFillOpacity--}
```
public final int getFillOpacity()
```


Haalt de vulopaciteit op of stelt deze in.

**Returns:**
int
### getFiller() {#getFiller--}
```
public final byte getFiller()
```


Haalt de laagvuller op of stelt deze in.

Waarde: de laagvuller.

**Returns:**
byte
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
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Haalt de laagvlaggen op of stelt ze in. bit 0 = transparantie beschermd; bit 1 = zichtbaar; bit 2 = verouderd; bit 3 = 1 voor Photoshop 5.0 en later, geeft aan of bit 4 nuttige informatie bevat; bit 4 = pixelgegevens irrelevant voor het uiterlijk van het document.

Waarde: de laagvlaggen.

**Returns:**
byte
### getFoldersHierarchy_internalized() {#getFoldersHierarchy-internalized--}
```
public final System.Collections.Generic.List<Layer> getFoldersHierarchy_internalized()
```


Haalt de lijst op van de mappenhiërarchie van [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) van de huidige laag.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.Layer> - Retourneert de lijst van [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) maphiërarchie van de huidige laag.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Haalt palet op van formatspecifieke locaties

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGUID_internalized() {#getGUID-internalized--}
```
public final String getGUID_internalized()
```


Haalt de unieke identifier op van deze Layer‑instantie.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Haalt op of stelt de header in.

Waarde: de header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
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


Haalt op of stelt de horizontale resolutie, in pixels per inch, van deze  RasterImage .

**Returns:**
double - De horizontale resolutie.

Opmerking: standaard is deze waarde altijd 96 omdat verschillende platforms de schermresolutie niet kunnen retourneren. U kunt overwegen de SetResolution-methode te gebruiken om beide resolutiewaarden in één oproep bij te werken.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Haalt de dekking op van deze afbeelding.

**Returns:**
float - De opaciteitswaarde tussen 0,0 (volledig transparant) en 1,0 (volledig ondoorzichtig).
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
### getLayerBlendingRangesData() {#getLayerBlendingRangesData--}
```
public final LayerBlendingRangesData getLayerBlendingRangesData()
```


Haalt op of stelt de laag‑blending‑bereiken‑gegevens in.

Waarde: de gegevens van de laagmengselbereiken.

**Returns:**
[LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata)
### getLayerCreationDateTime() {#getLayerCreationDateTime--}
```
public final Date getLayerCreationDateTime()
```


Haalt op of stelt de aanmaakdatum‑tijd van de laag in.

Waarde: de aanmaakdatum en -tijd van de laag. Als er geen gegevens over de aanmaak‑DateTime zijn, wordt de Unix‑tijd van de eerste epoch geretourneerd.

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


Haalt de laagvergrendeling op of stelt deze in. Opmerking: als de vlag LayerFlags.TransparencyProtected is ingesteld, wordt deze overschreven door de laagvergrendelingsvlag. Om de vlag LayerFlags.TransparencyProtected terug te geven, moet deze worden toegepast op de laagoptie layer.Flags |= LayerFlags.TransparencyProtected.

Waarde: de laagvergrendeling.

**Returns:**
int
### getLayerMaskData() {#getLayerMaskData--}
```
public final LayerMaskData getLayerMaskData()
```


Haalt op of stelt de laagmaskergegevens in.

Waarde: de laagmaskergegevens.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
### getLayerOptions() {#getLayerOptions--}
```
public final PsdOptions getLayerOptions()
```


Haalt de laagopties op.

Waarde: de laagopties.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)
### getLayerPalette_internalized() {#getLayerPalette-internalized--}
```
public final IColorPalette getLayerPalette_internalized()
```


Haalt op of stelt het laagpalet in.

Waarde: De laagpalet.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getLayerType_internalized() {#getLayerType-internalized--}
```
public byte getLayerType_internalized()
```


Haalt het type van de laag op.

Waarde: Het type van de laag.

**Returns:**
byte
### getLeft() {#getLeft--}
```
public int getLeft()
```


Haalt op of stelt de linkse laagpositie in.

Waarde: De linkse laagpositie.

**Returns:**
int
### getLength() {#getLength--}
```
public final long getLength()
```


Haalt de totale laaglengte in bytes op.

**Returns:**
long
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
### getName() {#getName--}
```
public final String getName()
```


Haalt op of stelt de laagnaam in.

Waarde: De laagnaam.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Haalt op of stelt de laagopaciteit in. 0 = transparant, 255 = ondoorzichtig.

Waarde: De laagopaciteit.

**Returns:**
byte
### getOpacityTotal_internalized() {#getOpacityTotal-internalized--}
```
public final byte getOpacityTotal_internalized()
```


Haalt de totale opaciteit op. De totale opaciteit is het product van de Laagopaciteit en de Laagvullingsopaciteit. Het wordt gebruikt voor laagblending.

Waarde: De totale opaciteit.

**Returns:**
byte
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

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
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
### getResources() {#getResources--}
```
public final LayerResource[] getResources()
```


Haalt de laagbronnen op of stelt deze in.

Waarde: De laagbronnen.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getRight() {#getRight--}
```
public int getRight()
```


Haalt de positie van de rechterlaag op of stelt deze in.

Waarde: De juiste laagpositie.

**Returns:**
int
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Haalt de rotatiemodus op of stelt deze in.

**Returns:**
int - De rotatiemodus.
### getSheetColorHighlight() {#getSheetColorHighlight--}
```
public final short getSheetColorHighlight()
```


Haalt de decoratieve bladkleurmarkering in de lagenlijst op of stelt deze in

Waarde: De bladkleurmarkering.

**Returns:**
short
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
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Haalt het bestandspad van de bronafbeelding op als deze bestaat. Retourneert een lege string als het bronpad niet kan worden gevonden.

**Returns:**
java.lang.String - Het bestandspad van de bronafbeelding.
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Haalt de synchronisatiewortel op.

Waarde: De synchronisatiewortel.

**Returns:**
java.lang.Object
### getTop() {#getTop--}
```
public int getTop()
```


Haalt de positie van de bovenste laag op of stelt deze in.

Waarde: De bovenste laagpositie.

**Returns:**
int
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
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Haalt op of stelt de verticale resolutie, in pixels per inch, van deze RasterImage in.

**Returns:**
double - De verticale resolutie.

Opmerking: standaard is deze waarde altijd 96 omdat verschillende platforms de schermresolutie niet kunnen retourneren. U kunt overwegen de SetResolution-methode te gebruiken om beide resolutiewaarden in één oproep bij te werken.
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

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformatie van een afbeelding naar zijn grijswaardenrepresentatie

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Haalt een waarde op die aangeeft of deze instantie alfa heeft.

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

**Returns:**
boolean -  true  als deze instantie een gewijzigde afbeelding heeft; anders,  false .
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Haalt een waarde op die aangeeft of de afbeelding een transparante kleur heeft.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor dit exemplaar.

**Returns:**
int - Een hashcode voor deze instantie, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel.
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

### insertResource_internalized(int index, LayerResource resource) {#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void insertResource_internalized(int index, LayerResource resource)
```


Voeg een bron toe aan de Resources-collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de resource die moet worden ingevoegd. |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | De resource die moet worden ingevoegd. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Haalt een waarde op die aangeeft of afbeeldingsgegevens momenteel in de cache staan.

**Returns:**
boolean -  true  als afbeeldingsgegevens in de cache staan; anders,  false .
### isLayerValid_internalized() {#isLayerValid-internalized--}
```
public boolean isLayerValid_internalized()
```


Detecteert of de laag geldig is voor opslaan naar een bestand.

**Returns:**
boolean -
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
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Haalt op of stelt een waarde in die aangeeft of de laag zichtbaar is

Waarde:  true  als deze instantie zichtbaar is; anders,  false .

**Returns:**
boolean
### isVisibleInGroup() {#isVisibleInGroup--}
```
public boolean isVisibleInGroup()
```


Haalt een waarde op die aangeeft of deze instantie zichtbaar is in groep (Als de laag niet in een groep zit, betekent dit de hoofdgroep).

Waarde:  true  als deze instantie zichtbaar is in de groep; anders,  false .

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
### mergeLayerTo(Layer layerToMergeInto) {#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public void mergeLayerTo(Layer layerToMergeInto)
```


Voegt de laag samen met de opgegeven laag

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layerToMergeInto | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | De laag om in te voegen. |

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


Roep aan wanneer de container van deze  Image  is ingesteld.

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
### removeResource_internalized(LayerResource resource) {#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void removeResource_internalized(LayerResource resource)
```


Verwijdert de bron.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | De resource. |

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

### resizeChannelsData_internalized(Rectangle rect) {#resizeChannelsData-internalized-com.aspose.psd.Rectangle-}
```
public void resizeChannelsData_internalized(Rectangle rect)
```


Wijzigt de grootte van de kanaalgegevens

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Het rect. |

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

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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

### save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dstStream | java.io.OutputStream | De stream om de gegevens van de afbeelding op te slaan. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opslagopties. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek met de grenzen van de doelafbeelding. Stel de lege rechthoek in om de brongrenzen te gebruiken. |

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

### save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth) {#save-internalized-com.aspose.psd.StreamContainer-int-int-}
```
public final void save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)
```


Slaat gegevens op in de opgegeven streamcontainer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |
| psdVersion | int | De PSD-versie. |
| bitDepth | int | De bitsdiepte. |

### setAbsoluteBounds_internalized(Rectangle value) {#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setAbsoluteBounds_internalized(Rectangle value)
```


Haalt op of stelt de absolute grenzen in.

Waarde: De absolute grenzen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

### setBlendClippedElements(boolean value) {#setBlendClippedElements-boolean-}
```
public final void setBlendClippedElements(boolean value)
```


Haalt op of stelt de menging van het bijgesneden element in.

Waarde: Het mengen van het bijgesneden element.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setBlendModeKey(long value) {#setBlendModeKey-long-}
```
public void setBlendModeKey(long value)
```


Haalt op of stelt de sleutel van de mengmodus in.

Waarde: De blend-modus sleutel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Haalt op of stelt de positie van de onderste laag in.

Waarde: De positie van de onderste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

### setChannelInformation(ChannelInformation[] value) {#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public final void setChannelInformation(ChannelInformation[] value)
```


Haalt de kanaalinformatie op of stelt deze in.

Waarde: De kanaalinformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) |  |

### setClipping(byte value) {#setClipping-byte-}
```
public final void setClipping(byte value)
```


Haalt of stelt de laag‑clipping in. 0 = basis, 1 = niet‑basis.

Waarde: De laag‑clipping.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

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

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Haalt op of stelt de weergavenaam van de laag in.

Waarde: De weergavenaam van de laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setFillOpacity(int value) {#setFillOpacity-int-}
```
public final void setFillOpacity(int value)
```


Haalt de vulopaciteit op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setFiller(byte value) {#setFiller-byte-}
```
public final void setFiller(byte value)
```


Haalt de laagvuller op of stelt deze in.

Waarde: de laagvuller.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Haalt de laagvlaggen op of stelt ze in. bit 0 = transparantie beschermd; bit 1 = zichtbaar; bit 2 = verouderd; bit 3 = 1 voor Photoshop 5.0 en later, geeft aan of bit 4 nuttige informatie bevat; bit 4 = pixelgegevens irrelevant voor het uiterlijk van het document.

Waarde: de laagvlaggen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

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
### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Haalt op of stelt de header in.

Waarde: de header.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Haalt op of stelt de horizontale resolutie, in pixels per inch, van deze  RasterImage .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De horizontale resolutie. |

Opmerking: standaard is deze waarde altijd 96 omdat verschillende platforms de schermresolutie niet kunnen retourneren. U kunt overwegen de SetResolution-methode te gebruiken om beide resolutiewaarden in één oproep bij te werken. |

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

### setLayerBlendingRangesData(LayerBlendingRangesData value) {#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-}
```
public final void setLayerBlendingRangesData(LayerBlendingRangesData value)
```


Haalt op of stelt de laag‑blending‑bereiken‑gegevens in.

Waarde: de gegevens van de laagmengselbereiken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata) |  |

### setLayerCreationDateTime(Date value) {#setLayerCreationDateTime-java.util.Date-}
```
public final void setLayerCreationDateTime(Date value)
```


Haalt op of stelt de aanmaakdatum‑tijd van de laag in.

Waarde: de aanmaakdatum en -tijd van de laag. Als er geen gegevens over de aanmaak‑DateTime zijn, wordt de Unix‑tijd van de eerste epoch geretourneerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Date |  |

### setLayerCreationDateTime_internalized(System.DateTime value) {#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-}
```
public final void setLayerCreationDateTime_internalized(System.DateTime value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.ms.System.DateTime |  |

### setLayerLock(int value) {#setLayerLock-int-}
```
public final void setLayerLock(int value)
```


Haalt op of stelt de laagvergrendeling in (Opmerking: als de vlag LayerFlags.TransparencyProtected is ingesteld, wordt deze overschreven door de laagvergrendelingsvlag. Om de vlag LayerFlags.TransparencyProtected terug te geven, moet deze worden toegepast op de laagoptie layer.Flags |= LayerFlags.TransparencyProtected

Waarde: de laagvergrendeling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setLayerMaskData(LayerMaskData value) {#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void setLayerMaskData(LayerMaskData value)
```


Haalt op of stelt de laagmaskergegevens in.

Waarde: de laagmaskergegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) |  |

### setLayerPalette_internalized(IColorPalette value) {#setLayerPalette-internalized-com.aspose.psd.IColorPalette-}
```
public final void setLayerPalette_internalized(IColorPalette value)
```


Haalt op of stelt het laagpalet in.

Waarde: De laagpalet.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Haalt op of stelt de linkse laagpositie in.

Waarde: De linkse laagpositie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

### setName(String name) {#setName-java.lang.String-}
```
public final void setName(String name)
```


Stelt de laagnaam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De laagnaam. |

### setName_internalized(String value) {#setName-internalized-java.lang.String-}
```
public final void setName_internalized(String value)
```


Haalt op of stelt de laagnaam in.

Waarde: De laagnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Haalt op of stelt de laagopaciteit in. 0 = transparant, 255 = ondoorzichtig.

Waarde: De laagopaciteit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

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


Stelt de resolutie in voor deze  RasterImage .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dpiX | double | De horizontale resolutie, in dots per inch, van de  RasterImage . |
| dpiY | double | De verticale resolutie, in dots per inch, van de  RasterImage . |

### setResources(LayerResource[] value) {#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setResources(LayerResource[] value)
```


Haalt de laagbronnen op of stelt deze in.

Waarde: De laagbronnen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Haalt de positie van de rechterlaag op of stelt deze in.

Waarde: De juiste laagpositie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Haalt de rotatiemodus op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De rotatiemodus. |

### setSheetColorHighlight(short value) {#setSheetColorHighlight-short-}
```
public final void setSheetColorHighlight(short value)
```


Haalt de decoratieve bladkleurmarkering in de lagenlijst op of stelt deze in

Waarde: De bladkleurmarkering.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Haalt de positie van de bovenste laag op of stelt deze in.

Waarde: De bovenste laagpositie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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


Alle Aspose-producten moeten deze methode implementeren. Deze wordt aangeroepen door een GroupDocs-product om aan te geven of GroupDocs zelf gelicentieerd is of niet en om een aangepaste watermerk op te geven. Wanneer GroupDocs gelicentieerd is, moet deze documentinstantie ook als gelicentieerd fungeren, zelfs als het Aspose-product niet gelicentieerd is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ventureLicense | java.lang.Object | license |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Haalt op of stelt de verticale resolutie, in pixels per inch, van deze RasterImage in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De verticale resolutie. |

Opmerking: standaard is deze waarde altijd 96 omdat verschillende platforms de schermresolutie niet kunnen retourneren. U kunt overwegen de SetResolution-methode te gebruiken om beide resolutiewaarden in één oproep bij te werken. |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of de laag zichtbaar is

Waarde:  true  als deze instantie zichtbaar is; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Haalt op of stelt de XMP-metadata in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | De XMP-metadata. |

### shallowCopy() {#shallowCopy--}
```
public final Layer shallowCopy()
```


Maakt een ondiepe kopie van de huidige Layer. Gelieve   voor uitleg.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - A shallow copy of the current Layer.
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
### updateBlendingOptions_internalized(PattResource pattResource) {#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateBlendingOptions_internalized(PattResource pattResource)
```


Werkt de mengopties bij nadat de laag of globale bronnen zijn gewijzigd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) |  |

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

