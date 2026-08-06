---
title: "CmykColor"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La couleur CMYK du pixel."
type: docs
weight: 17
url: /fr/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

La couleur CMYK du pixel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Crée une structure CmykColor à partir de valeurs cyan, magenta, jaune et noir sur 32 bits. |
| [getC()](#getC--) | Obtient la valeur du composant cyan de cette structure com.aspose.psd.Color . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Obtient le vide. |
| [getK()](#getK--) | Obtient la valeur du composant noir de cette structure com.aspose.psd.Color . |
| [getM()](#getM--) | Obtient la valeur du composant magenta de cette structure com.aspose.psd.Color . |
| [getY()](#getY--) | Obtient la valeur du composant jaune de cette structure com.aspose.psd.Color . |
| [hashCode()](#hashCode--) | Le code de hachage obtenu. |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si cette  com.aspose.psd.Color  structure est non initialisée. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | La conversion de CMYKColor en couleur ARGB 32 bits utilisant la conversion icc avec les profils par défaut. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | La conversion de ARGB 32 bits en CMYKColor. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | La conversion de la couleur ARGB 32 bits en CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | La conversion de CMYKColor en Color. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | La conversion de CMYKColor en Color utilisant la conversion icc avec les profils par défaut. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | La conversion de CMYKColor en Color utilisant la conversion icc avec les profils par défaut. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | La conversion de CMYKColor en Color utilisant la conversion icc. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | La conversion de CMYKColor en Color utilisant la conversion icc avec les profils par défaut. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | La conversion de CMYKColor en Color utilisant la conversion icc. |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | La conversion de CMYKColor en Color utilisant la conversion icc. |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | La conversion de CMYKColor en Color utilisant la conversion icc. |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | La valeur to. |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
booléen
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Crée une structure CmykColor à partir de valeurs cyan, magenta, jaune et noir 32 bits. Cette méthode est obsolète. Veuillez utiliser le plus efficace CmykColorHelper\#fromComponents(int, int, int, int).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cyan | int | Le composant cyan. Les valeurs valides sont de 0 à 255. |
| magenta | int | Le composant magenta. Les valeurs valides sont de 0 à 255. |
| jaune | int | Le composant jaune. Les valeurs valides sont de 0 à 255. |
| noir | int | Le composant noir. Les valeurs valides sont de 0 à 255. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


Obtient la valeur du composant cyan de cette structure com.aspose.psd.Color .

**Returns:**
byte - La valeur du composant cyan de ce com.aspose.psd.Color.
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


Obtient le vide.

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


Obtient la valeur du composant noir de cette structure com.aspose.psd.Color .

Valeur : La valeur du composant noir de ce com.aspose.psd.Color.

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


Obtient la valeur du composant magenta de cette structure com.aspose.psd.Color .

**Returns:**
byte - La valeur du composant magenta de ce com.aspose.psd.Color.
### getY() {#getY--}
```
public byte getY()
```


Obtient la valeur du composant jaune de cette structure com.aspose.psd.Color .

**Returns:**
byte - La valeur du composant jaune de ce com.aspose.psd.Color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Le code de hachage obtenu.

**Returns:**
int - L'entier int.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtient une valeur indiquant si cette  com.aspose.psd.Color  structure est non initialisée.

**Returns:**
boolean - Cette propriété renvoie true si cette couleur n'est pas initialisée ; sinon, false.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

**Returns:**
booléen
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


La conversion de CMYKColor en couleur ARGB 32 bits utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser le plus efficace CmykColorHelper.toArgb32(int[]) .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Les pixels de type CMYKColor au format CMYK. |

**Returns:**
int[] - Le tableau de la couleur ARGB 32 bits.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


La conversion de ARGB 32 bits en CMYKColor. Cette méthode est obsolète. Veuillez utiliser le plus efficace CmykColorHelper.toCmyk(int) .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argbPixel | int | Le pixel du format ARGB 32 bits. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


La conversion de la couleur ARGB 32 bits en CMYKColor. Cette méthode est obsolète. Veuillez utiliser le plus efficace CmykColorHelper.toCmyk(int[]) .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argbPixels | int[] | Les pixels du format ARGB 32 bits. |

**Returns:**
com.aspose.psd.CmykColor[] - Le  Aspose:Imaging:CmykColor[] .
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


La conversion de CMYKColor en Color. Cette méthode est obsolète. Veuillez utiliser le plus efficace CmykColorHelper.toArgb(int) .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Les pixels de type CMYKColor au format CMYK. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


La conversion de CMYKColor en Color utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser le plus efficace CmykColorHelper.toArgb(int[]) .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Les pixels de type CMYKColor au format CMYK. |

**Returns:**
com.aspose.psd.Color[] - Le tableau des couleurs ARGB.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


La conversion de CMYKColor en Color utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser le plus efficace CmykColorHelper.toArgbIcc(int) .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Le pixel de type CMYKColor au format CMYK. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversion de CMYKColor en Color utilisant la conversion icc. Cette méthode est obsolète. Veuillez utiliser le plus efficace CmykColorHelper.toArgbIcc(int, Stream, Stream).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Le pixel de type CMYKColor au format CMYK. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil icc cmyk. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil icc rgb. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


La conversion de CMYKColor en Color utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser le plus efficace CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Les pixels de type CMYKColor au format CMYK. |

**Returns:**
com.aspose.psd.Color[] - Le com.aspose.psd.Color[] .
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversion de CMYKColor en Color utilisant la conversion icc. Cette méthode est obsolète. Veuillez utiliser le plus efficace CmykColorHelper.toArgbIcc(int[], InputStream, InputStream).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Les pixels de type CMYKColor au format CMYK. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil icc cmyk. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil icc rgb. |

**Returns:**
com.aspose.psd.Color[] - Le Aspose.Imaging.Color[] .
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


La conversion de CMYKColor en Color utilisant la conversion icc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Le pixel de type CMYKColor au format CMYK. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Le flux contenant le profil icc cmyk. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Le flux contenant le profil icc rgb. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


La conversion de CMYKColor en Color utilisant la conversion icc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Les pixels de type CMYKColor au format CMYK. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Le flux contenant le profil icc cmyk. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Le flux contenant le profil icc rgb. |

**Returns:**
com.aspose.psd.Color[] - Le Aspose.Imaging.Color[] .
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


La valeur to.

**Returns:**
long - Le long .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

