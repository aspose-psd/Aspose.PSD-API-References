---
title: "PsdOptions"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die PSD‑Dateiformat‑Erstellungsoptionen."
type: docs
weight: 21
url: /de/java/com.aspose.psd.imageoptions/psdoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

Die PSD‑Dateiformat‑Erstellungsoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Initialisiert eine neue Instanz der [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)-Klasse. |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-) | Initialisiert eine neue Instanz der [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)-Klasse. |
| [PsdOptions(PsdImage image)](#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-) | Initialisiert eine neue Instanz der [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [deepClone()](#deepClone--) | Klont diese Instanz. |
| [deepClone_internalized()](#deepClone-internalized--) | Klont diese Instanz. |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundContents()](#getBackgroundContents--) | Liest oder setzt die Hintergrundfarbe. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Liest oder setzt die Bitanzahl pro Farbkanal. |
| [getChannelsCount()](#getChannelsCount--) | Liest oder setzt die Anzahl der Farbkanäle. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Liest oder setzt den PSD‑Farbmodus. |
| [getCompressionMethod()](#getCompressionMethod--) | Liest oder setzt die PSD‑Komprimierungsmethode. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Liest oder setzt die Standard‑Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen‑Schriftart in der PSD‑Datei im System nicht vorhanden ist). |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getFullFrame()](#getFullFrame--) | Gibt einen Wert zurück, der angibt, ob [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Die Mehrseitenoptionen |
| [getPalette()](#getPalette--) | Ruft die Farbpalette ab oder legt sie fest. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest. |
| [getPsdVersion()](#getPsdVersion--) | Liest oder setzt die Dateiformat-Version. |
| [getRefreshImagePreviewData()](#getRefreshImagePreviewData--) | Liest oder setzt einen Wert, der angibt, ob [refresh image preview data] – Option zur Maximierung der Kompatibilität mit anderen PSD‑Bildbetrachtern verwendet wird. |
| [getRemoveGlobalTextEngineResource()](#getRemoveGlobalTextEngineResource--) | Liest oder setzt einen Wert, der angibt, ob – Die globale Text‑Engine‑Ressource entfernen – Wird für einige textschichtige PSD‑Dateien verwendet, ausschließlich in dem Fall, dass sie nach der Verarbeitung nicht in Adobe Photoshop geöffnet werden können (hauptsächlich bei fehlenden Schriftarten‑Textschichten). |
| [getResolutionSettings()](#getResolutionSettings--) | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [getResources()](#getResources--) | Liest oder setzt die PSD‑Ressourcen. |
| [getSource()](#getSource--) | Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest. |
| [getUpdateMetadata()](#getUpdateMetadata--) | Liest oder setzt einen Wert, der angibt, ob [update metadata]. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest. |
| [getVersion()](#getVersion--) | Liest oder setzt die PSD‑Dateiversion. |
| [getXmpData()](#getXmpData--) | Abrufen oder Festlegen des XMP-Datencontainers |
| [hashCode()](#hashCode--) |  |
| [isColorModeSet()](#isColorModeSet--) | Zeigt an, ob die ColorMode‑Eigenschaft zugewiesen wurde. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundContents(RawColor value)](#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Liest oder setzt die Hintergrundfarbe. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Liest oder setzt die Bitanzahl pro Farbkanal. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Liest oder setzt die Anzahl der Farbkanäle. |
| [setColorMode(short value)](#setColorMode-short-) | Liest oder setzt den PSD‑Farbmodus. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Liest oder setzt die PSD‑Komprimierungsmethode. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Liest oder setzt die Standard‑Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen‑Schriftart in der PSD‑Datei im System nicht vorhanden ist). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Legt einen Wert fest, der angibt, ob [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Die Mehrseitenoptionen |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ruft die Farbpalette ab oder legt sie fest. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Liest oder setzt die Dateiformat-Version. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Liest oder setzt einen Wert, der angibt, ob [refresh image preview data] – Option zur Maximierung der Kompatibilität mit anderen PSD‑Bildbetrachtern verwendet wird. |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Liest oder setzt einen Wert, der angibt, ob – Die globale Text‑Engine‑Ressource entfernen – Wird für einige textschichtige PSD‑Dateien verwendet, ausschließlich in dem Fall, dass sie nach der Verarbeitung nicht in Adobe Photoshop geöffnet werden können (hauptsächlich bei fehlenden Schriftarten‑Textschichten). |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [setResources(ResourceBlock[] value)](#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Liest oder setzt die PSD‑Ressourcen. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest. |
| [setUpdateMetadata(boolean value)](#setUpdateMetadata-boolean-) | Liest oder setzt einen Wert, der angibt, ob [update metadata]. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest. |
| [setVersion(int value)](#setVersion-int-) | Liest oder setzt die PSD‑Dateiversion. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Abrufen oder Festlegen des XMP-Datencontainers |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Initialisiert eine neue Instanz der [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)-Klasse.

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Initialisiert eine neue Instanz der [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Die Optionen. |

### PsdOptions(PsdImage image) {#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-}
```
public PsdOptions(PsdImage image)
```


Initialisiert eine neue Instanz der [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Das Bild. |

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Implementiert das Closable-Interface und kann seit JDK 1.7 in der try-with-resources-Anweisung verwendet werden. Diese Methode ruft einfach die dispose-Methode auf.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Klont diese Instanz.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Klont diese Instanz.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Gibt die aktuelle Instanz frei.

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
### getBackgroundContents() {#getBackgroundContents--}
```
public final RawColor getBackgroundContents()
```


Liest oder setzt die Hintergrundfarbe. Sie ist unter transparenten Objekten zu sehen.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße, in Megabyte. Ein nicht-positiver Wert bedeutet keine Speicherbegrenzung für interne Puffer.

**Returns:**
int
### getChannelBitsCount() {#getChannelBitsCount--}
```
public final short getChannelBitsCount()
```


Liest oder setzt die Bitanzahl pro Farbkanal.

Wert: Die Bitanzahl pro Farbkanal.

**Returns:**
short
### getChannelsCount() {#getChannelsCount--}
```
public final short getChannelsCount()
```


Liest oder setzt die Anzahl der Farbkanäle.

Wert: Die Anzahl der Farbkanäle.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Liest oder setzt den PSD‑Farbmodus.

Wert: Der Farbmodus.

**Returns:**
short
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Liest oder setzt die PSD‑Komprimierungsmethode.

Wert: Die Komprimierungsmethode.

**Returns:**
short
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Ruft die Standardschriftart für den Ersatz ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die Schriftart der vorhandenen Ebene in der PSD-Datei im System nicht vorhanden ist). Um den korrekten Namen der Standardschriftart zu erhalten, kann folgender Code‑Snippet verwendet werden: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Wert: Die Standardschriftart für den Ersatz.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde.

**Returns:**
boolean -  true  wenn freigegeben; andernfalls,  false .
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Gibt einen Wert zurück, der angibt, ob [full frame].

Wert:  true  wenn [full frame]; andernfalls  false .

**Returns:**
boolescher Wert – ein Wert, der angibt, ob [full frame].
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird.

Wert:  true  wenn nach dem Erstellen-Ereignis ignoriert wird; andernfalls  false .

**Returns:**
boolean
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Die Mehrseitenoptionen

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Ruft die Farbpalette ab oder legt sie fest.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest.

Wert: Der Fortschritts‑Ereignis‑Handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Liest oder setzt die Dateiformat-Version. Sie kann PSD oder PSB sein.

Wert: Die Dateiformat-Version.

**Returns:**
byte
### getRefreshImagePreviewData() {#getRefreshImagePreviewData--}
```
public final boolean getRefreshImagePreviewData()
```


Liest oder setzt einen Wert, der angibt, ob [refresh image preview data] – Option, die verwendet wird, um die Kompatibilität mit anderen PSD-Bildbetrachtern zu maximieren. Bitte beachten Sie, dass das Zeichnen von Textebenen in das endgültige Layout für die Compact‑Framework‑Plattform nicht unterstützt wird.

Wert:  true  wenn [refresh image preview data]; andernfalls  false .

**Returns:**
boolean
### getRemoveGlobalTextEngineResource() {#getRemoveGlobalTextEngineResource--}
```
public final boolean getRemoveGlobalTextEngineResource()
```


Liest oder setzt einen Wert, der angibt, ob – Die globale Text‑Engine‑Ressource entfernen – Für einige textschichtige PSD‑Dateien verwendet, ausschließlich in dem Fall, wenn sie nach der Verarbeitung nicht in Adobe Photoshop geöffnet werden können (hauptsächlich bei fehlenden Schriftarten in Textebenen). Nach der Verwendung dieser Option muss der Benutzer im geöffneten Photoshop‑Dokument Folgendes ausführen: Menü „Text“ → „Fehlende Schriften verarbeiten“. Nach diesem Vorgang wird aller Text wieder angezeigt. Bitte beachten Sie, dass dieser Vorgang einige Änderungen im endgültigen Layout verursachen kann.

Wert:  true  wenn [remove global text engine resource]; andernfalls  false .

**Returns:**
boolean
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Ruft die Auflösungseinstellungen ab oder legt sie fest.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResources() {#getResources--}
```
public final ResourceBlock[] getResources()
```


Liest oder setzt die PSD‑Ressourcen. Wenn der Wert: NULL – dann die ursprünglichen ImageResources speichern (Standardverhalten) Nicht leer – dann die über diese Eigenschaft übergebenen Ressourcen + [required resources] speichern. Leer – dann nur [required resources] speichern. Erforderliche Ressourcen: ResolutionInfoResource, XmpResource

Wert: Die PSD‑Ressourcen.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getSource() {#getSource--}
```
public final Source getSource()
```


Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest.

Wert: Die Quelle, in der das Bild erstellt wird.

**Returns:**
[Source](../../com.aspose.psd/source)
### getUpdateMetadata() {#getUpdateMetadata--}
```
public final boolean getUpdateMetadata()
```


Liest oder setzt einen Wert, der angibt, ob [update metadata]. Wenn der Wert true ist, werden die Metadaten beim Speichern eines Bildes aktualisiert.

Wert:  true  wenn [update metadata]; andernfalls  false .

**Returns:**
boolean
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Liest oder setzt die PSD‑Dateiversion.

Wert: Die PSD‑Dateiversion.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Abrufen oder Festlegen des XMP-Datencontainers

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorModeSet() {#isColorModeSet--}
```
public final boolean isColorModeSet()
```


Zeigt an, ob die ColorMode‑Eigenschaft zugewiesen wurde.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundContents(RawColor value) {#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents(RawColor value)
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


Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße, in Megabyte. Ein nicht-positiver Wert bedeutet keine Speicherbegrenzung für interne Puffer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public final void setChannelBitsCount(short value)
```


Liest oder setzt die Bitanzahl pro Farbkanal.

Wert: Die Bitanzahl pro Farbkanal.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setChannelsCount(short value) {#setChannelsCount-short-}
```
public final void setChannelsCount(short value)
```


Liest oder setzt die Anzahl der Farbkanäle.

Wert: Die Anzahl der Farbkanäle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Liest oder setzt den PSD‑Farbmodus.

Wert: Der Farbmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Liest oder setzt die PSD‑Komprimierungsmethode.

Wert: Die Komprimierungsmethode.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Ruft die Standardschriftart für den Ersatz ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die Schriftart der vorhandenen Ebene in der PSD-Datei im System nicht vorhanden ist). Um den korrekten Namen der Standardschriftart zu erhalten, kann folgender Code‑Snippet verwendet werden: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Wert: Die Standardschriftart für den Ersatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Legt einen Wert fest, der angibt, ob [full frame].

Wert:  true  wenn [full frame]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob [full frame]. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird.

Wert:  true  wenn nach dem Erstellen-Ereignis ignoriert wird; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Die Mehrseitenoptionen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Ruft die Farbpalette ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest.

Wert: Der Fortschritts‑Ereignis‑Handler.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Liest oder setzt die Dateiformat-Version. Sie kann PSD oder PSB sein.

Wert: Die Dateiformat-Version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public final void setRefreshImagePreviewData(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [refresh image preview data] – Option, die verwendet wird, um die Kompatibilität mit anderen PSD-Bildbetrachtern zu maximieren. Bitte beachten Sie, dass das Zeichnen von Textebenen in das endgültige Layout für die Compact‑Framework‑Plattform nicht unterstützt wird.

Wert:  true  wenn [refresh image preview data]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public final void setRemoveGlobalTextEngineResource(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob – Die globale Text‑Engine‑Ressource entfernen – Für einige textschichtige PSD‑Dateien verwendet, ausschließlich in dem Fall, wenn sie nach der Verarbeitung nicht in Adobe Photoshop geöffnet werden können (hauptsächlich bei fehlenden Schriftarten in Textebenen). Nach der Verwendung dieser Option muss der Benutzer im geöffneten Photoshop‑Dokument Folgendes ausführen: Menü „Text“ → „Fehlende Schriften verarbeiten“. Nach diesem Vorgang wird aller Text wieder angezeigt. Bitte beachten Sie, dass dieser Vorgang einige Änderungen im endgültigen Layout verursachen kann.

Wert:  true  wenn [remove global text engine resource]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Ruft die Auflösungseinstellungen ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResources(ResourceBlock[] value) {#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setResources(ResourceBlock[] value)
```


Liest oder setzt die PSD‑Ressourcen. Wenn der Wert: NULL – dann die ursprünglichen ImageResources speichern (Standardverhalten) Nicht leer – dann die über diese Eigenschaft übergebenen Ressourcen + [required resources] speichern. Leer – dann nur [required resources] speichern. Erforderliche Ressourcen: ResolutionInfoResource, XmpResource

Wert: Die PSD‑Ressourcen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest.

Wert: Die Quelle, in der das Bild erstellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setUpdateMetadata(boolean value) {#setUpdateMetadata-boolean-}
```
public final void setUpdateMetadata(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [update metadata]. Wenn der Wert true ist, werden die Metadaten beim Speichern eines Bildes aktualisiert.

Wert:  true  wenn [update metadata]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Liest oder setzt die PSD‑Dateiversion.

Wert: Die PSD‑Dateiversion.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Abrufen oder Festlegen des XMP-Datencontainers

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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

