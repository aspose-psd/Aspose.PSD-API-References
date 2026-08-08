---
title: "PathGradientBrush"
second_title: "Aspose.PSD för Java API-referens"
description: "Inkapslar ett Aspose.Imaging.Brush-objekt med en gradient."
type: docs
weight: 14
url: /sv/java/com.aspose.psd.brushes/pathgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Inkapslar ett  Aspose.Imaging.Brush  -objekt med en gradient. Denna klass kan inte ärvas.

Mittfärgen är vit som standard. En användare kan ändra detta värde när som helst senare.

Omringningsfärgernas array initieras med ett enda element som innehåller vit färg som standard. Omringningsfärgerna kan ändras senare, men minst ett element krävs när omringningsfärgerna konfigureras.

Se  Blend  för mer detaljer om dess initiering.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.psd.PointF---) | Initierar en ny instans av klassen  PathGradientBrush  med de angivna punkterna. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.PointF---int-) | Initierar en ny instans av klassen  PathGradientBrush  med de angivna punkterna och omslagsläget. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.psd.Point---) | Initierar en ny instans av klassen  PathGradientBrush  med de angivna punkterna. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.Point---int-) | Initierar en ny instans av klassen  PathGradientBrush  med de angivna punkterna och omslagsläget. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.psd.GraphicsPath-) | Initierar en ny instans av klassen  PathGradientBrush  med den angivna sökvägen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [deepClone()](#deepClone--) | Skapar en ny djupklon av den aktuella  Brush . |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlend()](#getBlend--) | Hämtar en  Aspose.Imaging.Blend  som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [getCenterColor()](#getCenterColor--) | Hämtar färgen i mitten av sökvägsgradienten. |
| [getCenterPoint()](#getCenterPoint--) | Hämtar eller anger centrumpunkten för path‑gradienten. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getFocusScales()](#getFocusScales--) | Hämtar fokuspunkten för gradientens avtagande. |
| [getGraphicsPath()](#getGraphicsPath--) | Hämtar grafikbanan som denna pensel byggdes på. |
| [getInterpolationColors()](#getInterpolationColors--) | Hämtar en  com.aspose.psd.ColorBlend  som definierar en flerfärgad linjär gradient. |
| [getOpacity()](#getOpacity--) | Hämtar penselns opacitet. |
| [getPathPoints()](#getPathPoints--) | Hämtar banpunkterna som denna pensel byggdes på. |
| [getSurroundColors()](#getSurroundColors--) | Hämtar en array av färger som motsvarar punkterna i den bana som denna  PathGradientBrush  fyller. |
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
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Anger en  Aspose.Imaging.Blend  som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Skapar en gradient med en mittfärg och en linjär avtagning till en omgivande färg. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Skapar en gradient med en mittfärg och en linjär avtagning till varje omgivande färg. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.psd.Color-) | Ställer in färgen i mitten av banans gradient. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | Hämtar eller anger centrumpunkten för path‑gradienten. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | Hämtar eller anger fokuspunkten för gradientens avtagande. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Anger en  com.aspose.psd.ColorBlend  som definierar en flerfärgad linjär gradient. |
| [setOpacity(float value)](#setOpacity-float-) | Anger penselns opacitet. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Skapar en gradientpensel som ändrar färg från banans mitt och utåt till banans gräns. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Skapar en gradientpensel som ändrar färg från banans mitt och utåt till banans gräns. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.psd.Color---) | Ställer in en array av färger som motsvarar punkterna i den bana som denna  PathGradientBrush  fyller. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Hämtar eller anger en kopia av  Aspose.Imaging.Matrix  som definierar en lokal geometrisk transformation för detta  TransformBrush . |
| [setWrapMode(int value)](#setWrapMode-int-) | Hämtar eller anger en  Aspose.Imaging.WrapMode ‑enumeration som indikerar omslagsläget för detta  TransformBrush . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.psd.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Initierar en ny instans av klassen  PathGradientBrush  med de angivna punkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | En matris av  Aspose.Imaging.PointF  strukturer som representerar de punkter som bildar hörnen på sökvägen. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Initierar en ny instans av klassen  PathGradientBrush  med de angivna punkterna och omslagsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | En matris av  Aspose.Imaging.PointF  strukturer som representerar de punkter som bildar hörnen på sökvägen. |
| wrapMode | int | En  Aspose.Imaging.WrapMode  som specificerar hur fyllningar ritade med denna  PathGradientBrush  upprepas. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.psd.Point---}
```
public PathGradientBrush(Point[] points)
```


Initierar en ny instans av klassen  PathGradientBrush  med de angivna punkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | En matris av  Aspose.Imaging.Point  strukturer som representerar de punkter som bildar hörnen på sökvägen. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Initierar en ny instans av klassen  PathGradientBrush  med de angivna punkterna och omslagsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | En matris av  Aspose.Imaging.Point  strukturer som representerar de punkter som bildar hörnen på sökvägen. |
| wrapMode | int | En  Aspose.Imaging.WrapMode  som specificerar hur fyllningar ritade med denna  PathGradientBrush  upprepas. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Initierar en ny instans av klassen  PathGradientBrush  med den angivna sökvägen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Den  GraphicsPath  som definierar området som fylls av denna  PathGradientBrush . |

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Hämtar en  Aspose.Imaging.Blend  som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Hämtar färgen i mitten av sökvägsgradienten.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  that represents the color at the center of the path gradient.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Hämtar eller anger centrumpunkten för path‑gradienten.

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


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean -  true  om frigjord; annars,  false .
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Hämtar fokuspunkten för gradientens avtagande.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Hämtar grafikbanan som denna pensel byggdes på.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Hämtar en  com.aspose.psd.ColorBlend  som definierar en flerfärgad linjär gradient.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Hämtar penselns opacitet. Värdet bör vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig.

**Returns:**
float - Penselns opacitetsvärde.
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Hämtar banpunkterna som denna pensel byggdes på.

**Returns:**
com.aspose.psd.PointF[] - Sökvägspunkterna.
### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Hämtar en array av färger som motsvarar punkterna i den bana som denna  PathGradientBrush  fyller.

**Returns:**
com.aspose.psd.Color[] - En array av  com.aspose.psd.Color  strukturer som representerar färgerna som är associerade med varje punkt i den bana som denna  PathGradientBrush  fyller.
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


Skapar en gradient med en mittfärg och en linjär avtagning till en omgivande färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde från 0 till 1 som specificerar var, längs någon radie från banans mitt till banans gräns, mittfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans mitt. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Skapar en gradient med en mittfärg och en linjär avtagning till varje omgivande färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde från 0 till 1 som specificerar var, längs någon radie från banans mitt till banans gräns, mittfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans mitt. |
| skala | float | Ett värde från 0 till 1 som specificerar den maximala intensiteten för mittfärgen som blandas med gränsfärgen. Ett värde på 1 ger den högsta möjliga intensiteten för mittfärgen, och det är standardvärdet. |

### setCenterColor(Color value) {#setCenterColor-com.aspose.psd.Color-}
```
public void setCenterColor(Color value)
```


Ställer in färgen i mitten av banans gradient.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | En  com.aspose.psd.Color  som representerar färgen i mitten av banans gradient. |

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


Hämtar eller anger centrumpunkten för path‑gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | En  Aspose.Imaging.PointF  som representerar mittpunkten för sökvägsgradienten. |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


Hämtar eller anger fokuspunkten för gradientens avtagande.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | En  Aspose.Imaging.PointF  som representerar fokuspunkten för gradientens avtagande. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Anger en  com.aspose.psd.ColorBlend  som definierar en flerfärgad linjär gradient.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | En  com.aspose.psd.ColorBlend  som definierar ett flerfärgslinjärt gradient. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Ställer in penselns opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Penselns opacitetsvärde. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Skapar en gradientpensel som ändrar färg från banans mitt och utåt till banans gräns. Övergången från en färg till en annan baseras på en klockformad kurva.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde från 0 till 1 som specificerar var, längs någon radie från banans mitt till banans gräns, mittfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans mitt. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Skapar en gradientpensel som ändrar färg från banans mitt och utåt till banans gräns. Övergången från en färg till en annan baseras på en klockformad kurva.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fokus | float | Ett värde från 0 till 1 som specificerar var, längs någon radie från banans mitt till banans gräns, mittfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans mitt. |
| skala | float | Ett värde från 0 till 1 som specificerar den maximala intensiteten för mittfärgen som blandas med gränsfärgen. Ett värde på 1 ger den högsta möjliga intensiteten för mittfärgen, och det är standardvärdet. |

### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.psd.Color---}
```
public void setSurroundColors(Color[] value)
```


Ställer in en array av färger som motsvarar punkterna i den bana som denna  PathGradientBrush  fyller.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | En array av  com.aspose.psd.Color  strukturer som representerar färgerna som är associerade med varje punkt i den bana som denna  PathGradientBrush  fyller. |

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

