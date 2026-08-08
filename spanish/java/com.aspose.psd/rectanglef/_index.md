---
title: "RectangleF"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Almacena un conjunto de cuatro números flotantes que representan la ubicación y el tamaño de un rectángulo."
type: docs
weight: 89
url: /es/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Almacena un conjunto de cuatro números flotantes que representan la ubicación y el tamaño de un rectángulo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Inicializa una nueva instancia de la estructura  com.aspose.psd.RectangleF  con la ubicación y el tamaño especificados. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Inicializa una nueva instancia de la estructura  com.aspose.psd.RectangleF  con la ubicación y el tamaño especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | Determina si el punto especificado está contenido dentro de esta estructura  com.aspose.psd.RectangleF . |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | Determina si la región rectangular representada por  rect  está completamente contenida dentro de esta estructura  com.aspose.psd.RectangleF . |
| [contains(float x, float y)](#contains-float-float-) | Determina si el punto especificado está contenido dentro de esta estructura  com.aspose.psd.RectangleF . |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | Divide los valores actuales del rectángulo para transformar los valores de escala vertical y horizontal de la matriz y devuelve una nueva instancia de [RectangleF](../../com.aspose.psd/rectanglef) con los valores resultantes. |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si  obj  es un  com.aspose.psd.RectangleF  con la misma ubicación y tamaño que este  com.aspose.psd.RectangleF . |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Crea una estructura  com.aspose.psd.RectangleF  con la esquina superior izquierda y la esquina inferior derecha en las ubicaciones especificadas. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Crea un nuevo  Rectangle  a partir de dos puntos especificados. |
| [getBottom()](#getBottom--) | Obtiene o establece la coordenada y que es la suma de  com.aspose.psd.RectangleF.Y  y  com.aspose.psd.RectangleF.Height  de esta estructura  com.aspose.psd.RectangleF . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Obtiene una nueva instancia de la estructura  com.aspose.psd.RectangleF  que tiene los valores  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  y  com.aspose.psd.RectangleF.Height  establecidos en cero. |
| [getHeight()](#getHeight--) | Obtiene o establece la altura de esta estructura  com.aspose.psd.RectangleF . |
| [getLeft()](#getLeft--) | Obtiene o establece la coordenada x del borde izquierdo de esta estructura  com.aspose.psd.RectangleF . |
| [getLocation()](#getLocation--) | Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura  com.aspose.psd.RectangleF . |
| [getRight()](#getRight--) | Obtiene o establece la coordenada x que es la suma de  com.aspose.psd.RectangleF.X  y  com.aspose.psd.RectangleF.Width  de esta estructura  com.aspose.psd.RectangleF . |
| [getSize()](#getSize--) | Obtiene o establece el tamaño de este  com.aspose.psd.RectangleF . |
| [getTop()](#getTop--) | Obtiene o establece la coordenada y del borde superior de esta estructura  com.aspose.psd.RectangleF . |
| [getWidth()](#getWidth--) | Obtiene o establece el ancho de esta estructura  com.aspose.psd.RectangleF . |
| [getX()](#getX--) | Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura  com.aspose.psd.RectangleF . |
| [getY()](#getY--) | Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura  com.aspose.psd.RectangleF . |
| [hashCode()](#hashCode--) | Obtiene el código hash de esta estructura  com.aspose.psd.RectangleF . |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | Crea y devuelve una copia inflada de la estructura  com.aspose.psd.RectangleF  especificada. |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | Infla este  com.aspose.psd.RectangleF  en la cantidad especificada. |
| [inflate(float x, float y)](#inflate-float-float-) | Infla esta estructura  com.aspose.psd.RectangleF  en la cantidad especificada. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Reemplaza esta estructura  com.aspose.psd.RectangleF  con la intersección de ella misma y la estructura  com.aspose.psd.RectangleF  especificada. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Devuelve una estructura  com.aspose.psd.RectangleF  que representa la intersección de dos rectángulos. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | Determina si este rectángulo intersecta con  rect . |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si la propiedad  com.aspose.psd.RectangleF.Width  o  com.aspose.psd.RectangleF.Height  de este  com.aspose.psd.RectangleF  tiene un valor de cero. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | Multiplica los valores actuales del rectángulo para transformar los valores de escala vertical y horizontal de la matriz y devuelve una nueva instancia de [RectangleF](../../com.aspose.psd/rectanglef) con los valores resultantes. |
| [normalize()](#normalize--) | Normaliza el rectángulo haciendo que su ancho y altura sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [offset(float x, float y)](#offset-float-float-) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | Implementa el operador /. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Comprueba si dos estructuras  com.aspose.psd.RectangleF  tienen la misma ubicación y tamaño. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Comprueba si dos estructuras  com.aspose.psd.RectangleF  difieren en ubicación o tamaño. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | Implementa el operador \*. |
| [setBottom(float value)](#setBottom-float-) | Obtiene o establece la coordenada y que es la suma de  com.aspose.psd.RectangleF.Y  y  com.aspose.psd.RectangleF.Height  de esta estructura  com.aspose.psd.RectangleF . |
| [setHeight(float value)](#setHeight-float-) | Obtiene o establece la altura de esta estructura  com.aspose.psd.RectangleF . |
| [setLeft(float value)](#setLeft-float-) | Obtiene o establece la coordenada x del borde izquierdo de esta estructura  com.aspose.psd.RectangleF . |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura  com.aspose.psd.RectangleF . |
| [setRight(float value)](#setRight-float-) | Obtiene o establece la coordenada x que es la suma de  com.aspose.psd.RectangleF.X  y  com.aspose.psd.RectangleF.Width  de esta estructura  com.aspose.psd.RectangleF . |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | Obtiene o establece el tamaño de este  com.aspose.psd.RectangleF . |
| [setTop(float value)](#setTop-float-) | Obtiene o establece la coordenada y del borde superior de esta estructura  com.aspose.psd.RectangleF . |
| [setWidth(float value)](#setWidth-float-) | Obtiene o establece el ancho de esta estructura  com.aspose.psd.RectangleF . |
| [setX(float value)](#setX-float-) | Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura  com.aspose.psd.RectangleF . |
| [setY(float value)](#setY-float-) | Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura  com.aspose.psd.RectangleF . |
| [toRectangle_internalized()](#toRectangle-internalized--) | Convierte un [RectangleF](../../com.aspose.psd/rectanglef) a una estructura [Rectangle](../../com.aspose.psd/rectangle) con valores de rectángulo truncados. |
| [toString()](#toString--) | Convierte los atributos de este  com.aspose.psd.RectangleF  a una cadena legible por humanos. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | Convierte la estructura  com.aspose.psd.Rectangle  especificada a una estructura  com.aspose.psd.RectangleF . |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Crea el tercer rectángulo más pequeño posible que pueda contener ambos rectángulos que forman una unión. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Inicializa una nueva instancia de la estructura  com.aspose.psd.RectangleF  con la ubicación y el tamaño especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo. |
| ancho | float | El ancho del rectángulo. |
| alto | float | La altura del rectángulo. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Inicializa una nueva instancia de la estructura  com.aspose.psd.RectangleF  con la ubicación y el tamaño especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | Un  com.aspose.psd.PointF  que representa la esquina superior izquierda de la región rectangular. |
| size | [SizeF](../../com.aspose.psd/sizef) | Un  com.aspose.psd.SizeF  que representa el ancho y la altura de la región rectangular. |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


Determina si el punto especificado está contenido dentro de esta estructura  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | El  com.aspose.psd.PointF  a probar. |

**Returns:**
boolean - Este método devuelve true si el punto representado por el parámetro  point  está contenido dentro de esta estructura  com.aspose.psd.RectangleF ; de lo contrario false.
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Determina si la región rectangular representada por  rect  está completamente contenida dentro de esta estructura  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | El  com.aspose.psd.RectangleF  a probar. |

**Returns:**
boolean - Este método devuelve true si la región rectangular representada por  rect  está completamente contenida dentro de la región rectangular representada por este  com.aspose.psd.RectangleF ; de lo contrario false.
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Determina si el punto especificado está contenido dentro de esta estructura  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns:**
boolean - Este método devuelve true si el punto definido por  x  y  y  está contenido dentro de esta estructura  com.aspose.psd.RectangleF ; de lo contrario false.
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| size | [SizeF](../../com.aspose.psd/sizef) |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### divideToTransformMatrix_internalized(double[] transformMatrix) {#divideToTransformMatrix-internalized-double---}
```
public final RectangleF divideToTransformMatrix_internalized(double[] transformMatrix)
```


Divide los valores actuales del rectángulo para transformar los valores de escala vertical y horizontal de la matriz y devuelve una nueva instancia de [RectangleF](../../com.aspose.psd/rectanglef) con los valores resultantes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| transformMatrix | double[] | La matriz de transformación de la capa. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprueba si  obj  es un  com.aspose.psd.RectangleF  con la misma ubicación y tamaño que este  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El  System.Object  a probar. |

**Returns:**
boolean - Este método devuelve true si  obj  es un  com.aspose.psd.RectangleF  y sus propiedades X, Y, Width y Height son iguales a las propiedades correspondientes de este  com.aspose.psd.RectangleF ; de lo contrario, false.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Crea una estructura  com.aspose.psd.RectangleF  con la esquina superior izquierda y la esquina inferior derecha en las ubicaciones especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | float | La coordenada x de la esquina superior izquierda de la región rectangular. |
| top | float | La coordenada y de la esquina superior izquierda de la región rectangular. |
| right | float | La coordenada x de la esquina inferior derecha de la región rectangular. |
| bottom | float | La coordenada y de la esquina inferior derecha de la región rectangular. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Crea un nuevo Rectangle a partir de dos puntos especificados. Dos vértices del Rectangle creado serán iguales a los puntos point1 y point2 pasados. Estos serían típicamente los vértices opuestos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | El primer Point para el nuevo rectángulo. |
| point2 | [PointF](../../com.aspose.psd/pointf) | El segundo Point para el nuevo rectángulo. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


Obtiene o establece la coordenada y que es la suma de  com.aspose.psd.RectangleF.Y  y  com.aspose.psd.RectangleF.Height  de esta estructura  com.aspose.psd.RectangleF .

**Returns:**
float - La coordenada y que es la suma de com.aspose.psd.RectangleF.Y y com.aspose.psd.RectangleF.Height de esta estructura com.aspose.psd.RectangleF.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Obtiene una nueva instancia de la estructura  com.aspose.psd.RectangleF  que tiene los valores  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  y  com.aspose.psd.RectangleF.Height  establecidos en cero.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


Obtiene o establece la altura de esta estructura  com.aspose.psd.RectangleF .

**Returns:**
float - La altura de esta estructura com.aspose.psd.RectangleF.
### getLeft() {#getLeft--}
```
public float getLeft()
```


Obtiene o establece la coordenada x del borde izquierdo de esta estructura  com.aspose.psd.RectangleF .

**Returns:**
float - La coordenada x del borde izquierdo de esta estructura com.aspose.psd.RectangleF.
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura  com.aspose.psd.RectangleF .

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


Obtiene o establece la coordenada x que es la suma de  com.aspose.psd.RectangleF.X  y  com.aspose.psd.RectangleF.Width  de esta estructura  com.aspose.psd.RectangleF .

**Returns:**
float - La coordenada x que es la suma de com.aspose.psd.RectangleF.X y com.aspose.psd.RectangleF.Width de esta estructura com.aspose.psd.RectangleF.
### getSize() {#getSize--}
```
public SizeF getSize()
```


Obtiene o establece el tamaño de este  com.aspose.psd.RectangleF .

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


Obtiene o establece la coordenada y del borde superior de esta estructura  com.aspose.psd.RectangleF .

**Returns:**
float - La coordenada y del borde superior de esta estructura com.aspose.psd.RectangleF.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Obtiene o establece el ancho de esta estructura  com.aspose.psd.RectangleF .

**Returns:**
float - El ancho de esta estructura com.aspose.psd.RectangleF.
### getX() {#getX--}
```
public float getX()
```


Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura  com.aspose.psd.RectangleF .

**Returns:**
float - La coordenada x de la esquina superior izquierda de esta estructura com.aspose.psd.RectangleF.
### getY() {#getY--}
```
public float getY()
```


Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura  com.aspose.psd.RectangleF .

**Returns:**
float - La coordenada y de la esquina superior izquierda de esta estructura com.aspose.psd.RectangleF.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash de esta estructura  com.aspose.psd.RectangleF .

**Returns:**
int - El código hash de este com.aspose.psd.RectangleF.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Crea y devuelve una copia inflada de la estructura com.aspose.psd.RectangleF especificada. La copia se infla en la cantidad especificada. El rectángulo original permanece sin modificar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | El com.aspose.psd.RectangleF a copiar. Este rectángulo no se modifica. |
| x | float | La cantidad para inflar horizontalmente la copia del rectángulo. |
| y | float | La cantidad para inflar verticalmente la copia del rectángulo. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


Infla este  com.aspose.psd.RectangleF  en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | La cantidad para inflar este rectángulo. |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Infla esta estructura  com.aspose.psd.RectangleF  en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La cantidad para inflar horizontalmente esta estructura com.aspose.psd.RectangleF. |
| y | float | La cantidad para inflar verticalmente esta estructura com.aspose.psd.RectangleF. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Reemplaza esta estructura  com.aspose.psd.RectangleF  con la intersección de ella misma y la estructura  com.aspose.psd.RectangleF  especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | El rectángulo a intersectar. |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Devuelve una estructura com.aspose.psd.RectangleF que representa la intersección de dos rectángulos. Si no hay intersección, se devuelve un com.aspose.psd.RectangleF vacío.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Un primer rectángulo a intersectar. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Un segundo rectángulo a intersectar. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Determina si este rectángulo intersecta con  rect .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | El rectángulo a probar. |

**Returns:**
boolean - Este método devuelve true si hay alguna intersección.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtiene un valor que indica si la propiedad  com.aspose.psd.RectangleF.Width  o  com.aspose.psd.RectangleF.Height  de este  com.aspose.psd.RectangleF  tiene un valor de cero.

**Returns:**
boolean - Esta propiedad devuelve true si la propiedad com.aspose.psd.RectangleF.Width o com.aspose.psd.RectangleF.Height de este com.aspose.psd.RectangleF tiene un valor de cero; de lo contrario, false.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


Multiplica los valores actuales del rectángulo para transformar los valores de escala vertical y horizontal de la matriz y devuelve una nueva instancia de [RectangleF](../../com.aspose.psd/rectanglef) con los valores resultantes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| transformMatrix | double[] | La matriz de transformación de la capa. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
### normalize() {#normalize--}
```
public void normalize()
```


Normaliza el rectángulo haciendo que su ancho y altura sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | La cantidad para desplazar la ubicación. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La cantidad para desplazar la ubicación horizontalmente. |
| y | float | La cantidad para desplazar la ubicación verticalmente. |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Implementa el operador /.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | El rectángulo. |
| divisor | float | El divisor. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Comprueba si dos estructuras  com.aspose.psd.RectangleF  tienen la misma ubicación y tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | La estructura com.aspose.psd.RectangleF que está a la izquierda del operador de igualdad. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | La estructura com.aspose.psd.RectangleF que está a la derecha del operador de igualdad. |

**Returns:**
boolean - Este operador devuelve true si las dos estructuras com.aspose.psd.RectangleF especificadas tienen iguales las propiedades com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width y com.aspose.psd.RectangleF.Height.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Comprueba si dos estructuras  com.aspose.psd.RectangleF  difieren en ubicación o tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | La estructura com.aspose.psd.RectangleF que está a la izquierda del operador de desigualdad. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | La estructura com.aspose.psd.RectangleF que está a la derecha del operador de desigualdad. |

**Returns:**
boolean - Este operador devuelve true si cualquiera de las propiedades com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width o com.aspose.psd.RectangleF.Height de las dos estructuras com.aspose.psd.RectangleF son diferentes; de lo contrario, false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Implementa el operador \*.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | El rectángulo. |
| multiplicador | float | El multiplicador. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Obtiene o establece la coordenada y que es la suma de  com.aspose.psd.RectangleF.Y  y  com.aspose.psd.RectangleF.Height  de esta estructura  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Obtiene o establece la altura de esta estructura  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Obtiene o establece la coordenada x del borde izquierdo de esta estructura  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


Obtiene o establece las coordenadas de la esquina superior izquierda de esta estructura  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Obtiene o establece la coordenada x que es la suma de  com.aspose.psd.RectangleF.X  y  com.aspose.psd.RectangleF.Width  de esta estructura  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


Obtiene o establece el tamaño de este  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Obtiene o establece la coordenada y del borde superior de esta estructura  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Obtiene o establece el ancho de esta estructura  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Obtiene o establece la coordenada x de la esquina superior izquierda de esta estructura  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Obtiene o establece la coordenada y de la esquina superior izquierda de esta estructura  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


Convierte un [RectangleF](../../com.aspose.psd/rectanglef) a una estructura [Rectangle](../../com.aspose.psd/rectangle) con valores de rectángulo truncados.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


Convierte los atributos de este  com.aspose.psd.RectangleF  a una cadena legible por humanos.

**Returns:**
java.lang.String - Una cadena que contiene la posición, el ancho y la altura de esta estructura com.aspose.psd.RectangleF.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Convierte la estructura  com.aspose.psd.Rectangle  especificada a una estructura  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | La estructura com.aspose.psd.Rectangle a convertir. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Crea el tercer rectángulo más pequeño posible que pueda contener ambos rectángulos que forman una unión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Un primer rectángulo para unir. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Un segundo rectángulo para unir. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure that contains both of the two rectangles that form the union.
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

