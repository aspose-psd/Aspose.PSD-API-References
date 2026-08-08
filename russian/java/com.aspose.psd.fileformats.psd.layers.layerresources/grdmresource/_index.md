---
title: "GrdmResource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс GrdmResource."
type: docs
weight: 35
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class GrdmResource extends AdjustmentLayerResource
```

Класс GrdmResource. Содержит информацию о слое Gradient-Map.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GrdmResource()](#GrdmResource--) |  |
| [GrdmResource(int psdVersion)](#GrdmResource-int-) | Инициализирует новый экземпляр класса [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource). |
## Поля

| Поле | Описание |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | Масштаб по умолчанию. |
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
| [getColorModel()](#getColorModel--) | Цветовая модель. |
| [getColorPoints()](#getColorPoints--) | Получает или задаёт точки цвета. |
| [getData()](#getData--) | Получает или задает данные. |
| [getDither()](#getDither--) | Градиент дезерирован. |
| [getExpansionCount()](#getExpansionCount--) | Количество расширений ( = 2 для Photoshop 6.0). |
| [getGradientLength_internalized()](#getGradientLength-internalized--) | Length(= 32 for Photoshop 6.0) Нет информации о том, за что отвечает. |
| [getGradientMode()](#getGradientMode--) | Режим для этого градиента определяет 'Gradient Type' = 'Solid/Noise' (0/1). |
| [getGradientName()](#getGradientName--) | Имя градиента: строка Unicode, дополнена. |
| [getHeader_internalized()](#getHeader-internalized--) | Получает или задает заголовок. |
| [getInterpolation()](#getInterpolation--) | Интерполяция. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Получает или задает метод интерполяции для градиента. |
| [getKey()](#getKey--) | Получает ключ ресурса слоя. |
| [getLength()](#getLength--) | Получает длину ресурса слоя в байтах. |
| [getMaximumColor()](#getMaximumColor--) | Максимальный цвет формата PixelDataFormat.Rgba64Bpp. |
| [getMinimumColor()](#getMinimumColor--) | Минимальный цвет формата PixelDataFormat.Rgba64Bpp. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Получает длину префикса. |
| [getPsdVersion()](#getPsdVersion--) | Получает минимальную версию PSD, необходимую для этого ресурса. |
| [getReverse()](#getReverse--) | Градиент инвертирован. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Случайное число‑засев, используемое для генерации цветов шумового градиента. |
| [getRoughness()](#getRoughness--) | Коэффициент шероховатости. Когда 'Gradient type' = 'Noise', можно задать 'Roughness' (0 - 2048). |
| [getShowTransparency()](#getShowTransparency--) | Флаг отображения прозрачности. Когда 'Gradient type' = 'Noise', можно установить 'Add transparency' в true. |
| [getSignature()](#getSignature--) | Получает подпись ресурса слоя. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Получает или задаёт точки прозрачности. |
| [getUseVectorColor()](#getUseVectorColor--) | Флаг использования векторного цвета. |
| [hashCode()](#hashCode--) |  |
| [initGradientLength_internalized(short value)](#initGradientLength-internalized-short-) | Инициализирует длину градиента. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Определяет, является ли ресурс специфичным для PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Получает значение, указывающее, является ли данный экземпляр ресурсом, специфичным для PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Сохраняет данные ресурса в указанный контейнер потока. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Сохраняет пользовательский заголовок ресурса. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Сохраняет подпись заголовка, идентификатор и длину. |
| [setColorModel(short value)](#setColorModel-short-) | Цветовая модель. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Получает или задаёт точки цвета. |
| [setDither(boolean value)](#setDither-boolean-) | Градиент дезерирован. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Количество расширений ( = 2 для Photoshop 6.0). |
| [setGradientMode(int value)](#setGradientMode-int-) | Режим для этого градиента определяет 'Gradient Type' = 'Solid/Noise' (0/1). |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Имя градиента: строка Unicode, дополнена. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Получает или задает заголовок. |
| [setInterpolation(short value)](#setInterpolation-short-) | Интерполяция. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Получает или задает метод интерполяции для градиента. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Максимальный цвет формата PixelDataFormat.Rgba64Bpp. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Минимальный цвет формата PixelDataFormat.Rgba64Bpp. |
| [setReverse(boolean value)](#setReverse-boolean-) | Градиент инвертирован. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Случайное число‑засев, используемое для генерации цветов шумового градиента. |
| [setRoughness(int value)](#setRoughness-int-) | Коэффициент шероховатости. Когда 'Gradient type' = 'Noise', можно задать 'Roughness' (0 - 2048). |
| [setShowTransparency(short value)](#setShowTransparency-short-) | Флаг отображения прозрачности. Когда 'Gradient type' = 'Noise', можно установить 'Add transparency' в true. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Получает или задаёт точки прозрачности. |
| [setUseVectorColor(short value)](#setUseVectorColor-short-) | Флаг использования векторного цвета. |
| [toString()](#toString--) | Возвращает объект String, представляющий этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GrdmResource() {#GrdmResource--}
```
public GrdmResource()
```


### GrdmResource(int psdVersion) {#GrdmResource-int-}
```
public GrdmResource(int psdVersion)
```


Инициализирует новый экземпляр класса [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| psdVersion | int | Версия PSD ресурса. |

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


Масштаб по умолчанию.

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Цветовая модель. Когда 'Gradient type' = 'Noise', можно задать 'Color Model' как RGB/SHB/LAB (3/4/6).

**Returns:**
short
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Получает или задаёт точки цвета.

Значение: точки цвета.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getData() {#getData--}
```
public final byte[] getData()
```


Получает или задает данные.

Значение: Данные.

**Returns:**
byte[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


Градиент дезерирован.

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Количество расширений ( = 2 для Photoshop 6.0).

**Returns:**
short
### getGradientLength_internalized() {#getGradientLength-internalized--}
```
public final short getGradientLength_internalized()
```


Length(= 32 for Photoshop 6.0) Нет информации о том, за что отвечает.

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Режим для этого градиента определяет 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Имя градиента: строка Unicode, дополнена.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Получает или задает заголовок.

Значение: Заголовок.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Интерполяция. Определяет плавность, когда 'Gradient Type' = 'Solid' (GradientMode = 0).

**Returns:**
short
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Получает или задает метод интерполяции для градиента.

**Returns:**
long
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Максимальный цвет формата PixelDataFormat.Rgba64Bpp. Цвет имеет каналы ARGB, каждый канал 16 бит.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Минимальный цвет формата PixelDataFormat.Rgba64Bpp. Цвет имеет каналы ARGB, каждый канал 16 бит.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
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


Получает минимальную версию PSD, необходимую для этого ресурса. Версия 3 требуется, когда метод интерполяции хранится явно.

**Returns:**
int
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Градиент инвертирован.

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Случайное число‑засев, используемое для генерации цветов шумового градиента.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Коэффициент шероховатости. Когда 'Gradient type' = 'Noise', можно задать 'Roughness' (0 - 2048).

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final short getShowTransparency()
```


