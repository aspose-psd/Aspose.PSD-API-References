---
title: "CmykColor"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El color CMYK del píxel."
type: docs
weight: 17
url: /es/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

El color CMYK del píxel.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Crea una estructura  CmykColor  a partir de valores de cian, magenta, amarillo y negro de 32 bits. |
| [getC()](#getC--) | Obtiene el valor del componente cian de esta  com.aspose.psd.Color  estructura. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Obtiene el vacío. |
| [getK()](#getK--) | Obtiene el valor del componente negro de esta  com.aspose.psd.Color  estructura. |
| [getM()](#getM--) | Obtiene el valor del componente magenta de esta  com.aspose.psd.Color  estructura. |
| [getY()](#getY--) | Obtiene el valor del componente amarillo de esta  com.aspose.psd.Color  estructura. |
| [hashCode()](#hashCode--) | El código hash. |
| [isEmpty()](#isEmpty--) | Obtiene un valor que indica si esta estructura  com.aspose.psd.Color  está sin inicializar. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | La conversión de CMYKColor a Color ARGB de 32 bits usando conversión icc con perfiles predeterminados. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | La conversión de ARGB de 32 bits a CMYKColor. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | La conversión de color ARGB de 32 bits a CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | La conversión de CMYKColor a Color. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | La conversión de CMYKColor a Color usando conversión icc. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | La conversión de CMYKColor a Color usando conversión icc. |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | La conversión de CMYKColor a Color usando conversión icc. |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | La conversión de CMYKColor a Color usando conversión icc. |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | El valor to. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CmykColor() {#CmykColor--}
```
public CmykColor()
```


### Clone() {#Clone--}
```
public CmykColor Clone()
```




**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Crea una  CmykColor  estructura a partir de valores cian, magenta, amarillo y negro de 32 bits. Este método está obsoleto. Por favor, use CmykColorHelper\\#fromComponents(int, int, int, int) más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cian | int | El componente cian. Los valores válidos son de 0 a 255. |
| magenta | int | El componente magenta. Los valores válidos son de 0 a 255. |
| amarillo | int | El componente amarillo. Los valores válidos son de 0 a 255. |
| negro | int | El componente negro. Los valores válidos son de 0 a 255. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


Obtiene el valor del componente cian de esta  com.aspose.psd.Color  estructura.

**Returns:**
byte - El valor del componente cian de este  com.aspose.psd.Color .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static CmykColor getEmpty()
```


Obtiene el vacío.

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


Obtiene el valor del componente negro de esta  com.aspose.psd.Color  estructura.

Valor: El valor del componente negro de este  com.aspose.psd.Color .

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


Obtiene el valor del componente magenta de esta  com.aspose.psd.Color  estructura.

**Returns:**
byte - El valor del componente magenta de este  com.aspose.psd.Color .
### getY() {#getY--}
```
public byte getY()
```


Obtiene el valor del componente amarillo de esta  com.aspose.psd.Color  estructura.

**Returns:**
byte - El valor del componente amarillo de este  com.aspose.psd.Color .
### hashCode() {#hashCode--}
```
public int hashCode()
```


El código hash.

**Returns:**
int - El  int .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtiene un valor que indica si esta estructura  com.aspose.psd.Color  está sin inicializar.

**Returns:**
boolean - Esta propiedad devuelve true si este color no está inicializado; de lo contrario, false.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

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




### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.psd.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


La conversión de CMYKColor a Color ARGB de 32 bits usando conversión icc con perfiles predeterminados. Este método está obsoleto. Por favor, use  CmykColorHelper.toArgb32(int[]) más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Los píxeles de tipo CMYKColor en formato CMYK. |

**Returns:**
int[] - La matriz del color ARGB de 32 bits.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


La conversión de ARGB de 32 bits a CMYKColor. Este método está obsoleto. Por favor, use  CmykColorHelper.toCmyk(int) más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argbPixel | int | El píxel del formato ARGB de 32 bits. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


La conversión de color ARGB de 32 bits a CMYKColor. Este método está obsoleto. Por favor, use  CmykColorHelper.toCmyk(int[]) más eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argbPixels | int[] | Los píxeles del formato ARGB de 32 bits. |

**Returns:**
com.aspose.psd.CmykColor[] - El  Aspose:Imaging:CmykColor[] .
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


La conversión de CMYKColor a Color. Este método está obsoleto. Por favor, use una versión más eficaz  CmykColorHelper.toArgb(int) .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Los píxeles de tipo CMYKColor en formato CMYK. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. Este método está obsoleto. Por favor, use una versión más eficaz  CmykColorHelper.toArgb(int[]) .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Los píxeles de tipo CMYKColor en formato CMYK. |

**Returns:**
com.aspose.psd.Color[] - La matriz de los colores ARGB.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. Este método está obsoleto. Por favor, use una versión más eficaz  CmykColorHelper.toArgbIcc(int) .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | El píxel del tipo CMYKColor en formato CMYK. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversión de CMYKColor a Color usando conversión icc. Este método está obsoleto. Por favor, use una versión más eficaz  CmykColorHelper.toArgbIcc(int, Stream, Stream) .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | El píxel del tipo CMYKColor en formato CMYK. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil icc cmyk. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil icc rgb. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados. Este método está obsoleto. Por favor, use una versión más eficaz CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Los píxeles de tipo CMYKColor en formato CMYK. |

**Returns:**
com.aspose.psd.Color[] - El  com.aspose.psd.Color[] .
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversión de CMYKColor a Color usando conversión icc. Este método está obsoleto. Por favor, use una versión más eficaz  CmykColorHelper.toArgbIcc(int[], InputStream, InputStream) .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Los píxeles de tipo CMYKColor en formato CMYK. |
| cmykIccStream | java.io.InputStream | El flujo que contiene el perfil icc cmyk. |
| rgbIccStream | java.io.InputStream | El flujo que contiene el perfil icc rgb. |

**Returns:**
com.aspose.psd.Color[] - El  Aspose.Imaging.Color[] .
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


La conversión de CMYKColor a Color usando conversión icc.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | El píxel del tipo CMYKColor en formato CMYK. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | El flujo que contiene el perfil icc cmyk. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | El flujo que contiene el perfil icc rgb. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


La conversión de CMYKColor a Color usando conversión icc.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Los píxeles de tipo CMYKColor en formato CMYK. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | El flujo que contiene el perfil icc cmyk. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | El flujo que contiene el perfil icc rgb. |

**Returns:**
com.aspose.psd.Color[] - El  Aspose.Imaging.Color[] .
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toValue() {#toValue--}
```
public long toValue()
```


El valor to.

**Returns:**
long - El  long .
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

