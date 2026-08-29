---
title: "TextureBrush"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Jede Eigenschaft der Aspose.Imaging.Brushes.TextureBrush‑Klasse ist ein Aspose.Imaging.Brush‑Objekt, das ein Bild verwendet, um das Innere einer Form zu füllen."
type: docs
weight: 18
url: /de/java/com.aspose.psd.brushes/texturebrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

Jede Eigenschaft der  Aspose.Imaging.Brushes.TextureBrush  Klasse ist ein  Aspose.Imaging.Brush  Objekt, das ein Bild verwendet, um das Innere einer Form zu füllen. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.psd.Image-) | Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild verwendet. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.psd.Image-int-) | Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild und den Wrap‑Modus verwendet. |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-) | Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild, den Wrap‑Modus und das Begrenzungsrechteck verwendet. |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-) | Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild, den Wrap‑Modus und das Begrenzungsrechteck verwendet. |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet. |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-) | Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet. |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet. |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-) | Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [deepClone()](#deepClone--) | Erstellt einen neuen Deep‑Clone des aktuellen  Pinsel . |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getImage()](#getImage--) | Liest das  com.aspose.psd.Image  Objekt, das mit diesem  com.aspose.psd.brushes.TextureBrush  Objekt verknüpft ist. |
| [getImageAttributes()](#getImageAttributes--) | Liest die  ImageAttributes , die mit diesem  TextureBrush  verknüpft sind. |
| [getImageRectangle()](#getImageRectangle--) | Ruft das  Rectangle  ab, das mit diesem  TextureBrush  verknüpft ist. |
| [getOpacity()](#getOpacity--) | Liefert die Deckkraft des Pinsels. |
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
| [setOpacity(float value)](#setOpacity-float-) | Setzt die Deckkraft des Pinsels. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Liest oder setzt eine Kopie von  Aspose.Imaging.Matrix , die eine lokale geometrische Transformation für diesen  TransformBrush  definiert. |
| [setWrapMode(int value)](#setWrapMode-int-) | Liest oder setzt eine  Aspose.Imaging.WrapMode  Aufzählung, die den Wrap-Modus für diesen  TransformBrush  angibt. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureBrush(Image image) {#TextureBrush-com.aspose.psd.Image-}
```
public TextureBrush(Image image)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das  Aspose.Imaging.Image  Objekt, mit dem dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt Innenflächen füllt. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.psd.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild und den Wrap‑Modus verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das  Aspose.Imaging.Image  Objekt, mit dem dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt Innenflächen füllt. |
| wrapMode | int | Eine  Aspose.Imaging.WrapMode  Aufzählung, die angibt, wie dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt gekachelt wird. |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild, den Wrap‑Modus und das Begrenzungsrechteck verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das  Aspose.Imaging.Image  Objekt, mit dem dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt Innenflächen füllt. |
| wrapMode | int | Eine  Aspose.Imaging.WrapMode  Aufzählung, die angibt, wie dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt gekachelt wird. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Eine  Aspose.Imaging.RectangleF  Struktur, die das Begrenzungsrechteck für dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt darstellt. |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild, den Wrap‑Modus und das Begrenzungsrechteck verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das  Aspose.Imaging.Image  Objekt, mit dem dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt Innenflächen füllt. |
| wrapMode | int | Eine  Aspose.Imaging.WrapMode  Aufzählung, die angibt, wie dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt gekachelt wird. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Eine  Aspose.Imaging.Rectangle  Struktur, die das Begrenzungsrechteck für dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt darstellt. |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das  Aspose.Imaging.Image  Objekt, mit dem dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt Innenflächen füllt. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Eine  Aspose.Imaging.RectangleF  Struktur, die das Begrenzungsrechteck für dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt darstellt. |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das  Aspose.Imaging.Image  Objekt, mit dem dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt Innenflächen füllt. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Eine  Aspose.Imaging.RectangleF  Struktur, die das Begrenzungsrechteck für dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt darstellt. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Ein com.aspose.psd.ImageAttributes-Objekt, das zusätzliche Informationen über das Bild enthält, das von diesem Aspose.Imaging.Brushes.TextureBrush-Objekt verwendet wird. |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild und das Begrenzungsrechteck verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das  Aspose.Imaging.Image  Objekt, mit dem dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt Innenflächen füllt. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Eine  Aspose.Imaging.Rectangle  Struktur, die das Begrenzungsrechteck für dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt darstellt. |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Brushes.TextureBrush  Klasse, die das angegebene Bild, das Begrenzungsrechteck und die Bildeigenschaften verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das  Aspose.Imaging.Image  Objekt, mit dem dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt Innenflächen füllt. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Eine  Aspose.Imaging.Rectangle  Struktur, die das Begrenzungsrechteck für dieses  Aspose.Imaging.Brushes.TextureBrush  Objekt darstellt. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Ein com.aspose.psd.ImageAttributes-Objekt, das zusätzliche Informationen über das Bild enthält, das von diesem Aspose.Imaging.Brushes.TextureBrush-Objekt verwendet wird. |

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
### getImage() {#getImage--}
```
public Image getImage()
```


Liest das  com.aspose.psd.Image  Objekt, das mit diesem  com.aspose.psd.brushes.TextureBrush  Objekt verknüpft ist.

Wert: Ein com.aspose.psd.Image-Objekt, das das Bild darstellt, mit dem dieses com.aspose.psd.brushes.TextureBrush-Objekt Formen füllt.

**Returns:**
[Image](../../com.aspose.psd/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


Liest die  ImageAttributes , die mit diesem  TextureBrush  verknüpft sind.

Wert: Die ImageAttributes.

**Returns:**
[ImageAttributes](../../com.aspose.psd/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


Ruft das  Rectangle  ab, das mit diesem  TextureBrush  verknüpft ist.

Wert: Das Rectangle.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Liest die Deckkraft des Pinsels. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist.

**Returns:**
float - Der Deckkraftwert des Pinsels.
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

