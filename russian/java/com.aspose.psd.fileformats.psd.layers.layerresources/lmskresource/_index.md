---
title: "LmskResource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Ресурс LMsk."
type: docs
weight: 50
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class LmskResource extends LayerResource
```

Ресурс LMsk.

--------------------

Этот ресурс содержит идентификатор цветового пространства (ID), который указывает на конкретный тип цветового пространства, и 4 цветовых компонента. В зависимости от ID, цветовые компоненты имеют разное значение. Если тип цветового пространства не требует четырёх значений, дополнительные компоненты неопределены и всегда записываются как нули. Цветовые компоненты по типам цветовых пространств: RGB — первые три компонента представляют красный, зелёный и синий. HSB — первые три компонента представляют оттенок, насыщенность и яркость. CMYK — четыре компонента представляют циан, магенту, жёлтый и чёрный. Lab — первые три компонента представляют светлость, a-хроминанс и b-хроминанс. Grayscale — первый компонент представляет значение серого от 0...10000.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LmskResource()](#LmskResource--) | Инициализирует новый экземпляр класса [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource). |
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
| [create_internalized(byte[] data)](#create-internalized-byte---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorComponent1()](#getColorComponent1--) | Получает цветовой компонент 1. |
| [getColorComponent2()](#getColorComponent2--) | Получает цветовой компонент 2. |
| [getColorComponent3()](#getColorComponent3--) | Получает цветовой компонент 3. |
| [getColorComponent4()](#getColorComponent4--) | Получает цветовой компонент 4. |
| [getColorSpace()](#getColorSpace--) | Получает цветовое пространство. |
| [getFlag()](#getFlag--) | Получает флаг. |
| [getHeader_internalized()](#getHeader-internalized--) | Получает или задает заголовок. |
| [getKey()](#getKey--) | Получает ключ ресурса слоя. |
| [getLength()](#getLength--) | Получает длину ресурса слоя в байтах. |
| [getOpacity()](#getOpacity--) | Получает непрозрачность. |
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
| [setColorComponent1(int value)](#setColorComponent1-int-) | Получает цветовой компонент 1. |
| [setColorComponent2(int value)](#setColorComponent2-int-) | Получает цветовой компонент 2. |
| [setColorComponent3(int value)](#setColorComponent3-int-) | Получает цветовой компонент 3. |
| [setColorComponent4(int value)](#setColorComponent4-int-) | Получает цветовой компонент 4. |
| [setColorSpace(int value)](#setColorSpace-int-) | Получает цветовое пространство. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Получает или задает заголовок. |
| [setOpacity(short value)](#setOpacity-short-) | Получает непрозрачность. |
| [toString()](#toString--) | Возвращает объект String, представляющий этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LmskResource() {#LmskResource--}
```
public LmskResource()
```


Инициализирует новый экземпляр класса [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource).

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

### create_internalized(byte[] data) {#create-internalized-byte---}
```
public static LmskResource create_internalized(byte[] data)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] |  |

**Returns:**
[LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorComponent1() {#getColorComponent1--}
```
public final int getColorComponent1()
```


Получает цветовой компонент 1.

Значение: Цветовой компонент 1.

**Returns:**
int
### getColorComponent2() {#getColorComponent2--}
```
public final int getColorComponent2()
```


Получает цветовой компонент 2.

Значение: Цветовой компонент 2.

**Returns:**
int
### getColorComponent3() {#getColorComponent3--}
```
public final int getColorComponent3()
```


Получает цветовой компонент 3.

Значение: Цветовой компонент 3.

**Returns:**
int
### getColorComponent4() {#getColorComponent4--}
```
public final int getColorComponent4()
```


Получает цветовой компонент 4.

Значение: Цветовой компонент 4.

**Returns:**
int
### getColorSpace() {#getColorSpace--}
```
public final int getColorSpace()
```


Получает цветовое пространство.

Значение: цветовое пространство.

**Returns:**
int
### getFlag() {#getFlag--}
```
public final byte getFlag()
```


Получает флаг.

Значение: Флаг.

**Returns:**
byte
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
### getOpacity() {#getOpacity--}
```
public final short getOpacity()
```


Получает непрозрачность.

Значение: непрозрачность.

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

### setColorComponent1(int value) {#setColorComponent1-int-}
```
public final void setColorComponent1(int value)
```


Получает цветовой компонент 1.

Значение: Цветовой компонент 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setColorComponent2(int value) {#setColorComponent2-int-}
```
public final void setColorComponent2(int value)
```


Получает цветовой компонент 2.

Значение: Цветовой компонент 2.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setColorComponent3(int value) {#setColorComponent3-int-}
```
public final void setColorComponent3(int value)
```


Получает цветовой компонент 3.

Значение: Цветовой компонент 3.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setColorComponent4(int value) {#setColorComponent4-int-}
```
public final void setColorComponent4(int value)
```


Получает цветовой компонент 4.

Значение: Цветовой компонент 4.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public final void setColorSpace(int value)
```


Получает цветовое пространство.

Значение: цветовое пространство.

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

### setOpacity(short value) {#setOpacity-short-}
```
public final void setOpacity(short value)
```


Получает непрозрачность.

Значение: непрозрачность.

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

