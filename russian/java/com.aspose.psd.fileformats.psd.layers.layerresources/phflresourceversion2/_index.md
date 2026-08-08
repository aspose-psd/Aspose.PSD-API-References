---
title: "PhflResourceVersion2"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс PhflResource."
type: docs
weight: 69
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.PhflResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresource)
```
public class PhflResourceVersion2 extends PhflResource
```

Класс PhflResource. Ресурс слоя коррекции экспозиции 2 версии ( = 3 ) или ( = 2 ) 12 4 байта каждый для цвета XYZ (только в версии 3) 10 2 байта цветовое пространство, за которым следует 4 \* 2 байта цветового компонента (только в версии 2) 4 Плотность 1 Сохранить яркость
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PhflResourceVersion2()](#PhflResourceVersion2--) | Инициализирует новый экземпляр класса [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2). |
| [PhflResourceVersion2(byte[] data)](#PhflResourceVersion2-byte---) | Инициализирует новый экземпляр класса [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2). |
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
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Получает цветовое пространство. |
| [getComponentA()](#getComponentA--) | Получает или задает компонент A цвета |
| [getComponentB()](#getComponentB--) | Получает или задает компонент B |
| [getComponentL()](#getComponentL--) | Получает или задает компонент L цвета |
| [getData()](#getData--) | Получает или задает данные. |
| [getDensity()](#getDensity--) | Получает или задает плотность. |
| [getHeader_internalized()](#getHeader-internalized--) | Получает или задает заголовок. |
| [getKey()](#getKey--) | Получает ключ ресурса слоя. |
| [getLength()](#getLength--) | Получает длину ресурса слоя в байтах. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Получает длину префикса. |
| [getPreserveLuminosity()](#getPreserveLuminosity--) | Получает или задает значение, указывающее, следует ли [preserve luminosity]. |
| [getPsdVersion()](#getPsdVersion--) | Получает минимальную версию PSD, требуемую для ресурса слоя. |
| [getRgbColor()](#getRgbColor--) | Получает цвет. |
| [getSignature()](#getSignature--) | Получает подпись ресурса слоя. |
| [getVersion()](#getVersion--) | Получает версию. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Определяет, является ли ресурс специфичным для PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Получает значение, указывающее, является ли данный экземпляр ресурсом, специфичным для PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Сохраняет ресурс в указанный контейнер потока. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Сохраняет пользовательский заголовок ресурса. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Сохраняет подпись заголовка, идентификатор и длину. |
| [setColorSpace(short value)](#setColorSpace-short-) | Получает цветовое пространство. |
| [setComponentA(short value)](#setComponentA-short-) | Получает или задает компонент A цвета |
| [setComponentB(short value)](#setComponentB-short-) | Получает или задает компонент B |
| [setComponentL(short value)](#setComponentL-short-) | Получает или задает компонент L цвета |
| [setDensity(int value)](#setDensity-int-) | Получает или задает плотность. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Получает или задает заголовок. |
| [setPreserveLuminosity(boolean value)](#setPreserveLuminosity-boolean-) | Получает или задает значение, указывающее, следует ли [preserve luminosity]. |
| [setRgbColor(Color color)](#setRgbColor-com.aspose.psd.Color-) | Устанавливает цвет RGB. |
| [setVersion(short value)](#setVersion-short-) | Получает версию. |
| [toString()](#toString--) | Возвращает объект String, представляющий этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhflResourceVersion2() {#PhflResourceVersion2--}
```
public PhflResourceVersion2()
```


Инициализирует новый экземпляр класса [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2).

### PhflResourceVersion2(byte[] data) {#PhflResourceVersion2-byte---}
```
public PhflResourceVersion2(byte[] data)
```


Инициализирует новый экземпляр класса [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные ресурса. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorSpace() {#getColorSpace--}
```
public final short getColorSpace()
```


Получает цветовое пространство.

Значение: цветовое пространство.

**Returns:**
short
### getComponentA() {#getComponentA--}
```
public final short getComponentA()
```


Получает или задает компонент A цвета

**Returns:**
short
### getComponentB() {#getComponentB--}
```
public final short getComponentB()
```


Получает или задает компонент B

**Returns:**
short
### getComponentL() {#getComponentL--}
```
public final short getComponentL()
```


Получает или задает компонент L цвета

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
### getDensity() {#getDensity--}
```
public final int getDensity()
```


Получает или задает плотность.

Значение: Плотность.

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
### getPreserveLuminosity() {#getPreserveLuminosity--}
```
public final boolean getPreserveLuminosity()
```


Получает или задает значение, указывающее, следует ли [preserve luminosity].

Значение:  true  если [preserve luminosity]; иначе,  false .

**Returns:**
boolean
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений.

**Returns:**
int
### getRgbColor() {#getRgbColor--}
```
public Color getRgbColor()
```


Получает цвет.

**Returns:**
[Color](../../com.aspose.psd/color) - The RGB color
### getSignature() {#getSignature--}
```
public int getSignature()
```


Получает подпись ресурса слоя.

**Returns:**
int
### getVersion() {#getVersion--}
```
public short getVersion()
```


Получает версию.

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

### setColorSpace(short value) {#setColorSpace-short-}
```
public void setColorSpace(short value)
```


Получает цветовое пространство.

Значение: цветовое пространство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setComponentA(short value) {#setComponentA-short-}
```
public final void setComponentA(short value)
```


Получает или задает компонент A цвета

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setComponentB(short value) {#setComponentB-short-}
```
public final void setComponentB(short value)
```


Получает или задает компонент B

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setComponentL(short value) {#setComponentL-short-}
```
public final void setComponentL(short value)
```


Получает или задает компонент L цвета

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setDensity(int value) {#setDensity-int-}
```
public final void setDensity(int value)
```


Получает или задает плотность.

Значение: Плотность.

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

### setPreserveLuminosity(boolean value) {#setPreserveLuminosity-boolean-}
```
public final void setPreserveLuminosity(boolean value)
```


Получает или задает значение, указывающее, следует ли [preserve luminosity].

Значение:  true  если [preserve luminosity]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setRgbColor(Color color) {#setRgbColor-com.aspose.psd.Color-}
```
public void setRgbColor(Color color)
```


Устанавливает цвет RGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Цвет. |

### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Получает версию.

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

