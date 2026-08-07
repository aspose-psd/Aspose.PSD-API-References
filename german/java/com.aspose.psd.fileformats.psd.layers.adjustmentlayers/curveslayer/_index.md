---
title: "CurvesLayer"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Kurven‑Einstellungsebene"
type: docs
weight: 17
url: /de/java/com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage), [com.aspose.psd.fileformats.psd.layers.Layer](../../com.aspose.psd.fileformats.psd.layers/layer), [com.aspose.psd.fileformats.psd.layers.adjustmentlayers.AdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer)
```
public class CurvesLayer extends AdjustmentLayer
```

Kurven‑Einstellungsebene
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BlendSignature](#BlendSignature) | Stellt die Signatur des Mischmodus dar. |
| [LayerHeaderSize](#LayerHeaderSize) | Die Größe des Ebenen-Headers. |
| [OnCreate_internalized](#OnCreate-internalized) | Tritt auf, wenn das Bild geladen wurde |
| [OnLoad_internalized](#OnLoad-internalized) | Tritt auf, wenn das Bild durch createFirstSupportedLoader geladen wurde |
| [OnSave_internalized](#OnSave-internalized) | Tritt auf, wenn das Bild geladen oder gespeichert wurde |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Tritt auf, wenn ein Guthaben verwendet wurde |
| [resources_internalized](#resources-internalized) | Die Ressourcen |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [<T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)](#-T-tryGetResource-internalized-java.lang.Class-T--T---) | Liefert die mit dem angegebenen Typ verknüpfte Ressource. |
| [addLayerMask(LayerMaskData layerMask)](#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Fügt die Maske zur aktuellen Ebene hinzu. |
| [addResource_internalized(LayerResource resource)](#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Fügt die Ressource hinzu. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Anpassung der Helligkeit für das Bild. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Bildkontrast |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gammakorrektur eines Bildes. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gammakorrektur eines Bildes. |
| [applyLayerMask()](#applyLayerMask--) | Wendet die Ebenenmaske auf die Ebene an und löscht anschließend die Maske. |
| [applyLayerState_internalized(LayerState layerState)](#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-) | Wendet die Ebenenstil‑Einstellung aus dem Eingabe-[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) auf die aktuelle [Layer](../../com.aspose.psd.fileformats.psd.layers/layer)-Instanz an. |
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
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Konvertiert zu aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Erstellt ein neues Bild mit den angegebenen Bildern als Seiten. |
| [createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) | Erstellt die neue Instanz der Klasse [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [createLayerState_internalized()](#createLayerState-internalized--) | Erstellt die neue Instanz von [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) basierend auf den aktuellen Werten von [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(PsdHeader header, LayerResource[] resources)](#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.fileformats.psd.layers.LayerResource---) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
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
| [drawImage(Point location, RasterImage image)](#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-) | Zeichnet das Bild auf die Ebene. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene Objekt diesem Exemplar gleich ist. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filtert das angegebene Rechteck. |
| [findAssignableResource_internalized(System.Type type)](#findAssignableResource-internalized-com.aspose.ms.System.Type-) | Findet die zuweisbare Ressource. |
| [findPattResource_internalized()](#findPattResource-internalized--) | Findet die PattResource. |
| [findResource_internalized(int typeToolKey)](#findResource-internalized-int-) | Findet die Ressource anhand des eindeutigen Schlüssels. |
| [getAbsoluteBounds_internalized()](#getAbsoluteBounds-internalized--) | Liest oder setzt die absoluten Grenzen. |
| [getAdjustmentLayerType_internalized()](#getAdjustmentLayerType-internalized--) | Liest den Typ der Anpassungsebene. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Liest ein 32‑Bit‑ARGB‑Pixel eines Bildes. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Gibt einen Wert zurück, der angibt, ob die automatische Palettenanpassung aktiviert ist. |
| [getBackgroundColor()](#getBackgroundColor--) | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Liest die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [getBlendClippedElements()](#getBlendClippedElements--) | Liest oder setzt das Blending des beschnittenen Elements. |
| [getBlendModeKey()](#getBlendModeKey--) | Liest oder setzt den Schlüssel des Mischmodus. |
| [getBlendModeSignature()](#getBlendModeSignature--) | Liest die Signatur des Mischmodus. |
| [getBlendingOptions()](#getBlendingOptions--) | Liest die Blending‑Optionen. |
| [getBottom()](#getBottom--) | Liest oder setzt die Position der unteren Ebene. |
| [getBounds()](#getBounds--) | Liest die Bildgrenzen. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liest den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [getBytesPerRowForFullMask_internalized(int bitDepth)](#getBytesPerRowForFullMask-internalized-int-) | Liest die Bytes pro Zeile für den Vollmaskenmodus. |
| [getBytesPerRowForMask_internalized(int bitDepth)](#getBytesPerRowForMask-internalized-int-) | Liest die Bytes pro Zeile. |
| [getBytesPerRow_internalized(int bitDepth)](#getBytesPerRow-internalized-int-) | Liest die Bytes pro Zeile. |
| [getChannelInformation()](#getChannelInformation--) | Liest oder setzt die Kanalinformationen. |
| [getChannelsCount()](#getChannelsCount--) | Liest die Kanalanzahl der Ebene. |
| [getClass()](#getClass--) |  |
| [getClipping()](#getClipping--) | Liest oder setzt das Ebenen‑Clipping. |
| [getContainer()](#getContainer--) | Liest den Image‑Container. |
| [getCurvesManager()](#getCurvesManager--) | Ruft den Kurven-Manager ab. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Liest den Datenstrom des Objekts. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Liest die tiefgreifende Palettenanpassung. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Liest das Standard‑32‑Bit‑ARGB‑Pixel‑Array. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Liest die Standardoptionen. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Liest das Standard‑Pixel‑Array unter Verwendung eines partiellen Pixel‑Loaders. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Liest das Standard‑Rohdaten‑Array unter Verwendung eines partiellen Pixel‑Loaders. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Liest das Standard‑Rohdaten‑Array. |
| [getDisplayName()](#getDisplayName--) | Liest den Anzeigenamen der Ebene. |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getExtraLength()](#getExtraLength--) | Ermittelt die Länge der zusätzlichen Ebeneninformationen in Bytes. |
| [getFileFormat()](#getFileFormat--) | Ermittelt einen Wert des Dateiformats |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Ermittelt das Dateiformat. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Ermittelt das Dateiformat. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Ermittelt das Dateiformat. |
| [getFillOpacity()](#getFillOpacity--) | Ermittelt oder legt die Füll-Opazität fest. |
| [getFiller()](#getFiller--) | Ermittelt oder legt den Ebenenfüller fest. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [getFlags()](#getFlags--) | Ermittelt oder legt die Ebenen-Flags fest. |
| [getFoldersHierarchy_internalized()](#getFoldersHierarchy-internalized--) | Ermittelt die Liste der Ordnerhierarchie von [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) des aktuellen Layers. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Ermittelt die Palette aus formatabhängigen Bereichen |
| [getGUID_internalized()](#getGUID-internalized--) | Ermittelt die eindeutige Kennung dieser Layer-Instanz. |
| [getHeader_internalized()](#getHeader-internalized--) | Ermittelt oder legt den Header fest. |
| [getHeight()](#getHeight--) | Ermittelt die Bildhöhe. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Ermittelt oder legt die horizontale Auflösung in Pixel pro Zoll dieses  RasterImage  fest. |
| [getImageOpacity()](#getImageOpacity--) | Ermittelt die Opazität dieses Bildes. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Ermittelt den internen Daten-Transformer. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Ermittelt den Unterbrechungsmonitor. |
| [getLayerBlendingRangesData()](#getLayerBlendingRangesData--) | Ermittelt oder legt die Daten der Ebenen‑Mischbereiche fest. |
| [getLayerCreationDateTime()](#getLayerCreationDateTime--) | Ermittelt oder legt das Erstellungsdatum und die -zeit der Ebene fest. |
| [getLayerCreationDateTime_internalized()](#getLayerCreationDateTime-internalized--) |  |
| [getLayerLock()](#getLayerLock--) | Ermittelt oder legt die Ebenensperre fest. |
| [getLayerMaskData()](#getLayerMaskData--) | Ermittelt oder legt die Ebenenmaskendaten fest. |
| [getLayerOptions()](#getLayerOptions--) | Ermittelt die Ebenenoptionen. |
| [getLayerPalette_internalized()](#getLayerPalette-internalized--) | Ermittelt oder legt die Ebenenpalette fest. |
| [getLayerType_internalized()](#getLayerType-internalized--) | Liefert den Typ der Ebene. |
| [getLeft()](#getLeft--) | Liefert oder setzt die linke Ebenenposition. |
| [getLength()](#getLength--) | Liefert die gesamte Ebenenlänge in Bytes. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Liefert oder setzt die maximal zulässige Zuweisung für das partielle Rotations‑Speichern. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Liefert den Speicher‑Manager. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Liefert Datum und Uhrzeit, wann das Ressourcen‑Bild zuletzt geändert wurde. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getName()](#getName--) | Liefert oder setzt den Ebenennamen. |
| [getOpacity()](#getOpacity--) | Liefert oder setzt die Ebenen‑Deckkraft. |
| [getOpacityTotal_internalized()](#getOpacityTotal-internalized--) | Liefert die Gesamtdeckkraft. |
| [getOriginalOptions()](#getOriginalOptions--) | Liefert die Optionen basierend auf den ursprünglichen Dateieinstellungen. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Liefert das zu malende Bild. |
| [getPalette()](#getPalette--) | Liefert die Farbpalette. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Liefert ein Bildpixel. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Liefert oder setzt einen Wert, der angibt, ob die Bildkomponenten vor multipliziert werden müssen. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Erstellt den privaten Schriftarten‑Cache. |
| [getProcessor_internalized()](#getProcessor-internalized--) | Liest den Prozessor. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Liefert die Informationen zum Fortschritts‑Ereignis‑Handler. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Liefert die Informationen zum Fortschritts‑Ereignis‑Handler. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Liefert eine proportionale Höhe. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Liefert eine proportionale Breite. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Liefert oder setzt den benutzerdefinierten Farbkonverter. |
| [getRawDataFormat()](#getRawDataFormat--) | Liefert das Rohdatenformat. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Liefert oder setzt den Ausweich‑Index, der verwendet wird, wenn der Paletten‑Index außerhalb des Bereichs liegt. |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Liefert oder setzt den indizierten Farbkonverter. |
| [getRawLineSize()](#getRawLineSize--) | Liefert die Rohzeilengröße in Bytes. |
| [getResources()](#getResources--) | Liefert oder setzt die Ebenen‑Ressourcen. |
| [getRight()](#getRight--) | Liefert oder setzt die rechte Ebenenposition. |
| [getRotateMode()](#getRotateMode--) | Liest oder setzt den Rotationsmodus. |
| [getSheetColorHighlight()](#getSheetColorHighlight--) | Liest oder setzt die dekorative Blattfarb-Hervorhebung in der Ebenenliste |
| [getSize()](#getSize--) | Liest die Bildgröße. |
| [getSkewAngle()](#getSkewAngle--) | Liest den Schrägwinkel. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Liest den Dateipfad des Quellbildes, falls es existiert. |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Liest die Synchronisationswurzel. |
| [getTop()](#getTop--) | Liest oder setzt die Position der obersten Ebene. |
| [getTransparentColor()](#getTransparentColor--) | Liest die transparente Farbe des Bildes. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Liest oder setzt einen Wert, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Liest einen Wert, der angibt, ob das Objekt eine Speicheroptimierungsstrategie verwendet |
| [getUseRawData()](#getUseRawData--) | Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Liest die verwendete Palette. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Liest die Venture-Lizenz. |
| [getVerticalResolution()](#getVerticalResolution--) | Liest oder setzt die vertikale Auflösung in Pixel pro Zoll dieses  RasterImage . |
| [getWidth()](#getWidth--) | Liest die Bildbreite. |
| [getXmpData()](#getXmpData--) | Liest oder setzt die XMP-Metadaten. |
| [grayscale()](#grayscale--) | Transformation eines Bildes in seine Graustufen-Darstellung |
| [hasAlpha()](#hasAlpha--) | Liest einen Wert, der angibt, ob diese Instanz Alpha enthält. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Liest einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Liest oder setzt einen Wert, der angibt, ob diese Bildinstanz nach dem Laden geändert wurde. |
| [hasTransparentColor()](#hasTransparentColor--) | Liest einen Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Liest oder setzt den maximalen Fortschrittswert |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Zeigt den Fortschritt an. |
| [insertResource_internalized(int index, LayerResource resource)](#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Fügt eine Ressource in die Resources‑Sammlung ein. |
| [isCached()](#isCached--) | Liest einen Wert, der angibt, ob Bilddaten derzeit im Cache sind. |
| [isContinuousManagerUsed()](#isContinuousManagerUsed--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz als kontinuierlicher Manager verwendet wird. |
| [isDiscreteManagerUsed()](#isDiscreteManagerUsed--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz als diskreter Manager verwendet wird. |
| [isLayerValid_internalized()](#isLayerValid-internalized--) | Ermittelt, ob die Ebene für das Speichern in einer Datei gültig ist. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Liest einen Wert, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| [isUsePalette()](#isUsePalette--) | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| [isVisible()](#isVisible--) | Liest oder setzt einen Wert, der angibt, ob die Ebene sichtbar ist |
| [isVisibleInGroup()](#isVisibleInGroup--) | Liest einen Wert, der angibt, ob diese Instanz in einer Gruppe sichtbar ist (Wenn die Ebene nicht in einer Gruppe ist, bedeutet das die Root-Gruppe). |
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
| [mergeLayerTo(Layer layerToMergeInto)](#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-) | Führt die Ebene mit der angegebenen Ebene zusammen |
| [normalizeAngle()](#normalizeAngle--) | Normalisiert den Winkel. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normalisiert den Winkel. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Aufrufen, wenn der Container dieses  Image  gesetzt wurde. |
| [processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#processAdjustmentLayer-internalized-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Verarbeitet die Anpassungsebene. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Liest die gesamte Scanzeile anhand des angegebenen Scanzeilen‑Index. |
| [removeResource_internalized(LayerResource resource)](#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Entfernt die Ressource. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Ersetzt alle nicht transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Ersetzt alle nicht transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Skaliert das Bild. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Skaliert das Bild. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Skaliert das Bild. |
| [resizeChannelsData_internalized(Rectangle rect)](#resizeChannelsData-internalized-com.aspose.psd.Rectangle-) | Führt die Daten zusammen. |
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
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Speichert die Objektdaten in den angegebenen Stream. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)](#save-internalized-com.aspose.psd.StreamContainer-int-int-) | Speichert Daten in den angegebenen Stream‑Container. |
| [setAbsoluteBounds_internalized(Rectangle value)](#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-) | Liest oder setzt die absoluten Grenzen. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| [setBlendClippedElements(boolean value)](#setBlendClippedElements-boolean-) | Liest oder setzt das Blending des beschnittenen Elements. |
| [setBlendModeKey(long value)](#setBlendModeKey-long-) | Liest oder setzt den Schlüssel des Mischmodus. |
| [setBottom(int value)](#setBottom-int-) | Liest oder setzt die Position der unteren Ebene. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setChannelInformation(ChannelInformation[] value)](#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Liest oder setzt die Kanalinformationen. |
| [setClipping(byte value)](#setClipping-byte-) | Liest oder setzt das Ebenen‑Clipping. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Setzt den Image‑Container. |
| [setContinuousManagerUsed(boolean value)](#setContinuousManagerUsed-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz als kontinuierlicher Manager verwendet wird. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Setzt den Datenlader direkt. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Setzt den Datenstream des Objekts. |
| [setDiscreteManagerUsed(boolean value)](#setDiscreteManagerUsed-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz als diskreter Manager verwendet wird. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Liest oder setzt den Anzeigenamen der Ebene. |
| [setFillOpacity(int value)](#setFillOpacity-int-) | Liest die Füll‑Deckkraft. |
| [setFiller(byte value)](#setFiller-byte-) | Ermittelt oder legt den Ebenenfüller fest. |
| [setFlags(byte value)](#setFlags-byte-) | Ermittelt oder legt die Ebenen-Flags fest. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Setzt die Palette an format‑spezifische Stellen. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ermittelt oder legt den Header fest. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Ermittelt oder legt die horizontale Auflösung in Pixel pro Zoll dieses  RasterImage  fest. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Setzt einen Wert, der angibt, ob [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Bildinstanz nach dem Laden geändert wurde. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Setzt den internen Datentransformator. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Setzt den Unterbrechungsmonitor. |
| [setLayerBlendingRangesData(LayerBlendingRangesData value)](#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-) | Ermittelt oder legt die Daten der Ebenen‑Mischbereiche fest. |
| [setLayerCreationDateTime(Date value)](#setLayerCreationDateTime-java.util.Date-) | Ermittelt oder legt das Erstellungsdatum und die -zeit der Ebene fest. |
| [setLayerCreationDateTime_internalized(System.DateTime value)](#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-) |  |
| [setLayerLock(int value)](#setLayerLock-int-) | Liest oder setzt die Ebenensperre (Hinweis: Wenn das Flag LayerFlags.TransparencyProtected gesetzt ist, wird es durch das Ebenensperr‑Flag überschrieben). |
| [setLayerMaskData(LayerMaskData value)](#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Ermittelt oder legt die Ebenenmaskendaten fest. |
| [setLayerPalette_internalized(IColorPalette value)](#setLayerPalette-internalized-com.aspose.psd.IColorPalette-) | Ermittelt oder legt die Ebenenpalette fest. |
| [setLeft(int value)](#setLeft-int-) | Liefert oder setzt die linke Ebenenposition. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Liefert oder setzt die maximal zulässige Zuweisung für das partielle Rotations‑Speichern. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Setzt den Speicher‑Manager. |
| [setName(String name)](#setName-java.lang.String-) | Legt den Ebenennamen fest. |
| [setName_internalized(String value)](#setName-internalized-java.lang.String-) | Liefert oder setzt den Ebenennamen. |
| [setOpacity(byte value)](#setOpacity-byte-) | Liefert oder setzt die Ebenen‑Deckkraft. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Legt die Farbpalette fest. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Legt die Bildpalette fest. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Setzt ein Bildpixel für die angegebene Position. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Liefert oder setzt einen Wert, der angibt, ob die Bildkomponenten vor multipliziert werden müssen. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Liefert oder setzt den benutzerdefinierten Farbkonverter. |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Liefert oder setzt den Ausweich‑Index, der verwendet wird, wenn der Paletten‑Index außerhalb des Bereichs liegt. |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Liefert oder setzt den indizierten Farbkonverter. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Legt die Auflösung für dieses RasterImage fest. |
| [setResources(LayerResource[] value)](#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Liefert oder setzt die Ebenen‑Ressourcen. |
| [setRight(int value)](#setRight-int-) | Liefert oder setzt die rechte Ebenenposition. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Liest oder setzt den Rotationsmodus. |
| [setSheetColorHighlight(short value)](#setSheetColorHighlight-short-) | Liest oder setzt die dekorative Blattfarb-Hervorhebung in der Ebenenliste |
| [setTop(int value)](#setTop-int-) | Liest oder setzt die Position der obersten Ebene. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Liest einen Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Liest die transparente Farbe des Bildes. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Liest oder setzt einen Wert, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Alle Aspose-Produkte sollten diese Methode implementieren. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Liest oder setzt die vertikale Auflösung in Pixel pro Zoll dieses  RasterImage . |
| [setVisible(boolean value)](#setVisible-boolean-) | Liest oder setzt einen Wert, der angibt, ob die Ebene sichtbar ist |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Liest oder setzt die XMP-Metadaten. |
| [shallowCopy()](#shallowCopy--) | Erstellt eine flache Kopie der aktuellen Ebene. |
| [toBitmap()](#toBitmap--) | Konvertiert das Rasterbild in das Bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [updateBlendingOptions_internalized(PattResource pattResource)](#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Aktualisiert die Blending-Optionen, nachdem sich Layer- oder globale Ressourcen geändert haben. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Schreibt die gesamte Scanzeile an den angegebenen Scanzeilenindex. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Schreibt die gesamte Scanzeile an den angegebenen Scanzeilenindex. |
### BlendSignature {#BlendSignature}
```
public static final int BlendSignature
```


Stellt die Signatur des Mischmodus dar.

### LayerHeaderSize {#LayerHeaderSize}
```
public static final int LayerHeaderSize
```


Die Größe des Ebenen-Headers.

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

### resources_internalized {#resources-internalized}
```
public ResourceNest resources_internalized
```


Die Ressourcen

### <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource) {#-T-tryGetResource-internalized-java.lang.Class-T--T---}
```
public final boolean <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)
```


Liefert die mit dem angegebenen Typ verknüpfte Ressource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | resource | T[] | Wenn diese Methode zurückkehrt, enthält sie die Ressource, die dem angegebenen Schlüsseltyp zugeordnet ist, falls der Schlüssel gefunden wird; andernfalls wird null zurückgegeben. |

T : Der Schlüsseltyp des abzurufenden Werts. |

**Returns:**
boolean -   true, wenn eine Ressource des angegebenen Typs enthalten ist; andernfalls false.
### addLayerMask(LayerMaskData layerMask) {#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void addLayerMask(LayerMaskData layerMask)
```


Fügt die Maske zur aktuellen Ebene hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layerMask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Die Ebenenmaske. |

### addResource_internalized(LayerResource resource) {#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void addResource_internalized(LayerResource resource)
```


Fügt die Ressource hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | Die Ressource. |

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

### applyLayerMask() {#applyLayerMask--}
```
public final void applyLayerMask()
```


Wendet die Ebenenmaske auf die Ebene an und löscht anschließend die Maske.

### applyLayerState_internalized(LayerState layerState) {#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-}
```
public final void applyLayerState_internalized(LayerState layerState)
```


Wendet die Ebenenstil‑Einstellung aus dem Eingabe-[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) auf die aktuelle [Layer](../../com.aspose.psd.fileformats.psd.layers/layer)-Instanz an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layerState | [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) | Der Layer-Zustand mit neuem Stil. |

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
### createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static Layer createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)
```


Erstellt die neue Instanz der Klasse [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader | Der Header. |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die Palette. |
| linkedLayersRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry | Die LinkedLayersRegistry. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Returns the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class.
### createLayerState_internalized() {#createLayerState-internalized--}
```
public final LayerState createLayerState_internalized()
```


Erstellt die neue Instanz von [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) basierend auf den aktuellen Werten von [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Returns:**
[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) - The new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values.
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
### create_internalized(PsdHeader header, LayerResource[] resources) {#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public static CurvesLayer create_internalized(PsdHeader header, LayerResource[] resources)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |
| resources | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

**Returns:**
[CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer)
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Layer create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
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

### drawImage(Point location, RasterImage image) {#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-}
```
public final void drawImage(Point location, RasterImage image)
```


Zeichnet das Bild auf die Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | Die Position. |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Das Bild. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene Objekt diesem Exemplar gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  true  wenn das angegebene Objekt dieser Instanz gleich ist; andernfalls  false .
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

### findAssignableResource_internalized(System.Type type) {#findAssignableResource-internalized-com.aspose.ms.System.Type-}
```
public final LayerResource findAssignableResource_internalized(System.Type type)
```


Findet die zuweisbare Ressource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | com.aspose.ms.System.Type | Der Typ. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - 
### findPattResource_internalized() {#findPattResource-internalized--}
```
public final PattResource findPattResource_internalized()
```


Findet die PattResource.

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - The found resource or null
### findResource_internalized(int typeToolKey) {#findResource-internalized-int-}
```
public final LayerResource findResource_internalized(int typeToolKey)
```


Findet die Ressource anhand des eindeutigen Schlüssels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeToolKey | int | Der Typ-Tool-Schlüssel. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - Found resource or null
### getAbsoluteBounds_internalized() {#getAbsoluteBounds-internalized--}
```
public final Rectangle getAbsoluteBounds_internalized()
```


Liest oder setzt die absoluten Grenzen.

Wert: Die absoluten Grenzen.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getAdjustmentLayerType_internalized() {#getAdjustmentLayerType-internalized--}
```
public byte getAdjustmentLayerType_internalized()
```


Liest den Typ der Anpassungsebene.

Wert: Der Typ der Anpassungsebene.

**Returns:**
byte
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
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Liest die Bit‑Pro‑Pixel‑Anzahl des Bildes.

Wert: Die Bild-Bits‑pro‑Pixel‑Anzahl.

**Returns:**
int
### getBlendClippedElements() {#getBlendClippedElements--}
```
public final boolean getBlendClippedElements()
```


Liest oder setzt das Blending des beschnittenen Elements.

Wert: Die Mischung des beschnittenen Elements.

**Returns:**
boolean
### getBlendModeKey() {#getBlendModeKey--}
```
public long getBlendModeKey()
```


Liest oder setzt den Schlüssel des Mischmodus.

Wert: Der Mischmodus‑Schlüssel.

**Returns:**
long
### getBlendModeSignature() {#getBlendModeSignature--}
```
public final int getBlendModeSignature()
```


Liest die Signatur des Mischmodus.

Wert: Die Mischmodus‑Signatur.

**Returns:**
int
### getBlendingOptions() {#getBlendingOptions--}
```
public final BlendingOptions getBlendingOptions()
```


Liest die Blending‑Optionen.

Wert: Die Mischoptionen.

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
### getBottom() {#getBottom--}
```
public int getBottom()
```


Liest oder setzt die Position der unteren Ebene.

Wert: Die Position der unteren Ebene.

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
### getBytesPerRowForFullMask_internalized(int bitDepth) {#getBytesPerRowForFullMask-internalized-int-}
```
public final int getBytesPerRowForFullMask_internalized(int bitDepth)
```


Liest die Bytes pro Zeile für den Vollmaskenmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| BitTiefe | int | Die Bit-Tiefe. |

**Returns:**
int - Bytes, die zum Speichern einer Zeile benötigt werden
### getBytesPerRowForMask_internalized(int bitDepth) {#getBytesPerRowForMask-internalized-int-}
```
public final int getBytesPerRowForMask_internalized(int bitDepth)
```


Liest die Bytes pro Zeile.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| BitTiefe | int | Die Bit-Tiefe. |

**Returns:**
int - Bytes, die zum Speichern einer Zeile benötigt werden
### getBytesPerRow_internalized(int bitDepth) {#getBytesPerRow-internalized-int-}
```
public final int getBytesPerRow_internalized(int bitDepth)
```


Liest die Bytes pro Zeile.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| BitTiefe | int | Die Bit-Tiefe. |

**Returns:**
int - Bytes, die zum Speichern einer Zeile benötigt werden
### getChannelInformation() {#getChannelInformation--}
```
public final ChannelInformation[] getChannelInformation()
```


Liest oder setzt die Kanalinformationen.

Wert: Die Kanalinformationen.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Liest die Kanalanzahl der Ebene.

Wert: Die Anzahl der Kanäle der Ebene.

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


Liest oder setzt das Ebenen-Clipping. 0 = Basis, 1 = Nicht-Basis.

Wert: Das Ebenen-Clipping.

**Returns:**
byte
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Liest den Image‑Container.

Wert: Der  Image  Container.

Wenn diese Eigenschaft nicht null ist, bedeutet dies, dass das Bild innerhalb eines anderen Bildes enthalten ist.

**Returns:**
[Image](../../com.aspose.psd/image)
### getCurvesManager() {#getCurvesManager--}
```
public final CurvesManager getCurvesManager()
```


Ruft den Kurven-Manager ab.

**Returns:**
[CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) - [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) or [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) that depends on IsDiscreteManagerUsed and IsContinuousManagerUsed property
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
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Liest den Anzeigenamen der Ebene.

Wert: Der Anzeigename der Ebene.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde.

**Returns:**
boolean -  true  wenn freigegeben; andernfalls,  false .
### getExtraLength() {#getExtraLength--}
```
public final int getExtraLength()
```


Ermittelt die Länge der zusätzlichen Ebeneninformationen in Bytes.

Wert: Die zusätzliche Ebenenlänge.

**Returns:**
int
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
### getFillOpacity() {#getFillOpacity--}
```
public final int getFillOpacity()
```


Ermittelt oder legt die Füll-Opazität fest.

**Returns:**
int
### getFiller() {#getFiller--}
```
public final byte getFiller()
```


Ermittelt oder legt den Ebenenfüller fest.

Wert: Der Ebenen‑Füller.

**Returns:**
byte
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
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Liest oder setzt die Ebenen‑Flags. Bit 0 = Transparenz geschützt; Bit 1 = sichtbar; Bit 2 = veraltet; Bit 3 = 1 für Photoshop 5.0 und höher, gibt an, ob Bit 4 nützliche Informationen enthält; Bit 4 = Pixeldaten für das Erscheinungsbild des Dokuments irrelevant.

Wert: Die Ebenen‑Flags.

**Returns:**
byte
### getFoldersHierarchy_internalized() {#getFoldersHierarchy-internalized--}
```
public final System.Collections.Generic.List<Layer> getFoldersHierarchy_internalized()
```


Ermittelt die Liste der Ordnerhierarchie von [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) des aktuellen Layers.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.Layer> - Gibt die Liste der Ordnerhierarchie von [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) der aktuellen Ebene zurück.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Ermittelt die Palette aus formatabhängigen Bereichen

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGUID_internalized() {#getGUID-internalized--}
```
public final String getGUID_internalized()
```


Ermittelt die eindeutige Kennung dieser Layer-Instanz.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Ermittelt oder legt den Header fest.

Wert: Der Header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
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


Ermittelt oder legt die horizontale Auflösung in Pixel pro Zoll dieses  RasterImage  fest.

**Returns:**
double - Die horizontale Auflösung.

Hinweis: Standardmäßig ist dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können die SetResolution‑Methode in Betracht ziehen, um beide Auflösungswerte in einem Aufruf zu aktualisieren.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Ermittelt die Opazität dieses Bildes.

**Returns:**
float - Der Deckkraftwert zwischen 0,0 (vollständig transparent) und 1,0 (vollständig undurchsichtig).
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
### getLayerBlendingRangesData() {#getLayerBlendingRangesData--}
```
public final LayerBlendingRangesData getLayerBlendingRangesData()
```


Ermittelt oder legt die Daten der Ebenen‑Mischbereiche fest.

Wert: Die Daten der Ebenen‑Mischbereichswerte.

**Returns:**
[LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata)
### getLayerCreationDateTime() {#getLayerCreationDateTime--}
```
public final Date getLayerCreationDateTime()
```


Ermittelt oder legt das Erstellungsdatum und die -zeit der Ebene fest.

Wert: Das Erstellungs‑DateTime der Ebene. Wenn keine Daten zum Erstellungs‑DateTime vorhanden sind, wird die Unix‑Zeit des ersten Epoch zurückgegeben.

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


Liest oder setzt die Ebenensperre. Hinweis: Wenn das Flag LayerFlags.TransparencyProtected gesetzt ist, wird es durch das Ebenen‑Sperre‑Flag überschrieben. Um das Flag LayerFlags.TransparencyProtected zurückzugeben, muss die Ebenenoption layer.Flags |= LayerFlags.TransparencyProtected angewendet werden.

Wert: Die Ebenensperre.

**Returns:**
int
### getLayerMaskData() {#getLayerMaskData--}
```
public final LayerMaskData getLayerMaskData()
```


Ermittelt oder legt die Ebenenmaskendaten fest.

Wert: Die Ebenenmaskendaten.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
### getLayerOptions() {#getLayerOptions--}
```
public final PsdOptions getLayerOptions()
```


Ermittelt die Ebenenoptionen.

Wert: Die Ebenenoptionen.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)
### getLayerPalette_internalized() {#getLayerPalette-internalized--}
```
public final IColorPalette getLayerPalette_internalized()
```


Ermittelt oder legt die Ebenenpalette fest.

Wert: Die Ebenenpalette.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getLayerType_internalized() {#getLayerType-internalized--}
```
public byte getLayerType_internalized()
```


Liefert den Typ der Ebene.

Wert: Der Typ der Ebene.

**Returns:**
byte
### getLeft() {#getLeft--}
```
public int getLeft()
```


Liefert oder setzt die linke Ebenenposition.

Wert: Die linke Position der Ebene.

**Returns:**
int
### getLength() {#getLength--}
```
public final long getLength()
```


Liefert die gesamte Ebenenlänge in Bytes.

**Returns:**
long
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
### getName() {#getName--}
```
public final String getName()
```


Liefert oder setzt den Ebenennamen.

Wert: Der Ebenenname.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Liest oder setzt die Ebenen‑Deckkraft. 0 = transparent, 255 = undurchsichtig.

Wert: Die Ebenen‑Deckkraft.

**Returns:**
byte
### getOpacityTotal_internalized() {#getOpacityTotal-internalized--}
```
public final byte getOpacityTotal_internalized()
```


Liest die Gesamtdurchsichtigkeit. Die Gesamtdurchsichtigkeit ist das Produkt aus Layer Opacity und Layer Fill Opacity. Sie wird für das Ebenen‑Mischen verwendet.

Wert: Die Gesamtdurchsichtigkeit.

**Returns:**
byte
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
### getProcessor_internalized() {#getProcessor-internalized--}
```
public final IPartialArgb32PixelLoader getProcessor_internalized()
```


Liest den Prozessor.

Wert: Der Prozessor.

**Returns:**
[IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
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

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
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
### getResources() {#getResources--}
```
public final LayerResource[] getResources()
```


Liefert oder setzt die Ebenen‑Ressourcen.

Value: Die Ebenenressourcen.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getRight() {#getRight--}
```
public int getRight()
```


Liefert oder setzt die rechte Ebenenposition.

Value: Die rechte Ebenenposition.

**Returns:**
int
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Liest oder setzt den Rotationsmodus.

**Returns:**
int - Der Rotationsmodus.
### getSheetColorHighlight() {#getSheetColorHighlight--}
```
public final short getSheetColorHighlight()
```


Liest oder setzt die dekorative Blattfarb-Hervorhebung in der Ebenenliste

Value: Die Hervorhebung der Blattfarbe.

**Returns:**
short
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
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Ruft den Dateipfad des Quellbildes ab, falls es existiert. Gibt einen leeren String zurück, wenn der Quellpfad nicht gefunden werden kann.

**Returns:**
java.lang.String - Der Dateipfad des Quellbildes.
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Liest die Synchronisationswurzel.

Value: Die Synchronisationswurzel.

**Returns:**
java.lang.Object
### getTop() {#getTop--}
```
public int getTop()
```


Liest oder setzt die Position der obersten Ebene.

Value: Die obere Ebenenposition.

**Returns:**
int
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
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Liest oder setzt die vertikale Auflösung in Pixel pro Zoll dieses  RasterImage .

**Returns:**
double - Die vertikale Auflösung.

Hinweis: Standardmäßig ist dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können die SetResolution‑Methode in Betracht ziehen, um beide Auflösungswerte in einem Aufruf zu aktualisieren.
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

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation eines Bildes in seine Graustufen-Darstellung

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Liest einen Wert, der angibt, ob diese Instanz Alpha enthält.

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

**Returns:**
boolean -  true  wenn diese Instanz das Bild geändert hat; andernfalls  false .
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Liest einen Wert, der angibt, ob das Bild eine transparente Farbe hat.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int - Ein Hashcode für diese Instanz, geeignet für die Verwendung in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
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

### insertResource_internalized(int index, LayerResource resource) {#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void insertResource_internalized(int index, LayerResource resource)
```


Fügt eine Ressource in die Resources‑Sammlung ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Index der Ressource, die eingefügt werden soll. |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | Die Ressource, die eingefügt werden soll. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Liest einen Wert, der angibt, ob Bilddaten derzeit im Cache sind.

**Returns:**
boolean -  true  wenn Bilddaten zwischengespeichert sind; andernfalls  false .
### isContinuousManagerUsed() {#isContinuousManagerUsed--}
```
public final boolean isContinuousManagerUsed()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz als kontinuierlicher Manager verwendet wird.

Wert:  true  wenn diese Instanz als kontinuierlicher Manager verwendet wird; andernfalls  false .

**Returns:**
boolean
### isDiscreteManagerUsed() {#isDiscreteManagerUsed--}
```
public final boolean isDiscreteManagerUsed()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz als diskreter Manager verwendet wird.

Wert:  true  wenn diese Instanz als diskreter Manager verwendet wird; andernfalls  false .

**Returns:**
boolean
### isLayerValid_internalized() {#isLayerValid-internalized--}
```
public boolean isLayerValid_internalized()
```


Ermittelt, ob die Ebene für das Speichern in einer Datei gültig ist.

**Returns:**
boolean -
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
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Liest oder setzt einen Wert, der angibt, ob die Ebene sichtbar ist

Wert:  true  wenn diese Instanz sichtbar ist; andernfalls  false .

**Returns:**
boolean
### isVisibleInGroup() {#isVisibleInGroup--}
```
public boolean isVisibleInGroup()
```


Liest einen Wert, der angibt, ob diese Instanz in einer Gruppe sichtbar ist (Wenn die Ebene nicht in einer Gruppe ist, bedeutet das die Root-Gruppe).

Wert:  true  wenn diese Instanz in der Gruppe sichtbar ist; andernfalls  false .

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
### mergeLayerTo(Layer layerToMergeInto) {#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public void mergeLayerTo(Layer layerToMergeInto)
```


Führt die Ebene mit der angegebenen Ebene zusammen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layerToMergeInto | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Die Ebene, in die zusammengeführt wird. |

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


Aufrufen, wenn der Container dieses  Image  gesetzt wurde.

### processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#processAdjustmentLayer-internalized-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public Tuple<int[],Rectangle> processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Verarbeitet die Anpassungsebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Pixelrechteck. |
| Pixel | int[] | Die Pixel. |
| start | [Point](../../com.aspose.psd/point) | Der Anfang. |
| end | [Point](../../com.aspose.psd/point) | Das Ende. |

**Returns:**
com.aspose.internal.fileformats.psd.common.Tuple<int[],com.aspose.psd.Rectangle>
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
### removeResource_internalized(LayerResource resource) {#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void removeResource_internalized(LayerResource resource)
```


Entfernt die Ressource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | Die Ressource. |

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

### resizeChannelsData_internalized(Rectangle rect) {#resizeChannelsData-internalized-com.aspose.psd.Rectangle-}
```
public void resizeChannelsData_internalized(Rectangle rect)
```


Führt die Daten zusammen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck. |

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

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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

### save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dstStream | java.io.OutputStream | Der Stream, in dem die Bilddaten gespeichert werden. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Speicheroptionen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Rechteck mit den Zielbildgrenzen. Setzen Sie das leere Rechteck, um die Quellgrenzen zu verwenden. |

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

### save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth) {#save-internalized-com.aspose.psd.StreamContainer-int-int-}
```
public final void save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)
```


Speichert Daten in den angegebenen Stream‑Container.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |
| psdVersion | int | Die PSD‑Version. |
| BitTiefe | int | Die Bit-Tiefe. |

### setAbsoluteBounds_internalized(Rectangle value) {#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setAbsoluteBounds_internalized(Rectangle value)
```


Liest oder setzt die absoluten Grenzen.

Wert: Die absoluten Grenzen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

### setBlendClippedElements(boolean value) {#setBlendClippedElements-boolean-}
```
public final void setBlendClippedElements(boolean value)
```


Liest oder setzt das Blending des beschnittenen Elements.

Wert: Die Mischung des beschnittenen Elements.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setBlendModeKey(long value) {#setBlendModeKey-long-}
```
public void setBlendModeKey(long value)
```


Liest oder setzt den Schlüssel des Mischmodus.

Wert: Der Mischmodus‑Schlüssel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Liest oder setzt die Position der unteren Ebene.

Wert: Die Position der unteren Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

### setChannelInformation(ChannelInformation[] value) {#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public final void setChannelInformation(ChannelInformation[] value)
```


Liest oder setzt die Kanalinformationen.

Wert: Die Kanalinformationen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) |  |

### setClipping(byte value) {#setClipping-byte-}
```
public final void setClipping(byte value)
```


Liest oder setzt das Ebenen-Clipping. 0 = Basis, 1 = Nicht-Basis.

Wert: Das Ebenen-Clipping.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Setzt den Image‑Container.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Der Image‑Container. |

### setContinuousManagerUsed(boolean value) {#setContinuousManagerUsed-boolean-}
```
public final void setContinuousManagerUsed(boolean value)
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz als kontinuierlicher Manager verwendet wird.

Wert:  true  wenn diese Instanz als kontinuierlicher Manager verwendet wird; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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

### setDiscreteManagerUsed(boolean value) {#setDiscreteManagerUsed-boolean-}
```
public final void setDiscreteManagerUsed(boolean value)
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz als diskreter Manager verwendet wird.

Wert:  true  wenn diese Instanz als diskreter Manager verwendet wird; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Liest oder setzt den Anzeigenamen der Ebene.

Wert: Der Anzeigename der Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFillOpacity(int value) {#setFillOpacity-int-}
```
public final void setFillOpacity(int value)
```


Liest die Füll‑Deckkraft.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setFiller(byte value) {#setFiller-byte-}
```
public final void setFiller(byte value)
```


Ermittelt oder legt den Ebenenfüller fest.

Wert: Der Ebenen‑Füller.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Liest oder setzt die Ebenen‑Flags. Bit 0 = Transparenz geschützt; Bit 1 = sichtbar; Bit 2 = veraltet; Bit 3 = 1 für Photoshop 5.0 und höher, gibt an, ob Bit 4 nützliche Informationen enthält; Bit 4 = Pixeldaten für das Erscheinungsbild des Dokuments irrelevant.

Wert: Die Ebenen‑Flags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

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
### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Ermittelt oder legt den Header fest.

Wert: Der Header.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Ermittelt oder legt die horizontale Auflösung in Pixel pro Zoll dieses  RasterImage  fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die horizontale Auflösung. |

Hinweis: Standardmäßig ist dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können erwägen, die Methode SetResolution zu verwenden, um beide Auflösungswerte in einem Aufruf zu aktualisieren. |

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

### setLayerBlendingRangesData(LayerBlendingRangesData value) {#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-}
```
public final void setLayerBlendingRangesData(LayerBlendingRangesData value)
```


Ermittelt oder legt die Daten der Ebenen‑Mischbereiche fest.

Wert: Die Daten der Ebenen‑Mischbereichswerte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata) |  |

### setLayerCreationDateTime(Date value) {#setLayerCreationDateTime-java.util.Date-}
```
public final void setLayerCreationDateTime(Date value)
```


Ermittelt oder legt das Erstellungsdatum und die -zeit der Ebene fest.

Wert: Das Erstellungs‑DateTime der Ebene. Wenn keine Daten zum Erstellungs‑DateTime vorhanden sind, wird die Unix‑Zeit des ersten Epoch zurückgegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### setLayerCreationDateTime_internalized(System.DateTime value) {#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-}
```
public final void setLayerCreationDateTime_internalized(System.DateTime value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.ms.System.DateTime |  |

### setLayerLock(int value) {#setLayerLock-int-}
```
public final void setLayerLock(int value)
```


Liest oder setzt die Ebenensperre (Hinweis: Wenn das Flag LayerFlags.TransparencyProtected gesetzt ist, wird es durch das Ebenensperre-Flag überschrieben. Um das Flag LayerFlags.TransparencyProtected zurückzugeben, muss es für die Ebenenoption angewendet werden: layer.Flags |= LayerFlags.TransparencyProtected

Wert: Die Ebenensperre.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setLayerMaskData(LayerMaskData value) {#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void setLayerMaskData(LayerMaskData value)
```


Ermittelt oder legt die Ebenenmaskendaten fest.

Wert: Die Ebenenmaskendaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) |  |

### setLayerPalette_internalized(IColorPalette value) {#setLayerPalette-internalized-com.aspose.psd.IColorPalette-}
```
public final void setLayerPalette_internalized(IColorPalette value)
```


Ermittelt oder legt die Ebenenpalette fest.

Wert: Die Ebenenpalette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Liefert oder setzt die linke Ebenenposition.

Wert: Die linke Position der Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

### setName(String name) {#setName-java.lang.String-}
```
public final void setName(String name)
```


Legt den Ebenennamen fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Der Ebenenname. |

### setName_internalized(String value) {#setName-internalized-java.lang.String-}
```
public final void setName_internalized(String value)
```


Liefert oder setzt den Ebenennamen.

Wert: Der Ebenenname.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Liest oder setzt die Ebenen‑Deckkraft. 0 = transparent, 255 = undurchsichtig.

Wert: Die Ebenen‑Deckkraft.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

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


Legt die Auflösung für dieses RasterImage fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dpiX | double | Die horizontale Auflösung, in Punkten pro Zoll, des RasterImage. |
| dpiY | double | Die vertikale Auflösung, in Punkten pro Zoll, des RasterImage. |

### setResources(LayerResource[] value) {#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setResources(LayerResource[] value)
```


Liefert oder setzt die Ebenen‑Ressourcen.

Value: Die Ebenenressourcen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Liefert oder setzt die rechte Ebenenposition.

Value: Die rechte Ebenenposition.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Liest oder setzt den Rotationsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Rotationsmodus. |

### setSheetColorHighlight(short value) {#setSheetColorHighlight-short-}
```
public final void setSheetColorHighlight(short value)
```


Liest oder setzt die dekorative Blattfarb-Hervorhebung in der Ebenenliste

Value: Die Hervorhebung der Blattfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Liest oder setzt die Position der obersten Ebene.

Value: Die obere Ebenenposition.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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


Alle Aspose-Produkte sollten diese Methode implementieren. Sie wird von einem GroupDocs-Produkt aufgerufen, um anzuzeigen, ob GroupDocs selbst lizenziert ist oder nicht, und um ein benutzerdefiniertes Wasserzeichen anzugeben. Wenn GroupDocs lizenziert ist, sollte diese Dokumentinstanz ebenfalls lizenziert sein, selbst wenn das Aspose-Produkt nicht lizenziert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ventureLicense | java.lang.Object | license |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Liest oder setzt die vertikale Auflösung in Pixel pro Zoll dieses  RasterImage .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die vertikale Auflösung. |

Hinweis: Standardmäßig ist dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können erwägen, die Methode SetResolution zu verwenden, um beide Auflösungswerte in einem Aufruf zu aktualisieren. |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die Ebene sichtbar ist

Wert:  true  wenn diese Instanz sichtbar ist; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Liest oder setzt die XMP-Metadaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Die XMP-Metadaten. |

### shallowCopy() {#shallowCopy--}
```
public final Layer shallowCopy()
```


Erstellt eine flache Kopie der aktuellen Layer. Bitte   für Erklärung.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - A shallow copy of the current Layer.
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
### updateBlendingOptions_internalized(PattResource pattResource) {#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateBlendingOptions_internalized(PattResource pattResource)
```


Aktualisiert die Blending-Optionen, nachdem sich Layer- oder globale Ressourcen geändert haben.

**Parameters:**
| Parameter | Typ | Beschreibung |
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

