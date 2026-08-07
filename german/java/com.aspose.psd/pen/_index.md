---
title: "Pen"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert ein Objekt, das zum Zeichnen von Linien, Kurven und Figuren verwendet wird."
type: docs
weight: 77
url: /de/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Definiert ein Objekt, das zum Zeichnen von Linien, Kurven und Figuren verwendet wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | Initialisiert eine neue Instanz der  Pen  Klasse mit der angegebenen Farbe. |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | Initialisiert eine neue Instanz der  Pen  Klasse mit den angegebenen  Color  und  Pen.Width  Eigenschaften. |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | Initialisiert eine neue Instanz der  Pen  Klasse mit dem angegebenen  Brush . |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | Initialisiert eine neue Instanz der  Pen  Klasse mit dem angegebenen  Brush  und  Pen.Width . |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Liefert die Ausrichtung für diesen  Pen . |
| [getBrush()](#getBrush--) | Liefert den  Brush , der die Attribute dieses  Pen  bestimmt. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Liefert die Farbe dieses  Pen . |
| [getCompoundArray()](#getCompoundArray--) | Liefert ein Array von Werten, das einen zusammengesetzten Stift angibt. |
| [getCustomEndCap()](#getCustomEndCap--) | Liefert eine benutzerdefinierte Cap, die am Ende von mit diesem  Pen  gezeichneten Linien verwendet wird. |
| [getCustomStartCap()](#getCustomStartCap--) | Liefert eine benutzerdefinierte Cap, die am Anfang von mit diesem  Pen  gezeichneten Linien verwendet wird. |
| [getDashCap()](#getDashCap--) | Liefert den Cap-Stil, der am Ende der Striche verwendet wird, aus denen mit diesem  Pen  gezeichnete gestrichelte Linien bestehen. |
| [getDashOffset()](#getDashOffset--) | Liefert den Abstand vom Anfang einer Linie bis zum Beginn eines Strichmusters. |
| [getDashPattern()](#getDashPattern--) | Liefert ein Array von benutzerdefinierten Strichen und Lücken. |
| [getDashStyle()](#getDashStyle--) | Liefert den Stil, der für mit diesem  Pen  gezeichnete gestrichelte Linien verwendet wird. |
| [getEndCap()](#getEndCap--) | Liefert den Cap-Stil, der am Ende von mit diesem  Pen  gezeichneten Linien verwendet wird. |
| [getLineJoin()](#getLineJoin--) | Liefert den Verbindungsstil für die Enden von zwei aufeinanderfolgenden Linien, die mit diesem  Pen  gezeichnet werden. |
| [getMiterLimit()](#getMiterLimit--) | Liefert die Grenze der Dicke der Verbindung an einer Gehrungsecke. |
| [getOpacity()](#getOpacity--) | Gibt die Deckkraft des Objekts zurück. |
| [getPenType()](#getPenType--) | Liefert den Stil der mit diesem  Pen  gezeichneten Linien. |
| [getStartCap()](#getStartCap--) | Liefert den Cap-Stil, der am Anfang von mit diesem  Pen  gezeichneten Linien verwendet wird. |
| [getTransform()](#getTransform--) | Gibt eine Kopie der geometrischen Transformation für diesen  Pen zurück. |
| [getWidth()](#getWidth--) | Gibt die Breite dieses  Pen zurück, in Einheiten des zum Zeichnen verwendeten Graphics-Objekts. |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multipliziert die Transformationsmatrix für diesen  Pen  mit der angegebenen  Matrix . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multipliziert die Transformationsmatrix für diesen  Pen  mit der angegebenen  Matrix  in der angegebenen Reihenfolge. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Setzt die geometrische Transformationsmatrix für diesen  Pen  auf die Identität zurück. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Dreht die lokale geometrische Transformation um den angegebenen Winkel. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Dreht die lokale geometrische Transformation um den angegebenen Winkel in der angegebenen Reihenfolge. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren in der angegebenen Reihenfolge. |
| [setAlignment(int value)](#setAlignment-int-) | Legt die Ausrichtung für diesen  Pen fest. |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | Legt den  Brush  fest, der die Attribute dieses  Pen bestimmt. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Legt die Farbe dieses  Pen fest. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Legt ein Array von Werten fest, das einen zusammengesetzten Pen definiert. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | Legt eine benutzerdefinierte Endkappe fest, die am Ende von mit diesem  Pen gezeichneten Linien verwendet wird. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | Legt eine benutzerdefinierte Anfangskappe fest, die am Anfang von mit diesem  Pen gezeichneten Linien verwendet wird. |
| [setDashCap(int value)](#setDashCap-int-) | Legt den Kappenstil fest, der am Ende der Striche verwendet wird, aus denen gestrichelte Linien mit diesem  Pen bestehen. |
| [setDashOffset(float value)](#setDashOffset-float-) | Legt den Abstand vom Beginn einer Linie bis zum Anfang eines Strichmusters fest. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Legt ein Array benutzerdefinierter Striche und Lücken fest. |
| [setDashStyle(int value)](#setDashStyle-int-) | Legt den Stil fest, der für mit diesem  Pen gezeichnete gestrichelte Linien verwendet wird. |
| [setEndCap(int value)](#setEndCap-int-) | Legt den Kappenstil fest, der am Ende von mit diesem  Pen gezeichneten Linien verwendet wird. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Legt die Werte fest, die den Stil der Kappe bestimmen, die zum Beenden von mit diesem  Pen gezeichneten Linien verwendet wird. |
| [setLineJoin(int value)](#setLineJoin-int-) | Legt den Verbindungsstil für die Enden von zwei aufeinanderfolgenden Linien fest, die mit diesem  Pen gezeichnet werden. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Legt die Grenze der Dicke der Verbindung an einer Gehrungsecke fest. |
| [setOpacity(float value)](#setOpacity-float-) | Setzt die Deckkraft des Objekts. |
| [setStartCap(int value)](#setStartCap-int-) | Legt den Kappenstil fest, der am Anfang von mit diesem  Pen gezeichneten Linien verwendet wird. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Legt eine Kopie der geometrischen Transformation für diesen  Pen fest. |
| [setWidth(float value)](#setWidth-float-) | Legt die Breite dieses Pen fest, in Einheiten des Graphics-Objekts, das zum Zeichnen verwendet wird. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


Initialisiert eine neue Instanz der  Pen  Klasse mit der angegebenen Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Eine Color-Struktur, die die Farbe dieses Pen angibt. |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


Initialisiert eine neue Instanz der  Pen  Klasse mit den angegebenen  Color  und  Pen.Width  Eigenschaften.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Eine Color-Struktur, die die Farbe dieses Pen angibt. |
| Breite | float | Ein Wert, der die Breite dieses Pen angibt. |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


Initialisiert eine neue Instanz der  Pen  Klasse mit dem angegebenen  Brush .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Ein Brush, der die Fülleigenschaften dieses Pen bestimmt. |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


Initialisiert eine neue Instanz der  Pen  Klasse mit dem angegebenen  Brush  und  Pen.Width .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Ein Brush, der die Eigenschaften dieses Pen bestimmt. |
| Breite | float | Die Breite des neuen Pen. |

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Liefert die Ausrichtung für diesen  Pen .

**Returns:**
int – Ein PenAlignment, das die Ausrichtung für diesen Pen darstellt.
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Liefert den  Brush , der die Attribute dieses  Pen  bestimmt.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Liefert die Farbe dieses  Pen .

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Ruft ein Array von Werten ab, das einen zusammengesetzten Stift spezifiziert. Ein zusammengesetzter Stift zeichnet eine zusammengesetzte Linie, die aus parallelen Linien und Zwischenräumen besteht.

**Returns:**
float[] – Ein Array von Gleitkommazahlen, das das Compound-Array spezifiziert. Die Elemente im Array müssen in aufsteigender Reihenfolge liegen, nicht kleiner als 0 und nicht größer als 1 sein.
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Liefert eine benutzerdefinierte Cap, die am Ende von mit diesem  Pen  gezeichneten Linien verwendet wird.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Liefert eine benutzerdefinierte Cap, die am Anfang von mit diesem  Pen  gezeichneten Linien verwendet wird.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Liefert den Cap-Stil, der am Ende der Striche verwendet wird, aus denen mit diesem  Pen  gezeichnete gestrichelte Linien bestehen.

**Returns:**
int – Einer der DashCap-Werte, der den Kappenstil am Anfang und Ende der Striche darstellt, aus denen gestrichelte Linien mit diesem Pen gezeichnet werden.
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Liefert den Abstand vom Anfang einer Linie bis zum Beginn eines Strichmusters.

**Returns:**
float – Der Abstand vom Beginn einer Linie bis zum Anfang eines Strichmusters.
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Liefert ein Array von benutzerdefinierten Strichen und Lücken.

**Returns:**
float[] – Ein Array von Gleitkommazahlen, das die Längen abwechselnder Striche und Lücken in gestrichelten Linien angibt.
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Liefert den Stil, der für mit diesem  Pen  gezeichnete gestrichelte Linien verwendet wird.

**Returns:**
int – Ein DashStyle, der den Stil für mit diesem Pen gezeichnete gestrichelte Linien darstellt.
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Liefert den Cap-Stil, der am Ende von mit diesem  Pen  gezeichneten Linien verwendet wird.

**Returns:**
int – Einer der LineCap-Werte, der den Kappenstil am Ende von mit diesem Pen gezeichneten Linien darstellt.
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Liefert den Verbindungsstil für die Enden von zwei aufeinanderfolgenden Linien, die mit diesem  Pen  gezeichnet werden.

**Returns:**
int – Ein LineJoin, der den Verbindungsstil für die Enden zweier aufeinanderfolgender Linien, die mit diesem Pen gezeichnet werden, darstellt.
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Liefert die Grenze der Dicke der Verbindung an einer Gehrungsecke.

**Returns:**
float – Die Begrenzung der Dicke der Verbindung an einer Gehrungsecke.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Gibt die Deckkraft des Objekts zurück. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass das Objekt vollständig sichtbar ist, ein Wert von 1 bedeutet, dass das Objekt vollständig undurchsichtig ist.

**Returns:**
float - Der Deckkraftwert.
### getPenType() {#getPenType--}
```
public int getPenType()
```


Liefert den Stil der mit diesem  Pen  gezeichneten Linien.

**Returns:**
int – Eine PenType-Aufzählung, die den Stil der mit diesem Pen gezeichneten Linien festlegt.
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Liefert den Cap-Stil, der am Anfang von mit diesem  Pen  gezeichneten Linien verwendet wird.

**Returns:**
int – Einer der LineCap-Werte, der den Kappenstil am Anfang von mit diesem Pen gezeichneten Linien darstellt.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Gibt eine Kopie der geometrischen Transformation für diesen  Pen zurück.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


Gibt die Breite dieses  Pen zurück, in Einheiten des zum Zeichnen verwendeten Graphics-Objekts.

**Returns:**
float – Die Breite dieses Pen.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multipliziert die Transformationsmatrix für diesen  Pen  mit der angegebenen  Matrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Das Matrix-Objekt, mit dem die Transformationsmatrix multipliziert wird. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multipliziert die Transformationsmatrix für diesen  Pen  mit der angegebenen  Matrix  in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Die Matrix, mit der die Transformationsmatrix multipliziert wird. |
| Reihenfolge | int | Die Reihenfolge, in der die Multiplikationsoperation ausgeführt wird. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Setzt die geometrische Transformationsmatrix für diesen  Pen  auf die Identität zurück.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Dreht die lokale geometrische Transformation um den angegebenen Winkel. Diese Methode fügt die Rotation der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Dreht die lokale geometrische Transformation um den angegebenen Winkel in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |
| Reihenfolge | int | Ein  MatrixOrder  der angibt, ob die Rotationsmatrix angehängt oder vorangestellt werden soll. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skaliert die lokale geometrische Transformation um die angegebenen Faktoren. Diese Methode stellt die Skalierungsmatrix vor die Transformation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Faktor, um den die Transformation in x‑Richtung skaliert wird. |
| sy | float | Der Faktor, um den die Transformation in y‑Richtung skaliert wird. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skaliert die lokale geometrische Transformation um die angegebenen Faktoren in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Faktor, um den die Transformation in x‑Richtung skaliert wird. |
| sy | float | Der Faktor, um den die Transformation in y‑Richtung skaliert wird. |
| Reihenfolge | int | Ein  MatrixOrder  der angibt, ob die Skalierungsmatrix angehängt oder vorangestellt werden soll. |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Legt die Ausrichtung für diesen  Pen fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Ein  PenAlignment  der die Ausrichtung für diesen  Pen  darstellt. |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


Legt den  Brush  fest, der die Attribute dieses  Pen bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | Ein  Brush  der die Attribute dieses  Pen  bestimmt. |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Legt die Farbe dieses  Pen fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Eine  Color  Struktur, die die Farbe dieses  Pen  darstellt. |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Legt ein Array von Werten fest, das einen zusammengesetzten Pen definiert. Ein zusammengesetzter Pen zeichnet eine zusammengesetzte Linie, die aus parallelen Linien und Zwischenräumen besteht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float[] | Ein Array von Gleitkommazahlen, das das zusammengesetzte Array angibt. Die Elemente im Array müssen in aufsteigender Reihenfolge sein, nicht kleiner als 0 und nicht größer als 1. |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Legt eine benutzerdefinierte Endkappe fest, die am Ende von mit diesem  Pen gezeichneten Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Ein  CustomLineCap , der die Endkappe darstellt, die bei Linien verwendet wird, die mit diesem  Pen  gezeichnet werden. |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Legt eine benutzerdefinierte Anfangskappe fest, die am Anfang von mit diesem  Pen gezeichneten Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Ein  CustomLineCap , der die Anfangskappe darstellt, die bei Linien verwendet wird, die mit diesem  Pen  gezeichnet werden. |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Legt den Kappenstil fest, der am Ende der Striche verwendet wird, aus denen gestrichelte Linien mit diesem  Pen bestehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Einer der  DashCap  Werte, der den Kappenstil darstellt, der am Anfang und Ende der Striche verwendet wird, aus denen gestrichelte Linien mit diesem  Pen  bestehen. |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Legt den Abstand vom Beginn einer Linie bis zum Anfang eines Strichmusters fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Abstand vom Beginn einer Linie bis zum Anfang eines Strichmusters. |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Legt ein Array benutzerdefinierter Striche und Lücken fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float[] | Ein Array von Gleitkommazahlen, das die Längen von abwechselnden Strichen und Lücken in gestrichelten Linien angibt. |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Legt den Stil fest, der für mit diesem  Pen gezeichnete gestrichelte Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Ein  DashStyle  der den Stil darstellt, der für gestrichelte Linien mit diesem  Pen  verwendet wird. |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Legt den Kappenstil fest, der am Ende von mit diesem  Pen gezeichneten Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Einer der  LineCap  Werte, der den Kappenstil darstellt, der am Ende von Linien verwendet wird, die mit diesem  Pen  gezeichnet werden. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Legt die Werte fest, die den Stil der Kappe bestimmen, die zum Beenden von mit diesem  Pen gezeichneten Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startCap | int | Ein  LineCap , der den Kappenstil darstellt, der am Anfang von Linien verwendet werden soll, die mit diesem  Pen  gezeichnet werden. |
| endCap | int | Ein  LineCap , der den Kappenstil darstellt, der am Ende von Linien verwendet werden soll, die mit diesem  Pen  gezeichnet werden. |
| dashCap | int | Ein  LineCap , der den Kappenstil darstellt, der am Anfang oder Ende von gestrichelten Linien verwendet werden soll, die mit diesem  Pen  gezeichnet werden. |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Legt den Verbindungsstil für die Enden von zwei aufeinanderfolgenden Linien fest, die mit diesem  Pen gezeichnet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Ein  LineJoin , der den Verbindungsstil für die Enden von zwei aufeinanderfolgenden Linien darstellt, die mit diesem  Pen  gezeichnet werden. |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Legt die Grenze der Dicke der Verbindung an einer Gehrungsecke fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Die Grenze der Dicke der Verbindung an einer Gehrungsecke. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Setzt die Deckkraft des Objekts. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass das Objekt vollständig sichtbar ist, ein Wert von 1 bedeutet, dass das Objekt vollständig undurchsichtig ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Deckkraftwert. |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Legt den Kappenstil fest, der am Anfang von mit diesem  Pen gezeichneten Linien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Einer der  LineCap  Werte, der den Kappenstil darstellt, der am Anfang von Linien verwendet wird, die mit diesem  Pen  gezeichnet werden. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Legt eine Kopie der geometrischen Transformation für diesen  Pen fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Eine Kopie der  Matrix , die die geometrische Transformation für diesen  Pen  darstellt. |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Legt die Breite dieses Pen fest, in Einheiten des Graphics-Objekts, das zum Zeichnen verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Die Breite dieses Pen. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Übersetzung der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Wert der Translation in x. |
| dy | float | Der Wert der Translation in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Wert der Translation in x. |
| dy | float | Der Wert der Translation in y. |
| Reihenfolge | int | Die Reihenfolge (voranstellen oder anhängen), in der die Translation angewendet wird. |

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

