---
title: "JpegOptions"
second_title: "Aspose.PSD för Java API-referens"
description: "JPEG-filformatets skapandealternativ."
type: docs
weight: 15
url: /sv/java/com.aspose.psd.imageoptions/jpegoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class JpegOptions extends ImageOptionsBase
```

JPEG-filformatets skapandealternativ.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Initierar en ny instans av klassen JpegOptions. |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Initierar en ny instans av klassen JpegOptions. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [deepClone()](#deepClone--) | Klonar den här instansen. |
| [deepClone_internalized()](#deepClone-internalized--) | Klonar den här instansen. |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerChannel()](#getBitsPerChannel--) | Hämtar bitar per kanal för förlustfri jpeg-bild. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Destinations-CMYK-färgprofilen för CMYK jpeg-bilder. |
| [getColorType()](#getColorType--) | Hämtar färgtypen för jpeg-bild. |
| [getComment()](#getComment--) | Hämtar jpeg-filkommentaren. |
| [getCompressionType()](#getCompressionType--) | Hämtar kompressionstypen. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Hämtar standardgränsen för minnesallokering. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD-filen inte finns i systemet). |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getExifData()](#getExifData--) | Hämta eller ange exif-datakontainer |
| [getFullFrame()](#getFullFrame--) | Hämtar ett värde som anger om [full frame]. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Hämtar de horisontella subsamplingarna för varje komponent. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Hämtar eller anger ett värde som anger om ignorera efter skapa‑händelse. |
| [getJfif()](#getJfif--) | Hämtar jfif. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Hämtar JPEG-LS-differensgränsen för nästan förlustfri kodning (NEAR-parameter från JPEG-LS-specifikationen). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Hämtar JPEG-LS-interleavläget. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Hämtar JPEG-LS-förinställda parametrar. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Multipagesalternativen |
| [getPalette()](#getPalette--) | Hämtar eller anger färgpaletten. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Hämtar ett värde som indikerar om röd, grön och blå komponenter ska blandas med en bakgrundsfärg, om alfakanal finns. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Hämtar eller anger hanteraren för förlopps‑händelsen. |
| [getQuality()](#getQuality--) | Hämtar bildkvaliteten. |
| [getRdOptSettings()](#getRdOptSettings--) | Hämtar RD-optimerarens inställningar. |
| [getResolutionSettings()](#getResolutionSettings--) | Hämtar eller anger upplösningsinställningarna. |
| [getResolutionUnit()](#getResolutionUnit--) | Hämtar upplösningsenheten. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Den destination RGB‑färgprofilen för CMYK‑jpeg‑bilder. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Hämtar provavrundningsläget för att anpassa ett 8‑bitars värde till ett n‑bitars värde. |
| [getScaledQuality()](#getScaledQuality--) | Den skalade kvaliteten. |
| [getSource()](#getSource--) | Hämtar eller anger källan där bilden ska skapas. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Hämtar eller anger vektor‑rasteriseringsalternativen. |
| [getVerticalSampling()](#getVerticalSampling--) | Hämtar de vertikala undersamplingsvärdena för varje komponent. |
| [getXmpData()](#getXmpData--) | Hämtar XMP‑metadata‑behållaren. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Ställer in bitar per kanal för förlustfri jpeg‑bild. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Destinations-CMYK-färgprofilen för CMYK jpeg-bilder. |
| [setColorType(int value)](#setColorType-int-) | Ställer in färgtypen för jpeg‑bild. |
| [setComment(String value)](#setComment-java.lang.String-) | Ställer in jpeg‑filkommentaren. |
| [setCompressionType(int value)](#setCompressionType-int-) | Ställer in komprimeringstypen. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Ställer in standardgränsen för minnesallokering. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Hämtar eller anger standardersättningsfonten (font som kommer att användas för att rita text vid export till raster, om befintlig lagerfont i PSD-filen inte finns i systemet). |
| [setExifData(JpegExifData value)](#setExifData-com.aspose.psd.exif.JpegExifData-) | Hämta eller ange exif-datakontainer |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Anger ett värde som anger om [full frame]. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Ställer in de horisontella undersamplingsvärdena för varje komponent. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Hämtar eller anger ett värde som anger om ignorera efter skapa‑händelse. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-) | Ställer in jfif. |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Ställer in JPEG-LS‑differensgränsen för nästan förlustfri kodning (NEAR‑parametern från JPEG-LS‑specifikationen). |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Ställer in JPEG-LS‑interleavläget. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-) | Ställer in JPEG-LS‑förinställda parametrar. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Multipagesalternativen |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Hämtar eller anger färgpaletten. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Ställer in ett värde som indikerar om röd, grön och blå komponenter ska blandas med en bakgrundsfärg, om alfakanal finns. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Hämtar eller anger hanteraren för förlopps‑händelsen. |
| [setQuality(int value)](#setQuality-int-) | Ställer in bildkvaliteten. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-) | Ställer in RD‑optimerarens inställningar. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Hämtar eller anger upplösningsinställningarna. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Ställer in upplösningsenheten. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Den destination RGB‑färgprofilen för CMYK‑jpeg‑bilder. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Ställer in provavrundningsläget för att anpassa ett 8‑bitars värde till ett n‑bitars värde. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Hämtar eller anger källan där bilden ska skapas. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Hämtar eller anger vektor‑rasteriseringsalternativen. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Ställer in de vertikala undersamplingsvärdena för varje komponent. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Ställer in XMP‑metadata‑behållaren. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Initierar en ny instans av klassen JpegOptions.

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Initierar en ny instans av klassen JpegOptions.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) | JPEG‑alternativen. |

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
### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Hämtar bitar per kanal för förlustfri jpeg‑bild. Nu stödjer vi från 2 till 8 bitar per kanal.

**Returns:**
byte
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
### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


Den destination CMYK‑färgprofilen för CMYK‑jpeg‑bilder. Använd för att spara bilder. Måste vara i par med RGBColorProfile för korrekt färgkonvertering.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorType() {#getColorType--}
```
public int getColorType()
```


Hämtar färgtypen för jpeg-bild.

**Returns:**
int
### getComment() {#getComment--}
```
public String getComment()
```


Hämtar jpeg-filkommentaren.

**Returns:**
java.lang.String
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Hämtar kompressionstypen.

**Returns:**
int
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Hämtar standardgränsen för minnesallokering.

**Returns:**
int - Den standardmässiga gränsen för minnesallokering.
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
### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Hämta eller ange exif-datakontainer

**Returns:**
[JpegExifData](../../com.aspose.psd.exif/jpegexifdata)
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Hämtar ett värde som anger om [full frame].

Värde:  true  om [full frame]; annars  false .

**Returns:**
boolean - ett värde som anger om [full frame].
### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Hämtar de horisontella subsamplingarna för varje komponent.

**Returns:**
byte[]
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Hämtar eller anger ett värde som anger om ignorera efter skapa‑händelse.

Värde:  true  om ignorera efter skapa‑händelse; annars  false .

**Returns:**
boolean
### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Hämtar jfif.

**Returns:**
[JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata)
### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


Hämtar JPEG-LS-differensgränsen för nästan förlustfri kodning (NEAR-parameter från JPEG-LS-specifikationen).

**Returns:**
int
### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Hämtar JPEG-LS-interleavläget.

**Returns:**
int
### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Hämtar JPEG-LS-förinställda parametrar.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters)
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
### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Hämtar ett värde som indikerar om röd, grön och blå komponenter ska blandas med en bakgrundsfärg, om alfakanal finns.

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Hämtar eller anger hanteraren för förlopps‑händelsen.

Värde: hanteraren för progress‑händelsen.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getQuality() {#getQuality--}
```
public int getQuality()
```


Hämtar bildkvaliteten.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Hämtar RD-optimerarens inställningar.

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Hämtar eller anger upplösningsinställningarna.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Hämtar upplösningsenheten.

**Returns:**
byte - upplösningsenheten.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Destinations‑RGB‑färgprofilen för CMYK‑jpeg‑bilder. Använd för att spara bilder. Måste paras med CMYKColorProfile för korrekt färgkonvertering.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Hämtar provavrundningsläget för att anpassa ett 8‑bitars värde till ett n‑bitars värde.  P:JpegOptions.BitsPerChannel

**Returns:**
int
### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


Den skalade kvaliteten.

**Returns:**
int
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
### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Hämtar de vertikala undersamplingsvärdena för varje komponent.

**Returns:**
byte[]
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Hämtar XMP‑metadata‑behållaren.

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


Ställer in bitar per kanal för förlustfri jpeg‑bild. Nu stöds 2 till 8 bitar per kanal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

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

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Den destination CMYK‑färgprofilen för CMYK‑jpeg‑bilder. Använd för att spara bilder. Måste vara i par med RGBColorProfile för korrekt färgkonvertering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Ställer in färgtypen för jpeg‑bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Ställer in jpeg‑filkommentaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Ställer in komprimeringstypen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Ställer in standardgränsen för minnesallokering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Den standardmässiga gränsen för minnesallokering. |

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

### setExifData(JpegExifData value) {#setExifData-com.aspose.psd.exif.JpegExifData-}
```
public void setExifData(JpegExifData value)
```


Hämta eller ange exif-datakontainer

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.psd.exif/jpegexifdata) |  |

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

### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Ställer in de horisontella undersamplingsvärdena för varje komponent.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

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

### setJfif(JFIFData value) {#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Ställer in jfif.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata) |  |

### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Ställer in JPEG-LS‑differensgränsen för nästan förlustfri kodning (NEAR‑parametern från JPEG-LS‑specifikationen).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Ställer in JPEG-LS‑interleavläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Ställer in JPEG-LS‑förinställda parametrar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters) |  |

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

### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Ställer in ett värde som indikerar om röd, grön och blå komponenter ska blandas med en bakgrundsfärg, om alfakanal finns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Ställer in bildkvaliteten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Ställer in RD‑optimerarens inställningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) | Inställningarna för RD‑optimeraren. |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Hämtar eller anger upplösningsinställningarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Ställer in upplösningsenheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | upplösningsenheten. |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Destinations‑RGB‑färgprofilen för CMYK‑jpeg‑bilder. Använd för att spara bilder. Måste paras med CMYKColorProfile för korrekt färgkonvertering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Ställer in provavrundningsläget för att anpassa ett 8‑bitars värde till ett n‑bitars värde.  P:JpegOptions.BitsPerChannel

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Ställer in de vertikala undersamplingsvärdena för varje komponent.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Ställer in XMP‑metadata‑behållaren.

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

