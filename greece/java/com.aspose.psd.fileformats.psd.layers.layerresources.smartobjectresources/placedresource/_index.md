---
title: "PlacedResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ορίζει την κλάση PlacedResource που περιέχει κοινές πληροφορίες σχετικά με ένα τοποθετημένο στρώμα ή ένα στρώμα έξυπνου αντικειμένου στο αρχείο PSD."
type: docs
weight: 12
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.IPlacedLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource)
```
public abstract class PlacedResource extends LayerResource implements IPlacedLayerResource
```

Ορίζει την κλάση PlacedResource που περιέχει κοινές πληροφορίες σχετικά με ένα τοποθετημένο στρώμα ή ένα στρώμα έξυπνου αντικειμένου στο αρχείο PSD. Χρησιμοποιείται για την υποστήριξη στρωμάτων έξυπνου αντικειμένου στις εικόνες Adobe\ufffd Photoshop\ufffd.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | Το προσαρμοσμένο όνομα παραμόρφωσης περιτύλιξης |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | Το προεπιλεγμένο όνομα κλάσης παραμόρφωσης |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | Το προεπιλεγμένο όνομα κλάσης παραμόρφωσης |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | Η αναμενόμενη έκδοση περιγραφέα παραμόρφωσης |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | Η αναμενόμενη έκδοση παραμόρφωσης |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | Το όνομα οριζόντιου αναγνωριστικού |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | Το όνομα κλειδιού σημείων πλέγματος |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | Το όνομα αναγνωριστικού προσανατολισμού |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | Η αναμενόμενη τιμή έκδοσης |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Η έκδοση κεφαλίδας PSB |
| [PsbResourceSignature](#PsbResourceSignature) | Η υπογραφή πόρου ειδική για PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Η έκδοση κεφαλίδας PSD |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | Το όνομα αναγνωριστικού κλάσης λογικού σημείου |
| [ResourceSignature](#ResourceSignature) | Η κοινή υπογραφή πόρου. |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | Το μέγεθος του double |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | Το μέγεθος του int |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | Ο αριθμός τιμών μετασχηματισμού |
| [UOrderKey_internalized](#UOrderKey-internalized) | Το κλειδί σειράς u |
| [VOrderKey_internalized](#VOrderKey-internalized) | Το κλειδί σειράς v |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | Το όνομα κάθετου αναγνωριστικού |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | Το προσαρμοσμένο όνομα παραμόρφωσης |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | Το μήκος κεφαλίδας παραμόρφωσης. |
| [WarpKey_internalized](#WarpKey-internalized) | Το κλειδί παραμόρφωσης. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | Το όνομα χωρίς παραμόρφωση |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | Το κλειδί προοπτικής παραμόρφωσης |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | Η άλλη προοπτική παραμόρφωσης |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | Το κλειδί περιστροφής παραμόρφωσης |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | Το κλειδί στυλ παραμόρφωσης |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | Το κλειδί τιμής παραμόρφωσης |
| [ZeroChar_internalized](#ZeroChar-internalized) | Ο χαρακτήρας μηδέν. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Η άδεια venture. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Διασφαλίζει ότι η καθορισμένη πραγματική τιμή ισούται με την αναμενόμενη τιμή. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Ελέγχει και ορίζει αν ο πόρος είναι ειδικός για PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Λαμβάνει ή ορίζει την πολιτική anti-alias του τοποθετημένου στρώματος στην εικόνα PSD. |
| [getBottom()](#getBottom--) | Λαμβάνει ή ορίζει τη θέση κάτω του τοποθετημένου στρώματος στην εικόνα PSD. |
| [getBounds()](#getBounds--) | Λαμβάνει ή ορίζει τα όρια του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getClass()](#getClass--) |  |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Λαμβάνει ή ορίζει τον προεπιλεγμένο τύπο μονάδας για τις εκχωρημένες τιμές όπως Αριστερά, Πάνω, Δεξιά, Κάτω, TransformMatrix. |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Λαμβάνει ή ορίζει τη μονάδα μέτρησης των οριζόντιων σημείων πλέγματος. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getItems()](#getItems--) | Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLeft()](#getLeft--) | Λαμβάνει ή ορίζει τη θέση αριστερά του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getPageNumber()](#getPageNumber--) | Λαμβάνει ή ορίζει τον αριθμό σελίδας του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getPerspective()](#getPerspective--) | Λαμβάνει ή ορίζει την τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Λαμβάνει ή ορίζει την άλλη τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Λαμβάνει ή ορίζει τον τύπο του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getRight()](#getRight--) | Λαμβάνει ή ορίζει τη θέση δεξιά του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [getTop()](#getTop--) | Λαμβάνει ή ορίζει τη θέση πάνω του τοποθετημένου στρώματος στην εικόνα PSD. |
| [getTotalPages()](#getTotalPages--) | Λαμβάνει ή ορίζει τις συνολικές σελίδες του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getUOrder()](#getUOrder--) | Λαμβάνει ή ορίζει την τιμή σειράς U του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getUniqueId()](#getUniqueId--) | Λαμβάνει ή ορίζει το παγκόσμιο μοναδικό αναγνωριστικό του τοποθετημένου στρώματος στην εικόνα PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Λαμβάνει ή ορίζει την τιμή σειράς V του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getValue()](#getValue--) | Λαμβάνει ή ορίζει την τιμή παραμόρφωσης του τοποθετημένου στρώματος στην εικόνα PSD. |
| [getVersion()](#getVersion--) | Λαμβάνει την έκδοση του τοποθετημένου στρώματος στο αρχείο PSD, συνήθως 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Λαμβάνει ή ορίζει τη μονάδα μέτρησης των κατακόρυφων σημείων πλέγματος. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | Λαμβάνει ή ορίζει το όνομα κλάσης παραμόρφωσης. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | Λαμβάνει ή ορίζει την έκδοση περιγραφέα παραμόρφωσης. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | Λαμβάνει ή ορίζει την έκδοση παραμόρφωσης. |
| [get_Item(String index)](#get-Item-java.lang.String-) | Λαμβάνει το [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) στον καθορισμένο δείκτη. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει μονάδες ορίων. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [isCustom()](#isCustom--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στυλ παραμόρφωσης αυτής της παρουσίας είναι προσαρμοσμένο. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η προσανατολισμός περιστροφής αυτής της παρουσίας είναι οριζόντια. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Λαμβάνει ή ορίζει την πολιτική anti-alias του τοποθετημένου στρώματος στην εικόνα PSD. |
| [setBottom(double value)](#setBottom-double-) | Λαμβάνει ή ορίζει τη θέση κάτω του τοποθετημένου στρώματος στην εικόνα PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Λαμβάνει ή ορίζει τα όρια του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στυλ παραμόρφωσης αυτής της παρουσίας είναι προσαρμοσμένο. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Λαμβάνει ή ορίζει τον προεπιλεγμένο τύπο μονάδας για τις εκχωρημένες τιμές όπως Αριστερά, Πάνω, Δεξιά, Κάτω, TransformMatrix. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Λαμβάνει ή ορίζει τη μονάδα μέτρησης των οριζόντιων σημείων πλέγματος. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης. |
| [setLeft(double value)](#setLeft-double-) | Λαμβάνει ή ορίζει τη θέση αριστερά του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setPageNumber(int value)](#setPageNumber-int-) | Λαμβάνει ή ορίζει τον αριθμό σελίδας του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setPerspective(double value)](#setPerspective-double-) | Λαμβάνει ή ορίζει την τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Λαμβάνει ή ορίζει την άλλη τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Λαμβάνει ή ορίζει τον τύπο του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setRight(double value)](#setRight-double-) | Λαμβάνει ή ορίζει τη θέση δεξιά του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η προσανατολισμός περιστροφής αυτής της παρουσίας είναι οριζόντια. |
| [setTop(double value)](#setTop-double-) | Λαμβάνει ή ορίζει τη θέση πάνω του τοποθετημένου στρώματος στην εικόνα PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | Λαμβάνει ή ορίζει τις συνολικές σελίδες του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setUOrder(int value)](#setUOrder-int-) | Λαμβάνει ή ορίζει την τιμή σειράς U του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Λαμβάνει ή ορίζει το παγκόσμιο μοναδικό αναγνωριστικό του τοποθετημένου στρώματος στην εικόνα PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Λαμβάνει ή ορίζει την τιμή σειράς V του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setValue(double value)](#setValue-double-) | Λαμβάνει ή ορίζει την τιμή παραμόρφωσης του τοποθετημένου στρώματος στην εικόνα PSD. |
| [setVersion(int value)](#setVersion-int-) | Λαμβάνει την έκδοση του τοποθετημένου στρώματος στο αρχείο PSD, συνήθως 3. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Λαμβάνει ή ορίζει τη μονάδα μέτρησης των κατακόρυφων σημείων πλέγματος. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα κλάσης παραμόρφωσης. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | Λαμβάνει ή ορίζει την έκδοση περιγραφέα παραμόρφωσης. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | Λαμβάνει ή ορίζει την έκδοση παραμόρφωσης. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


Το προσαρμοσμένο όνομα παραμόρφωσης περιτύλιξης

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


Το προεπιλεγμένο όνομα κλάσης παραμόρφωσης

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


Το προεπιλεγμένο όνομα κλάσης παραμόρφωσης

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


Η αναμενόμενη έκδοση περιγραφέα παραμόρφωσης

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


Η αναμενόμενη έκδοση παραμόρφωσης

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


Το όνομα οριζόντιου αναγνωριστικού

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


Το όνομα κλειδιού σημείων πλέγματος

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


Το όνομα αναγνωριστικού προσανατολισμού

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


Η αναμενόμενη τιμή έκδοσης

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


Η έκδοση κεφαλίδας PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Η υπογραφή πόρου ειδική για PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


Η έκδοση κεφαλίδας PSD

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


Το όνομα αναγνωριστικού κλάσης λογικού σημείου

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Η κοινή υπογραφή πόρου.

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


Το μέγεθος του double

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


Το μέγεθος του int

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


Ο αριθμός τιμών μετασχηματισμού

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


Το κλειδί σειράς u

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


Το κλειδί σειράς v

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


Το όνομα κάθετου αναγνωριστικού

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


Το προσαρμοσμένο όνομα παραμόρφωσης

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


Το μήκος κεφαλίδας παραμόρφωσης.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


Το κλειδί παραμόρφωσης. Επίσης το προεπιλεγμένο όνομα κλάσης παραμόρφωσης.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


Το όνομα χωρίς παραμόρφωση

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


Το κλειδί προοπτικής παραμόρφωσης

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


Η άλλη προοπτική παραμόρφωσης

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


Το κλειδί περιστροφής παραμόρφωσης

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


Το κλειδί στυλ παραμόρφωσης

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


Το κλειδί τιμής παραμόρφωσης

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Ο χαρακτήρας μηδέν.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Η άδεια venture.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


Διασφαλίζει ότι η καθορισμένη πραγματική τιμή ισούται με την αναμενόμενη τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| actualValue | java.lang.Object | Η πραγματική τιμή. |
| expectedValue | java.lang.Object | Η αναμενόμενη τιμή. |
| μήνυμα | java.lang.String | Το μήνυμα. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Ελέγχει και ορίζει αν ο πόρος είναι ειδικός για PSB. Κάποιοι πόροι δεν αναγνωρίζονται προς το παρόν, αλλά διαθέτουμε πλήρη λίστα πόρων ειδικών για PSB που αλλάζουν τη συμπεριφορά τους κατά την αποθήκευση. Έτσι, πρέπει τουλάχιστον να ελέγξουμε αυτό στο UnknownResource.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | int | Το κλειδί. |

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
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


Λαμβάνει ή ορίζει την πολιτική anti-alias του τοποθετημένου στρώματος στην εικόνα PSD.

Value: Η πολιτική anti alias του τοποθετημένου στρώματος.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


Λαμβάνει ή ορίζει τη θέση κάτω του τοποθετημένου στρώματος στην εικόνα PSD.

Value: Η κάτω θέση του τοποθετημένου στρώματος.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Λαμβάνει ή ορίζει τα όρια του τοποθετημένου στρώματος στο αρχείο PSD.

Value: Τα όρια του τοποθετημένου στρώματος.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


Λαμβάνει ή ορίζει τον προεπιλεγμένο τύπο μονάδας για τις εκχωρημένες τιμές όπως Αριστερά, Πάνω, Δεξιά, Κάτω, TransformMatrix.

Value: Ο προεπιλεγμένος τύπος μονάδας μέτρησης.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Λαμβάνει ή ορίζει την κεφαλίδα.

Τιμή: Η κεφαλίδα.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


Λαμβάνει ή ορίζει τη μονάδα μέτρησης των οριζόντιων σημείων πλέγματος.

Τιμή: Η μονάδα μέτρησης των οριζόντιων σημείων πλέγματος.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης.

Τιμή: Τα στοιχεία παραμόρφωσης.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Λαμβάνει το κλειδί πόρου της στρώσης.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


Λαμβάνει ή ορίζει τη θέση αριστερά του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η αριστερή θέση του τοποθετημένου στρώματος.

**Returns:**
double
### getLength() {#getLength--}
```
public abstract int getLength()
```


Λαμβάνει το μήκος του πόρου της στρώσης σε bytes.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Λαμβάνει ή ορίζει τον αριθμό σελίδας του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Ο αριθμός σελίδας του τοποθετημένου στρώματος.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


Λαμβάνει ή ορίζει την τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η τιμή προοπτικής του τοποθετημένου στρώματος.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


Λαμβάνει ή ορίζει την άλλη τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η άλλη τιμή προοπτικής του τοποθετημένου στρώματος.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


Λαμβάνει ή ορίζει τον τύπο του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Ο τύπος του τοποθετημένου στρώματος.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Λαμβάνει το μήκος του προθέματος. Η προεπιλεγμένη τιμή είναι 12 για πόρους 8BIM και 16 για 8B64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| psdVersion | int | Η έκδοση PSD. |

**Returns:**
int - Το μήκος του προθέματος.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για πόρο στρώσης. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί.

**Returns:**
int
### getRight() {#getRight--}
```
public final double getRight()
```


Λαμβάνει ή ορίζει τη θέση δεξιά του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η δεξιά θέση του τοποθετημένου στρώματος.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


Λαμβάνει την υπογραφή του πόρου της στρώσης.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


Λαμβάνει ή ορίζει τη θέση πάνω του τοποθετημένου στρώματος στην εικόνα PSD.

Τιμή: Η πάνω θέση του τοποθετημένου στρώματος.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Λαμβάνει ή ορίζει τις συνολικές σελίδες του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Οι συνολικές σελίδες του τοποθετημένου στρώματος.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Ο πίνακας μετασχηματισμού του τοποθετημένου στρώματος.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


Λαμβάνει ή ορίζει την τιμή σειράς U του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η τιμή σειράς U του τοποθετημένου στρώματος.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


Λαμβάνει ή ορίζει το παγκόσμιο μοναδικό αναγνωριστικό του τοποθετημένου στρώματος στην εικόνα PSD.

Τιμή: Το μοναδικό αναγνωριστικό του τοποθετημένου στρώματος.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public final int getVOrder()
```


Λαμβάνει ή ορίζει την τιμή σειράς V του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η τιμή σειράς V του τοποθετημένου στρώματος.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Λαμβάνει ή ορίζει την τιμή παραμόρφωσης του τοποθετημένου στρώματος στην εικόνα PSD.

Τιμή: Η τιμή παραμόρφωσης του τοποθετημένου στρώματος.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Λαμβάνει την έκδοση του τοποθετημένου στρώματος στο αρχείο PSD, συνήθως 3.

Τιμή: Η έκδοση του τοποθετημένου στρώματος.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


Λαμβάνει ή ορίζει τη μονάδα μέτρησης των κατακόρυφων σημείων πλέγματος.

Τιμή: Η μονάδα μέτρησης των κάθετων σημείων πλέγματος.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης.

Τιμή: Το αναγνωριστικό κλάσης.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


Λαμβάνει ή ορίζει το όνομα κλάσης παραμόρφωσης.

Τιμή: Το όνομα κλάσης παραμόρφωσης.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


Λαμβάνει ή ορίζει την έκδοση περιγραφέα παραμόρφωσης.

Τιμή: Η έκδοση περιγραφέα παραμόρφωσης.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης.

Τιμή: Τα στοιχεία παραμόρφωσης.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


Λαμβάνει ή ορίζει την έκδοση παραμόρφωσης.

Τιμή: Η έκδοση παραμόρφωσης.

**Returns:**
int
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


Λαμβάνει το [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) στον καθορισμένο δείκτη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | java.lang.String | Το όνομα κλειδιού. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει μονάδες ορίων.

Τιμή:  true  εάν αυτή η παρουσία έχει μονάδες ορίων· διαφορετικά,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initProreties_internalized(PlaceResourceParams plLdResourceParams) {#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-}
```
public final void initProreties_internalized(PlaceResourceParams plLdResourceParams)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στυλ παραμόρφωσης αυτής της παρουσίας είναι προσαρμοσμένο. Εάν είναι true περιέχει σημεία πλέγματος. Εάν οριστεί σε false διαγράφει τα σημεία πλέγματος.

Τιμή:  true  εάν το τοποθετημένο στρώμα έχει προσαρμοσμένο στυλ· διαφορετικά,  false .

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Καθορίζει εάν ο πόρος είναι ειδικός για PSB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | int | Το κλειδί του πόρου. |

**Returns:**
boolean -  true  αν ο πόρος είναι ειδικός για PSB· διαφορετικά,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB.

Τιμή:  true  αν αυτή η παρουσία είναι πόρος ειδικός για PSB· διαφορετικά,  false .

**Returns:**
boolean
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η προσανατολισμός περιστροφής αυτής της παρουσίας είναι οριζόντια.

Τιμή:  true  εάν η προσανατολισμός περιστροφής είναι οριζόντια· διαφορετικά,  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public abstract void save(StreamContainer streamContainer, int psdVersion)
```


Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής στο οποίο θα αποθηκευτεί. |
| psdVersion | int | Η έκδοση PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής. |
| υπογραφή | int | Η υπογραφή. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής. |
| υπογραφή | int | Η υπογραφή. |
| isLengthLong | boolean | αν οριστεί σε  true  το μήκος είναι μεγάλο. |

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


Λαμβάνει ή ορίζει την πολιτική anti-alias του τοποθετημένου στρώματος στην εικόνα PSD.

Value: Η πολιτική anti alias του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Λαμβάνει ή ορίζει τη θέση κάτω του τοποθετημένου στρώματος στην εικόνα PSD.

Value: Η κάτω θέση του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Λαμβάνει ή ορίζει τα όρια του τοποθετημένου στρώματος στο αρχείο PSD.

Value: Τα όρια του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στυλ παραμόρφωσης αυτής της παρουσίας είναι προσαρμοσμένο. Εάν είναι true περιέχει σημεία πλέγματος. Εάν οριστεί σε false διαγράφει τα σημεία πλέγματος.

Τιμή:  true  εάν το τοποθετημένο στρώμα έχει προσαρμοσμένο στυλ· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Λαμβάνει ή ορίζει τον προεπιλεγμένο τύπο μονάδας για τις εκχωρημένες τιμές όπως Αριστερά, Πάνω, Δεξιά, Κάτω, TransformMatrix.

Value: Ο προεπιλεγμένος τύπος μονάδας μέτρησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Λαμβάνει ή ορίζει την κεφαλίδα.

Τιμή: Η κεφαλίδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


Λαμβάνει ή ορίζει τη μονάδα μέτρησης των οριζόντιων σημείων πλέγματος.

Τιμή: Η μονάδα μέτρησης των οριζόντιων σημείων πλέγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης.

Τιμή: Τα στοιχεία παραμόρφωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Λαμβάνει ή ορίζει τη θέση αριστερά του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η αριστερή θέση του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Λαμβάνει ή ορίζει τον αριθμό σελίδας του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Ο αριθμός σελίδας του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


Λαμβάνει ή ορίζει την τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η τιμή προοπτικής του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


Λαμβάνει ή ορίζει την άλλη τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η άλλη τιμή προοπτικής του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


Λαμβάνει ή ορίζει τον τύπο του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Ο τύπος του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Λαμβάνει ή ορίζει τη θέση δεξιά του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η δεξιά θέση του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η προσανατολισμός περιστροφής αυτής της παρουσίας είναι οριζόντια.

Τιμή:  true  εάν η προσανατολισμός περιστροφής είναι οριζόντια· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Λαμβάνει ή ορίζει τη θέση πάνω του τοποθετημένου στρώματος στην εικόνα PSD.

Τιμή: Η πάνω θέση του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


Λαμβάνει ή ορίζει τις συνολικές σελίδες του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Οι συνολικές σελίδες του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Ο πίνακας μετασχηματισμού του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


Λαμβάνει ή ορίζει την τιμή σειράς U του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η τιμή σειράς U του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


Λαμβάνει ή ορίζει το παγκόσμιο μοναδικό αναγνωριστικό του τοποθετημένου στρώματος στην εικόνα PSD.

Τιμή: Το μοναδικό αναγνωριστικό του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


Λαμβάνει ή ορίζει την τιμή σειράς V του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Η τιμή σειράς V του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Λαμβάνει ή ορίζει την τιμή παραμόρφωσης του τοποθετημένου στρώματος στην εικόνα PSD.

Τιμή: Η τιμή παραμόρφωσης του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Λαμβάνει την έκδοση του τοποθετημένου στρώματος στο αρχείο PSD, συνήθως 3.

Τιμή: Η έκδοση του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


Λαμβάνει ή ορίζει τη μονάδα μέτρησης των κατακόρυφων σημείων πλέγματος.

Τιμή: Η μονάδα μέτρησης των κάθετων σημείων πλέγματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD.

Τιμή: Τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης.

Τιμή: Το αναγνωριστικό κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


Λαμβάνει ή ορίζει το όνομα κλάσης παραμόρφωσης.

Τιμή: Το όνομα κλάσης παραμόρφωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


Λαμβάνει ή ορίζει την έκδοση περιγραφέα παραμόρφωσης.

Τιμή: Η έκδοση περιγραφέα παραμόρφωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


Λαμβάνει ή ορίζει την έκδοση παραμόρφωσης.

Τιμή: Η έκδοση παραμόρφωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο.

**Returns:**
java.lang.String - Ένα String που αντιπροσωπεύει αυτήν την παρουσία.
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

