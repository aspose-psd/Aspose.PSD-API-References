---
title: "GdflResourceHelper"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Βοηθητική κλάση που υλοποιεί τη μετατροπή δεδομένων από το GdflResource."
type: docs
weight: 32
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/gdflresourcehelper/
---

**Inheritance:**
java.lang.Object
```
public final class GdflResourceHelper
```

Βοηθητική κλάση που υλοποιεί τη μετατροπή δεδομένων από το GdflResource.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GdflResourceHelper()](#GdflResourceHelper--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [StrGradientNoise](#StrGradientNoise) | Σταθερά συμβολοσειράς διαβάθμισης θορύβου. |
| [StrGradientSolid](#StrGradientSolid) | Σταθερά συμβολοσειράς στερεής διαβάθμισης. |
| [StrModelHSB](#StrModelHSB) | Σταθερά συμβολοσειράς μοντέλου χρώματος HSBL για διαβάθμιση θορύβου. |
| [StrModelLAB](#StrModelLAB) | Σταθερά συμβολοσειράς μοντέλου χρώματος LBCL για διαβάθμιση θορύβου. |
| [StrModelRGB](#StrModelRGB) | Σταθερά συμβολοσειράς μοντέλου χρώματος RGBC για διαβάθμιση θορύβου. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | Μετατρέπει την τιμή GradientKind σε συμβολοσειρά. |
| [hashCode()](#hashCode--) |  |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | Μετατρέπει την τιμή NoiseColorModel σε συμβολοσειρά. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | Μετατρέπει την τιμή συμβολοσειράς σε GradientKind. |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | Μετατρέπει την τιμή συμβολοσειράς σε NoiseColorModel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GdflResourceHelper() {#GdflResourceHelper--}
```
public GdflResourceHelper()
```


### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


Σταθερά συμβολοσειράς διαβάθμισης θορύβου.

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


Σταθερά συμβολοσειράς στερεής διαβάθμισης.

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


Σταθερά συμβολοσειράς μοντέλου χρώματος HSBL για διαβάθμιση θορύβου.

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


Σταθερά συμβολοσειράς μοντέλου χρώματος LBCL για διαβάθμιση θορύβου.

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


Σταθερά συμβολοσειράς μοντέλου χρώματος RGBC για διαβάθμιση θορύβου.

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
### gradientKindToStr(int gradientKind) {#gradientKindToStr-int-}
```
public static String gradientKindToStr(int gradientKind)
```


Μετατρέπει την τιμή GradientKind σε συμβολοσειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| gradientKind | int | Τιμή GradientKind |

**Returns:**
java.lang.String - τιμή συμβολοσειράς
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


Μετατρέπει την τιμή NoiseColorModel σε συμβολοσειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorModel | short | Τιμή NoiseColorModel |

**Returns:**
java.lang.String -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### strToGradientKind(String str) {#strToGradientKind-java.lang.String-}
```
public static int strToGradientKind(String str)
```


Μετατρέπει την τιμή συμβολοσειράς σε GradientKind.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | java.lang.String | τιμή συμβολοσειράς |

**Returns:**
int - τιμή GradientKind
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


Μετατρέπει την τιμή συμβολοσειράς σε NoiseColorModel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorModel | java.lang.String | τιμή συμβολοσειράς |

**Returns:**
short - τιμή NoiseColorModel
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

