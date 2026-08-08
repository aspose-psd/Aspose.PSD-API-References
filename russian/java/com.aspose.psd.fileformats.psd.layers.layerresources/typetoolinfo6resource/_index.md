---
title: "TypeToolInfo6Resource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Информация о типе инструмента."
type: docs
weight: 78
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfo6Resource extends LayerResource
```

Информация о типе инструмента. Для версии PSD 6.0 и выше.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)](#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Инициализирует новый экземпляр класса [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource). |
## Поля

| Поле | Описание |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Версия заголовка PSB |
| [PsbResourceSignature](#PsbResourceSignature) | Подпись ресурса, специфичная для PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Версия заголовка PSD |
| [ResourceSignature](#ResourceSignature) | Общая подпись ресурса. |
| [TypeToolKey](#TypeToolKey) | Ключ информации о типе инструмента. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Лицензия предприятия. |
## Методы

| Метод | Описание |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Проверяет и устанавливает, является ли ресурс специфичным для PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Получает или задаёт положение снизу. |
| [getBoundingBox_internalized()](#getBoundingBox-internalized--) | Получает или задаёт границы текста в текстовом поле. |
| [getBounds_internalized()](#getBounds-internalized--) | Получает или задаёт границы текстового поля. |
| [getClass()](#getClass--) |  |
| [getClassID()](#getClassID--) | Получает или задает идентификатор класса. |
| [getClassName()](#getClassName--) | Получает или задает имя класса. |
| [getDescriptorVersion()](#getDescriptorVersion--) | Получает или задает версию дескриптора. |
| [getHeader_internalized()](#getHeader-internalized--) | Получает или задает заголовок. |
| [getItems()](#getItems--) | Получает или задает элементы. |
| [getKey()](#getKey--) | Получает ключ ресурса слоя. |
| [getLeft()](#getLeft--) | Получает или задаёт положение слева. |
| [getLength()](#getLength--) | Получает длину ресурса слоя в байтах. |
| [getParsedTyShModel_internalized()](#getParsedTyShModel-internalized--) | Разбирает необработанные данные в экземпляр класса TyShRoot. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Получает длину префикса. |
| [getPsdVersion()](#getPsdVersion--) | Получает минимальную версию PSD, требуемую для ресурса слоя. |
| [getRawDataStructure_internalized()](#getRawDataStructure-internalized--) | Получает элемент [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure), если он существует. |
| [getRight()](#getRight--) | Получает или задает правое положение. |
| [getSignature()](#getSignature--) | Получает подпись ресурса слоя. |
| [getTextIndex_internalized()](#getTextIndex-internalized--) | Получает индекс текста в этом ресурсе. |
| [getTextVersion()](#getTextVersion--) | Получает или задает версию текста. |
| [getTop()](#getTop--) | Получает или задает верхнее положение. |
| [getTransformMatrix()](#getTransformMatrix--) | Получает или задает матрицу преобразования. |
| [getVersion()](#getVersion--) | Получает или задает версию инструмента типизации. |
| [getWarpClassID()](#getWarpClassID--) | Получает или задает идентификатор класса. |
| [getWarpClassName()](#getWarpClassName--) | Получает или задает название класса искажения. |
| [getWarpDescriptorVersion()](#getWarpDescriptorVersion--) | Получает или задает версию дескриптора искажения. |
| [getWarpItems()](#getWarpItems--) | Получает или задает элементы искажения. |
| [getWarpVersion()](#getWarpVersion--) | Получает или задает версию искажения. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Определяет, является ли ресурс специфичным для PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Получает значение, указывающее, является ли данный экземпляр ресурсом, специфичным для PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Сохраняет ресурс в указанный контейнер потока. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Сохраняет пользовательский заголовок ресурса. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Сохраняет подпись заголовка, идентификатор и длину. |
| [setBottom(int value)](#setBottom-int-) | Получает или задаёт положение снизу. |
| [setBoundingBox_internalized(RectangleF value)](#setBoundingBox-internalized-com.aspose.psd.RectangleF-) | Получает или задаёт границы текста в текстовом поле. |
| [setClassID(ClassID value)](#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Получает или задает идентификатор класса. |
| [setClassName(String value)](#setClassName-java.lang.String-) | Получает или задает имя класса. |
| [setDescriptorVersion(int value)](#setDescriptorVersion-int-) | Получает или задает версию дескриптора. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Получает или задает заголовок. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Получает или задает элементы. |
| [setLeft(int value)](#setLeft-int-) | Получает или задаёт положение слева. |
| [setRight(int value)](#setRight-int-) | Получает или задает правое положение. |
| [setTextVersion(short value)](#setTextVersion-short-) | Получает или задает версию текста. |
| [setTop(int value)](#setTop-int-) | Получает или задает верхнее положение. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Получает или задает матрицу преобразования. |
| [setVersion(short value)](#setVersion-short-) | Получает или задает версию инструмента типизации. |
| [setWarpClassID(ClassID value)](#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Получает или задает идентификатор класса. |
| [setWarpClassName(String value)](#setWarpClassName-java.lang.String-) | Получает или задает название класса искажения. |
| [setWarpDescriptorVersion(int value)](#setWarpDescriptorVersion-int-) | Получает или задает версию дескриптора искажения. |
| [setWarpItems(OSTypeStructure[] value)](#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Получает или задает элементы искажения. |
| [setWarpVersion(short value)](#setWarpVersion-short-) | Получает или задает версию искажения. |
| [toString()](#toString--) | Возвращает объект String, представляющий этот экземпляр. |
| [updateFromTyShModel_internalized(TyShRoot dataModel)](#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-) | Сериализовать данные TyShRoot в необработанный вид. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfo6Resource(ClassID classID, ClassID warpClassID) {#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)
```


