---
title: "PsdColorPalette"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η παλέτα χρώματος PSD."
type: docs
weight: 13
url: /el/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

Η παλέτα χρώματος PSD.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) και το IsCompactPalette είναι ψευδές. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) και το IsCompactPalette είναι ψευδές. |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) και το IsCompactPalette είναι ψευδές. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) και το IsCompactPalette είναι ψευδές. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Αντιγράφει την παλέτα. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Αντιγράφει την παλέτα. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Λαμβάνει το χρώμα παλέτας ARGB 32-bit με βάση το δείκτη. |
| [getArgb32Entries()](#getArgb32Entries--) | Λαμβάνει έναν πίνακα 32-bit χρωμάτων ARGB. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Λαμβάνει το χρώμα της παλέτας με βάση το δείκτη. |
| [getEntries()](#getEntries--) | Λαμβάνει έναν πίνακα δομών [Color](../../com.aspose.psd/color). |
| [getEntriesCount()](#getEntriesCount--) | Λαμβάνει τον αριθμό των καταχωρήσεων. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Λαμβάνει το ευρετήριο του πλησιέστερου χρώματος. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Λαμβάνει το ευρετήριο του πλησιέστερου χρώματος. |
| [getRawEntries()](#getRawEntries--) | Λαμβάνει τα ακατέργαστα δεδομένα καταχωρήσεων της παλέτας χρωμάτων. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Λαμβάνει τον αριθμό των ακατέργαστων καταχωρήσεων της παλέτας χρωμάτων. |
| [getTransparentColor()](#getTransparentColor--) | Λαμβάνει το διαφανές χρώμα. |
| [getTransparentIndex()](#getTransparentIndex--) | Λαμβάνει το ευρετήριο του διαφανούς χρώματος. |
| [hasTransparentColor()](#hasTransparentColor--) | Λαμβάνει μια τιμή που υποδεικνύει αν υπάρχει διαφανές χρώμα. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Λαμβάνει μια τιμή που υποδεικνύει αν η παλέτα είναι συμπαγής. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdColorPalette(IColorPalette colorPalette) {#PsdColorPalette-com.aspose.psd.IColorPalette-}
```
public PsdColorPalette(IColorPalette colorPalette)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |
| transparentIndex | short | Το ευρετήριο του διαφανούς χρώματος. |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rawEntriesData | byte[] | Τα ακατέργαστα δεδομένα καταχωρήσεων. |
| isCompactPalette | boolean | Δείχνει αν η παλέτα είναι συμπαγής. |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) και το IsCompactPalette είναι ψευδές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rawEntriesData | byte[] | Τα ακατέργαστα δεδομένα καταχωρήσεων. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rawEntriesData | byte[] | Τα ακατέργαστα δεδομένα καταχωρήσεων. |
| transparentIndex | short | Το ευρετήριο του διαφανούς χρώματος. Σημείωση: το ευρετήριο δεν είναι το ευρετήριο των ακατέργαστων καταχωρήσεων, αλλά αφορά τον μετατρεπόμενο πίνακα χρωμάτων. |
| useCompactPalette | boolean | Δείχνει αν η παλέτα είναι συμπαγής. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) και το IsCompactPalette είναι ψευδές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rawEntriesData | byte[] | Τα ακατέργαστα δεδομένα καταχωρήσεων. |
| transparentIndex | short | Το ευρετήριο του διαφανούς χρώματος. Σημείωση: το ευρετήριο δεν είναι το ευρετήριο των ακατέργαστων καταχωρήσεων, αλλά αφορά τον μετατρεπόμενο πίνακα χρωμάτων. |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | Οι 32-bit ARGB καταχωρήσεις της παλέτας χρωμάτων. |
| isCompactPalette | boolean | Δείχνει αν η παλέτα είναι συμπαγής. |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Οι καταχωρήσεις της παλέτας χρωμάτων. |
| isCompactPalette | boolean | Δείχνει αν η παλέτα είναι συμπαγής. |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) και το IsCompactPalette είναι ψευδές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Οι καταχωρήσεις της παλέτας χρωμάτων. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Οι καταχωρήσεις της παλέτας χρωμάτων. |
| transparentIndex | short | Το ευρετήριο του διαφανούς χρώματος. |
| useCompactPalette | boolean | Δείχνει αν η παλέτα είναι συμπαγής. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) και το IsCompactPalette είναι ψευδές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Οι καταχωρήσεις της παλέτας χρωμάτων. |
| transparentIndex | short | Το ευρετήριο του διαφανούς χρώματος. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


Αντιγράφει την παλέτα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Αντιγράφει την παλέτα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |
| useCompactPalette | boolean | Δείχνει αν η παλέτα είναι συμπαγής. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
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
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public final int getArgb32Color(int index)
```


Λαμβάνει το χρώμα παλέτας ARGB 32-bit με βάση το δείκτη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Το ευρετήριο χρώματος της 32-bit ARGB παλέτας. |

**Returns:**
int - Η καταχώρηση της παλέτας χρωμάτων που καθορίζεται από το ευρετήριο.
### getArgb32Entries() {#getArgb32Entries--}
```
public final int[] getArgb32Entries()
```


Λαμβάνει έναν πίνακα 32-bit χρωμάτων ARGB.

**Returns:**
int[] - Ο πίνακας των δομών 32-bit ARGB που αποτελούν αυτή τη [ColorPalette](../../com.aspose.psd/colorpalette). Τιμή: Οι καταχωρήσεις.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public final Color getColor(int index)
```


Λαμβάνει το χρώμα της παλέτας με βάση το δείκτη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Το ευρετήριο χρώματος της παλέτας. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public final Color[] getEntries()
```


Λαμβάνει έναν πίνακα δομών [Color](../../com.aspose.psd/color).

**Returns:**
com.aspose.psd.Color[] - Ο πίνακας των δομών [Color](../../com.aspose.psd/color) που αποτελούν αυτή τη [ColorPalette](../../com.aspose.psd/colorpalette). Τιμή: Οι καταχωρήσεις.
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


Λαμβάνει τον αριθμό των καταχωρήσεων.

Τιμή: Ο αριθμός των καταχωρήσεων.

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
```


Λαμβάνει το ευρετήριο του πλησιέστερου χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Το χρώμα. |

**Returns:**
int - Ο δείκτης του πλησιέστερου χρώματος.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public final int getNearestColorIndex(int argb32Color)
```


Λαμβάνει το ευρετήριο του πλησιέστερου χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argb32Color | int | Το 32-bit ARGB χρώμα. |

**Returns:**
int - Ο δείκτης του πλησιέστερου χρώματος.
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


Λαμβάνει τα ακατέργαστα δεδομένα καταχωρήσεων της παλέτας χρωμάτων.

Τιμή: Τα ακατέργαστα δεδομένα καταχωρίσεων παλέτας χρώματος.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


Λαμβάνει τον αριθμό των ακατέργαστων καταχωρήσεων της παλέτας χρωμάτων.

Τιμή: Ο αριθμός των ακατέργαστων καταχωρίσεων παλέτας χρώματος.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


Λαμβάνει το διαφανές χρώμα.

Τιμή: Το διαφανές χρώμα.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


Λαμβάνει το ευρετήριο του διαφανούς χρώματος.

Τιμή: Ο δείκτης του διαφανούς χρώματος.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


Λαμβάνει μια τιμή που υποδεικνύει αν υπάρχει διαφανές χρώμα.

Τιμή:  true  εάν υπάρχει διαφανές χρώμα· διαφορετικά,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public final boolean isCompactPalette()
```


Λαμβάνει μια τιμή που υποδεικνύει αν η παλέτα είναι συμπαγής.

Τιμή:  true  εάν η παλέτα είναι συμπαγής· διαφορετικά,  false .

--------------------

Η συμπαγής παλέτα σημαίνει ότι η εικόνα θα περιέχει μόνο τις καθορισμένες καταχωρίσεις παλέτας εάν είναι δυνατόν, ή με άλλα λόγια η εικόνα θα είναι πιο συμπαγής και θα καταλαμβάνει λιγότερο χώρο· διαφορετικά θα υπάρχουν καταχωρίσεις 2^BitsPerPixel και η εικόνα θα διατηρεί περισσότερο χώρο για όλες τις πιθανές καταχωρίσεις παλέτας. Ορισμός αυτής της τιμής σε true και η αλλαγή των καταχωρίσεων παλέτας μπορεί να προκαλέσει ποινή απόδοσης, καθώς μπορεί να συμβεί μετακίνηση δεδομένων, οπότε χρησιμοποιήστε το προσεκτικά.

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

