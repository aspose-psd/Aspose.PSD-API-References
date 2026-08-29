---
title: "AnimatedDataSectionResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Den animerade datasektions-plug-in-resursen."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.fileformats.psd.resources/animateddatasectionresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public class AnimatedDataSectionResource extends ResourceBlock
```

Den animerade datasektions-plug-in-resursen.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Resurssignaturen för ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Den vanliga Photoshop-resurssignaturen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [create_internalized()](#create-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnimatedDataSection()](#getAnimatedDataSection--) | Hämtar eller anger strukturen för den animerade datasektionen. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Hämtar resursens datastorlek i byte. |
| [getID()](#getID--) | Hämtar eller anger den unika identifieraren för resursen. |
| [getKeyName()](#getKeyName--) | Resursnyckelns namn. |
| [getMinimalVersion()](#getMinimalVersion--) | Hämtar den minsta erforderliga PSD-versionen. |
| [getName()](#getName--) | Hämtar eller anger resursnamnet. |
| [getSignature()](#getSignature--) | Hämtar resurssignaturen. |
| [getSize()](#getSize--) | Hämtar resursblockets storlek i byte inklusive dess data. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Sparar resursblocket till den angivna strömmen. |
| [setAnimatedDataSection_internalized(AnimatedDataSectionStructure value)](#setAnimatedDataSection-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.AnimatedDataSectionStructure-) | Hämtar eller anger strukturen för den animerade datasektionen. |
| [setID(short value)](#setID-short-) | Hämtar eller anger den unika identifieraren för resursen. |
| [setKeyName_internalized(String value)](#setKeyName-internalized-java.lang.String-) | Resursnyckelns namn. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Hämtar eller anger lager- och maskinformation. |
| [setName(String value)](#setName-java.lang.String-) | Hämtar eller anger resursnamnet. |
| [setRoll_internalized(RollStructure value)](#setRoll-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.RollStructure-) | Hämtar eller anger rollstrukturen. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Hämtar eller anger resursblockets tillstånd. |
| [setUnknownLeftBytes_internalized(byte[] value)](#setUnknownLeftBytes-internalized-byte---) | De okända byten från originalresursen. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validerar resursvärdena. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### create_internalized() {#create-internalized--}
```
public static AnimatedDataSectionResource create_internalized()
```




**Returns:**
[AnimatedDataSectionResource](../../com.aspose.psd.fileformats.psd.resources/animateddatasectionresource)
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
### getAnimatedDataSection() {#getAnimatedDataSection--}
```
public final AnimatedDataSectionStructure getAnimatedDataSection()
```


Hämtar eller anger strukturen för den animerade datasektionen.

**Returns:**
[AnimatedDataSectionStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure)
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
### getKeyName() {#getKeyName--}
```
public final String getKeyName()
```


Resursnyckelns namn.

**Returns:**
java.lang.String
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Sparar resursblocket till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömmen att spara resursblocket till. |

### setAnimatedDataSection_internalized(AnimatedDataSectionStructure value) {#setAnimatedDataSection-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.AnimatedDataSectionStructure-}
```
public final void setAnimatedDataSection_internalized(AnimatedDataSectionStructure value)
```


Hämtar eller anger strukturen för den animerade datasektionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [AnimatedDataSectionStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure) |  |

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

### setKeyName_internalized(String value) {#setKeyName-internalized-java.lang.String-}
```
public final void setKeyName_internalized(String value)
```


Resursnyckelns namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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

### setRoll_internalized(RollStructure value) {#setRoll-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.RollStructure-}
```
public final void setRoll_internalized(RollStructure value)
```


Hämtar eller anger rollstrukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.fileformats.psd.layers.layerresources.RollStructure |  |

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

### setUnknownLeftBytes_internalized(byte[] value) {#setUnknownLeftBytes-internalized-byte---}
```
public final void setUnknownLeftBytes_internalized(byte[] value)
```


De okända byten från originalresursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

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

