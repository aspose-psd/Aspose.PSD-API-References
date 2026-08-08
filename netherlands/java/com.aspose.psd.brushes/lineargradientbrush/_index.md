---
title: "LinearGradientBrush"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Omvat een Aspose.Imaging.Brush met een lineaire kleurverloop."
type: docs
weight: 11
url: /nl/java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Omvat een  Aspose.Imaging.Brush  met een lineaire kleurverloop. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | Initialiseert een nieuw exemplaar van de  LinearGradientBrush  klasse met standaardparameters. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | Initialiseert een nieuw exemplaar van de  LinearGradientBrush  klasse met de opgegeven punten en kleuren. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | Initialiseert een nieuw exemplaar van de  LinearGradientBrush  klasse met de opgegeven punten en kleuren. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Initialiseert een nieuw exemplaar van de  LinearGradientBrush  klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Initialiseert een nieuw exemplaar van de  LinearGradientBrush  klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Initialiseert een nieuw exemplaar van de  LinearGradientBrush  klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Initialiseert een nieuw exemplaar van de  LinearGradientBrush  klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [deepClone()](#deepClone--) | Maakt een nieuwe diepe kloon van de huidige Brush. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Haalt de gradiënthoek op. |
| [getBlend()](#getBlend--) | Haalt een  Aspose.Imaging.Blend  op die posities en factoren specificeert die een aangepaste afname voor de kleurverloop definiëren. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getEndColor()](#getEndColor--) | Haalt de eindkleur van de kleurverloop op. |
| [getGammaCorrection()](#getGammaCorrection--) | Haalt een waarde op die aangeeft of gamma-correctie is ingeschakeld voor deze LinearGradientBrushBase. |
| [getInterpolationColors()](#getInterpolationColors--) | Haalt een com.aspose.psd.ColorBlend op die een meerkleurige lineaire gradiënt definieert. |
| [getLinearColors()](#getLinearColors--) | Haalt de start- en eindkleuren van de kleurverloop op. |
| [getOpacity()](#getOpacity--) | Haalt de dekking van de brush op. |
| [getRectangle()](#getRectangle--) | Haalt een rechthoekig gebied op dat de begin- en eindpunten van de gradiënt definieert. |
| [getStartColor()](#getStartColor--) | Haalt de startkleur van de kleurverloop op. |
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
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Stelt een  Aspose.Imaging.Blend  in die posities en factoren specificeert die een aangepaste afname voor de kleurverloop definiëren. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Maakt een lineaire kleurverloop met een middelkleur en een lineaire afname naar één kleur aan beide uiteinden. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Maakt een lineaire kleurverloop met een middelkleur en een lineaire afname naar één kleur aan beide uiteinden. |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | Stelt de eindkleur van de kleurverloop in. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Stelt een waarde in die aangeeft of gamma-correctie is ingeschakeld voor deze LinearGradientBrushBase. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Stelt een com.aspose.psd.ColorBlend in die een meerkleurige lineaire gradiënt definieert. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | Stelt de start- en eindkleuren van de kleurverloop in. |
| [setOpacity(float value)](#setOpacity-float-) | Stelt de dekking van de brush in. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Stelt een rechthoekig gebied in dat de begin- en eindpunten van de gradiënt definieert. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Maakt een kleurverloop-afname gebaseerd op een klokvormige curve. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Maakt een kleurverloop-afname gebaseerd op een klokvormige curve. |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | Stelt de startkleur van de kleurverloop in. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Haalt op of stelt een kopie van Aspose.Imaging.Matrix in die een lokale geometrische transformatie voor deze TransformBrush definieert. |
| [setWrapMode(int value)](#setWrapMode-int-) | Haalt op of stelt een Aspose.Imaging.WrapMode‑enumeratie in die de wrap-modus voor deze TransformBrush aangeeft. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Initialiseert een nieuw exemplaar van de **LinearGradientBrush**-klasse met standaardparameters. De startkleur is zwart, de eindkleur is wit, de hoek is 45 graden en het rechthoek bevindt zich op (0,0) met grootte (1,1).

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Initialiseert een nieuw exemplaar van de  LinearGradientBrush  klasse met de opgegeven punten en kleuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Een Aspose.Imaging.Point-structuur die het startpunt van de lineaire gradiënt weergeeft. |
| point2 | [Point](../../com.aspose.psd/point) | Een Aspose.Imaging.Point-structuur die het eindpunt van de lineaire gradiënt weergeeft. |
| color1 | [Color](../../com.aspose.psd/color) | Een com.aspose.psd.Color-structuur die de startkleur van de lineaire gradiënt weergeeft. |
| color2 | [Color](../../com.aspose.psd/color) | Een com.aspose.psd.Color-structuur die de eindkleur van de lineaire gradiënt weergeeft. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Initialiseert een nieuw exemplaar van de  LinearGradientBrush  klasse met de opgegeven punten en kleuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Een Aspose.Imaging.PointF-structuur die het startpunt van de lineaire gradiënt weergeeft. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Een Aspose.Imaging.PointF-structuur die het eindpunt van de lineaire gradiënt weergeeft. |
| color1 | [Color](../../com.aspose.psd/color) | Een com.aspose.psd.Color-structuur die de startkleur van de lineaire gradiënt weergeeft. |
| color2 | [Color](../../com.aspose.psd/color) | Een com.aspose.psd.Color-structuur die de eindkleur van de lineaire gradiënt weergeeft. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Initialiseert een nieuw exemplaar van de  LinearGradientBrush  klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Een Aspose.Imaging.RectangleF-structuur die de grenzen van de lineaire gradiënt specificeert. |
| color1 | [Color](../../com.aspose.psd/color) | Een com.aspose.psd.Color-structuur die de startkleur voor de gradiënt weergeeft. |
| color2 | [Color](../../com.aspose.psd/color) | Een com.aspose.psd.Color-structuur die de eindkleur voor de gradiënt weergeeft. |
| angle | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradiënt. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Initialiseert een nieuw exemplaar van de  LinearGradientBrush  klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Een Aspose.Imaging.RectangleF-structuur die de grenzen van de lineaire gradiënt specificeert. |
| color1 | [Color](../../com.aspose.psd/color) | Een com.aspose.psd.Color-structuur die de startkleur voor de gradiënt weergeeft. |
| color2 | [Color](../../com.aspose.psd/color) | Een com.aspose.psd.Color-structuur die de eindkleur voor de gradiënt weergeeft. |
| angle | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradiënt. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initialiseert een nieuw exemplaar van de  LinearGradientBrush  klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Een Aspose.Imaging.RectangleF-structuur die de grenzen van de lineaire gradiënt specificeert. |
| color1 | [Color](../../com.aspose.psd/color) | Een com.aspose.psd.Color-structuur die de startkleur voor de gradiënt weergeeft. |
| color2 | [Color](../../com.aspose.psd/color) | Een com.aspose.psd.Color-structuur die de eindkleur voor de gradiënt weergeeft. |
| angle | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradiënt. |
| isAngleScalable | boolean | Indien ingesteld op true, wordt de hoek tijdens transformaties gewijzigd met deze **LinearGradientBrush**. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initialiseert een nieuw exemplaar van de  LinearGradientBrush  klasse gebaseerd op een rechthoek, start- en eindkleuren, en een oriëntatiehoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Een Aspose.Imaging.RectangleF-structuur die de grenzen van de lineaire gradiënt specificeert. |
| color1 | [Color](../../com.aspose.psd/color) | Een com.aspose.psd.Color-structuur die de startkleur voor de gradiënt weergeeft. |
| color2 | [Color](../../com.aspose.psd/color) | Een com.aspose.psd.Color-structuur die de eindkleur voor de gradiënt weergeeft. |
| angle | float | De hoek, gemeten in graden met de klok mee vanaf de x-as, van de oriëntatielijn van de gradiënt. |
| isAngleScalable | boolean | Indien ingesteld op true, wordt de hoek tijdens transformaties gewijzigd met deze **LinearGradientBrush**. |

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Haalt een  Aspose.Imaging.Blend  op die posities en factoren specificeert die een aangepaste afname voor de kleurverloop definiëren.

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


Haalt een waarde op die aangeeft of deze instantie is vrijgegeven.

**Returns:**
boolean -  true  als vrijgegeven; anders,  false .
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Haalt de eindkleur van de kleurverloop op.

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
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
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Haalt de start- en eindkleuren van de kleurverloop op.

**Returns:**
com.aspose.psd.Color[] - Een array van twee Color-structuren die de start- en eindkleuren van de gradiënt weergeven.
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
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Haalt de startkleur van de kleurverloop op.

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
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

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


Stelt een  Aspose.Imaging.Blend  in die posities en factoren specificeert die een aangepaste afname voor de kleurverloop definiëren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | Een **Aspose.Imaging.Blend** die een aangepaste uitval voor de gradiënt weergeeft. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Maakt een lineaire kleurverloop met een middelkleur en een lineaire afname naar één kleur aan beide uiteinden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| focus | float | Een waarde van 0 tot 1 die het midden van de gradiënt specificeert (het punt waar de gradiënt uitsluitend uit de eindkleur bestaat). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Maakt een lineaire kleurverloop met een middelkleur en een lineaire afname naar één kleur aan beide uiteinden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| focus | float | Een waarde van 0 tot 1 die het midden van de gradiënt specificeert (het punt waar de gradiënt uitsluitend uit de eindkleur bestaat). |
| scale | float | Een waarde van 0 tot 1 die aangeeft hoe snel de kleuren afnemen van de startkleur naar de focus (eindkleur). |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


Stelt de eindkleur van de kleurverloop in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | De eindkleur van de gradiënt. |

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

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


Stelt de start- en eindkleuren van de kleurverloop in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Een array van twee Color-structuren die de start- en eindkleuren van de gradiënt weergeven. |

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

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Maakt een kleurverloop-afname gebaseerd op een klokvormige curve.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| focus | float | Een waarde van 0 tot 1 die het midden van de gradiënt specificeert (het punt waar de startkleur en eindkleur gelijkmatig worden gemengd). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Maakt een kleurverloop-afname gebaseerd op een klokvormige curve.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| focus | float | Een waarde van 0 tot 1 die het midden van de gradiënt specificeert (het punt waar de gradiënt uitsluitend uit de eindkleur bestaat). |
| scale | float | Een waarde van 0 tot 1 die aangeeft hoe snel de kleuren afnemen van de focus. |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


Stelt de startkleur van de kleurverloop in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | De startkleur van de gradiënt. |

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

