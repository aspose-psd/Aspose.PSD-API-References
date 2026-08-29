---
title: "PsdLoadOptions"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Psd laadopties"
type: docs
weight: 12
url: /nl/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

Psd laadopties
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | Initialiseert een nieuw exemplaar van de klasse [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions). |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | De aangepaste lettertype‑bronnen |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | Haalt op of stelt in of de originele laagpixels behouden moeten blijven tijdens het renderen als de laag niet is gewijzigd. |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | Haalt op of stelt in of er opgeslagen moet worden met het gerenderde beeld, met of zonder een warp‑transformatie. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Haalt de buffer‑groottehint op, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Haalt de  Image  achtergrond  Color op. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Haalt de gegevensherstelmodus op. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Haalt een waarde op die aangeeft of [ignore after load]. |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | Haalt op of stelt een waarde in die aangeeft of [ignore alpha channel]. |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | Haalt op of stelt een waarde in die aangeeft of de vaste breedte van een PSD‑tekstlaag wordt genegeerd bij de uitvoering van de UpdateText‑bewerking. |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | Haalt op of stelt een waarde in die aangeeft of [load effects resource] (standaard wordt de bron niet geladen). |
| [getProgressEventHandler()](#getProgressEventHandler--) | Haalt de voortgangs‑eventhandler op. |
| [getReadOnlyMode()](#getReadOnlyMode--) | Haalt op of stelt een waarde in die aangeeft of [use read only mode]. |
| [getReadOnlyType()](#getReadOnlyType--) | Haalt op of stelt de alleen‑lezen‑modus in die wordt gebruikt bij het laden van een PSD‑afbeelding. |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | Haalt op of stelt een waarde in die aangeeft of [use disk for load effects resource] (standaard wordt de schijf gebruikt om effectbronnen te laden, maar geheugen kan worden gebruikt als het voldoende is door deze waarde op false te zetten). |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Haalt een waarde op die aangeeft of ICC‑profielconversie moet worden toegepast. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Dit is onderdeel van het venture‑licentiepatroon. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | Haalt op of stelt in of de originele laagpixels behouden moeten blijven tijdens het renderen als de laag niet is gewijzigd. |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | Haalt op of stelt in of er opgeslagen moet worden met het gerenderde beeld, met of zonder een warp‑transformatie. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Stelt de buffergroottehint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Stelt de Image‑achtergrondkleur in. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Stelt de gegevensherstelmodus in. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Stelt een waarde in die aangeeft of [ignore after load]. |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | Haalt op of stelt een waarde in die aangeeft of [ignore alpha channel]. |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | Haalt op of stelt een waarde in die aangeeft of de vaste breedte van een PSD‑tekstlaag wordt genegeerd bij de uitvoering van de UpdateText‑bewerking. |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | Haalt op of stelt een waarde in die aangeeft of [load effects resource] (standaard wordt de bron niet geladen). |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Haalt op of stelt de geheugen‑MGR in. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Stelt de voortgangs‑eventhandler in. |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | Haalt op of stelt een waarde in die aangeeft of [use read only mode]. |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | Haalt op of stelt de alleen‑lezen‑modus in die wordt gebruikt bij het laden van een PSD‑afbeelding. |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | Haalt op of stelt een waarde in die aangeeft of [use disk for load effects resource] (standaard wordt de schijf gebruikt om effectbronnen te laden, maar geheugen kan worden gebruikt als het voldoende is door deze waarde op false te zetten). |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Stelt een waarde in die aangeeft of ICC‑profielconversie moet worden toegepast. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Dit is onderdeel van het venture‑licentiepatroon. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


Initialiseert een nieuw exemplaar van de klasse [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions).

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


De aangepaste lettertype‑bronnen

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


Haalt op of stelt in of de originele laagpixels behouden moeten blijven tijdens het renderen als de laag niet is gewijzigd.

Waarde: true om de originele pixels van onveranderde lagen te behouden; anders, false.

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


Haalt op of stelt in of er opgeslagen moet worden met het gerenderde beeld, met of zonder een warp‑transformatie.

Waarde: true om afbeelding te renderen met warp‑transformatie; false.

**Returns:**
boolean
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Haalt de buffer‑groottehint op, die de maximaal toegestane grootte voor alle interne buffers definieert.

Waarde: De buffer‑grootte hint, in megabytes. Een niet‑positieve waarde betekent geen geheugenlimiet voor interne buffers

**Returns:**
int - de buffer‑grootte hint die de maximaal toegestane grootte voor alle interne buffers definieert.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Haalt de  Image  achtergrond  Color op.

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

Meestal wordt de achtergrondkleur ingesteld wanneer een pixelwaarde niet kan worden hersteld vanwege gegevenscorruptie.
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Haalt de gegevensherstelmodus op.

**Returns:**
int - De gegevensherstelmodus.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Haalt een waarde op die aangeeft of [ignore after load].

**Returns:**
boolean -  true  als [ignore after load]; anders,  false .
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


Haalt op of stelt een waarde in die aangeeft of [ignore alpha channel].

Waarde: true als [ignore alpha channel]; anders, false.

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


Haalt op of stelt een waarde in die aangeeft of de vaste breedte van een PSD‑tekstlaag wordt genegeerd bij de uitvoering van de UpdateText‑bewerking.

Waarde: true als [ignore text layer width]; anders, false.

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


Haalt op of stelt een waarde in die aangeeft of [load effects resource] (standaard wordt de bron niet geladen). Wanneer deze optie is ingesteld, worden alleen ondersteunde effecten gerenderd naar de uiteindelijke samengevoegde afbeelding.

Waarde: true als [load effects resource]; anders, false.

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Haalt de voortgangs‑eventhandler op.

Waarde: De voortgangs‑eventhandler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


Haalt op of stelt een waarde in die aangeeft of [use read only mode]. Dit is een alleen‑lezen‑modus, ondersteund voor identieke compatibiliteit met Adobe Photoshop. Wanneer deze optie is ingesteld, worden alle wijzigingen die op lagen zijn toegepast niet opgeslagen in de uiteindelijke afbeelding. Alle gegevens worden gebruikt uit de ImageData‑sectie, waardoor het identiek is aan Photoshop. Standaard zijn alle geladen afbeeldingen niet identiek compatibel met Adobe Photoshop.

Waarde: true als [use photoshop compatibility mode]; anders, false.

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


Haalt op of stelt de alleen‑lezen‑modus in die wordt gebruikt bij het laden van een PSD‑afbeelding.

Waarde: Een van de ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)) waarden:

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


Haalt op of stelt een waarde in die aangeeft of [use disk for load effects resource] (standaard wordt de schijf gebruikt om effectbronnen te laden, maar geheugen kan worden gebruikt als het voldoende is door deze waarde op false te zetten).

Waarde: true als [use disk for load effects resource]; anders, false.

**Returns:**
boolean
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Haalt een waarde op die aangeeft of ICC‑profielconversie moet worden toegepast.

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Dit is onderdeel van het venture‑licentiepatroon. Deze waarde wordt ingesteld door VentureLicenser als de venture ons een LoadOptions‑object doorgeeft.

**Returns:**
java.lang.Object
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




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


Haalt op of stelt in of de originele laagpixels behouden moeten blijven tijdens het renderen als de laag niet is gewijzigd.

Waarde: true om de originele pixels van onveranderde lagen te behouden; anders, false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


Haalt op of stelt in of er opgeslagen moet worden met het gerenderde beeld, met of zonder een warp‑transformatie.

Waarde: true om afbeelding te renderen met warp‑transformatie; false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Stelt de buffergroottehint in, die de maximaal toegestane grootte voor alle interne buffers definieert.

Waarde: De buffer‑grootte hint, in megabytes. Een niet‑positieve waarde betekent geen geheugenlimiet voor interne buffers

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | de buffergroottehint die de maximaal toegestane grootte voor alle interne buffers definieert. |

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


Stelt de Image‑achtergrondkleur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | De achtergrondkleur. |

Meestal wordt de achtergrondkleur ingesteld wanneer een pixelwaarde niet kan worden hersteld vanwege gegevenscorruptie. |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Stelt de gegevensherstelmodus in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De gegevensherstelmodus. |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Stelt een waarde in die aangeeft of [ignore after load].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true als [ignore after load]; anders, false. |

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of [ignore alpha channel].

Waarde: true als [ignore alpha channel]; anders, false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of de vaste breedte van een PSD‑tekstlaag wordt genegeerd bij de uitvoering van de UpdateText‑bewerking.

Waarde: true als [ignore text layer width]; anders, false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of [load effects resource] (standaard wordt de bron niet geladen). Wanneer deze optie is ingesteld, worden alleen ondersteunde effecten gerenderd naar de uiteindelijke samengevoegde afbeelding.

Waarde: true als [load effects resource]; anders, false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


Haalt op of stelt de geheugen‑MGR in.

Waarde: Het geheugen MGR.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Stelt de voortgangs‑eventhandler in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | de voortgangs‑eventhandler. |

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of [use read only mode]. Dit is een alleen‑lezen‑modus, ondersteund voor identieke compatibiliteit met Adobe Photoshop. Wanneer deze optie is ingesteld, worden alle wijzigingen die op lagen zijn toegepast niet opgeslagen in de uiteindelijke afbeelding. Alle gegevens worden gebruikt uit de ImageData‑sectie, waardoor het identiek is aan Photoshop. Standaard zijn alle geladen afbeeldingen niet identiek compatibel met Adobe Photoshop.

Waarde: true als [use photoshop compatibility mode]; anders, false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


Haalt op of stelt de alleen‑lezen‑modus in die wordt gebruikt bij het laden van een PSD‑afbeelding.

Waarde: Een van de ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)) waarden:

 *  
 *  
 *  

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of [use disk for load effects resource] (standaard wordt de schijf gebruikt om effectbronnen te laden, maar geheugen kan worden gebruikt als het voldoende is door deze waarde op false te zetten).

Waarde: true als [use disk for load effects resource]; anders, false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Stelt een waarde in die aangeeft of ICC‑profielconversie moet worden toegepast.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


Dit is onderdeel van het venture‑licentiepatroon. Deze waarde wordt ingesteld door VentureLicenser als de venture ons een LoadOptions‑object doorgeeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

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

