---
title: "ImageAttributes"
second_title: "Aspose.PSD for Java API Справочник"
description: "Объект com.aspose.psd.ImageAttributes содержит информацию о том, как цвета растровых изображений и метафайлов изменяются во время рендеринга."
type: docs
weight: 55
url: /ru/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Объект com.aspose.psd.ImageAttributes содержит информацию о том, как цвета растровых изображений и метафайлов изменяются во время рендеринга. Объект com.aspose.psd.ImageAttributes поддерживает несколько настроек коррекции цвета, включая матрицы коррекции цвета, матрицы коррекции в градациях серого, значения гамма‑коррекции, таблицы сопоставления цветов и пороговые значения цвета. Во время рендеринга цвета могут быть скорректированы, затемнены, осветлены и удалены. Чтобы применить такие изменения, инициализируйте объект com.aspose.psd.ImageAttributes и передайте путь к этому объекту (а также путь к [Image](../../com.aspose.psd/image)) в метод drawImage.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Инициализирует новый экземпляр класса com.aspose.psd.ImageAttributes. |
## Поля

| Поле | Описание |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | Атрибуты изображения GDI. |
## Методы

| Метод | Описание |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Очищает таблицу переопределения цветов кисти этого объекта com.aspose.psd.ImageAttributes. |
| [clearColorKey()](#clearColorKey--) | Очищает цветовой ключ (диапазон прозрачности) для категории по умолчанию. |
| [clearColorKey(int type)](#clearColorKey-int-) | Очищает цветовой ключ (диапазон прозрачности) для указанной категории. |
| [clearColorMatrix()](#clearColorMatrix--) | Очищает матрицу коррекции цвета для категории по умолчанию. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Очищает матрицу коррекции цвета для указанной категории. |
| [clearGamma()](#clearGamma--) | Отключает гамма‑коррекцию для категории по умолчанию. |
| [clearGamma(int type)](#clearGamma-int-) | Отключает гамма‑коррекцию для указанной категории. |
| [clearNoOp()](#clearNoOp--) | Очищает настройку NoOp для категории по умолчанию. |
| [clearNoOp(int type)](#clearNoOp-int-) | Очищает настройку NoOp для указанной категории. |
| [clearOutputChannel()](#clearOutputChannel--) | Очищает настройку выходного канала CMYK (циан‑пурпурный‑жёлтый‑чёрный) для категории по умолчанию. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Очищает настройку выходного канала (циан‑пурпурный‑жёлтый‑чёрный) для указанной категории. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Очищает настройку цветового профиля выходного канала для категории по умолчанию. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Очищает настройку цветового профиля выходного канала для указанной категории. |
| [clearRemapTable()](#clearRemapTable--) | Очищает таблицу переопределения цветов для категории по умолчанию. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Очищает таблицу переопределения цветов для указанной категории. |
| [clearThreshold()](#clearThreshold--) | Очищает пороговое значение для категории по умолчанию. |
| [clearThreshold(int type)](#clearThreshold-int-) | Очищает пороговое значение для указанной категории. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | Устанавливает таблицу переопределения цветов для категории кисти. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | Устанавливает цветовой ключ для категории по умолчанию. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | Устанавливает цветовой ключ (диапазон прозрачности) для указанной категории. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | Устанавливает матрицу коррекции цвета и матрицу коррекции оттенков серого для категории по умолчанию. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | Устанавливает матрицу коррекции цвета и матрицу коррекции оттенков серого для категории по умолчанию. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Устанавливает матрицу коррекции цвета и матрицу коррекции оттенков серого для указанной категории. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | Устанавливает матрицу коррекции цвета для категории по умолчанию. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | Устанавливает матрицу коррекции цвета для категории по умолчанию. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Устанавливает матрицу коррекции цвета для указанной категории. |
| [setGamma(float gamma)](#setGamma-float-) | Устанавливает значение гаммы для категории по умолчанию. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Устанавливает значение гаммы для указанной категории. |
| [setNoOp()](#setNoOp--) | Отключает коррекцию цвета для категории по умолчанию. |
| [setNoOp(int type)](#setNoOp-int-) | Отключает коррекцию цвета для указанной категории. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Устанавливает канал вывода CMYK (циан‑пурпур‑желтый‑чёрный) для категории по умолчанию. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Устанавливает канал вывода CMYK (циан‑пурпур‑желтый‑чёрный) для указанной категории. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Устанавливает файл цветового профиля канала вывода для категории по умолчанию. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Устанавливает файл цветового профиля канала вывода для указанной категории. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | Устанавливает таблицу переопределения цветов для категории по умолчанию. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | Устанавливает таблицу переопределения цветов для указанной категории. |
| [setThreshold(float threshold)](#setThreshold-float-) | Устанавливает порог (диапазон прозрачности) для категории по умолчанию. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Устанавливает порог (диапазон прозрачности) для указанной категории. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Устанавливает режим обтекания, который используется для определения способа наложения текстуры на форму или на границы формы. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | Устанавливает режим обтекания и цвет, используемые для определения способа наложения текстуры на форму или на границы формы. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | Устанавливает режим обтекания и цвет, используемые для определения способа наложения текстуры на форму или на границы формы. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Инициализирует новый экземпляр класса com.aspose.psd.ImageAttributes.

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


Атрибуты изображения GDI.

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Очищает таблицу переопределения цветов кисти этого объекта com.aspose.psd.ImageAttributes.

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Очищает цветовой ключ (диапазон прозрачности) для категории по умолчанию.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Очищает цветовой ключ (диапазон прозрачности) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой цветовой ключ очищается. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Очищает матрицу коррекции цвета для категории по умолчанию.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Очищает матрицу коррекции цвета для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой матрица коррекции цвета очищается. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Отключает гамма‑коррекцию для категории по умолчанию.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Отключает гамма‑коррекцию для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой коррекция гаммы отключена. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Очищает настройку NoOp для категории по умолчанию.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Очищает настройку NoOp для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой настройка NoOp очищается. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Очищает настройку выходного канала CMYK (циан‑пурпурный‑жёлтый‑чёрный) для категории по умолчанию.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Очищает настройку выходного канала (циан‑пурпурный‑жёлтый‑чёрный) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент типа  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой параметр выходного канала сбрасывается. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Очищает настройку цветового профиля выходного канала для категории по умолчанию.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Очищает настройку цветового профиля выходного канала для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент типа  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой параметр профиля выходного канала сбрасывается. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Очищает таблицу переопределения цветов для категории по умолчанию.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Очищает таблицу переопределения цветов для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент типа  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой таблица переопределения сбрасывается. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Очищает пороговое значение для категории по умолчанию.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Очищает пороговое значение для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент типа  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой пороговое значение сбрасывается. |

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




### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.psd.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Устанавливает таблицу переопределения цветов для категории кисти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Массив объектов  com.aspose.psd.ColorMap. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Устанавливает цветовой ключ для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | Низкое значение цветового ключа. |
| colorHigh | [Color](../../com.aspose.psd/color) | Высокое значение цветового ключа. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Устанавливает цветовой ключ (диапазон прозрачности) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | Низкое значение цветового ключа. |
| colorHigh | [Color](../../com.aspose.psd/color) | Высокое значение цветового ключа. |
| type | int | Элемент типа  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой задаётся цветовой ключ. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Устанавливает матрицу коррекции цвета и матрицу коррекции оттенков серого для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Матрица коррекции цвета. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Матрица коррекции оттенков серого. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Устанавливает матрицу коррекции цвета и матрицу коррекции оттенков серого для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Матрица коррекции цвета. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Матрица коррекции оттенков серого. |
| флаги | int | Элемент типа  Aspose.Imaging.ColorMatrixFlag, который указывает тип изображения и цвета, которые будут затронуты матрицами коррекции цвета и коррекции оттенков серого. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Устанавливает матрицу коррекции цвета и матрицу коррекции оттенков серого для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Матрица коррекции цвета. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Матрица коррекции оттенков серого. |
| mode | int | Элемент типа  Aspose.Imaging.ColorMatrixFlag, который указывает тип изображения и цвета, которые будут затронуты матрицами коррекции цвета и коррекции оттенков серого. |
| type | int | Элемент типа  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой задаются матрицы коррекции цвета и коррекции оттенков серого. |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Устанавливает матрицу коррекции цвета для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Матрица коррекции цвета. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Устанавливает матрицу коррекции цвета для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Матрица коррекции цвета. |
| флаги | int | Элемент типа  Aspose.Imaging.ColorMatrixFlag, который указывает тип изображения и цвета, которые будут затронуты матрицей коррекции цвета. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Устанавливает матрицу коррекции цвета для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Матрица коррекции цвета. |
| mode | int | Элемент типа  Aspose.Imaging.ColorMatrixFlag, который указывает тип изображения и цвета, которые будут затронуты матрицей коррекции цвета. |
| type | int | Элемент типа  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой задаётся матрица коррекции цвета. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Устанавливает значение гаммы для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| gamma | float | Значение гамма‑коррекции. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Устанавливает значение гаммы для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| gamma | float | Значение гамма‑коррекции. |
| type | int | Элемент перечисления  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой задаётся значение гаммы. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Отключает коррекцию цвета для категории по умолчанию.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Отключает коррекцию цвета для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Элемент типа  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой отключается коррекция цвета. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Устанавливает канал вывода CMYK (циан‑пурпур‑желтый‑чёрный) для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| флаги | int | Элемент типа  Aspose.Imaging.ColorChannelFlag, который указывает выходной канал. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Устанавливает канал вывода CMYK (циан‑пурпур‑желтый‑чёрный) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| флаги | int | Элемент типа  Aspose.Imaging.ColorChannelFlag, который указывает выходной канал. |
| type | int | Элемент типа  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой задаётся выходной канал. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Устанавливает файл цветового профиля канала вывода для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Путь к файлу цветового профиля. Если файл цветового профиля находится в каталоге %SystemRoot%\\\\System32\\\\Spool\\\\Drivers\\\\Color, этот параметр может быть именем файла. В противном случае параметр должен содержать полностью квалифицированный путь. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Устанавливает файл цветового профиля канала вывода для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Путь к файлу цветового профиля. Если файл цветового профиля находится в каталоге %SystemRoot%\\\\System32\\\\Spool\\\\Drivers\\\\Color, этот параметр может быть именем файла. В противном случае параметр должен содержать полностью квалифицированный путь. |
| type | int | Элемент типа  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой задаётся файл цветового профиля выходного канала. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Устанавливает таблицу переопределения цветов для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Массив пар цветов типа  com.aspose.psd.ColorMap. Каждая пара цветов содержит существующий цвет (первое значение) и цвет, которому он будет сопоставлен (второе значение). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Устанавливает таблицу переопределения цветов для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Массив пар цветов типа  com.aspose.psd.ColorMap. Каждая пара цветов содержит существующий цвет (первое значение) и цвет, которому он будет сопоставлен (второе значение). |
| type | int | Элемент типа  Aspose.Imaging.ColorAdjustType, который указывает категорию, для которой задаётся таблица переопределения цвета. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Устанавливает порог (диапазон прозрачности) для категории по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | float | Вещественное число, определяющее значение порога. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Устанавливает порог (диапазон прозрачности) для указанной категории.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | float | Значение порога от 0,0 до 1,0, используемое в качестве точки разрыва для сортировки цветов, которые будут сопоставлены либо с максимальным, либо с минимальным значением. |
| type | int | Элемент  Aspose.Imaging.ColorAdjustType , определяющий категорию, для которой установлен цветовой порог. |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Устанавливает режим обтекания, используемый для определения способа наложения текстуры на форму или её границы. Текстура повторяется по форме, заполняя её, когда текстура меньше формы, которую она заполняет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | int | Элемент  Aspose.Imaging.WrapMode , определяющий, как повторяющиеся копии изображения используются для заполнения области. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


Устанавливает режим обтекания и цвет, используемые для определения способа наложения текстуры на форму или её границы. Текстура повторяется по форме, заполняя её, когда текстура меньше формы, которую она заполняет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | int | Элемент  Aspose.Imaging.WrapMode , определяющий, как повторяющиеся копии изображения используются для заполнения области. |
| color | [Color](../../com.aspose.psd/color) | Объект  com.aspose.psd.ImageAttributes , определяющий цвет пикселей за пределами отрисованного изображения. Этот цвет виден, если параметр режима установлен в  WrapMode.Clamp  и исходный прямоугольник, переданный в DrawImage, больше самого изображения. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Устанавливает режим обтекания и цвет, используемые для определения способа наложения текстуры на форму или её границы. Текстура повторяется по форме, заполняя её, когда текстура меньше формы, которую она заполняет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | int | Элемент  Aspose.Imaging.WrapMode , определяющий, как повторяющиеся копии изображения используются для заполнения области. |
| color | [Color](../../com.aspose.psd/color) | Объект цвета, определяющий цвет пикселей за пределами отрисованного изображения. Этот цвет виден, если параметр режима установлен в  WrapMode.Clamp  и исходный прямоугольник, переданный в DrawImage, больше самого изображения. |
| clamp | boolean | Этот параметр не оказывает влияния. Установите его в false. |

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

