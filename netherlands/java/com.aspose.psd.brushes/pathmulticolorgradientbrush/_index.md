---
title: "PathMulticolorGradientBrush"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Omvat een Aspose.Imaging.Brush-object met een gradiënt."
type: docs
weight: 16
url: /nl/java/com.aspose.psd.brushes/pathmulticolorgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathMulticolorGradientBrush extends PathGradientBrushBase
```

Omvat een  Aspose.Imaging.Brush  object met een gradiënt. Deze klasse kan niet worden geërfd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PathMulticolorGradientBrush(PointF[] points)](#PathMulticolorGradientBrush-com.aspose.psd.PointF---) | Initialiseert een nieuw exemplaar van de  PathMulticolorGradientBrush  klasse met de opgegeven punten. |
| [PathMulticolorGradientBrush(PointF[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.psd.PointF---int-) | Initialiseert een nieuw exemplaar van de  PathMulticolorGradientBrush  klasse met de opgegeven punten en wrap-modus. |
| [PathMulticolorGradientBrush(Point[] points)](#PathMulticolorGradientBrush-com.aspose.psd.Point---) | Initialiseert een nieuw exemplaar van de  PathMulticolorGradientBrush  klasse met de opgegeven punten. |
| [PathMulticolorGradientBrush(Point[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.psd.Point---int-) | Initialiseert een nieuw exemplaar van de  PathMulticolorGradientBrush  klasse met de opgegeven punten en wrap-modus. |
| [PathMulticolorGradientBrush(GraphicsPath path)](#PathMulticolorGradientBrush-com.aspose.psd.GraphicsPath-) | Initialiseert een nieuw exemplaar van de  PathMulticolorGradientBrush  klasse met het opgegeven pad. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [deepClone()](#deepClone--) | Maakt een nieuwe diepe kloon van de huidige Brush. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCenterPoint()](#getCenterPoint--) | Haalt op of stelt het middelpunt van de padgradiënt in. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getFocusScales()](#getFocusScales--) | Haalt het focuspunt op voor de afname van de gradiënt. |
| [getGraphicsPath()](#getGraphicsPath--) | Haalt het grafische pad op waarop deze kwast is gebaseerd. |
| [getInterpolationColors()](#getInterpolationColors--) | Haalt een  com.aspose.psd.ColorBlend  op of stelt deze in die een meerkleurige lineaire gradiënt definieert. |
| [getOpacity()](#getOpacity--) | Haalt de dekking van de brush op. |
| [getPathPoints()](#getPathPoints--) | Haalt de padpunten op waarop deze kwast is gebaseerd. |
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
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | Haalt op of stelt het middelpunt van de padgradiënt in. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | Haalt het focuspunt op of stelt het in voor de vervaging van de gradiënt. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Haalt een  com.aspose.psd.ColorBlend  op of stelt deze in die een meerkleurige lineaire gradiënt definieert. |
| [setOpacity(float value)](#setOpacity-float-) | Stelt de dekking van de brush in. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Haalt op of stelt een kopie van Aspose.Imaging.Matrix in die een lokale geometrische transformatie voor deze TransformBrush definieert. |
| [setWrapMode(int value)](#setWrapMode-int-) | Haalt op of stelt een Aspose.Imaging.WrapMode‑enumeratie in die de wrap-modus voor deze TransformBrush aangeeft. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathMulticolorGradientBrush(PointF[] points) {#PathMulticolorGradientBrush-com.aspose.psd.PointF---}
```
public PathMulticolorGradientBrush(PointF[] points)
```


Initialiseert een nieuw exemplaar van de  PathMulticolorGradientBrush  klasse met de opgegeven punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Een array van  Aspose.Imaging.PointF  structuren die de punten vertegenwoordigen die de hoekpunten van het pad vormen. |

### PathMulticolorGradientBrush(PointF[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.psd.PointF---int-}
```
public PathMulticolorGradientBrush(PointF[] points, int wrapMode)
```


Initialiseert een nieuw exemplaar van de  PathMulticolorGradientBrush  klasse met de opgegeven punten en wrap-modus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Een array van  Aspose.Imaging.PointF  structuren die de punten vertegenwoordigen die de hoekpunten van het pad vormen. |
| wrapMode | int | Een  Aspose.Imaging.WrapMode  die specificeert hoe vullingen die met deze  PathMulticolorGradientBrush  worden getekend, worden getegeld. |

### PathMulticolorGradientBrush(Point[] points) {#PathMulticolorGradientBrush-com.aspose.psd.Point---}
```
public PathMulticolorGradientBrush(Point[] points)
```


Initialiseert een nieuw exemplaar van de  PathMulticolorGradientBrush  klasse met de opgegeven punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Een array van  Aspose.Imaging.Point  structuren die de punten vertegenwoordigen die de hoekpunten van het pad vormen. |

### PathMulticolorGradientBrush(Point[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.psd.Point---int-}
```
public PathMulticolorGradientBrush(Point[] points, int wrapMode)
```


Initialiseert een nieuw exemplaar van de  PathMulticolorGradientBrush  klasse met de opgegeven punten en wrap-modus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Een array van  Aspose.Imaging.Point  structuren die de punten vertegenwoordigen die de hoekpunten van het pad vormen. |
| wrapMode | int | Een  Aspose.Imaging.WrapMode  die specificeert hoe vullingen die met deze  PathMulticolorGradientBrush  worden getekend, worden getegeld. |

### PathMulticolorGradientBrush(GraphicsPath path) {#PathMulticolorGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathMulticolorGradientBrush(GraphicsPath path)
```


Initialiseert een nieuw exemplaar van de  PathMulticolorGradientBrush  klasse met het opgegeven pad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Het  GraphicsPath  dat het gebied definieert dat door deze  PathMulticolorGradientBrush  wordt gevuld. |

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
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Haalt op of stelt het middelpunt van de padgradiënt in.

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


Haalt een waarde op die aangeeft of deze instantie is vrijgegeven.

**Returns:**
boolean -  true  als vrijgegeven; anders,  false .
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Haalt het focuspunt op voor de afname van de gradiënt.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Haalt het grafische pad op waarop deze kwast is gebaseerd.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Haalt een  com.aspose.psd.ColorBlend  op of stelt deze in die een meerkleurige lineaire gradiënt definieert.

Waarde: Een  com.aspose.psd.ColorBlend  die een meerkleurige lineaire gradiënt definieert.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend)
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Haalt de dekking van de penseel op. De waarde moet tussen 0 en 1 liggen. Een waarde van 0 betekent dat de penseel volledig zichtbaar is, een waarde van 1 betekent dat de penseel volledig ondoorzichtig is.

**Returns:**
float - De dekkingwaarde van de penseel.
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Haalt de padpunten op waarop deze kwast is gebaseerd.

**Returns:**
com.aspose.psd.PointF[] - De padpunten.
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

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


Haalt op of stelt het middelpunt van de padgradiënt in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Een  Aspose.Imaging.PointF  die het middelpunt van de padgradiënt weergeeft. |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


Haalt het focuspunt op of stelt het in voor de vervaging van de gradiënt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Een  Aspose.Imaging.PointF  die het focuspunt voor de vervaging van de gradiënt weergeeft. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Haalt een  com.aspose.psd.ColorBlend  op of stelt deze in die een meerkleurige lineaire gradiënt definieert.

Waarde: Een  com.aspose.psd.ColorBlend  die een meerkleurige lineaire gradiënt definieert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) |  |

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

