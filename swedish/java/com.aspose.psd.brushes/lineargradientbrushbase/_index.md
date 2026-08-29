---
title: "LinearGradientBrushBase"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar en pensel med gradientfunktioner och lämpliga egenskaper."
type: docs
weight: 12
url: /sv/java/com.aspose.psd.brushes/lineargradientbrushbase/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush)
```
public abstract class LinearGradientBrushBase extends TransformBrush
```

Representerar en  Brush  med gradientfunktioner och lämpliga egenskaper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [deepClone()](#deepClone--) | Skapar en ny djupklon av den aktuella  Brush . |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Hämtar gradientvinkeln. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getGammaCorrection()](#getGammaCorrection--) | Hämtar ett värde som indikerar om gamma‑korrigering är aktiverad för detta  LinearGradientBrushBase . |
| [getOpacity()](#getOpacity--) | Hämtar penselns opacitet. |
| [getRectangle()](#getRectangle--) | Hämtar en rektangulär region som definierar start- och slutpunkterna för gradienten. |
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
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Anger ett värde som indikerar om gamma‑korrigering är aktiverad för detta  LinearGradientBrushBase . |
| [setOpacity(float value)](#setOpacity-float-) | Anger penselns opacitet. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Anger en rektangulär region som definierar start- och slutpunkterna för gradienten. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Hämtar eller anger en kopia av  Aspose.Imaging.Matrix  som definierar en lokal geometrisk transformation för detta  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Hämtar eller anger en  Aspose.Imaging.WrapMode ‑enumeration som indikerar omslagsläget för detta  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Hämtar ett värde som indikerar om gamma‑korrigering är aktiverad för detta  LinearGradientBrushBase .

**Returns:**
boolean - Värdet är true om gamma-korrigering är aktiverad för denna  LinearGradientBrushBase ; annars false.
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

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Anger ett värde som indikerar om gamma‑korrigering är aktiverad för detta  LinearGradientBrushBase .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Värdet är true om gammakorrigering är aktiverad för detta  LinearGradientBrushBase ; annars false. |

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

