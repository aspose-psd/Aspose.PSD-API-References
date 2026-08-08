---
title: "RawColor"
second_title: "Aspose.PSD för Java API-referens"
description: "Raw Color Class hjälper till att lagra färger med valfritt antal kanaler, valfritt färgläge och valfri bitdjup. Observera att vissa interna klasser kan ha problem med att konvertera RawColor till dess ursprungsformat, så om API:et tillhandahåller en CMYK‑färg är det mer pålitligt att använda det angivna formatet."
type: docs
weight: 11
url: /sv/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

Raw Color Class hjälper till att lagra färger med valfritt antal kanaler, valfritt färgläge och valfri bitdjup. Observera att vissa interna klasser kan ha problem med att konvertera RawColor till dess ursprungsformat, så om API:et tillhandahåller en CMYK‑färg är det mer pålitligt att använda det angivna formatet. Dessutom kan det finnas vissa fall då Raw Color kan konverteras.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | Initierar en ny instans av klassen [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor). |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | Initierar en ny instans av klassen [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) från pixeldataformat med fördefinierade färglägen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna objektet är lika med denna instans. |
| [getAsInt()](#getAsInt--) | Hämtar färgen som int om det är möjligt att hämta den. |
| [getAsLong()](#getAsLong--) | Hämtar färgen som long om det är möjligt att hämta den. |
| [getBitDepth()](#getBitDepth--) | Hämtar bitdjupet för Raw Color. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Läge för färgen att följa. |
| [getColorModeName()](#getColorModeName--) | Hämtar namnet på färgläget. |
| [getComponents()](#getComponents--) | Hämtar färgkomponenterna. |
| [hashCode()](#hashCode--) | Hämta hashkod för det aktuella objektet. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Implementerar operatorn ==. |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Implementerar operatorn !=. |
| [setAsInt(int value)](#setAsInt-int-) | Ställer in data till alla kanaler från int-argumentet om det är möjligt |
| [setAsLong(long value)](#setAsLong-long-) | Ställer in data till alla kanaler från int-argumentet om det är möjligt |
| [setColorMode(short value)](#setColorMode-short-) | Läge för färgen att följa. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


Initierar en ny instans av klassen [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | De anpassade färgkomponenterna. |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


Initierar en ny instans av klassen [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) från pixeldataformat med fördefinierade färglägen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Pixeldataformatet. |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna objektet är lika med denna instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att jämföra med den här instansen. |

**Returns:**
boolean -  true  om det angivna objektet är lika med den här instansen; annars,  false .
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


Hämtar färgen som int om det är möjligt att hämta den.

**Returns:**
int - Kanaldata lagrad i Int
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


Hämtar färgen som long om det är möjligt att hämta den.

**Returns:**
long - Kanaldata lagrad i Int
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Hämtar bitdjupet för Raw Color. Till exempel för ARGB-färg med 8 bitar per kanal/komponent är det 32. Bitdjupet för full ARGB-färg med 16 bitar per kanal/komponent är 64. Bitdjupet ackumuleras från summan av kanalernas bitdjup. Det är möjligt om olika kanaler har olika bitdjup.

**Returns:**
int - Summan av alla kanalers bitdjup
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


Läge för färgen att följa.

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


Hämtar namnet på färgläget. Färglägesnamnet ackumuleras från kanalernas/komponenternas namn

**Returns:**
java.lang.String - Sträng med färglägesnamnet
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


Hämtar färgkomponenterna. Varje komponent är en separat kanal, och om du använder ett mindre vanligt färgschema är det bättre att arbeta med varje kanal separat

Värde: Färgkomponenterna

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkod för det aktuella objektet.

**Returns:**
int - Hashkoden.
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


Implementerar operatorn ==.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Den första RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Den andra RawColor. |

**Returns:**
boolean - Resultatet av operatorn.
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


Implementerar operatorn !=.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Den första RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Den andra RawColor. |

**Returns:**
boolean - Resultatet av operatorn.
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


Ställer in data till alla kanaler från int-argumentet om det är möjligt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Int-värdet som innehåller komponentdata |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


Ställer in data till alla kanaler från int-argumentet om det är möjligt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Int-värdet som innehåller komponentdata |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Läge för färgen att följa.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

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

