---
title: "PsdOptions"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De PSD‑bestandsformaat‑creatieopties."
type: docs
weight: 21
url: /nl/java/com.aspose.psd.imageoptions/psdoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

De PSD‑bestandsformaat‑creatieopties.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Initialiseert een nieuw exemplaar van de [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) klasse. |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-) | Initialiseert een nieuw exemplaar van de [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) klasse. |
| [PsdOptions(PsdImage image)](#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-) | Initialiseert een nieuw exemplaar van de [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [deepClone()](#deepClone--) | Kloont deze instantie. |
| [deepClone_internalized()](#deepClone-internalized--) | Kloont deze instantie. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundContents()](#getBackgroundContents--) | Haalt de achtergrondkleur op of stelt deze in. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Haalt het aantal bits per kleurkanaal op of stelt dit in. |
| [getChannelsCount()](#getChannelsCount--) | Haalt het aantal kleurkanalen op of stelt dit in. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Haalt de PSD-kleurmodus op of stelt deze in. |
| [getCompressionMethod()](#getCompressionMethod--) | Haalt de PSD-compressiemethode op of stelt deze in. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Haalt op of stelt het standaard vervangende lettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij export naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is). |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getFullFrame()](#getFullFrame--) | Haalt een waarde op die aangeeft of [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event. |
| [getMultiPageOptions()](#getMultiPageOptions--) | De multipage-opties |
| [getPalette()](#getPalette--) | Haalt of stelt het kleurenpalet in. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Haalt of stelt de voortgang‑eventhandler in. |
| [getPsdVersion()](#getPsdVersion--) | Haalt de bestandsformaatversie op of stelt deze in. |
| [getRefreshImagePreviewData()](#getRefreshImagePreviewData--) | Haalt een waarde op of stelt deze in die aangeeft of [refresh image preview data] - optie gebruikt om de compatibiliteit met andere PSD-beeldkijkers te maximaliseren. |
| [getRemoveGlobalTextEngineResource()](#getRemoveGlobalTextEngineResource--) | Haalt een waarde op of stelt deze in die aangeeft of - Verwijder de globale tekstengine resource - Gebruikt voor sommige tekst‑gelaagde PSD‑bestanden, alleen in het geval dat ze na verwerking niet kunnen worden geopend in Adobe Photoshop (voornamelijk gerelateerd aan ontbrekende lettertype‑tekstlagen). |
| [getResolutionSettings()](#getResolutionSettings--) | Haalt of stelt de resolutie‑instellingen in. |
| [getResources()](#getResources--) | Haalt de PSD-resources op of stelt deze in. |
| [getSource()](#getSource--) | Haalt of stelt de bron in waarin de afbeelding wordt gemaakt. |
| [getUpdateMetadata()](#getUpdateMetadata--) | Haalt een waarde op of stelt deze in die aangeeft of [update metadata]. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Haalt of stelt de vector‑rasterisatie‑opties in. |
| [getVersion()](#getVersion--) | Haalt de PSD-bestandsversie op of stelt deze in. |
| [getXmpData()](#getXmpData--) | Haal of stel XMP-gegevenscontainer in |
| [hashCode()](#hashCode--) |  |
| [isColorModeSet()](#isColorModeSet--) | Toont of de ColorMode‑eigenschap is toegewezen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundContents(RawColor value)](#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Haalt de achtergrondkleur op of stelt deze in. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Haalt het aantal bits per kleurkanaal op of stelt dit in. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Haalt het aantal kleurkanalen op of stelt dit in. |
| [setColorMode(short value)](#setColorMode-short-) | Haalt de PSD-kleurmodus op of stelt deze in. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Haalt de PSD-compressiemethode op of stelt deze in. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Haalt op of stelt het standaard vervangende lettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij export naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Stelt een waarde in die aangeeft of [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of negeren na het aanmaken‑event. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | De multipage-opties |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Haalt of stelt het kleurenpalet in. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Haalt of stelt de voortgang‑eventhandler in. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Haalt de bestandsformaatversie op of stelt deze in. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of [refresh image preview data] - optie gebruikt om de compatibiliteit met andere PSD-beeldkijkers te maximaliseren. |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of - Verwijder de globale tekstengine resource - Gebruikt voor sommige tekst‑gelaagde PSD‑bestanden, alleen in het geval dat ze na verwerking niet kunnen worden geopend in Adobe Photoshop (voornamelijk gerelateerd aan ontbrekende lettertype‑tekstlagen). |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Haalt of stelt de resolutie‑instellingen in. |
| [setResources(ResourceBlock[] value)](#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Haalt de PSD-resources op of stelt deze in. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Haalt of stelt de bron in waarin de afbeelding wordt gemaakt. |
| [setUpdateMetadata(boolean value)](#setUpdateMetadata-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of [update metadata]. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Haalt of stelt de vector‑rasterisatie‑opties in. |
| [setVersion(int value)](#setVersion-int-) | Haalt de PSD-bestandsversie op of stelt deze in. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Haal of stel XMP-gegevenscontainer in |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Initialiseert een nieuw exemplaar van de [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) klasse.

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Initialiseert een nieuw exemplaar van de [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | De opties. |

### PsdOptions(PsdImage image) {#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-}
```
public PsdOptions(PsdImage image)
```


Initialiseert een nieuw exemplaar van de [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | De afbeelding. |

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
### getBackgroundContents() {#getBackgroundContents--}
```
public final RawColor getBackgroundContents()
```


Haalt of stelt de achtergrondkleur in. Deze kan worden gezien onder transparante objecten.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Haalt op of stelt de buffer grootte hint in, die de maximaal toegestane grootte voor alle interne buffers definieert.

Waarde: De buffer‑grootte hint, in megabytes. Een niet‑positieve waarde betekent geen geheugenlimiet voor interne buffers

**Returns:**
int
### getChannelBitsCount() {#getChannelBitsCount--}
```
public final short getChannelBitsCount()
```


Haalt het aantal bits per kleurkanaal op of stelt dit in.

Waarde: Het aantal bits per kleurkanaal.

**Returns:**
short
### getChannelsCount() {#getChannelsCount--}
```
public final short getChannelsCount()
```


Haalt het aantal kleurkanalen op of stelt dit in.

Waarde: Het aantal kleurkanalen.

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


Haalt de PSD-kleurmodus op of stelt deze in.

Waarde: De kleurmodus.

**Returns:**
short
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Haalt de PSD-compressiemethode op of stelt deze in.

Waarde: De compressiemethode.

**Returns:**
short
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
### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Haalt de bestandsformaatversie op of stelt deze in. Het kan PSD of PSB zijn.

Waarde: De bestandsformaatversie.

**Returns:**
byte
### getRefreshImagePreviewData() {#getRefreshImagePreviewData--}
```
public final boolean getRefreshImagePreviewData()
```


Haalt een waarde op of stelt deze in die aangeeft of [refresh image preview data] - optie gebruikt om de compatibiliteit met andere PSD-beeldkijkers te maximaliseren. Houd er rekening mee dat het tekenen van tekstlagen naar de uiteindelijke lay-out niet wordt ondersteund op het Compact Framework‑platform.

Waarde:  true  als [refresh image preview data]; anders,  false .

**Returns:**
boolean
### getRemoveGlobalTextEngineResource() {#getRemoveGlobalTextEngineResource--}
```
public final boolean getRemoveGlobalTextEngineResource()
```


Haalt een waarde op of stelt deze in die aangeeft of - Verwijder de globale tekstengine resource - Gebruikt voor sommige tekst‑gelaagde PSD‑bestanden, alleen in het geval dat ze na verwerking niet kunnen worden geopend in Adobe Photoshop (voornamelijk gerelateerd aan ontbrekende lettertype‑tekstlagen). Na het gebruiken van deze optie moet de gebruiker het volgende doen in het geopende Photoshop‑bestand: Menu \"Text\" -> \"Process absent fonts\". Na die bewerking zal alle tekst weer verschijnen. Houd er rekening mee dat deze bewerking enkele wijzigingen in de uiteindelijke lay-out kan veroorzaken.

Waarde:  true  als [remove global text engine resource]; anders,  false .

**Returns:**
boolean
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Haalt of stelt de resolutie‑instellingen in.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResources() {#getResources--}
```
public final ResourceBlock[] getResources()
```


Haalt de PSD-resources op of stelt deze in. Als waarde: NULL - sla dan de originele ImageResources op (standaardgedrag) Niet Leeg - sla dan de resources op die aan deze eigenschap zijn doorgegeven + [required resources] Leeg - sla dan alleen [required resources] op. Vereiste resources: ResolutionInfoResource, XmpResource.

Waarde: De PSD-resources.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getSource() {#getSource--}
```
public final Source getSource()
```


Haalt of stelt de bron in waarin de afbeelding wordt gemaakt.

Waarde: De bron waarin de afbeelding wordt gemaakt.

**Returns:**
[Source](../../com.aspose.psd/source)
### getUpdateMetadata() {#getUpdateMetadata--}
```
public final boolean getUpdateMetadata()
```


Haalt een waarde op of stelt deze in die aangeeft of [update metadata]. Als de waarde true is, wordt de metadata bijgewerkt bij het opslaan van een afbeelding.

Waarde:  true  als [update metadata]; anders,  false .

**Returns:**
boolean
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Haalt of stelt de vector‑rasterisatie‑opties in.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Haalt de PSD-bestandsversie op of stelt deze in.

Waarde: De PSD-bestandsversie.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Haal of stel XMP-gegevenscontainer in

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


Toont of de ColorMode‑eigenschap is toegewezen.

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


Haalt of stelt de achtergrondkleur in. Deze kan worden gezien onder transparante objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public final void setChannelBitsCount(short value)
```


Haalt het aantal bits per kleurkanaal op of stelt dit in.

Waarde: Het aantal bits per kleurkanaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setChannelsCount(short value) {#setChannelsCount-short-}
```
public final void setChannelsCount(short value)
```


Haalt het aantal kleurkanalen op of stelt dit in.

Waarde: Het aantal kleurkanalen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Haalt de PSD-kleurmodus op of stelt deze in.

Waarde: De kleurmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Haalt de PSD-compressiemethode op of stelt deze in.

Waarde: De compressiemethode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

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

### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Haalt de bestandsformaatversie op of stelt deze in. Het kan PSD of PSB zijn.

Waarde: De bestandsformaatversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public final void setRefreshImagePreviewData(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of [refresh image preview data] - optie gebruikt om de compatibiliteit met andere PSD-beeldkijkers te maximaliseren. Houd er rekening mee dat het tekenen van tekstlagen naar de uiteindelijke lay-out niet wordt ondersteund op het Compact Framework‑platform.

Waarde:  true  als [refresh image preview data]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public final void setRemoveGlobalTextEngineResource(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of - Verwijder de globale tekstengine resource - Gebruikt voor sommige tekst‑gelaagde PSD‑bestanden, alleen in het geval dat ze na verwerking niet kunnen worden geopend in Adobe Photoshop (voornamelijk gerelateerd aan ontbrekende lettertype‑tekstlagen). Na het gebruiken van deze optie moet de gebruiker het volgende doen in het geopende Photoshop‑bestand: Menu \"Text\" -> \"Process absent fonts\". Na die bewerking zal alle tekst weer verschijnen. Houd er rekening mee dat deze bewerking enkele wijzigingen in de uiteindelijke lay-out kan veroorzaken.

Waarde:  true  als [remove global text engine resource]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Haalt of stelt de resolutie‑instellingen in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResources(ResourceBlock[] value) {#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setResources(ResourceBlock[] value)
```


Haalt de PSD-resources op of stelt deze in. Als waarde: NULL - sla dan de originele ImageResources op (standaardgedrag) Niet Leeg - sla dan de resources op die aan deze eigenschap zijn doorgegeven + [required resources] Leeg - sla dan alleen [required resources] op. Vereiste resources: ResolutionInfoResource, XmpResource.

Waarde: De PSD-resources.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setUpdateMetadata(boolean value) {#setUpdateMetadata-boolean-}
```
public final void setUpdateMetadata(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of [update metadata]. Als de waarde true is, wordt de metadata bijgewerkt bij het opslaan van een afbeelding.

Waarde:  true  als [update metadata]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Haalt of stelt de vector‑rasterisatie‑opties in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Haalt de PSD-bestandsversie op of stelt deze in.

Waarde: De PSD-bestandsversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Haal of stel XMP-gegevenscontainer in

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

