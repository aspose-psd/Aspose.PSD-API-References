---
title: "AutoMaskingArgs"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa los argumentos que se especifican para los métodos de enmascarado automatizado"
type: docs
weight: 11
url: /es/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Representa los argumentos que se especifican para los métodos de enmascarado automatizado
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Obtiene el número máximo de iteraciones. |
| [getNumberOfObjects()](#getNumberOfObjects--) | Obtiene el número de objetos a los que separar la imagen inicial (opcional), el valor predeterminado es 2 (objeto y fondo). |
| [getObjectsPoints()](#getObjectsPoints--) | Obtiene los puntos que pertenecen a los objetos separados (opcional) coordenadas NumberOfObjects que pertenecen a los objetos NumberOfObjects de la imagen inicial. |
| [getObjectsRectangles()](#getObjectsRectangles--) | Obtiene los rectángulos de los objetos que pertenecen a los objetos separados (opcional). |
| [getOrphanedPoints()](#getOrphanedPoints--) | Obtiene los puntos que ya no pertenecen a ningún objeto (opcional). |
| [getPrecision()](#getPrecision--) | Obtiene la precisión del método de segmentación (opcional). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Establece el número máximo de iteraciones. |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Establece el número de objetos a los que separar la imagen inicial (opcional), el valor predeterminado es 2 (objeto y fondo). |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | Establece los puntos que pertenecen a los objetos separados (opcional) coordenadas NumberOfObjects que pertenecen a los objetos NumberOfObjects de la imagen inicial. |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | Establece los rectángulos de los objetos que pertenecen a los objetos separados (opcional). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | Establece los puntos que ya no pertenecen a ningún objeto (opcional). |
| [setPrecision(double value)](#setPrecision-double-) | Establece la precisión del método de segmentación (opcional). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Obtiene el número máximo de iteraciones.

Valor: El número máximo máximo de iteraciones.

**Returns:**
int - el número máximo de iteraciones.
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Obtiene el número de objetos a los que separar la imagen inicial (opcional), el valor predeterminado es 2 (objeto y fondo).

Valor: El número de objetos.

**Returns:**
int - el número de objetos a los que separar la imagen inicial (opcional), el valor predeterminado es 2 (objeto y fondo).
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Obtiene los puntos que pertenecen a los objetos separados (opcional) coordenadas NumberOfObjects que pertenecen a los objetos NumberOfObjects de la imagen inicial. Este parámetro se usa para aumentar la precisión del método de segmentación.

Valor: Los puntos de los objetos.

**Returns:**
com.aspose.psd.Point[][] - los puntos que pertenecen a objetos separados (opcional) NumberOfObjects coordenadas que pertenecen a NumberOfObjects objetos de la imagen inicial.
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Obtiene los rectángulos de los objetos que pertenecen a objetos separados (opcional). Este parámetro se usa para aumentar la precisión del método de segmentación.

Valor: Los rectángulos de los objetos.

**Returns:**
com.aspose.psd.Rectangle[] - los rectángulos de los objetos que pertenecen a objetos separados (opcional).
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Obtiene los puntos que ya no pertenecen a ningún objeto (opcional). Este parámetro se usa solo en caso de resegmentación.

Valor: Los puntos huérfanos.

**Returns:**
com.aspose.psd.Point[] - los puntos que ya no pertenecen a ningún objeto (opcional).
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Obtiene la precisión del método de segmentación (opcional).

Valor: La precisión del método de segmentación (opcional).

**Returns:**
double - la precisión del método de segmentación (opcional).
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Establece el número máximo de iteraciones.

Valor: El número máximo máximo de iteraciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el número máximo de iteraciones. |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Establece el número de objetos a los que separar la imagen inicial (opcional), el valor predeterminado es 2 (objeto y fondo).

Valor: El número de objetos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el número de objetos en los que separar la imagen inicial (opcional), el valor predeterminado es 2 (objeto y fondo). |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Establece los puntos que pertenecen a objetos separados (opcional) NumberOfObjects coordenadas que pertenecen a NumberOfObjects objetos de la imagen inicial. Este parámetro se usa para aumentar la precisión del método de segmentación.

Valor: Los puntos de los objetos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | los puntos que pertenecen a objetos separados (opcional) NumberOfObjects coordenadas que pertenecen a NumberOfObjects objetos de la imagen inicial. |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Establece los rectángulos de los objetos que pertenecen a objetos separados (opcional). Este parámetro se usa para aumentar la precisión del método de segmentación.

Valor: Los rectángulos de los objetos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | los rectángulos de los objetos que pertenecen a objetos separados (opcional). |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Establece los puntos que ya no pertenecen a ningún objeto (opcional). Este parámetro se usa solo en caso de resegmentación.

Valor: Los puntos huérfanos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | los puntos que ya no pertenecen a ningún objeto (opcional). |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Establece la precisión del método de segmentación (opcional).

Valor: La precisión del método de segmentación (opcional).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | la precisión del método de segmentación (opcional). |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

