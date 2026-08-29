---
title: "TextureBrush"
second_title: "Aspose.PSD för Java API-referens"
description: "Varje egenskap i klassen Aspose.Imaging.Brushes.TextureBrush är ett Aspose.Imaging.Brush-objekt som använder en bild för att fylla insidan av en form."
type: docs
weight: 18
url: /sv/java/com.aspose.psd.brushes/texturebrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

Varje egenskap i klassen  Aspose.Imaging.Brushes.TextureBrush  är ett  Aspose.Imaging.Brush  -objekt som använder en bild för att fylla insidan av en form. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.psd.Image-) | Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.psd.Image-int-) | Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden och omslagsläget. |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-) | Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden, omslagsläget och begränsningsrektangeln. |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-) | Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden, omslagsläget och begränsningsrektangeln. |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden och begränsningsrektangeln. |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-) | Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden, den avgränsande rektangeln och bildattributen. |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden och begränsningsrektangeln. |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-) | Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden, den avgränsande rektangeln och bildattributen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [deepClone()](#deepClone--) | Skapar en ny djupklon av den aktuella  Brush . |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getImage()](#getImage--) | Hämtar  com.aspose.psd.Image  objektet som är associerat med detta  com.aspose.psd.brushes.TextureBrush  objekt. |
| [getImageAttributes()](#getImageAttributes--) | Hämtar  ImageAttributes  som är associerad med detta  TextureBrush . |
| [getImageRectangle()](#getImageRectangle--) | Hämtar  Rectangle  som är associerad med detta  TextureBrush . |
| [getOpacity()](#getOpacity--) | Hämtar penselns opacitet. |
| [getTransform()](#getTransform--) | Hämtar eller anger en kopia av  Aspose.Imaging.Matrix  som definierar en lokal geometrisk transformation för detta  TransformBrush . |
| [getWrapMode()](#getWrapMode--) | Hämtar eller anger en  Aspose.Imaging.WrapMode ‑enumeration som indikerar omslagsläget för detta  TransformBrush . |
| [hashCode()](#hashCode--) |  |
| [isTransformChanged()](#isTransformChanged--) | Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multiplicerar  Aspose.Imaging.Matrix  som representerar den lokala geometriska transformationen för detta  LinearGradientBrush  med den angivna  Aspose.Imaging.Matrix  genom att föregå den angivna  Aspose.Imaging.Matrix . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multiplicerar  Aspose.Imaging.Matrix  som representerar den lokala geometriska transformationen för detta  LinearGradientBrush  med den angivna  Aspose.Imaging.Matrix  i den angivna ordningen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Återställer egenskapen  TransformBrush.Transform  till identitet. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rotera den lokala geometriska transformationen med den angivna mängden. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rotera den lokala geometriska transformationen med den angivna mängden i den angivna ordningen. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skalar den lokala geometriska transformationen med de angivna värdena. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen. |
| [setOpacity(float value)](#setOpacity-float-) | Anger penselns opacitet. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Hämtar eller anger en kopia av  Aspose.Imaging.Matrix  som definierar en lokal geometrisk transformation för detta  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Hämtar eller anger en  Aspose.Imaging.WrapMode ‑enumeration som indikerar omslagsläget för detta  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureBrush(Image image) {#TextureBrush-com.aspose.psd.Image-}
```
public TextureBrush(Image image)
```


Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Det  Aspose.Imaging.Image  objektet som detta  Aspose.Imaging.Brushes.TextureBrush  objekt fyller interiörer. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.psd.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden och omslagsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Det  Aspose.Imaging.Image  objektet som detta  Aspose.Imaging.Brushes.TextureBrush  objekt fyller interiörer. |
| wrapMode | int | En  Aspose.Imaging.WrapMode  enumeration som anger hur detta  Aspose.Imaging.Brushes.TextureBrush  objekt upprepas. |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden, omslagsläget och begränsningsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Det  Aspose.Imaging.Image  objektet som detta  Aspose.Imaging.Brushes.TextureBrush  objekt fyller interiörer. |
| wrapMode | int | En  Aspose.Imaging.WrapMode  enumeration som anger hur detta  Aspose.Imaging.Brushes.TextureBrush  objekt upprepas. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | En  Aspose.Imaging.RectangleF  struktur som representerar den avgränsande rektangeln för detta  Aspose.Imaging.Brushes.TextureBrush  objekt. |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden, omslagsläget och begränsningsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Det  Aspose.Imaging.Image  objektet som detta  Aspose.Imaging.Brushes.TextureBrush  objekt fyller interiörer. |
| wrapMode | int | En  Aspose.Imaging.WrapMode  enumeration som anger hur detta  Aspose.Imaging.Brushes.TextureBrush  objekt upprepas. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | En  Aspose.Imaging.Rectangle  struktur som representerar den avgränsande rektangeln för detta  Aspose.Imaging.Brushes.TextureBrush  objekt. |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden och begränsningsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Det  Aspose.Imaging.Image  objektet som detta  Aspose.Imaging.Brushes.TextureBrush  objekt fyller interiörer. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | En  Aspose.Imaging.RectangleF  struktur som representerar den avgränsande rektangeln för detta  Aspose.Imaging.Brushes.TextureBrush  objekt. |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden, den avgränsande rektangeln och bildattributen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Det  Aspose.Imaging.Image  objektet som detta  Aspose.Imaging.Brushes.TextureBrush  objekt fyller interiörer. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | En  Aspose.Imaging.RectangleF  struktur som representerar den avgränsande rektangeln för detta  Aspose.Imaging.Brushes.TextureBrush  objekt. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Ett  com.aspose.psd.ImageAttributes  objekt som innehåller ytterligare information om bilden som används av detta  Aspose.Imaging.Brushes.TextureBrush  objekt. |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden och begränsningsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Det  Aspose.Imaging.Image  objektet som detta  Aspose.Imaging.Brushes.TextureBrush  objekt fyller interiörer. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | En  Aspose.Imaging.Rectangle  struktur som representerar den avgränsande rektangeln för detta  Aspose.Imaging.Brushes.TextureBrush  objekt. |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


Initierar en ny instans av klassen  Aspose.Imaging.Brushes.TextureBrush  som använder den angivna bilden, den avgränsande rektangeln och bildattributen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Det  Aspose.Imaging.Image  objektet som detta  Aspose.Imaging.Brushes.TextureBrush  objekt fyller interiörer. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | En  Aspose.Imaging.Rectangle  struktur som representerar den avgränsande rektangeln för detta  Aspose.Imaging.Brushes.TextureBrush  objekt. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Ett  com.aspose.psd.ImageAttributes  objekt som innehåller ytterligare information om bilden som används av detta  Aspose.Imaging.Brushes.TextureBrush  objekt. |

### close() {#close--}
```
public void close()
```


Implementerar Closable‑gränssnittet och kan användas i try‑with‑resources‑satsen sedan JDK 1.7. Denna metod anropar helt enkelt dispose‑metoden.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Skapar en ny djupklon av den aktuella  Brush .

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Frigör den aktuella instansen.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean -  true  om frigjord; annars,  false .
### getImage() {#getImage--}
```
public Image getImage()
```


Hämtar  com.aspose.psd.Image  objektet som är associerat med detta  com.aspose.psd.brushes.TextureBrush  objekt.

Värde: Ett  com.aspose.psd.Image  objekt som representerar bilden som detta  com.aspose.psd.brushes.TextureBrush  objekt fyller former med.

**Returns:**
[Image](../../com.aspose.psd/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


Hämtar  ImageAttributes  som är associerad med detta  TextureBrush .

Värde:  ImageAttributes .

**Returns:**
[ImageAttributes](../../com.aspose.psd/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


Hämtar  Rectangle  som är associerad med detta  TextureBrush .

Värde:  Rectangle .

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Hämtar penselns opacitet. Värdet bör vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig.

**Returns:**
float - Penselns opacitetsvärde.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Hämtar eller anger en kopia av  Aspose.Imaging.Matrix  som definierar en lokal geometrisk transformation för detta  TransformBrush .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Hämtar eller anger en  Aspose.Imaging.WrapMode ‑enumeration som indikerar omslagsläget för detta  TransformBrush .

**Returns:**
int - En  Aspose.Imaging.WrapMode  som specificerar hur fyllningar som ritas med denna  TransformBrush  tileas.
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


Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att sätta transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introduceras för bakåtkompatibilitet med GDI+.

Värde:  True  om transformationen ändrades; annars,  false .

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplicerar  Aspose.Imaging.Matrix  som representerar den lokala geometriska transformationen för detta  LinearGradientBrush  med den angivna  Aspose.Imaging.Matrix  genom att föregå den angivna  Aspose.Imaging.Matrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Den  Aspose.Imaging.Matrix  som används för att multiplicera den geometriska transformationen. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplicerar  Aspose.Imaging.Matrix  som representerar den lokala geometriska transformationen för detta  LinearGradientBrush  med den angivna  Aspose.Imaging.Matrix  i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Den  Aspose.Imaging.Matrix  som används för att multiplicera den geometriska transformationen. |
| ordning | int | En  Aspose.Imaging.MatrixOrder  som specificerar i vilken ordning de två matriserna ska multipliceras. |

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


Återställer egenskapen  TransformBrush.Transform  till identitet.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Roterar den lokala geometriska transformationen med den angivna mängden. Denna metod lägger till rotationen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rotera den lokala geometriska transformationen med den angivna mängden i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln. |
| ordning | int | En  Aspose.Imaging.MatrixOrder  som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skalar den lokala geometriska transformationen med de angivna värdena. Denna metod lägger till skalningsmatrisen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | Mängden att skala transformen i x‑axelns riktning. |
| sy | float | Mängden att skala transformen i y‑axelns riktning. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | Mängden att skala transformen i x‑axelns riktning. |
| sy | float | Mängden att skala transformen i y‑axelns riktning. |
| ordning | int | En  Aspose.Imaging.MatrixOrder  som anger om skalningsmatrisen ska läggas till i slutet eller i början. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Ställer in penselns opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Penselns opacitetsvärde. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Hämtar eller anger en kopia av  Aspose.Imaging.Matrix  som definierar en lokal geometrisk transformation för detta  TransformBrush .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Hämtar eller anger en  Aspose.Imaging.WrapMode ‑enumeration som indikerar omslagsläget för detta  TransformBrush .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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


Översätter den lokala geometriska transformen med de angivna dimensionerna. Denna metod lägger till översättningen i början av transformen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | float | Värdet för översättningen i x. |
| dy | float | Värdet för översättningen i y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | float | Värdet för översättningen i x. |
| dy | float | Värdet för översättningen i y. |
| ordning | int | Ordningen (infoga i början eller i slutet) i vilken översättningen ska tillämpas. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

