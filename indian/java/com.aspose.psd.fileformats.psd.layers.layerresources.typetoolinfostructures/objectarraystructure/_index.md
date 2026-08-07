---
title: "ObjectArrayStructure"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "ObjectArrayStructure क्लास को परिभाषित करता है जो आमतौर पर  एरे रखता है।"
type: docs
weight: 20
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
```
public final class ObjectArrayStructure extends OSTypeStructure
```

ObjectArrayStructure क्लास को परिभाषित करता है जो आमतौर पर [UnitArrayStructure](../../com.aspose.psd.fileformats/psd.layers.layerresources.typetoolinfostructures/unitarraystructure) एरे रखता है। यह PSD फ़ाइल संसाधनों में उपयोग किया जाता है, जैसे PlLd Resource और SoLd Resource।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [ObjectArrayStructure(String keyName, String classIdName, OSTypeStructure[] structures)](#ObjectArrayStructure-java.lang.String-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | एक नया उदाहरण प्रारंभ करता है [ObjectArrayStructure](../../com.aspose.psd.fileformats/psd.layers.layerresources.typetoolinfostructures/objectarraystructure) क्लास का। |
| [ObjectArrayStructure(int key, ClassID keyName, ClassID classID, String className, OSTypeStructure[] structures)](#ObjectArrayStructure-int-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | एक नया उदाहरण प्रारंभ करता है [ObjectArrayStructure](../../com.aspose.psd.fileformats/psd.layers.layerresources.typetoolinfostructures/objectarraystructure) क्लास का। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [StructureKey](#StructureKey) | ‘ObAr’ संरचना कुंजी की पहचान करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [<T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container)](#-T-findByKeyName-from-placed-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | कुंजी नाम मान द्वारा संरचना खोजता है। |
| [<T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items)](#-T-findByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | कुंजी नाम मान द्वारा संरचना खोजता है। |
| [arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix)](#arrangeToDictionary-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा संरचनाओं को एक शब्दकोश में व्यवस्थित करता है। |
| [createColorDescriptor_internalized(Color value)](#createColorDescriptor-internalized-com.aspose.psd.Color-) |  |
| [createColorDescriptor_internalized(Color value, String keyName)](#createColorDescriptor-internalized-com.aspose.psd.Color-java.lang.String-) | निर्दिष्ट कुंजी नाम के साथ रंग मान के साथ [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getBoolValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा संरचनाओं की सूची से बूलियन मान प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getClassID()](#getClassID--) | ऑब्जेक्ट एरे क्लास ID को प्राप्त करता है या सेट करता है। |
| [getClassName()](#getClassName--) | ऑब्जेक्ट एरे क्लास नाम को प्राप्त करता है या सेट करता है। |
| [getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getColorValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा संरचनाओं की सूची से रंग मान प्राप्त करता है। |
| [getColorValue_internalized(List<OSTypeStructure> itemsList)](#getColorValue-internalized-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) |  |
| [getCopy_internalized()](#getCopy-internalized--) | इस संरचना की पूरी प्रति बनाता है। |
| [getHeaderLength()](#getHeaderLength--) | हेडर की लंबाई प्राप्त करता है। |
| [getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getInt32Value-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा संरचनाओं की सूची से int32 मान प्राप्त करता है। |
| [getItemsList_internalized()](#getItemsList-internalized--) | स्ट्रक्चर की सूची प्राप्त करता है। |
| [getKey()](#getKey--) | ऑब्जेक्ट एरे स्ट्रक्चर कुंजी को प्राप्त करता है। |
| [getKeyName()](#getKeyName--) | कुंजी नाम प्राप्त करता है या सेट करता है। |
| [getLength()](#getLength--) | OSTypeStructure की लंबाई बाइट्स में प्राप्त करता है। |
| [getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा अन्य संरचनाओं की सूची से संरचनाओं के मान की सूची प्राप्त करता है। |
| [getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getPointDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा संरचनाओं की सूची से PointF मान प्राप्त करता है। |
| [getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getRectDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा संरचनाओं की सूची से RectangleF मान प्राप्त करता है। |
| [getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getStringValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा संरचनाओं की सूची से स्ट्रिंग मान प्राप्त करता है। |
| [getStructureCount()](#getStructureCount--) | ऑब्जेक्ट एरे सबस्ट्रक्चर गिनती को प्राप्त करता है। |
| [getStructures()](#getStructures--) | ऑब्जेक्ट एरे स्ट्रक्चर में सबस्ट्रक्चर को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeByKeyName_internalized(String keyName, System.Collections.Generic.List<OSTypeStructure> items)](#removeByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | इनपुट आइटम सूची से संरचना खोजता और हटाता है। |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना सहेजता है। |
| [saveWithoutKeyName(StreamContainer streamContainer)](#saveWithoutKeyName-com.aspose.psd.StreamContainer-) | निर्दिष्ट स्ट्रीम कंटेनर में संरचना सहेजता है। |
| [setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setBoolValue-internalized-boolean-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा संरचनाओं की सूची में बूलियन मान सेट करता है। |
| [setClassID(ClassID value)](#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | ऑब्जेक्ट एरे क्लास ID को प्राप्त करता है या सेट करता है। |
| [setClassName(String value)](#setClassName-java.lang.String-) | ऑब्जेक्ट एरे क्लास नाम को प्राप्त करता है या सेट करता है। |
| [setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setColorValue-internalized-com.aspose.psd.Color-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा संरचना सूची में रंग मान सेट करता है। |
| [setColorValue_internalized(Color value, List<OSTypeStructure> itemsList)](#setColorValue-internalized-com.aspose.psd.Color-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) |  |
| [setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setInt32Value-internalized-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा संरचनाओं की सूची में int32 मान सेट करता है। |
| [setKeyName(ClassID value)](#setKeyName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | कुंजी नाम प्राप्त करता है या सेट करता है। |
| [setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा अन्य संरचनाओं की सूची में संरचनाओं के मान की सूची सेट करता है। |
| [setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setPointDoubleValue-internalized-com.aspose.psd.PointF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा संरचनाओं की सूची में PointF मान सेट करता है। |
| [setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setRectDoubleValue-internalized-com.aspose.psd.RectangleF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा संरचनाओं की सूची में RectangleF मान सेट करता है। |
| [setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setStringValue-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | कुंजी नाम द्वारा स्ट्रक्चर सूची में स्ट्रिंग मान सेट करता है। |
| [setStructures(OSTypeStructure[] value)](#setStructures-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | ऑब्जेक्ट एरे स्ट्रक्चर में सबस्ट्रक्चर को प्राप्त करता है या सेट करता है। |
| [setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items)](#setToList-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | इनपुट आइटम सूची में स्ट्रक्चर जोड़ें या अपडेट करें। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ObjectArrayStructure(String keyName, String classIdName, OSTypeStructure[] structures) {#ObjectArrayStructure-java.lang.String-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public ObjectArrayStructure(String keyName, String classIdName, OSTypeStructure[] structures)
```


एक नया उदाहरण प्रारंभ करता है [ObjectArrayStructure](../../com.aspose.psd.fileformats/psd.layers.layerresources.typetoolinfostructures/objectarraystructure) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keyName | java.lang.String | कुंजी का नाम। |
| classIdName | java.lang.String | क्लास पहचानकर्ता का नाम। |
| structures | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | स्ट्रक्चर। |

### ObjectArrayStructure(int key, ClassID keyName, ClassID classID, String className, OSTypeStructure[] structures) {#ObjectArrayStructure-int-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public ObjectArrayStructure(int key, ClassID keyName, ClassID classID, String className, OSTypeStructure[] structures)
```


एक नया उदाहरण प्रारंभ करता है [ObjectArrayStructure](../../com.aspose.psd.fileformats/psd.layers.layerresources.typetoolinfostructures/objectarraystructure) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | int | इंटीजर कुंजी। |
| keyName | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | कुंजी नाम। |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | क्लास पहचानकर्ता। |
| className | java.lang.String | क्लास का नाम। |
| structures | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | स्ट्रक्चर। |

### StructureKey {#StructureKey}
```
public static final int StructureKey
```


‘ObAr’ संरचना कुंजी की पहचान करता है।

### <T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container) {#-T-findByKeyName-from-placed-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public static T <T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container)
```


कुंजी नाम मान द्वारा संरचना खोजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keyName | java.lang.String | कुंजी नाम। |
|  | container | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | खोज के लिए आइटम कंटेनर। |

T : परिणाम ऑब्जेक्ट का प्रकार। |

**Returns:**
T - कुंजी नाम मान द्वारा स्ट्रक्चर।
### <T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items) {#-T-findByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static T <T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items)
```


कुंजी नाम मान द्वारा संरचना खोजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keyName | java.lang.String | कुंजी नाम। |
|  | आइटम्स | com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | खोज के लिए आइटम्स। |

T : परिणाम ऑब्जेक्ट का प्रकार। |

**Returns:**
T - कुंजी नाम मान द्वारा स्ट्रक्चर।
### arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix) {#arrangeToDictionary-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static System.Collections.Generic.Dictionary<String,OSTypeStructure> arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix)
```


कुंजी नाम द्वारा संरचनाओं को एक शब्दकोश में व्यवस्थित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| structures | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | स्ट्रक्चर। |
| डिक्शनरी | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | व्यवस्थित करने के लिए डिक्शनरी। |
| उपसर्ग | java.lang.String | कुंजी नामों के लिए उपसर्ग। |

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - कुंजी नाम द्वारा डिक्शनरी के रूप में व्यवस्थित स्ट्रक्चर।
### createColorDescriptor_internalized(Color value) {#createColorDescriptor-internalized-com.aspose.psd.Color-}
```
public static DescriptorStructure createColorDescriptor_internalized(Color value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### createColorDescriptor_internalized(Color value, String keyName) {#createColorDescriptor-internalized-com.aspose.psd.Color-java.lang.String-}
```
public static DescriptorStructure createColorDescriptor_internalized(Color value, String keyName)
```


निर्दिष्ट कुंजी नाम के साथ रंग मान के साथ [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | रंग मान। |
| keyName | java.lang.String | कुंजी नाम। |

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getBoolValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static boolean getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा संरचनाओं की सूची से बूलियन मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | खोज के लिए स्ट्रक्चर सूची। |
| keyName | java.lang.String | खोज के लिए कुंजी नाम। |

**Returns:**
boolean - यदि मौजूद हो तो स्ट्रक्चर सूची से बूलियन मान, अन्यथा डिफ़ॉल्ट मान।
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


ऑब्जेक्ट एरे क्लास ID को प्राप्त करता है या सेट करता है।

मान: ऑब्जेक्ट एरे क्लास ID।

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName() {#getClassName--}
```
public final String getClassName()
```


ऑब्जेक्ट एरे क्लास नाम को प्राप्त करता है या सेट करता है।

मान: ऑब्जेक्ट एरे क्लास नाम।

**Returns:**
java.lang.String
### getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getColorValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static Color getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा संरचनाओं की सूची से रंग मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | खोज के लिए स्ट्रक्चर सूची। |
| keyName | java.lang.String | खोज के लिए कुंजी नाम। |

**Returns:**
[Color](../../com.aspose.psd/color) - The color value from the structures list if it exists, otherwise the default value.
### getColorValue_internalized(List<OSTypeStructure> itemsList) {#getColorValue-internalized-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static Color getColorValue_internalized(List<OSTypeStructure> itemsList)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| itemsList | java.util.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

**Returns:**
[Color](../../com.aspose.psd/color)
### getCopy_internalized() {#getCopy-internalized--}
```
public final OSTypeStructure getCopy_internalized()
```


इस संरचना की पूरी प्रति बनाता है।

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - Returns the full copy of this structure.
### getHeaderLength() {#getHeaderLength--}
```
public int getHeaderLength()
```


हेडर की लंबाई प्राप्त करता है।

**Returns:**
int - हेडर की लंबाई
### getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getInt32Value-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static int getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा संरचनाओं की सूची से int32 मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | खोज के लिए स्ट्रक्चर सूची। |
| keyName | java.lang.String | खोज के लिए कुंजी नाम। |

**Returns:**
int - यदि मौजूद हो तो स्ट्रक्चर सूची से int32 मान, अन्यथा डिफ़ॉल्ट मान।
### getItemsList_internalized() {#getItemsList-internalized--}
```
public final System.Collections.Generic.List<OSTypeStructure> getItemsList_internalized()
```


स्ट्रक्चर की सूची प्राप्त करता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure>
### getKey() {#getKey--}
```
public int getKey()
```


ऑब्जेक्ट एरे स्ट्रक्चर कुंजी को प्राप्त करता है।

**Returns:**
int
### getKeyName() {#getKeyName--}
```
public final ClassID getKeyName()
```


कुंजी नाम प्राप्त करता है या सेट करता है।

मान: कुंजी नाम.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getLength() {#getLength--}
```
public int getLength()
```


OSTypeStructure की लंबाई बाइट्स में प्राप्त करता है।

**Returns:**
int
### getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static System.Collections.Generic.List<OSTypeStructure> getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा अन्य संरचनाओं की सूची से संरचनाओं के मान की सूची प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | खोज के लिए स्ट्रक्चर सूची। |
| keyName | java.lang.String | खोज के लिए कुंजी नाम। |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - यदि मौजूद हो तो अन्य संरचनाओं की सूची से संरचनाओं के मान की सूची, अन्यथा डिफ़ॉल्ट मान।
### getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getPointDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static PointF getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा संरचनाओं की सूची से PointF मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | खोज के लिए स्ट्रक्चर सूची। |
| keyName | java.lang.String | खोज के लिए कुंजी नाम। |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The PointF value from the structures list if it exists, otherwise the default value.
### getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getRectDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static RectangleF getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा संरचनाओं की सूची से RectangleF मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | खोज के लिए स्ट्रक्चर सूची। |
| keyName | java.lang.String | खोज के लिए कुंजी नाम। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The RectangleF value from the structures list if it exists, otherwise the default value.
### getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getStringValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static String getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा संरचनाओं की सूची से स्ट्रिंग मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | खोज के लिए स्ट्रक्चर सूची। |
| keyName | java.lang.String | खोज के लिए कुंजी नाम। |

**Returns:**
java.lang.String - यदि मौजूद हो तो संरचनाओं की सूची से स्ट्रिंग मान, अन्यथा डिफ़ॉल्ट मान।
### getStructureCount() {#getStructureCount--}
```
public final int getStructureCount()
```


ऑब्जेक्ट एरे सबस्ट्रक्चर गिनती को प्राप्त करता है।

मान: ऑब्जेक्ट एरे स्ट्रक्चर में सबस्ट्रक्चर गिनती।

**Returns:**
int
### getStructures() {#getStructures--}
```
public final OSTypeStructure[] getStructures()
```


ऑब्जेक्ट एरे स्ट्रक्चर में सबस्ट्रक्चर को प्राप्त करता है या सेट करता है।

मान: ऑब्जेक्ट एरे स्ट्रक्चर में सबस्ट्रक्चर।

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
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


इनपुट आइटम सूची से संरचना खोजता और हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keyName | java.lang.String | कुंजी नाम। |
| आइटम्स | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | आइटम्स। |

### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


निर्दिष्ट स्ट्रीम कंटेनर में संरचना सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |

### saveWithoutKeyName(StreamContainer streamContainer) {#saveWithoutKeyName-com.aspose.psd.StreamContainer-}
```
public final void saveWithoutKeyName(StreamContainer streamContainer)
```


निर्दिष्ट स्ट्रीम कंटेनर में संरचना सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |

### setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setBoolValue-internalized-boolean-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा संरचनाओं की सूची में बूलियन मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | सेट किया जाने वाला मान। |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | संरचनाओं की सूची। |
| keyName | java.lang.String | कुंजी नाम। |

### setClassID(ClassID value) {#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassID(ClassID value)
```


ऑब्जेक्ट एरे क्लास ID को प्राप्त करता है या सेट करता है।

मान: ऑब्जेक्ट एरे क्लास ID।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName(String value) {#setClassName-java.lang.String-}
```
public final void setClassName(String value)
```


ऑब्जेक्ट एरे क्लास नाम को प्राप्त करता है या सेट करता है।

मान: ऑब्जेक्ट एरे क्लास नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setColorValue-internalized-com.aspose.psd.Color-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा संरचना सूची में रंग मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | सेट किया जाने वाला मान। |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | संरचनाओं की सूची। |
| keyName | java.lang.String | कुंजी नाम। |

### setColorValue_internalized(Color value, List<OSTypeStructure> itemsList) {#setColorValue-internalized-com.aspose.psd.Color-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void setColorValue_internalized(Color value, List<OSTypeStructure> itemsList)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |
| itemsList | java.util.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

### setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setInt32Value-internalized-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा संरचनाओं की सूची में int32 मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | सेट किया जाने वाला मान। |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | संरचनाओं की सूची। |
| keyName | java.lang.String | कुंजी नाम। |

### setKeyName(ClassID value) {#setKeyName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setKeyName(ClassID value)
```


कुंजी नाम प्राप्त करता है या सेट करता है।

मान: कुंजी नाम.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा अन्य संरचनाओं की सूची में संरचनाओं के मान की सूची सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | सेट किया जाने वाला मान। |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | संरचनाओं की सूची। |
| keyName | java.lang.String | कुंजी नाम। |

### setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setPointDoubleValue-internalized-com.aspose.psd.PointF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा संरचनाओं की सूची में PointF मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | सेट किया जाने वाला मान। |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | संरचनाओं की सूची। |
| keyName | java.lang.String | कुंजी नाम। |

### setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setRectDoubleValue-internalized-com.aspose.psd.RectangleF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा संरचनाओं की सूची में RectangleF मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | सेट किया जाने वाला मान। |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | संरचनाओं की सूची। |
| keyName | java.lang.String | कुंजी नाम। |

### setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setStringValue-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


कुंजी नाम द्वारा स्ट्रक्चर सूची में स्ट्रिंग मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | सेट किया जाने वाला मान। |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | संरचनाओं की सूची। |
| keyName | java.lang.String | कुंजी नाम। |

### setStructures(OSTypeStructure[] value) {#setStructures-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setStructures(OSTypeStructure[] value)
```


ऑब्जेक्ट एरे स्ट्रक्चर में सबस्ट्रक्चर को प्राप्त करता है या सेट करता है।

मान: ऑब्जेक्ट एरे स्ट्रक्चर में सबस्ट्रक्चर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items) {#setToList-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items)
```


इनपुट आइटम सूची में स्ट्रक्चर जोड़ें या अपडेट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | जोड़ने या अपडेट करने के लिए संरचना। |
| आइटम्स | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | आइटम्स। |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

