---
title: "Point"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa un par ordenado de coordenadas enteras x e y que define un punto en un plano bidimensional."
type: docs
weight: 82
url: /es/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Representa un par ordenado de coordenadas enteras x e y que define un punto en un plano bidimensional.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Inicializa una nueva instancia de la estructura Aspose.Imaging.Point con las coordenadas especificadas. |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Inicializa una nueva instancia de la estructura Aspose.Imaging.Point a partir de la estructura Aspose.Imaging.Size. |
| [Point(int dw)](#Point-int-) | Inicializa una nueva instancia de la  Aspose.Imaging.Point  estructura usando coordenadas especificadas por un valor entero. |
## Campos

| Campo | Descripción |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | Representa el formato del punto. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | Agrega el  Aspose.Imaging.Size  especificado al  Aspose.Imaging.Point  especificado. |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | Convierte el  Aspose.Imaging.PointF  especificado a un  Aspose.Imaging.Point  redondeando los valores del  Aspose.Imaging.PointF  al siguiente entero superior. |
| [equals(Object obj)](#equals-java.lang.Object-) | Especifica si este  Aspose.Imaging.Point  contiene las mismas coordenadas que el  System.Object  especificado. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Obtiene una nueva instancia de la  Aspose.Imaging.Point  estructura que tiene los valores  Aspose.Imaging.Point.X  y  Aspose.Imaging.Point.Y  establecidos en cero. |
| [getX()](#getX--) | Obtiene o establece la coordenada x de este  Aspose.Imaging.Point . |
| [getY()](#getY--) | Obtiene o establece la coordenada y de este  Aspose.Imaging.Point . |
| [hashCode()](#hashCode--) | Devuelve un código hash para este  Aspose.Imaging.Point . |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si este  Aspose.Imaging.Point  está vacío. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | Traslada este  Aspose.Imaging.Point  por el  Aspose.Imaging.Point  especificado. |
| [offset(int dx, int dy)](#offset-int-int-) | Traslada este  Aspose.Imaging.Point  por la cantidad especificada. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | Traslada un  Aspose.Imaging.Point  por un  Aspose.Imaging.Size  dado. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | Compara dos objetos  Aspose.Imaging.Point . |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | Compara dos objetos  Aspose.Imaging.Point . |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | Traslada un  Aspose.Imaging.Point  por el negativo de un  Aspose.Imaging.Size  dado. |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | Convierte el  Aspose.Imaging.PointF  especificado a un objeto  Aspose.Imaging.Point  redondeando los valores del  Aspose.Imaging.Point  al entero más cercano. |
| [setX(int value)](#setX-int-) | Obtiene o establece la coordenada x de este  Aspose.Imaging.Point . |
| [setY(int value)](#setY-int-) | Obtiene o establece la coordenada y de este  Aspose.Imaging.Point . |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | Devuelve el resultado de restar el  Aspose.Imaging.Size  especificado del  Aspose.Imaging.Point  especificado. |
| [toString()](#toString--) | Convierte este  Aspose.Imaging.Point  a una cadena legible por humanos. |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | Convierte la estructura  Point  especificada a la estructura  PointF . |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | Convierte la estructura  Aspose.Imaging.Point  especificada a una estructura  Aspose.Imaging.Size . |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | Convierte el  Aspose.Imaging.PointF  especificado a un  Aspose.Imaging.Point  truncando los valores del  Aspose.Imaging.Point . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Inicializa una nueva instancia de la estructura Aspose.Imaging.Point con las coordenadas especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La posición horizontal del punto. |
| y | int | La posición vertical del punto. |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Inicializa una nueva instancia de la estructura Aspose.Imaging.Point a partir de la estructura Aspose.Imaging.Size.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Contiene las nuevas coordenadas del punto. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Inicializa una nueva instancia de la  Aspose.Imaging.Point  estructura usando coordenadas especificadas por un valor entero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dw | int | Un entero de 32 bits que especifica las coordenadas del nuevo punto. |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


Representa el formato del punto.

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


Agrega el  Aspose.Imaging.Size  especificado al  Aspose.Imaging.Point  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | El  Aspose.Imaging.Point  al que se agrega. |
| size | [Size](../../com.aspose.psd/size) | El  Aspose.Imaging.Size  para añadir al  punto . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


Convierte el  Aspose.Imaging.PointF  especificado a un  Aspose.Imaging.Point  redondeando los valores del  Aspose.Imaging.PointF  al siguiente entero superior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | El  Aspose.Imaging.PointF  para convertir. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Especifica si este  Aspose.Imaging.Point  contiene las mismas coordenadas que el  System.Object  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El  System.Object  a probar. |

**Returns:**
boolean - Verdadero si  obj  es un  Aspose.Imaging.Point  y tiene las mismas coordenadas que este  Aspose.Imaging.Point .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Obtiene una nueva instancia de la  Aspose.Imaging.Point  estructura que tiene los valores  Aspose.Imaging.Point.X  y  Aspose.Imaging.Point.Y  establecidos en cero.

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


Obtiene o establece la coordenada x de este  Aspose.Imaging.Point .

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Obtiene o establece la coordenada y de este  Aspose.Imaging.Point .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para este  Aspose.Imaging.Point .

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtiene un valor que indica si este  Aspose.Imaging.Point  está vacío.

**Returns:**
boolean - Verdadero si tanto  Aspose.Imaging.Point.X  como  Aspose.Imaging.Point.Y  son 0; de lo contrario, falso.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


Traslada este  Aspose.Imaging.Point  por el  Aspose.Imaging.Point  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | El  Aspose.Imaging.Point  usado para desplazar este  Aspose.Imaging.Point . |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Traslada este  Aspose.Imaging.Point  por la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dx | int | La cantidad para desplazar la coordenada x. |
| dy | int | La cantidad para desplazar la coordenada y. |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Traslada un  Aspose.Imaging.Point  por un  Aspose.Imaging.Size  dado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | El  Aspose.Imaging.Point  para trasladar. |
| size | [Size](../../com.aspose.psd/size) | Un  Aspose.Imaging.Size  que especifica el par de números para añadir a las coordenadas del  punto . |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Compara dos objetos  Aspose.Imaging.Point. El resultado indica si los valores de las propiedades  Aspose.Imaging.Point.X  y  Aspose.Imaging.Point.Y  de los dos objetos  Aspose.Imaging.Point  son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Un primer  Aspose.Imaging.Point  para comparar. |
| point2 | [Point](../../com.aspose.psd/point) | Un segundo  Aspose.Imaging.Point  para comparar. |

**Returns:**
boolean - Verdadero si los valores  Aspose.Imaging.Point.X  y  Aspose.Imaging.Point.Y  de  point1  y  point2  son iguales; de lo contrario, falso.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Compara dos objetos  Aspose.Imaging.Point. El resultado indica si los valores de las propiedades  Aspose.Imaging.Point.X  o  Aspose.Imaging.Point.Y  de los dos objetos  Aspose.Imaging.Point  son diferentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Un primer  Aspose.Imaging.Point  para comparar. |
| point2 | [Point](../../com.aspose.psd/point) | Un segundo  Aspose.Imaging.Point  para comparar. |

**Returns:**
boolean - Verdadero si los valores de cualquiera de las propiedades  Aspose.Imaging.Point.X  o  Aspose.Imaging.Point.Y  de  point1  y  point2  difieren; de lo contrario, falso.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Traslada un  Aspose.Imaging.Point  por el negativo de un  Aspose.Imaging.Size  dado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | El  Aspose.Imaging.Point  para trasladar. |
| size | [Size](../../com.aspose.psd/size) | Un  Aspose.Imaging.Size  que especifica el par de números para restar de las coordenadas del  punto . |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


Convierte el  Aspose.Imaging.PointF  especificado a un objeto  Aspose.Imaging.Point  redondeando los valores del  Aspose.Imaging.Point  al entero más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | El  Aspose.Imaging.PointF  para convertir. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Obtiene o establece la coordenada x de este  Aspose.Imaging.Point .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Obtiene o establece la coordenada y de este  Aspose.Imaging.Point .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


Devuelve el resultado de restar el  Aspose.Imaging.Size  especificado del  Aspose.Imaging.Point  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | El  Aspose.Imaging.Point  del cual se restará. |
| size | [Size](../../com.aspose.psd/size) | El  Aspose.Imaging.Size  para restar del  punto . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Convierte este  Aspose.Imaging.Point  a una cadena legible por humanos.

**Returns:**
java.lang.String - Un  System.String  que representa esta instancia.
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


Convierte la estructura  Point  especificada a la estructura  PointF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | El  Point  a convertir. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


Convierte la estructura  Aspose.Imaging.Point  especificada a una estructura  Aspose.Imaging.Size .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | El  Aspose.Imaging.Point  a convertir. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


Convierte el  Aspose.Imaging.PointF  especificado a un  Aspose.Imaging.Point  truncando los valores del  Aspose.Imaging.Point .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | El  Aspose.Imaging.PointF  para convertir. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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

