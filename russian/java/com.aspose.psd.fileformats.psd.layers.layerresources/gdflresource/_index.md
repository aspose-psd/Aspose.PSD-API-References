---
title: "GdFlResource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс GdFlResource."
type: docs
weight: 33
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.FillLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/filllayerresource)
```
public class GdFlResource extends FillLayerResource
```

Класс GdFlResource. Этот ресурс содержит информацию о смешивании обрезанного элемента.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GdFlResource()](#GdFlResource--) | Инициализирует новый экземпляр класса [.GdFlResource](../../null/\\#GdFlResource). |
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
| [addUnknownStructure_internalized(OSTypeStructure structure)](#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Добавляет неизвестную структуру. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Проверяет и устанавливает, является ли ресурс специфичным для PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateDefaultControlPoints_internalized()](#generateDefaultControlPoints-internalized--) | Генерирует контрольные точки по умолчанию. |
| [generateDefaultTransparencyPoints_internalized()](#generateDefaultTransparencyPoints-internalized--) | Генерирует точки прозрачности по умолчанию. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Получает или задает значение, указывающее, [align with layer]. |
| [getAngle()](#getAngle--) | Получает или задает угол. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Получает цвет RGB. |
| [getColorModel()](#getColorModel--) | Цветовая модель - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| [getColorPoints()](#getColorPoints--) | Получает цветовые точки. |
| [getDither()](#getDither--) | Получает или задает значение, указывающее, используется ли дизеринг для этого [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource). |
| [getGradientInterval()](#getGradientInterval--) | Получает или задает интервал градиента. |
| [getGradientMode()](#getGradientMode--) | Режим для этого градиента. |
| [getGradientName()](#getGradientName--) | Получает или задаёт имя градиента. |
| [getGradientType()](#getGradientType--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Получает или задает заголовок. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Получает или задает горизонтальное смещение. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Получает или задает метод интерполяции для градиента. |
| [getKey()](#getKey--) | Получает ключ ресурса слоя. |
| [getLength()](#getLength--) | Получает длину ресурса слоя в байтах. |
| [getMaximumColor()](#getMaximumColor--) | Максимальный цвет PixelDataFormat. |
| [getMinimumColor()](#getMinimumColor--) | Минимальный цвет PixelDataFormat. |
| [getOffset_internalized()](#getOffset-internalized--) | Получает или задает смещение. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Получает длину префикса. |
| [getPsdVersion()](#getPsdVersion--) | Получает минимальную версию PSD, требуемую для ресурса слоя. |
| [getReverse()](#getReverse--) | Получает или задает значение, указывающее, является ли этот [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) обратным. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Случайное число‑засев, используемое для генерации цветов шумового градиента. |
| [getRoughness()](#getRoughness--) | Коэффициент шероховатости. |
| [getScale()](#getScale--) | Получает или задает масштаб. |
| [getShowTransparency()](#getShowTransparency--) | Флаг отображения прозрачности. |
| [getSignature()](#getSignature--) | Получает подпись ресурса слоя. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Получает точки прозрачности. |
| [getUseVectorColor()](#getUseVectorColor--) | Флаг использования векторного цвета. |
| [getVerticalOffset()](#getVerticalOffset--) | Получает или задает вертикальное смещение. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Определяет, является ли ресурс специфичным для PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Получает значение, указывающее, является ли данный экземпляр ресурсом, специфичным для PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Сохраняет ресурс в указанный контейнер потока. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Сохраняет пользовательский заголовок ресурса. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Сохраняет подпись заголовка, идентификатор и длину. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Получает или задает значение, указывающее, [align with layer]. |
| [setAngle(double value)](#setAngle-double-) |  |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Получает цвет RGB. |
| [setColorModel(String value)](#setColorModel-java.lang.String-) | Цветовая модель - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Получает цветовые точки. |
| [setDither(boolean value)](#setDither-boolean-) | Получает или задает значение, указывающее, используется ли дизеринг для этого [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource). |
| [setGradientInterval(double value)](#setGradientInterval-double-) | Получает или задает интервал градиента. |
| [setGradientMode(String value)](#setGradientMode-java.lang.String-) | Режим для этого градиента. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Получает или задаёт имя градиента. |
| [setGradientType(int value)](#setGradientType-int-) |  |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Получает или задает заголовок. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) |  |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Получает или задает метод интерполяции для градиента. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Максимальный цвет PixelDataFormat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Минимальный цвет PixelDataFormat. |
| [setOffset_internalized(OffsetEntity value)](#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Получает или задает смещение. |
| [setReverse(boolean value)](#setReverse-boolean-) | Получает или задает значение, указывающее, является ли этот [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) обратным. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Случайное число‑засев, используемое для генерации цветов шумового градиента. |
| [setRoughness(int value)](#setRoughness-int-) | Коэффициент шероховатости. |
| [setScale(double value)](#setScale-double-) | Получает или задает масштаб. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Флаг отображения прозрачности. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Получает точки прозрачности. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Флаг использования векторного цвета. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) |  |
| [toString()](#toString--) | Возвращает объект String, представляющий этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GdFlResource() {#GdFlResource--}
```
public GdFlResource()
```


Инициализирует новый экземпляр класса [.GdFlResource](../../null/\\#GdFlResource).

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

### addUnknownStructure_internalized(OSTypeStructure structure) {#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public void addUnknownStructure_internalized(OSTypeStructure structure)
```


Добавляет неизвестную структуру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Структура. |

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
### generateDefaultControlPoints_internalized() {#generateDefaultControlPoints-internalized--}
```
public static IGradientColorPoint[] generateDefaultControlPoints_internalized()
```


Генерирует контрольные точки по умолчанию.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[] - Контрольные точки по умолчанию.
### generateDefaultTransparencyPoints_internalized() {#generateDefaultTransparencyPoints-internalized--}
```
public static IGradientTransparencyPoint[] generateDefaultTransparencyPoints_internalized()
```


Генерирует точки прозрачности по умолчанию.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[] - Точки прозрачности по умолчанию.
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
public double getAngle()
```


Получает или задает угол.

Угол.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


Получает цвет RGB.

**Returns:**
[Color](../../com.aspose.psd/color) - The RGB Color
### getColorModel() {#getColorModel--}
```
public final String getColorModel()
```


Цветовая модель - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl").

**Returns:**
java.lang.String
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Получает цветовые точки.

Значение: точки цвета.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


Получает или задает значение, указывающее, используется ли дизеринг для этого [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource).

Значение:  true  если включён дизеринг; иначе  false .

**Returns:**
boolean
### getGradientInterval() {#getGradientInterval--}
```
public final double getGradientInterval()
```


Получает или задает интервал градиента.

Значение: интервал градиента.

**Returns:**
double
### getGradientMode() {#getGradientMode--}
```
public final String getGradientMode()
```


Режим для этого градиента. Определяет 'Тип градиента' = 'Сплошной/Шум' = "CstS"/"ClNs".

**Returns:**
java.lang.String
### getGradientName() {#getGradientName--}
```
public String getGradientName()
```


Получает или задаёт имя градиента.

Значение: Имя градиента.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public int getGradientType()
```




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
### getHorizontalOffset() {#getHorizontalOffset--}
```
public double getHorizontalOffset()
```


Получает или задает горизонтальное смещение.

Горизонтальное смещение.

**Returns:**
double
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


Максимальный цвет PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Минимальный цвет PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getOffset_internalized() {#getOffset-internalized--}
```
public final OffsetEntity getOffset_internalized()
```


Получает или задает смещение.

Значение: смещение.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
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
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Получает или задает значение, указывающее, является ли этот [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) обратным.

Значение:  true  если обратный; иначе  false .

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


Коэффициент шероховатости.

**Returns:**
int
### getScale() {#getScale--}
```
public final double getScale()
```


Получает или задает масштаб.

**Returns:**
double
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Флаг отображения прозрачности.

**Returns:**
boolean
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


Получает точки прозрачности.

Значение: точки прозрачности.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Флаг использования векторного цвета.

**Returns:**
boolean
### getVerticalOffset() {#getVerticalOffset--}
```
public double getVerticalOffset()
```


Получает или задает вертикальное смещение.

Вертикальное смещение.

**Returns:**
double
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
public void setAngle(double value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Получает цвет RGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setColorModel(String value) {#setColorModel-java.lang.String-}
```
public final void setColorModel(String value)
```


Цветовая модель - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl").

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Получает цветовые точки.

Значение: точки цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Получает или задает значение, указывающее, используется ли дизеринг для этого [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource).

Значение:  true  если включён дизеринг; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setGradientInterval(double value) {#setGradientInterval-double-}
```
public final void setGradientInterval(double value)
```


Получает или задает интервал градиента.

Значение: интервал градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setGradientMode(String value) {#setGradientMode-java.lang.String-}
```
public final void setGradientMode(String value)
```


Режим для этого градиента. Определяет 'Тип градиента' = 'Сплошной/Шум' = "CstS"/"ClNs".

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public void setGradientName(String value)
```


Получает или задаёт имя градиента.

Значение: Имя градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public void setGradientType(int value)
```




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

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public void setHorizontalOffset(double value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

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


Максимальный цвет PixelDataFormat.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Минимальный цвет PixelDataFormat.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setOffset_internalized(OffsetEntity value) {#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setOffset_internalized(OffsetEntity value)
```


Получает или задает смещение.

Значение: смещение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Получает или задает значение, указывающее, является ли этот [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) обратным.

Значение:  true  если обратный; иначе  false .

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


Коэффициент шероховатости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Получает или задает масштаб.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Флаг отображения прозрачности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Получает точки прозрачности.

Значение: точки прозрачности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Флаг использования векторного цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public void setVerticalOffset(double value)
```




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

