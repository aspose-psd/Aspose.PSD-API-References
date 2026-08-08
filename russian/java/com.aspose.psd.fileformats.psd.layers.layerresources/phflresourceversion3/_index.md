---
title: "PhflResourceVersion3"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс PhflResource."
type: docs
weight: 70
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.PhflResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresource)
```
public class PhflResourceVersion3 extends PhflResource
```

Класс PhflResource. Ресурс слоя коррекции экспозиции 2 версии ( = 3 ) или ( = 2 ) 12 4 байта каждый для цвета XYZ (только в версии 3) 10 2 байта цветовое пространство, за которым следует 4 \* 2 байта цветового компонента (только в версии 2) 4 Плотность 1 Сохранить яркость
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PhflResourceVersion3()](#PhflResourceVersion3--) | Инициализирует новый экземпляр класса [PhflResourceVersion3](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3). |
| [PhflResourceVersion3(byte[] data)](#PhflResourceVersion3-byte---) | Инициализирует новый экземпляр класса [PhflResourceVersion3](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3). |
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
| [getColorX()](#getColorX--) | Получает или задаёт цвет X. |
| [getColorY()](#getColorY--) | Получает или задаёт цвет Y. |
| [getColorZ()](#getColorZ--) | Получает или задаёт цвет Z. |
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
| [setColorX(float value)](#setColorX-float-) | Получает или задаёт цвет X. |
| [setColorY(float value)](#setColorY-float-) | Получает или задаёт цвет Y. |
| [setColorZ(float value)](#setColorZ-float-) | Получает или задаёт цвет Z. |
| [setDensity(int value)](#setDensity-int-) | Получает или задает плотность. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Получает или задает заголовок. |
| [setPreserveLuminosity(boolean value)](#setPreserveLuminosity-boolean-) | Получает или задает значение, указывающее, следует ли [preserve luminosity]. |
| [setRgbColor(Color color)](#setRgbColor-com.aspose.psd.Color-) | Устанавливает цвет RGB. |
| [setVersion(short value)](#setVersion-short-) | Получает версию. |
| [toString()](#toString--) | Возвращает объект String, представляющий этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhflResourceVersion3() {#PhflResourceVersion3--}
```
public PhflResourceVersion3()
```


Инициализирует новый экземпляр класса [PhflResourceVersion3](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3).

### PhflResourceVersion3(byte[] data) {#PhflResourceVersion3-byte---}
```
public PhflResourceVersion3(byte[] data)
```


Инициализирует новый экземпляр класса [PhflResourceVersion3](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3).

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
### getColorX() {#getColorX--}
```
public final float getColorX()
```


Получает или задаёт цвет X.

Значение: цвет X.

**Returns:**
float
### getColorY() {#getColorY--}
```
public final float getColorY()
```


Получает или задаёт цвет Y.

Значение: цвет Y.

**Returns:**
float
### getColorZ() {#getColorZ--}
```
public final float getColorZ()
```


Получает или задаёт цвет Z.

Значение: цвет Z.

**Returns:**
float
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


Получает версию. По умолчанию 2 или 3

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

### setColorX(float value) {#setColorX-float-}
```
public final void setColorX(float value)
```


Получает или задаёт цвет X.

Значение: цвет X.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setColorY(float value) {#setColorY-float-}
```
public final void setColorY(float value)
```


Получает или задаёт цвет Y.

Значение: цвет Y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setColorZ(float value) {#setColorZ-float-}
```
public final void setColorZ(float value)
```


Получает или задаёт цвет Z.

Значение: цвет Z.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

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


Получает версию. По умолчанию 2 или 3

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

