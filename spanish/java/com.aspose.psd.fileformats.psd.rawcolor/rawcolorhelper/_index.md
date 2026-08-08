---
title: "RawColorHelper"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La clase Raw Color Helper ayuda a crear RawColor más rápido usando metadatos de canal predefinidos."
type: docs
weight: 12
url: /es/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Raw Color Helper Class ayuda a crear RawColor más rápido, usando metadatos de canal predefinidos
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | Crea un color ARGB de 16 bits por canal. |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | Crea un color ARGB de 8 bits por canal. |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Crea un color ARGB de 8 bits por canal a partir de Drawing.Color |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | Crea un color CMYK de 16 bits por canal. |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | Crea un color CMYK de 8 bits por canal. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColorHelper() {#RawColorHelper--}
```
public RawColorHelper()
```


### createArgb16BitColor(int a, int r, int g, int b) {#createArgb16BitColor-int-int-int-int-}
```
public static RawColor createArgb16BitColor(int a, int r, int g, int b)
```


Crea un color ARGB de 16 bits por canal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | int | El valor del componente alfa (0-65535). |
| r | int | El valor del componente rojo (0-65535). |
| g | int | El valor del componente verde (0-65535). |
|  | b | int | El valor del componente azul (0-65535). |

--------------------

Los componentes de color se empaquetan en un entero de 64 bits en el siguiente orden: alfa (bits 48-63), rojo (bits 32-47), verde (bits 16-31) y azul (bits 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


Crea un color ARGB de 8 bits por canal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | byte | El valor del componente alfa (0-255). |
| r | byte | El valor del componente rojo (0-255). |
| g | byte | El valor del componente verde (0-255). |
|  | b | byte | El valor del componente azul (0-255). |

--------------------

Los componentes de color se empaquetan en un entero de 32 bits en el siguiente orden: alfa (bits 24-31), rojo (bits 16-23), verde (bits 8-15) y azul (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Crea un color ARGB de 8 bits por canal a partir de Drawing.Color

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | El color System.Drawing |

--------------------

Los componentes de color se empaquetan en un entero de 32 bits en el siguiente orden: alfa (bits 24-31), rojo (bits 16-23), verde (bits 8-15) y azul (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


Crea un color CMYK de 16 bits por canal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | int | El valor del componente cian (0-65535). |
| m | int | El valor del componente magenta (0-65535). |
| y | int | El valor del componente amarillo (0-65535). |
|  | k | int | El valor del componente clave (negro) (0-65535). |

--------------------

Los componentes de color se empaquetan en un entero de 64 bits en el orden: cian (bits 48-63), magenta (bits 32-47), amarillo (bits 16-31) y clave/negro (bits 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


Crea un color CMYK de 8 bits por canal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | byte | El valor del componente cian (0-255). |
| m | byte | El valor del componente magenta (0-255). |
| y | byte | El valor del componente amarillo (0-255). |
|  | k | byte | El valor del componente clave (negro) (0-255). |

--------------------

Los componentes de color se empaquetan en un entero de 32 bits en el orden: cian (bits 24-31), magenta (bits 16-23), amarillo (bits 8-15) y clave/negro (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
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

