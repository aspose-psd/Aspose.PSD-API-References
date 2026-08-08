---
title: "PtFlResource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс PtFlResource."
type: docs
weight: 72
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.FillLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/filllayerresource)
```
public class PtFlResource extends FillLayerResource
```

Класс PtFlResource. Содержит данные слоя заполнения шаблоном.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PtFlResource()](#PtFlResource--) | Инициализирует новый экземпляр класса [PtFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource). |
| [PtFlResource(String patternName, String patternId)](#PtFlResource-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [PtFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource). |
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
| [getAlignWithLayer()](#getAlignWithLayer--) | Получает или задает значение, указывающее, [align with layer]. |
| [getAngle()](#getAngle--) | Получает или задает угол. |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Получает или задает заголовок. |
| [getKey()](#getKey--) | Получает ключ ресурса слоя. |
| [getLength()](#getLength--) | Получает длину ресурса слоя в байтах. |
| [getOffset()](#getOffset--) | Получает или задает смещение. |
| [getPatternId()](#getPatternId--) | Получает или задает идентификатор шаблона. |
| [getPatternName()](#getPatternName--) | Получает или задает имя шаблона. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Получает длину префикса. |
| [getPsdVersion()](#getPsdVersion--) | Получает минимальную версию PSD, требуемую для ресурса слоя. |
| [getScale()](#getScale--) | Получает или задает масштаб. |
| [getSignature()](#getSignature--) | Получает подпись ресурса слоя. |
| [hashCode()](#hashCode--) |  |
| [isLinkedWithLayer()](#isLinkedWithLayer--) | Получает или задает значение, указывающее, связан ли этот экземпляр со слоем. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Определяет, является ли ресурс специфичным для PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Получает значение, указывающее, является ли данный экземпляр ресурсом, специфичным для PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Сохраняет ресурс в указанный контейнер потока. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Сохраняет пользовательский заголовок ресурса. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Сохраняет подпись заголовка, идентификатор и длину. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Получает или задает значение, указывающее, [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Получает или задает угол. |
| [setClassNameAndId_internalized(String className, ClassID classID)](#setClassNameAndId-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Устанавливает имя класса и идентификатор. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Получает или задает заголовок. |
| [setLinkedWithLayer(boolean value)](#setLinkedWithLayer-boolean-) | Получает или задает значение, указывающее, связан ли этот экземпляр со слоем. |
| [setOffset(Point value)](#setOffset-com.aspose.psd.Point-) | Получает или задает смещение. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Получает или задает идентификатор шаблона. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | Получает или задает имя шаблона. |
| [setScale(double value)](#setScale-double-) | Получает или задает масштаб. |
| [toString()](#toString--) | Возвращает объект String, представляющий этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PtFlResource() {#PtFlResource--}
```
public PtFlResource()
```


Инициализирует новый экземпляр класса [PtFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource).

### PtFlResource(String patternName, String patternId) {#PtFlResource-java.lang.String-java.lang.String-}
```
public PtFlResource(String patternName, String patternId)
```


Инициализирует новый экземпляр класса [PtFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| patternName | java.lang.String | Имя шаблона. |
| patternId | java.lang.String | Идентификатор шаблона. |

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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Получает или задает значение, указывающее, [align with layer].

Значение:  true  если [align with layer]; иначе,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Получает или задает угол.

Значение: Угол.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Получает или задает заголовок.

Значение: Заголовок.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


Получает ключ ресурса слоя.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Получает длину ресурса слоя в байтах.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final Point getOffset()
```


Получает или задает смещение.

Значение: смещение.

**Returns:**
[Point](../../com.aspose.psd/point)
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Получает или задает идентификатор шаблона.

Значение: Идентификатор шаблона.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


Получает или задает имя шаблона.

Значение: Имя шаблона.

**Returns:**
java.lang.String
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
### getScale() {#getScale--}
```
public final double getScale()
```


Получает или задает масштаб.

Значение: Масштаб.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


Получает подпись ресурса слоя.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLinkedWithLayer() {#isLinkedWithLayer--}
```
public final boolean isLinkedWithLayer()
```


Получает или задает значение, указывающее, связан ли этот экземпляр со слоем.

Значение:  true  если этот экземпляр связан со слоем; иначе,  false .

**Returns:**
boolean
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

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Получает или задает значение, указывающее, [align with layer].

Значение:  true  если [align with layer]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Получает или задает угол.

Значение: Угол.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setClassNameAndId_internalized(String className, ClassID classID) {#setClassNameAndId-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassNameAndId_internalized(String className, ClassID classID)
```


Устанавливает имя класса и идентификатор.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| className | java.lang.String | Имя класса. |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Идентификатор класса. |

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

### setLinkedWithLayer(boolean value) {#setLinkedWithLayer-boolean-}
```
public final void setLinkedWithLayer(boolean value)
```


Получает или задает значение, указывающее, связан ли этот экземпляр со слоем.

Значение:  true  если этот экземпляр связан со слоем; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setOffset(Point value) {#setOffset-com.aspose.psd.Point-}
```
public final void setOffset(Point value)
```


Получает или задает смещение.

Значение: смещение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Получает или задает идентификатор шаблона.

Значение: Идентификатор шаблона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


Получает или задает имя шаблона.

Значение: Имя шаблона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Получает или задает масштаб.

Значение: Масштаб.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает объект String, представляющий этот экземпляр.

**Returns:**
java.lang.String — объект String, представляющий этот экземпляр.
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

