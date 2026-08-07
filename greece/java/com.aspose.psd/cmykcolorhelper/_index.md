---
title: "CmykColorHelper"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Βοηθητικές μέθοδοι για εργασία με χρώμα CMYK που παρουσιάζεται ως υπογεγραμμένη τιμή 32-bit ακέραιου."
type: docs
weight: 18
url: /el/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Βοηθητικές μέθοδοι για εργασία με χρώμα CMYK που παρουσιάζεται ως υπογεγραμμένη 32-bit ακέραια τιμή. Παρέχει παρόμοιο API με τη δομή  com.aspose.psd.CmykColor  . Είναι πιο ελαφρύ επειδή το χρώμα CMYK παρουσιάζεται μόνο ως Int32 αντί για δομή με εσωτερικά πεδία. Παρακαλώ προτιμήστε τη χρήση στατικών μεθόδων αυτής της κλάσης όταν είναι δυνατόν αντί για την αποσυρμένη δομή  com.aspose.psd.CmykColor  .
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Δημιουργεί CMYK από τιμές 32-bit κυανίου, ματζέντας, κίτρινου και μαύρου. |
| [getC(int cmyk)](#getC-int-) | Επιστρέφει την τιμή του συστατικού κυανίου. |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | Επιστρέφει την τιμή του συστατικού μαύρου. |
| [getM(int cmyk)](#getM-int-) | Επιστρέφει την τιμή του συστατικού ματζέντας. |
| [getY(int cmyk)](#getY-int-) | Επιστρέφει την τιμή του συστατικού κίτρινου. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | Η μετατροπή από χρώμα CMYK σε χρώμα ARGB. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | Η μετατροπή από χρώμα CMYK σε χρώμα ARGB χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | Η μετατροπή από χρώμα CMYK σε χρώμα ARGB χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένο προφίλ. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | Η μετατροπή από χρώμα ARGB σε χρώμα CMYK. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Η μετατροπή από χρώμα ARGB σε χρώμα CMYK. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Μετατρέπει RGB σε CMYK. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | Η μετατροπή από χρώμα ARGB σε χρώμα CMYK χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | Η μετατροπή από χρώμα ARGB σε χρώμα CMYK χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Μετατρέπει RGB σε CMYK χρησιμοποιώντας προσαρμοσμένα προφίλ ICC. |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Δημιουργεί CMYK από τιμές 32-bit κυανίου, ματζέντας, κίτρινου και μαύρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κυανό | int | Το κυανό συστατικό. Έγκυρες τιμές είναι 0 έως 255. |
| ματζέντα | int | Το ματζέντα συστατικό. Έγκυρες τιμές είναι 0 έως 255. |
| κίτρινο | int | Το κίτρινο συστατικό. Έγκυρες τιμές είναι 0 έως 255. |
| μαύρο | int | Το μαύρο συστατικό. Έγκυρες τιμές είναι 0 έως 255. |

**Returns:**
int - Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit.
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Επιστρέφει την τιμή του συστατικού κυανίου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmyk | int | Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit. |

**Returns:**
int - Η τιμή του κυανό συστατικού.
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


Επιστρέφει την τιμή του συστατικού μαύρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmyk | int | Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit. |

**Returns:**
int - Η τιμή του μαύρου συστατικού.
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Επιστρέφει την τιμή του συστατικού ματζέντας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmyk | int | Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit. |

**Returns:**
int - Η τιμή του ματζέντα συστατικού.
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Επιστρέφει την τιμή του συστατικού κίτρινου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmyk | int | Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit. |

**Returns:**
int - Η τιμή του κίτρινου συστατικού.
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


Η μετατροπή από χρώμα CMYK σε χρώμα ARGB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixel | int | Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


Η μετατροπή από χρώματα CMYK σε χρώματα ARGB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixels | int[] | Τα χρώματα CMYK που παρουσιάζονται ως τιμές 32-bit ακέραιου. |

**Returns:**
com.aspose.psd.Color[] - Τα χρώματα ARGB.
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


Η μετατροπή από χρώματα CMYK σε χρώματα ARGB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixels | int[] | Τα χρώματα CMYK που παρουσιάζονται ως τιμές 32-bit ακέραιου. |

**Returns:**
int[] - Τα χρώματα ARGB που παρουσιάζονται ως τιμές 32-bit ακέραιου.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


Η μετατροπή από χρώμα CMYK σε χρώμα ARGB χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixel | int | Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Η μετατροπή από χρώμα CMYK σε χρώμα ARGB χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένο προφίλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixel | int | Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit. |
| cmykIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ CMYK Icc. |
| rgbIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ RGB Icc. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixels | int[] | Τα pixel CMYK που παρουσιάζονται ως τιμές 32-bit ακέραιου. |

**Returns:**
com.aspose.psd.Color[] - Τα χρώματα ARGB.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixels | int[] | Τα χρώματα CMYK που παρουσιάζονται ως τιμές 32-bit ακέραιου. |
| cmykIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ CMYK Icc. |
| rgbIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ RGB Icc. |

**Returns:**
com.aspose.psd.Color[] - Τα χρώματα ARGB.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


Η μετατροπή από χρώμα ARGB σε χρώμα CMYK.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Το χρώμα ARGB. |

**Returns:**
int - Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit.
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


Η μετατροπή από χρώματα ARGB σε χρώματα CMYK.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Τα χρώματα ARGB. |

**Returns:**
int[] - Τα χρώματα CMYK που παρουσιάζονται ως τιμές 32-bit ακέραιου.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


Η μετατροπή από χρώμα ARGB σε χρώμα CMYK.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argbPixel | int | Το χρώμα ARGB που παρουσιάζεται ως τιμή 32-bit ακέραιου. |

**Returns:**
int - Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


Η μετατροπή από χρώματα ARGB σε χρώματα CMYK.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argbPixels | int[] | Τα χρώματα ARGB που παρουσιάζονται ως τιμές 32-bit ακέραιου. |

**Returns:**
int[] - Τα χρώματα CMYK που παρουσιάζονται ως τιμές 32-bit ακέραιου.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Μετατρέπει RGB σε CMYK.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argbPixels | int[] | Τα χρώματα RGB που παρουσιάζονται ως τιμές 32-bit ακέραιου. |
| startIndex | int | Ο αρχικός δείκτης του χρώματος RGB. |
| μήκος | int | Ο αριθμός των pixel RGB προς μετατροπή. |

**Returns:**
byte[] - Τα χρώματα CMYK που παρουσιάζονται ως πίνακας byte.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


Η μετατροπή από χρώμα ARGB σε χρώμα CMYK χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Το χρώμα ARGB. |

**Returns:**
int - Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Η μετατροπή από χρώμα ARGB σε χρώμα CMYK χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Το χρώμα ARGB. |
| rgbIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ RGB Icc. |
| cmykIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ CMYK Icc. |

**Returns:**
int - Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Τα χρώματα ARGB. |

**Returns:**
int[] - Τα χρώματα CMYK που παρουσιάζονται ως τιμές 32-bit ακέραιου.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Τα χρώματα ARGB. |
| rgbIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ RGB Icc. |
| cmykIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ CMYK Icc. |

**Returns:**
int[] - Τα χρώματα CMYK που παρουσιάζονται ως τιμές 32-bit ακέραιου.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Μετατρέπει RGB σε CMYK χρησιμοποιώντας προσαρμοσμένα προφίλ ICC.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixels | int[] | Τα χρώματα RGB που παρουσιάζονται ως τιμές 32-bit ακέραιου. |
| startIndex | int | Ο αρχικός δείκτης του χρώματος RGB. |
| μήκος | int | Ο αριθμός των pixel RGB προς μετατροπή. |
| rgbIccStream | java.io.InputStream | Η ροή προφίλ RGB. |
| cmykIccStream | java.io.InputStream | Η ροή προφίλ CMYK. |

**Returns:**
byte[] - Τα χρώματα CMYK που παρουσιάζονται ως πίνακας byte.
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixels | int[] |  |
| startIndex | int |  |
| μήκος | int |  |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

