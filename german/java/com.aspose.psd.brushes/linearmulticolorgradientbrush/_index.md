---
title: "LinearMulticolorGradientBrush"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt einen Pinsel mit linearem Farbverlauf dar, der durch mehrere Farben und passende Positionen definiert ist."
type: docs
weight: 13
url: /de/java/com.aspose.psd.brushes/linearmulticolorgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearMulticolorGradientBrush extends LinearGradientBrushBase
```

Stellt einen  Pinsel  mit linearem Farbverlauf dar, der durch mehrere Farben und passende Positionen definiert ist. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush--) | Initialisiert eine neue Instanz der  LinearMulticolorGradientBrush  Klasse mit Standardparametern. |
| [LinearMulticolorGradientBrush(Point point1, Point point2)](#LinearMulticolorGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-) | Initialisiert eine neue Instanz der  LinearMulticolorGradientBrush  Klasse mit den angegebenen Punkten. |
| [LinearMulticolorGradientBrush(PointF point1, PointF point2)](#LinearMulticolorGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Initialisiert eine neue Instanz der  LinearMulticolorGradientBrush  Klasse mit den angegebenen Punkten. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-) | Initialisiert eine neue Instanz der  LinearMulticolorGradientBrush  Klasse basierend auf einem Rechteck und einem Orientierungwinkel. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-) | Initialisiert eine neue Instanz der  LinearMulticolorGradientBrush  Klasse basierend auf einem Rechteck und einem Orientierungwinkel. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-boolean-) | Initialisiert eine neue Instanz der  LinearMulticolorGradientBrush  Klasse basierend auf einem Rechteck und einem Orientierungwinkel. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-boolean-) | Initialisiert eine neue Instanz der  LinearMulticolorGradientBrush  Klasse basierend auf einem Rechteck und einem Orientierungwinkel. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [deepClone()](#deepClone--) | Erstellt einen neuen Deep‑Clone des aktuellen  Pinsel . |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Liest den Winkel des Farbverlaufs. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getGammaCorrection()](#getGammaCorrection--) | Liest einen Wert, der angibt, ob die Gammakorrektur für dieses  LinearGradientBrushBase  aktiviert ist. |
| [getInterpolationColors()](#getInterpolationColors--) | Gibt ein  com.aspose.psd.ColorBlend  zurück, das einen mehrfarbigen linearen Farbverlauf definiert. |
| [getOpacity()](#getOpacity--) | Liefert die Deckkraft des Pinsels. |
| [getRectangle()](#getRectangle--) | Liefert einen rechteckigen Bereich, der die Start- und Endpunkte des Farbverlaufs definiert. |
| [getTransform()](#getTransform--) | Liest oder setzt eine Kopie von  Aspose.Imaging.Matrix , die eine lokale geometrische Transformation für diesen  TransformBrush  definiert. |
| [getWrapMode()](#getWrapMode--) | Liest oder setzt eine  Aspose.Imaging.WrapMode  Aufzählung, die den Wrap-Modus für diesen  TransformBrush  angibt. |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | Liefert einen Wert, der angibt, ob  LinearGradientBrushBase.Angle  während Transformationen mit diesem  LinearGradientBrushBase  geändert wird. |
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
| [setAngle(float value)](#setAngle-float-) | Setzt den Winkel des Farbverlaufs. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Setzt einen Wert, der angibt, ob  LinearGradientBrushBase.Angle  während Transformationen mit diesem  LinearGradientBrushBase  geändert wird. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Setzt einen Wert, der angibt, ob die Gammakorrektur für diesen  LinearGradientBrushBase  aktiviert ist. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Setzt ein  com.aspose.psd.ColorBlend , das einen mehrfarbigen linearen Farbverlauf definiert. |
| [setOpacity(float value)](#setOpacity-float-) | Setzt die Deckkraft des Pinsels. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Setzt einen rechteckigen Bereich, der die Start- und Endpunkte des Farbverlaufs definiert. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Liest oder setzt eine Kopie von  Aspose.Imaging.Matrix , die eine lokale geometrische Transformation für diesen  TransformBrush  definiert. |
| [setWrapMode(int value)](#setWrapMode-int-) | Liest oder setzt eine  Aspose.Imaging.WrapMode  Aufzählung, die den Wrap-Modus für diesen  TransformBrush  angibt. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush--}
```
public LinearMulticolorGradientBrush()
```


Initialisiert eine neue Instanz der Klasse  LinearMulticolorGradientBrush  mit Standardparametern. Die Startfarbe ist Schwarz, die Endfarbe ist Weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich bei (0,0) mit der Größe (1,1).

### LinearMulticolorGradientBrush(Point point1, Point point2) {#LinearMulticolorGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public LinearMulticolorGradientBrush(Point point1, Point point2)
```


