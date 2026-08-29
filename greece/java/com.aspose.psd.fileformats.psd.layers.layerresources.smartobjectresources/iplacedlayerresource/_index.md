---
title: "IPlacedLayerResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ορίζει τη διεπαφή IPlacedLayerResource που περιέχει πληροφορίες σχετικά με ένα τοποθετημένο στρώμα στο αρχείο PSD."
type: docs
weight: 17
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

Ορίζει τη διεπαφή IPlacedLayerResource που περιέχει πληροφορίες σχετικά με ένα τοποθετημένο στρώμα στο αρχείο PSD. Είναι μια διεπαφή σήμανσης που χρησιμοποιείται για τον καθορισμό των πόρων PlLd, Sold και Sole στις εικόνες Adobe\ufffd Photoshop\ufffd. Χρησιμοποιείται για την υποστήριξη εξυπνων αντικειμένων στρωμάτων στις εικόνες Adobe\ufffd Photoshop\ufffd.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Λαμβάνει ή ορίζει την πολιτική anti-alias του τοποθετημένου στρώματος στην εικόνα PSD. |
| [getBottom()](#getBottom--) | Λαμβάνει ή ορίζει τη θέση κάτω του τοποθετημένου στρώματος στην εικόνα PSD. |
| [getBounds()](#getBounds--) | Λαμβάνει ή ορίζει τα όρια του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Λαμβάνει ή ορίζει τη μονάδα μέτρησης των οριζόντιων σημείων πλέγματος. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getItems()](#getItems--) | Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης. |
| [getLeft()](#getLeft--) | Λαμβάνει ή ορίζει τη θέση αριστερά του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getPageNumber()](#getPageNumber--) | Λαμβάνει ή ορίζει τον αριθμό σελίδας του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getPerspective()](#getPerspective--) | Λαμβάνει ή ορίζει την τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Λαμβάνει ή ορίζει την άλλη τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Λαμβάνει ή ορίζει τον τύπο του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getRight()](#getRight--) | Λαμβάνει ή ορίζει τη θέση δεξιά του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getTop()](#getTop--) | Λαμβάνει ή ορίζει τη θέση πάνω του τοποθετημένου στρώματος στην εικόνα PSD. |
| [getTotalPages()](#getTotalPages--) | Λαμβάνει ή ορίζει τις συνολικές σελίδες του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getUOrder()](#getUOrder--) | Λαμβάνει ή ορίζει την τιμή σειράς U του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getUniqueId()](#getUniqueId--) | Λαμβάνει ή ορίζει το παγκόσμιο μοναδικό αναγνωριστικό του τοποθετημένου έξυπνου αντικειμένου στρώματος στην εικόνα PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Λαμβάνει ή ορίζει την τιμή σειράς V του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getValue()](#getValue--) | Λαμβάνει ή ορίζει την τιμή παραμόρφωσης του τοποθετημένου στρώματος στην εικόνα PSD. |
| [getVersion()](#getVersion--) | Λαμβάνει την έκδοση του τοποθετημένου στρώματος στο αρχείο PSD, συνήθως 3-5. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Λαμβάνει ή ορίζει τη μονάδα μέτρησης των κατακόρυφων σημείων πλέγματος. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD. |
| [isCustom()](#isCustom--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στυλ παραμόρφωσης αυτής της παρουσίας είναι προσαρμοσμένο. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Λαμβάνει ή ορίζει την πολιτική anti-alias του τοποθετημένου στρώματος στην εικόνα PSD. |
| [setBottom(double value)](#setBottom-double-) | Λαμβάνει ή ορίζει τη θέση κάτω του τοποθετημένου στρώματος στην εικόνα PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Λαμβάνει ή ορίζει τα όρια του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στυλ παραμόρφωσης αυτής της παρουσίας είναι προσαρμοσμένο. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Λαμβάνει ή ορίζει τη μονάδα μέτρησης των οριζόντιων σημείων πλέγματος. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης. |
| [setLeft(double value)](#setLeft-double-) | Λαμβάνει ή ορίζει τη θέση αριστερά του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setPageNumber(int value)](#setPageNumber-int-) | Λαμβάνει ή ορίζει τον αριθμό σελίδας του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setPerspective(double value)](#setPerspective-double-) | Λαμβάνει ή ορίζει την τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Λαμβάνει ή ορίζει την άλλη τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Λαμβάνει ή ορίζει τον τύπο του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setRight(double value)](#setRight-double-) | Λαμβάνει ή ορίζει τη θέση δεξιά του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setTop(double value)](#setTop-double-) | Λαμβάνει ή ορίζει τη θέση πάνω του τοποθετημένου στρώματος στην εικόνα PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | Λαμβάνει ή ορίζει τις συνολικές σελίδες του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setUOrder(int value)](#setUOrder-int-) | Λαμβάνει ή ορίζει την τιμή σειράς U του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Λαμβάνει ή ορίζει το παγκόσμιο μοναδικό αναγνωριστικό του τοποθετημένου έξυπνου αντικειμένου στρώματος στην εικόνα PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Λαμβάνει ή ορίζει την τιμή σειράς V του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setValue(double value)](#setValue-double-) | Λαμβάνει ή ορίζει την τιμή παραμόρφωσης του τοποθετημένου στρώματος στην εικόνα PSD. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Λαμβάνει ή ορίζει τη μονάδα μέτρησης των κατακόρυφων σημείων πλέγματος. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD. |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


Λαμβάνει ή ορίζει την πολιτική anti-alias του τοποθετημένου στρώματος στην εικόνα PSD.

Value: Η πολιτική anti alias του τοποθετημένου στρώματος.

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


Λαμβάνει ή ορίζει τη θέση κάτω του τοποθετημένου στρώματος στην εικόνα PSD.

Value: Η κάτω θέση του τοποθετημένου στρώματος.

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Λαμβάνει ή ορίζει τα όρια του τοποθετημένου στρώματος στο αρχείο PSD.

Value: Τα όρια του τοποθετημένου στρώματος.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


Λαμβάνει ή ορίζει τη μονάδα μέτρησης των οριζόντιων σημείων πλέγματος.

Τιμή: Η μονάδα μέτρησης των οριζόντιων σημείων πλέγματος.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος.

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης.

Τιμή: Τα στοιχεία παραμόρφωσης.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


Λαμβάνει ή ορίζει τη θέση αριστερά του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η αριστερή θέση του τοποθετημένου στρώματος.

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Λαμβάνει ή ορίζει τον αριθμό σελίδας του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Ο αριθμός σελίδας του τοποθετημένου στρώματος.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


Λαμβάνει ή ορίζει την τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η τιμή προοπτικής του τοποθετημένου στρώματος.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


Λαμβάνει ή ορίζει την άλλη τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η άλλη τιμή προοπτικής του τοποθετημένου στρώματος.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


Λαμβάνει ή ορίζει τον τύπο του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Ο τύπος του τοποθετημένου στρώματος.

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


Λαμβάνει ή ορίζει τη θέση δεξιά του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η δεξιά θέση του τοποθετημένου στρώματος.

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


Λαμβάνει ή ορίζει τη θέση πάνω του τοποθετημένου στρώματος στην εικόνα PSD.

Τιμή: Η πάνω θέση του τοποθετημένου στρώματος.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


Λαμβάνει ή ορίζει τις συνολικές σελίδες του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Οι συνολικές σελίδες του τοποθετημένου στρώματος.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Ο πίνακας μετασχηματισμού του τοποθετημένου στρώματος.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


Λαμβάνει ή ορίζει την τιμή σειράς U του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η τιμή σειράς U του τοποθετημένου στρώματος.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


Λαμβάνει ή ορίζει το παγκόσμιο μοναδικό αναγνωριστικό του τοποθετημένου έξυπνου αντικειμένου στρώματος στην εικόνα PSD.

Τιμή: Το μοναδικό αναγνωριστικό του τοποθετημένου στρώματος.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public abstract System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public abstract int getVOrder()
```


Λαμβάνει ή ορίζει την τιμή σειράς V του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η τιμή σειράς V του τοποθετημένου στρώματος.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


Λαμβάνει ή ορίζει την τιμή παραμόρφωσης του τοποθετημένου στρώματος στην εικόνα PSD.

Τιμή: Η τιμή παραμόρφωσης του τοποθετημένου στρώματος.

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


Λαμβάνει την έκδοση του τοποθετημένου στρώματος στο αρχείο PSD, συνήθως 3-5.

Τιμή: Η έκδοση του τοποθετημένου ή του έξυπνου αντικειμένου στρώματος.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


Λαμβάνει ή ορίζει τη μονάδα μέτρησης των κατακόρυφων σημείων πλέγματος.

Τιμή: Η μονάδα μέτρησης των κάθετων σημείων πλέγματος.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος.

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στυλ παραμόρφωσης αυτής της παρουσίας είναι προσαρμοσμένο. Εάν είναι true περιέχει σημεία πλέγματος. Εάν οριστεί σε false διαγράφει τα σημεία πλέγματος.

Τιμή:  true  εάν ο πόρος του τοποθετημένου ή του έξυπνου αντικειμένου στρώματος έχει προσαρμοσμένο στυλ· διαφορετικά,  false .

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


Λαμβάνει ή ορίζει την πολιτική anti-alias του τοποθετημένου στρώματος στην εικόνα PSD.

Value: Η πολιτική anti alias του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


Λαμβάνει ή ορίζει τη θέση κάτω του τοποθετημένου στρώματος στην εικόνα PSD.

Value: Η κάτω θέση του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


Λαμβάνει ή ορίζει τα όρια του τοποθετημένου στρώματος στο αρχείο PSD.

Value: Τα όρια του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στυλ παραμόρφωσης αυτής της παρουσίας είναι προσαρμοσμένο. Εάν είναι true περιέχει σημεία πλέγματος. Εάν οριστεί σε false διαγράφει τα σημεία πλέγματος.

Τιμή:  true  εάν ο πόρος του τοποθετημένου ή του έξυπνου αντικειμένου στρώματος έχει προσαρμοσμένο στυλ· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


Λαμβάνει ή ορίζει τη μονάδα μέτρησης των οριζόντιων σημείων πλέγματος.

Τιμή: Η μονάδα μέτρησης των οριζόντιων σημείων πλέγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης.

Τιμή: Τα στοιχεία παραμόρφωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


Λαμβάνει ή ορίζει τη θέση αριστερά του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η αριστερή θέση του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


Λαμβάνει ή ορίζει τον αριθμό σελίδας του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Ο αριθμός σελίδας του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


Λαμβάνει ή ορίζει την τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η τιμή προοπτικής του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


Λαμβάνει ή ορίζει την άλλη τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η άλλη τιμή προοπτικής του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


Λαμβάνει ή ορίζει τον τύπο του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Ο τύπος του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


Λαμβάνει ή ορίζει τη θέση δεξιά του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η δεξιά θέση του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


Λαμβάνει ή ορίζει τη θέση πάνω του τοποθετημένου στρώματος στην εικόνα PSD.

Τιμή: Η πάνω θέση του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


Λαμβάνει ή ορίζει τις συνολικές σελίδες του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Οι συνολικές σελίδες του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Ο πίνακας μετασχηματισμού του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


Λαμβάνει ή ορίζει την τιμή σειράς U του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η τιμή σειράς U του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


Λαμβάνει ή ορίζει το παγκόσμιο μοναδικό αναγνωριστικό του τοποθετημένου έξυπνου αντικειμένου στρώματος στην εικόνα PSD.

Τιμή: Το μοναδικό αναγνωριστικό του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


Λαμβάνει ή ορίζει την τιμή σειράς V του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η τιμή σειράς V του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


Λαμβάνει ή ορίζει την τιμή παραμόρφωσης του τοποθετημένου στρώματος στην εικόνα PSD.

Τιμή: Η τιμή παραμόρφωσης του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


Λαμβάνει ή ορίζει τη μονάδα μέτρησης των κατακόρυφων σημείων πλέγματος.

Τιμή: Η μονάδα μέτρησης των κάθετων σημείων πλέγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double[] |  |

