---
title: "Size"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt die Größe dar."
type: docs
weight: 98
url: /de/java/com.aspose.psd/size/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Stellt die Größe dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.psd.Point-) | Initialisiert eine neue Instanz der  Aspose.Imaging.Size  Struktur aus dem angegebenen  Aspose.Imaging.Point . |
| [Size(int width, int height)](#Size-int-int-) | Initialisiert eine neue Instanz der  Aspose.Imaging.Size  Struktur aus den angegebenen Abmessungen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Size that)](#CloneTo-com.aspose.psd.Size-) |  |
| [add(Size size1, Size size2)](#add-com.aspose.psd.Size-com.aspose.psd.Size-) | Addiert die Breite und Höhe einer  Aspose.Imaging.Size  Struktur zur Breite und Höhe einer anderen  Aspose.Imaging.Size  Struktur. |
| [ceiling(SizeF size)](#ceiling-com.aspose.psd.SizeF-) | Konvertiert die angegebene Aspose.Imaging.SizeF-Struktur in eine Aspose.Imaging.Size-Struktur, indem die Werte der Aspose.Imaging.Size-Struktur auf die nächsthöheren Ganzzahlen gerundet werden. |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob das angegebene Objekt ein Aspose.Imaging.Size mit denselben Abmessungen wie dieses Aspose.Imaging.Size ist. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Gibt eine neue Instanz der Aspose.Imaging.Size-Struktur zurück, deren Aspose.Imaging.Size.Width- und Aspose.Imaging.Size.Height-Werte auf Null gesetzt sind. |
| [getHeight()](#getHeight--) | Liest oder setzt die vertikale Komponente dieses Aspose.Imaging.Size. |
| [getWidth()](#getWidth--) | Liest oder setzt die horizontale Komponente dieses Aspose.Imaging.Size. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Aspose.Imaging.Size-Struktur zurück. |
| [isEmpty()](#isEmpty--) | Gibt einen Wert zurück, der angibt, ob dieses Aspose.Imaging.Size Breite und Höhe von 0 hat. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-) | Addiert die Breite und Höhe einer  Aspose.Imaging.Size  Struktur zur Breite und Höhe einer anderen  Aspose.Imaging.Size  Struktur. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-) | Prüft, ob zwei Aspose.Imaging.Size-Strukturen gleich sind. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-) | Prüft, ob zwei Aspose.Imaging.Size-Strukturen unterschiedlich sind. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-) | Subtrahiert die Breite und Höhe einer Aspose.Imaging.Size-Struktur von der Breite und Höhe einer anderen Aspose.Imaging.Size-Struktur. |
| [round(SizeF size)](#round-com.aspose.psd.SizeF-) | Konvertiert die angegebene Aspose.Imaging.SizeF-Struktur in eine Aspose.Imaging.Size-Struktur, indem die Werte der Aspose.Imaging.SizeF-Struktur auf die nächstgelegenen Ganzzahlen gerundet werden. |
| [setHeight(int value)](#setHeight-int-) | Liest oder setzt die vertikale Komponente dieses Aspose.Imaging.Size. |
| [setWidth(int value)](#setWidth-int-) | Liest oder setzt die horizontale Komponente dieses Aspose.Imaging.Size. |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.psd.Size-com.aspose.psd.Size-) | Subtrahiert die Breite und Höhe einer Aspose.Imaging.Size-Struktur von der Breite und Höhe einer anderen Aspose.Imaging.Size-Struktur. |
| [toString()](#toString--) | Erstellt eine menschenlesbare Zeichenkette, die dieses Aspose.Imaging.Size darstellt. |
| [to_Point(Size size)](#to-Point-com.aspose.psd.Size-) | Konvertiert das angegebene Aspose.Imaging.Size in ein Aspose.Imaging.Point. |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.psd.Size-) | Konvertiert das angegebene Aspose.Imaging.Size in ein Aspose.Imaging.SizeF. |
| [truncate(SizeF size)](#truncate-com.aspose.psd.SizeF-) | Konvertiert die angegebene Aspose.Imaging.SizeF-Struktur in eine Aspose.Imaging.Size-Struktur, indem die Werte der Aspose.Imaging.SizeF-Struktur auf die nächstniedrigeren Ganzzahlen abgeschnitten werden. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.psd.Point-}
```
public Size(Point point)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Size  Struktur aus dem angegebenen  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Der Aspose.Imaging.Point, von dem aus dieses Aspose.Imaging.Size initialisiert wird. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Size  Struktur aus den angegebenen Abmessungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breitenkomponente des neuen Aspose.Imaging.Size. |
| Höhe | int | Die Höhenkomponente des neuen Aspose.Imaging.Size. |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.psd/size)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Size that) {#CloneTo-com.aspose.psd.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [Size](../../com.aspose.psd/size) |  |

### add(Size size1, Size size2) {#add-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size add(Size size1, Size size2)
```


Addiert die Breite und Höhe einer  Aspose.Imaging.Size  Struktur zur Breite und Höhe einer anderen  Aspose.Imaging.Size  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Der erste Aspose.Imaging.Size, der addiert werden soll. |
| size2 | [Size](../../com.aspose.psd/size) | Der zweite Aspose.Imaging.Size, der addiert werden soll. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.psd.SizeF-}
```
public static Size ceiling(SizeF size)
```


Konvertiert die angegebene Aspose.Imaging.SizeF-Struktur in eine Aspose.Imaging.Size-Struktur, indem die Werte der Aspose.Imaging.Size-Struktur auf die nächsthöheren Ganzzahlen gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Die Aspose.Imaging.SizeF-Struktur, die konvertiert werden soll. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Prüft, ob das angegebene Objekt ein Aspose.Imaging.Size mit denselben Abmessungen wie dieses Aspose.Imaging.Size ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das  System.Object  zum Testen. |

**Returns:**
boolean – True, wenn obj ein Aspose.Imaging.Size ist und dieselbe Breite und Höhe wie dieses Aspose.Imaging.Size hat; andernfalls false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Gibt eine neue Instanz der Aspose.Imaging.Size-Struktur zurück, deren Aspose.Imaging.Size.Width- und Aspose.Imaging.Size.Height-Werte auf Null gesetzt sind.

**Returns:**
[Size](../../com.aspose.psd/size)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Liest oder setzt die vertikale Komponente dieses Aspose.Imaging.Size.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Liest oder setzt die horizontale Komponente dieses Aspose.Imaging.Size.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Aspose.Imaging.Size-Struktur zurück.

**Returns:**
int – Ein ganzzahliger Wert, der einen Hashwert für diese Aspose.Imaging.Size-Struktur angibt.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gibt einen Wert zurück, der angibt, ob dieses Aspose.Imaging.Size Breite und Höhe von 0 hat.

**Returns:**
boolean
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.psd/size) |  |
| obj2 | [Size](../../com.aspose.psd/size) |  |

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




### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Addiert die Breite und Höhe einer  Aspose.Imaging.Size  Struktur zur Breite und Höhe einer anderen  Aspose.Imaging.Size  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Der erste Aspose.Imaging.Size, der addiert werden soll. |
| size2 | [Size](../../com.aspose.psd/size) | Der zweite Aspose.Imaging.Size, der addiert werden soll. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


Prüft, ob zwei Aspose.Imaging.Size-Strukturen gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Die Aspose.Imaging.Size-Struktur auf der linken Seite des Gleichheitsoperators. |
| size2 | [Size](../../com.aspose.psd/size) | Die Aspose.Imaging.Size-Struktur auf der rechten Seite des Gleichheitsoperators. |

**Returns:**
boolesch - Wahr, wenn  size1  und  size2  gleiche Breite und Höhe haben; andernfalls falsch.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


Prüft, ob zwei Aspose.Imaging.Size-Strukturen unterschiedlich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Die  Aspose.Imaging.Size  Struktur links vom Ungleichheitsoperator. |
| size2 | [Size](../../com.aspose.psd/size) | Die  Aspose.Imaging.Size  Struktur rechts vom Ungleichheitsoperator. |

**Returns:**
boolesch - Wahr, wenn  size1  und  size2  sich entweder in der Breite oder Höhe unterscheiden; falsch, wenn  size1  und  size2  gleich sind.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Subtrahiert die Breite und Höhe einer Aspose.Imaging.Size-Struktur von der Breite und Höhe einer anderen Aspose.Imaging.Size-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Die  Aspose.Imaging.Size  Struktur auf der linken Seite des Subtraktionsoperators. |
| size2 | [Size](../../com.aspose.psd/size) | Die  Aspose.Imaging.Size  Struktur auf der rechten Seite des Subtraktionsoperators. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the subtraction operation.
### round(SizeF size) {#round-com.aspose.psd.SizeF-}
```
public static Size round(SizeF size)
```


Konvertiert die angegebene Aspose.Imaging.SizeF-Struktur in eine Aspose.Imaging.Size-Struktur, indem die Werte der Aspose.Imaging.SizeF-Struktur auf die nächstgelegenen Ganzzahlen gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Die Aspose.Imaging.SizeF-Struktur, die konvertiert werden soll. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Liest oder setzt die vertikale Komponente dieses Aspose.Imaging.Size.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Liest oder setzt die horizontale Komponente dieses Aspose.Imaging.Size.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### subtract(Size size1, Size size2) {#subtract-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Subtrahiert die Breite und Höhe einer Aspose.Imaging.Size-Struktur von der Breite und Höhe einer anderen Aspose.Imaging.Size-Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Die  Aspose.Imaging.Size  Struktur auf der linken Seite des Subtraktionsoperators. |
| size2 | [Size](../../com.aspose.psd/size) | Die  Aspose.Imaging.Size  Struktur auf der rechten Seite des Subtraktionsoperators. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that is a result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Erstellt eine menschenlesbare Zeichenkette, die dieses Aspose.Imaging.Size darstellt.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses  Aspose.Imaging.Size  darstellt.
### to_Point(Size size) {#to-Point-com.aspose.psd.Size-}
```
public static Point to_Point(Size size)
```


Konvertiert das angegebene Aspose.Imaging.Size in ein Aspose.Imaging.Point.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Das  Aspose.Imaging.Size  zum Konvertieren. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  structure to which this operator converts.
### to_SizeF(Size size) {#to-SizeF-com.aspose.psd.Size-}
```
public static SizeF to_SizeF(Size size)
```


Konvertiert das angegebene Aspose.Imaging.Size in ein Aspose.Imaging.SizeF.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Das  Aspose.Imaging.Size  zum Konvertieren. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The  Aspose.Imaging.SizeF  structure to which this operator converts.
### truncate(SizeF size) {#truncate-com.aspose.psd.SizeF-}
```
public static Size truncate(SizeF size)
```


Konvertiert die angegebene Aspose.Imaging.SizeF-Struktur in eine Aspose.Imaging.Size-Struktur, indem die Werte der Aspose.Imaging.SizeF-Struktur auf die nächstniedrigeren Ganzzahlen abgeschnitten werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Die Aspose.Imaging.SizeF-Struktur, die konvertiert werden soll. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
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

