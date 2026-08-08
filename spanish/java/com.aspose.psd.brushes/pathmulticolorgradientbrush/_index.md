---
title: "PathMulticolorGradientBrush"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Encapsula un objeto Aspose.Imaging.Brush con un degradado."
type: docs
weight: 16
url: /es/java/com.aspose.psd.brushes/pathmulticolorgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathMulticolorGradientBrush extends PathGradientBrushBase
```

Encapsula un objeto  Aspose.Imaging.Brush  con un degradado. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PathMulticolorGradientBrush(PointF[] points)](#PathMulticolorGradientBrush-com.aspose.psd.PointF---) | Inicializa una nueva instancia de la clase  PathMulticolorGradientBrush  con los puntos especificados. |
| [PathMulticolorGradientBrush(PointF[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.psd.PointF---int-) | Inicializa una nueva instancia de la clase  PathMulticolorGradientBrush  con los puntos especificados y el modo de ajuste. |
| [PathMulticolorGradientBrush(Point[] points)](#PathMulticolorGradientBrush-com.aspose.psd.Point---) | Inicializa una nueva instancia de la clase  PathMulticolorGradientBrush  con los puntos especificados. |
| [PathMulticolorGradientBrush(Point[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.psd.Point---int-) | Inicializa una nueva instancia de la clase  PathMulticolorGradientBrush  con los puntos especificados y el modo de ajuste. |
| [PathMulticolorGradientBrush(GraphicsPath path)](#PathMulticolorGradientBrush-com.aspose.psd.GraphicsPath-) | Inicializa una nueva instancia de la clase  PathMulticolorGradientBrush  con la ruta especificada. |
## Métodos

| Método | Descripción |
| --- | --- |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [deepClone()](#deepClone--) | Crea una nueva clonación profunda del Brush actual. |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCenterPoint()](#getCenterPoint--) | Obtiene o establece el punto central del degradado de ruta. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getFocusScales()](#getFocusScales--) | Obtiene el punto de foco para la caída del degradado. |
| [getGraphicsPath()](#getGraphicsPath--) | Obtiene la ruta gráfica en la que se construyó este pincel. |
| [getInterpolationColors()](#getInterpolationColors--) | Obtiene o establece un  com.aspose.psd.ColorBlend  que define un degradado lineal multicolor. |
| [getOpacity()](#getOpacity--) | Obtiene la opacidad del pincel. |
| [getPathPoints()](#getPathPoints--) | Obtiene los puntos de la ruta en la que se construyó este pincel. |
| [getTransform()](#getTransform--) | Obtiene o establece una copia de Aspose.Imaging.Matrix que define una transformación geométrica local para este TransformBrush. |
| [getWrapMode()](#getWrapMode--) | Obtiene o establece una enumeración Aspose.Imaging.WrapMode que indica el modo de ajuste para este TransformBrush. |
| [hashCode()](#hashCode--) |  |
| [isTransformChanged()](#isTransformChanged--) | Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multiplica la Aspose.Imaging.Matrix que representa la transformación geométrica local de este LinearGradientBrush por la Aspose.Imaging.Matrix especificada, anteponiendo la Aspose.Imaging.Matrix indicada. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multiplica la Aspose.Imaging.Matrix que representa la transformación geométrica local de este LinearGradientBrush por la Aspose.Imaging.Matrix especificada en el orden indicado. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Restablece la propiedad TransformBrush.Transform a la identidad. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rota la transformación geométrica local en la cantidad especificada. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rota la transformación geométrica local en la cantidad especificada en el orden indicado. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Escala la transformación geométrica local por las cantidades especificadas. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Escala la transformación geométrica local por las cantidades especificadas en el orden indicado. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | Obtiene o establece el punto central del degradado de ruta. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | Obtiene o establece el punto focal para la caída del degradado. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Obtiene o establece un  com.aspose.psd.ColorBlend  que define un degradado lineal multicolor. |
| [setOpacity(float value)](#setOpacity-float-) | Establece la opacidad del pincel. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Obtiene o establece una copia de Aspose.Imaging.Matrix que define una transformación geométrica local para este TransformBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtiene o establece una enumeración Aspose.Imaging.WrapMode que indica el modo de ajuste para este TransformBrush. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Traslada la transformación geométrica local por las dimensiones especificadas. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathMulticolorGradientBrush(PointF[] points) {#PathMulticolorGradientBrush-com.aspose.psd.PointF---}
```
public PathMulticolorGradientBrush(PointF[] points)
```


Inicializa una nueva instancia de la clase  PathMulticolorGradientBrush  con los puntos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Una matriz de estructuras  Aspose.Imaging.PointF  que representan los puntos que forman los vértices de la ruta. |

### PathMulticolorGradientBrush(PointF[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.psd.PointF---int-}
```
public PathMulticolorGradientBrush(PointF[] points, int wrapMode)
```


Inicializa una nueva instancia de la clase  PathMulticolorGradientBrush  con los puntos especificados y el modo de ajuste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Una matriz de estructuras  Aspose.Imaging.PointF  que representan los puntos que forman los vértices de la ruta. |
| wrapMode | int | Un  Aspose.Imaging.WrapMode  que especifica cómo se mosaican los rellenos dibujados con este  PathMulticolorGradientBrush . |

### PathMulticolorGradientBrush(Point[] points) {#PathMulticolorGradientBrush-com.aspose.psd.Point---}
```
public PathMulticolorGradientBrush(Point[] points)
```


Inicializa una nueva instancia de la clase  PathMulticolorGradientBrush  con los puntos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Una matriz de estructuras  Aspose.Imaging.Point  que representan los puntos que forman los vértices de la ruta. |

### PathMulticolorGradientBrush(Point[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.psd.Point---int-}
```
public PathMulticolorGradientBrush(Point[] points, int wrapMode)
```


Inicializa una nueva instancia de la clase  PathMulticolorGradientBrush  con los puntos especificados y el modo de ajuste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Una matriz de estructuras  Aspose.Imaging.Point  que representan los puntos que forman los vértices de la ruta. |
| wrapMode | int | Un  Aspose.Imaging.WrapMode  que especifica cómo se mosaican los rellenos dibujados con este  PathMulticolorGradientBrush . |

### PathMulticolorGradientBrush(GraphicsPath path) {#PathMulticolorGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathMulticolorGradientBrush(GraphicsPath path)
```


