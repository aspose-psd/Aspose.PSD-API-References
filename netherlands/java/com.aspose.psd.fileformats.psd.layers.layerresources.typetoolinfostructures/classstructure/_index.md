---
title: "ClassStructure"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De klasse‑structuur."
type: docs
weight: 12
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
```
public final class ClassStructure extends OSTypeStructure
```

De klasse‑structuur.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ClassStructure(ClassID keyName, ClassID classID, int structureKey)](#ClassStructure-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-int-) | Initialiseert een nieuw exemplaar van de [ClassStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure) klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [StructureKeyClss](#StructureKeyClss) | Identificeert de structuur‑sleutel. |
| [StructureKeyGlbc](#StructureKeyGlbc) | Identificeert de structuur‑sleutel. |
| [StructureKeyType](#StructureKeyType) | Identificeert de structuur‑sleutel. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [<T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container)](#-T-findByKeyName-from-placed-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Vindt de structuur op basis van de sleutelnaamwaarde. |
| [<T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items)](#-T-findByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Vindt de structuur op basis van de sleutelnaamwaarde. |
| [arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix)](#arrangeToDictionary-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Rangschikt structuren in één woordenboek op sleutelnaam. |
| [createColorDescriptor_internalized(Color value)](#createColorDescriptor-internalized-com.aspose.psd.Color-) |  |
| [createColorDescriptor_internalized(Color value, String keyName)](#createColorDescriptor-internalized-com.aspose.psd.Color-java.lang.String-) | Maakt de [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) met kleurwaarde met opgegeven sleutelnaam. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getBoolValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Haalt de booleaanse waarde op uit de structurenlijst op sleutelnaam. |
| [getClass()](#getClass--) |  |
| [getClassID()](#getClassID--) | Haalt op of stelt de klasse‑ID in. |
| [getClassName()](#getClassName--) | Haalt de klassenaam op of stelt deze in. |
| [getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getColorValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Haalt de kleurwaarde op uit de structurenlijst op sleutelnaam. |
| [getColorValue_internalized(List<OSTypeStructure> itemsList)](#getColorValue-internalized-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) |  |
| [getCopy_internalized()](#getCopy-internalized--) | Maakt een volledige kopie van deze structuur. |
| [getHeaderLength()](#getHeaderLength--) | Haalt de headerlengte op. |
| [getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getInt32Value-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Haalt de int32‑waarde op uit de structurenlijst op sleutelnaam. |
| [getKey()](#getKey--) | Haalt de structuur‑sleutel op. |
| [getKeyName()](#getKeyName--) | Haalt op of stelt de sleutelnaam in. |
| [getLength()](#getLength--) | Haalt de [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) lengte in bytes op. |
| [getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Haalt de lijst met structurenwaarde op uit een andere structurenlijst op sleutelnaam. |
| [getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getPointDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Haalt de PointF‑waarde op uit de structurenlijst op sleutelnaam. |
| [getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getRectDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Haalt de RectangleF‑waarde op uit de structurenlijst op sleutelnaam. |
| [getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getStringValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Haalt de tekenreekswaarde op uit de structurenlijst op sleutelnaam. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeByKeyName_internalized(String keyName, System.Collections.Generic.List<OSTypeStructure> items)](#removeByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Zoekt en verwijdert de structuur uit de invoer‑itemslijst. |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Slaat de structuur op in de opgegeven streamcontainer. |
| [saveWithoutKeyName(StreamContainer streamContainer)](#saveWithoutKeyName-com.aspose.psd.StreamContainer-) | Slaat de structuur op in de opgegeven streamcontainer. |
| [setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setBoolValue-internalized-boolean-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Stelt de booleaanse waarde in de structurenlijst in op sleutelnaam. |
| [setClassID(ClassID value)](#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Haalt op of stelt de klasse‑ID in. |
| [setClassName(String value)](#setClassName-java.lang.String-) | Haalt de klassenaam op of stelt deze in. |
| [setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setColorValue-internalized-com.aspose.psd.Color-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Stelt de kleurwaarde in een structurenlijst in op sleutelnaam. |
| [setColorValue_internalized(Color value, List<OSTypeStructure> itemsList)](#setColorValue-internalized-com.aspose.psd.Color-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) |  |
| [setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setInt32Value-internalized-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Stelt de int32‑waarde in de structurenlijst in op sleutelnaam. |
| [setKeyName(ClassID value)](#setKeyName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Haalt op of stelt de sleutelnaam in. |
| [setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Stelt de lijst met structurenwaarde in de andere structurenlijst in op sleutelnaam. |
| [setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setPointDoubleValue-internalized-com.aspose.psd.PointF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Stelt de PointF‑waarde in de structurenlijst in op sleutelnaam. |
| [setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setRectDoubleValue-internalized-com.aspose.psd.RectangleF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Stelt de RectangleF‑waarde in de structurenlijst in op sleutelnaam. |
| [setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setStringValue-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Stelt de tekenreekswaarde in voor de structurenlijst op basis van de sleutelnaam. |
| [setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items)](#setToList-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Voeg de structuur toe of werk deze bij in de invoeritemslijst. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ClassStructure(ClassID keyName, ClassID classID, int structureKey) {#ClassStructure-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-int-}
```
public ClassStructure(ClassID keyName, ClassID classID, int structureKey)
```


Initialiseert een nieuw exemplaar van de [ClassStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keyName | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Naam van de sleutel. |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | De klasse-ID. |
| structureKey | int | De structuur-sleutel. |

### StructureKeyClss {#StructureKeyClss}
```
public static final int StructureKeyClss
```


Identificeert de structuur‑sleutel.

### StructureKeyGlbc {#StructureKeyGlbc}
```
public static final int StructureKeyGlbc
```


Identificeert de structuur‑sleutel.

### StructureKeyType {#StructureKeyType}
```
public static final int StructureKeyType
```


Identificeert de structuur‑sleutel.

### <T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container) {#-T-findByKeyName-from-placed-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public static T <T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container)
```


Vindt de structuur op basis van de sleutelnaamwaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keyName | java.lang.String | De sleutelnaam. |
|  | container | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | De itemscontainer om in te zoeken. |

T : Het type van het resultaatobject. |

**Returns:**
T - De structuur op basis van de sleutelnaamwaarde.
### <T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items) {#-T-findByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static T <T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items)
```


Vindt de structuur op basis van de sleutelnaamwaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keyName | java.lang.String | De sleutelnaam. |
|  | items | com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De items om in te zoeken. |

T : Het type van het resultaatobject. |

**Returns:**
T - De structuur op basis van de sleutelnaamwaarde.
### arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix) {#arrangeToDictionary-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static System.Collections.Generic.Dictionary<String,OSTypeStructure> arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix)
```


Rangschikt structuren in één woordenboek op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| structures | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | De structuren |
| woordenboek | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Het woordenboek om te rangschikken |
| prefix | java.lang.String | Het voorvoegsel voor sleutelnamen. |

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Gesorteerde structuren als woordenboek op sleutelnaam.
### createColorDescriptor_internalized(Color value) {#createColorDescriptor-internalized-com.aspose.psd.Color-}
```
public static DescriptorStructure createColorDescriptor_internalized(Color value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### createColorDescriptor_internalized(Color value, String keyName) {#createColorDescriptor-internalized-com.aspose.psd.Color-java.lang.String-}
```
public static DescriptorStructure createColorDescriptor_internalized(Color value, String keyName)
```


Maakt de [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) met kleurwaarde met opgegeven sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | De kleurwaarde. |
| keyName | java.lang.String | De sleutelnaam. |

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getBoolValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static boolean getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Haalt de booleaanse waarde op uit de structurenlijst op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst om in te zoeken. |
| keyName | java.lang.String | De sleutelnaam om op te zoeken. |

**Returns:**
boolean - De booleaanse waarde uit de structurenlijst als deze bestaat, anders de standaardwaarde.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassID() {#getClassID--}
```
public final ClassID getClassID()
```


Haalt op of stelt de klasse‑ID in.

Waarde: Het class-ID.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName() {#getClassName--}
```
public final String getClassName()
```


Haalt de klassenaam op of stelt deze in.

Waarde: De klassenaam.

**Returns:**
java.lang.String
### getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getColorValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static Color getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Haalt de kleurwaarde op uit de structurenlijst op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst om in te zoeken. |
| keyName | java.lang.String | De sleutelnaam om op te zoeken. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color value from the structures list if it exists, otherwise the default value.
### getColorValue_internalized(List<OSTypeStructure> itemsList) {#getColorValue-internalized-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static Color getColorValue_internalized(List<OSTypeStructure> itemsList)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| itemsList | java.util.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

**Returns:**
[Color](../../com.aspose.psd/color)
### getCopy_internalized() {#getCopy-internalized--}
```
public final OSTypeStructure getCopy_internalized()
```


Maakt een volledige kopie van deze structuur.

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - Returns the full copy of this structure.
### getHeaderLength() {#getHeaderLength--}
```
public int getHeaderLength()
```


Haalt de headerlengte op.

**Returns:**
int - De headerlengte
### getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getInt32Value-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static int getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Haalt de int32‑waarde op uit de structurenlijst op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst om in te zoeken. |
| keyName | java.lang.String | De sleutelnaam om op te zoeken. |

**Returns:**
int - De int32-waarde uit de structurenlijst als deze bestaat, anders de standaardwaarde.
### getKey() {#getKey--}
```
public int getKey()
```


Haalt de structuur‑sleutel op.

**Returns:**
int
### getKeyName() {#getKeyName--}
```
public final ClassID getKeyName()
```


Haalt op of stelt de sleutelnaam in.

Waarde: de sleutelnaam.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getLength() {#getLength--}
```
public int getLength()
```


Haalt de [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) lengte in bytes op.

**Returns:**
int
### getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static System.Collections.Generic.List<OSTypeStructure> getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Haalt de lijst met structurenwaarde op uit een andere structurenlijst op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst om in te zoeken. |
| keyName | java.lang.String | De sleutelnaam om op te zoeken. |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - De lijst van structurenwaarde van de andere structurenlijst indien aanwezig, anders de standaardwaarde.
### getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getPointDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static PointF getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Haalt de PointF‑waarde op uit de structurenlijst op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst om in te zoeken. |
| keyName | java.lang.String | De sleutelnaam om op te zoeken. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The PointF value from the structures list if it exists, otherwise the default value.
### getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getRectDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static RectangleF getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Haalt de RectangleF‑waarde op uit de structurenlijst op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst om in te zoeken. |
| keyName | java.lang.String | De sleutelnaam om op te zoeken. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The RectangleF value from the structures list if it exists, otherwise the default value.
### getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getStringValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static String getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Haalt de tekenreekswaarde op uit de structurenlijst op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst om in te zoeken. |
| keyName | java.lang.String | De sleutelnaam om op te zoeken. |

**Returns:**
java.lang.String - De tekenreekswaarde van de structurenlijst indien aanwezig, anders de standaardwaarde.
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


Zoekt en verwijdert de structuur uit de invoer‑itemslijst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keyName | java.lang.String | De sleutelnaam. |
| items | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De items. |

### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Slaat de structuur op in de opgegeven streamcontainer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |

### saveWithoutKeyName(StreamContainer streamContainer) {#saveWithoutKeyName-com.aspose.psd.StreamContainer-}
```
public final void saveWithoutKeyName(StreamContainer streamContainer)
```


Slaat de structuur op in de opgegeven streamcontainer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |

### setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setBoolValue-internalized-boolean-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Stelt de booleaanse waarde in de structurenlijst in op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | De waarde die moet worden ingesteld. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst. |
| keyName | java.lang.String | De sleutelnaam. |

### setClassID(ClassID value) {#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassID(ClassID value)
```


Haalt op of stelt de klasse‑ID in.

Waarde: Het class-ID.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName(String value) {#setClassName-java.lang.String-}
```
public final void setClassName(String value)
```


Haalt de klassenaam op of stelt deze in.

Waarde: De klassenaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setColorValue-internalized-com.aspose.psd.Color-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Stelt de kleurwaarde in een structurenlijst in op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | De waarde die moet worden ingesteld. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst. |
| keyName | java.lang.String | De sleutelnaam. |

### setColorValue_internalized(Color value, List<OSTypeStructure> itemsList) {#setColorValue-internalized-com.aspose.psd.Color-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void setColorValue_internalized(Color value, List<OSTypeStructure> itemsList)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |
| itemsList | java.util.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

### setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setInt32Value-internalized-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Stelt de int32‑waarde in de structurenlijst in op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De waarde die moet worden ingesteld. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst. |
| keyName | java.lang.String | De sleutelnaam. |

### setKeyName(ClassID value) {#setKeyName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setKeyName(ClassID value)
```


Haalt op of stelt de sleutelnaam in.

Waarde: de sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Stelt de lijst met structurenwaarde in de andere structurenlijst in op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De waarde die moet worden ingesteld. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst. |
| keyName | java.lang.String | De sleutelnaam. |

### setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setPointDoubleValue-internalized-com.aspose.psd.PointF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Stelt de PointF‑waarde in de structurenlijst in op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | De waarde die moet worden ingesteld. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst. |
| keyName | java.lang.String | De sleutelnaam. |

### setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setRectDoubleValue-internalized-com.aspose.psd.RectangleF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Stelt de RectangleF‑waarde in de structurenlijst in op sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | De waarde die moet worden ingesteld. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst. |
| keyName | java.lang.String | De sleutelnaam. |

### setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setStringValue-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Stelt de tekenreekswaarde in voor de structurenlijst op basis van de sleutelnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | De waarde die moet worden ingesteld. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De structurenlijst. |
| keyName | java.lang.String | De sleutelnaam. |

### setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items) {#setToList-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items)
```


Voeg de structuur toe of werk deze bij in de invoeritemslijst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | De structuur om toe te voegen of bij te werken. |
| items | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | De items. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

