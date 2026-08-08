---
title: "EnumeratedReferenceStructure"
second_title: "Aspose.PSD for Java API Справочник"
description: "Структура enumerated reference."
type: docs
weight: 16
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure), [com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.EnumeratedDescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumerateddescriptorstructure)
```
public final class EnumeratedReferenceStructure extends EnumeratedDescriptorStructure
```

Структура enumerated reference.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EnumeratedReferenceStructure(ClassID keyName, ClassID classID, ClassID typeID, ClassID enumName)](#EnumeratedReferenceStructure-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Инициализирует новый экземпляр класса [EnumeratedReferenceStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure). |
## Поля

| Поле | Описание |
| --- | --- |
| [EnumeratedStructureKey](#EnumeratedStructureKey) | Определяет ключ структуры. |
| [StructureKey](#StructureKey) | Ключ перечисленного дескриптора. |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container)](#-T-findByKeyName-from-placed-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Находит структуру по значению имени ключа. |
| [<T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items)](#-T-findByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Находит структуру по значению имени ключа. |
| [arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix)](#arrangeToDictionary-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Организует структуры в один словарь по имени ключа. |
| [createColorDescriptor_internalized(Color value)](#createColorDescriptor-internalized-com.aspose.psd.Color-) |  |
| [createColorDescriptor_internalized(Color value, String keyName)](#createColorDescriptor-internalized-com.aspose.psd.Color-java.lang.String-) | Создаёт [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) со значением цвета и указанным именем ключа. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getBoolValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Получает логическое значение из списка структур по имени ключа. |
| [getClass()](#getClass--) |  |
| [getClassID()](#getClassID--) | Получает или задает идентификатор класса. |
| [getClassName()](#getClassName--) | Получает или задает имя класса. |
| [getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getColorValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Получает значение цвета из списка структур по имени ключа. |
| [getColorValue_internalized(List<OSTypeStructure> itemsList)](#getColorValue-internalized-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) |  |
| [getCopy_internalized()](#getCopy-internalized--) | Создаёт полную копию этой структуры. |
| [getEnumName()](#getEnumName--) | Получает или задает имя перечисления. |
| [getHeaderLength()](#getHeaderLength--) | Получает длину заголовка. |
| [getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getInt32Value-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Получает значение int32 из списка структур по имени ключа. |
| [getKey()](#getKey--) | Получает ключ. |
| [getKeyName()](#getKeyName--) | Получает или задаёт имя ключа. |
| [getLength()](#getLength--) | Получает длину [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) в байтах. |
| [getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Получает список значений структур из другого списка структур по имени ключа. |
| [getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getPointDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Получает значение PointF из списка структур по имени ключа. |
| [getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getRectDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Получает значение RectangleF из списка структур по имени ключа. |
| [getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#getStringValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Получает строковое значение из списка структур по имени ключа. |
| [getTypeID()](#getTypeID--) | Получает или задает идентификатор типа. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeByKeyName_internalized(String keyName, System.Collections.Generic.List<OSTypeStructure> items)](#removeByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Находит и удаляет структуру из входного списка элементов. |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Сохраняет структуру в указанный потоковый контейнер. |
| [saveWithoutKeyName(StreamContainer streamContainer)](#saveWithoutKeyName-com.aspose.psd.StreamContainer-) | Сохраняет структуру в указанный потоковый контейнер. |
| [setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setBoolValue-internalized-boolean-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Устанавливает логическое значение в список структур по имени ключа. |
| [setClassID(ClassID value)](#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Получает или задает идентификатор класса. |
| [setClassName(String value)](#setClassName-java.lang.String-) | Получает или задает имя класса. |
| [setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setColorValue-internalized-com.aspose.psd.Color-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Устанавливает значение цвета в список структур по имени ключа. |
| [setColorValue_internalized(Color value, List<OSTypeStructure> itemsList)](#setColorValue-internalized-com.aspose.psd.Color-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) |  |
| [setEnumName(ClassID value)](#setEnumName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Получает или задает имя перечисления. |
| [setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setInt32Value-internalized-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Устанавливает значение int32 в список структур по имени ключа. |
| [setKeyName(ClassID value)](#setKeyName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Получает или задаёт имя ключа. |
| [setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Устанавливает список значений структур в другой список структур по имени ключа. |
| [setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setPointDoubleValue-internalized-com.aspose.psd.PointF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Устанавливает значение PointF в список структур по имени ключа. |
| [setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setRectDoubleValue-internalized-com.aspose.psd.RectangleF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Устанавливает значение RectangleF в список структур по имени ключа. |
| [setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)](#setStringValue-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Устанавливает строковое значение в список структур по имени ключа. |
| [setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items)](#setToList-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Добавить или обновить структуру в список входных элементов. |
| [setTypeID(ClassID value)](#setTypeID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Получает или задает идентификатор типа. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EnumeratedReferenceStructure(ClassID keyName, ClassID classID, ClassID typeID, ClassID enumName) {#EnumeratedReferenceStructure-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public EnumeratedReferenceStructure(ClassID keyName, ClassID classID, ClassID typeID, ClassID enumName)
```


Инициализирует новый экземпляр класса [EnumeratedReferenceStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| keyName | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Имя ключа. |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Идентификатор класса. |
| typeID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Идентификатор типа. |
| enumName | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Имя перечисления. |

### EnumeratedStructureKey {#EnumeratedStructureKey}
```
public static final int EnumeratedStructureKey
```


Определяет ключ структуры.

### StructureKey {#StructureKey}
```
public static final int StructureKey
```


Ключ перечисленного дескриптора.

### <T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container) {#-T-findByKeyName-from-placed-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public static T <T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container)
```


Находит структуру по значению имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| keyName | java.lang.String | Имя ключа. |
|  | container | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Контейнер элементов для поиска. |

T : Тип результирующего объекта. |

**Returns:**
T - Структура по значению имени ключа.
### <T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items) {#-T-findByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static T <T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items)
```


Находит структуру по значению имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| keyName | java.lang.String | Имя ключа. |
|  | items | com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Элементы для поиска. |

T : Тип результирующего объекта. |

**Returns:**
T - Структура по значению имени ключа.
### arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix) {#arrangeToDictionary-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static System.Collections.Generic.Dictionary<String,OSTypeStructure> arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix)
```


Организует структуры в один словарь по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| structures | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Структуры |
| словарь | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Словарь для упорядочения |
| префикс | java.lang.String | Префикс для имён ключей. |

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Упорядоченные структуры в виде словаря по имени ключа.
### createColorDescriptor_internalized(Color value) {#createColorDescriptor-internalized-com.aspose.psd.Color-}
```
public static DescriptorStructure createColorDescriptor_internalized(Color value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### createColorDescriptor_internalized(Color value, String keyName) {#createColorDescriptor-internalized-com.aspose.psd.Color-java.lang.String-}
```
public static DescriptorStructure createColorDescriptor_internalized(Color value, String keyName)
```


Создаёт [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) со значением цвета и указанным именем ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Значение цвета. |
| keyName | java.lang.String | Имя ключа. |

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getBoolValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static boolean getBoolValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Получает логическое значение из списка структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур для поиска. |
| keyName | java.lang.String | Имя ключа для поиска. |

**Returns:**
boolean - Булевое значение из списка структур, если оно существует, иначе значение по умолчанию.
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


Получает или задает идентификатор класса.

Значение: Идентификатор класса.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName() {#getClassName--}
```
public final String getClassName()
```


Получает или задает имя класса.

Value: Имя класса.

**Returns:**
java.lang.String
### getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getColorValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static Color getColorValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Получает значение цвета из списка структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур для поиска. |
| keyName | java.lang.String | Имя ключа для поиска. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color value from the structures list if it exists, otherwise the default value.
### getColorValue_internalized(List<OSTypeStructure> itemsList) {#getColorValue-internalized-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static Color getColorValue_internalized(List<OSTypeStructure> itemsList)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| itemsList | java.util.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

**Returns:**
[Color](../../com.aspose.psd/color)
### getCopy_internalized() {#getCopy-internalized--}
```
public final OSTypeStructure getCopy_internalized()
```


Создаёт полную копию этой структуры.

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - Returns the full copy of this structure.
### getEnumName() {#getEnumName--}
```
public final ClassID getEnumName()
```


Получает или задает имя перечисления.

Значение: Имя перечисления.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getHeaderLength() {#getHeaderLength--}
```
public int getHeaderLength()
```


Получает длину заголовка.

**Returns:**
int - Длина заголовка
### getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getInt32Value-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static int getInt32Value_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Получает значение int32 из списка структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур для поиска. |
| keyName | java.lang.String | Имя ключа для поиска. |

**Returns:**
int - Значение int32 из списка структур, если оно существует, иначе значение по умолчанию.
### getKey() {#getKey--}
```
public int getKey()
```


Получает ключ.

**Returns:**
int
### getKeyName() {#getKeyName--}
```
public final ClassID getKeyName()
```


Получает или задаёт имя ключа.

Значение: имя ключа.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getLength() {#getLength--}
```
public int getLength()
```


Получает длину [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) в байтах.

**Returns:**
int
### getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static System.Collections.Generic.List<OSTypeStructure> getListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Получает список значений структур из другого списка структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур для поиска. |
| keyName | java.lang.String | Имя ключа для поиска. |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Список значений структур из другого списка структур, если он существует, иначе значение по умолчанию.
### getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getPointDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static PointF getPointDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Получает значение PointF из списка структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур для поиска. |
| keyName | java.lang.String | Имя ключа для поиска. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The PointF value from the structures list if it exists, otherwise the default value.
### getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getRectDoubleValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static RectangleF getRectDoubleValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Получает значение RectangleF из списка структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур для поиска. |
| keyName | java.lang.String | Имя ключа для поиска. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The RectangleF value from the structures list if it exists, otherwise the default value.
### getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#getStringValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static String getStringValue_internalized(System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Получает строковое значение из списка структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур для поиска. |
| keyName | java.lang.String | Имя ключа для поиска. |

**Returns:**
java.lang.String - Строковое значение из списка структур, если оно существует, иначе значение по умолчанию.
### getTypeID() {#getTypeID--}
```
public final ClassID getTypeID()
```


Получает или задает идентификатор типа.

Значение: Идентификатор типа.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
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


Находит и удаляет структуру из входного списка элементов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| keyName | java.lang.String | Имя ключа. |
| items | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Элементы. |

### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Сохраняет структуру в указанный потоковый контейнер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |

### saveWithoutKeyName(StreamContainer streamContainer) {#saveWithoutKeyName-com.aspose.psd.StreamContainer-}
```
public final void saveWithoutKeyName(StreamContainer streamContainer)
```


Сохраняет структуру в указанный потоковый контейнер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |

### setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setBoolValue-internalized-boolean-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setBoolValue_internalized(boolean value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Устанавливает логическое значение в список структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Значение, которое будет установлено. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур. |
| keyName | java.lang.String | Имя ключа. |

### setClassID(ClassID value) {#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassID(ClassID value)
```


Получает или задает идентификатор класса.

Значение: Идентификатор класса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName(String value) {#setClassName-java.lang.String-}
```
public final void setClassName(String value)
```


Получает или задает имя класса.

Value: Имя класса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setColorValue-internalized-com.aspose.psd.Color-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setColorValue_internalized(Color value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Устанавливает значение цвета в список структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Значение, которое будет установлено. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур. |
| keyName | java.lang.String | Имя ключа. |

### setColorValue_internalized(Color value, List<OSTypeStructure> itemsList) {#setColorValue-internalized-com.aspose.psd.Color-java.util.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void setColorValue_internalized(Color value, List<OSTypeStructure> itemsList)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |
| itemsList | java.util.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

### setEnumName(ClassID value) {#setEnumName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setEnumName(ClassID value)
```


Получает или задает имя перечисления.

Значение: Имя перечисления.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setInt32Value-internalized-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setInt32Value_internalized(int value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Устанавливает значение int32 в список структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Значение, которое будет установлено. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур. |
| keyName | java.lang.String | Имя ключа. |

### setKeyName(ClassID value) {#setKeyName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setKeyName(ClassID value)
```


Получает или задаёт имя ключа.

Значение: имя ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setListOfStructuresValue-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setListOfStructuresValue_internalized(System.Collections.Generic.List<OSTypeStructure> value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Устанавливает список значений структур в другой список структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Значение, которое будет установлено. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур. |
| keyName | java.lang.String | Имя ключа. |

### setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setPointDoubleValue-internalized-com.aspose.psd.PointF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setPointDoubleValue_internalized(PointF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Устанавливает значение PointF в список структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Значение, которое будет установлено. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур. |
| keyName | java.lang.String | Имя ключа. |

### setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setRectDoubleValue-internalized-com.aspose.psd.RectangleF-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setRectDoubleValue_internalized(RectangleF value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Устанавливает значение RectangleF в список структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Значение, которое будет установлено. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур. |
| keyName | java.lang.String | Имя ключа. |

### setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName) {#setStringValue-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static void setStringValue_internalized(String value, System.Collections.Generic.List<OSTypeStructure> itemsList, String keyName)
```


Устанавливает строковое значение в список структур по имени ключа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Значение, которое будет установлено. |
| itemsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Список структур. |
| keyName | java.lang.String | Имя ключа. |

### setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items) {#setToList-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items)
```


Добавить или обновить структуру в список входных элементов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Структура для добавления или обновления. |
| items | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | Элементы. |

### setTypeID(ClassID value) {#setTypeID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setTypeID(ClassID value)
```


Получает или задает идентификатор типа.

Значение: Идентификатор типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

