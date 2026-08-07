---
title: "JpegOptions"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die JPEG‑Dateiformat‑Erstellungsoptionen."
type: docs
weight: 15
url: /de/java/com.aspose.psd.imageoptions/jpegoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class JpegOptions extends ImageOptionsBase
```

Die JPEG‑Dateiformat‑Erstellungsoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Initialisiert eine neue Instanz der  JpegOptions  Klasse. |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Initialisiert eine neue Instanz der  JpegOptions  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [deepClone()](#deepClone--) | Klont diese Instanz. |
| [deepClone_internalized()](#deepClone-internalized--) | Klont diese Instanz. |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerChannel()](#getBitsPerChannel--) | Ermittelt Bits pro Kanal für verlustfreies JPEG-Bild. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Das Ziel-CMYK-Farbprofil für CMYK-JPEG-Bilder. |
| [getColorType()](#getColorType--) | Ermittelt den Farbtyp für JPEG-Bild. |
| [getComment()](#getComment--) | Ermittelt den JPEG-Dateikommentar. |
| [getCompressionType()](#getCompressionType--) | Ermittelt den Kompressionstyp. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Ermittelt das Standard-Limit für Speicherzuweisung. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Liest oder setzt die Standard‑Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen‑Schriftart in der PSD‑Datei im System nicht vorhanden ist). |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getExifData()](#getExifData--) | Exif-Datencontainer abrufen oder festlegen |
| [getFullFrame()](#getFullFrame--) | Gibt einen Wert zurück, der angibt, ob [full frame]. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Ermittelt die horizontalen Subsamplings für jede Komponente. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird. |
| [getJfif()](#getJfif--) | Ermittelt das JFIF. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Ermittelt die JPEG-LS-Differenzgrenze für nahezu verlustlose Kodierung (NEAR-Parameter aus der JPEG-LS-Spezifikation). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Ermittelt den JPEG-LS-Interleave-Modus. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Ermittelt die JPEG-LS-Voreinstellungsparameter. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Die Mehrseitenoptionen |
| [getPalette()](#getPalette--) | Ruft die Farbpalette ab oder legt sie fest. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Ermittelt einen Wert, der angibt, ob Rot-, Grün- und Blaukomponenten mit einer Hintergrundfarbe gemischt werden sollen, falls ein Alpha-Kanal vorhanden ist. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest. |
| [getQuality()](#getQuality--) | Ermittelt die Bildqualität. |
| [getRdOptSettings()](#getRdOptSettings--) | Ermittelt die RD-Optimierer-Einstellungen. |
| [getResolutionSettings()](#getResolutionSettings--) | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [getResolutionUnit()](#getResolutionUnit--) | Liest die Auflösungseinheit. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Das Ziel-RGB-Farbprofil für CMYK-JPEG-Bilder. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Liest den Rundungsmodus der Probe, um einen 8‑Bit‑Wert an einen n‑Bit‑Wert anzupassen. |
| [getScaledQuality()](#getScaledQuality--) | Die skalierte Qualität. |
| [getSource()](#getSource--) | Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest. |
| [getVerticalSampling()](#getVerticalSampling--) | Liest die vertikalen Subsamplings für jede Komponente. |
| [getXmpData()](#getXmpData--) | Liest den XMP-Metadaten‑Container. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Setzt Bits pro Kanal für verlustfreie JPEG‑Bilder. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Das Ziel-CMYK-Farbprofil für CMYK-JPEG-Bilder. |
| [setColorType(int value)](#setColorType-int-) | Setzt den Farbtyp für JPEG‑Bilder. |
| [setComment(String value)](#setComment-java.lang.String-) | Setzt den JPEG‑Dateikommentar. |
| [setCompressionType(int value)](#setCompressionType-int-) | Setzt den Kompressionstyp. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Setzt das Standard‑Speicherzuweisungs‑Limit. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Liest oder setzt die Standard‑Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen‑Schriftart in der PSD‑Datei im System nicht vorhanden ist). |
| [setExifData(JpegExifData value)](#setExifData-com.aspose.psd.exif.JpegExifData-) | Exif-Datencontainer abrufen oder festlegen |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Legt einen Wert fest, der angibt, ob [full frame]. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Setzt die horizontalen Subsamplings für jede Komponente. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-) | Setzt das JFIF. |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Setzt die JPEG‑LS-Differenzgrenze für nahezu verlustfreie Kodierung (NEAR‑Parameter aus der JPEG‑LS‑Spezifikation). |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Setzt den JPEG‑LS‑Interleavemodus. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-) | Setzt die JPEG‑LS‑Voreinstellungsparameter. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Die Mehrseitenoptionen |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ruft die Farbpalette ab oder legt sie fest. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Setzt einen Wert, der angibt, ob Rot-, Grün‑ und Blau‑Komponenten mit einer Hintergrundfarbe gemischt werden sollen, falls ein Alpha‑Kanal vorhanden ist. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest. |
| [setQuality(int value)](#setQuality-int-) | Setzt die Bildqualität. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-) | Setzt die RD‑Optimierer‑Einstellungen. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Setzt die Auflösungseinheit. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Das Ziel-RGB-Farbprofil für CMYK-JPEG-Bilder. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Setzt den Rundungsmodus der Probe, um einen 8‑Bit‑Wert an einen n‑Bit‑Wert anzupassen. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Ruft die Quelle ab, in der das Bild erstellt wird, oder legt sie fest. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Ruft die Vektor-Rasterisierungsoptionen ab oder legt sie fest. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Setzt die vertikalen Subsamplings für jede Komponente. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Setzt den XMP‑Metadaten‑Container. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Initialisiert eine neue Instanz der  JpegOptions  Klasse.

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Initialisiert eine neue Instanz der  JpegOptions  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) | Die JPEG‑Optionen. |

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
### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Liest Bits pro Kanal für verlustfreie JPEG‑Bilder. Jetzt unterstützen wir von 2 bis 8 Bits pro Kanal.

**Returns:**
byte
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
### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


Das Ziel-CMYK-Farbprofil für CMYK-JPEG-Bilder. Wird zum Speichern von Bildern verwendet. Muss zusammen mit RGBColorProfile für korrekte Farbumwandlung verwendet werden.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorType() {#getColorType--}
```
public int getColorType()
```


Ermittelt den Farbtyp für JPEG-Bild.

**Returns:**
int
### getComment() {#getComment--}
```
public String getComment()
```


Ermittelt den JPEG-Dateikommentar.

**Returns:**
java.lang.String
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Ermittelt den Kompressionstyp.

**Returns:**
int
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Ermittelt das Standard-Limit für Speicherzuweisung.

**Returns:**
int - Das standardmäßige Speicherzuweisungs-Limit.
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
### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Exif-Datencontainer abrufen oder festlegen

**Returns:**
[JpegExifData](../../com.aspose.psd.exif/jpegexifdata)
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Gibt einen Wert zurück, der angibt, ob [full frame].

Wert:  true  wenn [full frame]; andernfalls  false .

**Returns:**
boolescher Wert – ein Wert, der angibt, ob [full frame].
### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Ermittelt die horizontalen Subsamplings für jede Komponente.

**Returns:**
byte[]
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob nach dem Erstellen-Ereignis ignoriert wird.

Wert:  true  wenn nach dem Erstellen-Ereignis ignoriert wird; andernfalls  false .

**Returns:**
boolean
### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Ermittelt das JFIF.

**Returns:**
[JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata)
### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


Ermittelt die JPEG-LS-Differenzgrenze für nahezu verlustlose Kodierung (NEAR-Parameter aus der JPEG-LS-Spezifikation).

**Returns:**
int
### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Ermittelt den JPEG-LS-Interleave-Modus.

**Returns:**
int
### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Ermittelt die JPEG-LS-Voreinstellungsparameter.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters)
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
### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Ermittelt einen Wert, der angibt, ob Rot-, Grün- und Blaukomponenten mit einer Hintergrundfarbe gemischt werden sollen, falls ein Alpha-Kanal vorhanden ist.

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Ruft den Fortschritt-Ereignishandler ab oder legt ihn fest.

Wert: Der Fortschritts‑Ereignis‑Handler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getQuality() {#getQuality--}
```
public int getQuality()
```


Ermittelt die Bildqualität.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Ermittelt die RD-Optimierer-Einstellungen.

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Ruft die Auflösungseinstellungen ab oder legt sie fest.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Liest die Auflösungseinheit.

**Returns:**
byte - die Auflösungseinheit.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Das Ziel-RGB-Farbprofil für CMYK-JPEG-Bilder. Wird zum Speichern von Bildern verwendet. Muss zusammen mit CMYKColorProfile für korrekte Farbumwandlung verwendet werden.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Liest den Rundungsmodus für das Sample, um einen 8‑Bit‑Wert an einen n‑Bit‑Wert anzupassen.  P:JpegOptions.BitsPerChannel

**Returns:**
int
### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


Die skalierte Qualität.

**Returns:**
int
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
### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Liest die vertikalen Subsamplings für jede Komponente.

**Returns:**
byte[]
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Liest den XMP-Metadaten‑Container.

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




### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Setzt die Bits pro Kanal für verlustfreie JPEG‑Bilder. Jetzt unterstützen wir 2 bis 8 Bits pro Kanal.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

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

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Das Ziel-CMYK-Farbprofil für CMYK-JPEG-Bilder. Wird zum Speichern von Bildern verwendet. Muss zusammen mit RGBColorProfile für korrekte Farbumwandlung verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Setzt den Farbtyp für JPEG‑Bilder.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Setzt den JPEG‑Dateikommentar.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Setzt den Kompressionstyp.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Setzt das Standard‑Speicherzuweisungs‑Limit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Das standardmäßige Speicherzuweisungs-Limit. |

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

### setExifData(JpegExifData value) {#setExifData-com.aspose.psd.exif.JpegExifData-}
```
public void setExifData(JpegExifData value)
```


Exif-Datencontainer abrufen oder festlegen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.psd.exif/jpegexifdata) |  |

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

### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Setzt die horizontalen Subsamplings für jede Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

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

### setJfif(JFIFData value) {#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Setzt das JFIF.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata) |  |

### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Setzt die JPEG‑LS-Differenzgrenze für nahezu verlustfreie Kodierung (NEAR‑Parameter aus der JPEG‑LS‑Spezifikation).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Setzt den JPEG‑LS‑Interleavemodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Setzt die JPEG‑LS‑Voreinstellungsparameter.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters) |  |

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

### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Setzt einen Wert, der angibt, ob Rot-, Grün‑ und Blau‑Komponenten mit einer Hintergrundfarbe gemischt werden sollen, falls ein Alpha‑Kanal vorhanden ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Setzt die Bildqualität.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Setzt die RD‑Optimierer‑Einstellungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) | Die RD‑Optimizer‑Einstellungen. |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Ruft die Auflösungseinstellungen ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Setzt die Auflösungseinheit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | die Auflösungseinheit. |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Das Ziel-RGB-Farbprofil für CMYK-JPEG-Bilder. Wird zum Speichern von Bildern verwendet. Muss zusammen mit CMYKColorProfile für korrekte Farbumwandlung verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Setzt den Rundungsmodus für das Sample, um einen 8‑Bit‑Wert an einen n‑Bit‑Wert anzupassen.  P:JpegOptions.BitsPerChannel

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Setzt die vertikalen Subsamplings für jede Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Setzt den XMP‑Metadaten‑Container.

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

