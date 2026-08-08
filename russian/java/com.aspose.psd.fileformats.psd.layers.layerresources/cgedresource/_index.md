---
title: "CgEdResource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс CgEdResource."
type: docs
weight: 18
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class CgEdResource extends AdjustmentLayerResource
```

Класс CgEdResource. Дополнительные данные генератора контента (Photoshop CS5)
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CgEdResource()](#CgEdResource--) | Инициализирует новый экземпляр класса [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource). |
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
| [getAuto()](#getAuto--) | Получает или задаёт значение, указывающее, является ли этот [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) автоматическим. |
| [getBrightness()](#getBrightness--) | Получает или задает яркость. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Получает или задаёт контраст. |
| [getData()](#getData--) | Получает или задает данные. |
| [getHeader_internalized()](#getHeader-internalized--) | Получает или задает заголовок. |
| [getKey()](#getKey--) | Получает ключ ресурса слоя. |
| [getLabColor()](#getLabColor--) | Получает или задаёт значение, указывающее, используется ли [lab color]. |
| [getLength()](#getLength--) | Получает длину ресурса слоя в байтах. |
| [getMeanValueForBrightnessAndContrast()](#getMeanValueForBrightnessAndContrast--) | Получает или задаёт среднее значение яркости и контраста. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Получает длину префикса. |
| [getPropertyValueByTypeStructure_internalized(String structureName)](#getPropertyValueByTypeStructure-internalized-java.lang.String-) | Получает значение свойства по типу структуры. |
| [getPsdVersion()](#getPsdVersion--) | Получает минимальную версию PSD, требуемую для ресурса слоя. |
| [getSignature()](#getSignature--) | Получает подпись ресурса слоя. |
| [getUseLegacy()](#getUseLegacy--) | Получает или задаёт значение, указывающее, использовать ли [use legacy]. |
| [getVersion()](#getVersion--) | Получает или задает версию. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Определяет, является ли ресурс специфичным для PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Получает значение, указывающее, является ли данный экземпляр ресурсом, специфичным для PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Сохраняет ресурс в указанный контейнер потока. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Сохраняет пользовательский заголовок ресурса. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Сохраняет подпись заголовка, идентификатор и длину. |
| [setAuto(boolean value)](#setAuto-boolean-) | Получает или задаёт значение, указывающее, является ли этот [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) автоматическим. |
| [setBrightness(int value)](#setBrightness-int-) | Получает или задает яркость. |
| [setContrast(int value)](#setContrast-int-) | Получает или задаёт контраст. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Получает или задает заголовок. |
| [setLabColor(boolean value)](#setLabColor-boolean-) | Получает или задаёт значение, указывающее, используется ли [lab color]. |
| [setMeanValueForBrightnessAndContrast(int value)](#setMeanValueForBrightnessAndContrast-int-) | Получает или задаёт среднее значение яркости и контраста. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Устанавливает значение свойства по типовой структуре. |
| [setUseLegacy(boolean value)](#setUseLegacy-boolean-) | Получает или задаёт значение, указывающее, использовать ли [use legacy]. |
| [setVersion(int value)](#setVersion-int-) | Получает или задает версию. |
| [toString()](#toString--) | Возвращает объект String, представляющий этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CgEdResource() {#CgEdResource--}
```
public CgEdResource()
```


Инициализирует новый экземпляр класса [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource). Спецификация формата PSD содержит следующее описание: 4 Descriptor Version( = 16) Variable Length Descriptor of extra data. Рекомендация: может не использоваться в старых версиях PS (до CS5).

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
### getAuto() {#getAuto--}
```
public final boolean getAuto()
```


Получает или задаёт значение, указывающее, является ли этот [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) автоматическим.

Значение:  true  если автоматический; иначе  false .

**Returns:**
boolean
### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Получает или задает яркость.

Значение: яркость.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public final int getContrast()
```


Получает или задаёт контраст.

Значение: контраст.

**Returns:**
int
### getData() {#getData--}
```
public final byte[] getData()
```


Получает или задает данные.

Значение: Данные.

**Returns:**
byte[]
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
### getLabColor() {#getLabColor--}
```
public final boolean getLabColor()
```


Получает или задаёт значение, указывающее, используется ли [lab color].

Значение:  true  если используется [lab color]; иначе,  false .

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


Получает длину ресурса слоя в байтах.

**Returns:**
int
### getMeanValueForBrightnessAndContrast() {#getMeanValueForBrightnessAndContrast--}
```
public final int getMeanValueForBrightnessAndContrast()
```


Получает или задаёт среднее значение яркости и контраста.

Значение: Среднее значение яркости и контраста.

**Returns:**
int
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
### getPropertyValueByTypeStructure_internalized(String structureName) {#getPropertyValueByTypeStructure-internalized-java.lang.String-}
```
public final Object getPropertyValueByTypeStructure_internalized(String structureName)
```


Получает значение свойства по типу структуры. Используется только для UnitTests.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| structureName | java.lang.String | Имя структуры. |

**Returns:**
java.lang.Object - структура OSType для простого unit-testing
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Получает подпись ресурса слоя.

**Returns:**
int
### getUseLegacy() {#getUseLegacy--}
```
public final boolean getUseLegacy()
```


Получает или задаёт значение, указывающее, использовать ли [use legacy].

Значение:  true  если [use legacy]; иначе,  false .

**Returns:**
boolean
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Получает или задает версию.

Значение: Версия.

**Returns:**
int
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

### setAuto(boolean value) {#setAuto-boolean-}
```
public final void setAuto(boolean value)
```


Получает или задаёт значение, указывающее, является ли этот [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) автоматическим.

Значение:  true  если автоматический; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Получает или задает яркость.

Значение: яркость.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Получает или задаёт контраст.

Значение: контраст.

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

### setLabColor(boolean value) {#setLabColor-boolean-}
```
public final void setLabColor(boolean value)
```


Получает или задаёт значение, указывающее, используется ли [lab color].

Значение:  true  если используется [lab color]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setMeanValueForBrightnessAndContrast(int value) {#setMeanValueForBrightnessAndContrast-int-}
```
public final void setMeanValueForBrightnessAndContrast(int value)
```


Получает или задаёт среднее значение яркости и контраста.

Значение: Среднее значение яркости и контраста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Устанавливает значение свойства по типовой структуре.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Структура. |

### setUseLegacy(boolean value) {#setUseLegacy-boolean-}
```
public final void setUseLegacy(boolean value)
```


Получает или задаёт значение, указывающее, использовать ли [use legacy].

Значение:  true  если [use legacy]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Получает или задает версию.

Значение: Версия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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

