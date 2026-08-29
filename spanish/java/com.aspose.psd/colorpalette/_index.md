---
title: "ColorPalette"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Define una matriz de colores que conforman una paleta de colores."
type: docs
weight: 27
url: /es/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Define una matriz de colores que conforman una paleta de colores. Los colores son de 32 bits ARGB. No heredable.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Inicializa una nueva instancia de la clase  ColorPalette . |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Inicializa una nueva instancia de la clase  ColorPalette  y IsCompactPalette es false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | Inicializa una nueva instancia de la clase  ColorPalette . |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | Inicializa una nueva instancia de la clase  ColorPalette  y IsCompactPalette es false. |
## Métodos

| Método | Descripción |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Copia la paleta. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Copia la paleta. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Obtiene el color de la paleta ARGB de 32 bits por índice. |
| [getArgb32Entries()](#getArgb32Entries--) | Obtiene una matriz de estructuras ARGB de 32 bits. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Obtiene el color de la paleta por índice. |
| [getEntries()](#getEntries--) | Obtiene una matriz de  com.aspose.psd.Color  estructuras. |
| [getEntriesCount()](#getEntriesCount--) | Obtiene el recuento de entradas. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Obtiene el índice del color más cercano. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Obtiene el índice del color más cercano. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Obtiene o establece un valor que indica si se utiliza una paleta compacta. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


Inicializa una nueva instancia de la clase  ColorPalette .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb32Entries | int[] | Las entradas de la paleta de colores ARGB de 32 bits. |
| isCompactPalette | boolean | Indica si la paleta está compacta. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Inicializa una nueva instancia de la clase  ColorPalette  y IsCompactPalette es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb32Entries | int[] | Las entradas de la paleta de colores ARGB de 32 bits. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Inicializa una nueva instancia de la clase  ColorPalette .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Las entradas de la paleta de colores. |
| isCompactPalette | boolean | Indica si la paleta está compacta. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


Inicializa una nueva instancia de la clase  ColorPalette  y IsCompactPalette es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Las entradas de la paleta de colores. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Copia la paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta de colores. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Copia la paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta de colores. |
| useCompactPalette | boolean | Indica si la paleta está compacta. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
```


Obtiene el color de la paleta ARGB de 32 bits por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | El índice de color de la paleta ARGB de 32 bits. |

**Returns:**
int - La entrada de la paleta de colores especificada por el índice.
### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Obtiene una matriz de estructuras ARGB de 32 bits.

**Returns:**
int[] - Las entradas. La matriz de estructuras ARGB de 32 bits que forman este  Aspose.Imaging.ColorPalette .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
```


Obtiene el color de la paleta por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | El índice de color de la paleta. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Obtiene una matriz de  com.aspose.psd.Color  estructuras.

**Returns:**
com.aspose.psd.Color[] - Las entradas. La matriz de  com.aspose.psd.Color  estructura que forman este  Aspose.Imaging.ColorPalette .
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Obtiene el recuento de entradas.

**Returns:**
int - El recuento de entradas.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
```


Obtiene el índice del color más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | El color. |

**Returns:**
int - El índice del color más cercano.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public int getNearestColorIndex(int argb32Color)
```


Obtiene el índice del color más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb32Color | int | El color ARGB de 32 bits. |

**Returns:**
int - El índice del color más cercano.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Obtiene o establece un valor que indica si se utiliza una paleta compacta.

**Returns:**
boolean -  true  si se utiliza una paleta compacta; de lo contrario,  false .

Una paleta compacta significa que la imagen contendrá solo las entradas de paleta especificadas si es posible; en otras palabras, la imagen será más compacta y ocupará menos espacio; de lo contrario, habrá 2^BitsPerPixel entradas y la imagen reservará más espacio para todas las posibles entradas de la paleta. Establecer este valor en true y cambiar las entradas de la paleta puede causar una penalización de rendimiento ya que puede producirse movimiento de datos, así que úselo con cuidado.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

