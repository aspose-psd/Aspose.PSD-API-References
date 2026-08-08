---
title: "UnknownSmartFilter"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс для хранения данных неизвестного умного фильтра."
type: docs
weight: 14
url: /ru/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/unknownsmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class UnknownSmartFilter extends SmartFilter
```

Класс для хранения данных неизвестного умного фильтра.
## Методы

| Метод | Описание |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Применяет текущий фильтр к входному изображению RasterImage. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Применяет текущий фильтр к входным данным маски [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Создаёт побочный клон текущего экземпляра данного типа. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Получает или задает режим смешивания. |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | Получает идентификатор типа умного фильтра. |
| [getName()](#getName--) | Получает имя умного фильтра. |
| [getOpacity()](#getOpacity--) | Получает или задает значение непрозрачности умного фильтра. |
| [getSourceDescriptor()](#getSourceDescriptor--) | Исходная структура дескриптора с данными умного фильтра. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Получает или задает статус включения умного фильтра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Получает или задает режим смешивания. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Получает или задает статус включения умного фильтра. |
| [setOpacity(double value)](#setOpacity-double-) | Получает или задает значение непрозрачности умного фильтра. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Сохраняет информацию об умном фильтре в данные [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) и возвращает. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


Применяет текущий фильтр к входному изображению RasterImage.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Растровое изображение. |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


Применяет текущий фильтр к входным данным маски [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Слой с данными маски. |

### create_internalized(DescriptorStructure sourceDescriptor) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static UnknownSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[UnknownSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/unknownsmartfilter)
### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


Создаёт побочный клон текущего экземпляра данного типа.

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Получает или задает режим смешивания.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFilterId() {#getFilterId--}
```
public int getFilterId()
```


Получает идентификатор типа умного фильтра.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Получает имя умного фильтра.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Получает или задает значение непрозрачности умного фильтра.

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


Исходная структура дескриптора с данными умного фильтра.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Получает или задает статус включения умного фильтра.

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




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Получает или задает режим смешивания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Получает или задает статус включения умного фильтра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Получает или задает значение непрозрачности умного фильтра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


Сохраняет информацию об умном фильтре в данные [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) и возвращает.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) - The [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) with saved smart filter information.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

