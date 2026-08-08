---
title: "TransparencyIndexResource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Блок ресурса индекса прозрачности."
type: docs
weight: 37
url: /ru/java/com.aspose.psd.fileformats.psd.resources/transparencyindexresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class TransparencyIndexResource extends ResourceBlock
```

Блок ресурса индекса прозрачности.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TransparencyIndexResource()](#TransparencyIndexResource--) | Инициализирует новый экземпляр класса [TransparencyIndexResource](../../com.aspose.psd.fileformats.psd.resources/transparencyindexresource). |
## Поля

| Поле | Описание |
| --- | --- |
| [RequiredVersion_internalized](#RequiredVersion-internalized) | Требуемая версия PSD. |
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
| [getSignature()](#getSignature--) | Получает сигнатуру ресурса. |
| [getSize()](#getSize--) | Получает размер блока ресурса в байтах, включая его данные. |
| [getTransparencyIndex()](#getTransparencyIndex--) | Получает или задает индекс цвета прозрачности. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Сохраняет блок ресурса в указанный поток. |
| [setID(short value)](#setID-short-) | Получает или задает уникальный идентификатор ресурса. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Получает или задает информацию о слое и маске. |
| [setName(String value)](#setName-java.lang.String-) | Получает или задает имя ресурса. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Получает или задает состояние блока ресурса. |
| [setTransparencyIndex(short value)](#setTransparencyIndex-short-) | Получает или задает индекс цвета прозрачности. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Проверяет значения ресурса. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransparencyIndexResource() {#TransparencyIndexResource--}
```
public TransparencyIndexResource()
```


Инициализирует новый экземпляр класса [TransparencyIndexResource](../../com.aspose.psd.fileformats.psd.resources/transparencyindexresource).

### RequiredVersion_internalized {#RequiredVersion-internalized}
```
public static final int RequiredVersion_internalized
```


Требуемая версия PSD.

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

Значение: минимальная версия psd.

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
### getTransparencyIndex() {#getTransparencyIndex--}
```
public final short getTransparencyIndex()
```


Получает или задает индекс цвета прозрачности.

Значение: Индекс цвета прозрачности.

**Returns:**
short
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

### setTransparencyIndex(short value) {#setTransparencyIndex-short-}
```
public final void setTransparencyIndex(short value)
```


Получает или задает индекс цвета прозрачности.

Значение: Индекс цвета прозрачности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

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

