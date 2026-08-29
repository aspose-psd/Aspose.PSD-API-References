---
title: "CustomLineCap"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Kapselt eine benutzerdefinierte Linienendkappe."
type: docs
weight: 34
url: /de/java/com.aspose.psd/customlinecap/
---

**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Kapselt eine benutzerdefinierte Linienendkappe.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-) | Initialisiert eine neue Instanz der  CustomLineCap  Klasse mit der angegebenen Kontur und Füllung. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-) | Initialisiert eine neue Instanz der  CustomLineCap  Klasse aus der angegebenen vorhandenen  LineCap  Aufzählung mit der angegebenen Kontur und Füllung. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-) | Initialisiert eine neue Instanz der  CustomLineCap  Klasse aus der angegebenen vorhandenen  LineCap  Aufzählung mit der angegebenen Kontur, Füllung und Einrückung. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseCap()](#getBaseCap--) | Liest die  LineCap  Aufzählung, auf der diese  CustomLineCap  basiert. |
| [getBaseInset()](#getBaseInset--) | Liest den Abstand zwischen der Kappe und der Linie. |
| [getClass()](#getClass--) |  |
| [getFillPath()](#getFillPath--) | Liest das Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Liest die Kappen, die zum Starten und Beenden von Linien verwendet werden, die diese benutzerdefinierte Kappe bilden. |
| [getStrokeJoin()](#getStrokeJoin--) | Liest die  LineJoin  Aufzählung, die bestimmt, wie Linien, die dieses  CustomLineCap  Objekt bilden, verbunden werden. |
| [getStrokePath()](#getStrokePath--) | Liest das Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |
| [getWidthScale()](#getWidthScale--) | Liest den Betrag, um den dieses  CustomLineCap  Klassenobjekt in Bezug auf die Breite des  System.Drawing.Pen  Objekts skaliert wird. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaseCap(int value)](#setBaseCap-int-) | Setzt die  LineCap  Aufzählung, auf der diese  CustomLineCap  basiert. |
| [setBaseInset(float value)](#setBaseInset-float-) | Setzt den Abstand zwischen der Kappe und der Linie. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.psd.GraphicsPath-) | Setzt das Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Setzt die Kappen, die zum Starten und Beenden von Linien verwendet werden, die diese benutzerdefinierte Kappe bilden. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Setzt die  LineJoin  Aufzählung, die bestimmt, wie Linien, die dieses  CustomLineCap  Objekt bilden, verbunden werden. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.psd.GraphicsPath-) | Setzt das Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |
| [setWidthScale(float value)](#setWidthScale-float-) | Legt den Betrag fest, um den dieses  CustomLineCap  Klassenobjekt in Bezug auf die Breite des  System.Drawing.Pen  Objekts skaliert wird. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Initialisiert eine neue Instanz der  CustomLineCap  Klasse mit der angegebenen Kontur und Füllung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Ein  GraphicsPath  Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Ein  GraphicsPath  Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Initialisiert eine neue Instanz der  CustomLineCap  Klasse aus der angegebenen vorhandenen  LineCap  Aufzählung mit der angegebenen Kontur und Füllung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Ein  GraphicsPath  Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Ein  GraphicsPath  Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |
| baseCap | int | Die Linienkappe, aus der die benutzerdefinierte Kappe erstellt wird. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Initialisiert eine neue Instanz der  CustomLineCap  Klasse aus der angegebenen vorhandenen  LineCap  Aufzählung mit der angegebenen Kontur, Füllung und Einrückung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Ein  GraphicsPath  Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Ein  GraphicsPath  Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |
| baseCap | int | Die Linienkappe, aus der die benutzerdefinierte Kappe erstellt wird. |
| baseInset | float | Der Abstand zwischen der Kappe und der Linie. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Liest die  LineCap  Aufzählung, auf der diese  CustomLineCap  basiert.

**Returns:**
int - Die  LineCap  Aufzählung, auf der dieses  CustomLineCap  basiert.
### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Liest den Abstand zwischen der Kappe und der Linie.

**Returns:**
float - Der Abstand zwischen dem Anfang der Kappe und dem Ende der Linie.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Liest das Objekt, das die Füllung für die benutzerdefinierte Kappe definiert.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the fill for the custom cap.
### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Liest die Kappen, die zum Starten und Beenden von Linien verwendet werden, die diese benutzerdefinierte Kappe bilden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startCap | int[] | Die  LineCap  Aufzählung, die am Anfang einer Linie innerhalb dieser Kappe verwendet wird. |
| endCap | int[] | Die  LineCap  Aufzählung, die am Ende einer Linie innerhalb dieser Kappe verwendet wird. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Liest die  LineJoin  Aufzählung, die bestimmt, wie Linien, die dieses  CustomLineCap  Objekt bilden, verbunden werden.

**Returns:**
int - Die  LineJoin  Aufzählung, die dieses  CustomLineCap  Objekt zum Verbinden von Linien verwendet.
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Liest das Objekt, das die Kontur der benutzerdefinierten Kappe definiert.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the outline of the custom cap.
### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Liest den Betrag, um den dieses  CustomLineCap  Klassenobjekt in Bezug auf die Breite des  System.Drawing.Pen  Objekts skaliert wird.

**Returns:**
float - Der Betrag, um den die Kappe skaliert wird.
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




### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Setzt die  LineCap  Aufzählung, auf der diese  CustomLineCap  basiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die  LineCap  Aufzählung, auf der dieses  CustomLineCap  basiert. |

### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Setzt den Abstand zwischen der Kappe und der Linie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Abstand zwischen dem Anfang der Kappe und dem Ende der Linie. |

### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.psd.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Setzt das Objekt, das die Füllung für die benutzerdefinierte Kappe definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | Das Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Setzt die Kappen, die zum Starten und Beenden von Linien verwendet werden, die diese benutzerdefinierte Kappe bilden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startCap | int | Die  LineCap  Aufzählung, die am Anfang einer Linie innerhalb dieser Kappe verwendet wird. |
| endCap | int | Die  LineCap  Aufzählung, die am Ende einer Linie innerhalb dieser Kappe verwendet wird. |

### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Setzt die  LineJoin  Aufzählung, die bestimmt, wie Linien, die dieses  CustomLineCap  Objekt bilden, verbunden werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die  LineJoin  Aufzählung, die dieses  CustomLineCap  Objekt zum Verbinden von Linien verwendet. |

### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.psd.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Setzt das Objekt, das die Kontur der benutzerdefinierten Kappe definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | Das Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |

### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Legt den Betrag fest, um den dieses  CustomLineCap  Klassenobjekt in Bezug auf die Breite des  System.Drawing.Pen  Objekts skaliert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Betrag, um den die Kappe skaliert wird. |

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

