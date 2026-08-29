---
title: "MotionWienerFilterOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Επιλογές φίλτρου αποσύνθεσης     αποθόλωση κίνησης"
type: docs
weight: 18
url: /el/java/com.aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends DeconvolutionFilterOptions
```

Επιλογές φίλτρου αποσύνθεσης αποθόλωση κίνησης
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MotionWienerFilterOptions(int length, double smooth, double angle)](#MotionWienerFilterOptions-int-double-double-) | Αρχικοποιεί μια νέα παρουσία της  MotionWienerFilterOptions  κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Λαμβάνει ή ορίζει τη γωνία σε βαθμούς. |
| [getBrightness()](#getBrightness--) | Λαμβάνει ή ορίζει το brightness. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) είναι σε γκρι κλίμακα. |
| [getLength()](#getLength--) | Λαμβάνει ή ορίζει το μήκος. |
| [getSmooth()](#getSmooth--) | Λαμβάνει ή ορίζει την ομαλότητα. |
| [getSnr()](#getSnr--) | Λαμβάνει ή ορίζει το SNR (αναλογία σήματος προς θόρυβο) προτεινόμενο εύρος 0.002 - 0.009, προεπιλεγμένη τιμή = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι μερικά φορτωμένη. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(double value)](#setAngle-double-) | Λαμβάνει ή ορίζει τη γωνία σε βαθμούς. |
| [setBrightness(double value)](#setBrightness-double-) | Λαμβάνει ή ορίζει το brightness. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) είναι σε γκρι κλίμακα. |
| [setLength(int value)](#setLength-int-) | Λαμβάνει ή ορίζει το μήκος. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι μερικά φορτωμένη. |
| [setSmooth(double value)](#setSmooth-double-) | Λαμβάνει ή ορίζει την ομαλότητα. |
| [setSnr(double value)](#setSnr-double-) | Λαμβάνει ή ορίζει το SNR (αναλογία σήματος προς θόρυβο) προτεινόμενο εύρος 0.002 - 0.009, προεπιλεγμένη τιμή = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MotionWienerFilterOptions(int length, double smooth, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int length, double smooth, double angle)
```


Αρχικοποιεί μια νέα παρουσία της  MotionWienerFilterOptions  κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήκος | int | Το μήκος. |
| ομαλό | double | Το ομαλό. |
| angle | double | Η γωνία σε βαθμούς. |

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
### getAngle() {#getAngle--}
```
public double getAngle()
```


Λαμβάνει ή ορίζει τη γωνία σε βαθμούς.

Τιμή: Η γωνία.

**Returns:**
double
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Λαμβάνει ή ορίζει τη φωτεινότητα. προτεινόμενο εύρος 1 - 1.5 προεπιλεγμένη τιμή = 1.15

Τιμή: Το brightness.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) είναι σε κλίμακα του γκρι. Επιστρέφει λειτουργία κλίμακας του γκρι ή λειτουργία RGB.

Τιμή:  true  εάν είναι κλίμακα του γκρι· διαφορετικά,  false .

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


Λαμβάνει ή ορίζει το μήκος.

Τιμή: Το μήκος.

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


Λαμβάνει ή ορίζει την ομαλότητα.

Τιμή: Η εξομάλυνση.

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


Λαμβάνει ή ορίζει το SNR (αναλογία σήματος προς θόρυβο) προτεινόμενο εύρος 0.002 - 0.009, προεπιλεγμένη τιμή = 0.007

Τιμή: Το SNR.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPartialLoaded() {#isPartialLoaded--}
```
public final boolean isPartialLoaded()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι μερικά φορτωμένη.

Τιμή:  true  εάν αυτή η παρουσία είναι μερικά φορτωμένη· διαφορετικά,  false .

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




### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```


Λαμβάνει ή ορίζει τη γωνία σε βαθμούς.

Τιμή: Η γωνία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Λαμβάνει ή ορίζει τη φωτεινότητα. προτεινόμενο εύρος 1 - 1.5 προεπιλεγμένη τιμή = 1.15

Τιμή: Το brightness.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) είναι σε κλίμακα του γκρι. Επιστρέφει λειτουργία κλίμακας του γκρι ή λειτουργία RGB.

Τιμή:  true  εάν είναι κλίμακα του γκρι· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Λαμβάνει ή ορίζει το μήκος.

Τιμή: Το μήκος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι μερικά φορτωμένη.

Τιμή:  true  εάν αυτή η παρουσία είναι μερικά φορτωμένη· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


Λαμβάνει ή ορίζει την ομαλότητα.

Τιμή: Η εξομάλυνση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


Λαμβάνει ή ορίζει το SNR (αναλογία σήματος προς θόρυβο) προτεινόμενο εύρος 0.002 - 0.009, προεπιλεγμένη τιμή = 0.007

Τιμή: Το SNR.

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

