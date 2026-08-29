---
title: "CmykColorHelper"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Métodos auxiliares para trabajar con el color CMYK presentado como un valor entero de 32 bits con signo."
type: docs
weight: 18
url: /es/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Métodos auxiliares para trabajar con el color CMYK presentado como un valor entero de 32 bits con signo. Proporciona una API similar a la estructura com.aspose.psd.CmykColor. Es más liviano porque el color CMYK se presenta simplemente como Int32 en lugar de una estructura con campos internos. Por favor, prefiera usar los métodos estáticos de esta clase cuando sea posible en lugar de la estructura obsoleta com.aspose.psd.CmykColor.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Crea CMYK a partir de valores de cian, magenta, amarillo y negro de 32 bits. |
| [getC(int cmyk)](#getC-int-) | Obtiene el valor del componente cian. |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | Obtiene el valor del componente negro. |
| [getM(int cmyk)](#getM-int-) | Obtiene el valor del componente magenta. |
| [getY(int cmyk)](#getY-int-) | Obtiene el valor del componente amarillo. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | La conversión de color CMYK a color ARGB. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | La conversión de colores CMYK a colores ARGB. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | La conversión de colores CMYK a colores ARGB. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | La conversión de color CMYK a ARGB Color usando conversión Icc con perfiles predeterminados. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | La conversión de color CMYK a color ARGB usando conversión Icc con perfil personalizado. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | La conversión de color ARGB a color CMYK. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | La conversión de colores ARGB a colores CMYK. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | La conversión de color ARGB a color CMYK. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | La conversión de colores ARGB a colores CMYK. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Convierte RGB a CMYK. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Convierte RGB a CMYK usando perfiles ICC personalizados. |
| [toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Crea CMYK a partir de valores de cian, magenta, amarillo y negro de 32 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cian | int | El componente cian. Los valores válidos son de 0 a 255. |
| magenta | int | El componente magenta. Los valores válidos son de 0 a 255. |
| amarillo | int | El componente amarillo. Los valores válidos son de 0 a 255. |
| negro | int | El componente negro. Los valores válidos son de 0 a 255. |

**Returns:**
int - El color CMYK presentado como un valor entero de 32 bits.
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Obtiene el valor del componente cian.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns:**
int - El valor del componente cian.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


Obtiene el valor del componente negro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns:**
int - El valor del componente negro.
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Obtiene el valor del componente magenta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns:**
int - El valor del componente magenta.
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Obtiene el valor del componente amarillo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns:**
int - El valor del componente amarillo.
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




### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


La conversión de color CMYK a color ARGB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


La conversión de colores CMYK a colores ARGB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | int[] | Los colores CMYK presentados como valores enteros de 32 bits. |

**Returns:**
com.aspose.psd.Color[] - Los colores ARGB.
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


La conversión de colores CMYK a colores ARGB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | int[] | Los colores CMYK presentados como valores enteros de 32 bits. |

**Returns:**
int[] - Los colores ARGB presentados como valores enteros de 32 bits.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


La conversión de color CMYK a ARGB Color usando conversión Icc con perfiles predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversión de color CMYK a color ARGB usando conversión Icc con perfil personalizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | int | El color CMYK presentado como un valor entero de 32 bits. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil Icc CMYK. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil Icc RGB. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | int[] | Los píxeles CMYK presentados como valores enteros de 32 bits. |

**Returns:**
com.aspose.psd.Color[] - Los colores ARGB.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | int[] | Los colores CMYK presentados como valores enteros de 32 bits. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil Icc CMYK. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil Icc RGB. |

**Returns:**
com.aspose.psd.Color[] - Los colores ARGB.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


La conversión de color ARGB a color CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | El color ARGB. |

**Returns:**
int - El color CMYK presentado como un valor entero de 32 bits.
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


La conversión de colores ARGB a colores CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Los colores ARGB. |

**Returns:**
int[] - Los colores CMYK presentados como valores enteros de 32 bits.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


La conversión de color ARGB a color CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argbPixel | int | El color ARGB presentado como un valor entero de 32 bits. |

**Returns:**
int - El color CMYK presentado como un valor entero de 32 bits.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


La conversión de colores ARGB a colores CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argbPixels | int[] | Los colores ARGB presentados como valores enteros de 32 bits. |

**Returns:**
int[] - Los colores CMYK presentados como valores enteros de 32 bits.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Convierte RGB a CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argbPixels | int[] | Los colores RGB presentados como valores enteros de 32 bits. |
| startIndex | int | El índice de inicio del color RGB. |
| longitud | int | El número de píxeles RGB a convertir. |

**Returns:**
byte[] - Los colores CMYK presentados como una matriz de bytes.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


La conversión de color ARGB a color CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | El color ARGB. |

**Returns:**
int - El color CMYK presentado como un valor entero de 32 bits.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversión de color ARGB a color CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | El color ARGB. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil Icc RGB. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil Icc CMYK. |

**Returns:**
int - El color CMYK presentado como un valor entero de 32 bits.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Los colores ARGB. |

**Returns:**
int[] - Los colores CMYK presentados como valores enteros de 32 bits.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Los colores ARGB. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil Icc RGB. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil Icc CMYK. |

**Returns:**
int[] - Los colores CMYK presentados como valores enteros de 32 bits.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Convierte RGB a CMYK usando perfiles ICC personalizados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] | Los colores RGB presentados como valores enteros de 32 bits. |
| startIndex | int | El índice de inicio del color RGB. |
| longitud | int | El número de píxeles RGB a convertir. |
| rgbIccStream | java.io.InputStream | El flujo del perfil RGB. |
| cmykIccStream | java.io.InputStream | El flujo del perfil CMYK. |

**Returns:**
byte[] - Los colores CMYK presentados como una matriz de bytes.
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| píxeles | int[] |  |
| startIndex | int |  |
| longitud | int |  |
| rgbIccStream | com.aspose.ms.System.IO.Stream |  |
| cmykIccStream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
byte[]
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

