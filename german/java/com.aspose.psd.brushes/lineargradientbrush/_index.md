---
title: "LinearGradientBrush"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Kapselt einen Aspose.Imaging.Brush mit einem linearen Farbverlauf."
type: docs
weight: 11
url: /de/java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Kapselt einen  Aspose.Imaging.Brush  mit einem linearen Farbverlauf. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse mit Standardparametern. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse mit den angegebenen Punkten und Farben. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse mit den angegebenen Punkten und Farben. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierung‑Winkel. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierung‑Winkel. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierung‑Winkel. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierung‑Winkel. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [deepClone()](#deepClone--) | Erstellt einen neuen Deep‑Clone des aktuellen  Pinsel . |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Liest den Winkel des Farbverlaufs. |
| [getBlend()](#getBlend--) | Liest ein  Aspose.Imaging.Blend  ein, das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getEndColor()](#getEndColor--) | Liest die Endfarbe des Farbverlaufs. |
| [getGammaCorrection()](#getGammaCorrection--) | Liest einen Wert, der angibt, ob die Gammakorrektur für dieses  LinearGradientBrushBase  aktiviert ist. |
| [getInterpolationColors()](#getInterpolationColors--) | Gibt ein  com.aspose.psd.ColorBlend  zurück, das einen mehrfarbigen linearen Farbverlauf definiert. |
| [getLinearColors()](#getLinearColors--) | Liest die Anfangs‑ und Endfarben des Farbverlaufs. |
| [getOpacity()](#getOpacity--) | Liefert die Deckkraft des Pinsels. |
| [getRectangle()](#getRectangle--) | Liefert einen rechteckigen Bereich, der die Start- und Endpunkte des Farbverlaufs definiert. |
| [getStartColor()](#getStartColor--) | Liest die Anfangsfarbe des Farbverlaufs. |
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
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Setzt ein  Aspose.Imaging.Blend , das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Erstellt einen linearen Farbverlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Erstellt einen linearen Farbverlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden. |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | Setzt die Endfarbe des Farbverlaufs. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Setzt einen Wert, der angibt, ob die Gammakorrektur für diesen  LinearGradientBrushBase  aktiviert ist. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Setzt ein  com.aspose.psd.ColorBlend , das einen mehrfarbigen linearen Farbverlauf definiert. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | Setzt die Anfangs‑ und Endfarben des Farbverlaufs. |
| [setOpacity(float value)](#setOpacity-float-) | Setzt die Deckkraft des Pinsels. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Setzt einen rechteckigen Bereich, der die Start- und Endpunkte des Farbverlaufs definiert. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Erstellt einen Farbverlaufs‑Abfall basierend auf einer glockenförmigen Kurve. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Erstellt einen Farbverlaufs‑Abfall basierend auf einer glockenförmigen Kurve. |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | Setzt die Anfangsfarbe des Farbverlaufs. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Liest oder setzt eine Kopie von  Aspose.Imaging.Matrix , die eine lokale geometrische Transformation für diesen  TransformBrush  definiert. |
| [setWrapMode(int value)](#setWrapMode-int-) | Liest oder setzt eine  Aspose.Imaging.WrapMode  Aufzählung, die den Wrap-Modus für diesen  TransformBrush  angibt. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse mit Standardparametern. Die Anfangsfarbe ist Schwarz, die Endfarbe ist Weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich bei (0,0) mit der Größe (1,1).

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse mit den angegebenen Punkten und Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Eine  Aspose.Imaging.Point  Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [Point](../../com.aspose.psd/point) | Eine  Aspose.Imaging.Point  Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |
| color1 | [Color](../../com.aspose.psd/color) | Eine  com.aspose.psd.Color  Struktur, die die Anfangsfarbe des linearen Farbverlaufs darstellt. |
| color2 | [Color](../../com.aspose.psd/color) | Eine  com.aspose.psd.Color  Struktur, die die Endfarbe des linearen Farbverlaufs darstellt. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse mit den angegebenen Punkten und Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Eine Aspose.Imaging.PointF Struktur, die den Startpunkt des linearen Farbverlaufs darstellt. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Eine Aspose.Imaging.PointF Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |
| color1 | [Color](../../com.aspose.psd/color) | Eine  com.aspose.psd.Color  Struktur, die die Anfangsfarbe des linearen Farbverlaufs darstellt. |
| color2 | [Color](../../com.aspose.psd/color) | Eine  com.aspose.psd.Color  Struktur, die die Endfarbe des linearen Farbverlaufs darstellt. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierung‑Winkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Eine Aspose.Imaging.RectangleF Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | [Color](../../com.aspose.psd/color) | Eine  com.aspose.psd.Color  Struktur, die die Anfangsfarbe für den Farbverlauf darstellt. |
| color2 | [Color](../../com.aspose.psd/color) | Eine  com.aspose.psd.Color  Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| Winkel | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierung‑Winkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Eine Aspose.Imaging.RectangleF Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | [Color](../../com.aspose.psd/color) | Eine  com.aspose.psd.Color  Struktur, die die Anfangsfarbe für den Farbverlauf darstellt. |
| color2 | [Color](../../com.aspose.psd/color) | Eine  com.aspose.psd.Color  Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| Winkel | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierung‑Winkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Eine Aspose.Imaging.RectangleF Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | [Color](../../com.aspose.psd/color) | Eine  com.aspose.psd.Color  Struktur, die die Anfangsfarbe für den Farbverlauf darstellt. |
| color2 | [Color](../../com.aspose.psd/color) | Eine  com.aspose.psd.Color  Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| Winkel | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |
| isAngleScalable | boolean | Wenn auf true gesetzt, wird der Winkel während Transformationen mit diesem LinearGradientBrush geändert. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initialisiert eine neue Instanz der  LinearGradientBrush  Klasse basierend auf einem Rechteck, Anfangs‑ und Endfarben sowie einem Orientierung‑Winkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Eine Aspose.Imaging.RectangleF Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | [Color](../../com.aspose.psd/color) | Eine  com.aspose.psd.Color  Struktur, die die Anfangsfarbe für den Farbverlauf darstellt. |
| color2 | [Color](../../com.aspose.psd/color) | Eine  com.aspose.psd.Color  Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| Winkel | float | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |
| isAngleScalable | boolean | Wenn auf true gesetzt, wird der Winkel während Transformationen mit diesem LinearGradientBrush geändert. |

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Liest ein  Aspose.Imaging.Blend  ein, das Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
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
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Liest die Endfarbe des Farbverlaufs.

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
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
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Liest die Anfangs‑ und Endfarben des Farbverlaufs.

**Returns:**
com.aspose.psd.Color[] - Ein Array von zwei Color-Strukturen, das die Anfangs- und Endfarben des Farbverlaufs darstellt.
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
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Liest die Anfangsfarbe des Farbverlaufs.

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
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


Erstellt einen linearen Farbverlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Verlauf ausschließlich aus der Endfarbe besteht). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Erstellt einen linearen Farbverlauf mit einer Mittel­farbe und einem linearen Abfall zu einer einzelnen Farbe an beiden Enden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Verlauf ausschließlich aus der Endfarbe besteht). |
| Skala | float | Ein Wert von 0 bis 1, der angibt, wie schnell die Farben vom Ausgangsfarbton zum Fokus (Endfarbe) abfallen. |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


Setzt die Endfarbe des Farbverlaufs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Die Endfarbe des Farbverlaufs. |

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

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


Setzt die Anfangs‑ und Endfarben des Farbverlaufs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Ein Array von zwei Color-Strukturen, das die Anfangs- und Endfarben des Farbverlaufs darstellt. |

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

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Erstellt einen Farbverlaufs‑Abfall basierend auf einer glockenförmigen Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem die Anfangs- und Endfarbe zu gleichen Teilen gemischt werden). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Erstellt einen Farbverlaufs‑Abfall basierend auf einer glockenförmigen Kurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Fokus | float | Ein Wert von 0 bis 1, der das Zentrum des Farbverlaufs angibt (der Punkt, an dem der Verlauf ausschließlich aus der Endfarbe besteht). |
| Skala | float | Ein Wert von 0 bis 1, der angibt, wie schnell die Farben vom Fokus abfallen. |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


Setzt die Anfangsfarbe des Farbverlaufs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Die Startfarbe des Farbverlaufs. |

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

