---
title: "Jpeg2000Options"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die JPEG2000‑Dateiformat‑Optionen."
type: docs
weight: 14
url: /de/java/com.aspose.psd.imageoptions/jpeg2000options/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

Die JPEG2000‑Dateiformat‑Optionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | Initialisiert eine neue Instanz der Klasse  Jpeg2000Options . |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.psd.imageoptions.Jpeg2000Options-) | Initialisiert eine neue Instanz der Klasse  Jpeg2000Options . |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [deepClone()](#deepClone--) | Klont diese Instanz. |
| [deepClone_internalized()](#deepClone-internalized--) | Klont diese Instanz. |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [getClass()](#getClass--) |  |
| [getCodec()](#getCodec--) | Liest oder setzt den JPEG2000‑Codec |
| [getComments()](#getComments--) | Liest oder setzt die JPEG‑Kommentarmarker. |
| [getCompressionRatios()](#getCompressionRatios--) | Liest oder setzt das Array der Kompressionsraten. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Liest oder setzt die Standard‑Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen‑Schriftart in der PSD‑Datei im System nicht vorhanden ist). |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getFullFrame()](#getFullFrame--) | Gibt einen Wert zurück, der angibt, ob [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird. |
| [getIrreversible()](#getIrreversible--) | Liest einen Wert, der angibt, ob die irreversible DWT 9-7 (true) oder die verlustfreie DWT 5-3‑Kompression (Standard) verwendet wird. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Die Mehrseitenoptionen |
| [getPalette()](#getPalette--) | Ruft die Farbpalette ab oder legt sie fest. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest. |
| [getResolutionSettings()](#getResolutionSettings--) | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [getSource()](#getSource--) | Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest. |
| [getXmpData()](#getXmpData--) | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setCodec(int value)](#setCodec-int-) | Liest oder setzt den JPEG2000‑Codec |
| [setComments(String[] value)](#setComments-java.lang.String---) | Liest oder setzt die JPEG‑Kommentarmarker. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | Liest oder setzt das Array der Kompressionsraten. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Liest oder setzt die Standard‑Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen‑Schriftart in der PSD‑Datei im System nicht vorhanden ist). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Legt einen Wert fest, der angibt, ob [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird. |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | Setzt einen Wert, der angibt, ob die irreversible DWT 9-7 (true) oder die verlustfreie DWT 5-3‑Kompression (Standard) verwendet wird. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Die Mehrseitenoptionen |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ruft die Farbpalette ab oder legt sie fest. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


Initialisiert eine neue Instanz der Klasse  Jpeg2000Options .

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.psd.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


Initialisiert eine neue Instanz der Klasse  Jpeg2000Options .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.psd.imageoptions/jpeg2000options) | Die Jpeg2000-Dateiformatoptionen, von denen Einstellungen kopiert werden sollen. |

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
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße, in Megabyte. Ein nicht-positiver Wert bedeutet keine Speicherbegrenzung für interne Puffer.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodec() {#getCodec--}
```
public int getCodec()
```


Liest oder setzt den JPEG2000‑Codec

**Returns:**
int – Der JPEG2000‑Codec
### getComments() {#getComments--}
```
public String[] getComments()
```


Liest oder setzt die JPEG‑Kommentarmarker.

**Returns:**
java.lang.String[] – Die JPEG‑Kommentarmarker.
### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


Liest oder setzt das Array der Kompressionsraten. Unterschiedliche Kompressionsraten für aufeinanderfolgende Ebenen. Der für jede Qualitätsstufe angegebene Wert ist der gewünschte Kompressionsfaktor. Abnehmende Raten sind erforderlich.

**Returns:**
int[] - Die Kompressionsraten.
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
### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


Liest einen Wert, der angibt, ob die irreversible DWT 9-7 (true) oder die verlustfreie DWT 5-3‑Kompression (Standard) verwendet wird.

**Returns:**
boolean - ein Wert, der angibt, ob die irreversible DWT 9-7 (true) verwendet wird oder eine verlustfreie DWT 5-3-Kompression verwendet wird
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
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Ruft die Auflösungseinstellungen ab oder legt sie fest.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getSource() {#getSource--}
```
public final Source getSource()
```


Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest.

Wert: Die Quelle, in der das Bild erstellt wird.

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Ruft den XMP-Metadatencontainer ab oder legt ihn fest.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


Liest oder setzt den JPEG2000‑Codec

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der JPEG2000-Codec |

### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Liest oder setzt die JPEG‑Kommentarmarker.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String[] | Die JPEG-Kommentarmarker. |

### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


Liest oder setzt das Array der Kompressionsraten. Unterschiedliche Kompressionsraten für aufeinanderfolgende Ebenen. Der für jede Qualitätsstufe angegebene Wert ist der gewünschte Kompressionsfaktor. Abnehmende Raten sind erforderlich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | Die Kompressionsraten. |

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

### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


Setzt einen Wert, der angibt, ob die irreversible DWT 9-7 (true) oder die verlustfreie DWT 5-3‑Kompression (Standard) verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob die irreversible DWT 9-7 (true) verwendet wird oder eine verlustfreie DWT 5-3-Kompression verwendet wird |

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

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Ruft die Auflösungseinstellungen ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

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

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Ruft den XMP-Metadatencontainer ab oder legt ihn fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Der XMP-Datencontainer. |

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

