---
title: "ResolutionInfoResource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Ресурс информации о разрешении"
type: docs
weight: 33
url: /ru/java/com.aspose.psd.fileformats.psd.resources/resolutioninforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class ResolutionInfoResource extends ResourceBlock
```

Ресурс информации о разрешении
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ResolutionInfoResource()](#ResolutionInfoResource--) | Инициализирует новый экземпляр класса [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource). |
## Поля

| Поле | Описание |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Сигнатура ресурса ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Обычная сигнатура ресурса Photoshop. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Получает размер данных ресурса в байтах. |
| [getHDpi()](#getHDpi--) | Горизонтальное DPI. |
| [getHResDisplayUnit()](#getHResDisplayUnit--) | Единицы отображения для горизонтального разрешения. |
| [getHeightDisplayUnit()](#getHeightDisplayUnit--) | Получает или задаёт единицу отображения высоты. |
| [getID()](#getID--) | Получает или задает уникальный идентификатор ресурса. |
| [getMinimalVersion()](#getMinimalVersion--) | Получает минимальную требуемую версию PSD. |
| [getName()](#getName--) | Получает или задает имя ресурса. |
| [getSignature()](#getSignature--) | Получает сигнатуру ресурса. |
| [getSize()](#getSize--) | Получает размер блока ресурса в байтах, включая его данные. |
| [getVDpi()](#getVDpi--) | Вертикальное DPI. |
| [getVResDisplayUnit()](#getVResDisplayUnit--) | Единицы отображения для вертикального разрешения. |
| [getWidthDisplayUnit()](#getWidthDisplayUnit--) | Получает или задаёт единицу отображения ширины. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Сохраняет блок ресурса в указанный поток. |
| [setHDpi(FixedPointDecimal value)](#setHDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-) | Горизонтальное DPI. |
| [setHResDisplayUnit(int value)](#setHResDisplayUnit-int-) | Единицы отображения для горизонтального разрешения. |
| [setHeightDisplayUnit(int value)](#setHeightDisplayUnit-int-) | Получает или задаёт единицу отображения высоты. |
| [setID(short value)](#setID-short-) | Получает или задает уникальный идентификатор ресурса. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Получает или задает информацию о слое и маске. |
| [setName(String value)](#setName-java.lang.String-) | Получает или задает имя ресурса. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Получает или задает состояние блока ресурса. |
| [setVDpi(FixedPointDecimal value)](#setVDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-) | Вертикальное DPI. |
| [setVResDisplayUnit(int value)](#setVResDisplayUnit-int-) | Единицы отображения для вертикального разрешения. |
| [setWidthDisplayUnit(int value)](#setWidthDisplayUnit-int-) | Получает или задаёт единицу отображения ширины. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Проверяет значения ресурса. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionInfoResource() {#ResolutionInfoResource--}
```
public ResolutionInfoResource()
```


Инициализирует новый экземпляр класса [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


Сигнатура ресурса ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


Обычная сигнатура ресурса Photoshop.

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
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Получает размер данных ресурса в байтах.

Значение: Размер данных ресурса.

**Returns:**
int
### getHDpi() {#getHDpi--}
```
public final FixedPointDecimal getHDpi()
```


Горизонтальное DPI.

Значение: Горизонтальное DPI.

**Returns:**
[FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal)
### getHResDisplayUnit() {#getHResDisplayUnit--}
```
public final int getHResDisplayUnit()
```


Единицы отображения для горизонтального разрешения. Это влияет только на пользовательский интерфейс; разрешение всё равно хранится в файле PSD в виде пикселей/дюйм.

Значение: Единица отображения горизонтального разрешения.

**Returns:**
int
### getHeightDisplayUnit() {#getHeightDisplayUnit--}
```
public final int getHeightDisplayUnit()
```


Получает или задаёт единицу отображения высоты.

Значение: Единица отображения высоты.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Получает или задает уникальный идентификатор ресурса.

Значение: Уникальный идентификатор ресурса.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Получает минимальную требуемую версию PSD.

Значение: Минимальная версия PSD.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Получает или задает имя ресурса. Строка Pascal, дополненная до чётного размера (пустое имя состоит из двух байтов 0).

Значение: Имя ресурса.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Получает подпись ресурса. Должна всегда быть '8BIM'.

Значение: Подпись ресурса.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Получает размер блока ресурса в байтах, включая его данные.

Значение: Размер блока ресурса.

**Returns:**
int
### getVDpi() {#getVDpi--}
```
public final FixedPointDecimal getVDpi()
```


Вертикальное DPI.

Значение: вертикальное DPI.

**Returns:**
[FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal)
### getVResDisplayUnit() {#getVResDisplayUnit--}
```
public final int getVResDisplayUnit()
```


Единицы отображения для вертикального разрешения.

Значение: единица отображения вертикального разрешения.

**Returns:**
int
### getWidthDisplayUnit() {#getWidthDisplayUnit--}
```
public final int getWidthDisplayUnit()
```


Получает или задаёт единицу отображения ширины.

Значение: единица отображения ширины.

**Returns:**
int
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Сохраняет блок ресурса в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Поток, в который сохраняется блок ресурса. |

### setHDpi(FixedPointDecimal value) {#setHDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-}
```
public final void setHDpi(FixedPointDecimal value)
```


Горизонтальное DPI.

Значение: Горизонтальное DPI.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) |  |

### setHResDisplayUnit(int value) {#setHResDisplayUnit-int-}
```
public final void setHResDisplayUnit(int value)
```


Единицы отображения для горизонтального разрешения. Это влияет только на пользовательский интерфейс; разрешение всё равно хранится в файле PSD в виде пикселей/дюйм.

Значение: Единица отображения горизонтального разрешения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setHeightDisplayUnit(int value) {#setHeightDisplayUnit-int-}
```
public final void setHeightDisplayUnit(int value)
```


Получает или задаёт единицу отображения высоты.

Значение: Единица отображения высоты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Получает или задает уникальный идентификатор ресурса.

Значение: Уникальный идентификатор ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Получает или задает информацию о слое и маске.

Значение: Информация о слоях и масках.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Получает или задает имя ресурса. Строка Pascal, дополненная до чётного размера (пустое имя состоит из двух байтов 0).

Значение: Имя ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| подпись | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Получает или задает состояние блока ресурса.

Значение: Состояние блока ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setVDpi(FixedPointDecimal value) {#setVDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-}
```
public final void setVDpi(FixedPointDecimal value)
```


Вертикальное DPI.

Значение: вертикальное DPI.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) |  |

### setVResDisplayUnit(int value) {#setVResDisplayUnit-int-}
```
public final void setVResDisplayUnit(int value)
```


Единицы отображения для вертикального разрешения.

Значение: единица отображения вертикального разрешения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWidthDisplayUnit(int value) {#setWidthDisplayUnit-int-}
```
public final void setWidthDisplayUnit(int value)
```


Получает или задаёт единицу отображения ширины.

Значение: единица отображения ширины.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Проверяет значения ресурса.

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

