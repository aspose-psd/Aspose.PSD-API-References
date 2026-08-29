---
title: "CmykColorHelper"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Méthodes d'aide pour travailler avec la couleur CMYK présentée comme une valeur entière signée de 32 bits."
type: docs
weight: 18
url: /fr/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Méthodes d'aide pour travailler avec la couleur CMYK présentée comme une valeur entière signée de 32 bits. Fournit une API similaire à la structure  com.aspose.psd.CmykColor . Elle est plus légère car la couleur CMYK est présentée simplement comme Int32 plutôt que comme une structure avec des champs internes. Veuillez privilégier l'utilisation des méthodes statiques de cette classe lorsque cela est possible au lieu de la structure obsolète  com.aspose.psd.CmykColor .
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Crée un CMYK à partir de valeurs cyan, magenta, jaune et noir sur 32 bits. |
| [getC(int cmyk)](#getC-int-) | Obtient la valeur du composant cyan. |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | Obtient la valeur du composant noir. |
| [getM(int cmyk)](#getM-int-) | Obtient la valeur du composant magenta. |
| [getY(int cmyk)](#getY-int-) | Obtient la valeur du composant jaune. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | La conversion d'une couleur CMYK en couleur ARGB. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | La conversion de couleurs CMYK en couleurs ARGB. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | La conversion de couleurs CMYK en couleurs ARGB. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | La conversion d'une couleur CMYK en couleur ARGB en utilisant la conversion Icc avec les profils par défaut. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | La conversion d'une couleur CMYK en couleur ARGB en utilisant la conversion Icc avec un profil personnalisé. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec des profils personnalisés. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | La conversion d'une couleur ARGB en couleur CMYK. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | La conversion des couleurs ARGB en couleurs CMYK. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | La conversion d'une couleur ARGB en couleur CMYK. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | La conversion des couleurs ARGB en couleurs CMYK. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Convertit le RGB en CMYK. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | La conversion d'une couleur ARGB en couleur CMYK utilisant la conversion Icc avec les profils par défaut. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | La conversion d'une couleur ARGB en couleur CMYK utilisant la conversion Icc avec des profils personnalisés. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | La conversion des couleurs ARGB en couleurs CMYK utilisant la conversion Icc avec les profils par défaut. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | La conversion des couleurs ARGB en couleurs CMYK utilisant la conversion Icc avec des profils personnalisés. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Convertit le RGB en CMYK en utilisant des profils ICC personnalisés. |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Crée un CMYK à partir de valeurs cyan, magenta, jaune et noir sur 32 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cyan | int | Le composant cyan. Les valeurs valides sont de 0 à 255. |
| magenta | int | Le composant magenta. Les valeurs valides sont de 0 à 255. |
| jaune | int | Le composant jaune. Les valeurs valides sont de 0 à 255. |
| noir | int | Le composant noir. Les valeurs valides sont de 0 à 255. |

**Returns:**
int - La couleur CMYK présentée sous forme de valeur entière 32 bits.
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Obtient la valeur du composant cyan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmyk | int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |

**Returns:**
int - La valeur du composant cyan.
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


Obtient la valeur du composant noir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmyk | int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |

**Returns:**
int - La valeur du composant noir.
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Obtient la valeur du composant magenta.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmyk | int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |

**Returns:**
int - La valeur du composant magenta.
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Obtient la valeur du composant jaune.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmyk | int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |

**Returns:**
int - La valeur du composant jaune.
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


La conversion d'une couleur CMYK en couleur ARGB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


La conversion de couleurs CMYK en couleurs ARGB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |

**Returns:**
com.aspose.psd.Color[] - Les couleurs ARGB.
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


La conversion de couleurs CMYK en couleurs ARGB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |

**Returns:**
int[] - Les couleurs ARGB présentées sous forme de valeurs entières 32 bits.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


La conversion d'une couleur CMYK en couleur ARGB en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversion d'une couleur CMYK en couleur ARGB en utilisant la conversion Icc avec un profil personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixel | int | La couleur CMYK présentée sous forme de valeur entière 32 bits. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil Icc CMYK. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil Icc RGB. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | Les pixels CMYK présentés sous forme de valeurs entières 32 bits. |

**Returns:**
com.aspose.psd.Color[] - Les couleurs ARGB.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversion de couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | Les couleurs CMYK présentées sous forme de valeurs entières 32 bits. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil Icc CMYK. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil Icc RGB. |

**Returns:**
com.aspose.psd.Color[] - Les couleurs ARGB.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


La conversion d'une couleur ARGB en couleur CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | La couleur ARGB. |

**Returns:**
int - La couleur CMYK présentée sous forme de valeur entière 32 bits.
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


La conversion des couleurs ARGB en couleurs CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Les couleurs ARGB. |

**Returns:**
int[] - Les couleurs CMYK présentées sous forme de valeurs entières 32 bits.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


La conversion d'une couleur ARGB en couleur CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argbPixel | int | La couleur ARGB présentée sous forme d'une valeur entière 32 bits. |

**Returns:**
int - La couleur CMYK présentée sous forme de valeur entière 32 bits.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


La conversion des couleurs ARGB en couleurs CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argbPixels | int[] | Les couleurs ARGB présentées sous forme de valeurs entières 32 bits. |

**Returns:**
int[] - Les couleurs CMYK présentées sous forme de valeurs entières 32 bits.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Convertit le RGB en CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argbPixels | int[] | Les couleurs RGB présentées sous forme de valeurs entières 32 bits. |
| startIndex | int | L'index de départ de la couleur RGB. |
| length | int | Le nombre de pixels RGB à convertir. |

**Returns:**
byte[] - Les couleurs CMYK présentées sous forme d'un tableau d'octets.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


La conversion d'une couleur ARGB en couleur CMYK utilisant la conversion Icc avec les profils par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | La couleur ARGB. |

**Returns:**
int - La couleur CMYK présentée sous forme de valeur entière 32 bits.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversion d'une couleur ARGB en couleur CMYK utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | La couleur ARGB. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil Icc RGB. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil Icc CMYK. |

**Returns:**
int - La couleur CMYK présentée sous forme de valeur entière 32 bits.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


La conversion des couleurs ARGB en couleurs CMYK utilisant la conversion Icc avec les profils par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Les couleurs ARGB. |

**Returns:**
int[] - Les couleurs CMYK présentées sous forme de valeurs entières 32 bits.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversion des couleurs ARGB en couleurs CMYK utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Les couleurs ARGB. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil Icc RGB. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil Icc CMYK. |

**Returns:**
int[] - Les couleurs CMYK présentées sous forme de valeurs entières 32 bits.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Convertit le RGB en CMYK en utilisant des profils ICC personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Les couleurs RGB présentées sous forme de valeurs entières 32 bits. |
| startIndex | int | L'index de départ de la couleur RGB. |
| length | int | Le nombre de pixels RGB à convertir. |
| rgbIccStream | java.io.InputStream | Le flux du profil RGB. |
| cmykIccStream | java.io.InputStream | Le flux du profil CMYK. |

**Returns:**
byte[] - Les couleurs CMYK présentées sous forme d'un tableau d'octets.
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] |  |
| startIndex | int |  |
| length | int |  |
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

