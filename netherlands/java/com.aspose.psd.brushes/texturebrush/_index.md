---
title: "TextureBrush"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Elke eigenschap van de Aspose.Imaging.Brushes.TextureBrush-klasse is een Aspose.Imaging.Brush-object dat een afbeelding gebruikt om het binnenste van een vorm te vullen."
type: docs
weight: 18
url: /nl/java/com.aspose.psd.brushes/texturebrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public final class TextureBrush extends TransformBrush
```

Elke eigenschap van de  Aspose.Imaging.Brushes.TextureBrush  klasse is een  Aspose.Imaging.Brush  object dat een afbeelding gebruikt om het binnenste van een vorm te vullen. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextureBrush(Image image)](#TextureBrush-com.aspose.psd.Image-) | Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding gebruikt. |
| [TextureBrush(Image image, int wrapMode)](#TextureBrush-com.aspose.psd.Image-int-) | Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding en wrap-modus gebruikt. |
| [TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-) | Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding, wrap-modus en begrenzende rechthoek gebruikt. |
| [TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-) | Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding, wrap-modus en begrenzende rechthoek gebruikt. |
| [TextureBrush(Image image, RectangleF destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding en begrenzende rechthoek gebruikt. |
| [TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-) | Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding, begrenzende rechthoek en afbeeldingseigenschappen gebruikt. |
| [TextureBrush(Image image, Rectangle destinationRectangle)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding en begrenzende rechthoek gebruikt. |
| [TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)](#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-) | Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding, begrenzende rechthoek en afbeeldingseigenschappen gebruikt. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [deepClone()](#deepClone--) | Maakt een nieuwe diepe kloon van de huidige Brush. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getImage()](#getImage--) | Haalt het  com.aspose.psd.Image  object op dat is geassocieerd met dit  com.aspose.psd.brushes.TextureBrush  object. |
| [getImageAttributes()](#getImageAttributes--) | Haalt de  ImageAttributes  op die bij deze  TextureBrush . |
| [getImageRectangle()](#getImageRectangle--) | Haalt de  Rectangle  op die bij deze  TextureBrush . |
| [getOpacity()](#getOpacity--) | Haalt de dekking van de brush op. |
| [getTransform()](#getTransform--) | Haalt op of stelt een kopie van Aspose.Imaging.Matrix in die een lokale geometrische transformatie voor deze TransformBrush definieert. |
| [getWrapMode()](#getWrapMode--) | Haalt op of stelt een Aspose.Imaging.WrapMode‑enumeratie in die de wrap-modus voor deze TransformBrush aangeeft. |
| [hashCode()](#hashCode--) |  |
| [isTransformChanged()](#isTransformChanged--) | Haalt een waarde op die aangeeft of transformaties op een of andere manier zijn gewijzigd. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Vermenigvuldigt de Aspose.Imaging.Matrix die de lokale geometrische transformatie van deze LinearGradientBrush vertegenwoordigt met de opgegeven Aspose.Imaging.Matrix door de opgegeven Aspose.Imaging.Matrix vooraan toe te voegen. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Vermenigvuldigt de Aspose.Imaging.Matrix die de lokale geometrische transformatie van deze LinearGradientBrush vertegenwoordigt met de opgegeven Aspose.Imaging.Matrix in de opgegeven volgorde. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Stelt de TransformBrush.Transform‑eigenschap opnieuw in op de identiteit. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden in de opgegeven volgorde. |
| [setOpacity(float value)](#setOpacity-float-) | Stelt de dekking van de brush in. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Haalt op of stelt een kopie van Aspose.Imaging.Matrix in die een lokale geometrische transformatie voor deze TransformBrush definieert. |
| [setWrapMode(int value)](#setWrapMode-int-) | Haalt op of stelt een Aspose.Imaging.WrapMode‑enumeratie in die de wrap-modus voor deze TransformBrush aangeeft. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureBrush(Image image) {#TextureBrush-com.aspose.psd.Image-}
```
public TextureBrush(Image image)
```


Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Het  Aspose.Imaging.Image  object waarmee dit  Aspose.Imaging.Brushes.TextureBrush  object interieurs vult. |

### TextureBrush(Image image, int wrapMode) {#TextureBrush-com.aspose.psd.Image-int-}
```
public TextureBrush(Image image, int wrapMode)
```


Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding en wrap-modus gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Het  Aspose.Imaging.Image  object waarmee dit  Aspose.Imaging.Brushes.TextureBrush  object interieurs vult. |
| wrapMode | int | Een  Aspose.Imaging.WrapMode  enumeratie die specificeert hoe dit  Aspose.Imaging.Brushes.TextureBrush  object wordt getegeld. |

### TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, int wrapMode, RectangleF destinationRectangle)
```


Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding, wrap-modus en begrenzende rechthoek gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Het  Aspose.Imaging.Image  object waarmee dit  Aspose.Imaging.Brushes.TextureBrush  object interieurs vult. |
| wrapMode | int | Een  Aspose.Imaging.WrapMode  enumeratie die specificeert hoe dit  Aspose.Imaging.Brushes.TextureBrush  object wordt getegeld. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Een  Aspose.Imaging.RectangleF  structuur die de begrenzende rechthoek voor dit  Aspose.Imaging.Brushes.TextureBrush  object weergeeft. |

### TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-int-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, int wrapMode, Rectangle destinationRectangle)
```


Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding, wrap-modus en begrenzende rechthoek gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Het  Aspose.Imaging.Image  object waarmee dit  Aspose.Imaging.Brushes.TextureBrush  object interieurs vult. |
| wrapMode | int | Een  Aspose.Imaging.WrapMode  enumeratie die specificeert hoe dit  Aspose.Imaging.Brushes.TextureBrush  object wordt getegeld. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Een  Aspose.Imaging.Rectangle  structuur die de begrenzende rechthoek voor dit  Aspose.Imaging.Brushes.TextureBrush  object weergeeft. |

### TextureBrush(Image image, RectangleF destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public TextureBrush(Image image, RectangleF destinationRectangle)
```


Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding en begrenzende rechthoek gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Het  Aspose.Imaging.Image  object waarmee dit  Aspose.Imaging.Brushes.TextureBrush  object interieurs vult. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Een  Aspose.Imaging.RectangleF  structuur die de begrenzende rechthoek voor dit  Aspose.Imaging.Brushes.TextureBrush  object weergeeft. |

### TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, RectangleF destinationRectangle, ImageAttributes imageAttributes)
```


Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding, begrenzende rechthoek en afbeeldingseigenschappen gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Het  Aspose.Imaging.Image  object waarmee dit  Aspose.Imaging.Brushes.TextureBrush  object interieurs vult. |
| destinationRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Een  Aspose.Imaging.RectangleF  structuur die de begrenzende rechthoek voor dit  Aspose.Imaging.Brushes.TextureBrush  object weergeeft. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Een  com.aspose.psd.ImageAttributes  object dat extra informatie bevat over de afbeelding die door dit  Aspose.Imaging.Brushes.TextureBrush  object wordt gebruikt. |

### TextureBrush(Image image, Rectangle destinationRectangle) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public TextureBrush(Image image, Rectangle destinationRectangle)
```


Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding en begrenzende rechthoek gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Het  Aspose.Imaging.Image  object waarmee dit  Aspose.Imaging.Brushes.TextureBrush  object interieurs vult. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Een  Aspose.Imaging.Rectangle  structuur die de begrenzende rechthoek voor dit  Aspose.Imaging.Brushes.TextureBrush  object weergeeft. |

### TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes) {#TextureBrush-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.ImageAttributes-}
```
public TextureBrush(Image image, Rectangle destinationRectangle, ImageAttributes imageAttributes)
```


Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Brushes.TextureBrush  klasse die de opgegeven afbeelding, begrenzende rechthoek en afbeeldingseigenschappen gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Het  Aspose.Imaging.Image  object waarmee dit  Aspose.Imaging.Brushes.TextureBrush  object interieurs vult. |
| destinationRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Een  Aspose.Imaging.Rectangle  structuur die de begrenzende rechthoek voor dit  Aspose.Imaging.Brushes.TextureBrush  object weergeeft. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Een  com.aspose.psd.ImageAttributes  object dat extra informatie bevat over de afbeelding die door dit  Aspose.Imaging.Brushes.TextureBrush  object wordt gebruikt. |

### close() {#close--}
```
public void close()
```


Implementeert de Closable-interface en kan worden gebruikt in de try-with-resources-instructie sinds JDK 1.7. Deze methode roept simpelweg de dispose-methode aan.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Maakt een nieuwe diepe kloon van de huidige Brush.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert de huidige instantie.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt een waarde op die aangeeft of deze instantie is vrijgegeven.

**Returns:**
boolean -  true  als vrijgegeven; anders,  false .
### getImage() {#getImage--}
```
public Image getImage()
```


