---
title: "AutoMaskingArgs"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαριστά τα επιχειρήματα που καθορίζονται για τις αυτοματοποιημένες μεθόδους μάσκας"
type: docs
weight: 11
url: /el/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Αναπαριστά τα επιχειρήματα που καθορίζονται για τις αυτοματοποιημένες μεθόδους μάσκας
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Λαμβάνει τον μέγιστο αριθμό επαναλήψεων. |
| [getNumberOfObjects()](#getNumberOfObjects--) | Λαμβάνει τον αριθμό των αντικειμένων για διαχωρισμό της αρχικής εικόνας (προαιρετικό), η προεπιλεγμένη τιμή είναι 2 (αντικείμενο και φόντο). |
| [getObjectsPoints()](#getObjectsPoints--) | Λαμβάνει τα σημεία που ανήκουν σε διαχωρισμένα αντικείμενα (προαιρετικό) Συντεταγμένες NumberOfObjects που ανήκουν σε NumberOfObjects αντικείμενα της αρχικής εικόνας. |
| [getObjectsRectangles()](#getObjectsRectangles--) | Λαμβάνει τα ορθογώνια των αντικειμένων που ανήκουν σε διαχωρισμένα αντικείμενα (προαιρετικό). |
| [getOrphanedPoints()](#getOrphanedPoints--) | Λαμβάνει τα σημεία που δεν ανήκουν πλέον σε κανένα αντικείμενο (προαιρετικό). |
| [getPrecision()](#getPrecision--) | Λαμβάνει την ακρίβεια της μεθόδου τμηματοποίησης (προαιρετικό). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Ορίζει τον μέγιστο αριθμό επαναλήψεων. |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Ορίζει τον αριθμό των αντικειμένων για διαχωρισμό της αρχικής εικόνας (προαιρετικό), η προεπιλεγμένη τιμή είναι 2 (αντικείμενο και φόντο). |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | Ορίζει τα σημεία που ανήκουν σε διαχωρισμένα αντικείμενα (προαιρετικό) Συντεταγμένες NumberOfObjects που ανήκουν σε NumberOfObjects αντικείμενα της αρχικής εικόνας. |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | Ορίζει τα ορθογώνια των αντικειμένων που ανήκουν σε διαχωρισμένα αντικείμενα (προαιρετικό). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | Ορίζει τα σημεία που δεν ανήκουν πλέον σε κανένα αντικείμενο (προαιρετικό). |
| [setPrecision(double value)](#setPrecision-double-) | Ορίζει την ακρίβεια της μεθόδου τμηματοποίησης (προαιρετικό). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


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
### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Λαμβάνει τον μέγιστο αριθμό επαναλήψεων.

Τιμή: Ο μέγιστος μέγιστος αριθμός επαναλήψεων.

**Returns:**
int - ο μέγιστος αριθμός επαναλήψεων.
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Λαμβάνει τον αριθμό των αντικειμένων για διαχωρισμό της αρχικής εικόνας (προαιρετικό), η προεπιλεγμένη τιμή είναι 2 (αντικείμενο και φόντο).

Τιμή: Ο αριθμός των αντικειμένων.

**Returns:**
int - ο αριθμός των αντικειμένων για διαχωρισμό της αρχικής εικόνας (προαιρετικό), η προεπιλεγμένη τιμή είναι 2 (αντικείμενο και φόντο).
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Λαμβάνει τα σημεία που ανήκουν σε διαχωρισμένα αντικείμενα (προαιρετικό) Συντεταγμένες NumberOfObjects που ανήκουν σε NumberOfObjects αντικείμενα της αρχικής εικόνας. Αυτή η παράμετρος χρησιμοποιείται για την αύξηση της ακρίβειας της μεθόδου τμηματοποίησης.

Τιμή: Τα σημεία των αντικειμένων.

**Returns:**
com.aspose.psd.Point[][] - τα σημεία που ανήκουν σε διαχωρισμένα αντικείμενα (προαιρετικό) συντεταγμένες NumberOfObjects που ανήκουν σε αντικείμενα NumberOfObjects της αρχικής εικόνας.
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Λαμβάνει τα ορθογώνια των αντικειμένων που ανήκουν σε διαχωρισμένα αντικείμενα (προαιρετικό). Αυτή η παράμετρος χρησιμοποιείται για την αύξηση της ακρίβειας της μεθόδου τμηματοποίησης.

Τιμή: Τα ορθογώνια των αντικειμένων.

**Returns:**
com.aspose.psd.Rectangle[] - τα ορθογώνια των αντικειμένων που ανήκουν σε διαχωρισμένα αντικείμενα (προαιρετικό).
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Λαμβάνει τα σημεία που δεν ανήκουν πλέον σε κανένα αντικείμενο (προαιρετικό). Αυτή η παράμετρος χρησιμοποιείται μόνο σε περίπτωση επανατμηματοποίησης.

Τιμή: Τα ορφανά σημεία.

**Returns:**
com.aspose.psd.Point[] - τα σημεία που δεν ανήκουν πλέον σε κανένα αντικείμενο (προαιρετικό).
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Λαμβάνει την ακρίβεια της μεθόδου τμηματοποίησης (προαιρετικό).

Τιμή: Η ακρίβεια της μεθόδου τμηματοποίησης (προαιρετικό).

**Returns:**
double - η ακρίβεια της μεθόδου τμηματοποίησης (προαιρετικό).
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




### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Ορίζει τον μέγιστο αριθμό επαναλήψεων.

Τιμή: Ο μέγιστος μέγιστος αριθμός επαναλήψεων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | ο μέγιστος αριθμός επαναλήψεων. |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Ορίζει τον αριθμό των αντικειμένων για διαχωρισμό της αρχικής εικόνας (προαιρετικό), η προεπιλεγμένη τιμή είναι 2 (αντικείμενο και φόντο).

Τιμή: Ο αριθμός των αντικειμένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | ο αριθμός των αντικειμένων για διαχωρισμό της αρχικής εικόνας (προαιρετικό), η προεπιλεγμένη τιμή είναι 2 (αντικείμενο και φόντο). |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Ορίζει τα σημεία που ανήκουν σε διαχωρισμένα αντικείμενα (προαιρετικό) συντεταγμένες NumberOfObjects που ανήκουν σε αντικείμενα NumberOfObjects της αρχικής εικόνας. Αυτή η παράμετρος χρησιμοποιείται για την αύξηση της ακρίβειας της μεθόδου τμηματοποίησης.

Τιμή: Τα σημεία των αντικειμένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | τα σημεία που ανήκουν σε διαχωρισμένα αντικείμενα (προαιρετικό) συντεταγμένες NumberOfObjects που ανήκουν σε αντικείμενα NumberOfObjects της αρχικής εικόνας. |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Ορίζει τα ορθογώνια των αντικειμένων που ανήκουν σε διαχωρισμένα αντικείμενα (προαιρετικό). Αυτή η παράμετρος χρησιμοποιείται για την αύξηση της ακρίβειας της μεθόδου τμηματοποίησης.

Τιμή: Τα ορθογώνια των αντικειμένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | τα ορθογώνια των αντικειμένων που ανήκουν σε διαχωρισμένα αντικείμενα (προαιρετικό). |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Ορίζει τα σημεία που δεν ανήκουν πλέον σε κανένα αντικείμενο (προαιρετικό). Αυτή η παράμετρος χρησιμοποιείται μόνο σε περίπτωση επανατμηματοποίησης.

Τιμή: Τα ορφανά σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | τα σημεία που δεν ανήκουν πλέον σε κανένα αντικείμενο (προαιρετικό). |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Ορίζει την ακρίβεια της μεθόδου τμηματοποίησης (προαιρετικό).

Τιμή: Η ακρίβεια της μεθόδου τμηματοποίησης (προαιρετικό).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | η ακρίβεια της μεθόδου τμηματοποίησης (προαιρετικό). |

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

