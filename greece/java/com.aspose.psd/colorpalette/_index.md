---
title: "ColorPalette"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ορίζει έναν πίνακα χρωμάτων που αποτελούν μια παλέτα χρωμάτων."
type: docs
weight: 27
url: /el/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Ορίζει έναν πίνακα χρωμάτων που αποτελούν μια παλέτα χρωμάτων. Τα χρώματα είναι 32-bit ARGB χρώματα. Δεν είναι κληρονομήσιμα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  ColorPalette . |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Αρχικοποιεί μια νέα παρουσία της κλάσης  ColorPalette  και το IsCompactPalette είναι false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  ColorPalette . |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | Αρχικοποιεί μια νέα παρουσία της κλάσης  ColorPalette  και το IsCompactPalette είναι false. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Αντιγράφει την παλέτα. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Αντιγράφει την παλέτα. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Λαμβάνει το χρώμα παλέτας ARGB 32-bit με βάση το δείκτη. |
| [getArgb32Entries()](#getArgb32Entries--) | Λαμβάνει έναν πίνακα δομών 32-bit ARGB. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Λαμβάνει το χρώμα της παλέτας με βάση το δείκτη. |
| [getEntries()](#getEntries--) | Λαμβάνει έναν πίνακα δομών  com.aspose.psd.Color . |
| [getEntriesCount()](#getEntriesCount--) | Λαμβάνει τον αριθμό των καταχωρήσεων. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Λαμβάνει το ευρετήριο του πλησιέστερου χρώματος. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Λαμβάνει το ευρετήριο του πλησιέστερου χρώματος. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται συμπαγή παλέτα. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  ColorPalette .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argb32Entries | int[] | Οι καταχωρίσεις της παλέτας χρωμάτων 32-bit ARGB. |
| isCompactPalette | boolean | Δείχνει αν η παλέτα είναι συμπαγής. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  ColorPalette  και το IsCompactPalette είναι false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argb32Entries | int[] | Οι καταχωρίσεις της παλέτας χρωμάτων 32-bit ARGB. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  ColorPalette .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Οι καταχωρήσεις της παλέτας χρωμάτων. |
| isCompactPalette | boolean | Δείχνει αν η παλέτα είναι συμπαγής. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  ColorPalette  και το IsCompactPalette είναι false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Οι καταχωρήσεις της παλέτας χρωμάτων. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Αντιγράφει την παλέτα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Αντιγράφει την παλέτα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |
| useCompactPalette | boolean | Δείχνει αν η παλέτα είναι συμπαγής. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
public int getArgb32Color(int index)
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
public int[] getArgb32Entries()
```


Λαμβάνει έναν πίνακα δομών 32-bit ARGB.

**Returns:**
int[] - Οι καταχωρίσεις. Ο πίνακας δομών 32-bit ARGB που αποτελούν αυτό το  Aspose.Imaging.ColorPalette .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
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
public Color[] getEntries()
```


Λαμβάνει έναν πίνακα δομών  com.aspose.psd.Color .

**Returns:**
com.aspose.psd.Color[] - Οι καταχωρίσεις. Ο πίνακας δομών  com.aspose.psd.Color  που αποτελούν αυτό το  Aspose.Imaging.ColorPalette .
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Λαμβάνει τον αριθμό των καταχωρήσεων.

**Returns:**
int - Ο αριθμός των καταχωρίσεων.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
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
public int getNearestColorIndex(int argb32Color)
```


Λαμβάνει το ευρετήριο του πλησιέστερου χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argb32Color | int | Το 32-bit ARGB χρώμα. |

**Returns:**
int - Ο δείκτης του πλησιέστερου χρώματος.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται συμπαγή παλέτα.

**Returns:**
boolean -  true  εάν χρησιμοποιείται συμπαγής παλέτα· διαφορετικά,  false .

Η συμπαγής παλέτα σημαίνει ότι η εικόνα θα περιέχει μόνο τις καθορισμένες καταχωρίσεις παλέτας εάν είναι δυνατόν, ή με άλλα λόγια η εικόνα θα είναι πιο συμπαγής και θα καταλαμβάνει λιγότερο χώρο· διαφορετικά θα υπάρχουν καταχωρίσεις 2^BitsPerPixel και η εικόνα θα διατηρεί περισσότερο χώρο για όλες τις πιθανές καταχωρίσεις παλέτας. Ορισμός αυτής της τιμής σε true και η αλλαγή των καταχωρίσεων παλέτας μπορεί να προκαλέσει ποινή απόδοσης, καθώς μπορεί να συμβεί μετακίνηση δεδομένων, οπότε χρησιμοποιήστε το προσεκτικά.
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

