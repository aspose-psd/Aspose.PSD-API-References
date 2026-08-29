---
title: "ResolutionSetting"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η ρύθμιση ανάλυσης για τις επιλογές αποθήκευσης εικόνας."
type: docs
weight: 92
url: /el/java/com.aspose.psd/resolutionsetting/
---

**Inheritance:**
java.lang.Object
```
public class ResolutionSetting
```

Η ρύθμιση ανάλυσης για τις επιλογές αποθήκευσης εικόνας.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ResolutionSetting()](#ResolutionSetting--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  ResolutionSetting  . |
| [ResolutionSetting(double horizontalResolution, double verticalResolution)](#ResolutionSetting-double-double-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  ResolutionSetting  . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)](#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-) | Ορίζει το μέγεθος σελίδας PDF ανάλογα με την ανάλυση DPI που λαμβάνεται από το PdfOptions.ResolutionSettings ή εάν έχει προεπιλεγμένες τιμές· από την ίδια την εικόνα. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalResolution()](#getHorizontalResolution--) | Λαμβάνει ή ορίζει την οριζόντια ανάλυση. |
| [getVerticalResolution()](#getVerticalResolution--) | Λαμβάνει ή ορίζει την κάθετη ανάλυση. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Λαμβάνει ή ορίζει την οριζόντια ανάλυση. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Λαμβάνει ή ορίζει την κάθετη ανάλυση. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionSetting() {#ResolutionSetting--}
```
public ResolutionSetting()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  ResolutionSetting  .

### ResolutionSetting(double horizontalResolution, double verticalResolution) {#ResolutionSetting-double-double-}
```
public ResolutionSetting(double horizontalResolution, double verticalResolution)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  ResolutionSetting  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| horizontalResolution | double | Η οριζόντια ανάλυση. |
| verticalResolution | double | Η κάθετη ανάλυση. |

### adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution) {#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-}
```
public static SizeF adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)
```


Ορίζει το μέγεθος σελίδας PDF ανάλογα με την ανάλυση DPI που λαμβάνεται από το PdfOptions.ResolutionSettings ή εάν έχει προεπιλεγμένες τιμές· από την ίδια την εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Το μέγεθος της εικόνας. |
| originalResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Η αρχική ανάλυση. |
| newResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Η νέα ανάλυση. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef)
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
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Λαμβάνει ή ορίζει την οριζόντια ανάλυση.

**Returns:**
double
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Λαμβάνει ή ορίζει την κάθετη ανάλυση.

**Returns:**
double
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




### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Λαμβάνει ή ορίζει την οριζόντια ανάλυση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Λαμβάνει ή ορίζει την κάθετη ανάλυση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

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

