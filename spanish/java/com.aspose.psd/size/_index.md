---
title: "Tamaño"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa el tamaño."
type: docs
weight: 98
url: /es/java/com.aspose.psd/size/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Representa el tamaño.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.psd.Point-) | Inicializa una nueva instancia de la estructura  Aspose.Imaging.Size  a partir del  Aspose.Imaging.Point  especificado. |
| [Size(int width, int height)](#Size-int-int-) | Inicializa una nueva instancia de la estructura  Aspose.Imaging.Size  a partir de las dimensiones especificadas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Size that)](#CloneTo-com.aspose.psd.Size-) |  |
| [add(Size size1, Size size2)](#add-com.aspose.psd.Size-com.aspose.psd.Size-) | Añade el ancho y la altura de una estructura  Aspose.Imaging.Size  al ancho y la altura de otra estructura  Aspose.Imaging.Size . |
| [ceiling(SizeF size)](#ceiling-com.aspose.psd.SizeF-) | Convierte la estructura  Aspose.Imaging.SizeF  especificada a una estructura  Aspose.Imaging.Size  redondeando los valores de la estructura  Aspose.Imaging.Size  al siguiente entero superior. |
| [equals(Object obj)](#equals-java.lang.Object-) | Pruebas para ver si el objeto especificado es un  Aspose.Imaging.Size  con las mismas dimensiones que este  Aspose.Imaging.Size . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Obtiene una nueva instancia de la estructura  Aspose.Imaging.Size  que tiene los valores  Aspose.Imaging.Size.Width  y  Aspose.Imaging.Size.Height  establecidos en cero. |
| [getHeight()](#getHeight--) | Obtiene o establece el componente vertical de este  Aspose.Imaging.Size . |
| [getWidth()](#getWidth--) | Obtiene o establece el componente horizontal de este  Aspose.Imaging.Size . |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta estructura  Aspose.Imaging.Size . |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si este  Aspose.Imaging.Size  tiene ancho y alto de 0. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-) | Añade el ancho y la altura de una estructura  Aspose.Imaging.Size  al ancho y la altura de otra estructura  Aspose.Imaging.Size . |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-) | Prueba si dos estructuras  Aspose.Imaging.Size  son iguales. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-) | Prueba si dos estructuras  Aspose.Imaging.Size  son diferentes. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-) | Resta el ancho y alto de una estructura  Aspose.Imaging.Size  del ancho y alto de otra estructura  Aspose.Imaging.Size . |
| [round(SizeF size)](#round-com.aspose.psd.SizeF-) | Convierte la estructura  Aspose.Imaging.SizeF  especificada a una estructura  Aspose.Imaging.Size  redondeando los valores de la estructura  Aspose.Imaging.SizeF  al entero más cercano. |
| [setHeight(int value)](#setHeight-int-) | Obtiene o establece el componente vertical de este  Aspose.Imaging.Size . |
| [setWidth(int value)](#setWidth-int-) | Obtiene o establece el componente horizontal de este  Aspose.Imaging.Size . |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.psd.Size-com.aspose.psd.Size-) | Resta el ancho y alto de una estructura  Aspose.Imaging.Size  del ancho y alto de otra estructura  Aspose.Imaging.Size . |
| [toString()](#toString--) | Crea una cadena legible que representa este  Aspose.Imaging.Size . |
| [to_Point(Size size)](#to-Point-com.aspose.psd.Size-) | Convierte el  Aspose.Imaging.Size  especificado a un  Aspose.Imaging.Point . |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.psd.Size-) | Convierte el  Aspose.Imaging.Size  especificado a un  Aspose.Imaging.SizeF . |
| [truncate(SizeF size)](#truncate-com.aspose.psd.SizeF-) | Convierte la estructura  Aspose.Imaging.SizeF  especificada a una estructura  Aspose.Imaging.Size  truncando los valores de la estructura  Aspose.Imaging.SizeF  al entero inferior más próximo. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.psd.Point-}
```
public Size(Point point)
```


Inicializa una nueva instancia de la estructura  Aspose.Imaging.Size  a partir del  Aspose.Imaging.Point  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | El  Aspose.Imaging.Point  desde el cual inicializar este  Aspose.Imaging.Size . |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Inicializa una nueva instancia de la estructura  Aspose.Imaging.Size  a partir de las dimensiones especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho | int | El componente de ancho del nuevo  Aspose.Imaging.Size . |
| alto | int | El componente de alto del nuevo  Aspose.Imaging.Size . |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.psd/size)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Size that) {#CloneTo-com.aspose.psd.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [Size](../../com.aspose.psd/size) |  |

### add(Size size1, Size size2) {#add-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size add(Size size1, Size size2)
```


Añade el ancho y la altura de una estructura  Aspose.Imaging.Size  al ancho y la altura de otra estructura  Aspose.Imaging.Size .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | El primer  Aspose.Imaging.Size  a añadir. |
| size2 | [Size](../../com.aspose.psd/size) | El segundo  Aspose.Imaging.Size  a añadir. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.psd.SizeF-}
```
public static Size ceiling(SizeF size)
```


Convierte la estructura  Aspose.Imaging.SizeF  especificada a una estructura  Aspose.Imaging.Size  redondeando los valores de la estructura  Aspose.Imaging.Size  al siguiente entero superior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | La estructura  Aspose.Imaging.SizeF  a convertir. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Pruebas para ver si el objeto especificado es un  Aspose.Imaging.Size  con las mismas dimensiones que este  Aspose.Imaging.Size .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El  System.Object  a probar. |

**Returns:**
boolean - Verdadero si  obj  es un  Aspose.Imaging.Size  y tiene el mismo ancho y alto que este  Aspose.Imaging.Size ; de lo contrario, falso.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Obtiene una nueva instancia de la estructura  Aspose.Imaging.Size  que tiene los valores  Aspose.Imaging.Size.Width  y  Aspose.Imaging.Size.Height  establecidos en cero.

**Returns:**
[Size](../../com.aspose.psd/size)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene o establece el componente vertical de este  Aspose.Imaging.Size .

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene o establece el componente horizontal de este  Aspose.Imaging.Size .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta estructura  Aspose.Imaging.Size .

**Returns:**
int - Un valor entero que especifica un valor hash para esta estructura  Aspose.Imaging.Size .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtiene un valor que indica si este  Aspose.Imaging.Size  tiene ancho y alto de 0.

**Returns:**
boolean
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.psd/size) |  |
| obj2 | [Size](../../com.aspose.psd/size) |  |

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




### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Añade el ancho y la altura de una estructura  Aspose.Imaging.Size  al ancho y la altura de otra estructura  Aspose.Imaging.Size .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | El primer  Aspose.Imaging.Size  a añadir. |
| size2 | [Size](../../com.aspose.psd/size) | El segundo  Aspose.Imaging.Size  a añadir. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


Prueba si dos estructuras  Aspose.Imaging.Size  son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | La estructura  Aspose.Imaging.Size  del lado izquierdo del operador de igualdad. |
| size2 | [Size](../../com.aspose.psd/size) | La estructura  Aspose.Imaging.Size  del lado derecho del operador de igualdad. |

**Returns:**
boolean - Verdadero si  size1  y  size2  tienen el mismo ancho y alto; de lo contrario, falso.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


Prueba si dos estructuras  Aspose.Imaging.Size  son diferentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | La estructura Aspose.Imaging.Size a la izquierda del operador de desigualdad. |
| size2 | [Size](../../com.aspose.psd/size) | La estructura Aspose.Imaging.Size a la derecha del operador de desigualdad. |

**Returns:**
boolean - Verdadero si size1 y size2 difieren ya sea en ancho o altura; falso si size1 y size2 son iguales.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Resta el ancho y alto de una estructura  Aspose.Imaging.Size  del ancho y alto de otra estructura  Aspose.Imaging.Size .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | La estructura Aspose.Imaging.Size en el lado izquierdo del operador de resta. |
| size2 | [Size](../../com.aspose.psd/size) | La estructura Aspose.Imaging.Size en el lado derecho del operador de resta. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the subtraction operation.
### round(SizeF size) {#round-com.aspose.psd.SizeF-}
```
public static Size round(SizeF size)
```


Convierte la estructura  Aspose.Imaging.SizeF  especificada a una estructura  Aspose.Imaging.Size  redondeando los valores de la estructura  Aspose.Imaging.SizeF  al entero más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | La estructura  Aspose.Imaging.SizeF  a convertir. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtiene o establece el componente vertical de este  Aspose.Imaging.Size .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtiene o establece el componente horizontal de este  Aspose.Imaging.Size .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### subtract(Size size1, Size size2) {#subtract-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Resta el ancho y alto de una estructura  Aspose.Imaging.Size  del ancho y alto de otra estructura  Aspose.Imaging.Size .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | La estructura Aspose.Imaging.Size en el lado izquierdo del operador de resta. |
| size2 | [Size](../../com.aspose.psd/size) | La estructura Aspose.Imaging.Size en el lado derecho del operador de resta. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that is a result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Crea una cadena legible que representa este  Aspose.Imaging.Size .

**Returns:**
java.lang.String - Una cadena que representa este Aspose.Imaging.Size.
### to_Point(Size size) {#to-Point-com.aspose.psd.Size-}
```
public static Point to_Point(Size size)
```


Convierte el  Aspose.Imaging.Size  especificado a un  Aspose.Imaging.Point .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | El Aspose.Imaging.Size a convertir. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  structure to which this operator converts.
### to_SizeF(Size size) {#to-SizeF-com.aspose.psd.Size-}
```
public static SizeF to_SizeF(Size size)
```


Convierte el  Aspose.Imaging.Size  especificado a un  Aspose.Imaging.SizeF .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | El Aspose.Imaging.Size a convertir. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The  Aspose.Imaging.SizeF  structure to which this operator converts.
### truncate(SizeF size) {#truncate-com.aspose.psd.SizeF-}
```
public static Size truncate(SizeF size)
```


Convierte la estructura  Aspose.Imaging.SizeF  especificada a una estructura  Aspose.Imaging.Size  truncando los valores de la estructura  Aspose.Imaging.SizeF  al entero inferior más próximo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | La estructura  Aspose.Imaging.SizeF  a convertir. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
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