Инициализирует новый экземпляр класса [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Идентификатор класса. |
| warpClassID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Идентификатор класса warp. |

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


Версия заголовка PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Подпись ресурса, специфичная для PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


Версия заголовка PSD

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Общая подпись ресурса.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Ключ информации о типе инструмента.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Лицензия предприятия.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Проверяет и устанавливает, является ли ресурс специфичным для PSB. Некоторые ресурсы пока не распознаются, но у нас есть полный список ресурсов, специфичных для PSB, которые изменяют своё поведение при сохранении. Поэтому нам необходимо проверять это хотя бы в UnknownResource.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | int | Ключ. |

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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Получает или задаёт положение снизу.

Значение: Нижнее положение.

**Returns:**
int
### getBoundingBox_internalized() {#getBoundingBox-internalized--}
```
public final RectangleF getBoundingBox_internalized()
```


Получает или задаёт границы текста в текстовом поле.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds_internalized() {#getBounds-internalized--}
```
public final RectangleF getBounds_internalized()
```


Получает или задаёт границы текстового поля.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
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
### getDescriptorVersion() {#getDescriptorVersion--}
```
public final int getDescriptorVersion()
```


Получает или задает версию дескриптора.

Значение: версия дескриптора.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Получает или задает заголовок.

Значение: Заголовок.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


Получает или задает элементы.

Значение: элементы.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Получает ключ ресурса слоя.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Получает или задаёт положение слева.

Значение: Левое положение.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Получает длину ресурса слоя в байтах.

**Returns:**
int
### getParsedTyShModel_internalized() {#getParsedTyShModel-internalized--}
```
public final TyShRoot getParsedTyShModel_internalized()
```


Разбирает необработанные данные в экземпляр класса TyShRoot.

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot - Необработанные данные в виде экземпляра класса TyShRoot.
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Получает длину префикса. Значение по умолчанию — 12 для ресурсов 8BIM и 16 для 8B64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| psdVersion | int | Версия PSD. |

**Returns:**
int — длина префикса.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений.

**Returns:**
int
### getRawDataStructure_internalized() {#getRawDataStructure-internalized--}
```
public final RawDataStructure getRawDataStructure_internalized()
```


Получает элемент [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure), если он существует.

**Returns:**
[RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) - The raw data structure.
### getRight() {#getRight--}
```
public final int getRight()
```


Получает или задает правое положение.

Значение: Правое положение.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Получает подпись ресурса слоя.

**Returns:**
int
### getTextIndex_internalized() {#getTextIndex-internalized--}
```
public final int getTextIndex_internalized()
```


Получает индекс текста в этом ресурсе.

**Returns:**
int - Возвращает индекс текста в этом ресурсе.
### getTextVersion() {#getTextVersion--}
```
public final short getTextVersion()
```


Получает или задает версию текста.

Значение: Версия текста.

**Returns:**
short
### getTop() {#getTop--}
```
public final int getTop()
```


Получает или задает верхнее положение.

Значение: Верхнее положение.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Получает или задает матрицу преобразования.

Значение: Трансформационная матрица.

**Returns:**
double[]
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Получает или задает версию инструмента типизации.

Значение: Версия инструмента типизации.

**Returns:**
short
### getWarpClassID() {#getWarpClassID--}
```
public final ClassID getWarpClassID()
```


Получает или задает идентификатор класса.

Значение: Идентификатор класса.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName() {#getWarpClassName--}
```
public final String getWarpClassName()
```


Получает или задает название класса искажения.

Значение: Имя класса искажения.

**Returns:**
java.lang.String
### getWarpDescriptorVersion() {#getWarpDescriptorVersion--}
```
public final int getWarpDescriptorVersion()
```


Получает или задает версию дескриптора искажения.

Значение: Версия дескриптора искажения.

**Returns:**
int
### getWarpItems() {#getWarpItems--}
```
public final OSTypeStructure[] getWarpItems()
```


Получает или задает элементы искажения.

Значение: Элементы искажения.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion() {#getWarpVersion--}
```
public final short getWarpVersion()
```


Получает или задает версию искажения.

Значение: Версия искажения.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Определяет, является ли ресурс специфичным для PSB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | int | Ключ ресурса. |

**Returns:**
boolean —  true  если ресурс специфичен для PSB; иначе,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Получает значение, указывающее, является ли данный экземпляр ресурсом, специфичным для PSB.

Значение:  true  если этот экземпляр является ресурсом, специфичным для PSB; иначе,  false .

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
public void save(StreamContainer streamContainer, int psdVersion)
```


Сохраняет ресурс в указанный контейнер потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| psdVersion | int | Версия PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Сохраняет пользовательский заголовок ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |
| подпись | int | Подпись. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Сохраняет подпись заголовка, идентификатор и длину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |
| подпись | int | Подпись. |
| isLengthLong | boolean | если установлено значение  true , длина считается длинной. |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Получает или задаёт положение снизу.

Значение: Нижнее положение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setBoundingBox_internalized(RectangleF value) {#setBoundingBox-internalized-com.aspose.psd.RectangleF-}
```
public final void setBoundingBox_internalized(RectangleF value)
```


Получает или задаёт границы текста в текстовом поле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) |  |

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

### setDescriptorVersion(int value) {#setDescriptorVersion-int-}
```
public final void setDescriptorVersion(int value)
```


Получает или задает версию дескриптора.

Значение: версия дескриптора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Получает или задает заголовок.

Значение: Заголовок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


Получает или задает элементы.

Значение: элементы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Получает или задаёт положение слева.

Значение: Левое положение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Получает или задает правое положение.

Значение: Правое положение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTextVersion(short value) {#setTextVersion-short-}
```
public final void setTextVersion(short value)
```


Получает или задает версию текста.

Значение: Версия текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Получает или задает верхнее положение.

Значение: Верхнее положение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


Получает или задает матрицу преобразования.

Значение: Трансформационная матрица.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double[] |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Получает или задает версию инструмента типизации.

Значение: Версия инструмента типизации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setWarpClassID(ClassID value) {#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID(ClassID value)
```


Получает или задает идентификатор класса.

Значение: Идентификатор класса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName(String value) {#setWarpClassName-java.lang.String-}
```
public final void setWarpClassName(String value)
```


Получает или задает название класса искажения.

Значение: Имя класса искажения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setWarpDescriptorVersion(int value) {#setWarpDescriptorVersion-int-}
```
public final void setWarpDescriptorVersion(int value)
```


Получает или задает версию дескриптора искажения.

Значение: Версия дескриптора искажения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWarpItems(OSTypeStructure[] value) {#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setWarpItems(OSTypeStructure[] value)
```


Получает или задает элементы искажения.

Значение: Элементы искажения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setWarpVersion(short value) {#setWarpVersion-short-}
```
public final void setWarpVersion(short value)
```


Получает или задает версию искажения.

Значение: Версия искажения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает объект String, представляющий этот экземпляр.

**Returns:**
java.lang.String — объект String, представляющий этот экземпляр.
### updateFromTyShModel_internalized(TyShRoot dataModel) {#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-}
```
public final void updateFromTyShModel_internalized(TyShRoot dataModel)
```


Сериализовать данные TyShRoot в необработанный вид.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataModel | com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot |  |

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

