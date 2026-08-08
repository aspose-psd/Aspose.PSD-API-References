---
title: "LinearGradientBrush"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Encapsula un Aspose.Imaging.Brush con un degradado lineal."
type: docs
weight: 11
url: /es/java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Encapsula un Aspose.Imaging.Brush con un degradado lineal. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | Inicializa una nueva instancia de la clase LinearGradientBrush con parámetros predeterminados. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | Inicializa una nueva instancia de la clase LinearGradientBrush con los puntos y colores especificados. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | Inicializa una nueva instancia de la clase LinearGradientBrush con los puntos y colores especificados. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Inicializa una nueva instancia de la clase LinearGradientBrush basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Inicializa una nueva instancia de la clase LinearGradientBrush basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Inicializa una nueva instancia de la clase LinearGradientBrush basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Inicializa una nueva instancia de la clase LinearGradientBrush basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación. |
## Métodos

| Método | Descripción |
| --- | --- |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [deepClone()](#deepClone--) | Crea una nueva clonación profunda del Brush actual. |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Obtiene el ángulo del degradado. |
| [getBlend()](#getBlend--) | Obtiene un Aspose.Imaging.Blend que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getEndColor()](#getEndColor--) | Obtiene el color final del degradado. |
| [getGammaCorrection()](#getGammaCorrection--) | Obtiene un valor que indica si la corrección gamma está habilitada para este LinearGradientBrushBase. |
| [getInterpolationColors()](#getInterpolationColors--) | Obtiene un com.aspose.psd.ColorBlend que define un degradado lineal multicolor. |
| [getLinearColors()](#getLinearColors--) | Obtiene los colores de inicio y fin del degradado. |
| [getOpacity()](#getOpacity--) | Obtiene la opacidad del pincel. |
| [getRectangle()](#getRectangle--) | Obtiene una región rectangular que define los puntos de inicio y fin del degradado. |
| [getStartColor()](#getStartColor--) | Obtiene el color inicial del degradado. |
| [getTransform()](#getTransform--) | Obtiene o establece una copia de Aspose.Imaging.Matrix que define una transformación geométrica local para este TransformBrush. |
| [getWrapMode()](#getWrapMode--) | Obtiene o establece una enumeración Aspose.Imaging.WrapMode que indica el modo de ajuste para este TransformBrush. |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | Obtiene un valor que indica si LinearGradientBrushBase.Angle se modifica durante las transformaciones con este LinearGradientBrushBase. |
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
| [setAngle(float value)](#setAngle-float-) | Establece el ángulo del degradado. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Establece un valor que indica si LinearGradientBrushBase.Angle se modifica durante las transformaciones con este LinearGradientBrushBase. |
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Establece un Aspose.Imaging.Blend que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos. |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | Establece el color final del degradado. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Establece un valor que indica si la corrección gamma está habilitada para este LinearGradientBrushBase. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Establece un com.aspose.psd.ColorBlend que define un degradado lineal multicolor. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | Establece los colores de inicio y fin del degradado. |
| [setOpacity(float value)](#setOpacity-float-) | Establece la opacidad del pincel. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Establece una región rectangular que define los puntos de inicio y fin del degradado. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crea una caída de degradado basada en una curva en forma de campana. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crea una caída de degradado basada en una curva en forma de campana. |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | Establece el color inicial del degradado. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Obtiene o establece una copia de Aspose.Imaging.Matrix que define una transformación geométrica local para este TransformBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtiene o establece una enumeración Aspose.Imaging.WrapMode que indica el modo de ajuste para este TransformBrush. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Traslada la transformación geométrica local por las dimensiones especificadas. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Inicializa una nueva instancia de la  LinearGradientBrush  clase con parámetros predeterminados. El color inicial es negro, el color final es blanco, el ángulo es de 45 grados y el rectángulo está ubicado en (0,0) con tamaño (1,1).

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Inicializa una nueva instancia de la clase LinearGradientBrush con los puntos y colores especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Una estructura Aspose.Imaging.Point que representa el punto inicial del degradado lineal. |
| point2 | [Point](../../com.aspose.psd/point) | Una estructura Aspose.Imaging.Point que representa el punto final del degradado lineal. |
| color1 | [Color](../../com.aspose.psd/color) | Una  com.aspose.psd.Color  estructura que representa el color inicial del degradado lineal. |
| color2 | [Color](../../com.aspose.psd/color) | Una  com.aspose.psd.Color  estructura que representa el color final del degradado lineal. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Inicializa una nueva instancia de la clase LinearGradientBrush con los puntos y colores especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Una estructura Aspose.Imaging.PointF que representa el punto inicial del degradado lineal. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Una estructura Aspose.Imaging.PointF que representa el punto final del degradado lineal. |
| color1 | [Color](../../com.aspose.psd/color) | Una  com.aspose.psd.Color  estructura que representa el color inicial del degradado lineal. |
| color2 | [Color](../../com.aspose.psd/color) | Una  com.aspose.psd.Color  estructura que representa el color final del degradado lineal. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Inicializa una nueva instancia de la clase LinearGradientBrush basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Una estructura Aspose.Imaging.RectangleF que especifica los límites del degradado lineal. |
| color1 | [Color](../../com.aspose.psd/color) | Una  com.aspose.psd.Color  estructura que representa el color inicial para el degradado. |
| color2 | [Color](../../com.aspose.psd/color) | Una  com.aspose.psd.Color  estructura que representa el color final para el degradado. |
| angle | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Inicializa una nueva instancia de la clase LinearGradientBrush basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Una estructura Aspose.Imaging.RectangleF que especifica los límites del degradado lineal. |
| color1 | [Color](../../com.aspose.psd/color) | Una  com.aspose.psd.Color  estructura que representa el color inicial para el degradado. |
| color2 | [Color](../../com.aspose.psd/color) | Una  com.aspose.psd.Color  estructura que representa el color final para el degradado. |
| angle | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Inicializa una nueva instancia de la clase LinearGradientBrush basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Una estructura Aspose.Imaging.RectangleF que especifica los límites del degradado lineal. |
| color1 | [Color](../../com.aspose.psd/color) | Una  com.aspose.psd.Color  estructura que representa el color inicial para el degradado. |
| color2 | [Color](../../com.aspose.psd/color) | Una  com.aspose.psd.Color  estructura que representa el color final para el degradado. |
| angle | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |
| isAngleScalable | boolean | si se establece en  true  el ángulo se cambia durante las transformaciones con este  LinearGradientBrush . |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Inicializa una nueva instancia de la clase LinearGradientBrush basada en un rectángulo, colores de inicio y fin, y un ángulo de orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Una estructura Aspose.Imaging.RectangleF que especifica los límites del degradado lineal. |
| color1 | [Color](../../com.aspose.psd/color) | Una  com.aspose.psd.Color  estructura que representa el color inicial para el degradado. |
| color2 | [Color](../../com.aspose.psd/color) | Una  com.aspose.psd.Color  estructura que representa el color final para el degradado. |
| angle | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |
| isAngleScalable | boolean | si se establece en  true  el ángulo se cambia durante las transformaciones con este  LinearGradientBrush . |

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


Obtiene el ángulo del degradado.

**Returns:**
float - El ángulo del degradado.
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Obtiene un Aspose.Imaging.Blend que especifica posiciones y factores que definen una caída personalizada para el degradado.

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


Obtiene un valor que indica si esta instancia está eliminada.

**Returns:**
boolean -  true  si está eliminado; de lo contrario,  false .
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Obtiene el color final del degradado.

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Obtiene un valor que indica si la corrección gamma está habilitada para este LinearGradientBrushBase.

**Returns:**
boolean - El valor es true si la corrección gamma está habilitada para este LinearGradientBrushBase; de lo contrario, false.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Obtiene un com.aspose.psd.ColorBlend que define un degradado lineal multicolor.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Obtiene los colores de inicio y fin del degradado.

**Returns:**
com.aspose.psd.Color[] - Una matriz de dos  Color  estructuras que representa los colores inicial y final del degradado.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Obtiene la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco.

**Returns:**
float - El valor de opacidad del pincel.
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Obtiene una región rectangular que define los puntos de inicio y fin del degradado.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Obtiene el color inicial del degradado.

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
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
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Obtiene un valor que indica si LinearGradientBrushBase.Angle se modifica durante las transformaciones con este LinearGradientBrushBase.

**Returns:**
boolean - true si LinearGradientBrushBase.Angle se cambia durante las transformaciones con este LinearGradientBrushBase; de lo contrario, false.
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

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Establece el ángulo del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El ángulo del degradado. |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Establece un valor que indica si LinearGradientBrushBase.Angle se modifica durante las transformaciones con este LinearGradientBrushBase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | true  si  LinearGradientBrushBase.Angle  se cambia durante las transformaciones con este  LinearGradientBrushBase ; de lo contrario,  false . |

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


Establece un Aspose.Imaging.Blend que especifica posiciones y factores que definen una caída personalizada para el degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | Una  Aspose.Imaging.Blend  que representa una caída personalizada para el degradado. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto solo del color final). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto solo del color final). |
| escala | float | Un valor de 0 a1 que especifica qué tan rápido los colores disminuyen del color inicial al  focus  (color final) |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


Establece el color final del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | El color final del degradado. |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Establece un valor que indica si la corrección gamma está habilitada para este LinearGradientBrushBase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | El valor es true si la corrección gamma está habilitada para este  LinearGradientBrushBase ; de lo contrario, false. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Establece un com.aspose.psd.ColorBlend que define un degradado lineal multicolor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | Un  com.aspose.psd.ColorBlend  que define un degradado lineal multicolor. |

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


Establece los colores de inicio y fin del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Una matriz de dos  Color  estructuras que representa los colores inicial y final del degradado. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El valor de opacidad del pincel. |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Establece una región rectangular que define los puntos de inicio y fin del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Una estructura  com.aspose.psd.RectangleF  que especifica los puntos de inicio y fin del degradado. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Crea una caída de degradado basada en una curva en forma de campana.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el color inicial y el color final se mezclan por igual). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crea una caída de degradado basada en una curva en forma de campana.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto solo del color final). |
| escala | float | Un valor de 0 a 1 que especifica qué tan rápido los colores disminuyen desde el  focus . |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


Establece el color inicial del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | El color inicial del degradado. |

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

