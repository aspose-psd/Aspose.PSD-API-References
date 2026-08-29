---
title: "UnitArrayStructure"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ορίζει την κλάση UnitArrayStructure που περιέχει έναν πίνακα τιμών double και τη μονάδα μέτρησής τους."
type: docs
weight: 27
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
```
public final class UnitArrayStructure extends OSTypeStructure
```

Ορίζει την κλάση UnitArrayStructure που περιέχει έναν πίνακα τιμών double και τη μονάδα μέτρησής τους. Χρησιμοποιείται στους πόρους αρχείων PSD, συνήθως από [ObjectArrayStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [UnitArrayStructure(ClassID keyName, int unitType, double[] values)](#UnitArrayStructure-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-int-double---) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [UnitArrayStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [StructureKey](#StructureKey) | Ορίζει το κλειδί 'UnFl' του [UnitArrayStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container)](#-T-findByKeyName-from-placed-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Βρίσκει τη δομή με την τιμή του ονόματος κλειδιού. |
| [<T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items)](#-T-findByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Βρίσκει τη δομή με την τιμή του ονόματος κλειδιού. |
| [arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix)](#arrangeToDictionary-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Διατάσσει τις δομές σε ένα λεξικό με βάση το όνομα κλειδιού. |
| [createColorDescriptor_internalized(Color value)](#createColorDescriptor-internalized-com.aspose.psd.Color-) |  |
| [createColorDescriptor_internalized(Color value, String keyName)](#createColorDescriptor-internalized-com.aspose.psd.Color-java.lang.String-) | Δημιουργεί το [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) με τιμή χρώματος με το καθορισμένο όνομα κλειδιού. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getBoolValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Λαμβάνει την λογική τιμή από τη λίστα δομών με το όνομα κλειδιού. |
| [getClass()](#getClass--) |  |
| [getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getColorValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Λαμβάνει την τιμή χρώματος από τη λίστα δομών με το όνομα κλειδιού. |
| [getColorValue_internalized(List<OSTypeStructure> itemsList)](#getColorValue-internalized-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) |  |
| [getCopy_internalized()](#getCopy-internalized--) | Δημιουργεί το πλήρες αντίγραφο αυτής της δομής. |
| [getHeaderLength()](#getHeaderLength--) | Λαμβάνει το μήκος της κεφαλίδας. |
| [getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getInt32Value-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Λαμβάνει την τιμή int32 από τη λίστα δομών με το όνομα κλειδιού. |
| [getKey()](#getKey--) | Λαμβάνει αυτό το κλειδί δομής πίνακα μονάδας. |
| [getKeyName()](#getKeyName--) | Λαμβάνει ή ορίζει το όνομα κλειδιού. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του OSTypeStructure σε bytes. |
| [getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Λαμβάνει τη λίστα τιμών δομών από άλλη λίστα δομών με το όνομα κλειδιού. |
| [getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getPointDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Λαμβάνει την τιμή PointF από τη λίστα δομών με το όνομα κλειδιού. |
| [getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getRectDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Λαμβάνει την τιμή RectangleF από τη λίστα δομών με το όνομα κλειδιού. |
| [getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getStringValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Λαμβάνει την τιμή συμβολοσειράς από τη λίστα δομών με το όνομα κλειδιού. |
| [getUnitType()](#getUnitType--) | Λαμβάνει ή ορίζει τον τύπο μονάδας μέτρησης των τιμών του [UnitArrayStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure). |
| [getValueCount()](#getValueCount--) | Λαμβάνει τον αριθμό των τιμών. |
| [getValues()](#getValues--) | Λαμβάνει ή ορίζει τις τιμές της δομής πίνακα μονάδας. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeByKeyName_internalized(String keyName, System.Collections.Generic.List<OSTypeStructure> items)](#removeByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Βρίσκει και αφαιρεί τη δομή από τη λίστα στοιχείων εισόδου. |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Αποθηκεύει τη δομή στο καθορισμένο κοντέινερ ροής. |
| [saveWithoutKeyName(StreamContainer streamContainer)](#saveWithoutKeyName-com.aspose.psd.StreamContainer-) | Αποθηκεύει τη δομή στο καθορισμένο κοντέινερ ροής. |
| [setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setBoolValue-internalized-boolean-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ορίζει την λογική τιμή στη λίστα δομών με το όνομα κλειδιού. |
| [setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setColorValue-internalized-com.aspose.psd.Color-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ορίζει την τιμή χρώματος σε μια λίστα δομών με το όνομα κλειδιού. |
| [setColorValue_internalized(Color value, List<OSTypeStructure> itemsList)](#setColorValue-internalized-com.aspose.psd.Color-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) |  |
| [setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setInt32Value-internalized-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ορίζει την τιμή int32 στη λίστα δομών με το όνομα κλειδιού. |
| [setKeyName(ClassID value)](#setKeyName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Λαμβάνει ή ορίζει το όνομα κλειδιού. |
| [setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ορίζει τη λίστα τιμών δομών σε άλλη λίστα δομών με το όνομα κλειδιού. |
| [setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setPointDoubleValue-internalized-com.aspose.psd.PointF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ορίζει την τιμή PointF στη λίστα δομών με το όνομα κλειδιού. |
| [setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setRectDoubleValue-internalized-com.aspose.psd.RectangleF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ορίζει την τιμή RectangleF στη λίστα δομών με το όνομα κλειδιού. |
| [setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setStringValue-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Ορίζει την τιμή της συμβολοσειράς στη λίστα δομών με βάση το όνομα κλειδιού. |
| [setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items)](#setToList-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Προσθέτει ή ενημερώνει τη δομή στη λίστα στοιχείων εισόδου. |
| [setUnitType(int value)](#setUnitType-int-) | Λαμβάνει ή ορίζει τον τύπο μονάδας μέτρησης των τιμών του [UnitArrayStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure). |
| [setValues(double[] value)](#setValues-double---) | Λαμβάνει ή ορίζει τις τιμές της δομής πίνακα μονάδας. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### UnitArrayStructure(ClassID keyName, int unitType, double[] values) {#UnitArrayStructure-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-int-double---}
```
public UnitArrayStructure(ClassID keyName, int unitType, double[] values)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [UnitArrayStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keyName | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Όνομα του κλειδιού. |
| unitType | int | Τύπος της μονάδας. |
| τιμές | double[] | Οι τιμές. |

### StructureKey {#StructureKey}
```
public static final int StructureKey
```


Ορίζει το κλειδί 'UnFl' του [UnitArrayStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure).

### <T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container) {#-T-findByKeyName-from-placed-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public static T <T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container)
```


Βρίσκει τη δομή με την τιμή του ονόματος κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keyName | java.lang.String | Το όνομα κλειδιού. |
|  | container | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Το δοχείο των στοιχείων στο οποίο θα γίνει η αναζήτηση. |

T : Ο τύπος του αντικειμένου αποτελέσματος. |

**Returns:**
T - Η δομή με τιμή ονόματος κλειδιού.
### <T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items) {#-T-findByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static T <T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items)
```


Βρίσκει τη δομή με την τιμή του ονόματος κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keyName | java.lang.String | Το όνομα κλειδιού. |
|  | στοιχεία | com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Τα στοιχεία για αναζήτηση. |

T : Ο τύπος του αντικειμένου αποτελέσματος. |

**Returns:**
T - Η δομή με τιμή ονόματος κλειδιού.
### arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix) {#arrangeToDictionary-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static System.Collections.Generic.Dictionary<String,OSTypeStructure> arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix)
```


Διατάσσει τις δομές σε ένα λεξικό με βάση το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| structures | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Οι δομές |
| λεξικό | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Το λεξικό για διάταξη |
| πρόθεμα | java.lang.String | Το πρόθεμα για ονόματα κλειδιών. |

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Δομημένες δομές ως λεξικό κατά όνομα κλειδιού.
### createColorDescriptor_internalized(Color value) {#createColorDescriptor-internalized-com.aspose.psd.Color-}
```
public static DescriptorStructure createColorDescriptor_internalized(Color value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### createColorDescriptor_internalized(Color value, String keyName) {#createColorDescriptor-internalized-com.aspose.psd.Color-java.lang.String-}
```
public static DescriptorStructure createColorDescriptor_internalized(Color value, String keyName)
```


Δημιουργεί το [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) με τιμή χρώματος με το καθορισμένο όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Η τιμή του χρώματος. |
| keyName | java.lang.String | Το όνομα κλειδιού. |

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
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
### getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getBoolValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static boolean getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Λαμβάνει την λογική τιμή από τη λίστα δομών με το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών για αναζήτηση. |
| keyName | java.lang.String | Το όνομα κλειδιού για αναζήτηση. |

**Returns:**
boolean - Η λογική τιμή από τη λίστα δομών εάν υπάρχει, διαφορετικά η προεπιλεγμένη τιμή.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getColorValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static Color getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Λαμβάνει την τιμή χρώματος από τη λίστα δομών με το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών για αναζήτηση. |
| keyName | java.lang.String | Το όνομα κλειδιού για αναζήτηση. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color value from the structures list if it exists, otherwise the default value.
### getColorValue_internalized(List<OSTypeStructure> itemsList) {#getColorValue-internalized-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static Color getColorValue_internalized(List<OSTypeStructure> itemsList)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| itemsList | java.util.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

**Returns:**
[Color](../../com.aspose.psd/color)
### getCopy_internalized() {#getCopy-internalized--}
```
public final OSTypeStructure getCopy_internalized()
```


Δημιουργεί το πλήρες αντίγραφο αυτής της δομής.

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - Returns the full copy of this structure.
### getHeaderLength() {#getHeaderLength--}
```
public int getHeaderLength()
```


Λαμβάνει το μήκος της κεφαλίδας.

**Returns:**
int - Το μήκος της κεφαλίδας
### getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getInt32Value-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static int getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Λαμβάνει την τιμή int32 από τη λίστα δομών με το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών για αναζήτηση. |
| keyName | java.lang.String | Το όνομα κλειδιού για αναζήτηση. |

**Returns:**
int - Η τιμή int32 από τη λίστα δομών εάν υπάρχει, διαφορετικά η προεπιλεγμένη τιμή.
### getKey() {#getKey--}
```
public int getKey()
```


Λαμβάνει αυτό το κλειδί δομής πίνακα μονάδας.

**Returns:**
int
### getKeyName() {#getKeyName--}
```
public final ClassID getKeyName()
```


Λαμβάνει ή ορίζει το όνομα κλειδιού.

Τιμή: Το όνομα του κλειδιού.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getLength() {#getLength--}
```
public int getLength()
```


Λαμβάνει το μήκος του OSTypeStructure σε bytes.

**Returns:**
int
### getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static System.Collections.Generic.List<OSTypeStructure> getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Λαμβάνει τη λίστα τιμών δομών από άλλη λίστα δομών με το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών για αναζήτηση. |
| keyName | java.lang.String | Το όνομα κλειδιού για αναζήτηση. |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Η λίστα τιμών δομών από τη λίστα άλλων δομών εάν υπάρχει, διαφορετικά η προεπιλεγμένη τιμή.
### getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getPointDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static PointF getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Λαμβάνει την τιμή PointF από τη λίστα δομών με το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών για αναζήτηση. |
| keyName | java.lang.String | Το όνομα κλειδιού για αναζήτηση. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The PointF value from the structures list if it exists, otherwise the default value.
### getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getRectDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static RectangleF getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Λαμβάνει την τιμή RectangleF από τη λίστα δομών με το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών για αναζήτηση. |
| keyName | java.lang.String | Το όνομα κλειδιού για αναζήτηση. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The RectangleF value from the structures list if it exists, otherwise the default value.
### getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getStringValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static String getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Λαμβάνει την τιμή συμβολοσειράς από τη λίστα δομών με το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών για αναζήτηση. |
| keyName | java.lang.String | Το όνομα κλειδιού για αναζήτηση. |

**Returns:**
java.lang.String - Η τιμή συμβολοσειράς από τη λίστα δομών εάν υπάρχει, διαφορετικά η προεπιλεγμένη τιμή.
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


Λαμβάνει ή ορίζει τον τύπο μονάδας μέτρησης των τιμών του [UnitArrayStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure).

Τιμή: Ο τύπος μονάδας μέτρησης.

**Returns:**
int
### getValueCount() {#getValueCount--}
```
public final int getValueCount()
```


Λαμβάνει τον αριθμό των τιμών.

Τιμή: Ο αριθμός τιμών στη δομή πίνακα μονάδας.

**Returns:**
int
### getValues() {#getValues--}
```
public final double[] getValues()
```


Λαμβάνει ή ορίζει τις τιμές της δομής πίνακα μονάδας.

**Returns:**
double[]
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




### removeByKeyName_internalized(String keyName, System.Collections.Generic.List<OSTypeStructure> items) {#removeByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void removeByKeyName_internalized(String keyName, System.Collections.Generic.List<OSTypeStructure> items)
```


Βρίσκει και αφαιρεί τη δομή από τη λίστα στοιχείων εισόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keyName | java.lang.String | Το όνομα κλειδιού. |
| στοιχεία | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Τα στοιχεία. |

### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Αποθηκεύει τη δομή στο καθορισμένο κοντέινερ ροής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής. |

### saveWithoutKeyName(StreamContainer streamContainer) {#saveWithoutKeyName-com.aspose.psd.StreamContainer-}
```
public final void saveWithoutKeyName(StreamContainer streamContainer)
```


Αποθηκεύει τη δομή στο καθορισμένο κοντέινερ ροής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής. |

### setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setBoolValue-internalized-boolean-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ορίζει την λογική τιμή στη λίστα δομών με το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Η τιμή που θα οριστεί. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών. |
| keyName | java.lang.String | Το όνομα κλειδιού. |

### setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setColorValue-internalized-com.aspose.psd.Color-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ορίζει την τιμή χρώματος σε μια λίστα δομών με το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Η τιμή που θα οριστεί. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών. |
| keyName | java.lang.String | Το όνομα κλειδιού. |

### setColorValue_internalized(Color value, List<OSTypeStructure> itemsList) {#setColorValue-internalized-com.aspose.psd.Color-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void setColorValue_internalized(Color value, List<OSTypeStructure> itemsList)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |
| itemsList | java.util.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

### setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setInt32Value-internalized-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ορίζει την τιμή int32 στη λίστα δομών με το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η τιμή που θα οριστεί. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών. |
| keyName | java.lang.String | Το όνομα κλειδιού. |

### setKeyName(ClassID value) {#setKeyName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setKeyName(ClassID value)
```


Λαμβάνει ή ορίζει το όνομα κλειδιού.

Τιμή: Το όνομα του κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ορίζει τη λίστα τιμών δομών σε άλλη λίστα δομών με το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η τιμή που θα οριστεί. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών. |
| keyName | java.lang.String | Το όνομα κλειδιού. |

### setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setPointDoubleValue-internalized-com.aspose.psd.PointF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ορίζει την τιμή PointF στη λίστα δομών με το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Η τιμή που θα οριστεί. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών. |
| keyName | java.lang.String | Το όνομα κλειδιού. |

### setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setRectDoubleValue-internalized-com.aspose.psd.RectangleF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ορίζει την τιμή RectangleF στη λίστα δομών με το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Η τιμή που θα οριστεί. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών. |
| keyName | java.lang.String | Το όνομα κλειδιού. |

### setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setStringValue-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Ορίζει την τιμή της συμβολοσειράς στη λίστα δομών με βάση το όνομα κλειδιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Η τιμή που θα οριστεί. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Η λίστα δομών. |
| keyName | java.lang.String | Το όνομα κλειδιού. |

### setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items) {#setToList-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items)
```


Προσθέτει ή ενημερώνει τη δομή στη λίστα στοιχείων εισόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Η δομή για προσθήκη ή ενημέρωση. |
| στοιχεία | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Τα στοιχεία. |

### setUnitType(int value) {#setUnitType-int-}
```
public final void setUnitType(int value)
```


Λαμβάνει ή ορίζει τον τύπο μονάδας μέτρησης των τιμών του [UnitArrayStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure).

Τιμή: Ο τύπος μονάδας μέτρησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setValues(double[] value) {#setValues-double---}
```
public final void setValues(double[] value)
```


Λαμβάνει ή ορίζει τις τιμές της δομής πίνακα μονάδας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double[] |  |

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

