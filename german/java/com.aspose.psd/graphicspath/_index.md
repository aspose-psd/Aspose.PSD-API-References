---
title: "GraphicsPath"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt eine Reihe verbundener Linien und Kurven dar."
type: docs
weight: 50
url: /de/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Stellt eine Reihe verbundener Linien und Kurven dar. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Initialisiert eine neue Instanz der Klasse  GraphicsPath . |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | Initialisiert eine neue Instanz der Klasse  GraphicsPath . |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | Initialisiert eine neue Instanz der Klasse  GraphicsPath . |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Initialisiert eine neue Instanz der Klasse  GraphicsPath . |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | Fügt eine neue Figur hinzu. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | Fügt neue Figuren hinzu. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | Fügt den angegebenen  com.aspose.psd.GraphicsPath  zu diesem Pfad hinzu. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | Fügt den angegebenen  com.aspose.psd.GraphicsPath  zu diesem Pfad hinzu. |
| [deepClone()](#deepClone--) | Führt eine tiefe Kopie dieses Grafikpfads aus. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Konvertiert jede Kurve in diesem Pfad in eine Sequenz verbundener Liniensegmente. |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | Wendet die angegebene Transformation an und konvertiert dann jede Kurve in diesem  com.aspose.psd.GraphicsPath  in eine Sequenz verbundener Liniensegmente. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | Konvertiert jede Kurve in diesem  com.aspose.psd.GraphicsPath  in eine Sequenz verbundener Liniensegmente. |
| [getBounds()](#getBounds--) | Liest oder setzt die Begrenzungen des Objekts. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Liest die Begrenzungen des Objekts. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Liest die Begrenzungen des Objekts. |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | Liefert die Pfadfiguren. |
| [getFillMode()](#getFillMode--) | Liefert eine  com.aspose.psd.FillMode  Aufzählung, die bestimmt, wie die Innenbereiche von Formen in diesem  com.aspose.psd.GraphicsPath  gefüllt werden. |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wenn er mit dem angegebenen  com.aspose.psd.pen  gezeichnet wird. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses com.aspose.psd.GraphicsPath liegt, wenn er mit dem angegebenen com.aspose.psd.Pen gezeichnet und das angegebene com.aspose.psd.graphics verwendet wird. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wenn er mit dem angegebenen  com.aspose.psd.pen  gezeichnet wird. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses com.aspose.psd.GraphicsPath liegt, wenn er mit dem angegebenen com.aspose.psd.Pen gezeichnet und das angegebene com.aspose.psd.graphics verwendet wird. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wenn er mit dem angegebenen  com.aspose.psd.pen  gezeichnet wird. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses com.aspose.psd.GraphicsPath liegt, wenn er mit dem angegebenen com.aspose.psd.Pen gezeichnet und das angegebene com.aspose.psd.graphics verwendet wird. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wenn er mit dem angegebenen  com.aspose.psd.pen  gezeichnet wird. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses com.aspose.psd.GraphicsPath liegt, wenn er mit dem angegebenen com.aspose.psd.Pen gezeichnet und das angegebene com.aspose.psd.graphics verwendet wird. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.graphicsPath liegt. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.graphicsPath liegt. |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.graphicsPath liegt. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.graphicsPath liegt. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.graphicsPath liegt. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.GraphicsPath im sichtbaren Clip-Bereich des angegebenen com.aspose.psd.graphics liegt. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.graphicsPath liegt. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.GraphicsPath liegt, unter Verwendung des angegebenen com.aspose.psd.graphics. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | Entfernt eine Figur. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | Entfernt Figuren. |
| [reset()](#reset--) | Leert den Grafikpfad und setzt den com.aspose.psd.FillMode auf F:com.aspose.psd.fillMode.alternate. |
| [reverse()](#reverse--) | Kehrt die Reihenfolge von Figuren, Formen und Punkten in jeder Form dieses com.aspose.psd.graphicsPath um. |
| [setFillMode(int value)](#setFillMode-int-) | Legt eine com.aspose.psd.FillMode‑Aufzählung fest, die bestimmt, wie die Innenbereiche von Formen in diesem com.aspose.psd.GraphicsPath gefüllt werden. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Wendet die angegebene Transformation auf die Form an. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Wendet eine Warp-Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen com.aspose.psd.graphicsPath an. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | Wendet eine Warp-Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen com.aspose.psd.graphicsPath an. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | Wendet eine Warp-Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen com.aspose.psd.graphicsPath an. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | Wendet eine Warp-Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen com.aspose.psd.graphicsPath an. |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | Fügt dem Pfad eine zusätzliche Kontur hinzu. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | Fügt dem com.aspose.psd.graphicsPath eine zusätzliche Kontur hinzu. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | Ersetzt diesen com.aspose.psd.GraphicsPath durch Kurven, die den Bereich umschließen, der gefüllt wird, wenn dieser Pfad mit dem angegebenen Stift gezeichnet wird. |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Initialisiert eine neue Instanz der Klasse  GraphicsPath .

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Initialisiert eine neue Instanz der Klasse  GraphicsPath .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Die Figuren, von denen initialisiert werden soll. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Initialisiert eine neue Instanz der Klasse  GraphicsPath .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Die Figuren, von denen initialisiert werden soll. |
| fillMode | int | Der Füllmodus. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Initialisiert eine neue Instanz der Klasse  GraphicsPath .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillMode | int | Der Füllmodus. |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


Fügt eine neue Figur hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | Die hinzuzufügende Figur. |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


Fügt neue Figuren hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Die hinzuzufügenden Figuren. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Fügt den angegebenen  com.aspose.psd.GraphicsPath  zu diesem Pfad hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Den hinzuzufügenden com.aspose.psd.GraphicsPath. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Fügt den angegebenen  com.aspose.psd.GraphicsPath  zu diesem Pfad hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Den hinzuzufügenden com.aspose.psd.GraphicsPath. |
| connect | boolean | Ein boolescher Wert, der angibt, ob die erste Figur im hinzugefügten Pfad Teil der letzten Figur in diesem Pfad ist. Der Wert true gibt an, dass die erste Figur im hinzugefügten Pfad Teil der letzten Figur in diesem Pfad ist. Der Wert false gibt an, dass die erste Figur im hinzugefügten Pfad von der letzten Figur in diesem Pfad getrennt ist. |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Führt eine tiefe Kopie dieses Grafikpfads aus.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
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
### flatten() {#flatten--}
```
public void flatten()
```


Konvertiert jede Kurve in diesem Pfad in eine Sequenz verbundener Liniensegmente.

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


Wendet die angegebene Transformation an und konvertiert dann jede Kurve in diesem  com.aspose.psd.GraphicsPath  in eine Sequenz verbundener Liniensegmente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Eine com.aspose.psd.Matrix, mit der dieser com.aspose.psd.GraphicsPath vor dem Flachlegen transformiert wird. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Konvertiert jede Kurve in diesem  com.aspose.psd.GraphicsPath  in eine Sequenz verbundener Liniensegmente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Eine com.aspose.psd.Matrix, mit der dieser com.aspose.psd.GraphicsPath vor dem Flachlegen transformiert wird. |
| flatness | float | Gibt den maximal zulässigen Fehler zwischen der Kurve und ihrer abgeflachten Annäherung an. Der Standardwert ist 0,25. Eine Verringerung des Flatness-Werts erhöht die Anzahl der Liniensegmente in der Annäherung. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Liest oder setzt die Begrenzungen des Objekts.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Liest die Begrenzungen des Objekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Liest die Begrenzungen des Objekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |
| pen | [Pen](../../com.aspose.psd/pen) | Der Stift, der für das Objekt verwendet wird. Dies kann die Größe der Objektbegrenzungen beeinflussen. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Liefert die Pfadfiguren.

**Returns:**
com.aspose.psd.Figure[] – Die Pfadfiguren.
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Liefert eine  com.aspose.psd.FillMode  Aufzählung, die bestimmt, wie die Innenbereiche von Formen in diesem  com.aspose.psd.GraphicsPath  gefüllt werden.

**Returns:**
int - Der Füllmodus. Eine  com.aspose.psd.FillMode  Aufzählung, die angibt, wie die Innenbereiche von Formen in diesem  com.aspose.psd.GraphicsPath  gefüllt werden.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wenn er mit dem angegebenen  com.aspose.psd.pen  gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Ein  com.aspose.psd.Point , der den zu testenden Ort angibt. |
| pen | [Pen](../../com.aspose.psd/pen) | Der  com.aspose.psd.Pen  zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wenn er mit dem angegebenen  com.aspose.psd.Pen  gezeichnet wird; andernfalls false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses com.aspose.psd.GraphicsPath liegt, wenn er mit dem angegebenen com.aspose.psd.Pen gezeichnet und das angegebene com.aspose.psd.graphics verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Ein  com.aspose.psd.Point , der den zu testenden Ort angibt. |
| pen | [Pen](../../com.aspose.psd/pen) | Der  com.aspose.psd.Pen  zum Testen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Das  com.aspose.psd.Graphics , für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wie mit dem angegebenen  com.aspose.psd.Pen  gezeichnet; andernfalls false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wenn er mit dem angegebenen  com.aspose.psd.pen  gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Ein  com.aspose.psd.PointF , der den zu testenden Ort angibt. |
| pen | [Pen](../../com.aspose.psd/pen) | Der  com.aspose.psd.Pen  zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wenn er mit dem angegebenen  com.aspose.psd.Pen  gezeichnet wird; andernfalls false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses com.aspose.psd.GraphicsPath liegt, wenn er mit dem angegebenen com.aspose.psd.Pen gezeichnet und das angegebene com.aspose.psd.graphics verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Ein  com.aspose.psd.PointF , der den zu testenden Ort angibt. |
| pen | [Pen](../../com.aspose.psd/pen) | Der  com.aspose.psd.Pen  zum Testen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Das  com.aspose.psd.Graphics , für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wie mit dem angegebenen  com.aspose.psd.Pen  gezeichnet; andernfalls false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wenn er mit dem angegebenen  com.aspose.psd.pen  gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](../../com.aspose.psd/pen) | Der  com.aspose.psd.Pen  zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wenn er mit dem angegebenen  com.aspose.psd.Pen  gezeichnet wird; andernfalls false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses com.aspose.psd.GraphicsPath liegt, wenn er mit dem angegebenen com.aspose.psd.Pen gezeichnet und das angegebene com.aspose.psd.graphics verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](../../com.aspose.psd/pen) | Der  com.aspose.psd.Pen  zum Testen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Das  com.aspose.psd.Graphics , für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wie mit dem angegebenen  com.aspose.psd.Pen  gezeichnet; andernfalls false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wenn er mit dem angegebenen  com.aspose.psd.pen  gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](../../com.aspose.psd/pen) | Der  com.aspose.psd.Pen  zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wenn er mit dem angegebenen  com.aspose.psd.Pen  gezeichnet wird; andernfalls false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses com.aspose.psd.GraphicsPath liegt, wenn er mit dem angegebenen com.aspose.psd.Pen gezeichnet und das angegebene com.aspose.psd.graphics verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](../../com.aspose.psd/pen) | Der  com.aspose.psd.Pen  zum Testen. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Das  com.aspose.psd.Graphics , für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses  com.aspose.psd.GraphicsPath  liegt, wie mit dem angegebenen  com.aspose.psd.Pen  gezeichnet; andernfalls false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.graphicsPath liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Ein  com.aspose.psd.Point , der den zu testenden Punkt darstellt. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses  com.aspose.psd.GraphicsPath  liegt; andernfalls false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.graphicsPath liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Ein  com.aspose.psd.Point , der den zu testenden Punkt darstellt. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Das  com.aspose.psd.Graphics , für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses  com.aspose.psd.GraphicsPath  liegt; andernfalls false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.graphicsPath liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Ein  com.aspose.psd.PointF , der den zu testenden Punkt darstellt. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses  com.aspose.psd.GraphicsPath  liegt; andernfalls false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.graphicsPath liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Ein  com.aspose.psd.PointF , der den zu testenden Punkt darstellt. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Das  com.aspose.psd.Graphics , für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses Objekts liegt; andernfalls false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.graphicsPath liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses  com.aspose.psd.GraphicsPath  liegt; andernfalls false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.GraphicsPath im sichtbaren Clip-Bereich des angegebenen com.aspose.psd.graphics liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Das  com.aspose.psd.Graphics , für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses  com.aspose.psd.GraphicsPath  liegt; andernfalls false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.graphicsPath liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses  com.aspose.psd.GraphicsPath  liegt; andernfalls false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb dieses com.aspose.psd.GraphicsPath liegt, unter Verwendung des angegebenen com.aspose.psd.graphics.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Das  com.aspose.psd.Graphics , für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses  com.aspose.psd.GraphicsPath  liegt; andernfalls false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFigure(Figure figure) {#removeFigure-com.aspose.psd.Figure-}
```
public void removeFigure(Figure figure)
```


Entfernt eine Figur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | Die zu entfernende Figur. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


Entfernt Figuren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Die zu entfernenden Figuren. |

### reset() {#reset--}
```
public void reset()
```


Leert den Grafikpfad und setzt den com.aspose.psd.FillMode auf F:com.aspose.psd.fillMode.alternate.

### reverse() {#reverse--}
```
public void reverse()
```


Kehrt die Reihenfolge von Figuren, Formen und Punkten in jeder Form dieses com.aspose.psd.graphicsPath um.

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Legt eine com.aspose.psd.FillMode‑Aufzählung fest, die bestimmt, wie die Innenbereiche von Formen in diesem com.aspose.psd.GraphicsPath gefüllt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Füllmodus. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


Wendet die angegebene Transformation auf die Form an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | Die anzuwendende Transformation. |

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

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Wendet eine Warp-Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen com.aspose.psd.graphicsPath an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Ein Array von  com.aspose.psd.PointF  Strukturen, die ein Parallelogramm definieren, zu dem das durch  srcRect  definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Ein  com.aspose.psd.RectangleF , der das Rechteck darstellt, das in das durch  destPoints  definierte Parallelogramm transformiert wird. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Wendet eine Warp-Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen com.aspose.psd.graphicsPath an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Ein Array von  com.aspose.psd.PointF  Strukturen, die ein Parallelogramm definieren, zu dem das durch  srcRect  definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Ein  com.aspose.psd.RectangleF , der das Rechteck darstellt, das in das durch  destPoints  definierte Parallelogramm transformiert wird. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Eine  com.aspose.psd.Matrix , die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Wendet eine Warp-Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen com.aspose.psd.graphicsPath an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Ein Array von  com.aspose.psd.PointF  Strukturen, das ein Parallelogramm definiert, zu dem das durch  srcRect  definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Ein  com.aspose.psd.RectangleF , der das Rechteck darstellt, das in das durch  destPoints  definierte Parallelogramm transformiert wird. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Eine  com.aspose.psd.Matrix , die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |
| Verzerrungsmodus | int | Eine  com.aspose.psd.WarpMode  Aufzählung, die angibt, ob diese Verzerrungsoperation die Perspektiv- oder bilineare Methode verwendet. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Wendet eine Warp-Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen com.aspose.psd.graphicsPath an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Ein Array von  com.aspose.psd.PointF  Strukturen, die ein Parallelogramm definieren, zu dem das durch  srcRect  definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Ein  com.aspose.psd.RectangleF , der das Rechteck darstellt, das in das durch  destPoints  definierte Parallelogramm transformiert wird. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Eine  com.aspose.psd.Matrix , die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |
| Verzerrungsmodus | int | Eine  com.aspose.psd.WarpMode  Aufzählung, die angibt, ob diese Verzerrungsoperation die Perspektiv- oder bilineare Methode verwendet. |
| flatness | float | Ein Wert von 0 bis 1, der angibt, wie flach der resultierende Pfad ist. Weitere Informationen finden Sie in den  com.aspose.psd.GraphicsPath.flatten  Methoden. |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


Fügt dem Pfad eine zusätzliche Kontur hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Ein  com.aspose.psd.Pen , der die Breite zwischen der ursprünglichen Kontur des Pfads und der neuen Kontur, die diese Methode erstellt, angibt. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Fügt dem com.aspose.psd.graphicsPath eine zusätzliche Kontur hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Ein  com.aspose.psd.Pen , der die Breite zwischen der ursprünglichen Kontur des Pfads und der neuen Kontur, die diese Methode erstellt, angibt. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Eine  com.aspose.psd.Matrix , die eine Transformation angibt, die vor dem Verbreitern auf den Pfad angewendet wird. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Ersetzt diesen com.aspose.psd.GraphicsPath durch Kurven, die den Bereich umschließen, der gefüllt wird, wenn dieser Pfad mit dem angegebenen Stift gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Ein  com.aspose.psd.Pen , der die Breite zwischen der ursprünglichen Kontur des Pfads und der neuen Kontur, die diese Methode erstellt, angibt. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Eine  com.aspose.psd.Matrix , die eine Transformation angibt, die vor dem Verbreitern auf den Pfad angewendet wird. |
| flatness | float | Ein Wert, der die Flachheit für Kurven angibt. |

