---
title: "WorkingPathResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Resurs för arbetsökväg."
type: docs
weight: 43
url: /sv/java/com.aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class WorkingPathResource extends ResourceBlock implements IVectorPathData
```

Resurs för arbetsökväg.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [WorkingPathResource(byte[] dataBytes)](#WorkingPathResource-byte---) | Initierar en ny instans av klassen [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Resurssignaturen för ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Den vanliga Photoshop-resurssignaturen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Hämtar resursens datastorlek i byte. |
| [getID()](#getID--) | Hämtar eller anger den unika identifieraren för resursen. |
| [getMinimalVersion()](#getMinimalVersion--) | Hämtar den minsta erforderliga PSD-versionen. |
| [getName()](#getName--) | Hämtar eller anger resursnamnet. |
| [getPaths()](#getPaths--) | Hämtar eller anger sökvägsregistren. |
| [getSignature()](#getSignature--) | Hämtar resurssignaturen. |
| [getSize()](#getSize--) | Hämtar resursblockets storlek i byte inklusive dess data. |
| [getVersion()](#getVersion--) | Hämtar eller anger versionen. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Hämtar eller anger ett värde som indikerar om denna instans är inaktiverad. |
| [isInverted()](#isInverted--) | Hämtar eller anger ett värde som indikerar om denna instans är inverterad. |
| [isNotLinked()](#isNotLinked--) | Hämtar eller anger ett värde som indikerar om denna instans inte är länkad. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Sparar resursblocket till den angivna strömmen. |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är inaktiverad. |
| [setID(short value)](#setID-short-) | Hämtar eller anger den unika identifieraren för resursen. |
| [setInverted(boolean value)](#setInverted-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är inverterad. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Hämtar eller anger lager- och maskinformation. |
| [setName(String value)](#setName-java.lang.String-) | Hämtar eller anger resursnamnet. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans inte är länkad. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Hämtar eller anger sökvägsregistren. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Hämtar eller anger resursblockets tillstånd. |
| [setVersion(int value)](#setVersion-int-) | Hämtar eller anger versionen. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validerar resursvärdena. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WorkingPathResource(byte[] dataBytes) {#WorkingPathResource-byte---}
```
public WorkingPathResource(byte[] dataBytes)
```


Initierar en ny instans av klassen [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataBytes | byte[] | Data för vektorsökvägen. |

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


Resurssignaturen för ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


Den vanliga Photoshop-resurssignaturen.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Hämtar resursens datastorlek i byte.

Värde: Resursens datastorlek.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Hämtar eller anger den unika identifieraren för resursen.

Värde: Den unika identifieraren för resursen.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Hämtar den minsta erforderliga PSD-versionen.

Värde: Den minsta PSD-versionen.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två byte med 0).

Värde: Resursnamnet.

**Returns:**
java.lang.String
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Hämtar eller anger sökvägsregistren.

Värde: Sökvägarna.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Hämtar resursens signatur. Ska alltid vara '8BIM'.

Värde: Resursens signatur.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Hämtar resursblockets storlek i byte inklusive dess data.

Värde: Storleken på resursblocket.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Hämtar eller anger versionen.

Värde: Versionen.

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


Hämtar eller anger ett värde som indikerar om denna instans är inaktiverad.

Värde:  true  om denna instans är inaktiverad; annars,  false .

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


Hämtar eller anger ett värde som indikerar om denna instans är inverterad.

Värde:  true  om denna instans är inverterad; annars,  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


Hämtar eller anger ett värde som indikerar om denna instans inte är länkad.

Värde:  true  om denna instans inte är länkad; annars,  false .

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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Sparar resursblocket till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömmen att spara resursblocket till. |

### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna instans är inaktiverad.

Värde:  true  om denna instans är inaktiverad; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Hämtar eller anger den unika identifieraren för resursen.

Värde: Den unika identifieraren för resursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna instans är inverterad.

Värde:  true  om denna instans är inverterad; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Hämtar eller anger lager- och maskinformation.

Värde: Lager- och maskinformation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två byte med 0).

Värde: Resursnamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna instans inte är länkad.

Värde:  true  om denna instans inte är länkad; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


Hämtar eller anger sökvägsregistren.

Värde: Sökvägarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatur | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Hämtar eller anger resursblockets tillstånd.

Värde: Resursblockets tillstånd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Hämtar eller anger versionen.

Värde: Versionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Validerar resursvärdena.

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

