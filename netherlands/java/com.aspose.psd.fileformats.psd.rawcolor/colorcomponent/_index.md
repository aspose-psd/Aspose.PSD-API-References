---
title: "ColorComponent"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Kleurcomponent is een abstractie over Kanaalwaarde en Kanaalwaarde."
type: docs
weight: 10
url: /nl/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

Kleurcomponent is een abstractie over Channel Value en Channel Value. Elke kleur bestaat uit een array van ColorComponent
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | Initialiseert een nieuw exemplaar van de [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Haalt de bitdiepte van Color Component/Channel op |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Haalt de beschrijving van Color Component op |
| [getFullName()](#getFullName--) | Haalt de volledige naam van kleurcomponent op met naam en door spaties gescheiden beschrijving |
| [getName()](#getName--) | Haalt de naam van kleurcomponent op. |
| [getPermittedFullNames()](#getPermittedFullNames--) | Haalt de toegestane volledige namen op. |
| [getValue()](#getValue--) | Haalt de waarde op of stelt deze in. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | Haalt de waarde op of stelt deze in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


Initialiseert een nieuw exemplaar van de [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) klasse. Controleer alstublieft

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitDepth | byte | De bitsdiepte. |
| fullName | java.lang.String | De volledige naam. |

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
public final byte getBitDepth()
```


Haalt de bitdiepte van Color Component/Channel op

Waarde: De bitdiepte.

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


Haalt de beschrijving van Color Component op

Waarde: De beschrijving.

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


Haalt de volledige naam van kleurcomponent op met naam en door spaties gescheiden beschrijving

Waarde: De volledige naam.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


Haalt de naam van kleurcomponent op.

Waarde: De naam.

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


Haalt de toegestane volledige namen op.

Waarde: De toegestane volledige namen.

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


Haalt de waarde op of stelt deze in. Let op, als u probeert een waarde in te stellen die groter is dan wat mogelijk is opgeslagen in de huidige bitdiepte, krijgt u een uitzondering

Waarde: De waarde.

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


Haalt de waarde op of stelt deze in. Let op, als u probeert een waarde in te stellen die groter is dan wat mogelijk is opgeslagen in de huidige bitdiepte, krijgt u een uitzondering

Waarde: De waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

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