Флаг отображения прозрачности. Когда 'Gradient type' = 'Noise', можно установить 'Add transparency' в true.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Получает подпись ресурса слоя.

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Получает или задаёт точки прозрачности.

Значение: точки прозрачности.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final short getUseVectorColor()
```


Флаг использования векторного цвета.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initGradientLength_internalized(short value) {#initGradientLength-internalized-short-}
```
public final void initGradientLength_internalized(short value)
```


Инициализирует длину градиента. GradientLength только для чтения, поэтому его можно задать лишь один раз.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short | Значение. |

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


Сохраняет данные ресурса в указанный контейнер потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |
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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Цветовая модель. Когда 'Gradient type' = 'Noise', можно задать 'Color Model' как RGB/SHB/LAB (3/4/6).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Получает или задаёт точки цвета.

Значение: точки цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Градиент дезерирован.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Количество расширений ( = 2 для Photoshop 6.0).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setGradientMode(int value) {#setGradientMode-int-}
```
public final void setGradientMode(int value)
```


Режим для этого градиента определяет 'Gradient Type' = 'Solid/Noise' (0/1).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Имя градиента: строка Unicode, дополнена.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

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

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Интерполяция. Определяет плавность, когда 'Gradient Type' = 'Solid' (GradientMode = 0).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Получает или задает метод интерполяции для градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Максимальный цвет формата PixelDataFormat.Rgba64Bpp. Цвет имеет каналы ARGB, каждый канал 16 бит.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Минимальный цвет формата PixelDataFormat.Rgba64Bpp. Цвет имеет каналы ARGB, каждый канал 16 бит.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Градиент инвертирован.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Случайное число‑засев, используемое для генерации цветов шумового градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Коэффициент шероховатости. Когда 'Gradient type' = 'Noise', можно задать 'Roughness' (0 - 2048).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShowTransparency(short value) {#setShowTransparency-short-}
```
public final void setShowTransparency(short value)
```


Флаг отображения прозрачности. Когда 'Gradient type' = 'Noise', можно установить 'Add transparency' в true.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Получает или задаёт точки прозрачности.

Значение: точки прозрачности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(short value) {#setUseVectorColor-short-}
```
public final void setUseVectorColor(short value)
```


Флаг использования векторного цвета.

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

