---
title: "ColorComponent"
second_title: "Aspose.PSD för Java API-referens"
description: "Färgkomponent är en abstraktion över kanalvärde och kanalvärde."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

Färkomponent är en abstraktion över Channel Value och Channel Value. Alla färger är sammansatta av en array av ColorComponent
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | Initierar en ny instans av klassen [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Hämtar bitdjupet för Color Component/Channel |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Hämtar beskrivningen av Color Component |
| [getFullName()](#getFullName--) | Hämtar det fullständiga namnet på färgkomponenten med namn och mellanslagsseparerad beskrivning |
| [getName()](#getName--) | Hämtar namnet på färgkomponenten. |
| [getPermittedFullNames()](#getPermittedFullNames--) | Hämtar de tillåtna fullständiga namnen. |
| [getValue()](#getValue--) | Hämtar eller anger värdet. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | Hämtar eller anger värdet. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


Initierar en ny instans av klassen [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). Vänligen kontrollera

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitDepth | byte | Bitdjupet. |
| fullName | java.lang.String | Det fullständiga namnet. |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Hämtar bitdjupet för Color Component/Channel

Värde: Bitdjupet.

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Hämtar beskrivningen av Color Component

Värde: Beskrivningen.

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


Hämtar det fullständiga namnet på färgkomponenten med namn och mellanslagsseparerad beskrivning

Värde: Det fullständiga namnet.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


Hämtar namnet på färgkomponenten.

Värde: Namnet.

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


Hämtar de tillåtna fullständiga namnen.

Värde: De tillåtna fullständiga namnen.

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


Hämtar eller anger värdet. Observera att om du försöker sätta ett värde som är större än vad som kan lagras i det aktuella bitdjupet, får du ett undantag

Värde: Värdet.

**Returns:**
long
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




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


Hämtar eller anger värdet. Observera att om du försöker sätta ett värde som är större än vad som kan lagras i det aktuella bitdjupet, får du ett undantag

Värde: Värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

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

