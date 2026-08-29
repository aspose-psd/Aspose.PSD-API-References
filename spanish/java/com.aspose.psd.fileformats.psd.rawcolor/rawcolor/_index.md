---
title: "RawColor"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La clase Raw Color ayuda a almacenar colores con cualquier número de canales, cualquier modo de color y cualquier profundidad de bits. Tenga en cuenta que algunas clases internas pueden tener problemas al convertir RawColor a su formato nativo, por lo que si la API le proporciona un color CMYK, es más fiable usar el formato proporcionado."
type: docs
weight: 11
url: /es/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

La clase Raw Color ayuda a almacenar colores con cualquier número de canales, cualquier modo de color y cualquier profundidad de bits. Tenga en cuenta que algunas clases internas pueden tener problemas al convertir RawColor a su formato nativo, por lo que si la API le proporciona un color CMYK, es más fiable usar el formato proporcionado. Además, pueden existir algunos casos en los que Raw Color pueda ser convertido.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | Inicializa una nueva instancia de la clase [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor). |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | Inicializa una nueva instancia de la clase [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) a partir del formato de datos de píxel usando modos de color predefinidos. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el Object especificado es igual a esta instancia. |
| [getAsInt()](#getAsInt--) | Obtiene el color como int en caso de que sea posible obtenerlo. |
| [getAsLong()](#getAsLong--) | Obtiene el color como long en caso de que sea posible obtenerlo. |
| [getBitDepth()](#getBitDepth--) | Obtiene la profundidad de bits de Raw Color. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Modo que debe seguir el color. |
| [getColorModeName()](#getColorModeName--) | Obtiene el nombre del modo de color. |
| [getComponents()](#getComponents--) | Obtiene los componentes del color. |
| [hashCode()](#hashCode--) | Obtiene el código hash del objeto actual. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Implementa el operador ==. |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Implementa el operador !=. |
| [setAsInt(int value)](#setAsInt-int-) | Establece los datos a todos los canales a partir del argumento int si es posible. |
| [setAsLong(long value)](#setAsLong-long-) | Establece los datos a todos los canales a partir del argumento int si es posible. |
| [setColorMode(short value)](#setColorMode-short-) | Modo que debe seguir el color. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


Inicializa una nueva instancia de la clase [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | Los componentes de color personalizados. |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


Inicializa una nueva instancia de la clase [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) a partir del formato de datos de píxel usando modos de color predefinidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | El formato de datos de píxel. |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el Object especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El Object para comparar con esta instancia. |

**Returns:**
boolean -  true  si el Object especificado es igual a esta instancia; de lo contrario,  false .
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


Obtiene el color como int en caso de que sea posible obtenerlo.

**Returns:**
int - Datos de canales almacenados en Int
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


Obtiene el color como long en caso de que sea posible obtenerlo.

**Returns:**
long - Datos de canales almacenados en Int
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Obtiene la profundidad de bits del Color Crudo. Por ejemplo, para el color ARGB con 8 bits por canal/componente es 32. La profundidad de bits del color ARGB completo con 16 bits por canal/componente es 64. La profundidad de bits se acumula a partir de la suma de las profundidades de bits de los canales. Es posible que diferentes canales tengan diferentes profundidades de bits.

**Returns:**
int - La suma de todas las profundidades de bits de los canales
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Modo que debe seguir el color.

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


Obtiene el nombre del modo de color. El nombre del modo de color se acumula a partir de los nombres de canales/componentes

**Returns:**
java.lang.String - Cadena con el nombre del modo de color
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


Obtiene los componentes del color. Cada componente es un canal separado, y si utilizas un esquema de color no popular, es mejor trabajar con cada canal por separado

Valor: Los componentes del color

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash del objeto actual.

**Returns:**
int - El código hash.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(RawColor left, RawColor right) {#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Equality(RawColor left, RawColor right)
```


Implementa el operador ==.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | El primer RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | El segundo RawColor. |

**Returns:**
boolean - El resultado del operador.
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


Implementa el operador !=.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | El primer RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | El segundo RawColor. |

**Returns:**
boolean - El resultado del operador.
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


Establece los datos a todos los canales a partir del argumento int si es posible.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El valor int que contiene los datos del componente |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


Establece los datos a todos los canales a partir del argumento int si es posible.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | El valor int que contiene los datos del componente |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Modo que debe seguir el color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

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

