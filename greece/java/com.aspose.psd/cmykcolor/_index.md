---
title: "CmykColor"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Το χρώμα CMYK του pixel."
type: docs
weight: 17
url: /el/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

Το χρώμα CMYK του pixel.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Δημιουργεί μια δομή  CmykColor  από τιμές κυανής, ματζέντας, κίτρινης και μαύρης 32-bit. |
| [getC()](#getC--) | Λαμβάνει την τιμή του κυανίου συστατικού αυτής της δομής com.aspose.psd.Color. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Λαμβάνει το κενό. |
| [getK()](#getK--) | Λαμβάνει την τιμή του μαύρου συστατικού αυτής της δομής com.aspose.psd.Color. |
| [getM()](#getM--) | Λαμβάνει την τιμή του ματζέντα συστατικού αυτής της δομής com.aspose.psd.Color. |
| [getY()](#getY--) | Λαμβάνει την τιμή του κίτρινου συστατικού αυτής της δομής com.aspose.psd.Color. |
| [hashCode()](#hashCode--) | Η λήψη του κώδικα κατακερματισμού. |
| [isEmpty()](#isEmpty--) | Αποκτά μια τιμή που υποδεικνύει εάν αυτή η  com.aspose.psd.Color  δομή δεν έχει αρχικοποιηθεί. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | Η μετατροπή από CMYKColor σε 32-bit ARGB Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Η μετατροπή από 32-bit ARGB σε CMYKColor. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Η μετατροπή από χρώμα 32-bit ARGB σε CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | Η μετατροπή από CMYKColor σε Color. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc. |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc. |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc. |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | Η τιμή to. |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Δημιουργεί μια δομή CmykColor από τιμές 32-bit κυανίου, ματζέντα, κίτρινου και μαύρου. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτικό το CmykColorHelper\#fromComponents(int, int, int, int).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κυανό | int | Το κυανό συστατικό. Έγκυρες τιμές είναι 0 έως 255. |
| ματζέντα | int | Το ματζέντα συστατικό. Έγκυρες τιμές είναι 0 έως 255. |
| κίτρινο | int | Το κίτρινο συστατικό. Έγκυρες τιμές είναι 0 έως 255. |
| μαύρο | int | Το μαύρο συστατικό. Έγκυρες τιμές είναι 0 έως 255. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


Λαμβάνει την τιμή του κυανίου συστατικού αυτής της δομής com.aspose.psd.Color.

**Returns:**
byte - Η τιμή του κυανίου συστατικού αυτής της com.aspose.psd.Color .
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


Λαμβάνει το κενό.

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


Λαμβάνει την τιμή του μαύρου συστατικού αυτής της δομής com.aspose.psd.Color.

Τιμή: Η τιμή του μαύρου συστατικού αυτής της com.aspose.psd.Color .

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


Λαμβάνει την τιμή του ματζέντα συστατικού αυτής της δομής com.aspose.psd.Color.

**Returns:**
byte - Η τιμή του ματζέντα συστατικού αυτής της com.aspose.psd.Color .
### getY() {#getY--}
```
public byte getY()
```


Λαμβάνει την τιμή του κίτρινου συστατικού αυτής της δομής com.aspose.psd.Color.

**Returns:**
byte - Η τιμή του κίτρινου συστατικού αυτής της com.aspose.psd.Color .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Η λήψη του κώδικα κατακερματισμού.

**Returns:**
int - Το int.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Αποκτά μια τιμή που υποδεικνύει εάν αυτή η  com.aspose.psd.Color  δομή δεν έχει αρχικοποιηθεί.

**Returns:**
boolean - Αυτή η ιδιότητα επιστρέφει true εάν αυτό το χρώμα δεν έχει αρχικοποιηθεί· διαφορετικά, false.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Η μετατροπή από CMYKColor σε 32-bit ARGB Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτικό το CmykColorHelper.toArgb32(int[]) .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Τα pixel τύπου CMYKColor σε μορφή CMYK. |

**Returns:**
int[] - Ο πίνακας του χρώματος 32-bit ARGB.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


Η μετατροπή από 32-bit ARGB σε CMYKColor. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτικό το CmykColorHelper.toCmyk(int) .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argbPixel | int | Το pixel της μορφής 32-bit ARGB. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


Η μετατροπή από χρώμα 32-bit ARGB σε CMYKColor. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτικό το CmykColorHelper.toCmyk(int[]) .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argbPixels | int[] | Τα pixel της μορφής 32-bit ARGB. |

**Returns:**
com.aspose.psd.CmykColor[] - Το  Aspose:Imaging:CmykColor[] .
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


Η μετατροπή από CMYKColor σε Color. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτικό  CmykColorHelper.toArgb(int) .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Τα pixel τύπου CMYKColor σε μορφή CMYK. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτικό  CmykColorHelper.toArgb(int[]) .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Τα pixel τύπου CMYKColor σε μορφή CMYK. |

**Returns:**
com.aspose.psd.Color[] - Ο πίνακας των χρωμάτων ARGB.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτικό  CmykColorHelper.toArgbIcc(int) .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Το pixel τύπου CMYKColor σε μορφή CMYK. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτικό  CmykColorHelper.toArgbIcc(int, Stream, Stream) .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Το pixel τύπου CMYKColor σε μορφή CMYK. |
| cmykIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ icc cmyk. |
| rgbIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ icc rgb. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτικό CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Τα pixel τύπου CMYKColor σε μορφή CMYK. |

**Returns:**
com.aspose.psd.Color[] - Το  com.aspose.psd.Color[] .
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτικό  CmykColorHelper.toArgbIcc(int[], InputStream, InputStream) .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Τα pixel τύπου CMYKColor σε μορφή CMYK. |
| cmykIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ icc cmyk. |
| rgbIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ icc rgb. |

**Returns:**
com.aspose.psd.Color[] - Το  Aspose.Imaging.Color[] .
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Το pixel τύπου CMYKColor σε μορφή CMYK. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Η ροή που περιέχει το προφίλ icc cmyk. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Η ροή που περιέχει το προφίλ icc rgb. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Τα pixel τύπου CMYKColor σε μορφή CMYK. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Η ροή που περιέχει το προφίλ icc cmyk. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Η ροή που περιέχει το προφίλ icc rgb. |

**Returns:**
com.aspose.psd.Color[] - Το  Aspose.Imaging.Color[] .
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


Η τιμή to.

**Returns:**
long - Το  long .
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

