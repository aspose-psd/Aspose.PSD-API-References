---
title: "Image"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Das Bild ist die Basisklasse für alle Bildtypen."
type: docs
weight: 54
url: /de/java/com.aspose.psd/image/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.psd.IObjectWithBounds](../../com.aspose.psd/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler
```

Das Bild ist die Basisklasse für alle Bildtypen.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | Tritt auf, wenn das Bild geladen wurde |
| [OnLoad_internalized](#OnLoad-internalized) | Tritt auf, wenn das Bild durch createFirstSupportedLoader geladen wurde |
| [OnSave_internalized](#OnSave-internalized) | Tritt auf, wenn das Bild geladen oder gespeichert wurde |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Tritt auf, wenn ein Guthaben verwendet wurde |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [cacheData()](#cacheData--) | Puffert die Daten und stellt sicher, dass keine zusätzlichen Daten aus dem zugrunde liegenden DataStreamSupporter.DataStreamContainer geladen werden. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Bestimmt, ob das Bild aus dem angegebenen Stream geladen werden kann. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Bestimmt, ob das Bild aus dem angegebenen Stream geladen werden kann und optional die angegebenen loadOptions verwendet. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann. |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Konvertiert zu aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Erstellt ein neues Bild, wobei die angegebenen Bilder als Seiten verwendet werden. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Erstellt ein neues Bild mit den angegebenen Bildern als Seiten. |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Gibt einen Wert zurück, der angibt, ob die automatische Palettenanpassung aktiviert ist. |
| [getBackgroundColor()](#getBackgroundColor--) | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Liest die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [getBounds()](#getBounds--) | Liest die Bildgrenzen. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liest den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Liest den Image‑Container. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Liest den Datenstrom des Objekts. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Liest die tiefgreifende Palettenanpassung. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Liest die Standardoptionen. |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getFileFormat()](#getFileFormat--) | Ermittelt einen Wert des Dateiformats |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Ermittelt das Dateiformat. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Ermittelt das Dateiformat. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Ermittelt das Dateiformat. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [getHeight()](#getHeight--) | Ermittelt die Bildhöhe. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Ermittelt den Unterbrechungsmonitor. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Liefert den Speicher‑Manager. |
| [getOriginalOptions()](#getOriginalOptions--) | Liefert die Optionen basierend auf den ursprünglichen Dateieinstellungen. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Liefert das zu malende Bild. |
| [getPalette()](#getPalette--) | Liefert die Farbpalette. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Erstellt den privaten Schriftarten‑Cache. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Liefert die Informationen zum Fortschritts‑Ereignis‑Handler. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Liefert die Informationen zum Fortschritts‑Ereignis‑Handler. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Liefert eine proportionale Höhe. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Liefert eine proportionale Breite. |
| [getSize()](#getSize--) | Liest die Bildgröße. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Liest den Dateipfad des Quellbildes, falls es existiert. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Liest einen Wert, der angibt, ob das Objekt eine Speicheroptimierungsstrategie verwendet |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Liest die Venture-Lizenz. |
| [getWidth()](#getWidth--) | Liest die Bildbreite. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Liest einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Liest oder setzt einen Wert, der angibt, ob diese Bildinstanz nach dem Laden geändert wurde. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Liest oder setzt den maximalen Fortschrittswert |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Zeigt den Fortschritt an. |
| [isCached()](#isCached--) | Gibt einen Wert zurück, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| [isUsePalette()](#isUsePalette--) | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(String filePath)](#load-java.lang.String-) | Lädt ein neues Bild aus der angegebenen Datei. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Lädt ein neues Bild aus der angegebenen Datei. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Aufrufen, wenn der Container dieses [Image](../../com.aspose.psd/image) festgelegt wurde. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Skaliert das Bild. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Skaliert das Bild. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Skaliert das Bild. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Ändert die Höhe proportional. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Ändert die Höhe proportional. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ändert die Höhe proportional. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Ändert die Breite proportional. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Ändert die Breite proportional. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ändert die Breite proportional. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Setzt den Image‑Container. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Setzt den Datenstream des Objekts. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Setzt einen Wert, der angibt, ob [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Bildinstanz nach dem Laden geändert wurde. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Setzt den Unterbrechungsmonitor. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Setzt den Speicher‑Manager. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Legt die Farbpalette fest. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Legt die Bildpalette fest. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Alle Aspose-Produkte sollten diese Methode implementieren. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### cacheData() {#cacheData--}
```
public abstract void cacheData()
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

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public abstract ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


Konvertiert zu aps.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Bildoptionen. |
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
### dispose() {#dispose--}
```
public final void dispose()
```


Gibt die aktuelle Instanz frei.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
public abstract int getBitsPerPixel()
```


Liest die Bit‑Pro‑Pixel‑Anzahl des Bildes.

**Returns:**
int - Die Bit‑Anzahl pro Pixel des Bildes.
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


Liest den Image‑Container.

Wert: Der  Image  Container.

Wenn diese Eigenschaft nicht null ist, bedeutet dies, dass das Bild innerhalb eines anderen Bildes enthalten ist.

**Returns:**
[Image](../../com.aspose.psd/image)
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
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Ermittelt die Bildhöhe.

**Returns:**
int - Die Bildhöhe.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Ermittelt den Unterbrechungsmonitor.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Liefert den Speicher‑Manager.

Wert: Der Speicher‑Manager.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - der Speicher‑Manager.
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
### getSize() {#getSize--}
```
public Size getSize()
```


Liest die Bildgröße.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Ruft den Dateipfad des Quellbildes ab, falls es existiert. Gibt einen leeren String zurück, wenn der Quellpfad nicht gefunden werden kann.

**Returns:**
java.lang.String - Der Dateipfad des Quellbildes.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Liest einen Wert, der angibt, ob das Objekt eine Speicheroptimierungsstrategie verwendet

Value:  true  wenn das Objekt eine Speicheroptimierungsstrategie verwendet; andernfalls,  false .

**Returns:**
boolean - ein Wert, der angibt, ob das Objekt eine Speicheroptimierungsstrategie verwendet
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Liest die Venture-Lizenz.

**Returns:**
java.lang.Object - Die Venture-Lizenz als Objekt.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Liest die Bildbreite.

**Returns:**
int - Die Bildbreite.
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

### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Gibt einen Wert zurück, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist.

**Returns:**
boolean – ein Wert, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist.
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Liest einen Wert, der angibt, ob die Bildpalette verwendet wird.

Wert:  true  wenn die Palette im Bild verwendet wird; andernfalls  false .

**Returns:**
boolean - ein Wert, der angibt, ob die Bildpalette verwendet wird.
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
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
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
public abstract void resize(int newWidth, int newHeight, int resizeType)
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

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Typ der Dreh‑Umkehr. |

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




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Setzt den Image‑Container.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Der Image‑Container. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Setzt den Datenstream des Objekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Datenstrom des Objekts. |

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

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Setzt den Unterbrechungsmonitor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | der Interrupt-Monitor. |

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
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


Legt die Bildpalette fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die zu setzende Palette. |
| updateColors | boolean | wenn auf  true  gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben Farbindizes unverändert. Hinweis: Unveränderte Indizes können das Bild beim Laden zum Absturz bringen, wenn einige Indizes keine entsprechenden Paletteneinträge haben. |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Alle Aspose-Produkte sollten diese Methode implementieren. Sie wird von einem GroupDocs-Produkt aufgerufen, um anzuzeigen, ob GroupDocs selbst lizenziert ist oder nicht, und um ein benutzerdefiniertes Wasserzeichen anzugeben. Wenn GroupDocs lizenziert ist, sollte diese Dokumentinstanz ebenfalls lizenziert sein, selbst wenn das Aspose-Produkt nicht lizenziert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ventureLicense | java.lang.Object |  |

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

