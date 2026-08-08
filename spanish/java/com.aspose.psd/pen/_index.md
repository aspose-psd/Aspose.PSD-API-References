---
title: "Pen"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Define un objeto utilizado para dibujar líneas, curvas y figuras."
type: docs
weight: 77
url: /es/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Define un objeto usado para dibujar líneas, curvas y figuras.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | Inicializa una nueva instancia de la clase  Pen  con el color especificado. |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | Inicializa una nueva instancia de la clase  Pen  con las propiedades especificadas  Color  y  Pen.Width . |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | Inicializa una nueva instancia de la clase  Pen  con el  Brush  especificado. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | Inicializa una nueva instancia de la clase  Pen  con el  Brush  y  Pen.Width  especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Obtiene la alineación de este  Pen . |
| [getBrush()](#getBrush--) | Obtiene el  Brush  que determina los atributos de este  Pen . |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Obtiene el color de este  Pen . |
| [getCompoundArray()](#getCompoundArray--) | Obtiene una matriz de valores que especifica un  Pen  compuesto. |
| [getCustomEndCap()](#getCustomEndCap--) | Obtiene una tapa personalizada para usar al final de las líneas dibujadas con este  Pen . |
| [getCustomStartCap()](#getCustomStartCap--) | Obtiene una tapa personalizada para usar al comienzo de las líneas dibujadas con este  Pen . |
| [getDashCap()](#getDashCap--) | Obtiene el estilo de tapa usado al final de los guiones que forman líneas discontinuas dibujadas con este  Pen . |
| [getDashOffset()](#getDashOffset--) | Obtiene la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |
| [getDashPattern()](#getDashPattern--) | Obtiene una matriz de guiones y espacios personalizados. |
| [getDashStyle()](#getDashStyle--) | Obtiene el estilo usado para líneas discontinuas dibujadas con este  Pen . |
| [getEndCap()](#getEndCap--) | Obtiene el estilo de tapa usado al final de las líneas dibujadas con este  Pen . |
| [getLineJoin()](#getLineJoin--) | Obtiene el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este  Pen . |
| [getMiterLimit()](#getMiterLimit--) | Obtiene el límite del grosor de la unión en una esquina en ángulo. |
| [getOpacity()](#getOpacity--) | Obtiene la opacidad del objeto. |
| [getPenType()](#getPenType--) | Obtiene el estilo de las líneas dibujadas con este  Pen . |
| [getStartCap()](#getStartCap--) | Obtiene el estilo de tapa usado al comienzo de las líneas dibujadas con este  Pen . |
| [getTransform()](#getTransform--) | Obtiene una copia de la transformación geométrica de este  Pen . |
| [getWidth()](#getWidth--) | Obtiene el ancho de este  Pen , en unidades del objeto Graphics utilizado para dibujar. |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multiplica la matriz de transformación de este  Pen  por la  Matrix  especificada . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multiplica la matriz de transformación de este  Pen  por la  Matrix  especificada en el orden especificado. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Restablece la matriz de transformación geométrica de este  Pen  a la identidad. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rota la transformación geométrica local por el ángulo especificado. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rota la transformación geométrica local por el ángulo especificado en el orden especificado. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Escala la transformación geométrica local por los factores especificados. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Escala la transformación geométrica local por los factores especificados en el orden especificado. |
| [setAlignment(int value)](#setAlignment-int-) | Establece la alineación para este  Pen . |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | Establece el  Brush  que determina los atributos de este  Pen . |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Establece el color de este  Pen . |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Establece una matriz de valores que especifica un pen compuesto. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | Establece una tapa personalizada para usar al final de las líneas dibujadas con este  Pen . |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | Establece una tapa personalizada para usar al comienzo de las líneas dibujadas con este  Pen . |
| [setDashCap(int value)](#setDashCap-int-) | Establece el estilo de tapa usado al final de los guiones que forman líneas discontinuas dibujadas con este  Pen . |
| [setDashOffset(float value)](#setDashOffset-float-) | Establece la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Establece una matriz de guiones y espacios personalizados. |
| [setDashStyle(int value)](#setDashStyle-int-) | Establece el estilo usado para líneas discontinuas dibujadas con este  Pen . |
| [setEndCap(int value)](#setEndCap-int-) | Establece el estilo de tapa usado al final de las líneas dibujadas con este  Pen . |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Establece los valores que determinan el estilo de tapa usado para terminar líneas dibujadas por este  Pen . |
| [setLineJoin(int value)](#setLineJoin-int-) | Establece el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este  Pen . |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Establece el límite del grosor de la unión en una esquina biselada. |
| [setOpacity(float value)](#setOpacity-float-) | Establece la opacidad del objeto. |
| [setStartCap(int value)](#setStartCap-int-) | Establece el estilo de tapa usado al comienzo de las líneas dibujadas con este  Pen . |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Establece una copia de la transformación geométrica para este  Pen . |
| [setWidth(float value)](#setWidth-float-) | Establece el ancho de este  Pen , en unidades del objeto Graphics usado para dibujar. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Traslada la transformación geométrica local por las dimensiones especificadas. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


Inicializa una nueva instancia de la clase  Pen  con el color especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Una estructura  Color  que indica el color de este  Pen . |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


Inicializa una nueva instancia de la clase  Pen  con las propiedades especificadas  Color  y  Pen.Width .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Una estructura  Color  que indica el color de este  Pen . |
| ancho | float | Un valor que indica el ancho de este  Pen . |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


Inicializa una nueva instancia de la clase  Pen  con el  Brush  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Un  Brush  que determina las propiedades de relleno de este  Pen . |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


Inicializa una nueva instancia de la clase  Pen  con el  Brush  y  Pen.Width  especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Un  Brush  que determina las características de este  Pen . |
| ancho | float | El ancho del nuevo  Pen . |

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Obtiene la alineación de este  Pen .

**Returns:**
int - Un  PenAlignment  que representa la alineación para este  Pen .
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Obtiene el  Brush  que determina los atributos de este  Pen .

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Obtiene el color de este  Pen .

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Obtiene una matriz de valores que especifica un Pen compuesto. Un Pen compuesto dibuja una línea compuesta formada por líneas paralelas y espacios.

**Returns:**
float[] - Una matriz de números reales que especifica la matriz compuesta. Los elementos de la matriz deben estar en orden creciente, no menores que 0 y no mayores que 1.
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Obtiene una tapa personalizada para usar al final de las líneas dibujadas con este  Pen .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Obtiene una tapa personalizada para usar al comienzo de las líneas dibujadas con este  Pen .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Obtiene el estilo de tapa usado al final de los guiones que forman líneas discontinuas dibujadas con este  Pen .

**Returns:**
int - Uno de los valores de  DashCap  que representa el estilo de tapa usado al principio y al final de los guiones que forman líneas discontinuas dibujadas con este  Pen .
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Obtiene la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones.

**Returns:**
float - La distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones.
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Obtiene una matriz de guiones y espacios personalizados.

**Returns:**
float[] - Una matriz de números reales que especifica las longitudes de guiones y espacios alternados en líneas discontinuas.
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Obtiene el estilo usado para líneas discontinuas dibujadas con este  Pen .

**Returns:**
int - Un  DashStyle  que representa el estilo usado para líneas discontinuas dibujadas con este  Pen .
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Obtiene el estilo de tapa usado al final de las líneas dibujadas con este  Pen .

**Returns:**
int - Uno de los valores de  LineCap  que representa el estilo de tapa usado al final de las líneas dibujadas con este  Pen .
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Obtiene el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este  Pen .

**Returns:**
int - Un  LineJoin  que representa el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este  Pen .
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Obtiene el límite del grosor de la unión en una esquina en ángulo.

**Returns:**
float - El límite del grosor de la unión en una esquina en inglete.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Obtiene la opacidad del objeto. El valor debe estar entre 0 y 1. Un valor de 0 significa que el objeto es totalmente visible, un valor de 1 significa que el objeto es totalmente opaco.

**Returns:**
float - El valor de opacidad.
### getPenType() {#getPenType--}
```
public int getPenType()
```


Obtiene el estilo de las líneas dibujadas con este  Pen .

**Returns:**
int - Una enumeración de  PenType  que especifica el estilo de líneas dibujadas con este  Pen .
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Obtiene el estilo de tapa usado al comienzo de las líneas dibujadas con este  Pen .

**Returns:**
int - Uno de los valores de  LineCap  que representa el estilo de tapa usado al principio de las líneas dibujadas con este  Pen .
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtiene una copia de la transformación geométrica de este  Pen .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


Obtiene el ancho de este  Pen , en unidades del objeto Graphics utilizado para dibujar.

**Returns:**
float - El ancho de este  Pen .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplica la matriz de transformación de este  Pen  por la  Matrix  especificada .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | El objeto  Matrix  por el cual multiplicar la matriz de transformación. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplica la matriz de transformación de este  Pen  por la  Matrix  especificada en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | La  Matrix  por la cual multiplicar la matriz de transformación. |
| orden | int | El orden en el que realizar la operación de multiplicación. |

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


Restablece la matriz de transformación geométrica de este  Pen  a la identidad.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Rota la transformación geométrica local por el ángulo especificado. Este método antepone la rotación a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rota la transformación geométrica local por el ángulo especificado en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación. |
| orden | int | Un  MatrixOrder  que especifica si se debe anexar o anteponer la matriz de rotación. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Escala la transformación geométrica local por los factores especificados. Este método antepone la matriz de escala a la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | El factor por el cual escalar la transformación en la dirección del eje x. |
| sy | float | El factor por el cual escalar la transformación en la dirección del eje y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Escala la transformación geométrica local por los factores especificados en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | El factor por el cual escalar la transformación en la dirección del eje x. |
| sy | float | El factor por el cual escalar la transformación en la dirección del eje y. |
| orden | int | Un  MatrixOrder  que especifica si se debe añadir o anteponer la matriz de escala. |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Establece la alineación para este  Pen .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Un  PenAlignment  que representa la alineación de este  Pen . |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


Establece el  Brush  que determina los atributos de este  Pen .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | Un  Brush  que determina los atributos de este  Pen . |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Establece el color de este  Pen .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Una estructura  Color  que representa el color de este  Pen . |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Establece una matriz de valores que especifica una Pen compuesta. Una Pen compuesta dibuja una línea compuesta formada por líneas paralelas y espacios.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float[] | Una matriz de números reales que especifica la matriz compuesta. Los elementos de la matriz deben estar en orden creciente, no ser menores que 0 y no ser mayores que 1. |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Establece una tapa personalizada para usar al final de las líneas dibujadas con este  Pen .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Un  CustomLineCap  que representa la tapa utilizada al final de las líneas dibujadas con este  Pen . |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Establece una tapa personalizada para usar al comienzo de las líneas dibujadas con este  Pen .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Un  CustomLineCap  que representa la tapa utilizada al comienzo de las líneas dibujadas con este  Pen . |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Establece el estilo de tapa usado al final de los guiones que forman líneas discontinuas dibujadas con este  Pen .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Uno de los valores de  DashCap  que representa el estilo de tapa usado al principio y al final de los guiones que forman las líneas discontinuas dibujadas con este  Pen . |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Establece la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | La distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Establece una matriz de guiones y espacios personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float[] | Una matriz de números reales que especifica las longitudes de guiones y espacios alternados en líneas discontinuas. |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Establece el estilo usado para líneas discontinuas dibujadas con este  Pen .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Un  DashStyle  que representa el estilo usado para líneas discontinuas dibujadas con este  Pen . |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Establece el estilo de tapa usado al final de las líneas dibujadas con este  Pen .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Uno de los valores de  LineCap  que representa el estilo de tapa usado al final de las líneas dibujadas con este  Pen . |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Establece los valores que determinan el estilo de tapa usado para terminar líneas dibujadas por este  Pen .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startCap | int | Un  LineCap  que representa el estilo de tapa a usar al comienzo de las líneas dibujadas con este  Pen . |
| endCap | int | Un  LineCap  que representa el estilo de tapa a usar al final de las líneas dibujadas con este  Pen . |
| dashCap | int | Un  LineCap  que representa el estilo de tapa a usar al comienzo o al final de líneas discontinuas dibujadas con este  Pen . |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Establece el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este  Pen .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Un  LineJoin  que representa el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este  Pen . |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Establece el límite del grosor de la unión en una esquina biselada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El límite del grosor de la unión en una esquina biselada. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Establece la opacidad del objeto. El valor debe estar entre 0 y 1. Un valor de 0 significa que el objeto es totalmente visible, un valor de 1 significa que el objeto es totalmente opaco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El valor de opacidad. |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Establece el estilo de tapa usado al comienzo de las líneas dibujadas con este  Pen .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Uno de los valores de  LineCap  que representa el estilo de tapa usado al comienzo de las líneas dibujadas con este  Pen . |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Establece una copia de la transformación geométrica para este  Pen .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Una copia de la  Matrix  que representa la transformación geométrica de este  Pen . |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Establece el ancho de este  Pen , en unidades del objeto Graphics usado para dibujar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El ancho de este  Pen . |

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

