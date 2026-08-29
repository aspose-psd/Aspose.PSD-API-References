---
title: "GaussWienerFilterOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Επιλογές φίλτρου Gauss Wiener Αποθόλωση gauss"
type: docs
weight: 15
url: /el/java/com.aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends DeconvolutionFilterOptions
```

Επιλογές φίλτρου Gauss Wiener Αποθόλωση gauss
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GaussWienerFilterOptions(int radius, double smooth)](#GaussWienerFilterOptions-int-double-) | Αρχικοποιεί μια νέα παρουσία της κλάσης GaussWienerFilterOptions. |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης GaussWienerFilterOptions. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBrightness()](#getBrightness--) | Λαμβάνει ή ορίζει το brightness. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) είναι σε γκρι κλίμακα. |
| [getRadius()](#getRadius--) | Λαμβάνει ή ορίζει την ακτίνα. |
| [getSmooth()](#getSmooth--) | Λαμβάνει ή ορίζει την ομαλότητα. |
| [getSnr()](#getSnr--) | Λαμβάνει ή ορίζει το SNR (αναλογία σήματος προς θόρυβο) προτεινόμενο εύρος 0.002 - 0.009, προεπιλεγμένη τιμή = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι μερικά φορτωμένη. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrightness(double value)](#setBrightness-double-) | Λαμβάνει ή ορίζει το brightness. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) είναι σε γκρι κλίμακα. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι μερικά φορτωμένη. |
| [setRadius(int value)](#setRadius-int-) | Λαμβάνει ή ορίζει την ακτίνα. |
| [setSmooth(double value)](#setSmooth-double-) | Λαμβάνει ή ορίζει την ομαλότητα. |
| [setSnr(double value)](#setSnr-double-) | Λαμβάνει ή ορίζει το SNR (αναλογία σήματος προς θόρυβο) προτεινόμενο εύρος 0.002 - 0.009, προεπιλεγμένη τιμή = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussWienerFilterOptions(int radius, double smooth) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int radius, double smooth)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης GaussWienerFilterOptions.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ακτίνα | int | Η ακτίνα. |
| ομαλό | double | Το ομαλό. |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης GaussWienerFilterOptions. Με προεπιλεγμένες ρυθμίσεις.

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
### getRadius() {#getRadius--}
```
public int getRadius()
```


Λαμβάνει ή ορίζει την ακτίνα.

Τιμή: Η ακτίνα.

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

### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Λαμβάνει ή ορίζει την ακτίνα.

Τιμή: Η ακτίνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

