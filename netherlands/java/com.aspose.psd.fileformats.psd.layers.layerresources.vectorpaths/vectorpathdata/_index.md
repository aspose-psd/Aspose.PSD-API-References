---
title: "VectorPathData"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De klasse om met een vectorpad te werken."
type: docs
weight: 18
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class VectorPathData implements IVectorPathData
```

De klasse om met een vectorpad te werken.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [VectorPathData(byte[] data)](#VectorPathData-byte---) | Initialiseert een nieuw exemplaar van de [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) klasse. |
| [VectorPathData()](#VectorPathData--) | Initialiseert een nieuw exemplaar van de [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [SizeOfTheGeneralInfo_internalized](#SizeOfTheGeneralInfo-internalized) | De grootte van de algemene informatie zoals versie en vlaggen. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsByteArray_internalized()](#getAsByteArray-internalized--) | Wordt opgehaald als byte-array. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Haalt de lengte van de vectorpadgegevens op in de resource als bytes. |
| [getPaths()](#getPaths--) | Haalt de padrecords op of stelt ze in. |
| [getVersion()](#getVersion--) | Haalt of stelt de versie in. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar is uitgeschakeld. |
| [isInverted()](#isInverted--) | Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar is omgekeerd. |
| [isNotLinked()](#isNotLinked--) | Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar niet gekoppeld is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar is uitgeschakeld. |
| [setInverted(boolean value)](#setInverted-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar is omgekeerd. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar niet gekoppeld is. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Haalt de padrecords op of stelt ze in. |
| [setVersion(int value)](#setVersion-int-) | Haalt of stelt de versie in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathData(byte[] data) {#VectorPathData-byte---}
```
public VectorPathData(byte[] data)
```


Initialiseert een nieuw exemplaar van de [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | byte[] | De resourcegegevens. |

### VectorPathData() {#VectorPathData--}
```
public VectorPathData()
```


Initialiseert een nieuw exemplaar van de [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) klasse.

### SizeOfTheGeneralInfo_internalized {#SizeOfTheGeneralInfo-internalized}
```
public static final int SizeOfTheGeneralInfo_internalized
```


De grootte van de algemene informatie zoals versie en vlaggen.

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
### getAsByteArray_internalized() {#getAsByteArray-internalized--}
```
public final byte[] getAsByteArray_internalized()
```


Wordt opgehaald als byte-array.

**Returns:**
byte[] - De resource als byte-array.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


Haalt de lengte van de vectorpadgegevens op in de resource als bytes.

**Returns:**
int
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Haalt de padrecords op of stelt ze in.

Waarde: de paden.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Haalt of stelt de versie in.

Waarde: De versie.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar is uitgeschakeld.

Waarde:  true  als dit exemplaar is uitgeschakeld; anders,  false .

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar is omgekeerd.

Waarde:  true  als dit exemplaar is omgekeerd; anders,  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar niet gekoppeld is.

Waarde:  true  als dit exemplaar niet gekoppeld is; anders,  false .

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




### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar is uitgeschakeld.

Waarde:  true  als dit exemplaar is uitgeschakeld; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar is omgekeerd.

Waarde:  true  als dit exemplaar is omgekeerd; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar niet gekoppeld is.

Waarde:  true  als dit exemplaar niet gekoppeld is; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


Haalt de padrecords op of stelt ze in.

Waarde: de paden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Haalt of stelt de versie in.

Waarde: De versie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

