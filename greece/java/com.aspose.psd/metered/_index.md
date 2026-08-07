---
title: "Μετρημένο"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Παρέχει μετρημένες μεθόδους για ενσωμάτωση."
type: docs
weight: 71
url: /el/java/com.aspose.psd/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Παρέχει μετρημένες μεθόδους για ενσωμάτωση.

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να οριστεί το μετρημένο δημόσιο και ιδιωτικό κλειδί

// το αρχείο jar του component: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey");
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Metered()](#Metered--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [FlushTimeout_internalized](#FlushTimeout-internalized) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το καθορισμένο Object είναι ίσο με αυτήν την παρουσία. |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | Λαμβάνει πίστωση κατανάλωσης |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Λαμβάνει μέγεθος αρχείου κατανάλωσης |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ορίζει το μετρημένο δημόσιο και ιδιωτικό κλειδί |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Metered() {#Metered--}
```
public Metered()
```


### FlushTimeout_internalized {#FlushTimeout-internalized}
```
public static int FlushTimeout_internalized
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν το καθορισμένο Object είναι ίσο με αυτήν την παρουσία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το Object για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean -  true  εάν το συγκεκριμένο Object είναι ίσο με αυτήν την παρουσία; διαφορετικά,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Λαμβάνει πίστωση κατανάλωσης

**Returns:**
java.math.BigDecimal - ποσότητα κατανάλωσης
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Λαμβάνει μέγεθος αρχείου κατανάλωσης

**Returns:**
java.math.BigDecimal - μέγεθος αρχείου κατανάλωσης
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




### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Ορίζει το μετρημένο δημόσιο και ιδιωτικό κλειδί

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| publicKey | java.lang.String | δημόσιο κλειδί |
| privateKey | java.lang.String | ιδιωτικό κλειδί |

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

