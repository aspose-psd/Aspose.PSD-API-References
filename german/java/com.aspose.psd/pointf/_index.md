---
title: "PointF"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt ein geordnetes Paar von Gleitkomma‑x‑ und y‑Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert."
type: docs
weight: 83
url: /de/java/com.aspose.psd/pointf/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

Stellt ein geordnetes Paar von Gleitkomma‑x‑ und y‑Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Initialisiert eine neue Instanz der  com.aspose.psd.PointF  Struktur mit den angegebenen Koordinaten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(PointF that)](#CloneTo-com.aspose.psd.PointF-) |  |
| [add(PointF point, Size size)](#add-com.aspose.psd.PointF-com.aspose.psd.Size-) | Verschiebt ein gegebenes  com.aspose.psd.PointF  um die angegebene  com.aspose.psd.Size . |
| [add(PointF point, SizeF size)](#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Verschiebt ein gegebenes  com.aspose.psd.PointF  um ein angegebenes  com.aspose.psd.SizeF . |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt an, ob dieses  com.aspose.psd.PointF  dieselben Koordinaten wie das angegebene  System.Object  enthält. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Ruft eine neue Instanz der  com.aspose.psd.PointF  Struktur ab, deren  com.aspose.psd.PointF.X  und  com.aspose.psd.PointF.Y  Werte auf Null gesetzt sind. |
| [getX()](#getX--) | Ruft die X‑Koordinate dieses  com.aspose.psd.PointF  ab oder legt sie fest. |
| [getY()](#getY--) | Ruft die Y‑Koordinate dieses  com.aspose.psd.PointF  ab oder legt sie fest. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese  com.aspose.psd.PointF  Struktur zurück. |
| [isEmpty()](#isEmpty--) | Ruft einen Wert ab, der angibt, ob dieses  com.aspose.psd.PointF  leer ist. |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-) | Verschiebt ein  com.aspose.psd.PointF  um ein gegebenes  com.aspose.psd.Size . |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Verschiebt das  com.aspose.psd.PointF  um das angegebene  com.aspose.psd.SizeF . |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Vergleicht zwei  com.aspose.psd.PointF  Strukturen. |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Bestimmt, ob die Koordinaten der angegebenen Punkte nicht gleich sind. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-) | Verschiebt ein  com.aspose.psd.PointF  um das Negative einer angegebenen  com.aspose.psd.Size . |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Verschiebt ein  com.aspose.psd.PointF  um das Negative einer angegebenen  com.aspose.psd.SizeF . |
| [setX(float value)](#setX-float-) | Ruft die X‑Koordinate dieses  com.aspose.psd.PointF  ab oder legt sie fest. |
| [setY(float value)](#setY-float-) | Ruft die Y‑Koordinate dieses  com.aspose.psd.PointF  ab oder legt sie fest. |
| [subtract(PointF point, Size size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-) | Verschiebt ein  com.aspose.psd.PointF  um das Negative einer angegebenen Größe. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Verschiebt ein  com.aspose.psd.PointF  um das Negative einer angegebenen Größe. |
| [toString()](#toString--) | Konvertiert dieses  com.aspose.psd.PointF  in eine menschenlesbare Zeichenkette. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Initialisiert eine neue Instanz der  com.aspose.psd.PointF  Struktur mit den angegebenen Koordinaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die horizontale Position des Punktes. |
| y | float | Die vertikale Position des Punktes. |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.psd/pointf)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(PointF that) {#CloneTo-com.aspose.psd.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [PointF](../../com.aspose.psd/pointf) |  |

### add(PointF point, Size size) {#add-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF add(PointF point, Size size)
```


Verschiebt ein gegebenes  com.aspose.psd.PointF  um die angegebene  com.aspose.psd.Size .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Das  com.aspose.psd.PointF  zu verschieben. |
| size | [Size](../../com.aspose.psd/size) | Die  com.aspose.psd.Size  die die Zahlen angibt, die zu den Koordinaten des  point  hinzuzufügen sind. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### add(PointF point, SizeF size) {#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


Verschiebt ein gegebenes  com.aspose.psd.PointF  um ein angegebenes  com.aspose.psd.SizeF .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Das  com.aspose.psd.PointF  zu verschieben. |
| size | [SizeF](../../com.aspose.psd/sizef) | Die  com.aspose.psd.SizeF  die die Zahlen angibt, die zu den Koordinaten des  point  hinzuzufügen sind. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt an, ob dieses  com.aspose.psd.PointF  dieselben Koordinaten wie das angegebene  System.Object  enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das  System.Object  zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn  obj  ein  com.aspose.psd.PointF  ist und dieselben Koordinaten wie dieses  com.aspose.psd.Point  hat.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


Ruft eine neue Instanz der  com.aspose.psd.PointF  Struktur ab, deren  com.aspose.psd.PointF.X  und  com.aspose.psd.PointF.Y  Werte auf Null gesetzt sind.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getX() {#getX--}
```
public float getX()
```


Ruft die X‑Koordinate dieses  com.aspose.psd.PointF  ab oder legt sie fest.

**Returns:**
float
### getY() {#getY--}
```
public float getY()
```


Ruft die Y‑Koordinate dieses  com.aspose.psd.PointF  ab oder legt sie fest.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese  com.aspose.psd.PointF  Struktur zurück.

**Returns:**
int - Ein ganzzahliger Wert, der einen Hashwert für diese  com.aspose.psd.PointF  Struktur angibt.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Ruft einen Wert ab, der angibt, ob dieses  com.aspose.psd.PointF  leer ist.

**Returns:**
boolean - True, wenn sowohl  com.aspose.psd.PointF.X  als auch  com.aspose.psd.PointF.Y  0 sind; andernfalls false.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.psd/pointf) |  |
| obj2 | [PointF](../../com.aspose.psd/pointf) |  |

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




### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


Verschiebt ein  com.aspose.psd.PointF  um ein gegebenes  com.aspose.psd.Size .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Das  com.aspose.psd.PointF  zu verschieben. |
| size | [Size](../../com.aspose.psd/size) | Ein  com.aspose.psd.Size , das das Zahlenpaar angibt, das zu den Koordinaten des  point  hinzuzufügen ist. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - Returns the translated  com.aspose.psd.PointF .
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


Verschiebt das  com.aspose.psd.PointF  um das angegebene  com.aspose.psd.SizeF .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Das  com.aspose.psd.PointF  zu verschieben. |
| size | [SizeF](../../com.aspose.psd/sizef) | Die  com.aspose.psd.SizeF  die die Zahlen angibt, die zu den x- und y-Koordinaten des  point  hinzuzufügen sind. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


Vergleicht zwei  com.aspose.psd.PointF  Strukturen. Das Ergebnis gibt an, ob die Werte der  com.aspose.psd.PointF.X  und  com.aspose.psd.PointF.Y  Eigenschaften der beiden  com.aspose.psd.PointF  Strukturen gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Ein erstes  com.aspose.psd.PointF  zum Vergleichen. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Ein zweites  com.aspose.psd.PointF  zum Vergleichen. |

**Returns:**
boolean - True, wenn die Werte von  com.aspose.psd.PointF.X  und  com.aspose.psd.PointF.Y  der ersten und zweiten  com.aspose.psd.PointF  Strukturen gleich sind; andernfalls false.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


Bestimmt, ob die Koordinaten der angegebenen Punkte nicht gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Ein erstes  com.aspose.psd.PointF  zum Vergleichen. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Ein zweites  com.aspose.psd.PointF  zum Vergleichen. |

**Returns:**
boolean - True, um anzuzeigen, dass die Werte von  com.aspose.psd.PointF.X  und  com.aspose.psd.PointF.Y  von  point1  und  point2  nicht gleich sind; andernfalls false.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


Verschiebt ein  com.aspose.psd.PointF  um das Negative einer angegebenen  com.aspose.psd.Size .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Ein  com.aspose.psd.PointF  zum Verschieben. |
| size | [Size](../../com.aspose.psd/size) | Ein  com.aspose.psd.Size , das die Zahlen angibt, die von den x- und y-Koordinaten des  point  subtrahiert werden sollen. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


Verschiebt ein  com.aspose.psd.PointF  um das Negative einer angegebenen  com.aspose.psd.SizeF .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Das  com.aspose.psd.PointF  zu verschieben. |
| size | [SizeF](../../com.aspose.psd/sizef) | Die  com.aspose.psd.SizeF  die die Zahlen angibt, die von den Koordinaten des  point  subtrahiert werden sollen. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Ruft die X‑Koordinate dieses  com.aspose.psd.PointF  ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Ruft die Y‑Koordinate dieses  com.aspose.psd.PointF  ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### subtract(PointF point, Size size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF subtract(PointF point, Size size)
```


Verschiebt ein  com.aspose.psd.PointF  um das Negative einer angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Das  com.aspose.psd.PointF  zu verschieben. |
| size | [Size](../../com.aspose.psd/size) | Die  com.aspose.psd.Size  die die Zahlen angibt, die von den Koordinaten des  point  subtrahiert werden sollen. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### subtract(PointF point, SizeF size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


Verschiebt ein  com.aspose.psd.PointF  um das Negative einer angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Das  com.aspose.psd.PointF  zu verschieben. |
| size | [SizeF](../../com.aspose.psd/sizef) | Die  com.aspose.psd.SizeF  die die Zahlen angibt, die von den Koordinaten des  point  subtrahiert werden sollen. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### toString() {#toString--}
```
public String toString()
```


Konvertiert dieses  com.aspose.psd.PointF  in eine menschenlesbare Zeichenkette.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses  com.aspose.psd.PointF  darstellt.
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

