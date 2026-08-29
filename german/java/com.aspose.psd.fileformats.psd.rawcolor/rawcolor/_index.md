---
title: "RawColor"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Raw-Color-Klasse hilft, Farben mit beliebiger Kanalanzahl, beliebigem Farbmodus und beliebiger Bit-Tiefe zu speichern. Bitte beachten Sie, dass einige interne Klassen Probleme beim Konvertieren von RawColor in ihr natives Format haben können, sodass es zuverlässiger ist, das von der API bereitgestellte CMYK-Format zu verwenden, wenn die API Ihnen eine CMYK-Farbe liefert."
type: docs
weight: 11
url: /de/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

Die Raw‑Color‑Klasse hilft, Farben mit beliebiger Kanalanzahl, beliebigem Farbmodus und beliebiger Bit‑Tiefe zu speichern. Bitte beachten Sie, dass einige interne Klassen Probleme beim Konvertieren von RawColor in ihr natives Format haben können, sodass es zuverlässiger ist, das von der API bereitgestellte CMYK‑Format zu verwenden. Außerdem kann es Fälle geben, in denen Raw Color konvertiert werden kann.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | Initialisiert eine neue Instanz der [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)-Klasse. |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | Initialisiert eine neue Instanz der [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)-Klasse aus dem Pixeldatenformat unter Verwendung vordefinierter Farbmodi. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene Objekt diesem Exemplar gleich ist. |
| [getAsInt()](#getAsInt--) | Gibt die Farbe als int zurück, falls sie ermittelt werden kann. |
| [getAsLong()](#getAsLong--) | Gibt die Farbe als long zurück, falls sie ermittelt werden kann. |
| [getBitDepth()](#getBitDepth--) | Gibt die Bit‑Tiefe von Raw Color zurück. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Modus, dem die Farbe folgen soll. |
| [getColorModeName()](#getColorModeName--) | Gibt den Namen des Farbmodus zurück. |
| [getComponents()](#getComponents--) | Gibt die Komponenten der Farbe zurück. |
| [hashCode()](#hashCode--) | Gibt den Hash‑Code des aktuellen Objekts zurück. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Implementiert den Operator ==. |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Implementiert den Operator !=. |
| [setAsInt(int value)](#setAsInt-int-) | Setzt Daten für alle Kanäle aus dem int‑Argument, falls möglich. |
| [setAsLong(long value)](#setAsLong-long-) | Setzt Daten für alle Kanäle aus dem int‑Argument, falls möglich. |
| [setColorMode(short value)](#setColorMode-short-) | Modus, dem die Farbe folgen soll. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


Initialisiert eine neue Instanz der [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | Die benutzerdefinierten Farbkomponenten. |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


Initialisiert eine neue Instanz der [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)-Klasse aus dem Pixeldatenformat unter Verwendung vordefinierter Farbmodi.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Das Pixel‑Datenformat. |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene Objekt diesem Exemplar gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  true  wenn das angegebene Objekt dieser Instanz gleich ist; andernfalls  false .
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


Gibt die Farbe als int zurück, falls sie ermittelt werden kann.

**Returns:**
int – Kanal­daten, gespeichert als int
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


Gibt die Farbe als long zurück, falls sie ermittelt werden kann.

**Returns:**
long – Kanal­daten, gespeichert als Int
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Gibt die Bit‑Tiefe von Raw Color zurück. Zum Beispiel hat eine ARGB‑Farbe mit 8 Bit pro Kanal/Komponente eine Bit‑Tiefe von 32, eine vollständige ARGB‑Farbe mit 16 Bit pro Kanal/Komponente hat eine Bit‑Tiefe von 64. Die Bit‑Tiefe ergibt sich aus der Summe der Bit‑Tiefen der einzelnen Kanäle. Dies ist möglich, wenn verschiedene Kanäle unterschiedliche Bit‑Tiefen besitzen.

**Returns:**
int – Die Summe aller Kanal‑Bit‑Tiefen
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


Modus, dem die Farbe folgen soll.

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


Gibt den Namen des Farbmodus zurück. Der Farbmodusname wird aus den Namen der Kanäle/Komponenten zusammengesetzt.

**Returns:**
java.lang.String – Zeichenkette mit dem Namen des Farbmodus
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


Gibt die Komponenten der Farbe zurück. Jede Komponente ist ein separater Kanal, und wenn Sie ein nicht verbreitetes Farbschema verwenden, ist es besser, mit jedem Kanal einzeln zu arbeiten.

Wert: Die Komponenten der Farbe

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hash‑Code des aktuellen Objekts zurück.

**Returns:**
int – Der Hash‑Code.
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


Implementiert den Operator ==.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Das erste RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Der zweite RawColor. |

**Returns:**
boolean - Das Ergebnis des Operators.
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


Implementiert den Operator !=.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Das erste RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Der zweite RawColor. |

**Returns:**
boolean - Das Ergebnis des Operators.
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


Setzt Daten für alle Kanäle aus dem int‑Argument, falls möglich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der int-Wert, der Komponentendaten enthält |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


Setzt Daten für alle Kanäle aus dem int‑Argument, falls möglich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Der int-Wert, der Komponentendaten enthält |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Modus, dem die Farbe folgen soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

