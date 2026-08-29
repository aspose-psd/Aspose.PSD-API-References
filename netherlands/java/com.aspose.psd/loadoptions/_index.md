---
title: "LoadOptions"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt de laadopties voor."
type: docs
weight: 68
url: /nl/java/com.aspose.psd/loadoptions/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.progressmanagement.IProgressEventHandler
```
public class LoadOptions implements IProgressEventHandler
```

Stelt de laadopties voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | De aangepaste lettertype‑bronnen |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Haalt de buffer‑groottehint op, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Haalt de  Image  achtergrond  Color op. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Haalt de gegevensherstelmodus op. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Haalt een waarde op die aangeeft of [ignore after load]. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Haalt de voortgangs‑eventhandler op. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Haalt een waarde op die aangeeft of ICC‑profielconversie moet worden toegepast. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Dit is onderdeel van het venture‑licentiepatroon. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Stelt de buffergroottehint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Stelt de Image‑achtergrondkleur in. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Stelt de gegevensherstelmodus in. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Stelt een waarde in die aangeeft of [ignore after load]. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Haalt op of stelt de geheugen‑MGR in. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Stelt de voortgangs‑eventhandler in. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Stelt een waarde in die aangeeft of ICC‑profielconversie moet worden toegepast. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Dit is onderdeel van het venture‑licentiepatroon. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


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
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Haalt de voortgangs‑eventhandler op.

Waarde: De voortgangs‑eventhandler.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
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

