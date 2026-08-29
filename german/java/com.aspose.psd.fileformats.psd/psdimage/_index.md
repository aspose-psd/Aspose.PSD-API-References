---
title: "PsdImage"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert die PsdImage-Klasse, die die Möglichkeit bietet, PSD-Dateien zu laden, zu bearbeiten und zu speichern sowie Eigenschaften zu aktualisieren, Wasserzeichen hinzuzufügen, Grafikoperationen durchzuführen oder ein Dateiformat in ein anderes zu konvertieren."
type: docs
weight: 14
url: /de/java/com.aspose.psd.fileformats.psd/psdimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage)
```
public final class PsdImage extends RasterCachedImage
```

Definiert die PsdImage-Klasse, die die Möglichkeit bietet, PSD-Dateien zu laden, zu bearbeiten und zu speichern sowie Eigenschaften zu aktualisieren, Wasserzeichen hinzuzufügen, Grafikoperationen durchzuführen oder ein Dateiformat in ein anderes zu konvertieren. Aspose.PSD unterstützt den Import als Ebene und den Export in die folgenden Formate: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb sowie den Export nach Pdf mit auswählbarem Text.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PsdImage(String path)](#PsdImage-java.lang.String-) | Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse aus dem angegebenen Pfad eines Rasterbildes (keine PSD‑Datei im Pfad). |
| [PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.lang.String-short-short-short-int-short-) | Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse aus dem angegebenen Pfad eines Rasterbildes (keine PSD‑Datei im Pfad) mit Konstruktorparametern. |
| [PsdImage(InputStream stream)](#PsdImage-java.io.InputStream-) | Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse aus dem angegebenen Pfad eines Rasterbildes (keine PSD‑Datei im Stream). |
| [PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.io.InputStream-short-short-short-int-short-) | Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse aus dem angegebenen Pfad eines Rasterbildes (keine PSD‑Datei im Stream) mit Konstruktorparametern. |
| [PsdImage(RasterImage rasterImage)](#PsdImage-com.aspose.psd.RasterImage-) | Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse aus einem bestehenden Rasterbild (keine PSD‑Datei) mit RGB-Farbmodus, 4 Kanälen, 8 Bit/Kanal und ohne Kompression. |
| [PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-) | Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse aus einem bestehenden Rasterbild (keine PSD‑Datei) mit Konstruktorparametern. |
| [PsdImage(int width, int height)](#PsdImage-int-int-) | Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse mit angegebener Breite und Höhe. |
| [PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-) | Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse mit angegebener Breite, Höhe, Palette, Farbmodus, Kanalanzahl und Kanal-Bitlänge sowie angegebenen Kompressionsmodus-Parametern. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DefaultStubEncodingName_internalized](#DefaultStubEncodingName-internalized) | Der Standardkodierungsname |
| [DefaultVersion](#DefaultVersion) | Die Standard‑PSD‑Version. |
| [OnCreate_internalized](#OnCreate-internalized) | Tritt auf, wenn das Bild geladen wurde |
| [OnLoad_internalized](#OnLoad-internalized) | Tritt auf, wenn das Bild durch createFirstSupportedLoader geladen wurde |
| [OnSave_internalized](#OnSave-internalized) | Tritt auf, wenn das Bild geladen oder gespeichert wurde |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Tritt auf, wenn ein Guthaben verwendet wurde |
| [SyncLayersRoot_internalized](#SyncLayersRoot-internalized) | Das Objekt, das verwendet werden kann, um den Zugriff auf die Ebenen zu synchronisieren. |
| [horizontalResolution](#horizontalResolution) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addBlackWhiteAdjustmentLayer()](#addBlackWhiteAdjustmentLayer--) | Fügt die Schwarz‑Weiß‑Anpassungsebene hinzu. |
| [addBrightnessContrastAdjustmentLayer(int brightness, int contrast)](#addBrightnessContrastAdjustmentLayer-int-int-) | Fügt die Helligkeit/Kontrast‑Anpassungsebene hinzu. |
| [addChannelMixerAdjustmentLayer()](#addChannelMixerAdjustmentLayer--) | Fügt die Kanalmixer‑Anpassungsebene mit Standardparametern hinzu. |
| [addColorBalanceAdjustmentLayer()](#addColorBalanceAdjustmentLayer--) | Fügt die Farbton‑Ausgleichs‑Anpassungsebene hinzu. |
| [addCurvesAdjustmentLayer()](#addCurvesAdjustmentLayer--) | Fügt die Kurven‑Anpassungsebene hinzu. |
| [addExposureAdjustmentLayer()](#addExposureAdjustmentLayer--) |  |
| [addExposureAdjustmentLayer(float exposure)](#addExposureAdjustmentLayer-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset)](#addExposureAdjustmentLayer-float-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)](#addExposureAdjustmentLayer-float-float-float-) | Fügt die Belichtungs‑Anpassungsebene hinzu. |
| [addGradientMapAdjustmentLayer()](#addGradientMapAdjustmentLayer--) | Fügt die GradientMap‑Anpassungsebene hinzu. |
| [addHueSaturationAdjustmentLayer()](#addHueSaturationAdjustmentLayer--) | Fügt die Farbton/Sättigung‑Anpassungsebene hinzu. |
| [addInvertAdjustmentLayer()](#addInvertAdjustmentLayer--) | Fügt eine Invertierungs‑Anpassungsebene hinzu. |
| [addLayer(Layer layer)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Fügt die Ebene hinzu. |
| [addLayerGroup(String groupName, int index, boolean startBehaviour)](#addLayerGroup-java.lang.String-int-boolean-) | Fügt die Ebenengruppe hinzu. |
| [addLayer_internalized(Layer layer, int index)](#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-) | Fügt die Ebene am Index hinzu. |
| [addLevelsAdjustmentLayer()](#addLevelsAdjustmentLayer--) | Fügt die Levels-Anpassungsebene hinzu. |
| [addPhotoFilterLayer(Color color)](#addPhotoFilterLayer-com.aspose.psd.Color-) | Fügt die Fotofilter-Ebene hinzu. |
| [addPosterizeAdjustmentLayer()](#addPosterizeAdjustmentLayer--) | Fügt die Posterize-Anpassungsebene hinzu. |
| [addRegularLayer()](#addRegularLayer--) | Fügt eine neue reguläre Ebene hinzu. |
| [addSelectiveColorAdjustmentLayer()](#addSelectiveColorAdjustmentLayer--) | Fügt die selektive Farb-Anpassungsebene hinzu. |
| [addShapeLayer()](#addShapeLayer--) | Füge leere Shape-Ebene hinzu. |
| [addTextLayer(String text, Rectangle rect)](#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-) | Fügt eine neue Text-Ebene hinzu. |
| [addThresholdAdjustmentLayer()](#addThresholdAdjustmentLayer--) | Fügt die Schwellenwert-Anpassungsebene hinzu. |
| [addVibranceAdjustmentLayer()](#addVibranceAdjustmentLayer--) | Fügt die Vibrance-Anpassungsebene hinzu. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Anpassung der Helligkeit für das Bild. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Bildkontrast |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gammakorrektur eines Bildes. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gammakorrektur eines Bildes. |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | Startet den Größenänderungsprozess. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild‑Schwellwertbestimmung. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild‑Schwellwertbestimmung. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisierung eines Bildes mit vordefiniertem Schwellenwert |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisierung eines Bildes mit Otsu‑Schwellwertbestimmung |
| [cacheData()](#cacheData--) | Puffert die Daten und stellt sicher, dass keine zusätzlichen Daten aus dem zugrunde liegenden DataStreamSupporter.DataStreamContainer geladen werden. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Bestimmt, ob das Bild aus dem angegebenen Stream geladen werden kann. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Bestimmt, ob das Bild aus dem angegebenen Stream geladen werden kann und optional die angegebenen loadOptions verwendet. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann. |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [convert(PsdOptions newOptions)](#convert-com.aspose.psd.imageoptions.PsdOptions-) | Konvertiert dieses Bildformat in das in den Optionen angegebene. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Konvertiert zu aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Erstellt ein neues Bild mit den angegebenen Bildern als Seiten. |
| [createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-) | Erstellt eine neue Instanz der Klasse [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Zuschneiden des Bildes. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Bild mit Verschiebungen zuschneiden. |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Führt Dithering auf dem aktuellen Bild aus. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Führt Dithering auf dem aktuellen Bild aus. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | Zuschneiden des Bildes. |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | Skaliert das Bild. |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filtert das angegebene Rechteck. |
| [flattenImage()](#flattenImage--) | Flacht alle Ebenen ab. |
| [getActiveLayer()](#getActiveLayer--) | Liest oder setzt die aktive Ebene. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Liest ein 32‑Bit‑ARGB‑Pixel eines Bildes. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Gibt einen Wert zurück, der angibt, ob die automatische Palettenanpassung aktiviert ist. |
| [getBackgroundColor()](#getBackgroundColor--) | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| [getBackgroundContents_internalized()](#getBackgroundContents-internalized--) | Liest oder setzt die Hintergrundfarbe. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Liest die Bits pro Kanal. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Liest die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [getBounds()](#getBounds--) | Liest die Bildgrenzen. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liest den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [getChannelsCount()](#getChannelsCount--) | Liest die Anzahl der PSD-Kanäle. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Liest oder setzt das CMYK-Farbprofil für CMYK-PSD-Bilder. |
| [getColorMode()](#getColorMode--) | Liest oder setzt den Farbmodus. |
| [getCompression()](#getCompression--) | Liest die Komprimierungsmethode. |
| [getContainer()](#getContainer--) | Liest den Image‑Container. |
| [getCurrentOptions_internalized()](#getCurrentOptions-internalized--) | Liest die aktuellen Bildoptionen. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Liest den Datenstrom des Objekts. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Liest die tiefgreifende Palettenanpassung. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Liest das Standard‑32‑Bit‑ARGB‑Pixel‑Array. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Liest die Standardoptionen. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Liest das Standard‑Pixel‑Array unter Verwendung eines partiellen Pixel‑Loaders. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Liest das Standard‑Rohdaten‑Array unter Verwendung eines partiellen Pixel‑Loaders. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Liest das Standard‑Rohdaten‑Array. |
| [getDefaultReplacementFont_internalized()](#getDefaultReplacementFont-internalized--) | Liest oder setzt die Standard-Ersetzungs-Schriftart. |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getFileFormat()](#getFileFormat--) | Ermittelt einen Wert des Dateiformats |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Ermittelt das Dateiformat. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Ermittelt das Dateiformat. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Ermittelt das Dateiformat. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Ermittelt die Palette aus formatabhängigen Bereichen |
| [getGlobalAngle()](#getGlobalAngle--) | Liest oder setzt den globalen Winkel. |
| [getGlobalLayerMaskInfo()](#getGlobalLayerMaskInfo--) | Liest die globalen Ebenenmaskeninformationen. |
| [getGlobalLayerResources()](#getGlobalLayerResources--) | Liest oder setzt die globalen Ebenenressourcen. |
| [getGrayColorProfile()](#getGrayColorProfile--) | Liest oder legt das GRAY (monochrome) Farbprofil für Graustufen‑PSD‑Bilder fest. |
| [getHeight()](#getHeight--) | Ermittelt die Bildhöhe. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Liest oder legt die horizontale Auflösung in Pixel pro Zoll für dieses [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) fest. |
| [getImageLayers_internalized()](#getImageLayers-internalized--) | Liest oder legt die PSD‑Ebenen fest. |
| [getImageOpacity()](#getImageOpacity--) | Ermittelt die Opazität dieses Bildes. |
| [getImageResources()](#getImageResources--) | Liest oder legt die PSD‑Bildressourcen fest. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Ermittelt den internen Daten-Transformer. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Ermittelt den Unterbrechungsmonitor. |
| [getLayerAndMask_internalized()](#getLayerAndMask-internalized--) | Liest die Ebene und Maske. |
| [getLayers()](#getLayers--) | Liest oder legt die PSD‑Ebenen fest. |
| [getLinkedLayersManager()](#getLinkedLayersManager--) | Liest den Manager für verknüpfte Ebenen. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Liefert oder setzt die maximal zulässige Zuweisung für das partielle Rotations‑Speichern. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Liefert den Speicher‑Manager. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Liefert Datum und Uhrzeit, wann das Ressourcen‑Bild zuletzt geändert wurde. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getOriginalOptions()](#getOriginalOptions--) | Liefert die Optionen basierend auf den ursprünglichen Dateieinstellungen. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Liefert das zu malende Bild. |
| [getPalette()](#getPalette--) | Liefert die Farbpalette. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Liefert ein Bildpixel. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Liefert oder setzt einen Wert, der angibt, ob die Bildkomponenten vor multipliziert werden müssen. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Erstellt den privaten Schriftarten‑Cache. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Liefert die Informationen zum Fortschritts‑Ereignis‑Handler. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Liefert die Informationen zum Fortschritts‑Ereignis‑Handler. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Liefert eine proportionale Höhe. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Liefert eine proportionale Breite. |
| [getPsdHeader_internalized()](#getPsdHeader-internalized--) | Liest oder legt den PSD‑Header fest. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Liefert oder setzt den benutzerdefinierten Farbkonverter. |
| [getRawDataFormat()](#getRawDataFormat--) | Liefert das Rohdatenformat. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Liefert oder setzt den Ausweich‑Index, der verwendet wird, wenn der Paletten‑Index außerhalb des Bereichs liegt. |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Liefert oder setzt den indizierten Farbkonverter. |
| [getRawLineSize()](#getRawLineSize--) | Liefert die Rohzeilengröße in Bytes. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Liest oder legt das RGB‑Farbprofil für CMYK‑PSD‑Bilder fest. |
| [getRotateMode()](#getRotateMode--) | Liest oder setzt den Rotationsmodus. |
| [getSize()](#getSize--) | Liest die Bildgröße. |
| [getSkewAngle()](#getSkewAngle--) | Liest den Schrägwinkel. |
| [getSmartObjectProvider()](#getSmartObjectProvider--) | Liest den Smart‑Object‑Provider. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Liest den Dateipfad des Quellbildes, falls es existiert. |
| [getSyncExclusiveOperation_internalized()](#getSyncExclusiveOperation-internalized--) |  |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Liest die Synchronisationswurzel. |
| [getTimeline()](#getTimeline--) | Liest die Timeline ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) dieses [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getTransparentColor()](#getTransparentColor--) | Liest die transparente Farbe des Bildes. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Liest oder setzt einen Wert, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| [getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)](#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-) | Liest aktualisierte Ressourcen mit einem brandneuen Ressourcenblock. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Liest einen Wert, der angibt, ob das Objekt eine Speicheroptimierungsstrategie verwendet |
| [getUseRawData()](#getUseRawData--) | Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Liest die verwendete Palette. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Liest die Venture-Lizenz. |
| [getVersion()](#getVersion--) | Liest oder setzt die Version. |
| [getVerticalResolution()](#getVerticalResolution--) | Liest oder legt die vertikale Auflösung in Pixel pro Zoll für dieses [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) fest. |
| [getWidth()](#getWidth--) | Liest die Bildbreite. |
| [getXmpData()](#getXmpData--) | Liest oder setzt die XMP-Metadaten. |
| [grayscale()](#grayscale--) | Transformation eines Bildes in seine Graustufen-Darstellung |
| [hasAlpha()](#hasAlpha--) | Liest oder setzt die vertikale Auflösung in Pixel pro Zoll dieses  RasterImage . |
| [hasBackgroundColor()](#hasBackgroundColor--) | Liest einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Liest oder setzt einen Wert, der angibt, ob diese Bildinstanz nach dem Laden geändert wurde. |
| [hasTransparencyData()](#hasTransparencyData--) | Liest oder legt einen Wert fest, der angibt, ob der erste Alphakanal die Transparenzdaten für das zusammengeführte Ergebnis enthält, wenn Ebenendaten angegeben werden. |
| [hasTransparentColor()](#hasTransparentColor--) | Liest einen Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Liest oder setzt den maximalen Fortschrittswert |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Zeigt den Fortschritt an. |
| [insertLayerAfter_internalized(Layer layer, Layer layerToInsert)](#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Fügt die Ebene nach der angegebenen Ebene mit allen Vorbereitungen ein. |
| [isCached()](#isCached--) | Liest einen Wert, der angibt, ob Bilddaten derzeit im Cache sind. |
| [isFlatten()](#isFlatten--) | Liest einen Wert, der angibt, ob das PSD‑Bild abgeflacht ist. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Liest einen Wert, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| [isUsePalette()](#isUsePalette--) | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| [isUsePhotoshopCompatibilityMode_internalized()](#isUsePhotoshopCompatibilityMode-internalized--) |  |
| [load(InputStream stream)](#load-java.io.InputStream-) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(String filePath)](#load-java.lang.String-) | Lädt ein neues Bild aus der angegebenen Datei. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Lädt ein neues Bild aus der angegebenen Datei. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | Lädt 32‑Bit‑ARGB‑Pixel. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | Lädt 64‑Bit‑ARGB‑Pixel. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | Lädt Pixel im CMYK‑Format. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | Lädt Pixel im CMYK‑Format. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Lädt 32‑Bit‑ARGB‑Pixel teilweise nach Paketen. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Lädt Pixel teilweise nach Paketen. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | Lädt Pixel. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Lädt Rohbilddaten mit dem Teilverarbeitungs‑Mechanismus. |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Lädt Rohdaten. |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [mergeLayers(Layer bottomLayer, Layer topLayer)](#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Führt die Ebenen zusammen. |
| [normalizeAngle()](#normalizeAngle--) | Normalisiert den Winkel. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normalisiert den Winkel. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Aufrufen, wenn der Container dieses [Image](../../com.aspose.psd/image) festgelegt wurde. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index. |
| [removeGlobalTextEngineResource_internalized()](#removeGlobalTextEngineResource-internalized--) | Entfernt die globale Text‑Engine‑Ressource – Die Methode wird für einige textbasierte PSD‑Dateien verwendet, die nach der Verarbeitung nicht in Adobe Photoshop geöffnet werden können (hauptsächlich bei fehlenden Schriftarten in Text‑Ebenen). |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Ersetzt alle nicht transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Ersetzt alle nicht transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Skaliert das Bild. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Skaliert das Bild. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Skaliert das Bild. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Ändert die Höhe proportional. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Ändert die Höhe proportional. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ändert die Höhe proportional. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Ändert die Breite proportional. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Ändert die Breite proportional. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ändert die Breite proportional. |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | Ändert die Größe der Ebene mit dem angegebenen inversen Maßstab. |
| [rotate(float angle)](#rotate-float-) | Bild um das Zentrum drehen. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Bild um das Zentrum drehen. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Speichert die Objektdaten in den angegebenen Stream. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Speichert die Objektdaten in den angegebenen Stream. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(String filePath)](#save-java.lang.String-) | Speichert die Objektdaten am angegebenen Speicherort. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Speichert die Objektdaten am angegebenen Speicherort. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | Speichert die 32‑Bit‑ARGB‑Pixel. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | Speichert die Pixel. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | Speichert die Pixel. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | Speichert die Pixel. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Speichert die Rohdaten. |
| [saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)](#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---) | Speichert die Bilddaten in den angegebenen Stream unter Verwendung der angegebenen Speicheroptionen und Grenzen. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [setActiveLayer(Layer value)](#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Liest oder setzt die aktive Ebene. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| [setBackgroundContents_internalized(RawColor value)](#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Liest oder setzt die Hintergrundfarbe. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Liest oder setzt das CMYK-Farbprofil für CMYK-PSD-Bilder. |
| [setColorMode(short value)](#setColorMode-short-) | Liest oder setzt den Farbmodus. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Setzt den Image‑Container. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Setzt den Datenlader direkt. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Setzt den Datenstream des Objekts. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Setzt die Palette an format‑spezifische Stellen. |
| [setGlobalAngle(int value)](#setGlobalAngle-int-) | Der globale Winkel. |
| [setGlobalLayerResources(LayerResource[] value)](#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Liest oder setzt die globalen Ebenenressourcen. |
| [setGrayColorProfile(StreamSource value)](#setGrayColorProfile-com.aspose.psd.sources.StreamSource-) | Das GRAY (monochrome) Farbprofil für Graustufen‑PSD‑Bilder. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Liest oder legt die horizontale Auflösung in Pixel pro Zoll für dieses [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) fest. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Setzt einen Wert, der angibt, ob [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Bildinstanz nach dem Laden geändert wurde. |
| [setImageResources(ResourceBlock[] value)](#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Liest oder legt die PSD‑Bildressourcen fest. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Setzt den internen Datentransformator. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Setzt den Unterbrechungsmonitor. |
| [setLayers(Layer[] value)](#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | Liest oder legt die PSD‑Ebenen fest. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Liefert oder setzt die maximal zulässige Zuweisung für das partielle Rotations‑Speichern. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Setzt den Speicher‑Manager. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Legt die Farbpalette fest. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Legt die Bildpalette fest. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Setzt ein Bildpixel für die angegebene Position. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Liefert oder setzt einen Wert, der angibt, ob die Bildkomponenten vor multipliziert werden müssen. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Liefert oder setzt den benutzerdefinierten Farbkonverter. |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Liefert oder setzt den Ausweich‑Index, der verwendet wird, wenn der Paletten‑Index außerhalb des Bereichs liegt. |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Liefert oder setzt den indizierten Farbkonverter. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Legt die Auflösung für dieses [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) fest. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Liest oder legt das RGB‑Farbprofil für CMYK‑PSD‑Bilder fest. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Liest oder setzt den Rotationsmodus. |
| [setTransparencyData(boolean value)](#setTransparencyData-boolean-) | Liest oder legt einen Wert fest, der angibt, ob der erste Alphakanal die Transparenzdaten für das zusammengeführte Ergebnis enthält, wenn Ebenendaten angegeben werden. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Liest einen Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Liest die transparente Farbe des Bildes. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Liest oder setzt einen Wert, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| [setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)](#setUsePhotoshopCompatibilityMode-internalized-boolean-) |  |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Legt die Venture‑Lizenz fest. |
| [setVersion(int value)](#setVersion-int-) | Liest oder setzt die Version. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Liest oder legt die vertikale Auflösung in Pixel pro Zoll für dieses [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) fest. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Liest oder setzt die XMP-Metadaten. |
| [toBitmap()](#toBitmap--) | Konvertiert das Rasterbild in das Bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Schreibt die gesamte Scanzeile an den angegebenen Scanzeilenindex. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Schreibt die gesamte Scanzeile an den angegebenen Scanzeilenindex. |
### PsdImage(String path) {#PsdImage-java.lang.String-}
```
public PsdImage(String path)
```


Initialisiert eine neue Instanz der Klasse [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) aus dem angegebenen Pfad einer Rastergrafik (nicht einer PSD‑Datei im Pfad). Wird verwendet, um ein PSD‑Bild mit Standardparametern zu initialisieren – Farbmodus – RGB, 4 Kanäle, 8 Bit pro Kanal, Kompression – Raw.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad, von dem Pixel- und Palettendaten geladen und initialisiert werden. |

### PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.lang.String-short-short-short-int-short-}
```
public PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse aus dem angegebenen Pfad eines Rasterbildes (keine PSD‑Datei im Pfad) mit Konstruktorparametern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad, von dem Pixel- und Palettendaten geladen und initialisiert werden. |
| colorMode | short | Der Farbmodus. |
| channelBitDepth | short | Die Bit-Tiefe pro Kanal im PSD. |
| channels | short | Die Anzahl der Kanäle im PSD. |
| psdVersion | int | Die PSD‑Version. |
| compression | short | Die zu verwendende Kompression. |

### PsdImage(InputStream stream) {#PsdImage-java.io.InputStream-}
```
public PsdImage(InputStream stream)
```


Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD-Bild im Stream). Wird verwendet, um ein PSD‑Bild mit Standardparametern zu initialisieren – Farbmodus – RGB, 4 Kanäle, 8 Bit pro Kanal, Kompression – Raw.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Stream, von dem Pixel- und Palettendaten geladen und initialisiert werden. |

### PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.io.InputStream-short-short-short-int-short-}
```
public PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse aus dem angegebenen Pfad eines Rasterbildes (keine PSD‑Datei im Stream) mit Konstruktorparametern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Stream, von dem Pixel- und Palettendaten geladen und initialisiert werden. |
| colorMode | short | Der Farbmodus. |
| channelBitDepth | short | Die Bit-Tiefe pro Kanal im PSD. |
| channels | short | Die Anzahl der Kanäle im PSD. |
| psdVersion | int | Die PSD‑Version. |
| compression | short | Die zu verwendende Kompression. |

### PsdImage(RasterImage rasterImage) {#PsdImage-com.aspose.psd.RasterImage-}
```
public PsdImage(RasterImage rasterImage)
```


Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse aus einem bestehenden Rasterbild (keine PSD‑Datei) mit RGB-Farbmodus, 4 Kanälen, 8 Bit/Kanal und ohne Kompression.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Das Bild, von dem Pixel- und Palettendaten geladen und initialisiert werden. |

### PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-}
```
public PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse aus einem bestehenden Rasterbild (keine PSD‑Datei) mit Konstruktorparametern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Das Bild, von dem Pixel- und Palettendaten geladen und initialisiert werden. |
| colorMode | short | Der Farbmodus. |
| channelBitDepth | short | Die Bit-Tiefe pro Kanal im PSD. |
| channels | short | Die Anzahl der Kanäle im PSD. |
| psdVersion | int | Die PSD‑Version. |
| compression | short | Die zu verwendende Kompression. |

### PsdImage(int width, int height) {#PsdImage-int-int-}
```
public PsdImage(int width, int height)
```


Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse mit angegebener Breite und Höhe. Wird verwendet, um ein leeres PSD‑Bild zu initialisieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Bildbreite. |
| Höhe | int | Die Bildhöhe. |

### PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-}
```
public PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initialisiert eine neue Instanz der [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)-Klasse mit angegebenen Breite, Höhe, Palette, Farbmodus, Kanalanzahl und Kanal-Bit-Länge sowie den angegebenen Kompressionsmodus-Parametern. Wird verwendet, um ein leeres PSD‑Bild zu initialisieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Bildbreite. |
| Höhe | int | Die Bildhöhe. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die Farbpalette. |
| colorMode | short | Der Farbmodus. |
| channelBitDepth | short | Die Bit-Tiefe pro Kanal im PSD. |
| channels | short | Die Anzahl der Kanäle im PSD. |
| psdVersion | int | Die PSD‑Version. |
| compression | short | Die zu verwendende Kompression. |

### DefaultStubEncodingName_internalized {#DefaultStubEncodingName-internalized}
```
public static final String DefaultStubEncodingName_internalized
```


Der Standardkodierungsname

### DefaultVersion {#DefaultVersion}
```
public static final int DefaultVersion
```


Die Standard‑PSD‑Version.

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Tritt auf, wenn das Bild geladen wurde

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Tritt auf, wenn das Bild durch createFirstSupportedLoader geladen wurde

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Tritt auf, wenn das Bild geladen oder gespeichert wurde

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Tritt auf, wenn ein Guthaben verwendet wurde

### SyncLayersRoot_internalized {#SyncLayersRoot-internalized}
```
public final Object SyncLayersRoot_internalized
```


Das Objekt, das verwendet werden kann, um den Zugriff auf die Ebenen zu synchronisieren.

### horizontalResolution {#horizontalResolution}
```
public double horizontalResolution
```


### addBlackWhiteAdjustmentLayer() {#addBlackWhiteAdjustmentLayer--}
```
public final BlackWhiteAdjustmentLayer addBlackWhiteAdjustmentLayer()
```


Fügt die Schwarz‑Weiß‑Anpassungsebene hinzu.

**Returns:**
[BlackWhiteAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer) - The created black white adjustment layer.
### addBrightnessContrastAdjustmentLayer(int brightness, int contrast) {#addBrightnessContrastAdjustmentLayer-int-int-}
```
public final BrightnessContrastLayer addBrightnessContrastAdjustmentLayer(int brightness, int contrast)
```


Fügt die Helligkeit/Kontrast‑Anpassungsebene hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Helligkeit | int | Die Helligkeit. |
| Kontrast | int | Der Kontrast. |

**Returns:**
[BrightnessContrastLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer) - Created brightness/contrast layer
### addChannelMixerAdjustmentLayer() {#addChannelMixerAdjustmentLayer--}
```
public final ChannelMixerLayer addChannelMixerAdjustmentLayer()
```


Fügt die Kanalmixer‑Anpassungsebene mit Standardparametern hinzu.

**Returns:**
[ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) - Added Channel Mixer Layer
### addColorBalanceAdjustmentLayer() {#addColorBalanceAdjustmentLayer--}
```
public final ColorBalanceAdjustmentLayer addColorBalanceAdjustmentLayer()
```


Fügt die Farbton‑Ausgleichs‑Anpassungsebene hinzu.

**Returns:**
[ColorBalanceAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer) - A newly created color balance layer.
### addCurvesAdjustmentLayer() {#addCurvesAdjustmentLayer--}
```
public final CurvesLayer addCurvesAdjustmentLayer()
```


Fügt die Kurven‑Anpassungsebene hinzu.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exposure | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset) {#addExposureAdjustmentLayer-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exposure | float |  |
| Versatz | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection) {#addExposureAdjustmentLayer-float-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)
```


Fügt die Belichtungs‑Anpassungsebene hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exposure | float | Die Belichtung. |
| Versatz | float | Der Versatz. |
| gammaCorrection | float | Die Gammakorrektur. |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer) - Created Exposure Adjustment Layer
### addGradientMapAdjustmentLayer() {#addGradientMapAdjustmentLayer--}
```
public final GradientMapLayer addGradientMapAdjustmentLayer()
```


Fügt die GradientMap‑Anpassungsebene hinzu.

**Returns:**
[GradientMapLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer) - GradientMap instance.
### addHueSaturationAdjustmentLayer() {#addHueSaturationAdjustmentLayer--}
```
public final HueSaturationLayer addHueSaturationAdjustmentLayer()
```


Fügt die Farbton/Sättigung‑Anpassungsebene hinzu.

**Returns:**
[HueSaturationLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer) - A newly created hue/saturation layer.
### addInvertAdjustmentLayer() {#addInvertAdjustmentLayer--}
```
public final InvertAdjustmentLayer addInvertAdjustmentLayer()
```


Fügt eine Invertierungs‑Anpassungsebene hinzu.

**Returns:**
[InvertAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer) - The created invert layer
### addLayer(Layer layer) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void addLayer(Layer layer)
```


Fügt die Ebene hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Die Ebene. |

### addLayerGroup(String groupName, int index, boolean startBehaviour) {#addLayerGroup-java.lang.String-int-boolean-}
```
public final LayerGroup addLayerGroup(String groupName, int index, boolean startBehaviour)
```


Fügt die Ebenengruppe hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| groupName | java.lang.String | Name der Gruppe. |
| Index | int | Der Index der Ebene, nach der eingefügt werden soll. |
| startBehaviour | boolean | Wenn auf true [start behaviour] gesetzt, befindet sich die Gruppe beim Start im offenen Zustand, andernfalls im minimierten Zustand. |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - Opening group layer
### addLayer_internalized(Layer layer, int index) {#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-}
```
public void addLayer_internalized(Layer layer, int index)
```


Fügt die Ebene am Index hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Die Ebene. |
| Index | int | Der Index. |

### addLevelsAdjustmentLayer() {#addLevelsAdjustmentLayer--}
```
public final LevelsLayer addLevelsAdjustmentLayer()
```


Fügt die Levels-Anpassungsebene hinzu.

**Returns:**
[LevelsLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer) - A newly created Levels layer
### addPhotoFilterLayer(Color color) {#addPhotoFilterLayer-com.aspose.psd.Color-}
```
public final PhotoFilterLayer addPhotoFilterLayer(Color color)
```


Fügt die Fotofilter-Ebene hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Die Farbe. |

**Returns:**
[PhotoFilterLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer) - Created PhotoFilter Layer
### addPosterizeAdjustmentLayer() {#addPosterizeAdjustmentLayer--}
```
public final PosterizeLayer addPosterizeAdjustmentLayer()
```


Fügt die Posterize-Anpassungsebene hinzu.

**Returns:**
[PosterizeLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer) - PosterizeLayer instance.
### addRegularLayer() {#addRegularLayer--}
```
public final Layer addRegularLayer()
```


Fügt eine neue reguläre Ebene hinzu.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Created regular layer.
### addSelectiveColorAdjustmentLayer() {#addSelectiveColorAdjustmentLayer--}
```
public final SelectiveColorLayer addSelectiveColorAdjustmentLayer()
```


Fügt die selektive Farb-Anpassungsebene hinzu.

**Returns:**
[SelectiveColorLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer) - The created selective color adjustment layer.
### addShapeLayer() {#addShapeLayer--}
```
public final ShapeLayer addShapeLayer()
```


Leere Shape‑Ebene hinzufügen. Ohne Pfade. Sie sollten vor dem Speichern zur Shape‑Ebene hinzugefügt werden.

**Returns:**
[ShapeLayer](../../com.aspose.psd.fileformats.psd.layers/shapelayer) - ShapeLayer instance.
### addTextLayer(String text, Rectangle rect) {#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-}
```
public final TextLayer addTextLayer(String text, Rectangle rect)
```


Fügt eine neue Text-Ebene hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der Text der Ebene. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck der Ebene. |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - Created text layer.
### addThresholdAdjustmentLayer() {#addThresholdAdjustmentLayer--}
```
public final ThresholdLayer addThresholdAdjustmentLayer()
```


Fügt die Schwellenwert-Anpassungsebene hinzu.

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer) - The created Threshold adjustment layer.
### addVibranceAdjustmentLayer() {#addVibranceAdjustmentLayer--}
```
public final VibranceLayer addVibranceAdjustmentLayer()
```


Fügt die Vibrance-Anpassungsebene hinzu.

**Returns:**
[VibranceLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer) - A newly created Vibrance layer.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Anpassung der Helligkeit für das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Helligkeit | int | Helligkeitswert. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Bildkontrast

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kontrast | float | Kontrastwert (im Bereich [-100; 100]) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Gammakorrektur eines Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Gamma-Koeffizient für Rot-, Grün- und Blaukanäle |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gammakorrektur eines Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| gammaRed | float | Gamma für Rotkanal-Koeffizient |
| gammaGreen | float | Gamma für Grünkanal-Koeffizient |
| gammaBlue | float | Gamma für Blaukanal-Koeffizient |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


Startet den Größenänderungsprozess.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Bildbreite. |
| newHeight | int | Die neue Bildhöhe. |

**Returns:**
com.aspose.internal.IResizeController - Der Resize-Controller.
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild‑Schwellwertbestimmung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightnessDifference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s-Fensters von Pixeln, das um dieses Pixel zentriert ist. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild‑Schwellwertbestimmung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightnessDifference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s-Fensters von Pixeln, das um dieses Pixel zentriert ist. |
| windowSize | int | Die Größe des s × s-Fensters von Pixeln, das um dieses Pixel zentriert ist. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarisierung eines Bildes mit vordefiniertem Schwellenwert

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm der Wert 255 zugewiesen, andernfalls 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarisierung eines Bildes mit Otsu‑Schwellwertbestimmung

### cacheData() {#cacheData--}
```
public void cacheData()
```


Puffert die Daten und stellt sicher, dass keine zusätzlichen Daten aus dem zugrunde liegenden DataStreamSupporter.DataStreamContainer geladen werden.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Bestimmt, ob das Bild aus dem angegebenen Stream geladen werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Stream, von dem geladen wird. |

**Returns:**
boolean -  true  wenn das Bild aus dem angegebenen Stream geladen werden kann; andernfalls  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Bestimmt, ob das Bild aus dem angegebenen Stream geladen werden kann und optional die angegebenen loadOptions verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Stream, von dem geladen wird. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Die Ladeoptionen. |

**Returns:**
boolean -  true  wenn das Bild aus dem angegebenen Stream geladen werden kann; andernfalls  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad. |

**Returns:**
boolean -  true  wenn das Bild aus der angegebenen Datei geladen werden kann; andernfalls  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Die Ladeoptionen. |

**Returns:**
boolean -  true  wenn das Bild aus der angegebenen Datei geladen werden kann; andernfalls  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die zu verwendenden Speicheroptionen. |

**Returns:**
boolean -  true  wenn das Bild im angegebenen Dateiformat gespeichert werden kann, das durch die übergebenen Speicheroptionen dargestellt wird; andernfalls  false .
### close() {#close--}
```
public void close()
```


Implementiert das Closable-Interface und kann seit JDK 1.7 in der try-with-resources-Anweisung verwendet werden. Diese Methode ruft einfach die dispose-Methode auf.

### convert(PsdOptions newOptions) {#convert-com.aspose.psd.imageoptions.PsdOptions-}
```
public final void convert(PsdOptions newOptions)
```


Konvertiert dieses Bildformat in das in den Optionen angegebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newOptions | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Die neuen Optionen. |

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


Konvertiert zu aps.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Optionen. |
| Modus | int | Der Modus. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Beschneidungsrechteck. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - Die APS-Seite.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Bildoptionen. |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Die Bilder. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Erstellt ein neues Bild mit den angegebenen Bildern als Seiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Die Bilder. |
| disposeImages | boolean | wenn auf  true  gesetzt [Bilder entsorgen]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-}
```
public static PsdImage createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)
```


Erstellt eine neue Instanz der Klasse [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | Der PSD-Header. |
| colorData | com.aspose.internal.fileformats.psd.sections.ColorData | Die Farbdaten. |
| imageResources | com.aspose.internal.fileformats.psd.sections.ImageResources | Die Bildressourcen. |
| layerAndMaskInfo | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo | Die Ebenen- und Maskeninformationen. |
| imageData | com.aspose.internal.fileformats.psd.sections.ImageData | Die Bilddaten. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die Farbpalette. |
| version | int | Die PSD‑Version. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Die Ladeoptionen. |
| noLayerLoad | boolean | Kein Ebenenladen |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) - Returns the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resizer | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| Breite | int |  |
| Höhe | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static PsdImage create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-}
```
public static PsdImage create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Zuschneiden des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Bild mit Verschiebungen zuschneiden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftShift | int | Die linke Verschiebung. |
| rightShift | int | Die rechte Verschiebung. |
| topShift | int | Die obere Verschiebung. |
| bottomShift | int | Die untere Verschiebung. |

### dispose() {#dispose--}
```
public final void dispose()
```


Gibt die aktuelle Instanz frei.

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Führt Dithering auf dem aktuellen Bild aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ditheringMethod | int | Die Dithering-Methode. |
| bitsCount | int | Die endgültige Bitanzahl für Dithering. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Führt Dithering auf dem aktuellen Bild aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ditheringMethod | int | Die Dithering-Methode. |
| bitsCount | int | Die endgültige Bitanzahl für Dithering. |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die benutzerdefinierte Palette für Dithering. |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


Zuschneiden des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck. |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


Skaliert das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Die Skalierungseinstellungen. |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float |  |
| resizeProportionally | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Der Dreh-Flip-Typ. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtert das angegebene Rechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck. |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | Die Optionen. |

### flattenImage() {#flattenImage--}
```
public final void flattenImage()
```


Flacht alle Ebenen ab.

### getActiveLayer() {#getActiveLayer--}
```
public final Layer getActiveLayer()
```


Liest oder setzt die aktive Ebene.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Liest ein 32‑Bit‑ARGB‑Pixel eines Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die Pixel-x-Position. |
| y | int | Die Pixel-y-Position. |

**Returns:**
int - Der 32‑Bit‑ARGB‑Pixel für die angegebene Position.
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Gibt einen Wert zurück, der angibt, ob die automatische Palettenanpassung aktiviert ist.

**Returns:**
boolean -  true  wenn die automatische Palettenanpassung aktiviert ist; andernfalls  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Liest oder setzt einen Wert für die Hintergrundfarbe.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBackgroundContents_internalized() {#getBackgroundContents-internalized--}
```
public final RawColor getBackgroundContents_internalized()
```


Liest oder setzt die Hintergrundfarbe. Sie ist unter transparenten Objekten zu sehen.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBitsPerChannel() {#getBitsPerChannel--}
```
public final int getBitsPerChannel()
```


Liest die Bits pro Kanal.

Wert: Die Bits pro Kanal.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Liest die Bit‑Pro‑Pixel‑Anzahl des Bildes.

Wert: Die Bild-Bits‑pro‑Pixel‑Anzahl.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Liest die Bildgrenzen.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Liest den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße, in Megabyte. Ein nicht-positiver Wert bedeutet keine Speicherbegrenzung für interne Puffer.

**Returns:**
int - der Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Liest die Anzahl der PSD-Kanäle.

Wert: Die Anzahl der PSD-Kanäle.

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


Liest oder setzt das CMYK-Farbprofil für CMYK-PSD-Bilder. Es muss zusammen mit RgbColorProfile für eine korrekte Farbumwandlung verwendet werden.

Wert: Das CMYK-Farbprofil.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Liest oder setzt den Farbmodus.

Wert: Der Farbmodus.

**Returns:**
short
### getCompression() {#getCompression--}
```
public final short getCompression()
```


Liest die Komprimierungsmethode.

Wert: Die Kompression.

**Returns:**
short
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Liest den Image‑Container.

Wert: Der  Image  Container.

Wenn diese Eigenschaft nicht null ist, bedeutet dies, dass das Bild innerhalb eines anderen Bildes enthalten ist.

**Returns:**
[Image](../../com.aspose.psd/image)
### getCurrentOptions_internalized() {#getCurrentOptions-internalized--}
```
public final PsdOptions getCurrentOptions_internalized()
```


Liest die aktuellen Bildoptionen.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) - Current options for PSD image
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Liest den Datenstrom des Objekts.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Liest die tiefgreifende Palettenanpassung.

**Returns:**
boolean - Die tiefgreifend angepasste Palette.
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Liest das Standard‑32‑Bit‑ARGB‑Pixel‑Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, für das Pixel abgerufen werden sollen. |

**Returns:**
int[] - Das Standard-Pixel-Array.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Liest die Standardoptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Argumente | java.lang.Object[] | Die Argumente. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Liest das Standard‑Pixel‑Array unter Verwendung eines partiellen Pixel‑Loaders.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, für das Pixel abgerufen werden sollen. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Der partielle Pixel-Lader. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Liest das Standard‑Rohdaten‑Array unter Verwendung eines partiellen Pixel‑Loaders.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, für das Pixel abgerufen werden sollen. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Der partielle Rohdaten-Lader. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Die Rohdaten-Einstellungen. |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Liest das Standard‑Rohdaten‑Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, für das Rohdaten abgerufen werden sollen. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Die Rohdaten-Einstellungen. |

**Returns:**
byte[] - Das Standard-Rohdaten-Array.
### getDefaultReplacementFont_internalized() {#getDefaultReplacementFont-internalized--}
```
public final String getDefaultReplacementFont_internalized()
```


Liest oder setzt die Standard‑Ersatzschriftart. Wenn die Ersatzschriftart festgelegt ist, wird sie für das Rendern verwendet. Wir benötigen diese Methode für die interne Unterstützung.

**Returns:**
java.lang.String - Der Name der Ersatzschriftart
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde.

**Returns:**
boolean -  true  wenn freigegeben; andernfalls,  false .
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ermittelt einen Wert des Dateiformats

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Ermittelt das Dateiformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Der Stream. |

--------------------

Das ermittelte Dateiformat bedeutet nicht, dass das angegebene Bild geladen werden kann. Verwenden Sie eine der CanLoad-Methodenüberladungen, um zu bestimmen, ob der Stream geladen werden kann. |

**Returns:**
long - Das ermittelte Dateiformat.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Ermittelt das Dateiformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | java.io.InputStream | Der Stream. |

Das ermittelte Dateiformat bedeutet nicht, dass das angegebene Bild geladen werden kann. Verwenden Sie eine der CanLoad-Methodenüberladungen, um zu bestimmen, ob der Stream geladen werden kann. |

**Returns:**
long - Das ermittelte Dateiformat.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Ermittelt das Dateiformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad. |

Das ermittelte Dateiformat bedeutet nicht, dass das angegebene Bild geladen werden kann. Verwenden Sie eine der CanLoad-Methodenüberladungen, um zu bestimmen, ob die Datei geladen werden kann. |

**Returns:**
long - Das ermittelte Dateiformat.
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Ermittelt das Rechteck, das zum aktuellen Bild passt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, für das ein passendes Rechteck ermittelt werden soll. |
| Breite | int | Die Objektbreite. |
| Höhe | int | Die Objekthöhe. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Ermittelt das Rechteck, das zum aktuellen Bild passt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, für das ein passendes Rechteck ermittelt werden soll. |
| Pixel | int[] | Die 32‑Bit‑ARGB‑Pixel. |
| Breite | int | Die Objektbreite. |
| Höhe | int | Die Objekthöhe. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Ermittelt die Palette aus formatabhängigen Bereichen

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGlobalAngle() {#getGlobalAngle--}
```
public final int getGlobalAngle()
```


Liest oder setzt den globalen Winkel.

**Returns:**
int
### getGlobalLayerMaskInfo() {#getGlobalLayerMaskInfo--}
```
public final GlobalLayerMaskInfo getGlobalLayerMaskInfo()
```


Liest die globalen Ebenenmaskeninformationen.

**Returns:**
[GlobalLayerMaskInfo](../../com.aspose.psd.fileformats.psd.layers/globallayermaskinfo)
### getGlobalLayerResources() {#getGlobalLayerResources--}
```
public final LayerResource[] getGlobalLayerResources()
```


Liest oder setzt die globalen Ebenenressourcen.

Wert: Die globalen Ebenenressourcen.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getGrayColorProfile() {#getGrayColorProfile--}
```
public final StreamSource getGrayColorProfile()
```


Liest oder legt das GRAY (monochrome) Farbprofil für Graustufen‑PSD‑Bilder fest.

Wert: Das GRAY (monochrome) Farbprofil.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ermittelt die Bildhöhe.

Wert: Die Bildhöhe.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Liest oder legt die horizontale Auflösung in Pixel pro Zoll für dieses [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) fest.

**Returns:**
double
### getImageLayers_internalized() {#getImageLayers-internalized--}
```
public final Layer[] getImageLayers_internalized()
```


Liest oder legt die PSD‑Ebenen fest.

Wert: Die PSD-Ebenen.

--------------------

Hinweis: Wenn es keine Ebenen gibt, werden die anderen zugehörigen Informationen im Abschnitt für Ebenen‑ und Maskeninformationen nicht erhalten (Ebenenmasken, Ressourcen usw.).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Ermittelt die Opazität dieses Bildes.

**Returns:**
float - Der Deckkraftwert zwischen 0,0 (vollständig transparent) und 1,0 (vollständig undurchsichtig).
### getImageResources() {#getImageResources--}
```
public final ResourceBlock[] getImageResources()
```


Liest oder legt die PSD‑Bildressourcen fest.

Wert: Die PSD-Bildressourcen.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


Ermittelt den internen Daten-Transformer.

Wert: Der innere Daten-Transformer.

**Returns:**
com.aspose.internal.IInnerDataTransformer - der innere Daten-Transformer.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Ermittelt den Unterbrechungsmonitor.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerAndMask_internalized() {#getLayerAndMask-internalized--}
```
public final LayerAndMaskInfo getLayerAndMask_internalized()
```


Liest die Ebene und Maske.

Wert: Die Ebene und Maske.

**Returns:**
com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo
### getLayers() {#getLayers--}
```
public final Layer[] getLayers()
```


Liest oder legt die PSD‑Ebenen fest.

Wert: Die PSD-Ebenen.

--------------------

Hinweis: Wenn es keine Ebenen gibt, werden die anderen zugehörigen Informationen im Abschnitt für Ebenen‑ und Maskeninformationen nicht erhalten (Ebenenmasken, Ressourcen usw.).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getLinkedLayersManager() {#getLinkedLayersManager--}
```
public final LinkedLayersManager getLinkedLayersManager()
```


Liest den Manager für verknüpfte Ebenen.

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


Liefert oder setzt die maximal zulässige Zuweisung für das partielle Rotations‑Speichern.

**Returns:**
int - Die maximal zulässige Zuweisung für das partielle Rotations‑Speichern.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Liefert den Speicher‑Manager.

Wert: Der Speicher‑Manager.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - der Speicher‑Manager.
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Liefert Datum und Uhrzeit, wann das Ressourcen‑Bild zuletzt geändert wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| useDefault | boolean | Wenn auf  true  gesetzt, verwendet die Information aus FileInfo als Standardwert. |

**Returns:**
java.util.Date - Das Datum und die Uhrzeit, wann das Ressourcen‑Bild zuletzt geändert wurde.
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Liest die Optionen basierend auf den Einstellungen der Originaldatei. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es dann mit der  DataStreamSupporter.Save(string)  Methode speichern, wird ein PNG‑Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie als zweiten Parameter an die  Image.Save(string, ImageOptionsBase)  Methode.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Liefert das zu malende Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Ruft die Farbpalette ab. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Liefert ein Bildpixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die Pixel-x-Position. |
| y | int | Die Pixel-y-Position. |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Liefert oder setzt einen Wert, der angibt, ob die Bildkomponenten vor multipliziert werden müssen.

**Returns:**
boolean -  true  wenn die Bildkomponenten premultipliziert werden müssen; andernfalls,  false .
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Erstellt den privaten Schriftarten‑Cache.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - Der private Schriftarten-Cache.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Liefert die Informationen zum Fortschritts‑Ereignis‑Handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Liefert die Informationen zum Fortschritts‑Ereignis‑Handler.

Value: Die Informationen zum Fortschritts-Ereignishandler.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Liefert eine proportionale Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |
| newWidth | int | Die neue Breite. |

**Returns:**
int - Die proportionale Höhe.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Liefert eine proportionale Breite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |
| newHeight | int | Die neue Höhe. |

**Returns:**
int - Die proportionale Breite.
### getPsdHeader_internalized() {#getPsdHeader-internalized--}
```
public final PsdHeader getPsdHeader_internalized()
```


Liest oder legt den PSD‑Header fest.

Wert: Der PSD‑Header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Liefert oder setzt den benutzerdefinierten Farbkonverter.

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Liefert das Rohdatenformat.

Wert: Das Rohdatenformat.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Ruft die aktuellen Rohdaten-Einstellungen ab. Hinweis: Bei Verwendung dieser Einstellungen werden die Daten ohne Konvertierung geladen.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Liefert oder setzt den Ausweich‑Index, der verwendet wird, wenn der Paletten‑Index außerhalb des Bereichs liegt.

**Returns:**
int - Der Ersatzindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Liefert oder setzt den indizierten Farbkonverter.

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Liefert die Rohzeilengröße in Bytes.

**Returns:**
int - Die Rohzeilengröße in Bytes.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public final StreamSource getRgbColorProfile()
```


Liest oder setzt das RGB‑Farbprofil für CMYK‑PSD‑Bilder. Muss zusammen mit CmykColorProfile für eine korrekte Farbkonvertierung verwendet werden.

Wert: Das RGB‑Farbprofil.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Liest oder setzt den Rotationsmodus.

**Returns:**
int - Der Rotationsmodus.
### getSize() {#getSize--}
```
public Size getSize()
```


Liest die Bildgröße.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Ruft den Schrägwinkel ab. Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schrägwinkel beim Scannen zu bestimmen.

**Returns:**
float - Der Schrägwinkel in Grad.
### getSmartObjectProvider() {#getSmartObjectProvider--}
```
public final SmartObjectProvider getSmartObjectProvider()
```


Liest den Smart‑Object‑Provider.

Wert: Der Smart‑Object‑Provider.

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Ruft den Dateipfad des Quellbildes ab, falls es existiert. Gibt einen leeren String zurück, wenn der Quellpfad nicht gefunden werden kann.

**Returns:**
java.lang.String - Der Dateipfad des Quellbildes.
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


Liest die Synchronisationswurzel.

Value: Die Synchronisationswurzel.

**Returns:**
java.lang.Object
### getTimeline() {#getTimeline--}
```
public Timeline getTimeline()
```


Liest die Timeline ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) dieses [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
[Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Liest die transparente Farbe des Bildes.

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Liest oder setzt einen Wert, der angibt, ob die XMP-Metadaten aktualisiert werden sollen.

**Returns:**
boolean -  true  wenn die XMP-Metadaten aktualisiert werden; andernfalls,  false .
### getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates) {#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-}
```
public static ResourceBlock[] getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)
```


Liest aktualisierte Ressourcen mit einem brandneuen Ressourcenblock.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resources | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) | Die Ressourcen. |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | Die Ressource, die zu bestehenden Ressourcen hinzugefügt werden soll. |
| removeDuplicates | boolean | wenn auf  true  gesetzt, entfernt Ressourcen mit identischen IDs. |

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[] - Gibt ein Array mit aktualisierten Ressourcenblöcken zurück.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Liest einen Wert, der angibt, ob das Objekt eine Speicheroptimierungsstrategie verwendet

Value:  true  wenn das Objekt eine Speicheroptimierungsstrategie verwendet; andernfalls,  false .

**Returns:**
boolean - ein Wert, der angibt, ob das Objekt eine Speicheroptimierungsstrategie verwendet
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist.

**Returns:**
boolean -  true  wenn Rohdatenladen verwendet wird, wenn das Rohdatenladen verfügbar ist.; andernfalls,  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


Liest die verwendete Palette.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Liest die Venture-Lizenz.

**Returns:**
java.lang.Object - Die Venture-Lizenz als Objekt.
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Liest oder setzt die Version.

Wert: Die Version.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Liest oder legt die vertikale Auflösung in Pixel pro Zoll für dieses [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) fest.

**Returns:**
double
### getWidth() {#getWidth--}
```
public int getWidth()
```


Liest die Bildbreite.

Wert: Die Bildbreite.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Liest oder setzt die XMP-Metadaten.

Wert: Die XMP‑Metadaten.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation eines Bildes in seine Graustufen-Darstellung

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Liest oder setzt die vertikale Auflösung in Pixel pro Zoll dieses  RasterImage .

Wert:  true  wenn diese Instanz Alpha hat; andernfalls  false .

**Returns:**
boolean
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Liest einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Liest oder setzt einen Wert, der angibt, ob diese Bildinstanz nach dem Laden geändert wurde.

Wert:  true  wenn diese Instanz das Bild geändert hat; andernfalls  false .

**Returns:**
boolean
### hasTransparencyData() {#hasTransparencyData--}
```
public final boolean hasTransparencyData()
```


Liest oder legt einen Wert fest, der angibt, ob der erste Alphakanal die Transparenzdaten für das zusammengeführte Ergebnis enthält, wenn Ebenendaten angegeben werden.

Wert:  true  wenn der erste Alpha‑Kanal die Transparenzdaten für das zusammengeführte Ergebnis enthält, wenn Ebenendaten angegeben werden; andernfalls  false .

**Returns:**
boolean
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Liest einen Wert, der angibt, ob das Bild eine transparente Farbe hat.

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


Liest oder setzt den maximalen Fortschrittswert

Wert: Der maximale Fortschrittswert

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Zeigt den Fortschritt an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### insertLayerAfter_internalized(Layer layer, Layer layerToInsert) {#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void insertLayerAfter_internalized(Layer layer, Layer layerToInsert)
```


Fügt die Ebene nach der angegebenen Ebene mit allen Vorbereitungen ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Die Ebene. |
| layerToInsert | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Die einzufügende Ebene. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Liest einen Wert, der angibt, ob Bilddaten derzeit im Cache sind.

**Returns:**
boolean -  true  wenn Bilddaten zwischengespeichert sind; andernfalls  false .
### isFlatten() {#isFlatten--}
```
public final boolean isFlatten()
```


Liest einen Wert, der angibt, ob das PSD‑Bild abgeflacht ist.

Wert:  true  wenn diese Instanz abgeflacht ist; andernfalls  false .

**Returns:**
boolean
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Liest einen Wert, der angibt, ob das Laden von Rohdaten verfügbar ist.

**Returns:**
boolean -  true  wenn das Laden der Rohdaten verfügbar ist; andernfalls  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Liest einen Wert, der angibt, ob die Bildpalette verwendet wird.

Wert:  true  wenn die Palette im Bild verwendet wird; andernfalls  false .

**Returns:**
boolean - ein Wert, der angibt, ob die Bildpalette verwendet wird.
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


Lädt ein neues Bild aus dem angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Stream, aus dem das Bild geladen wird. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Lädt ein neues Bild aus dem angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Stream, aus dem das Bild geladen wird. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Die Ladeoptionen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Lädt ein neues Bild aus dem angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datei | java.io.RandomAccessFile | Die Datei, aus der das Bild geladen wird. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Lädt ein neues Bild aus dem angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datei | java.io.RandomAccessFile | Die Datei, aus der das Bild geladen wird. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Die Ladeoptionen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Lädt ein neues Bild aus der angegebenen Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, aus dem das Bild geladen wird. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Lädt ein neues Bild aus der angegebenen Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, aus dem das Bild geladen wird. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Die Ladeoptionen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Lädt 32‑Bit‑ARGB‑Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, aus dem die Pixel geladen werden. |

**Returns:**
int[] - Das geladene 32‑Bit‑ARGB‑Pixel‑Array.
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


Lädt 64‑Bit‑ARGB‑Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, aus dem die Pixel geladen werden. |

**Returns:**
long[] - Das geladene 64‑Bit‑ARGB‑Pixel‑Array.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Lädt Pixel im CMYK‑Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, aus dem die Pixel geladen werden. |

**Returns:**
int[] - Das geladene CMYK‑Pixel‑Array, präsentiert als 32‑Bit‑Ganzzahlwerte.
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


Lädt Pixel im CMYK‑Format. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere Methode  loadCmyk32Pixels(Rectangle) .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, aus dem die Pixel geladen werden. |

**Returns:**
com.aspose.psd.CmykColor[] - Das geladene CMYK‑Pixel‑Array.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Lädt 32‑Bit‑ARGB‑Pixel teilweise nach Paketen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das gewünschte Rechteck. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Der 32‑Bit‑ARGB‑Pixel‑Lader. |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Lädt Pixel teilweise nach Paketen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das gewünschte Rechteck. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | Der Pixel‑Lader. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Lädt Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, aus dem die Pixel geladen werden. |

**Returns:**
com.aspose.psd.Color[] - Das geladene Pixel-Array.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Lädt Rohbilddaten mit dem Teilverarbeitungs‑Mechanismus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Der gewünschte rechteckige Bereich des Bildes, aus dem Daten geladen werden sollen. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Die Rohdaten-Einstellungen. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Der Rohdaten‑Lader. |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Lädt Rohdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, aus dem Rohdaten geladen werden. |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | Die Ziel‑Bildgrenzen. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Die Rohdaten‑Einstellungen, die für geladene Daten verwendet werden. Hinweis: Wenn die Daten nicht im angegebenen Format vorliegen, wird eine Datenkonvertierung durchgeführt. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Der Rohdaten‑Lader. |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Lädt ein neues Bild aus dem angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Der Stream, aus dem das Bild geladen wird. |
| startPosition | long | Die Startposition, von der das Bild geladen wird. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Lädt ein neues Bild aus dem angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Der Stream, aus dem das Bild geladen wird. |
| startPosition | long | Die Startposition, von der das Bild geladen wird. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Die Ladeoptionen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### mergeLayers(Layer bottomLayer, Layer topLayer) {#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final Layer mergeLayers(Layer bottomLayer, Layer topLayer)
```


Führt die Ebenen zusammen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bottomLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Die untere Ebene. |
| topLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Die obere Ebene. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Bottom layer after the merge
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Normalisiert den Winkel. Diese Methode ist auf gescannte Textdokumente anwendbar, um die verzerrte Aufnahme zu korrigieren. Diese Methode verwendet die Methoden [.getSkewAngle](../../null/\#getSkewAngle) und [.rotate(float)](../../null/\#rotate-float-).

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normalisiert den Winkel. Diese Methode ist auf gescannte Textdokumente anwendbar, um die verzerrte Aufnahme zu korrigieren. Diese Methode verwendet die Methoden [.getSkewAngle](../../null/\#getSkewAngle) und [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resizeProportionally | boolean | Wenn auf true gesetzt, wird die Bildgröße gemäß den Projektionen des rotierten Rechtecks (Eckpunkte) angepasst; andernfalls bleiben die Abmessungen unverändert und nur der Bildinhalt wird rotiert. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Farbe des Hintergrunds. |

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


Aufrufen, wenn der Container dieses [Image](../../com.aspose.psd/image) festgelegt wurde.

### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scanLineIndex | int | Nullbasierter Index der Scan‑Zeile. |

**Returns:**
int[] - Das 32‑Bit‑ARGB‑Farbwert‑Array der Scan‑Zeile.
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scanLineIndex | int | Nullbasierter Index der Scan‑Zeile. |

**Returns:**
com.aspose.psd.Color[] - Das Pixel‑Farbwert‑Array der Scan‑Zeile.
### removeGlobalTextEngineResource_internalized() {#removeGlobalTextEngineResource-internalized--}
```
public final void removeGlobalTextEngineResource_internalized()
```


Entfernt die globale Text‑Engine‑Ressource – Die Methode wird für einige textbasierte PSD‑Dateien verwendet, die nach der Verarbeitung nicht in Adobe Photoshop geöffnet werden können (hauptsächlich bei fehlenden Schriftarten in Text‑Ebenen). Nach der Verwendung dieser Option muss der Benutzer im geöffneten Photoshop‑Dokument Folgendes ausführen: Menü "Text" -> "Fehlende Schriften verarbeiten". Nach diesem Vorgang wird sämtlicher Text wieder angezeigt. Bitte beachten Sie, dass dieser Vorgang einige endgültige Layout‑Änderungen verursachen kann.

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | Alte Farbe, die ersetzt werden soll. |
| oldColorDiff | byte | Erlaubte Differenz der alten Farbe, um den ersetzten Farbton zu erweitern. |
| newColor | [Color](../../com.aspose.psd/color) | Neue Farbe, mit der die alte Farbe ersetzt wird. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldColorArgb | int | Alter Farb-ARGB-Wert, der ersetzt werden soll. |
| oldColorDiff | byte | Erlaubte Differenz der alten Farbe, um den ersetzten Farbton zu erweitern. |
| newColorArgb | int | Neuer Farb-ARGB-Wert, mit dem die alte Farbe ersetzt wird. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Ersetzt alle nicht-transparenten Farben durch die neue Farbe und bewahrt den ursprünglichen Alpha-Wert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | Neue Farbe, mit der nicht-transparente Farben ersetzt werden. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Ersetzt alle nicht-transparenten Farben durch die neue Farbe und bewahrt den ursprünglichen Alpha-Wert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorArgb | int | Neuer Farb-ARGB-Wert, mit dem nicht-transparente Farben ersetzt werden. |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Skaliert das Bild. Der Standardwert  ResizeType.LeftTopToLeftTop  wird verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Skaliert das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Die Skalierungseinstellungen. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Skaliert das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Der Skalierungstyp. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Ändert die Höhe proportional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newHeight | int | Die neue Höhe. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Ändert die Höhe proportional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Die Bildeinstellungen für die Skalierung. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Ändert die Höhe proportional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Typ der Skalierung. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Ändert die Breite proportional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Ändert die Breite proportional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Die Bildeinstellungen für die Skalierung. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ändert die Breite proportional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| resizeType | int | Typ der Skalierung. |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


Skaliert die Ebene mit dem angegebenen inversen Faktor. (neue Breite = alte Breite / Faktor; neue Höhe = alte Höhe / Faktor)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleX | double | Der Skalierungsfaktor X. |
| scaleY | double | Der Skalierungsfaktor Y. |
| resizeType | int | Typ der Skalierung. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Bild um das Zentrum drehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Bild um das Zentrum drehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resizeProportionally | boolean | Wenn auf true gesetzt, wird die Bildgröße gemäß den Projektionen des rotierten Rechtecks (Eckpunkte) angepasst; andernfalls bleiben die Abmessungen unverändert und nur der Bildinhalt wird rotiert. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Farbe des Hintergrunds. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


Speichert die Bilddaten in den zugrunde liegenden Stream.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Speichert die Objektdaten in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Stream, in dem die Objektdaten gespeichert werden. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Stream, in dem die Bilddaten gespeichert werden. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Speicheroptionen. |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Stream, in dem die Bilddaten gespeichert werden. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Speicheroptionen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck der Zielbildgrenzen. Setzen Sie das leere Rechteck, um Quellgrenzen zu verwenden. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Speichert die Objektdaten in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datei | java.io.RandomAccessFile | Der Stream, in dem die Objektdaten gespeichert werden. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datei | java.io.RandomAccessFile | Die Datei, in die die Bilddaten gespeichert werden. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Optionen. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datei | java.io.RandomAccessFile | Die Datei, in die die Bilddaten gespeichert werden. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Speicheroptionen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck mit den Zielbildgrenzen. Setzen Sie das leere Rechteck, um die Quellgrenzen zu verwenden. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Speichert die Objektdaten am angegebenen Speicherort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, in dem die Daten des Objekts gespeichert werden sollen. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Speichert die Objektdaten am angegebenen Speicherort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, in dem die Daten des Objekts gespeichert werden sollen. |
| Überschreiben | boolean | Wenn auf true gesetzt, wird der Dateiinhalt überschrieben, andernfalls wird angehängt. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Optionen. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Optionen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck mit den Zielbildgrenzen. Setzen Sie das leere Rechteck, um die Quellgrenzen zu verwenden. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Speichert die 32‑Bit‑ARGB‑Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, in dem die Pixel gespeichert werden sollen. |
| Pixel | int[] | Das 32‑Bit‑ARGB‑Pixel‑Array. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Speichert die Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, in dem die Pixel gespeichert werden sollen. |
| Pixel | int[] | Die CMYK‑Pixel, dargestellt als 32‑Bit‑Ganzzahlwerte. |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Speichert die Pixel. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere Methode saveCmyk32Pixels(Rectangle, int[]).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, in dem die Pixel gespeichert werden sollen. |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Das CMYK‑Pixel‑Array. |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Speichert die Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck, in dem die Pixel gespeichert werden sollen. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Das Pixel‑Array. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Speichert die Rohdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Rohdaten. |
| dataOffset | int | Der Anfangs‑Rohdaten‑Versatz. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rohdaten‑Rechteck. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Die Rohdaten‑Einstellungen, in denen sich die Daten befinden. |

### saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport) {#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)
```


Speichert die Bilddaten in den angegebenen Stream unter Verwendung der angegebenen Speicheroptionen und Grenzen. Optional werden nur die angegebenen Ebenen für die Render‑Vorschau exportiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Der Stream, in dem die Bilddaten gespeichert werden. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die zu verwendenden Speicheroptionen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Zielrechteck für die Bildgrenzen. Auf  Rectangle.Empty  setzen, um die Quellgrenzen zu verwenden. |
| layersToExport | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Die spezifischen Ebenen, die exportiert werden sollen. Ein  null  Wert bedeutet das Standardverhalten mit allen Ebenen. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Der Stream, in dem die Bilddaten gespeichert werden. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Speicheroptionen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck der Zielbildgrenzen. Setzen Sie das leere Rechteck, um Quellgrenzen zu verwenden. |

### setActiveLayer(Layer value) {#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void setActiveLayer(Layer value)
```


Liest oder setzt die aktive Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die Pixel-x-Position. |
| y | int | Die Pixel-y-Position. |
| argb32Color | int | Das 32‑Bit‑ARGB‑Pixel für die angegebene Position. |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true, wenn die automatische Palettenanpassung aktiviert ist; andernfalls false. |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Liest oder setzt einen Wert für die Hintergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBackgroundContents_internalized(RawColor value) {#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents_internalized(RawColor value)
```


Liest oder setzt die Hintergrundfarbe. Sie ist unter transparenten Objekten zu sehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße, in Megabyte. Ein nicht-positiver Wert bedeutet keine Speicherbegrenzung für interne Puffer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setCmykColorProfile(StreamSource value)
```


Liest oder setzt das CMYK-Farbprofil für CMYK-PSD-Bilder. Es muss zusammen mit RgbColorProfile für eine korrekte Farbumwandlung verwendet werden.

Wert: Das CMYK-Farbprofil.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Liest oder setzt den Farbmodus.

Wert: Der Farbmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Setzt den Image‑Container.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Der Image‑Container. |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


Setzt den Datenlader direkt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | Der Datenlader. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Setzt den Datenstream des Objekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Datenstrom des Objekts. |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


Setzt die Palette an format‑spezifische Stellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Neue 32‑Bit‑ARGB‑Palette. |

**Returns:**
boolean
### setGlobalAngle(int value) {#setGlobalAngle-int-}
```
public final void setGlobalAngle(int value)
```


Der globale Winkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setGlobalLayerResources(LayerResource[] value) {#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setGlobalLayerResources(LayerResource[] value)
```


Liest oder setzt die globalen Ebenenressourcen.

Wert: Die globalen Ebenenressourcen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setGrayColorProfile(StreamSource value) {#setGrayColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setGrayColorProfile(StreamSource value)
```


Das GRAY (monochrome) Farbprofil für Graustufen‑PSD‑Bilder.

Wert: Das GRAY (monochrome) Farbprofil.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Liest oder legt die horizontale Auflösung in Pixel pro Zoll für dieses [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Setzt einen Wert, der angibt, ob [ignore after save].

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true  wenn [ignore after save]; andernfalls,  false . |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Bildinstanz nach dem Laden geändert wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true  wenn diese Instanz das Bild geändert hat; andernfalls,  false . |

### setImageResources(ResourceBlock[] value) {#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setImageResources(ResourceBlock[] value)
```


Liest oder legt die PSD‑Bildressourcen fest.

Wert: Die PSD-Bildressourcen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


Setzt den internen Datentransformator.

Wert: Der innere Daten-Transformer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.internal.IInnerDataTransformer | der innere Daten-Transformer. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Setzt den Unterbrechungsmonitor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | der Interrupt-Monitor. |

### setLayers(Layer[] value) {#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void setLayers(Layer[] value)
```


Liest oder legt die PSD‑Ebenen fest.

Wert: Die PSD-Ebenen.

--------------------

Hinweis: Wenn es keine Ebenen gibt, werden die anderen zugehörigen Informationen im Abschnitt für Ebenen‑ und Maskeninformationen nicht erhalten (Ebenenmasken, Ressourcen usw.).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


Liefert oder setzt die maximal zulässige Zuweisung für das partielle Rotations‑Speichern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die maximal zulässige Zuweisung für das partielle Rotations‑Speichern. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Setzt den Speicher‑Manager.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | Der Speicher-Manager. |
| needDispose | boolean | wenn auf  true  gesetzt [need dispose]. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die Farbpalette. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Legt die Bildpalette fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die zu setzende Palette. |
| updateColors | boolean | wenn auf  true  gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben Farbindizes unverändert. Hinweis: Unveränderte Indizes können das Bild beim Laden zum Absturz bringen, wenn einige Indizes keine entsprechenden Paletteneinträge haben. |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


Setzt ein Bildpixel für die angegebene Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die Pixel-x-Position. |
| y | int | Die Pixel-y-Position. |
| color | [Color](../../com.aspose.psd/color) | Die Pixel‑Farbe für die angegebene Position. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Liefert oder setzt einen Wert, der angibt, ob die Bildkomponenten vor multipliziert werden müssen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true  wenn die Bildkomponenten vor multipliziert werden müssen; andernfalls,  false . |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Liefert oder setzt den benutzerdefinierten Farbkonverter.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | Der benutzerdefinierte Farbkonverter |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Liefert oder setzt den Ausweich‑Index, der verwendet wird, wenn der Paletten‑Index außerhalb des Bereichs liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Ausweich‑Index, der verwendet wird, wenn der Paletten‑Index außerhalb des Bereichs liegt |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Liefert oder setzt den indizierten Farbkonverter.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | Der indizierte Farbkonverter |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Legt die Auflösung für dieses [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dpiX | double | Die horizontale Auflösung, in Punkten pro Zoll, des RasterImage. |
| dpiY | double | Die vertikale Auflösung, in Punkten pro Zoll, des RasterImage. |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setRgbColorProfile(StreamSource value)
```


Liest oder setzt das RGB‑Farbprofil für CMYK‑PSD‑Bilder. Muss zusammen mit CmykColorProfile für eine korrekte Farbkonvertierung verwendet werden.

Wert: Das RGB‑Farbprofil.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Liest oder setzt den Rotationsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Rotationsmodus. |

### setTransparencyData(boolean value) {#setTransparencyData-boolean-}
```
public final void setTransparencyData(boolean value)
```


Liest oder legt einen Wert fest, der angibt, ob der erste Alphakanal die Transparenzdaten für das zusammengeführte Ergebnis enthält, wenn Ebenendaten angegeben werden.

Wert:  true  wenn der erste Alpha‑Kanal die Transparenzdaten für das zusammengeführte Ergebnis enthält, wenn Ebenendaten angegeben werden; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Liest einen Wert, der angibt, ob das Bild eine transparente Farbe hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


Liest die transparente Farbe des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die XMP-Metadaten aktualisiert werden sollen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true, wenn die XMP-Metadaten aktualisiert werden; andernfalls false. |

### setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized) {#setUsePhotoshopCompatibilityMode-internalized-boolean-}
```
public void setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| usePhotoshopCompatibilityMode_internalized | boolean |  |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true, wenn das Laden roher Daten verwendet wird, wenn das Laden roher Daten verfügbar ist; andernfalls false. |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Legt die Venture‑Lizenz fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ventureLicense | java.lang.Object | Die Venture-Lizenz. |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Liest oder setzt die Version.

Wert: Die Version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Liest oder legt die vertikale Auflösung in Pixel pro Zoll für dieses [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Liest oder setzt die XMP-Metadaten.

Wert: Die XMP‑Metadaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Konvertiert das Rasterbild in das Bitmap.

**Returns:**
java.awt.image.BufferedImage - Das Bitmap
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Schreibt die gesamte Scanzeile an den angegebenen Scanzeilenindex.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scanLineIndex | int | Nullbasierter Index der Scan‑Zeile. |
| argb32Pixels | int[] | Das 32‑Bit‑ARGB‑Farbenarray zum Schreiben. |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Schreibt die gesamte Scanzeile an den angegebenen Scanzeilenindex.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scanLineIndex | int | Nullbasierter Index der Scan‑Zeile. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Das Pixel‑Farbenarray zum Schreiben. |