Inicializa una nueva instancia de la clase  PathMulticolorGradientBrush  con la ruta especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | El  GraphicsPath  que define el área rellenada por este  PathMulticolorGradientBrush . |

### close() {#close--}
```
public void close()
```


Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. Este método simplemente llama al método dispose.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Crea una nueva clonación profunda del Brush actual.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Descarta la instancia actual.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Obtiene o establece el punto central del degradado de ruta.

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


Obtiene un valor que indica si esta instancia está eliminada.

**Returns:**
boolean -  true  si está eliminado; de lo contrario,  false .
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Obtiene el punto de foco para la caída del degradado.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Obtiene la ruta gráfica en la que se construyó este pincel.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Obtiene o establece un  com.aspose.psd.ColorBlend  que define un degradado lineal multicolor.

Valor: Un  com.aspose.psd.ColorBlend  que define un degradado lineal multicolor.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend)
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Obtiene la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco.

**Returns:**
float - El valor de opacidad del pincel.
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Obtiene los puntos de la ruta en la que se construyó este pincel.

**Returns:**
com.aspose.psd.PointF[] - Los puntos de la ruta.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtiene o establece una copia de Aspose.Imaging.Matrix que define una transformación geométrica local para este TransformBrush.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtiene o establece una enumeración Aspose.Imaging.WrapMode que indica el modo de ajuste para este TransformBrush.

**Returns:**
int - Un Aspose.Imaging.WrapMode que especifica cómo se repiten los rellenos dibujados con este TransformBrush.
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


Obtiene un valor que indica si las transformaciones fueron modificadas de alguna manera. Por ejemplo, al establecer la matriz de transformación o al llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce para compatibilidad retroactiva con GDI+.

Valor: True si la transformación fue modificada; de lo contrario, false.

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplica la Aspose.Imaging.Matrix que representa la transformación geométrica local de este LinearGradientBrush por la Aspose.Imaging.Matrix especificada, anteponiendo la Aspose.Imaging.Matrix indicada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La Aspose.Imaging.Matrix por la cual multiplicar la transformación geométrica. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplica la Aspose.Imaging.Matrix que representa la transformación geométrica local de este LinearGradientBrush por la Aspose.Imaging.Matrix especificada en el orden indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La Aspose.Imaging.Matrix por la cual multiplicar la transformación geométrica. |
| orden | int | Una Aspose.Imaging.MatrixOrder que especifica en qué orden multiplicar las dos matrices. |

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


Restablece la propiedad TransformBrush.Transform a la identidad.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rota la transformación geométrica local por la cantidad especificada. Este método antepone la rotación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rota la transformación geométrica local en la cantidad especificada en el orden indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |
| orden | int | Una Aspose.Imaging.MatrixOrder que especifica si se debe anexar o anteponer la matriz de rotación. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Escala la transformación geométrica local por las cantidades especificadas. Este método antepone la matriz de escala a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | La cantidad por la que escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la que escalar la transformación en la dirección del eje y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Escala la transformación geométrica local por las cantidades especificadas en el orden indicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | La cantidad por la que escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la que escalar la transformación en la dirección del eje y. |
| orden | int | Un  Aspose.Imaging.MatrixOrder  que especifica si se debe añadir o anteponer la matriz de escala. |

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


Obtiene o establece el punto central del degradado de ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Un  Aspose.Imaging.PointF  que representa el punto central del degradado de la ruta. |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


Obtiene o establece el punto focal para la caída del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Un  Aspose.Imaging.PointF  que representa el punto focal para la caída del degradado. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Obtiene o establece un  com.aspose.psd.ColorBlend  que define un degradado lineal multicolor.

Valor: Un  com.aspose.psd.ColorBlend  que define un degradado lineal multicolor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El valor de opacidad del pincel. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Obtiene o establece una copia de Aspose.Imaging.Matrix que define una transformación geométrica local para este TransformBrush.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtiene o establece una enumeración Aspose.Imaging.WrapMode que indica el modo de ajuste para este TransformBrush.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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


Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |
| orden | int | El orden (anteponer o añadir) en el que aplicar la traslación. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

