---
title: "Jpeg2000Options"
second_title: "Aspose.PSD för Java API-referens"
description: "JPEG2000-filformatets alternativ."
type: docs
weight: 14
url: /sv/java/com.aspose.psd.imageoptions/jpeg2000options/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

JPEG2000-filformatets alternativ.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | Initierar en ny instans av klassen  Jpeg2000Options . |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.psd.imageoptions.Jpeg2000Options-) | Initierar en ny instans av klassen  Jpeg2000Options . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [deepClone()](#deepClone--) | Klonar den här instansen. |
| [deepClone_internalized()](#deepClone-internalized--) | Klonar den här instansen. |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [getClass()](#getClass--) |  |
| [getCodec()](#getCodec--) | Hämtar eller anger JPEG2000-codec |
| [getComments()](#getComments--) | Hämtar eller anger Jpeg-kommentarmarkörer. |
| [getCompressionRatios()](#getCompressionRatios--) | Hämtar eller anger arrayen med komprimeringsförhållanden. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD-filen inte finns i systemet). |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getFullFrame()](#getFullFrame--) | Hämtar ett värde som anger om [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Hämtar eller anger ett värde som anger om ignorera efter skapa‑händelse. |
| [getIrreversible()](#getIrreversible--) | Hämtar ett värde som indikerar om den irreversibla DWT 9-7 (true) ska användas eller om förlustfri DWT 5-3-kompression (standard) ska användas. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Multipagesalternativen |
| [getPalette()](#getPalette--) | Hämtar eller anger färgpaletten. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Hämtar eller anger hanteraren för förlopps‑händelsen. |
| [getResolutionSettings()](#getResolutionSettings--) | Hämtar eller anger upplösningsinställningarna. |
| [getSource()](#getSource--) | Hämtar eller anger källan där bilden ska skapas. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Hämtar eller anger vektor‑rasteriseringsalternativen. |
| [getXmpData()](#getXmpData--) | Hämtar eller anger XMP‑metadata‑behållaren. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [setCodec(int value)](#setCodec-int-) | Hämtar eller anger JPEG2000-codec |
| [setComments(String[] value)](#setComments-java.lang.String---) | Hämtar eller anger Jpeg-kommentarmarkörer. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | Hämtar eller anger arrayen med komprimeringsförhållanden. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD-filen inte finns i systemet). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Anger ett värde som anger om [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Hämtar eller anger ett värde som anger om ignorera efter skapa‑händelse. |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | Anger ett värde som indikerar om den irreversibla DWT 9-7 (true) ska användas eller om förlustfri DWT 5-3-kompression (standard) ska användas. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Multipagesalternativen |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Hämtar eller anger färgpaletten. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Hämtar eller anger hanteraren för förlopps‑händelsen. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Hämtar eller anger upplösningsinställningarna. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Hämtar eller anger källan där bilden ska skapas. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Hämtar eller anger vektor‑rasteriseringsalternativen. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Hämtar eller anger XMP‑metadata‑behållaren. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


Initierar en ny instans av klassen  Jpeg2000Options .

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.psd.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


Initierar en ny instans av klassen  Jpeg2000Options .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.psd.imageoptions/jpeg2000options) | Jpeg2000-filformatalternativen att kopiera inställningar från. |

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
### getCodec() {#getCodec--}
```
public int getCodec()
```


Hämtar eller anger JPEG2000-codec

**Returns:**
int - JPEG2000-codec
### getComments() {#getComments--}
```
public String[] getComments()
```


Hämtar eller anger Jpeg-kommentarmarkörer.

**Returns:**
java.lang.String[] - Jpeg-kommentarmarkörer.
### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


Hämtar eller anger arrayen med komprimeringsförhållanden. Olika komprimeringsförhållanden för på varandra följande lager. Hastigheten som anges för varje kvalitetsnivå är den önskade komprimeringsfaktorn. Minskande förhållanden krävs.

**Returns:**
int[] - Komprimeringsförhållandena.
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
### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


Hämtar ett värde som indikerar om den irreversibla DWT 9-7 (true) ska användas eller om förlustfri DWT 5-3-kompression (standard) ska användas.

**Returns:**
boolean - ett värde som indikerar om den irreversibla DWT 9-7 (true) ska användas eller om förlustfri DWT 5-3-komprimering ska användas
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


Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Tips om buffertstorlek, i megabyte. Icke‑positivt värde betyder ingen minnesbegränsning för interna buffertar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


Hämtar eller anger JPEG2000-codec

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | JPEG2000-codec |

### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Hämtar eller anger Jpeg-kommentarmarkörer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String[] | Jpeg-kommentarmarkörer. |

### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


Hämtar eller anger arrayen med komprimeringsförhållanden. Olika komprimeringsförhållanden för på varandra följande lager. Hastigheten som anges för varje kvalitetsnivå är den önskade komprimeringsfaktorn. Minskande förhållanden krävs.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] | Komprimeringsförhållandena. |

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

### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


Anger ett värde som indikerar om den irreversibla DWT 9-7 (true) ska användas eller om förlustfri DWT 5-3-kompression (standard) ska användas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om den irreversibla DWT 9-7 (true) ska användas eller om förlustfri DWT 5-3-komprimering ska användas |

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

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP-datakontainer. |

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

