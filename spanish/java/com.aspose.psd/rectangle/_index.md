---
title: "Rectángulo"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo."
type: docs
weight: 88
url: /es/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Inicializa una nueva instancia de la  com.aspose.psd.Rectangle  estructura con la ubicación y el tamaño especificados. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | Inicializa una nueva instancia de la  com.aspose.psd.Rectangle  estructura con la ubicación y el tamaño especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | Convierte la  com.aspose.psd.RectangleF  estructura especificada a una  com.aspose.psd.Rectangle  estructura redondeando los valores de  com.aspose.psd.RectangleF  al siguiente número entero superior. |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | Determina si el punto especificado está contenido dentro de esta  com.aspose.psd.Rectangle  estructura. |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | Determina si la región rectangular representada por  rect  está completamente contenida dentro de esta  com.aspose.psd.Rectangle  estructura. |
| [contains(int x, int y)](#contains-int-int-) | Determina si el punto especificado está contenido dentro de esta  com.aspose.psd.Rectangle  estructura. |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si  obj  es una  com.aspose.psd.Rectangle  estructura con la misma ubicación y tamaño que esta  com.aspose.psd.Rectangle  estructura. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Crea una  com.aspose.psd.Rectangle  estructura con las ubicaciones de borde especificadas. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | Crea un nuevo  Rectangle  a partir de dos puntos especificados. |
| [getBottom()](#getBottom--) | Obtiene o establece la coordenada y que es la suma de los valores de las propiedades  com.aspose.psd.Rectangle.Y  y  com.aspose.psd.Rectangle.Height  de esta  com.aspose.psd.Rectangle  estructura. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Obtiene una nueva instancia de la  com.aspose.psd.Rectangle  estructura que tiene los valores de  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  y  com.aspose.psd.Rectangle.Height  establecidos en cero. |
| [getHeight()](#getHeight--) | Obtiene o establece la altura de esta  com.aspose.psd.Rectangle  estructura. |
| [getLeft()](#getLeft--) | Obtiene o establece la coordenada x del borde izquierdo de esta  com.aspose.psd.Rectangle  estructura. |
| [getLocation()](#getLocation--) | Obtiene o establece las coordenadas de la esquina superior izquierda de esta  com.aspose.psd.Rectangle  estructura. |
| [getRight()](#getRight--) | Obtiene o establece la coordenada x que es la suma de los valores de las propiedades  com.aspose.psd.Rectangle.X  y  com.aspose.psd.Rectangle.Width  de esta  com.aspose.psd.Rectangle  estructura. |
| [getSize()](#getSize--) | Obtiene o establece el tamaño de esta  com.aspose.psd.Rectangle . |
| [getTop()](#getTop--) | Obtiene o establece la coordenada y del borde superior de esta  com.aspose.psd.Rectangle  estructura. |
| [getWidth()](#getWidth--) | Obtiene el ancho de esta  com.aspose.psd.Rectangle  estructura. |
| [getX()](#getX--) | Obtiene o establece la coordenada x de la esquina superior izquierda de esta  com.aspose.psd.Rectangle  estructura. |
| [getY()](#getY--) | Obtiene o establece la coordenada y de la esquina superior izquierda de esta  com.aspose.psd.Rectangle  estructura. |
| [hashCode()](#hashCode--) | Devuelve el código hash de esta  com.aspose.psd.Rectangle  estructura. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | Crea y devuelve una copia inflada de la  com.aspose.psd.Rectangle  estructura especificada. |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | Infla esta  com.aspose.psd.Rectangle  en la cantidad especificada. |
| [inflate(int width, int height)](#inflate-int-int-) | Infla esta  com.aspose.psd.Rectangle  en la cantidad especificada. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Reemplaza esta  com.aspose.psd.Rectangle  con la intersección de ella misma y la  com.aspose.psd.Rectangle  especificada. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Devuelve una tercera  com.aspose.psd.Rectangle  estructura que representa la intersección de dos  com.aspose.psd.Rectangle  estructuras adicionales. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | Determina si este rectángulo intersecta con  rect . |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si todas las propiedades numéricas de esta  com.aspose.psd.Rectangle  tienen valores cero. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | Obtiene un valor que indica si este  Rectangle  es al menos parcialmente visible |
| [normalize()](#normalize--) | Normaliza el rectángulo haciendo que su ancho y altura sean positivos, que la izquierda sea menor que la derecha y que la parte superior sea menor que la inferior. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [offset(int x, int y)](#offset-int-int-) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Comprueba si dos  com.aspose.psd.Rectangle  estructuras tienen la misma ubicación y tamaño. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Comprueba si dos estructuras  com.aspose.psd.Rectangle  difieren en ubicación o tamaño. |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | Convierte el  com.aspose.psd.RectangleF  especificado a un  com.aspose.psd.Rectangle  redondeando los valores del  com.aspose.psd.RectangleF  al entero más cercano. |
| [setBottom(int value)](#setBottom-int-) | Obtiene o establece la coordenada y que es la suma de los valores de las propiedades  com.aspose.psd.Rectangle.Y  y  com.aspose.psd.Rectangle.Height  de esta  com.aspose.psd.Rectangle  estructura. |
| [setHeight(int value)](#setHeight-int-) | Obtiene o establece la altura de esta  com.aspose.psd.Rectangle  estructura. |
| [setLeft(int value)](#setLeft-int-) | Obtiene o establece la coordenada x del borde izquierdo de esta  com.aspose.psd.Rectangle  estructura. |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | Obtiene o establece las coordenadas de la esquina superior izquierda de esta  com.aspose.psd.Rectangle  estructura. |
| [setRight(int value)](#setRight-int-) | Obtiene o establece la coordenada x que es la suma de los valores de las propiedades  com.aspose.psd.Rectangle.X  y  com.aspose.psd.Rectangle.Width  de esta  com.aspose.psd.Rectangle  estructura. |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | Obtiene o establece el tamaño de esta  com.aspose.psd.Rectangle . |
| [setTop(int value)](#setTop-int-) | Obtiene o establece la coordenada y del borde superior de esta  com.aspose.psd.Rectangle  estructura. |
| [setWidth(int value)](#setWidth-int-) | Establece el ancho de esta estructura  com.aspose.psd.Rectangle . |
| [setX(int value)](#setX-int-) | Obtiene o establece la coordenada x de la esquina superior izquierda de esta  com.aspose.psd.Rectangle  estructura. |
| [setY(int value)](#setY-int-) | Obtiene o establece la coordenada y de la esquina superior izquierda de esta  com.aspose.psd.Rectangle  estructura. |
| [toString()](#toString--) | Convierte los atributos de este  com.aspose.psd.Rectangle  a una cadena legible por humanos. |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | Convierte el  com.aspose.psd.RectangleF  especificado a un  com.aspose.psd.Rectangle  truncando los valores del  com.aspose.psd.RectangleF . |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Obtiene una estructura  com.aspose.psd.Rectangle  que contiene la unión de dos estructuras  com.aspose.psd.Rectangle . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Inicializa una nueva instancia de la  com.aspose.psd.Rectangle  estructura con la ubicación y el tamaño especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo. |
| ancho | int | El ancho del rectángulo. |
| alto | int | La altura del rectángulo. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


Inicializa una nueva instancia de la  com.aspose.psd.Rectangle  estructura con la ubicación y el tamaño especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | Un  com.aspose.psd.Point  que representa la esquina superior izquierda de la región rectangular. |
| size | [Size](../../com.aspose.psd/size) | Un  com.aspose.psd.Size  que representa el ancho y la altura de la región rectangular. |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Convierte la  com.aspose.psd.RectangleF  estructura especificada a una  com.aspose.psd.Rectangle  estructura redondeando los valores de  com.aspose.psd.RectangleF  al siguiente número entero superior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | La estructura  com.aspose.psd.RectangleF  a convertir. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


Determina si el punto especificado está contenido dentro de esta  com.aspose.psd.Rectangle  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | El  com.aspose.psd.Point  a probar. |

**Returns:**
boolean - Este método devuelve true si el punto representado por  point  está contenido dentro de esta estructura  com.aspose.psd.Rectangle ; de lo contrario, false.
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Determina si la región rectangular representada por  rect  está completamente contenida dentro de esta  com.aspose.psd.Rectangle  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | El  com.aspose.psd.Rectangle  a probar. |

**Returns:**
boolean - Este método devuelve true si la región rectangular representada por  rect  está completamente contenida dentro de esta estructura  com.aspose.psd.Rectangle ; de lo contrario, false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Determina si el punto especificado está contenido dentro de esta  com.aspose.psd.Rectangle  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |

**Returns:**
boolean - Este método devuelve true si el punto definido por  x  y  y  está contenido dentro de esta estructura  com.aspose.psd.Rectangle ; de lo contrario, false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprueba si  obj  es una  com.aspose.psd.Rectangle  estructura con la misma ubicación y tamaño que esta  com.aspose.psd.Rectangle  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El  System.Object  a probar. |

**Returns:**
boolean - Este método devuelve true si  obj  es una estructura  com.aspose.psd.Rectangle  y sus propiedades  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  y  com.aspose.psd.Rectangle.Height  son iguales a las propiedades correspondientes de esta estructura  com.aspose.psd.Rectangle ; de lo contrario, false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Crea una  com.aspose.psd.Rectangle  estructura con las ubicaciones de borde especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | int | La coordenada x de la esquina superior izquierda de esta estructura  com.aspose.psd.Rectangle . |
| top | int | La coordenada y de la esquina superior izquierda de esta estructura  com.aspose.psd.Rectangle . |
| right | int | La coordenada x de la esquina inferior derecha de esta estructura  com.aspose.psd.Rectangle . |
| bottom | int | La coordenada y de la esquina inferior derecha de esta estructura  com.aspose.psd.Rectangle . |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Crea un nuevo  Rectangle  a partir de dos puntos especificados. Dos vértices del  Rectangle  creado serán iguales a los puntos  point1  y  point2  pasados. Estos suelen ser los vértices opuestos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | El primer Point para el nuevo rectángulo. |
| point2 | [Point](../../com.aspose.psd/point) | El segundo Point para el nuevo rectángulo. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


Obtiene o establece la coordenada y que es la suma de los valores de las propiedades  com.aspose.psd.Rectangle.Y  y  com.aspose.psd.Rectangle.Height  de esta  com.aspose.psd.Rectangle  estructura.

**Returns:**
int - La coordenada y que es la suma de  com.aspose.psd.Rectangle.Y  y  com.aspose.psd.Rectangle.Height  de este  com.aspose.psd.Rectangle .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Obtiene una nueva instancia de la  com.aspose.psd.Rectangle  estructura que tiene los valores de  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  y  com.aspose.psd.Rectangle.Height  establecidos en cero.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene o establece la altura de esta  com.aspose.psd.Rectangle  estructura.

**Returns:**
int - La altura de esta estructura  com.aspose.psd.Rectangle .
### getLeft() {#getLeft--}
```
public int getLeft()
```


Obtiene o establece la coordenada x del borde izquierdo de esta  com.aspose.psd.Rectangle  estructura.

**Returns:**
int - La coordenada x del borde izquierdo de esta estructura  com.aspose.psd.Rectangle .
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Obtiene o establece las coordenadas de la esquina superior izquierda de esta  com.aspose.psd.Rectangle  estructura.

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


Obtiene o establece la coordenada x que es la suma de los valores de las propiedades  com.aspose.psd.Rectangle.X  y  com.aspose.psd.Rectangle.Width  de esta  com.aspose.psd.Rectangle  estructura.

**Returns:**
int - La coordenada x que es la suma de  com.aspose.psd.Rectangle.X  y  com.aspose.psd.Rectangle.Width  de este  com.aspose.psd.Rectangle .
### getSize() {#getSize--}
```
public Size getSize()
```


Obtiene o establece el tamaño de esta  com.aspose.psd.Rectangle .

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


Obtiene o establece la coordenada y del borde superior de esta  com.aspose.psd.Rectangle  estructura.

**Returns:**
int - La coordenada y del borde superior de esta estructura  com.aspose.psd.Rectangle .
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho de esta  com.aspose.psd.Rectangle  estructura.

**Returns:**
int - El ancho de esta estructura com.aspose.psd.Rectangle.
### getX() {#getX--}
```
public int getX()
```


Obtiene o establece la coordenada x de la esquina superior izquierda de esta  com.aspose.psd.Rectangle  estructura.

**Returns:**
int - La coordenada x de la esquina superior izquierda de esta estructura com.aspose.psd.Rectangle.
### getY() {#getY--}
```
public int getY()
```


Obtiene o establece la coordenada y de la esquina superior izquierda de esta  com.aspose.psd.Rectangle  estructura.

**Returns:**
int - La coordenada y de la esquina superior izquierda de esta estructura com.aspose.psd.Rectangle.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash de esta  com.aspose.psd.Rectangle  estructura.

**Returns:**
int - Un entero que representa el código hash de este rectángulo.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Crea y devuelve una copia inflada de la estructura com.aspose.psd.Rectangle especificada. La copia se infla en la cantidad especificada. La estructura com.aspose.psd.Rectangle original permanece sin modificar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | El com.aspose.psd.Rectangle con el que iniciar. Este rectángulo no se modifica. |
| x | int | La cantidad para inflar este com.aspose.psd.Rectangle horizontalmente. |
| y | int | La cantidad para inflar este com.aspose.psd.Rectangle verticalmente. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


Infla esta  com.aspose.psd.Rectangle  en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | La cantidad para inflar este rectángulo. |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Infla esta  com.aspose.psd.Rectangle  en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho | int | La cantidad para inflar este com.aspose.psd.Rectangle horizontalmente. |
| alto | int | La cantidad para inflar este com.aspose.psd.Rectangle verticalmente. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Reemplaza esta  com.aspose.psd.Rectangle  con la intersección de ella misma y la  com.aspose.psd.Rectangle  especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | El com.aspose.psd.Rectangle con el que intersectar. |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Devuelve una tercera estructura com.aspose.psd.Rectangle que representa la intersección de dos estructuras com.aspose.psd.Rectangle adicionales. Si no hay intersección, se devuelve un com.aspose.psd.Rectangle vacío.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Un primer rectángulo a intersectar. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Un segundo rectángulo a intersectar. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Determina si este rectángulo intersecta con  rect .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo a probar. |

**Returns:**
boolean - Este método devuelve true si hay alguna intersección, de lo contrario false.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtiene un valor que indica si todas las propiedades numéricas de esta  com.aspose.psd.Rectangle  tienen valores cero.

**Returns:**
boolean - Esta propiedad devuelve true si las propiedades com.aspose.psd.Rectangle.Width, com.aspose.psd.Rectangle.Height, com.aspose.psd.Rectangle.X y com.aspose.psd.Rectangle.Y de este com.aspose.psd.Rectangle tienen todos valores cero; de lo contrario, false.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


Obtiene un valor que indica si este  Rectangle  es al menos parcialmente visible

**Returns:**
boolean - true si este Rectangle es al menos parcialmente visible; de lo contrario, false.
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




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | Cantidad para desplazar la ubicación. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Ajusta la ubicación de este rectángulo en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | El desplazamiento horizontal. |
| y | int | El desplazamiento vertical. |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Comprueba si dos  com.aspose.psd.Rectangle  estructuras tienen la misma ubicación y tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | La estructura com.aspose.psd.Rectangle que está a la izquierda del operador de igualdad. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | La estructura com.aspose.psd.Rectangle que está a la derecha del operador de igualdad. |

**Returns:**
boolean - Este operador devuelve true si las dos estructuras com.aspose.psd.Rectangle tienen iguales las propiedades com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width y com.aspose.psd.Rectangle.Height.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Comprueba si dos estructuras  com.aspose.psd.Rectangle  difieren en ubicación o tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | La estructura com.aspose.psd.Rectangle que está a la izquierda del operador de desigualdad. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | La estructura com.aspose.psd.Rectangle que está a la derecha del operador de desigualdad. |

**Returns:**
boolean - Este operador devuelve true si alguna de las propiedades com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width o com.aspose.psd.Rectangle.Height de las dos estructuras com.aspose.psd.Rectangle no son iguales; de lo contrario false.
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Convierte el  com.aspose.psd.RectangleF  especificado a un  com.aspose.psd.Rectangle  redondeando los valores del  com.aspose.psd.RectangleF  al entero más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | El com.aspose.psd.RectangleF a convertir. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Obtiene o establece la coordenada y que es la suma de los valores de las propiedades  com.aspose.psd.Rectangle.Y  y  com.aspose.psd.Rectangle.Height  de esta  com.aspose.psd.Rectangle  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La coordenada y que es la suma de com.aspose.psd.Rectangle.Y y com.aspose.psd.Rectangle.Height de este com.aspose.psd.Rectangle. |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtiene o establece la altura de esta  com.aspose.psd.Rectangle  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La altura de esta estructura com.aspose.psd.Rectangle. |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Obtiene o establece la coordenada x del borde izquierdo de esta  com.aspose.psd.Rectangle  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La coordenada x del borde izquierdo de esta estructura com.aspose.psd.Rectangle. |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


Obtiene o establece las coordenadas de la esquina superior izquierda de esta  com.aspose.psd.Rectangle  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | Un Point que representa la esquina superior izquierda de esta estructura com.aspose.psd.Rectangle. |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Obtiene o establece la coordenada x que es la suma de los valores de las propiedades  com.aspose.psd.Rectangle.X  y  com.aspose.psd.Rectangle.Width  de esta  com.aspose.psd.Rectangle  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La coordenada x que es la suma de com.aspose.psd.Rectangle.X y com.aspose.psd.Rectangle.Width de esta com.aspose.psd.Rectangle. |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


Obtiene o establece el tamaño de esta  com.aspose.psd.Rectangle .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | Un com.aspose.psd.Size que representa el ancho y la altura de esta estructura com.aspose.psd.Rectangle. |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Obtiene o establece la coordenada y del borde superior de esta  com.aspose.psd.Rectangle  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La coordenada y del borde superior de esta estructura com.aspose.psd.Rectangle. |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Establece el ancho de esta estructura  com.aspose.psd.Rectangle .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El ancho de esta estructura com.aspose.psd.Rectangle. |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Obtiene o establece la coordenada x de la esquina superior izquierda de esta  com.aspose.psd.Rectangle  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La coordenada x de la esquina superior izquierda de esta estructura  com.aspose.psd.Rectangle . |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Obtiene o establece la coordenada y de la esquina superior izquierda de esta  com.aspose.psd.Rectangle  estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La coordenada y de la esquina superior izquierda de esta estructura  com.aspose.psd.Rectangle . |

### toString() {#toString--}
```
public String toString()
```


Convierte los atributos de este  com.aspose.psd.Rectangle  a una cadena legible por humanos.

**Returns:**
java.lang.String - Una cadena que contiene la posición, el ancho y la altura de esta estructura com.aspose.psd.Rectangle.
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Convierte el  com.aspose.psd.RectangleF  especificado a un  com.aspose.psd.Rectangle  truncando los valores del  com.aspose.psd.RectangleF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | El com.aspose.psd.RectangleF a convertir. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Obtiene una estructura  com.aspose.psd.Rectangle  que contiene la unión de dos estructuras  com.aspose.psd.Rectangle .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Un primer rectángulo para unir. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Un segundo rectángulo para unir. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
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

