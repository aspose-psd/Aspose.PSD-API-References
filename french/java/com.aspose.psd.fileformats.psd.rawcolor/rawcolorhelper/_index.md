---
title: "RawColorHelper"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La classe Raw Color Helper aide à créer RawColor plus rapidement en utilisant des métadonnées de canal prédéfinies"
type: docs
weight: 12
url: /fr/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Raw Color Helper Class aide à créer RawColor plus rapidement, en utilisant des métadonnées de canal prédéfinies.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | Crée une couleur ARGB de 16 bits par canal. |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | Crée une couleur ARGB de 8 bits par canal. |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Crée une couleur ARGB de 8 bits par canal à partir de Drawing.Color |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | Crée une couleur CMYK de 16 bits par canal. |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | Crée une couleur CMYK de 8 bits par canal. |
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


Crée une couleur ARGB de 16 bits par canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | int | La valeur du composant alpha (0-65535). |
| r | int | La valeur du composant rouge (0-65535). |
| g | int | La valeur du composant vert (0-65535). |
|  | b | int | La valeur du composant bleu (0-65535). |

--------------------

Les composants de couleur sont empaquetés dans un entier de 64 bits dans l'ordre : alpha (bits 48-63), rouge (bits 32-47), vert (bits 16-31) et bleu (bits 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


Crée une couleur ARGB de 8 bits par canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | byte | La valeur du composant alpha (0-255). |
| r | byte | La valeur du composant rouge (0-255). |
| g | byte | La valeur du composant vert (0-255). |
|  | b | byte | La valeur du composant bleu (0-255). |

--------------------

Les composants de couleur sont empaquetés dans un entier de 32 bits dans l'ordre : alpha (bits 24-31), rouge (bits 16-23), vert (bits 8-15) et bleu (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Crée une couleur ARGB de 8 bits par canal à partir de Drawing.Color

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | La couleur System.Drawing |

--------------------

Les composants de couleur sont empaquetés dans un entier de 32 bits dans l'ordre : alpha (bits 24-31), rouge (bits 16-23), vert (bits 8-15) et bleu (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


Crée une couleur CMYK de 16 bits par canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| c | int | La valeur du composant cyan (0-65535). |
| m | int | La valeur du composant magenta (0-65535). |
| y | int | La valeur du composant jaune (0-65535). |
|  | k | int | La valeur du composant clé (noir) (0-65535). |

--------------------

Les composants de couleur sont empaquetés dans un entier 64 bits dans l'ordre : cyan (bits 48-63), magenta (bits 32-47), jaune (bits 16-31) et clé/noir (bits 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


Crée une couleur CMYK de 8 bits par canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| c | byte | La valeur du composant cyan (0-255). |
| m | byte | La valeur du composant magenta (0-255). |
| y | byte | La valeur du composant jaune (0-255). |
|  | k | byte | La valeur du composant clé (noir) (0-255). |

--------------------

Les composants de couleur sont empaquetés dans un entier 32 bits dans l'ordre : cyan (bits 24-31), magenta (bits 16-23), jaune (bits 8-15) et clé/noir (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
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

