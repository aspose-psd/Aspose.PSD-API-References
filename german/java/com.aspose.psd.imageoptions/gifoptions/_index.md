---
title: "GifOptions"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die GIF‑Dateiformat‑Erstellungsoptionen."
type: docs
weight: 12
url: /de/java/com.aspose.psd.imageoptions/gifoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

Die GIF‑Dateiformat‑Erstellungsoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initialisiert eine neue Instanz der GifOptions-Klasse. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.psd.imageoptions.GifOptions-) | Initialisiert eine neue Instanz der GifOptions-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [deepClone()](#deepClone--) | Klont diese Instanz. |
| [deepClone_internalized()](#deepClone-internalized--) | Klont diese Instanz. |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Liest oder legt den GIF-Hintergrundfarbindizes fest. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [getClass()](#getClass--) |  |
| [getColorResolution()](#getColorResolution--) | Liest oder legt die GIF-Farbauflösung fest. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Liest oder setzt die Standard‑Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen‑Schriftart in der PSD‑Datei im System nicht vorhanden ist). |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Liest oder legt einen Wert fest, der angibt, ob die Palettenkorrektur angewendet wird. |
| [getFullFrame()](#getFullFrame--) | Gibt einen Wert zurück, der angibt, ob [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird. |
| [getInterlaced()](#getInterlaced--) | True, wenn das Bild interlaced sein soll. |
| [getMaxDiff()](#getMaxDiff--) | Liest oder legt die maximal zulässige Pixeldifferenz fest. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Die Mehrseitenoptionen |
| [getPalette()](#getPalette--) | Ruft die Farbpalette ab oder legt sie fest. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Liest oder legt das GIF-Pixel-Seitenverhältnis fest. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest. |
| [getResolutionSettings()](#getResolutionSettings--) | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [getSource()](#getSource--) | Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest. |
| [getXmpData()](#getXmpData--) | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |
| [hasTrailer()](#hasTrailer--) | Liest oder legt einen Wert fest, der angibt, ob das GIF einen Trailer hat. |
| [hashCode()](#hashCode--) |  |
| [isPaletteSorted()](#isPaletteSorted--) | Liest oder legt einen Wert fest, der angibt, ob Paletteneinträge sortiert sind. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Liest oder legt den GIF-Hintergrundfarbindizes fest. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Liest oder legt die GIF-Farbauflösung fest. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Liest oder setzt die Standard‑Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen‑Schriftart in der PSD‑Datei im System nicht vorhanden ist). |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Liest oder legt einen Wert fest, der angibt, ob die Palettenkorrektur angewendet wird. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Legt einen Wert fest, der angibt, ob [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | True, wenn das Bild interlaced sein soll. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Liest oder legt die maximal zulässige Pixeldifferenz fest. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Die Mehrseitenoptionen |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ruft die Farbpalette ab oder legt sie fest. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Liest oder legt einen Wert fest, der angibt, ob Paletteneinträge sortiert sind. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Liest oder legt das GIF-Pixel-Seitenverhältnis fest. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Liest oder legt einen Wert fest, der angibt, ob das GIF einen Trailer hat. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Initialisiert eine neue Instanz der GifOptions-Klasse.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.psd.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Initialisiert eine neue Instanz der GifOptions-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.psd.imageoptions/gifoptions) | Die GIF-Optionen. |

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
### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Liest oder legt den GIF-Hintergrundfarbindizes fest.

**Returns:**
byte – Der GIF-Hintergrundfarbindizes.
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
### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Liest oder legt die GIF-Farbauflösung fest.

**Returns:**
byte – Die Farbauflösung.

Color Resolution - Anzahl der Bits pro Primärfarbe, die dem Originalbild zur Verfügung stehen, minus 1. Dieser Wert stellt die Größe der gesamten Palette dar, aus der die Farben im Bild ausgewählt wurden, nicht die tatsächlich im Bild verwendete Farbanzahl. Zum Beispiel, wenn der Wert in diesem Feld 3 ist, dann hatte die Palette des Originalbildes 4 Bits pro Primärfarbe zur Erstellung des Bildes. Dieser Wert sollte gesetzt werden, um die Reichhaltigkeit der Originalpalette anzuzeigen, selbst wenn nicht jede Farbe der gesamten Palette auf der Quellmaschine verfügbar ist.
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
### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Liest oder legt einen Wert fest, der angibt, ob die Palettenkorrektur angewendet wird.

**Returns:**
boolean – true, wenn die Palettenkorrektur angewendet wird; andernfalls false.

Palette correction bedeutet, dass bei jedem Export eines Bildes nach GIF die Farben des Quellbildes analysiert werden, um die am besten passende Palette zu erstellen (falls die Bildpalette nicht existiert oder in den Optionen nicht angegeben ist). Der Analyseprozess benötigt etwas Zeit, jedoch wird das Ausgabebild die am besten passende Farbpalette besitzen und das Ergebnis ist visuell besser.
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
### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


True, wenn das Bild interlaced sein soll.

**Returns:**
boolean
### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Liest oder legt die maximal zulässige Pixeldifferenz fest. Wenn sie größer als Null ist, wird eine verlustbehaftete Kompression verwendet. Der empfohlene Wert für optimale verlustbehaftete Kompression beträgt 80. 30 ist eine sehr leichte Kompression, 200 ist stark. Sie funktioniert am besten, wenn nur wenig Verlust eingeführt wird, und aufgrund der Beschränkung des Kompressionsalgorithmus bringen sehr hohe Verluststufen nicht viel Gewinn. Der zulässige Wertebereich ist [0, 1000].

**Returns:**
int – Der zulässige Wertebereich.
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
### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Liest oder legt das GIF-Pixel-Seitenverhältnis fest.

Pixel Aspect Ratio - Faktor, der verwendet wird, um eine Annäherung des Seitenverhältnisses des Pixels im Originalbild zu berechnen. Wenn der Wert dieses Feldes nicht 0 ist, wird diese Annäherung des Seitenverhältnisses anhand der Formel berechnet: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Der Pixel Aspect Ratio ist definiert als das Verhältnis der Pixelbreite zur Pixelhöhe. Der Wertebereich in diesem Feld ermöglicht die Angabe des breitesten Pixels von 4:1 bis zum höchsten Pixel von 1:4 in Schritten von 1/64. Werte: 0 – Keine Seitenverhältnis-Informationen angegeben. 1..255 – Für die Berechnung verwendeter Wert.

**Returns:**
byte – Das GIF-Pixel-Seitenverhältnis.
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
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Liest oder legt einen Wert fest, der angibt, ob das GIF einen Trailer hat.

**Returns:**
boolean – true, wenn das GIF einen Trailer hat; andernfalls false.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Liest oder legt einen Wert fest, der angibt, ob Paletteneinträge sortiert sind.

**Returns:**
boolean – true, wenn Paletteneinträge sortiert sind; andernfalls false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Liest oder legt den GIF-Hintergrundfarbindizes fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | Der GIF-Hintergrundfarbindizes. |

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

### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Liest oder legt die GIF-Farbauflösung fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | byte | Die Farbauflösung. |

Farbauflösung – Anzahl der Bits pro Primärfarbe, die dem Originalbild zur Verfügung stehen, minus 1. Dieser Wert stellt die Größe der gesamten Palette dar, aus der die Farben in der Grafik ausgewählt wurden, nicht die Anzahl der tatsächlich in der Grafik verwendeten Farben. Zum Beispiel, wenn der Wert in diesem Feld 3 ist, dann hatte die Palette des Originalbildes 4 Bits pro Primärfarbe zur Erstellung des Bildes. Dieser Wert sollte gesetzt werden, um die Reichhaltigkeit der Originalpalette anzugeben, selbst wenn nicht jede Farbe der gesamten Palette auf der Quellmaschine verfügbar ist. |

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

### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Liest oder legt einen Wert fest, der angibt, ob die Palettenkorrektur angewendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | true  wenn die Palettenkorrektur angewendet wird; andernfalls  false . |

Palettenkorrektur bedeutet, dass jedes Mal, wenn ein Bild als GIF exportiert wird, die Farben des Quellbildes analysiert werden, um die am besten passende Palette zu erstellen (falls die Bildpalette nicht existiert oder in den Optionen nicht angegeben ist). Der Analyseprozess dauert etwas, jedoch wird das Ausgabebild die am besten passende Farbpalette besitzen und das Ergebnis ist visuell besser. |

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

### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


True, wenn das Bild interlaced sein soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Liest oder legt die maximal zulässige Pixeldifferenz fest. Wenn sie größer als Null ist, wird eine verlustbehaftete Kompression verwendet. Der empfohlene Wert für optimale verlustbehaftete Kompression beträgt 80. 30 ist eine sehr leichte Kompression, 200 ist stark. Sie funktioniert am besten, wenn nur wenig Verlust eingeführt wird, und aufgrund der Beschränkung des Kompressionsalgorithmus bringen sehr hohe Verluststufen nicht viel Gewinn. Der zulässige Wertebereich ist [0, 1000].

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Bereich der zulässigen Werte. |

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

### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Liest oder legt einen Wert fest, der angibt, ob Paletteneinträge sortiert sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true  wenn Paletteneinträge sortiert sind; andernfalls  false . |

### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Liest oder legt das GIF-Pixel-Seitenverhältnis fest.

Pixel Aspect Ratio - Faktor, der verwendet wird, um eine Annäherung des Seitenverhältnisses des Pixels im Originalbild zu berechnen. Wenn der Wert dieses Feldes nicht 0 ist, wird diese Annäherung des Seitenverhältnisses anhand der Formel berechnet: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Der Pixel Aspect Ratio ist definiert als das Verhältnis der Pixelbreite zur Pixelhöhe. Der Wertebereich in diesem Feld ermöglicht die Angabe des breitesten Pixels von 4:1 bis zum höchsten Pixel von 1:4 in Schritten von 1/64. Werte: 0 – Keine Seitenverhältnis-Informationen angegeben. 1..255 – Für die Berechnung verwendeter Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | Das Seitenverhältnis der GIF-Pixel. |

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

### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Liest oder legt einen Wert fest, der angibt, ob das GIF einen Trailer hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true  wenn das GIF einen Trailer hat; andernfalls  false . |

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

