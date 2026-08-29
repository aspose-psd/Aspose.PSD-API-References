---
title: "PngOptions"
second_title: "Aspose.PSD för Java API-referens"
description: "PNG-filformatets skapandealternativ."
type: docs
weight: 19
url: /sv/java/com.aspose.psd.imageoptions/pngoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

PNG-filformatets skapandealternativ.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PngOptions()](#PngOptions--) | Initierar en ny instans av  PngOptions  klassen. |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.psd.imageoptions.PngOptions-) | Initierar en ny instans av klassen JpegOptions. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | Standardkomprimeringsnivån. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [deepClone()](#deepClone--) | Klonar den här instansen. |
| [deepClone_internalized()](#deepClone-internalized--) | Klonar den här instansen. |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Hämtar bitdjupet. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Hämtar eller anger färgens typ. |
| [getCompressionLevel()](#getCompressionLevel--) | png-bildens komprimeringsnivå i intervallet 0-9, där 9 är maximal kompression och 0 är lagringsläge. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD-filen inte finns i systemet). |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getFilterType()](#getFilterType--) | Hämtar eller anger filtertypen som används under png-filsparningsprocessen. |
| [getFullFrame()](#getFullFrame--) | Hämtar ett värde som anger om [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Hämtar eller anger ett värde som anger om ignorera efter skapa‑händelse. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Multipagesalternativen |
| [getPalette()](#getPalette--) | Hämtar eller anger färgpaletten. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Hämtar eller anger hanteraren för förlopps‑händelsen. |
| [getProgressive()](#getProgressive--) | Hämtar eller anger ett värde som indikerar om detta  PngOptions  är progressivt. |
| [getResolutionSettings()](#getResolutionSettings--) | Hämtar eller anger upplösningsinställningarna. |
| [getSource()](#getSource--) | Hämtar eller anger källan där bilden ska skapas. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Hämtar eller anger vektor‑rasteriseringsalternativen. |
| [getXmpData()](#getXmpData--) | Hämtar eller anger XMP‑metadata‑behållaren. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Anger bitdjupet. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [setColorType(int value)](#setColorType-int-) | Hämtar eller anger färgens typ. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | png-bildens komprimeringsnivå i intervallet 0-9, där 9 är maximal kompression och 0 är lagringsläge. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD-filen inte finns i systemet). |
| [setFilterType(int value)](#setFilterType-int-) | Hämtar eller anger filtertypen som används under png-filsparningsprocessen. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Anger ett värde som anger om [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Hämtar eller anger ett värde som anger om ignorera efter skapa‑händelse. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Multipagesalternativen |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Hämtar eller anger färgpaletten. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Hämtar eller anger hanteraren för förlopps‑händelsen. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Hämtar eller anger ett värde som indikerar om detta  PngOptions  är progressivt. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Hämtar eller anger upplösningsinställningarna. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Hämtar eller anger källan där bilden ska skapas. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Hämtar eller anger vektor‑rasteriseringsalternativen. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Hämtar eller anger XMP‑metadata‑behållaren. |
| [toString()](#toString--) |  |
| [validate_internalized()](#validate-internalized--) | Valideringsrutinen för alternativen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngOptions() {#PngOptions--}
```
public PngOptions()
```


Initierar en ny instans av  PngOptions  klassen.

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.psd.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


Initierar en ny instans av klassen JpegOptions.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.psd.imageoptions/pngoptions) | PNG-alternativen. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


Standardkomprimeringsnivån.

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


Implementerar Closable‑gränssnittet och kan användas i try‑with‑resources‑satsen sedan JDK 1.7. Denna metod anropar helt enkelt dispose‑metoden.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Klonar den här instansen.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Klonar den här instansen.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Frigör den aktuella instansen.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


Hämtar bitdjupet.

**Returns:**
byte - Bitdjupet.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Tips om buffertstorlek, i megabyte. Icke‑positivt värde betyder ingen minnesbegränsning för interna buffertar.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Hämtar eller anger färgens typ.

**Returns:**
int - Färgens typ.
### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


png-bildens komprimeringsnivå i intervallet 0-9, där 9 är maximal kompression och 0 är lagringsläge.

**Returns:**
int - komprimeringsnivån i intervallet 0-9, där 9 är maximal kompression och 0 är lagringsläge.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD‑filen inte finns i systemet). För att få rätt namn på standardfonten kan följande kodsnutt användas: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Värde: Standardersättningsfonten.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean -  true  om frigjord; annars,  false .
### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Hämtar eller anger filtertypen som används under png-filsparningsprocessen.

**Returns:**
int - filtertypen som används under png-filsparningsprocessen.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Hämtar ett värde som anger om [full frame].

Värde:  true  om [full frame]; annars  false .

**Returns:**
boolean - ett värde som anger om [full frame].
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Hämtar eller anger ett värde som anger om ignorera efter skapa‑händelse.

Värde:  true  om ignorera efter skapa‑händelse; annars  false .

**Returns:**
boolean
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Multipagesalternativen

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Hämtar eller anger färgpaletten.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Hämtar eller anger hanteraren för förlopps‑händelsen.

Värde: hanteraren för progress‑händelsen.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


Hämtar eller anger ett värde som indikerar om detta  PngOptions  är progressivt.

**Returns:**
boolean -  true  om progressiv; annars,  false .
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Hämtar eller anger upplösningsinställningarna.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getSource() {#getSource--}
```
public final Source getSource()
```


Hämtar eller anger källan där bilden ska skapas.

Värde: Källan där bilden ska skapas.

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Hämtar eller anger vektor‑rasteriseringsalternativen.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Hämtar eller anger XMP‑metadata‑behållaren.

Värde: XMP‑databehållaren.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
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




### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


Anger bitdjupet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | Bitdjupet. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Tips om buffertstorlek, i megabyte. Icke‑positivt värde betyder ingen minnesbegränsning för interna buffertar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Hämtar eller anger färgens typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Färgens typ. |

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


png-bildens komprimeringsnivå i intervallet 0-9, där 9 är maximal kompression och 0 är lagringsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | komprimeringsnivån i intervallet 0-9, där 9 är maximal kompression och 0 är lagringsläge. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD‑filen inte finns i systemet). För att få rätt namn på standardfonten kan följande kodsnutt användas: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Värde: Standardersättningsfonten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Hämtar eller anger filtertypen som används under png-filsparningsprocessen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | filtertypen som används under png-filsparningsprocessen. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Anger ett värde som anger om [full frame].

Värde:  true  om [full frame]; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som anger om [full frame]. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Hämtar eller anger ett värde som anger om ignorera efter skapa‑händelse.

Värde:  true  om ignorera efter skapa‑händelse; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Multipagesalternativen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Hämtar eller anger färgpaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Hämtar eller anger hanteraren för förlopps‑händelsen.

Värde: hanteraren för progress‑händelsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta  PngOptions  är progressivt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true  om progressiv; annars,  false . |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Hämtar eller anger upplösningsinställningarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Hämtar eller anger källan där bilden ska skapas.

Värde: Källan där bilden ska skapas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Hämtar eller anger vektor‑rasteriseringsalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Hämtar eller anger XMP‑metadata‑behållaren.

Värde: XMP‑databehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate_internalized() {#validate-internalized--}
```
public void validate_internalized()
```


Valideringsrutinen för alternativen.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

