---
title: "CustomLineCap"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Encapsula un extremo de línea personalizado definido por el usuario."
type: docs
weight: 34
url: /es/java/com.aspose.psd/customlinecap/
---

**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Encapsula un extremo de línea personalizado definido por el usuario.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-) | Inicializa una nueva instancia de la  CustomLineCap  clase con el contorno y el relleno especificados. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-) | Inicializa una nueva instancia de la  CustomLineCap  clase a partir de la enumeración  LineCap  existente especificada, con el contorno y el relleno especificados. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-) | Inicializa una nueva instancia de la  CustomLineCap  clase a partir de la enumeración  LineCap  existente especificada, con el contorno, el relleno y el inset especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseCap()](#getBaseCap--) | Obtiene la enumeración  LineCap  en la que se basa este  CustomLineCap . |
| [getBaseInset()](#getBaseInset--) | Obtiene la distancia entre el cap y la línea. |
| [getClass()](#getClass--) |  |
| [getFillPath()](#getFillPath--) | Obtiene el objeto que define el relleno para el cap personalizado. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Obtiene los caps utilizados para iniciar y terminar líneas que componen este cap personalizado. |
| [getStrokeJoin()](#getStrokeJoin--) | Obtiene la enumeración  LineJoin  que determina cómo se unen las líneas que componen este objeto  CustomLineCap . |
| [getStrokePath()](#getStrokePath--) | Obtiene el objeto que define el contorno del cap personalizado. |
| [getWidthScale()](#getWidthScale--) | Obtiene la cantidad por la cual escalar este objeto de clase  CustomLineCap  con respecto al ancho del objeto  System.Drawing.Pen . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaseCap(int value)](#setBaseCap-int-) | Establece la enumeración  LineCap  en la que se basa este  CustomLineCap . |
| [setBaseInset(float value)](#setBaseInset-float-) | Establece la distancia entre el cap y la línea. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.psd.GraphicsPath-) | Establece el objeto que define el relleno para el cap personalizado. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Establece los caps utilizados para iniciar y terminar líneas que componen este cap personalizado. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Establece la enumeración  LineJoin  que determina cómo se unen las líneas que componen este objeto  CustomLineCap . |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.psd.GraphicsPath-) | Establece el objeto que define el contorno del cap personalizado. |
| [setWidthScale(float value)](#setWidthScale-float-) | Establece la cantidad por la cual escalar este objeto de clase  CustomLineCap  con respecto al ancho del objeto  System.Drawing.Pen . |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Inicializa una nueva instancia de la  CustomLineCap  clase con el contorno y el relleno especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un objeto  GraphicsPath  que define el relleno del cap personalizado. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un objeto  GraphicsPath  que define el contorno del cap personalizado. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Inicializa una nueva instancia de la  CustomLineCap  clase a partir de la enumeración  LineCap  existente especificada, con el contorno y el relleno especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un objeto  GraphicsPath  que define el relleno del cap personalizado. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un objeto  GraphicsPath  que define el contorno del cap personalizado. |
| baseCap | int | El extremo de línea desde el cual crear el extremo personalizado. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Inicializa una nueva instancia de la  CustomLineCap  clase a partir de la enumeración  LineCap  existente especificada, con el contorno, el relleno y el inset especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un objeto  GraphicsPath  que define el relleno del cap personalizado. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Un objeto  GraphicsPath  que define el contorno del cap personalizado. |
| baseCap | int | El extremo de línea desde el cual crear el extremo personalizado. |
| baseInset | float | La distancia entre el extremo y la línea. |

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
### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Obtiene la enumeración  LineCap  en la que se basa este  CustomLineCap .

**Returns:**
int - La  LineCap  enumeración en la que se basa este  CustomLineCap.
### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Obtiene la distancia entre el cap y la línea.

**Returns:**
float - La distancia entre el comienzo del extremo y el final de la línea.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Obtiene el objeto que define el relleno para el cap personalizado.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the fill for the custom cap.
### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Obtiene los caps utilizados para iniciar y terminar líneas que componen este cap personalizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startCap | int[] | La  LineCap  enumeración utilizada al comienzo de una línea dentro de este extremo. |
| endCap | int[] | La  LineCap  enumeración utilizada al final de una línea dentro de este extremo. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Obtiene la enumeración  LineJoin  que determina cómo se unen las líneas que componen este objeto  CustomLineCap .

**Returns:**
int - La  LineJoin  enumeración que este objeto  CustomLineCap  usa para unir líneas.
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Obtiene el objeto que define el contorno del cap personalizado.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the outline of the custom cap.
### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Obtiene la cantidad por la cual escalar este objeto de clase  CustomLineCap  con respecto al ancho del objeto  System.Drawing.Pen .

**Returns:**
float - La cantidad por la cual escalar el extremo.
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




### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Establece la enumeración  LineCap  en la que se basa este  CustomLineCap .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La  LineCap  enumeración en la que se basa este  CustomLineCap. |

### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Establece la distancia entre el cap y la línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | La distancia entre el comienzo del extremo y el final de la línea. |

### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.psd.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Establece el objeto que define el relleno para el cap personalizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | El objeto que define el relleno del extremo personalizado. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Establece los caps utilizados para iniciar y terminar líneas que componen este cap personalizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startCap | int | La  LineCap  enumeración utilizada al comienzo de una línea dentro de este extremo. |
| endCap | int | La  LineCap  enumeración utilizada al final de una línea dentro de este extremo. |

### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Establece la enumeración  LineJoin  que determina cómo se unen las líneas que componen este objeto  CustomLineCap .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La  LineJoin  enumeración que este objeto  CustomLineCap  usa para unir líneas. |

### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.psd.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Establece el objeto que define el contorno del cap personalizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | El objeto que define el contorno del extremo personalizado. |

### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Establece la cantidad por la cual escalar este objeto de clase  CustomLineCap  con respecto al ancho del objeto  System.Drawing.Pen .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | La cantidad por la cual escalar el extremo. |

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

