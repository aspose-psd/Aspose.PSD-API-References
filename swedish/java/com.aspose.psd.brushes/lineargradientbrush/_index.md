---
title: "LinearGradientBrush"
second_title: "Aspose.PSD för Java API-referens"
description: "Inkapslar en Aspose.Imaging.Brush med en linjär gradient."
type: docs
weight: 11
url: /sv/java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Inkapslar en  Aspose.Imaging.Brush  med en linjär gradient. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | Initierar en ny instans av  LinearGradientBrush  klassen med standardparametrar. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | Initierar en ny instans av  LinearGradientBrush  klassen med de angivna punkterna och färgerna. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | Initierar en ny instans av  LinearGradientBrush  klassen med de angivna punkterna och färgerna. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Initierar en ny instans av  LinearGradientBrush  klassen baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Initierar en ny instans av  LinearGradientBrush  klassen baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Initierar en ny instans av  LinearGradientBrush  klassen baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Initierar en ny instans av  LinearGradientBrush  klassen baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [deepClone()](#deepClone--) | Skapar en ny djupklon av den aktuella  Brush . |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Hämtar gradientvinkeln. |
| [getBlend()](#getBlend--) | Hämtar en  Aspose.Imaging.Blend  som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getEndColor()](#getEndColor--) | Hämtar den avslutande gradientfärgen. |
| [getGammaCorrection()](#getGammaCorrection--) | Hämtar ett värde som indikerar om gamma‑korrigering är aktiverad för detta  LinearGradientBrushBase . |
| [getInterpolationColors()](#getInterpolationColors--) | Hämtar en  com.aspose.psd.ColorBlend  som definierar en flerfärgad linjär gradient. |
| [getLinearColors()](#getLinearColors--) | Hämtar start- och slutfärgerna för gradienten. |
| [getOpacity()](#getOpacity--) | Hämtar penselns opacitet. |
| [getRectangle()](#getRectangle--) | Hämtar en rektangulär region som definierar start- och slutpunkterna för gradienten. |
| [getStartColor()](#getStartColor--) | Hämtar den startande gradientfärgen. |
| [getTransform()](#getTransform--) | Hämtar eller anger en kopia av  Aspose.Imaging.Matrix  som definierar en lokal geometrisk transformation för detta  TransformBrush . |
| [getWrapMode()](#getWrapMode--) | Hämtar eller anger en  Aspose.Imaging.WrapMode ‑enumeration som indikerar omslagsläget för detta  TransformBrush . |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | Hämtar ett värde som indikerar om  LinearGradientBrushBase.Angle  ändras under transformationer med detta  LinearGradientBrushBase . |
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
| [setAngle(float value)](#setAngle-float-) | Anger gradientvinkeln. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Anger ett värde som indikerar om  LinearGradientBrushBase.Angle  ändras under transformationer med detta  LinearGradientBrushBase . |
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Anger en  Aspose.Imaging.Blend  som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar. |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | Anger den avslutande gradientfärgen. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Anger ett värde som indikerar om gamma‑korrigering är aktiverad för detta  LinearGradientBrushBase . |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Anger en  com.aspose.psd.ColorBlend  som definierar en flerfärgad linjär gradient. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | Anger start- och slutfärgerna för gradienten. |
| [setOpacity(float value)](#setOpacity-float-) | Anger penselns opacitet. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Anger en rektangulär region som definierar start- och slutpunkterna för gradienten. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Skapar ett gradientavtagande baserat på en klockformad kurva. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Skapar ett gradientavtagande baserat på en klockformad kurva. |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | Anger den startande gradientfärgen. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Hämtar eller anger en kopia av  Aspose.Imaging.Matrix  som definierar en lokal geometrisk transformation för detta  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Hämtar eller anger en  Aspose.Imaging.WrapMode ‑enumeration som indikerar omslagsläget för detta  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Initierar en ny instans av  LinearGradientBrush  klassen med standardparametrar. Startfärgen är svart, slutfärgen är vit, vinkeln är 45 grader och rektangeln är placerad i (0,0) med storlek (1,1).

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Initierar en ny instans av  LinearGradientBrush  klassen med de angivna punkterna och färgerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | En  Aspose.Imaging.Point  struktur som representerar startpunkten för den linjära gradienten. |
| point2 | [Point](../../com.aspose.psd/point) | En  Aspose.Imaging.Point  struktur som representerar slutpunkten för den linjära gradienten. |
| color1 | [Color](../../com.aspose.psd/color) | En  com.aspose.psd.Color  struktur som representerar startfärgen för den linjära gradienten. |
| color2 | [Color](../../com.aspose.psd/color) | En  com.aspose.psd.Color  struktur som representerar den avslutande färgen för den linjära gradienten. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Initierar en ny instans av  LinearGradientBrush  klassen med de angivna punkterna och färgerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | En  Aspose.Imaging.PointF  struktur som representerar startpunkten för den linjära gradienten. |
| point2 | [PointF](../../com.aspose.psd/pointf) | En  Aspose.Imaging.PointF  struktur som representerar slutpunkten för den linjära gradienten. |
| color1 | [Color](../../com.aspose.psd/color) | En  com.aspose.psd.Color  struktur som representerar startfärgen för den linjära gradienten. |
| color2 | [Color](../../com.aspose.psd/color) | En  com.aspose.psd.Color  struktur som representerar den avslutande färgen för den linjära gradienten. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Initierar en ny instans av  LinearGradientBrush  klassen baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | En  Aspose.Imaging.RectangleF  struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](../../com.aspose.psd/color) | En  com.aspose.psd.Color  struktur som representerar startfärgen för gradienten. |
| color2 | [Color](../../com.aspose.psd/color) | En  com.aspose.psd.Color  struktur som representerar den avslutande färgen för gradienten. |
| angle | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Initierar en ny instans av  LinearGradientBrush  klassen baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | En  Aspose.Imaging.RectangleF  struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](../../com.aspose.psd/color) | En  com.aspose.psd.Color  struktur som representerar startfärgen för gradienten. |
| color2 | [Color](../../com.aspose.psd/color) | En  com.aspose.psd.Color  struktur som representerar den avslutande färgen för gradienten. |
| angle | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initierar en ny instans av  LinearGradientBrush  klassen baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | En  Aspose.Imaging.RectangleF  struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](../../com.aspose.psd/color) | En  com.aspose.psd.Color  struktur som representerar startfärgen för gradienten. |
| color2 | [Color](../../com.aspose.psd/color) | En  com.aspose.psd.Color  struktur som representerar den avslutande färgen för gradienten. |
| angle | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |
| isAngleScalable | boolean | om den är inställd på  true  ändras vinkeln under transformationer med denna  LinearGradientBrush . |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Initierar en ny instans av  LinearGradientBrush  klassen baserad på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | En  Aspose.Imaging.RectangleF  struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](../../com.aspose.psd/color) | En  com.aspose.psd.Color  struktur som representerar startfärgen för gradienten. |
| color2 | [Color](../../com.aspose.psd/color) | En  com.aspose.psd.Color  struktur som representerar den avslutande färgen för gradienten. |
| angle | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |
| isAngleScalable | boolean | om den är inställd på  true  ändras vinkeln under transformationer med denna  LinearGradientBrush . |

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


Hämtar gradientvinkeln.

**Returns:**
float - Gradientens vinkel.
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Hämtar en  Aspose.Imaging.Blend  som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten.

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


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean -  true  om frigjord; annars,  false .
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Hämtar den avslutande gradientfärgen.

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Hämtar ett värde som indikerar om gamma‑korrigering är aktiverad för detta  LinearGradientBrushBase .

**Returns:**
boolean - Värdet är true om gamma-korrigering är aktiverad för denna  LinearGradientBrushBase ; annars false.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Hämtar en  com.aspose.psd.ColorBlend  som definierar en flerfärgad linjär gradient.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Hämtar start- och slutfärgerna för gradienten.

**Returns:**
com.aspose.psd.Color[] - En array av två  Color  strukturer som representerar start- och slutfärgerna för gradienten.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Hämtar penselns opacitet. Värdet bör vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig.

**Returns:**
float - Penselns opacitetsvärde.
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Hämtar en rektangulär region som definierar start- och slutpunkterna för gradienten.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Hämtar den startande gradientfärgen.

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
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
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Hämtar ett värde som indikerar om  LinearGradientBrushBase.Angle  ändras under transformationer med detta  LinearGradientBrushBase .

**Returns:**
boolean -  true  om  LinearGradientBrushBase.Angle  ändras under transformationer med denna  LinearGradientBrushBase ; annars,  false .
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

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Anger gradientvinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Gradientvinkeln. |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Anger ett värde som indikerar om  LinearGradientBrushBase.Angle  ändras under transformationer med detta  LinearGradientBrushBase .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true om  LinearGradientBrushBase.Angle  ändras under transformationer med detta  LinearGradientBrushBase ; annars false. |

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


Anger en  Aspose.Imaging.Blend  som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | En  Aspose.Imaging.Blend  som representerar ett anpassat färgfall för gradienten. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde från 0 till 1 som anger mitten av gradienten (punkten där gradienten endast består av den avslutande färgen). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde från 0 till 1 som anger mitten av gradienten (punkten där gradienten endast består av den avslutande färgen). |
| skala | float | Ett värde från 0 till 1 som anger hur snabbt färgerna faller från startfärgen till  focus  (slutfärg) |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


Anger den avslutande gradientfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Den avslutande gradientfärgen. |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Anger ett värde som indikerar om gamma‑korrigering är aktiverad för detta  LinearGradientBrushBase .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Värdet är true om gammakorrigering är aktiverad för detta  LinearGradientBrushBase ; annars false. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Anger en  com.aspose.psd.ColorBlend  som definierar en flerfärgad linjär gradient.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | En  com.aspose.psd.ColorBlend  som definierar ett flerfärgslinjärt gradient. |

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


Anger start- och slutfärgerna för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | En array av två  Color  strukturer som representerar start- och slutfärgerna för gradienten. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Ställer in penselns opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Penselns opacitetsvärde. |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Anger en rektangulär region som definierar start- och slutpunkterna för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | En  com.aspose.psd.RectangleF  struktur som specificerar start- och slutpunkterna för gradienten. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Skapar ett gradientavtagande baserat på en klockformad kurva.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde från 0 till 1 som anger mitten av gradienten (punkten där startfärgen och slutfärgen blandas lika). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Skapar ett gradientavtagande baserat på en klockformad kurva.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde från 0 till 1 som anger mitten av gradienten (punkten där gradienten endast består av den avslutande färgen). |
| skala | float | Ett värde från 0 till 1 som anger hur snabbt färgerna faller från  focus . |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


Anger den startande gradientfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Den startande gradientfärgen. |

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

