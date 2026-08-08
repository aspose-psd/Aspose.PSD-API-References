---
title: "LinearMulticolorGradientBrush"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt een Brush voor met een lineaire gradient gedefinieerd door meerdere kleuren en geschikte posities."
type: docs
weight: 13
url: /nl/java/com.aspose.psd.brushes/linearmulticolorgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearMulticolorGradientBrush extends LinearGradientBrushBase
```

Stelt een  Brush  voor met een lineaire gradient gedefinieerd door meerdere kleuren en geschikte posities. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush--) | Initialiseert een nieuw exemplaar van de  LinearMulticolorGradientBrush  klasse met standaardparameters. |
| [LinearMulticolorGradientBrush(Point point1, Point point2)](#LinearMulticolorGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-) | Initialiseert een nieuw exemplaar van de LinearMulticolorGradientBrush‑klasse met de opgegeven punten. |
| [LinearMulticolorGradientBrush(PointF point1, PointF point2)](#LinearMulticolorGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Initialiseert een nieuw exemplaar van de LinearMulticolorGradientBrush‑klasse met de opgegeven punten. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-) | Initialiseert een nieuw exemplaar van de LinearMulticolorGradientBrush‑klasse op basis van een rechthoek en een oriëntatiehoek. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-) | Initialiseert een nieuw exemplaar van de LinearMulticolorGradientBrush‑klasse op basis van een rechthoek en een oriëntatiehoek. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-boolean-) | Initialiseert een nieuw exemplaar van de LinearMulticolorGradientBrush‑klasse op basis van een rechthoek en een oriëntatiehoek. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-boolean-) | Initialiseert een nieuw exemplaar van de LinearMulticolorGradientBrush‑klasse op basis van een rechthoek en een oriëntatiehoek. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [deepClone()](#deepClone--) | Maakt een nieuwe diepe kloon van de huidige Brush. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Haalt de gradiënthoek op. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getGammaCorrection()](#getGammaCorrection--) | Haalt een waarde op die aangeeft of gamma-correctie is ingeschakeld voor deze LinearGradientBrushBase. |
| [getInterpolationColors()](#getInterpolationColors--) | Haalt een com.aspose.psd.ColorBlend op die een meerkleurige lineaire gradiënt definieert. |
| [getOpacity()](#getOpacity--) | Haalt de dekking van de brush op. |
| [getRectangle()](#getRectangle--) | Haalt een rechthoekig gebied op dat de begin- en eindpunten van de gradiënt definieert. |
| [getTransform()](#getTransform--) | Haalt op of stelt een kopie van Aspose.Imaging.Matrix in die een lokale geometrische transformatie voor deze TransformBrush definieert. |
| [getWrapMode()](#getWrapMode--) | Haalt op of stelt een Aspose.Imaging.WrapMode‑enumeratie in die de wrap-modus voor deze TransformBrush aangeeft. |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | Haalt een waarde op die aangeeft of LinearGradientBrushBase.Angle wordt gewijzigd tijdens transformaties met deze LinearGradientBrushBase. |
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
| [setAngle(float value)](#setAngle-float-) | Stelt de gradiënthoek in. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Stelt een waarde in die aangeeft of LinearGradientBrushBase.Angle wordt gewijzigd tijdens transformaties met deze LinearGradientBrushBase. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Stelt een waarde in die aangeeft of gamma-correctie is ingeschakeld voor deze LinearGradientBrushBase. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Stelt een com.aspose.psd.ColorBlend in die een meerkleurige lineaire gradiënt definieert. |
| [setOpacity(float value)](#setOpacity-float-) | Stelt de dekking van de brush in. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Stelt een rechthoekig gebied in dat de begin- en eindpunten van de gradiënt definieert. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Haalt op of stelt een kopie van Aspose.Imaging.Matrix in die een lokale geometrische transformatie voor deze TransformBrush definieert. |
| [setWrapMode(int value)](#setWrapMode-int-) | Haalt op of stelt een Aspose.Imaging.WrapMode‑enumeratie in die de wrap-modus voor deze TransformBrush aangeeft. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush--}
```
public LinearMulticolorGradientBrush()
```


Initialiseert een nieuw exemplaar van de LinearMulticolorGradientBrush-klasse met standaardparameters. De startkleur is zwart, de eindkleur is wit, de hoek is 45 graden en het rechthoek bevindt zich op (0,0) met grootte (1,1).

### LinearMulticolorGradientBrush(Point point1, Point point2) {#LinearMulticolorGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public LinearMulticolorGradientBrush(Point point1, Point point2)
```


Initialiseert een nieuw exemplaar van de LinearMulticolorGradientBrush‑klasse met de opgegeven punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Een Aspose.Imaging.Point-structuur die het startpunt van de lineaire gradiënt weergeeft. |
| point2 | [Point](../../com.aspose.psd/point) | Een Aspose.Imaging.Point-structuur die het eindpunt van de lineaire gradiënt weergeeft. |

