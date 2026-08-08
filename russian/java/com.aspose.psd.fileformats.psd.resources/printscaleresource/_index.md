---
title: "PrintScaleResource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Ресурс масштаба печати"
type: docs
weight: 31
url: /ru/java/com.aspose.psd.fileformats.psd.resources/printscaleresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class PrintScaleResource extends ResourceBlock
```

Ресурс масштаба печати
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PrintScaleResource()](#PrintScaleResource--) | Инициализирует новый экземпляр класса [PrintScaleResource](../../com.aspose.psd.fileformats.psd.resources/printscaleresource). |
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
| [getID()](#getID--) | Получает или задает уникальный идентификатор ресурса. |
| [getMinimalVersion()](#getMinimalVersion--) | Получает минимальную требуемую версию PSD. |
| [getName()](#getName--) | Получает или задает имя ресурса. |
| [getScale()](#getScale--) | Получает или задает масштаб. |
| [getSignature()](#getSignature--) | Получает сигнатуру ресурса. |
| [getSize()](#getSize--) | Получает размер блока ресурса в байтах, включая его данные. |
| [getStyle()](#getStyle--) | Получает или задает стиль. |
| [getXLocation()](#getXLocation--) | Получает или задает положение по оси X. |
| [getYLocation()](#getYLocation--) | Получает или задает положение по оси Y. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Сохраняет блок ресурса в указанный поток. |
| [setID(short value)](#setID-short-) | Получает или задает уникальный идентификатор ресурса. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Получает или задает информацию о слое и маске. |
| [setName(String value)](#setName-java.lang.String-) | Получает или задает имя ресурса. |
| [setScale(float value)](#setScale-float-) | Получает или задает масштаб. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Получает или задает состояние блока ресурса. |
| [setStyle(short value)](#setStyle-short-) | Получает или задает стиль. |
| [setXLocation(float value)](#setXLocation-float-) | Получает или задает положение по оси X. |
| [setYLocation(float value)](#setYLocation-float-) | Получает или задает положение по оси Y. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Проверяет значения ресурса. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintScaleResource() {#PrintScaleResource--}
```
public PrintScaleResource()
```


Инициализирует новый экземпляр класса [PrintScaleResource](../../com.aspose.psd.fileformats.psd.resources/printscaleresource).

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
### getScale() {#getScale--}
```
public final float getScale()
```


Получает или задает масштаб.

Значение: Масштаб.

**Returns:**
float
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
### getStyle() {#getStyle--}
```
public final short getStyle()
```


Получает или задает стиль.

Значение: Стиль.

**Returns:**
short
### getXLocation() {#getXLocation--}
```
public final float getXLocation()
```


Получает или задает положение по оси X.

Значение: Положение по оси X.

**Returns:**
float
### getYLocation() {#getYLocation--}
```
public final float getYLocation()
```


Получает или задает положение по оси Y.

Значение: Положение по оси Y.

**Returns:**
float
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

### setScale(float value) {#setScale-float-}
```
public final void setScale(float value)
```


Получает или задает масштаб.

Значение: Масштаб.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

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

### setStyle(short value) {#setStyle-short-}
```
public final void setStyle(short value)
```


Получает или задает стиль.

Значение: Стиль.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setXLocation(float value) {#setXLocation-float-}
```
public final void setXLocation(float value)
```


Получает или задает положение по оси X.

Значение: Положение по оси X.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setYLocation(float value) {#setYLocation-float-}
```
public final void setYLocation(float value)
```


Получает или задает положение по оси Y.

Значение: Положение по оси Y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

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

