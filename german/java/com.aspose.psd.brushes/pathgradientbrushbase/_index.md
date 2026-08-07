---
title: "PathGradientBrushBase"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt einen Pinsel mit Basis-Pfadverlauf-Funktionalität dar."
type: docs
weight: 15
url: /de/java/com.aspose.psd.brushes/pathgradientbrushbase/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public abstract class PathGradientBrushBase extends TransformBrush
```

Stellt einen  Brush  mit Basis-Pfad-Verlaufsfunktionalität dar.

Hinweis: Beim Erstellen der  PathGradientBrushBase  Klasse sollte sie mit mindestens 2 Punkten initialisiert werden. Der erzeugte interne Pfad ist stets eine geschlossene Figur, wobei der letzte Punkt mit dem ersten verbunden wird. Diese Form wird mit diesem  PathGradientBrushBase  gefüllt. Die GDI+-Implementierung wirft einen  OutOfMemoryError , wenn leere Arrays oder Punktesätze mit identischen Koordinaten übergeben werden. Die  PathGradientBrushBase  wirft eine Ausnahme, wenn das Punktarray weniger als 2 Punkte enthält; in diesem Fall wird eine  ArgumentException  statt einer  OutOfMemoryError  ausgelöst, wenn das Punktarray unzulässig ist. Der Mittelpunkt wird standardmäßig als Schwerpunkt der übergebenen Punkte berechnet. Ein Benutzer kann diesen Punkt später ändern. Die Fokus‑Skala ist standardmäßig ein leerer Punkt (0,0).
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [deepClone()](#deepClone--) | Erstellt einen neuen Deep‑Clone des aktuellen  Pinsel . |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCenterPoint()](#getCenterPoint--) | Liest oder setzt den Mittelpunkt des Pfadverlaufs. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getFocusScales()](#getFocusScales--) | Liest den Fokuspunkt für den Verlaufabfall. |
| [getGraphicsPath()](#getGraphicsPath--) | Liest den Grafikpfad, auf dem dieser Pinsel aufgebaut ist. |
| [getOpacity()](#getOpacity--) | Liefert die Deckkraft des Pinsels. |
| [getPathPoints()](#getPathPoints--) | Liest die Pfadpunkte, auf denen dieser Pinsel aufgebaut ist. |
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
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | Liest oder setzt den Mittelpunkt des Pfadverlaufs. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | Liest oder setzt den Fokuspunkt für den Verlaufabfall. |
| [setOpacity(float value)](#setOpacity-float-) | Setzt die Deckkraft des Pinsels. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Liest oder setzt eine Kopie von  Aspose.Imaging.Matrix , die eine lokale geometrische Transformation für diesen  TransformBrush  definiert. |
| [setWrapMode(int value)](#setWrapMode-int-) | Liest oder setzt eine  Aspose.Imaging.WrapMode  Aufzählung, die den Wrap-Modus für diesen  TransformBrush  angibt. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Legt die Deckkraft des Pinsels fest. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Deckkraftwert des Pinsels. |

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

