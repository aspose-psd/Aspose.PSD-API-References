---
title: "PngOptions"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De PNG‑bestandsformaat‑creatieopties."
type: docs
weight: 19
url: /nl/java/com.aspose.psd.imageoptions/pngoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

De PNG‑bestandsformaat‑creatieopties.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PngOptions()](#PngOptions--) | Initialiseert een nieuw exemplaar van de  PngOptions  klasse. |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.psd.imageoptions.PngOptions-) | Initialiseert een nieuw exemplaar van de  JpegOptions  klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | Het standaard compressieniveau. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [deepClone()](#deepClone--) | Kloont deze instantie. |
| [deepClone_internalized()](#deepClone-internalized--) | Kloont deze instantie. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Haalt de bitsdiepte op. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Haalt op of stelt het type van de kleur in. |
| [getCompressionLevel()](#getCompressionLevel--) | Het png-afbeeldingscompressieniveau in het bereik 0-9, waarbij 9 maximale compressie is en 0 de opslagmodus. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Haalt op of stelt het standaard vervangende lettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij export naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is). |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getFilterType()](#getFilterType--) | Haalt op of stelt het filtertype in dat wordt gebruikt tijdens het opslaan van png-bestanden. |
| [getFullFrame()](#getFullFrame--) | Haalt een waarde op die aangeeft of [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event. |
| [getMultiPageOptions()](#getMultiPageOptions--) | De multipage-opties |
| [getPalette()](#getPalette--) | Haalt of stelt het kleurenpalet in. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Haalt of stelt de voortgang‑eventhandler in. |
| [getProgressive()](#getProgressive--) | Haalt op of stelt een waarde in die aangeeft of deze  PngOptions  progressief is. |
| [getResolutionSettings()](#getResolutionSettings--) | Haalt of stelt de resolutie‑instellingen in. |
| [getSource()](#getSource--) | Haalt of stelt de bron in waarin de afbeelding wordt gemaakt. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Haalt of stelt de vector‑rasterisatie‑opties in. |
| [getXmpData()](#getXmpData--) | Haalt of stelt de XMP‑metadatacontainer in. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Stelt de bitsdiepte in. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [setColorType(int value)](#setColorType-int-) | Haalt op of stelt het type van de kleur in. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Het png-afbeeldingscompressieniveau in het bereik 0-9, waarbij 9 maximale compressie is en 0 de opslagmodus. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Haalt op of stelt het standaard vervangende lettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij export naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is). |
| [setFilterType(int value)](#setFilterType-int-) | Haalt op of stelt het filtertype in dat wordt gebruikt tijdens het opslaan van png-bestanden. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Stelt een waarde in die aangeeft of [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | De multipage-opties |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Haalt of stelt het kleurenpalet in. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Haalt of stelt de voortgang‑eventhandler in. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze  PngOptions  progressief is. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Haalt of stelt de resolutie‑instellingen in. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Haalt of stelt de bron in waarin de afbeelding wordt gemaakt. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Haalt of stelt de vector‑rasterisatie‑opties in. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Haalt of stelt de XMP‑metadatacontainer in. |
| [toString()](#toString--) |  |
| [validate_internalized()](#validate-internalized--) | De validatieroutine voor opties. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngOptions() {#PngOptions--}
```
public PngOptions()
```


Initialiseert een nieuw exemplaar van de  PngOptions  klasse.

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.psd.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


Initialiseert een nieuw exemplaar van de  JpegOptions  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.psd.imageoptions/pngoptions) | De PNG-opties. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


Het standaard compressieniveau.

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


Implementeert de Closable-interface en kan worden gebruikt in de try-with-resources-instructie sinds JDK 1.7. Deze methode roept simpelweg de dispose-methode aan.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Kloont deze instantie.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Kloont deze instantie.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert de huidige instantie.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


Haalt de bitsdiepte op.

**Returns:**
byte - De bitsdiepte.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert.

Waarde: De buffer‑grootte hint, in megabytes. Een niet‑positieve waarde betekent geen geheugenlimiet voor interne buffers

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


Haalt op of stelt het type van de kleur in.

**Returns:**
int - Het type van de kleur.
### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


Het png-afbeeldingscompressieniveau in het bereik 0-9, waarbij 9 maximale compressie is en 0 de opslagmodus.

**Returns:**
int - het compressieniveau in het bereik 0-9, waarbij 9 maximale compressie is en 0 de opslagmodus.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Haalt of stelt het standaard vervangingslettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij exporteren naar raster, als het bestaande laagnaamlettertype in het PSD‑bestand niet in het systeem aanwezig is). Om de juiste naam van het standaardlettertype te verkrijgen, kan de volgende code‑fragment worden gebruikt: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Waarde: Het standaard vervangingslettertype.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Haalt een waarde op die aangeeft of deze instantie is vrijgegeven.

**Returns:**
boolean -  true  als vrijgegeven; anders,  false .
### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Haalt op of stelt het filtertype in dat wordt gebruikt tijdens het opslaan van png-bestanden.

**Returns:**
int - het filtertype dat wordt gebruikt tijdens het opslaan van png-bestanden.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Haalt een waarde op die aangeeft of [full frame].

Waarde:  true  als [full frame]; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of [full frame].
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event.

Waarde:  true  als negeren na het aanmaken‑event; anders,  false .

**Returns:**
boolean
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


De multipage-opties

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Haalt of stelt het kleurenpalet in.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Haalt of stelt de voortgang‑eventhandler in.

Waarde: De voortgangs‑eventhandler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


Haalt op of stelt een waarde in die aangeeft of deze  PngOptions  progressief is.

**Returns:**
boolean -  true  als progressief; anders,  false .
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Haalt of stelt de resolutie‑instellingen in.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getSource() {#getSource--}
```
public final Source getSource()
```


Haalt of stelt de bron in waarin de afbeelding wordt gemaakt.

Waarde: De bron waarin de afbeelding wordt gemaakt.

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Haalt of stelt de vector‑rasterisatie‑opties in.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Haalt of stelt de XMP‑metadatacontainer in.

Waarde: De XMP‑datacontainer.

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


Stelt de bitsdiepte in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte | De bitsdiepte. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert.

Waarde: De buffer‑grootte hint, in megabytes. Een niet‑positieve waarde betekent geen geheugenlimiet voor interne buffers

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Haalt op of stelt het type van de kleur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Het type van de kleur. |

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


Het png-afbeeldingscompressieniveau in het bereik 0-9, waarbij 9 maximale compressie is en 0 de opslagmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | het compressieniveau in het bereik 0-9, waarbij 9 maximale compressie is en 0 de opslagmodus. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Haalt of stelt het standaard vervangingslettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij exporteren naar raster, als het bestaande laagnaamlettertype in het PSD‑bestand niet in het systeem aanwezig is). Om de juiste naam van het standaardlettertype te verkrijgen, kan de volgende code‑fragment worden gebruikt: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Waarde: Het standaard vervangingslettertype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Haalt op of stelt het filtertype in dat wordt gebruikt tijdens het opslaan van png-bestanden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | het filtertype dat wordt gebruikt tijdens het opslaan van png-bestanden. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Stelt een waarde in die aangeeft of [full frame].

Waarde:  true  als [full frame]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | een waarde die aangeeft of [full frame]. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event.

Waarde:  true  als negeren na het aanmaken‑event; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


De multipage-opties

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Haalt of stelt het kleurenpalet in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Haalt of stelt de voortgang‑eventhandler in.

Waarde: De voortgangs‑eventhandler.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze  PngOptions  progressief is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true  als progressief; anders,  false . |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Haalt of stelt de resolutie‑instellingen in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Haalt of stelt de bron in waarin de afbeelding wordt gemaakt.

Waarde: De bron waarin de afbeelding wordt gemaakt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Haalt of stelt de vector‑rasterisatie‑opties in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Haalt of stelt de XMP‑metadatacontainer in.

Waarde: De XMP‑datacontainer.

**Parameters:**
| Parameter | Type | Beschrijving |
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


De validatieroutine voor opties.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

