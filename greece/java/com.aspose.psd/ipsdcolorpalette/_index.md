---
title: "IPsdColorPalette"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η παλέτα χρωμάτων pasd"
type: docs
weight: 134
url: /el/java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

Η παλέτα χρωμάτων pasd
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | Λαμβάνει τα ακατέργαστα δεδομένα καταχωρήσεων της παλέτας χρωμάτων. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Λαμβάνει τον αριθμό των ακατέργαστων καταχωρήσεων της παλέτας χρωμάτων. |
| [getTransparentColor()](#getTransparentColor--) | Λαμβάνει το διαφανές χρώμα. |
| [getTransparentIndex()](#getTransparentIndex--) | Λαμβάνει το ευρετήριο του διαφανούς χρώματος. |
| [hasTransparentColor()](#hasTransparentColor--) | Λαμβάνει μια τιμή που υποδεικνύει αν υπάρχει διαφανές χρώμα. |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


Λαμβάνει τα ακατέργαστα δεδομένα καταχωρήσεων της παλέτας χρωμάτων.

Τιμή: Τα ακατέργαστα δεδομένα καταχωρίσεων παλέτας χρώματος.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


Λαμβάνει τον αριθμό των ακατέργαστων καταχωρήσεων της παλέτας χρωμάτων.

Τιμή: Ο αριθμός των ακατέργαστων καταχωρίσεων παλέτας χρώματος.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


Λαμβάνει το διαφανές χρώμα.

Τιμή: Το διαφανές χρώμα.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


Λαμβάνει το ευρετήριο του διαφανούς χρώματος.

Τιμή: Ο δείκτης του διαφανούς χρώματος.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


Λαμβάνει μια τιμή που υποδεικνύει αν υπάρχει διαφανές χρώμα.

Τιμή:  true  εάν υπάρχει διαφανές χρώμα· διαφορετικά,  false .

**Returns:**
boolean
