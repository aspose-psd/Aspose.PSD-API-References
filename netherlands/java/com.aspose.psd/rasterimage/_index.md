---
title: "RasterImage"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt een rasterafbeelding voor die rastergrafische bewerkingen ondersteunt."
type: docs
weight: 86
url: /nl/java/com.aspose.psd/rasterimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image)

**All Implemented Interfaces:**
[com.aspose.psd.IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader), com.aspose.internal.IPixelsSaver
```
public abstract class RasterImage extends Image implements IRasterImageArgb32PixelLoader, IPixelsSaver
```

Stelt een rasterafbeelding voor die rastergrafische bewerkingen ondersteunt.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | Treedt op wanneer afbeelding werd geladen |
| [OnLoad_internalized](#OnLoad-internalized) | Treedt op wanneer afbeelding werd geladen door createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Treedt op wanneer afbeelding werd geladen of opgeslagen |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Treedt op wanneer krediet werd gebruikt |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Aanpassing van de helderheid voor een afbeelding. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Beeldcontrast |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gamma-correctie van een afbeelding. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma-correctie van een afbeelding. |
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
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Bijsnijdt de opgegeven rechthoek. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Afbeelding bijsnijden met verschuivingen. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Voert dithering uit op de huidige afbeelding. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Voert dithering uit op de huidige afbeelding. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filtert de opgegeven rechthoek. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Haalt een 32-bit ARGB-pixel van de afbeelding op. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Haalt een waarde op die aangeeft of het palet automatisch wordt aangepast. |
| [getBackgroundColor()](#getBackgroundColor--) | Haalt op of stelt een waarde voor de achtergrondkleur in. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Haalt het aantal bits per pixel van de afbeelding op. |
| [getBounds()](#getBounds--) | Haalt de grenzen van de afbeelding op. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Haalt de buffer‑groottehint op, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Haalt de Image-container op. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Haalt de gegevensstroom van het object op. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Haalt het diep aangepast palet op. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Haalt de standaard 32-bit ARGB-pixelarray op. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Haalt de standaardopties op. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Haalt de standaard pixelarray op met behulp van een gedeeltelijke pixelloader. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Haalt de standaard ruwe gegevensarray op met behulp van een gedeeltelijke pixelloader. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Haalt de standaard ruwe gegevensarray op. |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getFileFormat()](#getFileFormat--) | Haalt een waarde van bestandsformaat op |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Haalt het bestandsformaat op. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Haalt het bestandsformaat op. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Haalt het bestandsformaat op. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Haalt palet op van formatspecifieke locaties |
| [getHeight()](#getHeight--) | Haalt de afbeeldingshoogte op. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Haalt op of stelt de horizontale resolutie, in pixels per inch, van deze  RasterImage . |
| [getImageOpacity()](#getImageOpacity--) | Haalt de dekking op van deze afbeelding. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Haalt de interrupt‑monitor op. |
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
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Haalt de aangepaste kleurconverter op of stelt deze in |
| [getRawDataFormat()](#getRawDataFormat--) | Haalt het ruwe gegevensformaat op. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Haalt de fallback‑index op of stelt deze in die moet worden gebruikt wanneer de paletindex buiten bereik is |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Haalt de geïndexeerde kleurconverter op of stelt deze in |
| [getRawLineSize()](#getRawLineSize--) | Haalt de ruwe regelgrootte in bytes op. |
| [getSize()](#getSize--) | Haalt de afbeeldingsgrootte op. |
| [getSkewAngle()](#getSkewAngle--) | Haalt de scheefstandhoek op. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Haalt het bestandspad van de bronafbeelding op als deze bestaat. |
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
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Haalt op of stelt de maximale voortgangswaarde in |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Geeft de voortgang aan. |
| [isCached()](#isCached--) | Haalt een waarde op die aangeeft of de gegevens van het object momenteel zijn gecached en er geen gegevenslezen nodig is. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Haalt een waarde op die aangeeft of ruwe gegevensladen beschikbaar is. |
| [isUsePalette()](#isUsePalette--) | Haalt een waarde op die aangeeft of de afbeeldingspalet wordt gebruikt. |
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
| [normalizeAngle()](#normalizeAngle--) | Normaliseert de hoek. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normaliseert de hoek. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Wordt aangeroepen wanneer de container van deze [Image](../../com.aspose.psd/image) is ingesteld. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Leest de volledige scanlijn op basis van de opgegeven scanlijnindex. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Leest de volledige scanlijn op basis van de opgegeven scanlijnindex. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Vervangt alle niet-transparante kleuren door een nieuwe kleur en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Vervangt alle niet-transparante kleuren door een nieuwe kleur en behoudt de oorspronkelijke alfawaarde om gladde randen te behouden. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Wijzigt de grootte van de afbeelding. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Wijzigt de grootte van de afbeelding met uitgebreide opties. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Wijzigt de grootte van de afbeelding. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Wijzigt de hoogte proportioneel. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Wijzigt de hoogte proportioneel. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Wijzigt de hoogte proportioneel. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Wijzigt de breedte proportioneel. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Wijzigt de breedte proportioneel. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Wijzigt de breedte proportioneel. |
| [rotate(float angle)](#rotate-float-) | Roteer de afbeelding rond het midden. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Roteer de afbeelding rond het midden. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Roteert, spiegelt of roteert en spiegelt de afbeelding. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Stelt een afbeelding 32-bit ARGB-pixel in voor de opgegeven positie. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Stelt een waarde in die aangeeft of de palet automatisch wordt aangepast. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Haalt op of stelt een waarde in die aangeeft of de afbeelding een achtergrondkleur heeft. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Haalt op of stelt een waarde voor de achtergrondkleur in. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Stelt de buffergroottehint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Stelt de  Image  container in. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Stelt de data loader direct in. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Stelt de gegevensstroom van het object in. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Stelt palette in op formaat‑specifieke plaatsen |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Haalt op of stelt de horizontale resolutie, in pixels per inch, van deze  RasterImage . |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Stelt een waarde in die aangeeft of [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze afbeelding-instantie is gewijzigd na het laden. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Stelt de interrupt monitor in. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Stelt de geheugenbeheerder in. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Stelt het kleurenpalet in. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Stelt het afbeeldingspalet in. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Stelt een afbeeldingspixel in voor de opgegeven positie. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of de afbeeldingscomponenten moeten worden voorvermenigvuldigd. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Haalt de aangepaste kleurconverter op of stelt deze in |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Haalt de fallback‑index op of stelt deze in die moet worden gebruikt wanneer de paletindex buiten bereik is |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Haalt de geïndexeerde kleurconverter op of stelt deze in |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Stelt de resolutie in voor deze  RasterImage . |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Haalt een waarde op die aangeeft of de afbeelding een transparante kleur heeft. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Haalt de transparante kleur van de afbeelding op. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of de XMP‑metadata moet worden bijgewerkt. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Haalt op of stelt een waarde in die aangeeft of ruwe gegevensladen moet worden gebruikt wanneer ruwe gegevensladen beschikbaar is. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Alle Aspose-producten moeten deze methode implementeren. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Haalt op of stelt de verticale resolutie, in pixels per inch, van deze RasterImage in. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Haalt op of stelt de XMP-metadata in. |
| [toBitmap()](#toBitmap--) | Converteert rasterafbeelding naar de bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Schrijft de volledige scanlijn naar de opgegeven scanlijnindex. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Schrijft de volledige scanlijn naar de opgegeven scanlijnindex. |
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
public abstract void cacheData()
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
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Bijsnijdt de opgegeven rechthoek.

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
public abstract void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
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
public abstract int getBitsPerPixel()
```


Haalt het aantal bits per pixel van de afbeelding op.

**Returns:**
int - Het aantal bits per pixel van de afbeelding.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Haalt de afbeeldingshoogte op.

**Returns:**
int - De hoogte van de afbeelding.
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
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Haalt de interrupt‑monitor op.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
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
public abstract int getWidth()
```


Haalt de breedte van de afbeelding op.

**Returns:**
int - De breedte van de afbeelding.
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

**Returns:**
boolean -  true  als dit exemplaar een alfa heeft; anders,  false .
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

### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Haalt een waarde op die aangeeft of de gegevens van het object momenteel zijn gecached en er geen gegevenslezen nodig is.

**Returns:**
boolean - een waarde die aangeeft of de gegevens van het object momenteel zijn gecached en er geen gegevenslezen nodig is.
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


Wijzigt de grootte van de afbeelding met uitgebreide opties.

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
public abstract void rotateFlip(int rotateFlipType)
```


Roteert, spiegelt of roteert en spiegelt de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rotateFlipType | int | Type van de rotatie‑omslag. |

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

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Stelt de interrupt monitor in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | de onderbrekingsmonitor. |

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


Stelt de resolutie in voor deze  RasterImage .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dpiX | double | De horizontale resolutie, in dots per inch, van de  RasterImage . |
| dpiY | double | De verticale resolutie, in dots per inch, van de  RasterImage . |

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

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Haalt op of stelt de XMP-metadata in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | De XMP-metadata. |

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

