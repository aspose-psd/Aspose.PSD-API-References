---
title: "GifOptions"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De GIF‑bestandsformaat‑creatieopties."
type: docs
weight: 12
url: /nl/java/com.aspose.psd.imageoptions/gifoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

De GIF‑bestandsformaat‑creatieopties.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initialiseert een nieuw exemplaar van de  GifOptions  klasse. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.psd.imageoptions.GifOptions-) | Initialiseert een nieuw exemplaar van de  GifOptions  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [deepClone()](#deepClone--) | Kloont deze instantie. |
| [deepClone_internalized()](#deepClone-internalized--) | Kloont deze instantie. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Haalt op of stelt de GIF-achtergrondkleurindex in. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [getClass()](#getClass--) |  |
| [getColorResolution()](#getColorResolution--) | Haalt op of stelt de GIF-kleuroplossing in. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Haalt op of stelt het standaard vervangende lettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij export naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is). |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Haalt op of stelt een waarde in die aangeeft of paletcorrectie wordt toegepast. |
| [getFullFrame()](#getFullFrame--) | Haalt een waarde op die aangeeft of [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event. |
| [getInterlaced()](#getInterlaced--) | Waar als de afbeelding moet worden geïnterleaved. |
| [getMaxDiff()](#getMaxDiff--) | Haalt op of stelt het maximaal toegestane pixelverschil in. |
| [getMultiPageOptions()](#getMultiPageOptions--) | De multipage-opties |
| [getPalette()](#getPalette--) | Haalt of stelt het kleurenpalet in. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Haalt op of stelt de GIF-pixelaspectverhouding in. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Haalt of stelt de voortgang‑eventhandler in. |
| [getResolutionSettings()](#getResolutionSettings--) | Haalt of stelt de resolutie‑instellingen in. |
| [getSource()](#getSource--) | Haalt of stelt de bron in waarin de afbeelding wordt gemaakt. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Haalt of stelt de vector‑rasterisatie‑opties in. |
| [getXmpData()](#getXmpData--) | Haalt of stelt de XMP‑metadatacontainer in. |
| [hasTrailer()](#hasTrailer--) | Haalt op of stelt een waarde in die aangeeft of GIF een trailer heeft. |
| [hashCode()](#hashCode--) |  |
| [isPaletteSorted()](#isPaletteSorted--) | Haalt op of stelt een waarde in die aangeeft of paletinvoer gesorteerd zijn. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Haalt op of stelt de GIF-achtergrondkleurindex in. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Haalt op of stelt de GIF-kleuroplossing in. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Haalt op of stelt het standaard vervangende lettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij export naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is). |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Haalt op of stelt een waarde in die aangeeft of paletcorrectie wordt toegepast. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Stelt een waarde in die aangeeft of [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Waar als de afbeelding moet worden geïnterleaved. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Haalt op of stelt het maximaal toegestane pixelverschil in. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | De multipage-opties |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Haalt of stelt het kleurenpalet in. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Haalt op of stelt een waarde in die aangeeft of paletinvoer gesorteerd zijn. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Haalt op of stelt de GIF-pixelaspectverhouding in. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Haalt of stelt de voortgang‑eventhandler in. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Haalt of stelt de resolutie‑instellingen in. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Haalt of stelt de bron in waarin de afbeelding wordt gemaakt. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Haalt op of stelt een waarde in die aangeeft of GIF een trailer heeft. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Haalt of stelt de vector‑rasterisatie‑opties in. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Haalt of stelt de XMP‑metadatacontainer in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Initialiseert een nieuw exemplaar van de  GifOptions  klasse.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.psd.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Initialiseert een nieuw exemplaar van de  GifOptions  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.psd.imageoptions/gifoptions) | De GIF-opties. |

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
### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Haalt op of stelt de GIF-achtergrondkleurindex in.

**Returns:**
byte - De GIF-achtergrondkleurindex.
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
### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Haalt op of stelt de GIF-kleuroplossing in.

**Returns:**
byte - De kleurresolutie.

Color Resolution - Aantal bits per primaire kleur beschikbaar in de originele afbeelding, minus 1. Deze waarde vertegenwoordigt de grootte van de volledige palet waaruit de kleuren in de grafiek zijn geselecteerd, niet het aantal kleuren dat daadwerkelijk in de grafiek wordt gebruikt. Bijvoorbeeld, als de waarde in dit veld 3 is, dan had het palet van de originele afbeelding 4 bits per primaire kleur beschikbaar om de afbeelding te maken. Deze waarde moet worden ingesteld om de rijkdom van het originele palet aan te geven, zelfs als niet elke kleur uit het volledige palet beschikbaar is op de bronmachine.
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
### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Haalt op of stelt een waarde in die aangeeft of paletcorrectie wordt toegepast.

**Returns:**
boolean -  true  als paletcorrectie wordt toegepast; anders,  false .

Paletcorrectie betekent dat telkens wanneer een afbeelding wordt geëxporteerd naar GIF, de kleuren van de bronafbeelding worden geanalyseerd om het best passende palet samen te stellen (in het geval dat het afbeeldingspalet niet bestaat of niet is gespecificeerd in de opties). Het analyseproces kost wat tijd, maar de uitvoerafbeelding zal het best passende kleurenpalet hebben en het resultaat is visueel beter.
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
### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Waar als de afbeelding moet worden geïnterleaved.

**Returns:**
boolean
### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Haalt of stelt het maximaal toegestane pixelverschil in. Als het groter is dan nul, wordt verliesgevende compressie gebruikt. De aanbevolen waarde voor optimale verliesgevende compressie is 80. 30 is zeer lichte compressie, 200 is zwaar. Het werkt het beste wanneer slechts weinig verlies wordt geïntroduceerd, en door de beperking van het compressie‑algoritme zullen zeer hoge verliesniveaus niet zoveel winst opleveren. Het bereik van toegestane waarden is [0, 1000].

**Returns:**
int - Het bereik van toegestane waarden.
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
### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Haalt op of stelt de GIF-pixelaspectverhouding in.

Pixel Aspect Ratio - Factor die wordt gebruikt om een benadering van de beeldverhouding van de pixel in de originele afbeelding te berekenen. Als de waarde van het veld niet 0 is, wordt deze benadering van de beeldverhouding berekend op basis van de formule: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. De Pixel Aspect Ratio wordt gedefinieerd als het quotiënt van de breedte van de pixel gedeeld door de hoogte. Het waardebereik in dit veld maakt specificatie mogelijk van de breedste pixel van 4:1 tot de hoogste pixel van 1:4 in stappen van 1/64. Waarden: 0 - Geen beeldverhoudingsinformatie opgegeven. 1..255 - Waarde gebruikt in de berekening.

**Returns:**
byte - De GIF-pixelaspectverhouding.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Haalt of stelt de voortgang‑eventhandler in.

Waarde: De voortgangs‑eventhandler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
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

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Haalt op of stelt een waarde in die aangeeft of GIF een trailer heeft.

**Returns:**
boolean -  true  als GIF een trailer heeft; anders,  false .
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


Haalt op of stelt een waarde in die aangeeft of paletinvoer gesorteerd zijn.

**Returns:**
boolean -  true  als paletinvoer gesorteerd zijn; anders,  false .
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


Haalt op of stelt de GIF-achtergrondkleurindex in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte | De GIF-achtergrondkleurindex. |

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

### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Haalt op of stelt de GIF-kleuroplossing in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | byte | De kleurresolutie. |

Color Resolution - Aantal bits per primaire kleur beschikbaar in de originele afbeelding, minus 1. Deze waarde vertegenwoordigt de grootte van de volledige palet waaruit de kleuren in de grafiek zijn geselecteerd, niet het aantal kleuren dat daadwerkelijk in de grafiek wordt gebruikt. Bijvoorbeeld, als de waarde in dit veld 3 is, dan had het palet van de originele afbeelding 4 bits per primaire kleur beschikbaar om de afbeelding te maken. Deze waarde moet worden ingesteld om de rijkdom van het originele palet aan te geven, zelfs als niet elke kleur uit het volledige palet beschikbaar is op de bronmachine. |

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

### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of paletcorrectie wordt toegepast.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true  als paletcorrectie wordt toegepast; anders,  false . |

Paletcorrectie betekent dat telkens wanneer een afbeelding wordt geëxporteerd naar GIF, de kleuren van de bronafbeelding worden geanalyseerd om het best passende palet samen te stellen (in het geval dat het afbeeldingspalet niet bestaat of niet is gespecificeerd in de opties). Het analyseproces kost wat tijd, maar de uitvoerafbeelding zal het best passende kleurenpalet hebben en het resultaat is visueel beter. |

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

### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Waar als de afbeelding moet worden geïnterleaved.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Haalt of stelt het maximaal toegestane pixelverschil in. Als het groter is dan nul, wordt verliesgevende compressie gebruikt. De aanbevolen waarde voor optimale verliesgevende compressie is 80. 30 is zeer lichte compressie, 200 is zwaar. Het werkt het beste wanneer slechts weinig verlies wordt geïntroduceerd, en door de beperking van het compressie‑algoritme zullen zeer hoge verliesniveaus niet zoveel winst opleveren. Het bereik van toegestane waarden is [0, 1000].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Het bereik van toegestane waarden. |

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

### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of paletinvoer gesorteerd zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true  als paletinvoer gesorteerd zijn; anders,  false . |

### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Haalt op of stelt de GIF-pixelaspectverhouding in.

Pixel Aspect Ratio - Factor die wordt gebruikt om een benadering van de beeldverhouding van de pixel in de originele afbeelding te berekenen. Als de waarde van het veld niet 0 is, wordt deze benadering van de beeldverhouding berekend op basis van de formule: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. De Pixel Aspect Ratio wordt gedefinieerd als het quotiënt van de breedte van de pixel gedeeld door de hoogte. Het waardebereik in dit veld maakt specificatie mogelijk van de breedste pixel van 4:1 tot de hoogste pixel van 1:4 in stappen van 1/64. Waarden: 0 - Geen beeldverhoudingsinformatie opgegeven. 1..255 - Waarde gebruikt in de berekening.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte | De GIF-pixelaspectverhouding. |

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

### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of GIF een trailer heeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true  als GIF een trailer heeft; anders,  false . |

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | De XMP-gegevenscontainer. |

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

