---
title: "IColorPalette"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η διεπαφή παλέτας χρωμάτων."
type: docs
weight: 117
url: /el/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

Η διεπαφή παλέτας χρωμάτων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Λαμβάνει το χρώμα παλέτας ARGB 32-bit με βάση το δείκτη. |
| [getArgb32Entries()](#getArgb32Entries--) | Λαμβάνει έναν πίνακα δομών 32-bit ARGB. |
| [getColor(int index)](#getColor-int-) | Λαμβάνει το χρώμα της παλέτας με βάση το δείκτη. |
| [getEntries()](#getEntries--) | Λαμβάνει έναν πίνακα δομών  com.aspose.psd.Color . |
| [getEntriesCount()](#getEntriesCount--) | Λαμβάνει τον αριθμό των καταχωρήσεων. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Λαμβάνει το ευρετήριο του πλησιέστερου χρώματος. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Λαμβάνει το δείκτη του πλησιέστερου χρώματος ARGB 32-bit. |
| [isCompactPalette()](#isCompactPalette--) | Λαμβάνει μια τιμή που υποδεικνύει εάν χρησιμοποιείται συμπαγή παλέτα. |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
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
public abstract int[] getArgb32Entries()
```


Λαμβάνει έναν πίνακα δομών 32-bit ARGB.

**Returns:**
int[] - Οι καταχωρήσεις ARGB 32-bit. Ο πίνακας της δομής ARGB 32-bit που αποτελεί αυτή τη  com.aspose.psd.ColorPalette .
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
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
public abstract Color[] getEntries()
```


Λαμβάνει έναν πίνακα δομών  com.aspose.psd.Color .

**Returns:**
com.aspose.psd.Color[] - Οι καταχωρήσεις. Ο πίνακας της δομής  com.aspose.psd.Color  που αποτελεί αυτή τη  com.aspose.psd.ColorPalette .
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


Λαμβάνει τον αριθμό των καταχωρήσεων.

**Returns:**
int - Ο αριθμός των καταχωρίσεων.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
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
public abstract int getNearestColorIndex(int argb32Color)
```


Λαμβάνει το δείκτη του πλησιέστερου χρώματος ARGB 32-bit.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argb32Color | int | Το 32-bit ARGB χρώμα. |

**Returns:**
int - Ο δείκτης του πλησιέστερου χρώματος.
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν χρησιμοποιείται συμπαγή παλέτα.

Η συμπαγής παλέτα σημαίνει ότι η εικόνα θα περιέχει μόνο τις καθορισμένες καταχωρίσεις παλέτας εάν είναι δυνατόν, ή με άλλα λόγια η εικόνα θα είναι πιο συμπαγής και θα καταλαμβάνει λιγότερο χώρο· διαφορετικά θα υπάρχουν καταχωρίσεις 2^BitsPerPixel και η εικόνα θα διατηρεί περισσότερο χώρο για όλες τις πιθανές καταχωρίσεις παλέτας. Ορισμός αυτής της τιμής σε true και η αλλαγή των καταχωρίσεων παλέτας μπορεί να προκαλέσει ποινή απόδοσης, καθώς μπορεί να συμβεί μετακίνηση δεδομένων, οπότε χρησιμοποιήστε το προσεκτικά.

**Returns:**
boolean -  true  εάν χρησιμοποιείται συμπαγής παλέτα· διαφορετικά,  false .
