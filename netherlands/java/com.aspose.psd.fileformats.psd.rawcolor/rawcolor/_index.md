---
title: "RawColor"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De Raw Color‑klasse helpt bij het opslaan van kleuren met elk aantal kanalen, elke kleurmodus en elke bitdiepte. Houd er rekening mee dat sommige interne klassen problemen kunnen hebben met het converteren van RawColor naar het native formaat, dus als de API een CMYK‑kleur levert, is het betrouwbaarder om het geleverde formaat te gebruiken."
type: docs
weight: 11
url: /nl/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

De Raw Color‑klasse helpt bij het opslaan van kleuren met elk aantal kanalen, elke kleurmodus en elke bitdiepte. Houd er rekening mee dat sommige interne klassen problemen kunnen hebben met het converteren van RawColor naar het native formaat, dus als de API een CMYK‑kleur levert, is het betrouwbaarder om het geleverde formaat te gebruiken. Ook kunnen er gevallen zijn waarin Raw Color kan worden geconverteerd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | Initialiseert een nieuwe instantie van de [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) klasse. |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | Initialiseert een nieuwe instantie van de [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) klasse vanuit pixelgegevensformaat met behulp van vooraf gedefinieerde kleurmodi. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of het opgegeven Object gelijk is aan deze instantie. |
| [getAsInt()](#getAsInt--) | Haalt de kleur op als int, indien mogelijk. |
| [getAsLong()](#getAsLong--) | Haalt de kleur op als long, indien mogelijk. |
| [getBitDepth()](#getBitDepth--) | Haalt de bitdiepte van Raw Color op. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Modus die de kleur moet volgen. |
| [getColorModeName()](#getColorModeName--) | Haalt de naam van de kleurmodus op. |
| [getComponents()](#getComponents--) | Haalt de componenten van de kleur op. |
| [hashCode()](#hashCode--) | Haalt de hashcode van het huidige object op. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Implementeert de operator ==. |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Implementeert de operator !=. |
| [setAsInt(int value)](#setAsInt-int-) | Stelt gegevens in voor alle kanalen vanuit een int‑argument, indien mogelijk. |
| [setAsLong(long value)](#setAsLong-long-) | Stelt gegevens in voor alle kanalen vanuit een int‑argument, indien mogelijk. |
| [setColorMode(short value)](#setColorMode-short-) | Modus die de kleur moet volgen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


Initialiseert een nieuwe instantie van de [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | De aangepaste kleurcomponenten. |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


Initialiseert een nieuwe instantie van de [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) klasse vanuit pixelgegevensformaat met behulp van vooraf gedefinieerde kleurmodi.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Het pixelgegevensformaat. |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of het opgegeven Object gelijk is aan deze instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te vergelijken met deze instantie. |

**Returns:**
boolean - true als het opgegeven Object gelijk is aan deze instantie; anders false.
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


Haalt de kleur op als int, indien mogelijk.

**Returns:**
int - Kanaalgegevens opgeslagen in Int
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


Haalt de kleur op als long, indien mogelijk.

**Returns:**
long - Kanaalgegevens opgeslagen in Int
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Haalt de bitdiepte van Raw Color op. Bijvoorbeeld voor ARGB-kleur met 8 bits per kanaal/component is 32 Bit Depth van volledige ARGB-kleur met 16 bits per kanaal/component is 64. Bitdiepte wordt opgeteld uit de som van de bitdieptes van de kanalen. Het is mogelijk dat verschillende kanalen verschillende bitdieptes hebben.

**Returns:**
int - De som van alle kanaalbitdieptes
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


Modus die de kleur moet volgen.

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


Haalt de naam van de kleurmodus op. Kleurmodusnaam opgebouwd uit namen van kanalen/componenten

**Returns:**
java.lang.String - String met de naam van de kleurmodus
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


Haalt de componenten van de kleur op. Elke component is een afzonderlijk kanaal, en als u een minder gangbaar kleurenschema gebruikt, is het beter om met elk kanaal afzonderlijk te werken.

Waarde: De componenten van de kleur

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


Haalt de hashcode van het huidige object op.

**Returns:**
int - De hashcode.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(RawColor left, RawColor right) {#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Equality(RawColor left, RawColor right)
```


Implementeert de operator ==.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | De eerste RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | De tweede RawColor. |

**Returns:**
boolean - Het resultaat van de operator.
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


Implementeert de operator !=.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | De eerste RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | De tweede RawColor. |

**Returns:**
boolean - Het resultaat van de operator.
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


Stelt gegevens in voor alle kanalen vanuit een int‑argument, indien mogelijk.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De int-waarde die componentgegevens bevat |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


Stelt gegevens in voor alle kanalen vanuit een int‑argument, indien mogelijk.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long | De int-waarde die componentgegevens bevat |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Modus die de kleur moet volgen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

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

