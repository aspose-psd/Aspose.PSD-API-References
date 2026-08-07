---
title: "PathGradientBrush"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Kapselt ein Aspose.Imaging.Brush-Objekt mit einem Farbverlauf."
type: docs
weight: 14
url: /de/java/com.aspose.psd.brushes/pathgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Kapselt ein  Aspose.Imaging.Brush  Objekt mit einem Farbverlauf. Diese Klasse kann nicht abgeleitet werden.

Die Mittelpunktfarbe ist standardmäßig weiß. Ein Benutzer kann diesen Wert jederzeit später ändern.

Das Array der Umgebungsfarben wird standardmäßig mit einem einzelnen Element, das die weiße Farbe enthält, initialisiert. Die Umgebungsfarben können später geändert werden, jedoch ist mindestens ein einzelnes Element erforderlich, wenn die Umgebungsfarben festgelegt werden.

Siehe das Blend für weitere Details zur Initialisierung.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.psd.PointF---) | Initialisiert eine neue Instanz der Klasse PathGradientBrush mit den angegebenen Punkten. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.PointF---int-) | Initialisiert eine neue Instanz der Klasse PathGradientBrush mit den angegebenen Punkten und dem Wrap-Modus. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.psd.Point---) | Initialisiert eine neue Instanz der Klasse PathGradientBrush mit den angegebenen Punkten. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.Point---int-) | Initialisiert eine neue Instanz der Klasse PathGradientBrush mit den angegebenen Punkten und dem Wrap-Modus. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.psd.GraphicsPath-) | Initialisiert eine neue Instanz der Klasse PathGradientBrush mit dem angegebenen Pfad. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [deepClone()](#deepClone--) | Erstellt einen neuen Deep‑Clone des aktuellen  Pinsel . |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlend()](#getBlend--) | Liest ein  Aspose.Imaging.Blend  ein, das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [getCenterColor()](#getCenterColor--) | Gibt die Farbe im Zentrum des Pfadverlaufs zurück. |
| [getCenterPoint()](#getCenterPoint--) | Liest oder setzt den Mittelpunkt des Pfadverlaufs. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getFocusScales()](#getFocusScales--) | Liest den Fokuspunkt für den Verlaufabfall. |
| [getGraphicsPath()](#getGraphicsPath--) | Liest den Grafikpfad, auf dem dieser Pinsel aufgebaut ist. |
| [getInterpolationColors()](#getInterpolationColors--) | Gibt ein  com.aspose.psd.ColorBlend  zurück, das einen mehrfarbigen linearen Farbverlauf definiert. |
| [getOpacity()](#getOpacity--) | Liefert die Deckkraft des Pinsels. |
| [getPathPoints()](#getPathPoints--) | Liest die Pfadpunkte, auf denen dieser Pinsel aufgebaut ist. |
| [getSurroundColors()](#getSurroundColors--) | Gibt ein Array von Farben zurück, das den Punkten im Pfad entspricht, den dieser PathGradientBrush füllt. |
| [getTransform()](#getTransform--) | Liest oder setzt eine Kopie von  Aspose.Imaging.Matrix , die eine lokale geometrische Transformation für diesen  TransformBrush  definiert. |
| [getWrapMode()](#getWrapMode--) | Liest oder setzt eine  Aspose.Imaging.WrapMode  Aufzählung, die den Wrap-Modus für diesen  TransformBrush  angibt. |
| [hashCode()](#hashCode--) |  |
| [isTransformChanged()](#isTransformChanged--) | Liefert einen Wert, der angibt, ob Transformationen in irgendeiner Weise geändert wurden. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multipliziert die  Aspose.Imaging.Matrix , die die lokale geometrische Transformation dieses  LinearGradientBrush  darstellt, mit der angegebenen  Aspose.Imaging.Matrix , indem die angegebene  Aspose.Imaging.Matrix  vorangestellt wird. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multipliziert die  Aspose.Imaging.Matrix , die die lokale geometrische Transformation dieses  LinearGradientBrush  darstellt, mit der angegebenen  Aspose.Imaging.Matrix  in der angegebenen Reihenfolge. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Setzt die Eigenschaft  TransformBrush.Transform  auf die Identität zurück. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Setzt ein  Aspose.Imaging.Blend , das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Erstellt einen Farbverlauf mit einer Mittelpunktfarbe und einem linearen Falloff zu einer Umgebungsfarbe. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Erstellt einen Farbverlauf mit einer Mittelpunktfarbe und einem linearen Falloff zu jeder Umgebungsfarbe. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.psd.Color-) | Legt die Farbe im Zentrum des Pfadverlaufs fest. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | Liest oder setzt den Mittelpunkt des Pfadverlaufs. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | Liest oder setzt den Fokuspunkt für den Verlaufabfall. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Setzt ein  com.aspose.psd.ColorBlend , das einen mehrfarbigen linearen Farbverlauf definiert. |
| [setOpacity(float value)](#setOpacity-float-) | Setzt die Deckkraft des Pinsels. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Erstellt einen Farbverlaufspinsel, der die Farbe vom Zentrum des Pfads nach außen bis zur Pfadgrenze ändert. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Erstellt einen Farbverlaufspinsel, der die Farbe vom Zentrum des Pfads nach außen bis zur Pfadgrenze ändert. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.psd.Color---) | Legt ein Array von Farben fest, das den Punkten im Pfad entspricht, den dieser PathGradientBrush füllt. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Liest oder setzt eine Kopie von  Aspose.Imaging.Matrix , die eine lokale geometrische Transformation für diesen  TransformBrush  definiert. |
| [setWrapMode(int value)](#setWrapMode-int-) | Liest oder setzt eine  Aspose.Imaging.WrapMode  Aufzählung, die den Wrap-Modus für diesen  TransformBrush  angibt. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.psd.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Initialisiert eine neue Instanz der Klasse PathGradientBrush mit den angegebenen Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Ein Array von  Aspose.Imaging.PointF  Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Initialisiert eine neue Instanz der Klasse PathGradientBrush mit den angegebenen Punkten und dem Wrap-Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Ein Array von  Aspose.Imaging.PointF  Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |
| wrapMode | int | Ein Aspose.Imaging.WrapMode, der angibt, wie mit diesem PathGradientBrush gezeichnete Füllungen gekachelt werden. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.psd.Point---}
```
public PathGradientBrush(Point[] points)
```


Initialisiert eine neue Instanz der Klasse PathGradientBrush mit den angegebenen Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Ein Array von  Aspose.Imaging.Point  Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Initialisiert eine neue Instanz der Klasse PathGradientBrush mit den angegebenen Punkten und dem Wrap-Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Ein Array von  Aspose.Imaging.Point  Strukturen, das die Punkte darstellt, aus denen die Scheitelpunkte des Pfads bestehen. |
| wrapMode | int | Ein Aspose.Imaging.WrapMode, der angibt, wie mit diesem PathGradientBrush gezeichnete Füllungen gekachelt werden. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Initialisiert eine neue Instanz der Klasse PathGradientBrush mit dem angegebenen Pfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Der GraphicsPath, der den von diesem PathGradientBrush gefüllten Bereich definiert. |

### close() {#close--}
```
public void close()
```


Implementiert das Closable-Interface und kann seit JDK 1.7 in der try-with-resources-Anweisung verwendet werden. Diese Methode ruft einfach die dispose-Methode auf.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Erstellt einen neuen Deep‑Clone des aktuellen  Pinsel .

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Gibt die aktuelle Instanz frei.

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Liest ein  Aspose.Imaging.Blend  ein, das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Gibt die Farbe im Zentrum des Pfadverlaufs zurück.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  that represents the color at the center of the path gradient.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Liest oder setzt den Mittelpunkt des Pfadverlaufs.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the center point of the path gradient.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde.

**Returns:**
boolean -  true  wenn freigegeben; andernfalls,  false .
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Liest den Fokuspunkt für den Verlaufabfall.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Liest den Grafikpfad, auf dem dieser Pinsel aufgebaut ist.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Gibt ein  com.aspose.psd.ColorBlend  zurück, das einen mehrfarbigen linearen Farbverlauf definiert.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Liest die Deckkraft des Pinsels. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist.

**Returns:**
float - Der Deckkraftwert des Pinsels.
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Liest die Pfadpunkte, auf denen dieser Pinsel aufgebaut ist.

**Returns:**
com.aspose.psd.PointF[] - Die Pfadpunkte.
### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Gibt ein Array von Farben zurück, das den Punkten im Pfad entspricht, den dieser PathGradientBrush füllt.

**Returns:**
com.aspose.psd.Color[] - Ein Array von com.aspose.psd.Color-Strukturen, das die Farben darstellt, die jedem Punkt im Pfad zugeordnet sind, den dieser PathGradientBrush füllt.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Liest oder setzt eine Kopie von  Aspose.Imaging.Matrix , die eine lokale geometrische Transformation für diesen  TransformBrush  definiert.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Liest oder setzt eine  Aspose.Imaging.WrapMode  Aufzählung, die den Wrap-Modus für diesen  TransformBrush  angibt.

**Returns:**
int - Ein Aspose.Imaging.WrapMode, der angibt, wie mit diesem TransformBrush gezeichnete Füllungen gekachelt werden.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Liest einen Wert, der angibt, ob Transformationen in irgendeiner Weise geändert wurden. Zum Beispiel das Setzen der Transformationsmatrix oder das Aufrufen einer der Methoden, die die Transformationsmatrix verändern. Die Eigenschaft wurde zur Abwärtskompatibilität mit GDI+ eingeführt.

Wert:  True  wenn die Transformation geändert wurde; andernfalls  false .

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multipliziert die  Aspose.Imaging.Matrix , die die lokale geometrische Transformation dieses  LinearGradientBrush  darstellt, mit der angegebenen  Aspose.Imaging.Matrix , indem die angegebene  Aspose.Imaging.Matrix  vorangestellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Die Aspose.Imaging.Matrix, mit der die geometrische Transformation multipliziert wird. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multipliziert die  Aspose.Imaging.Matrix , die die lokale geometrische Transformation dieses  LinearGradientBrush  darstellt, mit der angegebenen  Aspose.Imaging.Matrix  in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Die Aspose.Imaging.Matrix, mit der die geometrische Transformation multipliziert wird. |
| Reihenfolge | int | Ein Aspose.Imaging.MatrixOrder, der angibt, in welcher Reihenfolge die beiden Matrizen multipliziert werden. |

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


Setzt die Eigenschaft  TransformBrush.Transform  auf die Identität zurück.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |
| Reihenfolge | int | Ein Aspose.Imaging.MatrixOrder, der angibt, ob die Rotationsmatrix angehängt oder vorangestellt wird. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungsmatrix der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |
| Reihenfolge | int | Ein  Aspose.Imaging.MatrixOrder , der angibt, ob die Skalierungsmatrix angehängt oder vorangestellt wird. |

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


Setzt ein  Aspose.Imaging.Blend , das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | Ein Aspose.Imaging.Blend, das einen benutzerdefinierten Falloff für den Farbverlauf darstellt. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Erstellt einen Farbverlauf mit einer Mittelpunktfarbe und einem linearen Falloff zu einer Umgebungsfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Zentrum des Pfads bis zur Pfadgrenze die Mittelwertfarbe ihre höchste Intensität hat. Ein Wert von 1 (Standard) legt die höchste Intensität im Zentrum des Pfads fest. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Erstellt einen Farbverlauf mit einer Mittelpunktfarbe und einem linearen Falloff zu jeder Umgebungsfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Zentrum des Pfads bis zur Pfadgrenze die Mittelwertfarbe ihre höchste Intensität hat. Ein Wert von 1 (Standard) legt die höchste Intensität im Zentrum des Pfads fest. |
| Skala | float | Ein Wert von 0 bis 1, der die maximale Intensität der Mittelwertfarbe angibt, die mit der Randfarbe gemischt wird. Ein Wert von 1 bewirkt die höchstmögliche Intensität der Mittelwertfarbe und ist der Standardwert. |

### setCenterColor(Color value) {#setCenterColor-com.aspose.psd.Color-}
```
public void setCenterColor(Color value)
```


Legt die Farbe im Zentrum des Pfadverlaufs fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Ein com.aspose.psd.Color, das die Farbe im Zentrum des Pfadverlaufs darstellt. |

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


Liest oder setzt den Mittelpunkt des Pfadverlaufs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Ein  Aspose.Imaging.PointF , der den Mittelpunkt des Pfadverlaufs darstellt. |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


Liest oder setzt den Fokuspunkt für den Verlaufabfall.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Ein  Aspose.Imaging.PointF  der den Fokuspunkt für den Verlaufabfall darstellt. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Setzt ein  com.aspose.psd.ColorBlend , das einen mehrfarbigen linearen Farbverlauf definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | Ein  com.aspose.psd.ColorBlend , der einen mehrfarbigen linearen Verlauf definiert. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Legt die Deckkraft des Pinsels fest. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Deckkraftwert des Pinsels. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Erstellt einen Farbverlaufspinsel, der die Farbe vom Zentrum des Pfads nach außen bis zur Pfadgrenze ändert. Der Übergang von einer Farbe zur nächsten basiert auf einer glockenförmigen Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Zentrum des Pfads bis zur Pfadgrenze die Mittelwertfarbe ihre höchste Intensität hat. Ein Wert von 1 (Standard) legt die höchste Intensität im Zentrum des Pfads fest. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Erstellt einen Farbverlaufspinsel, der die Farbe vom Zentrum des Pfads nach außen bis zur Pfadgrenze ändert. Der Übergang von einer Farbe zur nächsten basiert auf einer glockenförmigen Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der angibt, wo entlang eines beliebigen Radius vom Zentrum des Pfads bis zur Pfadgrenze die Mittelwertfarbe ihre höchste Intensität hat. Ein Wert von 1 (Standard) legt die höchste Intensität im Zentrum des Pfads fest. |
| Skala | float | Ein Wert von 0 bis 1, der die maximale Intensität der Mittelwertfarbe angibt, die mit der Randfarbe gemischt wird. Ein Wert von 1 bewirkt die höchstmögliche Intensität der Mittelwertfarbe und ist der Standardwert. |

### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.psd.Color---}
```
public void setSurroundColors(Color[] value)
```


Legt ein Array von Farben fest, das den Punkten im Pfad entspricht, den dieser PathGradientBrush füllt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Ein Array von com.aspose.psd.Color-Strukturen, das die Farben darstellt, die jedem Punkt im Pfad zugeordnet sind, den dieser PathGradientBrush füllt. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Liest oder setzt eine Kopie von  Aspose.Imaging.Matrix , die eine lokale geometrische Transformation für diesen  TransformBrush  definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Liest oder setzt eine  Aspose.Imaging.WrapMode  Aufzählung, die den Wrap-Modus für diesen  TransformBrush  angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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


Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran.

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

