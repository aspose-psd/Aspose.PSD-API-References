---
title: "Region"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Beschreibt das Innere einer Grafikform, die aus Rechtecken und Pfaden besteht."
type: docs
weight: 90
url: /de/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

Beschreibt das Innere einer Grafikform, die aus Rechtecken und Pfaden besteht. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Region()](#Region--) | Initialisiert ein neues  T:Aspose.Imaging.Region . |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | Initialisiert ein neues  T:Aspose.Imaging.Region  aus der angegebenen  T:Aspose.Imaging.RectangleF  Struktur. |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | Initialisiert ein neues  T:Aspose.Imaging.Region  aus der angegebenen  T:Aspose.Imaging.Rectangle  Struktur. |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | Initialisiert ein neues  T:Aspose.Imaging.Region  mit dem angegebenen  T:Aspose.Imaging.GraphicsPath . |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | Aktualisiert dieses  com.aspose.psd.Region  so, dass es den Teil des angegebenen  com.aspose.psd.GraphicsPath  enthält, der nicht mit diesem  com.aspose.psd.region  überschneidet. |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | Aktualisiert dieses  com.aspose.psd.Region  so, dass es den Teil der angegebenen  com.aspose.psd.Rectangle  Struktur enthält, der nicht mit diesem  com.aspose.psd.region  überschneidet . |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | Aktualisiert dieses  com.aspose.psd.Region  so, dass es den Teil der angegebenen  com.aspose.psd.RectangleF  Struktur enthält, der nicht mit diesem  com.aspose.psd.region  überschneidet . |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | Aktualisiert dieses  com.aspose.psd.Region  so, dass es den Teil des angegebenen  com.aspose.psd.Region  enthält, der nicht mit diesem  com.aspose.psd.region  überschneidet . |
| [deepClone()](#deepClone--) | Erstellt eine exakte Tiefenkopie dieses  com.aspose.psd.region . |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | Aktualisiert dieses  com.aspose.psd.Region  so, dass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen  com.aspose.psd.graphicsPath  überschneidet . |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | Aktualisiert dieses  com.aspose.psd.Region  so, dass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen  com.aspose.psd.Rectangle  Struktur überschneidet . |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | Aktualisiert dieses  com.aspose.psd.Region  so, dass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen  com.aspose.psd.RectangleF  Struktur überschneidet . |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | Aktualisiert dieses  com.aspose.psd.Region  so, dass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen  com.aspose.psd.region  überschneidet . |
| [getActions_internalized()](#getActions-internalized--) | Liest die Region-Aktionen . |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | Aktualisiert dieses  com.aspose.psd.Region  zur Schnittmenge mit dem angegebenen  com.aspose.psd.graphicsPath . |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Aktualisiert dieses  com.aspose.psd.Region  zur Schnittmenge mit der angegebenen  com.aspose.psd.Rectangle  Struktur . |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Aktualisiert dieses  com.aspose.psd.Region  zur Schnittmenge mit der angegebenen  com.aspose.psd.RectangleF  Struktur . |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | Aktualisiert dieses  com.aspose.psd.Region  zur Schnittmenge mit dem angegebenen  com.aspose.psd.region . |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | Prüft, ob dieses  com.aspose.psd.Region  ein leeres Inneres auf der angegebenen Zeichenfläche hat . |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | Prüft, ob das angegebene  com.aspose.psd.Region  identisch mit diesem  com.aspose.psd.Region  auf der angegebenen Zeichenfläche ist . |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | Prüft, ob dieses  com.aspose.psd.Region  ein unendliches Inneres auf der angegebenen Zeichenfläche hat . |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Prüft, ob die angegebene  com.aspose.psd.Point  Struktur in diesem  com.aspose.psd.region  enthalten ist . |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Prüft, ob die angegebene  com.aspose.psd.Point  Struktur in diesem  com.aspose.psd.Region  enthalten ist, wenn sie mit dem angegebenen  com.aspose.psd.graphics  gezeichnet wird . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Prüft, ob die angegebene  com.aspose.psd.PointF  Struktur in diesem  com.aspose.psd.region  enthalten ist . |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Prüft, ob die angegebene  com.aspose.psd.PointF  Struktur in diesem  com.aspose.psd.Region  enthalten ist, wenn sie mit dem angegebenen  com.aspose.psd.graphics  gezeichnet wird . |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | Prüft, ob irgendein Teil der angegebenen  com.aspose.psd.Rectangle  Struktur in diesem  com.aspose.psd.region  enthalten ist . |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | Prüft, ob irgendein Teil der angegebenen  com.aspose.psd.Rectangle  Struktur in diesem  com.aspose.psd.Region  enthalten ist, wenn sie mit dem angegebenen  com.aspose.psd.graphics  gezeichnet wird . |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | Prüft, ob irgendein Teil der angegebenen  com.aspose.psd.RectangleF  Struktur in diesem  com.aspose.psd.region  enthalten ist. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | Prüft, ob irgendein Teil der angegebenen  com.aspose.psd.RectangleF  Struktur in diesem  com.aspose.psd.Region  enthalten ist, wenn er mit den angegebenen  com.aspose.psd.graphics  gezeichnet wird. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Prüft, ob der angegebene Punkt in diesem  com.aspose.psd.region  enthalten ist. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | Prüft, ob der angegebene Punkt in diesem  com.aspose.psd.Region  enthalten ist, wenn er mit den angegebenen  com.aspose.psd.graphics  gezeichnet wird. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Prüft, ob irgendein Teil des angegebenen Rechtecks in diesem  com.aspose.psd.region  enthalten ist. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | Prüft, ob irgendein Teil des angegebenen Rechtecks in diesem  com.aspose.psd.Region  enthalten ist, wenn er mit den angegebenen  com.aspose.psd.graphics  gezeichnet wird. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | Prüft, ob der angegebene Punkt in diesem  com.aspose.psd.Region  Objekt enthalten ist, wenn er mit dem angegebenen  com.aspose.psd.Graphics  Objekt gezeichnet wird. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Prüft, ob irgendein Teil des angegebenen Rechtecks in diesem  com.aspose.psd.region  enthalten ist. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | Prüft, ob irgendein Teil des angegebenen Rechtecks in diesem  com.aspose.psd.Region  enthalten ist, wenn er mit den angegebenen  com.aspose.psd.graphics  gezeichnet wird. |
| [makeEmpty()](#makeEmpty--) | Initialisiert dieses  com.aspose.psd.Region  mit einem leeren Inneren. |
| [makeInfinite()](#makeInfinite--) | Initialisiert dieses  com.aspose.psd.Region  Objekt mit einem unendlichen Inneren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | Liest oder setzt die Region bei Änderung. |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | Transformiert dieses  com.aspose.psd.Region  mit der angegebenen  com.aspose.psd.matrix . |
| [translate(float dx, float dy)](#translate-float-float-) | Verschiebt die Koordinaten dieses  com.aspose.psd.Region  um den angegebenen Betrag. |
| [translate(int dx, int dy)](#translate-int-int-) | Verschiebt die Koordinaten dieses  com.aspose.psd.Region  um den angegebenen Betrag. |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung von sich selbst und dem angegebenen  com.aspose.psd.graphicsPath . |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung von sich selbst und der angegebenen  com.aspose.psd.Rectangle  Struktur. |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung von sich selbst und der angegebenen  com.aspose.psd.RectangleF  Struktur. |
| [union(Region region)](#union-com.aspose.psd.Region-) | Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung von sich selbst und dem angegebenen  com.aspose.psd.region . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung minus die Schnittmenge von sich selbst mit dem angegebenen  com.aspose.psd.graphicsPath . |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung minus die Schnittmenge von sich selbst mit der angegebenen  com.aspose.psd.Rectangle  Struktur. |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung minus die Schnittmenge von sich selbst mit der angegebenen  com.aspose.psd.RectangleF  Struktur. |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung minus die Schnittmenge von sich selbst mit dem angegebenen  com.aspose.psd.region . |
### Region() {#Region--}
```
public Region()
```


Initialisiert ein neues  T:Aspose.Imaging.Region .

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


Initialisiert ein neues  T:Aspose.Imaging.Region  aus der angegebenen  T:Aspose.Imaging.RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Eine  T:Aspose.Imaging.RectangleF  Struktur, die das Innere der neuen  T:Aspose.Imaging.Region  definiert. |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


Initialisiert ein neues  T:Aspose.Imaging.Region  aus der angegebenen  T:Aspose.Imaging.Rectangle  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Eine  T:Aspose.Imaging.Rectangle  Struktur, die das Innere der neuen  T:Aspose.Imaging.Region  definiert. |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Initialisiert ein neues  T:Aspose.Imaging.Region  mit dem angegebenen  T:Aspose.Imaging.GraphicsPath .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Ein  T:Aspose.Imaging.GraphicsPath , der die neue  T:Aspose.Imaging.Region  definiert. |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Aktualisiert dieses  com.aspose.psd.Region  so, dass es den Teil des angegebenen  com.aspose.psd.GraphicsPath  enthält, der nicht mit diesem  com.aspose.psd.region  überschneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Der  com.aspose.psd.GraphicsPath  zur Ergänzung dieses  com.aspose.psd.region . |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


Aktualisiert dieses  com.aspose.psd.Region  so, dass es den Teil der angegebenen  com.aspose.psd.Rectangle  Struktur enthält, der nicht mit diesem  com.aspose.psd.region  überschneidet .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Die  com.aspose.psd.Rectangle  Struktur zur Ergänzung dieses  com.aspose.psd.region . |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


Aktualisiert dieses  com.aspose.psd.Region  so, dass es den Teil der angegebenen  com.aspose.psd.RectangleF  Struktur enthält, der nicht mit diesem  com.aspose.psd.region  überschneidet .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Die  com.aspose.psd.RectangleF  Struktur, um diese  com.aspose.psd.region  zu ergänzen. |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


Aktualisiert dieses  com.aspose.psd.Region  so, dass es den Teil des angegebenen  com.aspose.psd.Region  enthält, der nicht mit diesem  com.aspose.psd.region  überschneidet .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Das  com.aspose.psd.Region  Objekt, um dieses  com.aspose.psd.Region  Objekt zu ergänzen. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Erstellt eine exakte Tiefenkopie dieses  com.aspose.psd.region .

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Aktualisiert dieses  com.aspose.psd.Region  so, dass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen  com.aspose.psd.graphicsPath  überschneidet .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Der  com.aspose.psd.GraphicsPath  zum Ausschließen von diesem  com.aspose.psd.region . |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


Aktualisiert dieses  com.aspose.psd.Region  so, dass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen  com.aspose.psd.Rectangle  Struktur überschneidet .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Die  com.aspose.psd.Rectangle  Struktur zum Ausschließen von diesem  com.aspose.psd.region . |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


Aktualisiert dieses  com.aspose.psd.Region  so, dass es nur den Teil seines Inneren enthält, der nicht mit der angegebenen  com.aspose.psd.RectangleF  Struktur überschneidet .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Die  com.aspose.psd.RectangleF  Struktur zum Ausschließen von diesem  com.aspose.psd.region . |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


Aktualisiert dieses  com.aspose.psd.Region  so, dass es nur den Teil seines Inneren enthält, der nicht mit dem angegebenen  com.aspose.psd.region  überschneidet .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Der  com.aspose.psd.Region  zum Ausschließen von diesem  com.aspose.psd.region . |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


Liest die Region-Aktionen .

**Returns:**
com.aspose.internal.RegionAction[] - Die Region-Aktionen.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(GraphicsPath path) {#intersect-com.aspose.psd.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Aktualisiert dieses  com.aspose.psd.Region  zur Schnittmenge mit dem angegebenen  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Der  com.aspose.psd.GraphicsPath  zum Schneiden mit diesem  com.aspose.psd.region . |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Aktualisiert dieses  com.aspose.psd.Region  zur Schnittmenge mit der angegebenen  com.aspose.psd.Rectangle  Struktur .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Die  com.aspose.psd.Rectangle  Struktur zum Schneiden mit diesem  com.aspose.psd.region . |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Aktualisiert dieses  com.aspose.psd.Region  zur Schnittmenge mit der angegebenen  com.aspose.psd.RectangleF  Struktur .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Die  com.aspose.psd.RectangleF  Struktur zum Schneiden mit diesem  com.aspose.psd.region . |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


Aktualisiert dieses  com.aspose.psd.Region  zur Schnittmenge mit dem angegebenen  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Der  com.aspose.psd.Region  zum Schneiden mit diesem  com.aspose.psd.region . |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Prüft, ob dieses  com.aspose.psd.Region  ein leeres Inneres auf der angegebenen Zeichenfläche hat .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Ein  com.aspose.psd.Graphics  , das eine Zeichenfläche darstellt. |

**Returns:**
boolean - wahr, wenn das Innere dieses  com.aspose.psd.Region  leer ist, wenn die mit  g  verbundene Transformation angewendet wird; andernfalls falsch.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Prüft, ob das angegebene  com.aspose.psd.Region  identisch mit diesem  com.aspose.psd.Region  auf der angegebenen Zeichenfläche ist .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Das  com.aspose.psd.Region  zum Testen. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ein  com.aspose.psd.Graphics  , das eine Zeichenfläche darstellt. |

**Returns:**
boolean - Wahr, wenn das Innere der Region identisch mit dem Inneren dieser Region ist, wenn die mit dem Parameter  g  verbundene Transformation angewendet wird; andernfalls falsch.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Prüft, ob dieses  com.aspose.psd.Region  ein unendliches Inneres auf der angegebenen Zeichenfläche hat .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Ein  com.aspose.psd.Graphics  , das eine Zeichenfläche darstellt. |

**Returns:**
boolean - wahr, wenn das Innere dieses  com.aspose.psd.Region  unendlich ist, wenn die mit  g  verbundene Transformation angewendet wird; andernfalls falsch.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Prüft, ob die angegebene  com.aspose.psd.Point  Struktur in diesem  com.aspose.psd.region  enthalten ist .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Die  com.aspose.psd.Point  Struktur zum Testen. |

**Returns:**
boolean - wahr, wenn  point  innerhalb dieses  com.aspose.psd.Region  enthalten ist; andernfalls falsch.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Prüft, ob die angegebene  com.aspose.psd.Point  Struktur in diesem  com.aspose.psd.Region  enthalten ist, wenn sie mit dem angegebenen  com.aspose.psd.graphics  gezeichnet wird .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Die  com.aspose.psd.Point  Struktur zum Testen. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ein  com.aspose.psd.Graphics  , das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - wahr, wenn  point  innerhalb dieses  com.aspose.psd.Region  enthalten ist; andernfalls falsch.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Prüft, ob die angegebene  com.aspose.psd.PointF  Struktur in diesem  com.aspose.psd.region  enthalten ist .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Die  com.aspose.psd.PointF  Struktur zum Testen. |

**Returns:**
boolean - wahr, wenn  point  innerhalb dieses  com.aspose.psd.Region  enthalten ist; andernfalls falsch.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Prüft, ob die angegebene  com.aspose.psd.PointF  Struktur in diesem  com.aspose.psd.Region  enthalten ist, wenn sie mit dem angegebenen  com.aspose.psd.graphics  gezeichnet wird .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Die  com.aspose.psd.PointF  Struktur zum Testen. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ein  com.aspose.psd.Graphics  , das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - wahr, wenn  point  innerhalb dieses  com.aspose.psd.Region  enthalten ist; andernfalls falsch.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Prüft, ob irgendein Teil der angegebenen  com.aspose.psd.Rectangle  Struktur in diesem  com.aspose.psd.region  enthalten ist .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Die  com.aspose.psd.Rectangle  Struktur zum Testen. |

**Returns:**
boolean - Diese Methode gibt wahr zurück, wenn ein beliebiger Teil von  rect  innerhalb dieses  com.aspose.psd.Region  enthalten ist; andernfalls falsch.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Prüft, ob irgendein Teil der angegebenen  com.aspose.psd.Rectangle  Struktur in diesem  com.aspose.psd.Region  enthalten ist, wenn sie mit dem angegebenen  com.aspose.psd.graphics  gezeichnet wird .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Die  com.aspose.psd.Rectangle  Struktur zum Testen. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ein  com.aspose.psd.Graphics  , das einen Grafik-Kontext darstellt. |

**Returns:**
boolean - wahr, wenn ein beliebiger Teil des  rect  innerhalb dieses  com.aspose.psd.Region  enthalten ist; andernfalls falsch.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Prüft, ob irgendein Teil der angegebenen  com.aspose.psd.RectangleF  Struktur in diesem  com.aspose.psd.region  enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Die  com.aspose.psd.RectangleF  Struktur zum Testen. |

**Returns:**
boolean - wahr, wenn ein beliebiger Teil von  rect  innerhalb dieses  com.aspose.psd.Region  enthalten ist; andernfalls falsch.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Prüft, ob irgendein Teil der angegebenen  com.aspose.psd.RectangleF  Struktur in diesem  com.aspose.psd.Region  enthalten ist, wenn er mit den angegebenen  com.aspose.psd.graphics  gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Die  com.aspose.psd.RectangleF  Struktur zum Testen. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ein  com.aspose.psd.Graphics  , das einen Grafik-Kontext darstellt. |

**Returns:**
boolesch - true wenn das Rechteck innerhalb dieser com.aspose.psd.Region enthalten ist; andernfalls false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Prüft, ob der angegebene Punkt in diesem  com.aspose.psd.region  enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |

**Returns:**
boolesch - True wenn der angegebene Punkt innerhalb dieser com.aspose.psd.Region enthalten ist; andernfalls false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Prüft, ob der angegebene Punkt in diesem  com.aspose.psd.Region  enthalten ist, wenn er mit den angegebenen  com.aspose.psd.graphics  gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ein  com.aspose.psd.Graphics  , das einen Grafik-Kontext darstellt. |

**Returns:**
boolesch - True wenn der angegebene Punkt innerhalb dieser com.aspose.psd.Region enthalten ist; andernfalls false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Prüft, ob irgendein Teil des angegebenen Rechtecks in diesem  com.aspose.psd.region  enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x‑Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | float | Die y‑Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| Breite | float | Die Breite des zu testenden Rechtecks. |
| Höhe | float | Die Höhe des zu testenden Rechtecks. |

**Returns:**
boolesch - true wenn irgendein Teil des angegebenen Rechtecks innerhalb dieses com.aspose.psd.Region‑Objekts enthalten ist; andernfalls false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Prüft, ob irgendein Teil des angegebenen Rechtecks in diesem  com.aspose.psd.Region  enthalten ist, wenn er mit den angegebenen  com.aspose.psd.graphics  gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x‑Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | float | Die y‑Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| Breite | float | Die Breite des zu testenden Rechtecks. |
| Höhe | float | Die Höhe des zu testenden Rechtecks. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ein  com.aspose.psd.Graphics  , das einen Grafik-Kontext darstellt. |

**Returns:**
boolesch - true wenn irgendein Teil des angegebenen Rechtecks innerhalb dieser com.aspose.psd.Region enthalten ist; andernfalls false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Prüft, ob der angegebene Punkt in diesem  com.aspose.psd.Region  Objekt enthalten ist, wenn er mit dem angegebenen  com.aspose.psd.Graphics  Objekt gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ein  com.aspose.psd.Graphics  , das einen Grafik-Kontext darstellt. |

**Returns:**
boolesch - true wenn der angegebene Punkt innerhalb dieser com.aspose.psd.Region enthalten ist; andernfalls false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Prüft, ob irgendein Teil des angegebenen Rechtecks in diesem  com.aspose.psd.region  enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | int | Die y‑Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| Breite | int | Die Breite des zu testenden Rechtecks. |
| Höhe | int | Die Höhe des zu testenden Rechtecks. |

**Returns:**
boolesch - true wenn irgendein Teil des angegebenen Rechtecks innerhalb dieser com.aspose.psd.Region enthalten ist; andernfalls false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Prüft, ob irgendein Teil des angegebenen Rechtecks in diesem  com.aspose.psd.Region  enthalten ist, wenn er mit den angegebenen  com.aspose.psd.graphics  gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| y | int | Die y‑Koordinate der oberen linken Ecke des zu testenden Rechtecks. |
| Breite | int | Die Breite des zu testenden Rechtecks. |
| Höhe | int | Die Höhe des zu testenden Rechtecks. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ein  com.aspose.psd.Graphics  , das einen Grafik-Kontext darstellt. |

**Returns:**
boolesch - true wenn irgendein Teil des angegebenen Rechtecks innerhalb dieser com.aspose.psd.Region enthalten ist; andernfalls false.
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Initialisiert dieses  com.aspose.psd.Region  mit einem leeren Inneren.

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Initialisiert dieses  com.aspose.psd.Region  Objekt mit einem unendlichen Inneren.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOnChangeRegion_internalized(ChangeActionList value) {#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-}
```
public final void setOnChangeRegion_internalized(ChangeActionList value)
```


Liest oder setzt die Region bei Änderung.

Wert: Die Region bei Änderung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.internal.ChangeActionList |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix matrix) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix matrix)
```


Transformiert dieses  com.aspose.psd.Region  mit der angegebenen  com.aspose.psd.matrix .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Die com.aspose.psd.Matrix, mit der dieses com.aspose.psd.region transformiert wird. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Verschiebt die Koordinaten dieses  com.aspose.psd.Region  um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Betrag, um den diese com.aspose.psd.Region horizontal verschoben wird. |
| dy | float | Der Betrag, um den diese com.aspose.psd.Region vertikal verschoben wird. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Verschiebt die Koordinaten dieses  com.aspose.psd.Region  um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | int | Der Betrag, um den diese com.aspose.psd.Region horizontal verschoben wird. |
| dy | int | Der Betrag, um den diese com.aspose.psd.Region vertikal verschoben wird. |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung von sich selbst und dem angegebenen  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Der com.aspose.psd.GraphicsPath, der mit diesem com.aspose.psd.region vereinigt wird. |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung von sich selbst und der angegebenen  com.aspose.psd.Rectangle  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Die com.aspose.psd.Rectangle-Struktur, die mit diesem com.aspose.psd.region vereinigt wird. |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung von sich selbst und der angegebenen  com.aspose.psd.RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Die com.aspose.psd.RectangleF-Struktur, die mit diesem com.aspose.psd.region vereinigt wird. |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung von sich selbst und dem angegebenen  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Die com.aspose.psd.Region, die mit diesem com.aspose.psd.region vereinigt wird. |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung minus die Schnittmenge von sich selbst mit dem angegebenen  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Der com.aspose.psd.GraphicsPath, der mit diesem com.aspose.psd.region XOR‑verknüpft wird. |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung minus die Schnittmenge von sich selbst mit der angegebenen  com.aspose.psd.Rectangle  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Die com.aspose.psd.Rectangle-Struktur, die mit diesem com.aspose.psd.region XOR‑verknüpft wird. |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung minus die Schnittmenge von sich selbst mit der angegebenen  com.aspose.psd.RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Die com.aspose.psd.RectangleF-Struktur, die mit diesem com.aspose.psd.region XOR‑verknüpft wird. |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


Aktualisiert dieses  com.aspose.psd.Region  auf die Vereinigung minus die Schnittmenge von sich selbst mit dem angegebenen  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Die com.aspose.psd.Region, die mit diesem com.aspose.psd.region XOR‑verknüpft wird. |