Haalt het  com.aspose.psd.Image  object op dat is geassocieerd met dit  com.aspose.psd.brushes.TextureBrush  object.

Waarde: Een  com.aspose.psd.Image  object dat de afbeelding vertegenwoordigt waarmee dit  com.aspose.psd.brushes.TextureBrush  object vormen vult.

**Returns:**
[Image](../../com.aspose.psd/image)
### getImageAttributes() {#getImageAttributes--}
```
public ImageAttributes getImageAttributes()
```


Haalt de  ImageAttributes  op die bij deze  TextureBrush .

Waarde: De  ImageAttributes .

**Returns:**
[ImageAttributes](../../com.aspose.psd/imageattributes)
### getImageRectangle() {#getImageRectangle--}
```
public RectangleF getImageRectangle()
```


Haalt de  Rectangle  op die bij deze  TextureBrush .

Waarde: De  Rectangle .

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Haalt de dekking van de penseel op. De waarde moet tussen 0 en 1 liggen. Een waarde van 0 betekent dat de penseel volledig zichtbaar is, een waarde van 1 betekent dat de penseel volledig ondoorzichtig is.

**Returns:**
float - De dekkingwaarde van de penseel.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Haalt op of stelt een kopie van Aspose.Imaging.Matrix in die een lokale geometrische transformatie voor deze TransformBrush definieert.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Haalt op of stelt een Aspose.Imaging.WrapMode‑enumeratie in die de wrap-modus voor deze TransformBrush aangeeft.

**Returns:**
int - Een Aspose.Imaging.WrapMode die specificeert hoe vullingen getekend met deze TransformBrush worden getegeld.
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


Haalt een waarde op die aangeeft of transformaties op enige wijze zijn gewijzigd. Bijvoorbeeld het instellen van de transformatie-matrix of het aanroepen van een van de methoden die de transformatie-matrix wijzigen. De eigenschap is geïntroduceerd voor achterwaartse compatibiliteit met GDI+.

Waarde: True als de transformatie is gewijzigd; anders false.

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Vermenigvuldigt de Aspose.Imaging.Matrix die de lokale geometrische transformatie van deze LinearGradientBrush vertegenwoordigt met de opgegeven Aspose.Imaging.Matrix door de opgegeven Aspose.Imaging.Matrix vooraan toe te voegen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | De Aspose.Imaging.Matrix waarmee de geometrische transformatie wordt vermenigvuldigd. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Vermenigvuldigt de Aspose.Imaging.Matrix die de lokale geometrische transformatie van deze LinearGradientBrush vertegenwoordigt met de opgegeven Aspose.Imaging.Matrix in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | De Aspose.Imaging.Matrix waarmee de geometrische transformatie wordt vermenigvuldigd. |
| volgorde | int | Een Aspose.Imaging.MatrixOrder die specificeert in welke volgorde de twee matrices worden vermenigvuldigd. |

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


Stelt de TransformBrush.Transform‑eigenschap opnieuw in op de identiteit.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. Deze methode voegt de rotatie vooraan toe aan de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | float | De rotatiehoek. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | float | De rotatiehoek. |
| volgorde | int | Een Aspose.Imaging.MatrixOrder die specificeert of de rotatiematrix moet worden toegevoegd of voorafgeplaatst. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden. Deze methode plaatst de schaalmatrix vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De hoeveelheid waarmee de transformatie in de x-richting wordt geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie in de y-richting wordt geschaald. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De hoeveelheid waarmee de transformatie in de x-richting wordt geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie in de y-richting wordt geschaald. |
| volgorde | int | Een  Aspose.Imaging.MatrixOrder  die aangeeft of de schaalmatrix moet worden toegevoegd of vóórgeplaatst. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Stelt de dekking van de penseel in. De waarde moet tussen 0 en 1 liggen. Een waarde van 0 betekent dat de penseel volledig zichtbaar is, een waarde van 1 betekent dat de penseel volledig ondoorzichtig is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | De dekkingwaarde van de penseel. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Haalt op of stelt een kopie van Aspose.Imaging.Matrix in die een lokale geometrische transformatie voor deze TransformBrush definieert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Haalt op of stelt een Aspose.Imaging.WrapMode‑enumeratie in die de wrap-modus voor deze TransformBrush aangeeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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


Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |
| volgorde | int | De volgorde (voorgaan of toevoegen) waarin de translatie moet worden toegepast. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

