---
title: "ColorMatrix"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ορίζει έναν πίνακα 5 x 5 που περιέχει τις συντεταγμένες για το χώρο RGBA."
type: docs
weight: 25
url: /el/java/com.aspose.psd/colormatrix/
---

**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Ορίζει έναν πίνακα 5 x 5 που περιέχει τις συντεταγμένες για το χώρο RGBA. Πολλές μέθοδοι της κλάσης  com.aspose.psd.ImageAttributes  προσαρμόζουν τα χρώματα της εικόνας χρησιμοποιώντας έναν πίνακα χρωμάτων. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  Aspose.Imaging.ColorMatrix . |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  Aspose.Imaging.ColorMatrix  χρησιμοποιώντας τα στοιχεία του καθορισμένου πίνακα  newColorMatrix . |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [MatrixDimensionElementsCount](#MatrixDimensionElementsCount) | Ο αριθμός των στοιχείων στη διάσταση του πίνακα. |
| [MatrixDimensionsCount](#MatrixDimensionsCount) | Ο αριθμός των διαστάσεων του πίνακα. |
| [MatrixTotalElementsCount](#MatrixTotalElementsCount) | Ο συνολικός αριθμός των στοιχείων στον πίνακα. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | Λαμβάνει τις τιμές του πίνακα. |
| [getMatrix00()](#getMatrix00--) | Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και στήλη 0 αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix01()](#getMatrix01--) | Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix02()](#getMatrix02--) | Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix03()](#getMatrix03--) | Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix04()](#getMatrix04--) | Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix10()](#getMatrix10--) | Λαμβάνει το στοιχείο στην πρώτη γραμμή και στήλη 0 (μηδέν) αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix11()](#getMatrix11--) | Λαμβάνει το στοιχείο στην πρώτη γραμμή και πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix12()](#getMatrix12--) | Λαμβάνει το στοιχείο στην πρώτη γραμμή και δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix13()](#getMatrix13--) | Λαμβάνει το στοιχείο στην πρώτη γραμμή και τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix14()](#getMatrix14--) | Λαμβάνει το στοιχείο στην πρώτη γραμμή και τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix20()](#getMatrix20--) | Λαμβάνει το στοιχείο στη δεύτερη γραμμή και στήλη 0 (μηδέν) αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix21()](#getMatrix21--) | Λαμβάνει το στοιχείο στη δεύτερη γραμμή και πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix22()](#getMatrix22--) | Λαμβάνει το στοιχείο στη δεύτερη γραμμή και δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix23()](#getMatrix23--) | Λαμβάνει το στοιχείο στη δεύτερη γραμμή και τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix24()](#getMatrix24--) | Λαμβάνει το στοιχείο στη δεύτερη γραμμή και τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix30()](#getMatrix30--) | Λαμβάνει το στοιχείο στην τρίτη γραμμή και στήλη 0 (μηδέν) αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix31()](#getMatrix31--) | Λαμβάνει το στοιχείο στην τρίτη γραμμή και πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix32()](#getMatrix32--) | Λαμβάνει το στοιχείο στην τρίτη γραμμή και δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix33()](#getMatrix33--) | Λαμβάνει το στοιχείο στην τρίτη γραμμή και τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix34()](#getMatrix34--) | Λαμβάνει το στοιχείο στην τρίτη γραμμή και τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix40()](#getMatrix40--) | Λαμβάνει το στοιχείο στην τέταρτη γραμμή και στήλη 0 (μηδέν) αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix41()](#getMatrix41--) | Λαμβάνει το στοιχείο στην τέταρτη γραμμή και πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |
| [getMatrix42()](#getMatrix42--) | Λαμβάνει το στοιχείο στην τέταρτη γραμμή και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [getMatrix43()](#getMatrix43--) | Λαμβάνει το στοιχείο στην τέταρτη γραμμή και στη τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [getMatrix44()](#getMatrix44--) | Λαμβάνει το στοιχείο στην τέταρτη γραμμή και στη τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Λαμβάνει το στοιχείο στην καθορισμένη γραμμή και στη στήλη στο Aspose.Imaging.ColorMatrix. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMatrix00(float value)](#setMatrix00-float-) | Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στη στήλη 0 αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix01(float value)](#setMatrix01-float-) | Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στην πρώτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix02(float value)](#setMatrix02-float-) | Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix03(float value)](#setMatrix03-float-) | Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στην τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix04(float value)](#setMatrix04-float-) | Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στη τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix10(float value)](#setMatrix10-float-) | Ορίζει το στοιχείο στην πρώτη γραμμή και στη στήλη 0 (μηδέν) αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix11(float value)](#setMatrix11-float-) | Ορίζει το στοιχείο στην πρώτη γραμμή και στην πρώτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix12(float value)](#setMatrix12-float-) | Ορίζει το στοιχείο στην πρώτη γραμμή και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix13(float value)](#setMatrix13-float-) | Ορίζει το στοιχείο στην πρώτη γραμμή και στην τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix14(float value)](#setMatrix14-float-) | Ορίζει το στοιχείο στην πρώτη γραμμή και στη τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix20(float value)](#setMatrix20-float-) | Ορίζει το στοιχείο στη δεύτερη γραμμή και στη στήλη 0 (μηδέν) αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix21(float value)](#setMatrix21-float-) | Ορίζει το στοιχείο στη δεύτερη γραμμή και στην πρώτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix22(float value)](#setMatrix22-float-) | Ορίζει το στοιχείο στη δεύτερη γραμμή και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix23(float value)](#setMatrix23-float-) | Ορίζει το στοιχείο στη δεύτερη γραμμή και στην τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix24(float value)](#setMatrix24-float-) | Ορίζει το στοιχείο στη δεύτερη γραμμή και στη τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix30(float value)](#setMatrix30-float-) | Ορίζει το στοιχείο στην τρίτη γραμμή και στη στήλη 0 (μηδέν) αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix31(float value)](#setMatrix31-float-) | Ορίζει το στοιχείο στην τρίτη γραμμή και στην πρώτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix32(float value)](#setMatrix32-float-) | Ορίζει το στοιχείο στην τρίτη γραμμή και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix33(float value)](#setMatrix33-float-) | Ορίζει το στοιχείο στην τρίτη γραμμή και στην τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix34(float value)](#setMatrix34-float-) | Ορίζει το στοιχείο στην τρίτη γραμμή και στη τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix40(float value)](#setMatrix40-float-) | Ορίζει το στοιχείο στην τέταρτη γραμμή και στη στήλη 0 (μηδέν) αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix41(float value)](#setMatrix41-float-) | Ορίζει το στοιχείο στην τέταρτη γραμμή και στην πρώτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix42(float value)](#setMatrix42-float-) | Ορίζει το στοιχείο στην τέταρτη γραμμή και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix43(float value)](#setMatrix43-float-) | Ορίζει το στοιχείο στην τέταρτη γραμμή και στην τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [setMatrix44(float value)](#setMatrix44-float-) | Ορίζει το στοιχείο στην τέταρτη γραμμή και στην τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix. |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Ορίζει το στοιχείο στη συγκεκριμένη γραμμή και στήλη στο Aspose.Imaging.ColorMatrix. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  Aspose.Imaging.ColorMatrix .

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  Aspose.Imaging.ColorMatrix  χρησιμοποιώντας τα στοιχεία του καθορισμένου πίνακα  newColorMatrix .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | float[][] | Οι τιμές των στοιχείων για το νέο Aspose.Imaging.ColorMatrix. |

### MatrixDimensionElementsCount {#MatrixDimensionElementsCount}
```
public static final int MatrixDimensionElementsCount
```


Ο αριθμός των στοιχείων στη διάσταση του πίνακα.

### MatrixDimensionsCount {#MatrixDimensionsCount}
```
public static final int MatrixDimensionsCount
```


Ο αριθμός των διαστάσεων του πίνακα.

### MatrixTotalElementsCount {#MatrixTotalElementsCount}
```
public static final int MatrixTotalElementsCount
```


Ο συνολικός αριθμός των στοιχείων στον πίνακα.

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
### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


Λαμβάνει τις τιμές του πίνακα.

**Returns:**
float[][] - Ο πίνακας τιμών του μητρώου.
### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και στήλη 0 αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην 0 γραμμή και στην 0 στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην 0 γραμμή και στην πρώτη στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην 0 γραμμή και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην 0 γραμμή και στην τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Λαμβάνει το στοιχείο στη γραμμή 0 (μηδέν) και τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην 0 γραμμή και στην τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Λαμβάνει το στοιχείο στην πρώτη γραμμή και στήλη 0 (μηδέν) αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην πρώτη γραμμή και στην 0 στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Λαμβάνει το στοιχείο στην πρώτη γραμμή και πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην πρώτη γραμμή και στην πρώτη στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Λαμβάνει το στοιχείο στην πρώτη γραμμή και δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην πρώτη γραμμή και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Λαμβάνει το στοιχείο στην πρώτη γραμμή και τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην πρώτη γραμμή και στην τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Λαμβάνει το στοιχείο στην πρώτη γραμμή και τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην πρώτη γραμμή και στην τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Λαμβάνει το στοιχείο στη δεύτερη γραμμή και στήλη 0 (μηδέν) αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στη δεύτερη γραμμή και στην 0 στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Λαμβάνει το στοιχείο στη δεύτερη γραμμή και πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στη δεύτερη γραμμή και στην πρώτη στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Λαμβάνει το στοιχείο στη δεύτερη γραμμή και δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στη δεύτερη γραμμή και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Λαμβάνει το στοιχείο στη δεύτερη γραμμή και τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στη δεύτερη γραμμή και στην τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Λαμβάνει το στοιχείο στη δεύτερη γραμμή και τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στη δεύτερη γραμμή και στην τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Λαμβάνει το στοιχείο στην τρίτη γραμμή και στήλη 0 (μηδέν) αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην τρίτη γραμμή και στην 0 στήλη αυτού του Aspose.Imaging.ColorMatrix.
### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Λαμβάνει το στοιχείο στην τρίτη γραμμή και πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην τρίτη γραμμή και την πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .
### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Λαμβάνει το στοιχείο στην τρίτη γραμμή και δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην τρίτη γραμμή και τη δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix .
### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Λαμβάνει το στοιχείο στην τρίτη γραμμή και τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην τρίτη γραμμή και την τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .
### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Λαμβάνει το στοιχείο στην τρίτη γραμμή και τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην τρίτη γραμμή και την τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .
### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Λαμβάνει το στοιχείο στην τέταρτη γραμμή και στήλη 0 (μηδέν) αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην τέταρτη γραμμή και στη στήλη 0 αυτού του  Aspose.Imaging.ColorMatrix .
### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Λαμβάνει το στοιχείο στην τέταρτη γραμμή και πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Το στοιχείο στην τέταρτη γραμμή και την πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .
### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Λαμβάνει το στοιχείο στην τέταρτη γραμμή και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Returns:**
float - Το στοιχείο στην τέταρτη γραμμή και τη δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix .
### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Λαμβάνει το στοιχείο στην τέταρτη γραμμή και στη τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Returns:**
float - Το στοιχείο στην τέταρτη γραμμή και την τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .
### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Λαμβάνει το στοιχείο στην τέταρτη γραμμή και στη τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Returns:**
float - Το στοιχείο στην τέταρτη γραμμή και την τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix .
### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Λαμβάνει το στοιχείο στην καθορισμένη γραμμή και στη στήλη στο Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γραμμή | int | Ο αριθμός της γραμμής. |
| στήλη | int | Ο αριθμός της στήλης. |

**Returns:**
float - Το στοιχείο στην καθορισμένη γραμμή και στήλη.
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




### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στη στήλη 0 αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στη γραμμή 0 και στη στήλη 0 αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στην πρώτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στη γραμμή 0 και στην πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix  . |

### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στη γραμμή 0 και στη δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στην τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στη γραμμή 0 και στην τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Ορίζει το στοιχείο στη γραμμή 0 (μηδέν) και στη τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στη γραμμή 0 και στην τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Ορίζει το στοιχείο στην πρώτη γραμμή και στη στήλη 0 (μηδέν) αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην πρώτη γραμμή και στη στήλη 0 αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Ορίζει το στοιχείο στην πρώτη γραμμή και στην πρώτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην πρώτη γραμμή και στην πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Ορίζει το στοιχείο στην πρώτη γραμμή και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην πρώτη γραμμή και στη δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Ορίζει το στοιχείο στην πρώτη γραμμή και στην τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην πρώτη γραμμή και στην τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Ορίζει το στοιχείο στην πρώτη γραμμή και στη τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην πρώτη γραμμή και στην τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Ορίζει το στοιχείο στη δεύτερη γραμμή και στη στήλη 0 (μηδέν) αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στη δεύτερη γραμμή και στη στήλη 0 αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Ορίζει το στοιχείο στη δεύτερη γραμμή και στην πρώτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στη δεύτερη σειρά και πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Ορίζει το στοιχείο στη δεύτερη γραμμή και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στη δεύτερη σειρά και δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Ορίζει το στοιχείο στη δεύτερη γραμμή και στην τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στη δεύτερη σειρά και τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Ορίζει το στοιχείο στη δεύτερη γραμμή και στη τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στη δεύτερη σειρά και τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Ορίζει το στοιχείο στην τρίτη γραμμή και στη στήλη 0 (μηδέν) αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην τρίτη σειρά και 0 στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Ορίζει το στοιχείο στην τρίτη γραμμή και στην πρώτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην τρίτη σειρά και πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Ορίζει το στοιχείο στην τρίτη γραμμή και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην τρίτη σειρά και δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Ορίζει το στοιχείο στην τρίτη γραμμή και στην τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην τρίτη σειρά και τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Ορίζει το στοιχείο στην τρίτη γραμμή και στη τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην τρίτη σειρά και τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Ορίζει το στοιχείο στην τέταρτη γραμμή και στη στήλη 0 (μηδέν) αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην τέταρτη σειρά και 0 στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Ορίζει το στοιχείο στην τέταρτη γραμμή και στην πρώτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην τέταρτη σειρά και πρώτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Ορίζει το στοιχείο στην τέταρτη γραμμή και στη δεύτερη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην τέταρτη σειρά και δεύτερη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Ορίζει το στοιχείο στην τέταρτη γραμμή και στην τρίτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην τέταρτη σειρά και τρίτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Ορίζει το στοιχείο στην τέταρτη γραμμή και στην τέταρτη στήλη αυτού του Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το στοιχείο στην τέταρτη σειρά και τέταρτη στήλη αυτού του  Aspose.Imaging.ColorMatrix . |

### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Ορίζει το στοιχείο στη συγκεκριμένη γραμμή και στήλη στο Aspose.Imaging.ColorMatrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γραμμή | int | Ο αριθμός της γραμμής. |
| στήλη | int | Ο αριθμός της στήλης. |
| τιμή | float | Η τιμή |

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