### LinearMulticolorGradientBrush(PointF point1, PointF point2) {#LinearMulticolorGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public LinearMulticolorGradientBrush(PointF point1, PointF point2)
```


Initialiseert een nieuw exemplaar van de LinearMulticolorGradientBrush‑klasse met de opgegeven punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Een Aspose.Imaging.PointF-structuur die het startpunt van de lineaire gradiënt weergeeft. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Een Aspose.Imaging.PointF-structuur die het eindpunt van de lineaire gradiënt weergeeft. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle)
```


Initialiseert een nieuw exemplaar van de LinearMulticolorGradientBrush‑klasse op basis van een rechthoek en een oriëntatiehoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Een Aspose.Imaging.RectangleF-structuur die de grenzen van de lineaire gradiënt specificeert. |
| angle | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradiënt. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle)
```


Initialiseert een nieuw exemplaar van de LinearMulticolorGradientBrush‑klasse op basis van een rechthoek en een oriëntatiehoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Een Aspose.Imaging.RectangleF-structuur die de grenzen van de lineaire gradiënt specificeert. |
| angle | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradiënt. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-boolean-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)
```


Initialiseert een nieuw exemplaar van de LinearMulticolorGradientBrush‑klasse op basis van een rechthoek en een oriëntatiehoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Een Aspose.Imaging.RectangleF-structuur die de grenzen van de lineaire gradiënt specificeert. |
| angle | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradiënt. |
| isAngleScalable | boolean | indien ingesteld op true, wordt de hoek gewijzigd tijdens transformaties met deze LinearMulticolorGradientBrush. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-boolean-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)
```


Initialiseert een nieuw exemplaar van de LinearMulticolorGradientBrush‑klasse op basis van een rechthoek en een oriëntatiehoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Een Aspose.Imaging.RectangleF-structuur die de grenzen van de lineaire gradiënt specificeert. |
| angle | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradiënt. |
| isAngleScalable | boolean | indien ingesteld op true, wordt de hoek gewijzigd tijdens transformaties met deze LinearMulticolorGradientBrush. |

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


Haalt de gradiënthoek op.

**Returns:**
float - De gradiënthoek.
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
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Haalt een waarde op die aangeeft of gamma-correctie is ingeschakeld voor deze LinearGradientBrushBase.

**Returns:**
boolean - De waarde is true als gamma-correctie is ingeschakeld voor deze LinearGradientBrushBase; anders false.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Haalt een com.aspose.psd.ColorBlend op die een meerkleurige lineaire gradiënt definieert.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Haalt de dekking van de penseel op. De waarde moet tussen 0 en 1 liggen. Een waarde van 0 betekent dat de penseel volledig zichtbaar is, een waarde van 1 betekent dat de penseel volledig ondoorzichtig is.

**Returns:**
float - De dekkingwaarde van de penseel.
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Haalt een rechthoekig gebied op dat de begin- en eindpunten van de gradiënt definieert.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
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
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Haalt een waarde op die aangeeft of LinearGradientBrushBase.Angle wordt gewijzigd tijdens transformaties met deze LinearGradientBrushBase.

**Returns:**
boolean - true als LinearGradientBrushBase.Angle wordt gewijzigd tijdens transformaties met deze LinearGradientBrushBase; anders false.
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

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Stelt de gradiënthoek in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | De gradiënthoek. |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Stelt een waarde in die aangeeft of LinearGradientBrushBase.Angle wordt gewijzigd tijdens transformaties met deze LinearGradientBrushBase.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true  als  LinearGradientBrushBase.Angle  wordt gewijzigd tijdens transformaties met deze  LinearGradientBrushBase ; anders,  false . |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Stelt een waarde in die aangeeft of gamma-correctie is ingeschakeld voor deze LinearGradientBrushBase.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | De waarde is true als gamma-correctie is ingeschakeld voor deze  LinearGradientBrushBase ; anders, false. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Stelt een com.aspose.psd.ColorBlend in die een meerkleurige lineaire gradiënt definieert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | Een  com.aspose.psd.ColorBlend  die een meerkleurige lineaire gradiënt definieert. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Stelt de dekking van de penseel in. De waarde moet tussen 0 en 1 liggen. Een waarde van 0 betekent dat de penseel volledig zichtbaar is, een waarde van 1 betekent dat de penseel volledig ondoorzichtig is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | De dekkingwaarde van de penseel. |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Stelt een rechthoekig gebied in dat de begin- en eindpunten van de gradiënt definieert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Een  com.aspose.psd.RectangleF  structuur die de begin- en eindpunten van de gradiënt specificeert. |

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

