---
title: "RawColorHelper"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Raw Color Helper Class βοηθά στη δημιουργία του RawColor πιο γρήγορα χρησιμοποιώντας προ-ορισμένα μεταδεδομένα καναλιού"
type: docs
weight: 12
url: /el/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Η Raw Color Helper Class βοηθά στη γρήγορη δημιουργία του RawColor, χρησιμοποιώντας προ‑ορισμένα μεταδεδομένα καναλιού.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | Δημιουργεί ένα χρώμα ARGB 16-bit ανά κανάλι. |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | Δημιουργεί ένα χρώμα ARGB 8-bit ανά κανάλι. |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Δημιουργεί ένα χρώμα ARGB 8-bit ανά κανάλι από το Drawing.Color |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | Δημιουργεί ένα χρώμα CMYK 16-bit ανά κανάλι. |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | Δημιουργεί ένα χρώμα CMYK 8-bit ανά κανάλι. |
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


Δημιουργεί ένα χρώμα ARGB 16-bit ανά κανάλι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| α | int | Η τιμή του συστατικού άλφα (0-65535). |
| r | int | Η τιμή του κόκκινου συστατικού (0-65535). |
| g | int | Η τιμή του πράσινου συστατικού (0-65535). |
|  | β | int | Η τιμή του μπλε συστατικού (0-65535). |

--------------------

Τα συστατικά του χρώματος συσκευάζονται σε έναν 64-bit ακέραιο με τη σειρά: άλφα (bits 48-63), κόκκινο (bits 32-47), πράσινο (bits 16-31) και μπλε (bits 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


Δημιουργεί ένα χρώμα ARGB 8-bit ανά κανάλι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| α | byte | Η τιμή του συστατικού άλφα (0-255). |
| r | byte | Η τιμή του κόκκινου συστατικού (0-255). |
| g | byte | Η τιμή του πράσινου συστατικού (0-255). |
|  | β | byte | Η τιμή του μπλε συστατικού (0-255). |

--------------------

Τα συστατικά του χρώματος συσκευάζονται σε έναν 32-bit ακέραιο με τη σειρά: άλφα (bits 24-31), κόκκινο (bits 16-23), πράσινο (bits 8-15) και μπλε (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Δημιουργεί ένα χρώμα ARGB 8-bit ανά κανάλι από το Drawing.Color

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | Το System.Drawing Color |

--------------------

Τα συστατικά του χρώματος συσκευάζονται σε έναν 32-bit ακέραιο με τη σειρά: άλφα (bits 24-31), κόκκινο (bits 16-23), πράσινο (bits 8-15) και μπλε (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


Δημιουργεί ένα χρώμα CMYK 16-bit ανά κανάλι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| c | int | Η τιμή του κυανίου συστατικού (0-65535). |
| m | int | Η τιμή του συστατικού ματζέντα (0-65535). |
| y | int | Η τιμή του συστατικού κίτρινο (0-65535). |
|  | k | int | Η τιμή του συστατικού κλειδί (μαύρο) (0-65535). |

--------------------

Τα χρωματικά συστατικά συσκευάζονται σε έναν ακέραιο 64-bit με τη σειρά: κυανό (bits 48-63), ματζέντα (bits 32-47), κίτρινο (bits 16-31), και κλειδί/μαύρο (bits 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


Δημιουργεί ένα χρώμα CMYK 8-bit ανά κανάλι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| c | byte | Η τιμή του συστατικού κυανό (0-255). |
| m | byte | Η τιμή του συστατικού ματζέντα (0-255). |
| y | byte | Η τιμή του συστατικού κίτρινο (0-255). |
|  | k | byte | Η τιμή του συστατικού κλειδί (μαύρο) (0-255). |

--------------------

Τα χρωματικά συστατικά συσκευάζονται σε έναν ακέραιο 32-bit με τη σειρά: κυανό (bits 24-31), ματζέντα (bits 16-23), κίτρινο (bits 8-15), και κλειδί/μαύρο (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
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

