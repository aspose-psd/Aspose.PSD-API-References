---
title: "BritResource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс BritResource."
type: docs
weight: 17
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BritResource extends AdjustmentLayerResource
```

Класс BritResource. Ресурс слоя регулировки яркости/контраста.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BritResource()](#BritResource--) | Инициализирует новый экземпляр класса [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource). |
| [BritResource(short brightness, short contrast, short meanValueForBrightnessAndContrast, boolean labColor)](#BritResource-short-short-short-boolean-) | Инициализирует новый экземпляр класса [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource). |
| [BritResource(byte[] bytes)](#BritResource-byte---) | Инициализирует новый экземпляр класса [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource). |
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
| [getBrightness()](#getBrightness--) | Получает или задает яркость. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Получает или задаёт контраст. |
| [getData()](#getData--) | Получает или задает данные. |
| [getHeader_internalized()](#getHeader-internalized--) | Получает или задает заголовок. |
| [getKey()](#getKey--) | Получает ключ ресурса слоя. |
| [getLabColor()](#getLabColor--) | Получает или задает значение, указывающее, является ли [lab color]. |
| [getLength()](#getLength--) | Получает длину ресурса слоя в байтах. |
| [getMeanValueForBrightnessAndContrast()](#getMeanValueForBrightnessAndContrast--) | Получает или задаёт среднее значение яркости и контраста. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Получает длину префикса. |
| [getPsdVersion()](#getPsdVersion--) | Получает минимальную версию PSD, требуемую для ресурса слоя. |
| [getSignature()](#getSignature--) | Получает подпись ресурса слоя. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Определяет, является ли ресурс специфичным для PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Получает значение, указывающее, является ли данный экземпляр ресурсом, специфичным для PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Сохраняет ресурс в указанный контейнер потока. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Сохраняет пользовательский заголовок ресурса. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Сохраняет подпись заголовка, идентификатор и длину. |
| [setBrightness(short value)](#setBrightness-short-) | Получает или задает яркость. |
| [setContrast(short value)](#setContrast-short-) | Получает или задаёт контраст. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Получает или задает заголовок. |
| [setLabColor(boolean value)](#setLabColor-boolean-) | Получает или задает значение, указывающее, является ли [lab color]. |
| [setMeanValueForBrightnessAndContrast(short value)](#setMeanValueForBrightnessAndContrast-short-) | Получает или задаёт среднее значение яркости и контраста. |
| [toString()](#toString--) | Возвращает объект String, представляющий этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BritResource() {#BritResource--}
```
public BritResource()
```


Инициализирует новый экземпляр класса [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource).

### BritResource(short brightness, short contrast, short meanValueForBrightnessAndContrast, boolean labColor) {#BritResource-short-short-short-boolean-}
```
public BritResource(short brightness, short contrast, short meanValueForBrightnessAndContrast, boolean labColor)
```


Инициализирует новый экземпляр класса [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | short | Яркость. |
| contrast | short | Контраст. |
| meanValueForBrightnessAndContrast | short | Среднее значение яркости и контраста. |
| labColor | boolean | если установлено значение true [lab color]. |

### BritResource(byte[] bytes) {#BritResource-byte---}
```
public BritResource(byte[] bytes)
```


Инициализирует новый экземпляр класса [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource). Спецификация формата PSD содержит следующее описание: 2 Яркость 2 Контраст 2 Среднее значение яркости и контраста 1 Только цвет Lab. Не используется в современных PSD (CS5 и выше), где используется CgEd. CgEd хранит свойства информации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | byte[] | Байты. |

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
### getBrightness() {#getBrightness--}
```
public final short getBrightness()
```


Получает или задает яркость.

Значение: яркость.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public final short getContrast()
```


Получает или задаёт контраст.

Значение: контраст.

**Returns:**
short
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


Получает или задает значение, указывающее, является ли [lab color].

Значение: true если [lab color]; иначе false.

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
public final short getMeanValueForBrightnessAndContrast()
```


Получает или задаёт среднее значение яркости и контраста.

Значение: Среднее значение яркости и контраста.

**Returns:**
short
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

### setBrightness(short value) {#setBrightness-short-}
```
public final void setBrightness(short value)
```


Получает или задает яркость.

Значение: яркость.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setContrast(short value) {#setContrast-short-}
```
public final void setContrast(short value)
```


Получает или задаёт контраст.

Значение: контраст.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

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


Получает или задает значение, указывающее, является ли [lab color].

Значение: true если [lab color]; иначе false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setMeanValueForBrightnessAndContrast(short value) {#setMeanValueForBrightnessAndContrast-short-}
```
public final void setMeanValueForBrightnessAndContrast(short value)
```


Получает или задаёт среднее значение яркости и контраста.

Значение: Среднее значение яркости и контраста.

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