Initialisiert eine neue Instanz der  LinearMulticolorGradientBrush  Klasse mit den angegebenen Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Eine  Aspose.Imaging.Point  Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [Point](../../com.aspose.psd/point) | Eine  Aspose.Imaging.Point  Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |

### LinearMulticolorGradientBrush(PointF point1, PointF point2) {#LinearMulticolorGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public LinearMulticolorGradientBrush(PointF point1, PointF point2)
```


Initialisiert eine neue Instanz der  LinearMulticolorGradientBrush  Klasse mit den angegebenen Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Eine Aspose.Imaging.PointF Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Eine Aspose.Imaging.PointF Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle)
```


Initialisiert eine neue Instanz der  LinearMulticolorGradientBrush  Klasse basierend auf einem Rechteck und einem Orientierungwinkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Eine Aspose.Imaging.RectangleF Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| Winkel | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle)
```


Initialisiert eine neue Instanz der  LinearMulticolorGradientBrush  Klasse basierend auf einem Rechteck und einem Orientierungwinkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Eine Aspose.Imaging.RectangleF Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| Winkel | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-boolean-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)
```


Initialisiert eine neue Instanz der  LinearMulticolorGradientBrush  Klasse basierend auf einem Rechteck und einem Orientierungwinkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Eine Aspose.Imaging.RectangleF Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| Winkel | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |
| isAngleScalable | boolean | Wenn auf  true  gesetzt, wird der Winkel während Transformationen mit diesem LinearMulticolorGradientBrush geändert. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-boolean-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)
```


Initialisiert eine neue Instanz der  LinearMulticolorGradientBrush  Klasse basierend auf einem Rechteck und einem Orientierungwinkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Eine Aspose.Imaging.RectangleF Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| Winkel | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |
| isAngleScalable | boolean | Wenn auf  true  gesetzt, wird der Winkel während Transformationen mit diesem LinearMulticolorGradientBrush geändert. |

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


Liest den Winkel des Farbverlaufs.

**Returns:**
float - Der Winkel des Farbverlaufs.
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
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Liest einen Wert, der angibt, ob die Gammakorrektur für dieses  LinearGradientBrushBase  aktiviert ist.

**Returns:**
boolean - Der Wert ist true, wenn die Gammakorrektur für dieses LinearGradientBrushBase aktiviert ist; andernfalls false.
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
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Liefert einen rechteckigen Bereich, der die Start- und Endpunkte des Farbverlaufs definiert.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
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
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Liefert einen Wert, der angibt, ob  LinearGradientBrushBase.Angle  während Transformationen mit diesem  LinearGradientBrushBase  geändert wird.

**Returns:**
boolean -  true  wenn  LinearGradientBrushBase.Angle  während Transformationen mit diesem LinearGradientBrushBase  geändert wird; andernfalls  false .
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

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Setzt den Winkel des Farbverlaufs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Gradientwinkel. |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Setzt einen Wert, der angibt, ob  LinearGradientBrushBase.Angle  während Transformationen mit diesem  LinearGradientBrushBase  geändert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true, wenn LinearGradientBrushBase.Angle während Transformationen mit diesem LinearGradientBrushBase geändert wird; andernfalls false. |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Setzt einen Wert, der angibt, ob die Gammakorrektur für diesen  LinearGradientBrushBase  aktiviert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | Der Wert ist true, wenn die Gammakorrektur für diesen LinearGradientBrushBase aktiviert ist; andernfalls false. |

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

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Setzt einen rechteckigen Bereich, der die Start- und Endpunkte des Farbverlaufs definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Eine  com.aspose.psd.RectangleF  Struktur, die die Start- und Endpunkte des Verlaufs angibt. |

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

