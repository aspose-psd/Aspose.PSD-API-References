---
title: "VectorShapeOriginSettings"
second_title: "Aspose.PSD for Java API Справочник"
description: "Настройки происхождения векторной формы."
type: docs
weight: 24
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings/
---

**Inheritance:**
java.lang.Object
```
public final class VectorShapeOriginSettings
```

Настройки происхождения векторной формы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)](#VectorShapeOriginSettings-boolean-int-) | Инициализирует новый экземпляр класса [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings). |
| [VectorShapeOriginSettings()](#VectorShapeOriginSettings--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [KeyOriginIndex_internalized](#KeyOriginIndex-internalized) | Ключ дескриптора для сохранения индекса происхождения фигуры. |
| [KeyOriginRRectRadii_internalized](#KeyOriginRRectRadii-internalized) | Ключ дескриптора радиусов прямоугольника происхождения |
| [KeyOriginResolution_internalized](#KeyOriginResolution-internalized) | Ключ дескриптора разрешения происхождения |
| [KeyOriginShapeBBox_internalized](#KeyOriginShapeBBox-internalized) | Ключ дескриптора ограничивающего прямоугольника происхождения фигуры |
| [KeyOriginType_internalized](#KeyOriginType-internalized) | Ключ дескриптора типа происхождения |
| [KeyShapeInvalidated_internalized](#KeyShapeInvalidated-internalized) | Ключ дескриптора для сохранения недействительного значения фигуры. |
| [KnownKeys_internalized](#KnownKeys-internalized) | Известные ключи свойств |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getId_internalized()](#getId-internalized--) | Получает уникальный идентификатор. |
| [getOriginBoxCorners()](#getOriginBoxCorners--) | Получает или задает углы исходного прямоугольника. |
| [getOriginIndex()](#getOriginIndex--) | Получает или задает индекс исходной фигуры. |
| [getOriginRadiiRectangle()](#getOriginRadiiRectangle--) | Получает или задает прямоугольник радиусов происхождения. |
| [getOriginResolution()](#getOriginResolution--) | Получает или задает разрешение происхождения. |
| [getOriginShapeBox()](#getOriginShapeBox--) | Получает или задает ограничивающий прямоугольник исходной фигуры. |
| [getOriginType()](#getOriginType--) | Получает или задает тип происхождения. |
| [getTransform()](#getTransform--) | Получает или задает матрицу преобразования. |
| [hasUnknownProperties_internalized()](#hasUnknownProperties-internalized--) | Получает или задает значение, указывающее, имеет ли данный экземпляр неизвестные свойства. |
| [hashCode()](#hashCode--) |  |
| [isChanged_internalized()](#isChanged-internalized--) | Получает или задает значение, указывающее, изменён ли данный экземпляр. |
| [isOriginBoxCornersPresent()](#isOriginBoxCornersPresent--) | Получает значение, указывающее, имеет ли данный экземпляр свойство углов исходного бокса. |
| [isOriginIndexPresent()](#isOriginIndexPresent--) | Получает значение, указывающее, имеет ли данный экземпляр свойство индекса источника. |
| [isOriginRadiiRectanglePresent()](#isOriginRadiiRectanglePresent--) | Получает значение, указывающее, присутствует ли прямоугольник радиусов источника у данного экземпляра. |
| [isOriginResolutionPresent()](#isOriginResolutionPresent--) | Получает значение, указывающее, имеет ли данный экземпляр свойство разрешения источника. |
| [isOriginShapeBBoxPresent()](#isOriginShapeBBoxPresent--) | Получает значение, указывающее, имеет ли данный экземпляр свойство прямоугольника. |
| [isOriginTypePresent()](#isOriginTypePresent--) | Получает значение, указывающее, имеет ли данный экземпляр свойство типа источника. |
| [isPropertyPresent_internalized(String key)](#isPropertyPresent-internalized-java.lang.String-) | Определяет, присутствует ли свойство с указанным ключом. |
| [isShapeInvalidated()](#isShapeInvalidated--) | Получает или задает значение, указывающее, недействительна ли фигура. |
| [isShapeInvalidatedPresent()](#isShapeInvalidatedPresent--) | Получает значение, указывающее, установлен ли у данного экземпляра набор свойств недействительной фигуры. |
| [isTransformPresent()](#isTransformPresent--) | Получает значение, указывающее, имеет ли данный экземпляр свойство преобразования. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChanged_internalized(boolean value)](#setChanged-internalized-boolean-) | Получает или задает значение, указывающее, изменён ли данный экземпляр. |
| [setOriginBoxCorners(double[] value)](#setOriginBoxCorners-double---) | Получает или задает углы исходного прямоугольника. |
| [setOriginIndex(int value)](#setOriginIndex-int-) | Получает или задает индекс исходной фигуры. |
| [setOriginRadiiRectangle(VectorShapeRadiiRectangle value)](#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-) | Получает или задает прямоугольник радиусов происхождения. |
| [setOriginResolution(double value)](#setOriginResolution-double-) | Получает или задает разрешение происхождения. |
| [setOriginShapeBox(VectorShapeBoundingBox value)](#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-) | Получает или задает ограничивающий прямоугольник исходной фигуры. |
| [setOriginType(int value)](#setOriginType-int-) | Получает или задает тип происхождения. |
| [setShapeInvalidated(boolean value)](#setShapeInvalidated-boolean-) | Получает или задает значение, указывающее, недействительна ли фигура. |
| [setTransform(VectorShapeTransform value)](#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-) | Получает или задает матрицу преобразования. |
| [setUnknownProperties_internalized(boolean value)](#setUnknownProperties-internalized-boolean-) | Получает или задает значение, указывающее, имеет ли данный экземпляр неизвестные свойства. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex) {#VectorShapeOriginSettings-boolean-int-}
```
public VectorShapeOriginSettings(boolean isShapeInvalidated, int originIndex)
```


Инициализирует новый экземпляр класса [VectorShapeOriginSettings](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeoriginsettings).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isShapeInvalidated | boolean | Значение, указывающее, что фигура недействительна. |
| originIndex | int | Индекс источника фигуры. |

### VectorShapeOriginSettings() {#VectorShapeOriginSettings--}
```
public VectorShapeOriginSettings()
```


### KeyOriginIndex_internalized {#KeyOriginIndex-internalized}
```
public static final String KeyOriginIndex_internalized
```


Ключ дескриптора для сохранения индекса происхождения фигуры.

### KeyOriginRRectRadii_internalized {#KeyOriginRRectRadii-internalized}
```
public static final String KeyOriginRRectRadii_internalized
```


Ключ дескриптора радиусов прямоугольника происхождения

### KeyOriginResolution_internalized {#KeyOriginResolution-internalized}
```
public static final String KeyOriginResolution_internalized
```


Ключ дескриптора разрешения происхождения

### KeyOriginShapeBBox_internalized {#KeyOriginShapeBBox-internalized}
```
public static final String KeyOriginShapeBBox_internalized
```


Ключ дескриптора ограничивающего прямоугольника происхождения фигуры

### KeyOriginType_internalized {#KeyOriginType-internalized}
```
public static final String KeyOriginType_internalized
```


Ключ дескриптора типа происхождения

### KeyShapeInvalidated_internalized {#KeyShapeInvalidated-internalized}
```
public static final String KeyShapeInvalidated_internalized
```


Ключ дескриптора для сохранения недействительного значения фигуры.

### KnownKeys_internalized {#KnownKeys-internalized}
```
public static final String[] KnownKeys_internalized
```


Известные ключи свойств

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
### getId_internalized() {#getId-internalized--}
```
public final System.Guid getId_internalized()
```


Получает уникальный идентификатор.

Значение: Уникальный идентификатор.

**Returns:**
com.aspose.ms.System.Guid
### getOriginBoxCorners() {#getOriginBoxCorners--}
```
public final double[] getOriginBoxCorners()
```


Получает или задает углы исходного прямоугольника.

Значение: Углы исходного бокса.

**Returns:**
double[]
### getOriginIndex() {#getOriginIndex--}
```
public final int getOriginIndex()
```


Получает или задает индекс исходной фигуры.

**Returns:**
int
### getOriginRadiiRectangle() {#getOriginRadiiRectangle--}
```
public final VectorShapeRadiiRectangle getOriginRadiiRectangle()
```


Получает или задает прямоугольник радиусов происхождения.

Значение: Прямоугольник радиусов источника.

**Returns:**
[VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle)
### getOriginResolution() {#getOriginResolution--}
```
public final double getOriginResolution()
```


Получает или задает разрешение происхождения.

Значение: Разрешение источника.

**Returns:**
double
### getOriginShapeBox() {#getOriginShapeBox--}
```
public final VectorShapeBoundingBox getOriginShapeBox()
```


Получает или задает ограничивающий прямоугольник исходной фигуры.

Значение: Бокс исходной фигуры.

**Returns:**
[VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox)
### getOriginType() {#getOriginType--}
```
public final int getOriginType()
```


Получает или задает тип происхождения.

Значение: Тип источника.

**Returns:**
int
### getTransform() {#getTransform--}
```
public final VectorShapeTransform getTransform()
```


Получает или задает матрицу преобразования.

Значение: Матрица преобразования.

**Returns:**
[VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform)
### hasUnknownProperties_internalized() {#hasUnknownProperties-internalized--}
```
public final boolean hasUnknownProperties_internalized()
```


Получает или задает значение, указывающее, имеет ли данный экземпляр неизвестные свойства.

Значение:  true  если у этого экземпляра есть неизвестные свойства; иначе,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isChanged_internalized() {#isChanged-internalized--}
```
public final boolean isChanged_internalized()
```


Получает или задает значение, указывающее, изменён ли данный экземпляр.

Значение:  true  если этот экземпляр изменён; иначе,  false .

**Returns:**
boolean
### isOriginBoxCornersPresent() {#isOriginBoxCornersPresent--}
```
public final boolean isOriginBoxCornersPresent()
```


Получает значение, указывающее, имеет ли данный экземпляр свойство углов исходного бокса.

Значение:  true  если у этого экземпляра есть свойство углов исходного прямоугольника; иначе,  false .

**Returns:**
boolean
### isOriginIndexPresent() {#isOriginIndexPresent--}
```
public final boolean isOriginIndexPresent()
```


Получает значение, указывающее, имеет ли данный экземпляр свойство индекса источника.

Значение:  true  если у этого экземпляра есть свойство индекса источника; иначе,  false .

**Returns:**
boolean
### isOriginRadiiRectanglePresent() {#isOriginRadiiRectanglePresent--}
```
public final boolean isOriginRadiiRectanglePresent()
```


Получает значение, указывающее, присутствует ли прямоугольник радиусов источника у данного экземпляра.

Значение:  true  если у этого экземпляра есть свойство исходного прямоугольника радиусов; иначе,  false .

**Returns:**
boolean
### isOriginResolutionPresent() {#isOriginResolutionPresent--}
```
public final boolean isOriginResolutionPresent()
```


Получает значение, указывающее, имеет ли данный экземпляр свойство разрешения источника.

Значение:  true  если у этого экземпляра есть свойство разрешения источника; иначе,  false .

**Returns:**
boolean
### isOriginShapeBBoxPresent() {#isOriginShapeBBoxPresent--}
```
public final boolean isOriginShapeBBoxPresent()
```


Получает значение, указывающее, имеет ли данный экземпляр свойство прямоугольника.

Значение:  true  если у этого экземпляра есть свойство исходного прямоугольника формы; иначе,  false .

**Returns:**
boolean
### isOriginTypePresent() {#isOriginTypePresent--}
```
public final boolean isOriginTypePresent()
```


Получает значение, указывающее, имеет ли данный экземпляр свойство типа источника.

Значение:  true  если у этого экземпляра есть свойство типа источника; иначе,  false .

**Returns:**
boolean
### isPropertyPresent_internalized(String key) {#isPropertyPresent-internalized-java.lang.String-}
```
public final boolean isPropertyPresent_internalized(String key)
```


Определяет, присутствует ли свойство с указанным ключом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ свойства. |

**Returns:**
boolean -  true  если свойство с указанным ключом присутствует; иначе,  false .
### isShapeInvalidated() {#isShapeInvalidated--}
```
public final boolean isShapeInvalidated()
```


Получает или задает значение, указывающее, недействительна ли фигура.

**Returns:**
boolean
### isShapeInvalidatedPresent() {#isShapeInvalidatedPresent--}
```
public final boolean isShapeInvalidatedPresent()
```


Получает значение, указывающее, установлен ли у данного экземпляра набор свойств недействительной фигуры.

Значение:  true  если у этого экземпляра есть набор свойства, указывающего, что форма недействительна; иначе,  false .

**Returns:**
boolean
### isTransformPresent() {#isTransformPresent--}
```
public final boolean isTransformPresent()
```


Получает значение, указывающее, имеет ли данный экземпляр свойство преобразования.

Значение:  true  если у этого экземпляра есть свойство трансформации; иначе,  false .

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




### setChanged_internalized(boolean value) {#setChanged-internalized-boolean-}
```
public final void setChanged_internalized(boolean value)
```


Получает или задает значение, указывающее, изменён ли данный экземпляр.

Значение:  true  если этот экземпляр изменён; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setOriginBoxCorners(double[] value) {#setOriginBoxCorners-double---}
```
public final void setOriginBoxCorners(double[] value)
```


Получает или задает углы исходного прямоугольника.

Значение: Углы исходного бокса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double[] |  |

### setOriginIndex(int value) {#setOriginIndex-int-}
```
public final void setOriginIndex(int value)
```


Получает или задает индекс исходной фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setOriginRadiiRectangle(VectorShapeRadiiRectangle value) {#setOriginRadiiRectangle-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeRadiiRectangle-}
```
public final void setOriginRadiiRectangle(VectorShapeRadiiRectangle value)
```


Получает или задает прямоугольник радиусов происхождения.

Значение: Прямоугольник радиусов источника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [VectorShapeRadiiRectangle](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshaperadiirectangle) |  |

### setOriginResolution(double value) {#setOriginResolution-double-}
```
public final void setOriginResolution(double value)
```


Получает или задает разрешение происхождения.

Значение: Разрешение источника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setOriginShapeBox(VectorShapeBoundingBox value) {#setOriginShapeBox-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeBoundingBox-}
```
public final void setOriginShapeBox(VectorShapeBoundingBox value)
```


Получает или задает ограничивающий прямоугольник исходной фигуры.

Значение: Бокс исходной фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [VectorShapeBoundingBox](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapeboundingbox) |  |

### setOriginType(int value) {#setOriginType-int-}
```
public final void setOriginType(int value)
```


Получает или задает тип происхождения.

Значение: Тип источника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShapeInvalidated(boolean value) {#setShapeInvalidated-boolean-}
```
public final void setShapeInvalidated(boolean value)
```


Получает или задает значение, указывающее, недействительна ли фигура.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setTransform(VectorShapeTransform value) {#setTransform-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorShapeTransform-}
```
public final void setTransform(VectorShapeTransform value)
```


Получает или задает матрицу преобразования.

Значение: Матрица преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [VectorShapeTransform](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorshapetransform) |  |

### setUnknownProperties_internalized(boolean value) {#setUnknownProperties-internalized-boolean-}
```
public final void setUnknownProperties_internalized(boolean value)
```


Получает или задает значение, указывающее, имеет ли данный экземпляр неизвестные свойства.

Значение:  true  если у этого экземпляра есть неизвестные свойства; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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

