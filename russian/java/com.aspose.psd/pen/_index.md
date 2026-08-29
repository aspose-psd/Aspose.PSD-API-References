---
title: "Pen"
second_title: "Aspose.PSD for Java API Справочник"
description: "Определяет объект, используемый для рисования линий, кривых и фигур."
type: docs
weight: 77
url: /ru/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Определяет объект, используемый для рисования линий, кривых и фигур.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | Инициализирует новый экземпляр класса Pen с указанным цветом. |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | Инициализирует новый экземпляр класса Pen с указанными свойствами Color и Pen.Width. |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | Инициализирует новый экземпляр класса Pen с указанным Brush. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | Инициализирует новый экземпляр класса Pen с указанными Brush и Pen.Width. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Возвращает выравнивание для этого Pen. |
| [getBrush()](#getBrush--) | Возвращает Brush, определяющий атрибуты этого Pen. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Возвращает цвет этого Pen. |
| [getCompoundArray()](#getCompoundArray--) | Возвращает массив значений, определяющих составной Pen. |
| [getCustomEndCap()](#getCustomEndCap--) | Возвращает пользовательскую заглушку, используемую в конце линий, нарисованных этим Pen. |
| [getCustomStartCap()](#getCustomStartCap--) | Возвращает пользовательскую заглушку, используемую в начале линий, нарисованных этим Pen. |
| [getDashCap()](#getDashCap--) | Возвращает стиль заглушки, используемый в конце штрихов, составляющих пунктирные линии, нарисованные этим Pen. |
| [getDashOffset()](#getDashOffset--) | Возвращает расстояние от начала линии до начала шаблона штриха. |
| [getDashPattern()](#getDashPattern--) | Возвращает массив пользовательских штрихов и пробелов. |
| [getDashStyle()](#getDashStyle--) | Возвращает стиль, используемый для пунктирных линий, нарисованных этим Pen. |
| [getEndCap()](#getEndCap--) | Возвращает стиль заглушки, используемый в конце линий, нарисованных этим Pen. |
| [getLineJoin()](#getLineJoin--) | Возвращает стиль соединения для концов двух последовательных линий, нарисованных этим Pen. |
| [getMiterLimit()](#getMiterLimit--) | Возвращает предел толщины соединения на скошенном угле. |
| [getOpacity()](#getOpacity--) | Получает непрозрачность объекта. |
| [getPenType()](#getPenType--) | Возвращает стиль линий, нарисованных этим Pen. |
| [getStartCap()](#getStartCap--) | Возвращает стиль заглушки, используемый в начале линий, нарисованных этим Pen. |
| [getTransform()](#getTransform--) | Возвращает копию геометрического преобразования для этого Pen. |
| [getWidth()](#getWidth--) | Возвращает ширину этого Pen в единицах объекта Graphics, используемого для рисования. |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Умножает матрицу преобразования для этого Pen на указанную Matrix. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Умножает матрицу преобразования для этого Pen на указанную Matrix в заданном порядке. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Сбрасывает матрицу геометрического преобразования для этого Pen к единичной. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Поворачивает локальное геометрическое преобразование на указанный угол. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Поворачивает локальное геометрическое преобразование на указанный угол в указанном порядке. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Масштабирует локальное геометрическое преобразование по указанным коэффициентам. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Масштабирует локальное геометрическое преобразование по указанным коэффициентам в указанном порядке. |
| [setAlignment(int value)](#setAlignment-int-) | Устанавливает выравнивание для этой  Pen . |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | Устанавливает  Brush  определяющий атрибуты этой  Pen . |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Устанавливает цвет этой  Pen . |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Устанавливает массив значений, определяющих составную pen. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | Устанавливает пользовательскую заглушку, используемую в конце линий, нарисованных этой  Pen . |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | Устанавливает пользовательскую заглушку, используемую в начале линий, нарисованных этой  Pen . |
| [setDashCap(int value)](#setDashCap-int-) | Устанавливает стиль заглушки, используемый в конце тире, составляющих пунктирные линии, нарисованные этой  Pen . |
| [setDashOffset(float value)](#setDashOffset-float-) | Устанавливает расстояние от начала линии до начала шаблона тире. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Устанавливает массив пользовательских тире и пробелов. |
| [setDashStyle(int value)](#setDashStyle-int-) | Устанавливает стиль, используемый для пунктирных линий, нарисованных этой  Pen . |
| [setEndCap(int value)](#setEndCap-int-) | Устанавливает стиль заглушки, используемый в конце линий, нарисованных этой  Pen . |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Устанавливает значения, определяющие стиль заглушки, используемой для завершения линий, нарисованных этой  Pen . |
| [setLineJoin(int value)](#setLineJoin-int-) | Устанавливает стиль соединения для концов двух последовательных линий, нарисованных этой  Pen . |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Устанавливает предел толщины соединения на скошенном угле. |
| [setOpacity(float value)](#setOpacity-float-) | Устанавливает непрозрачность объекта. |
| [setStartCap(int value)](#setStartCap-int-) | Устанавливает стиль заглушки, используемый в начале линий, нарисованных этой  Pen . |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Устанавливает копию геометрического преобразования для этой  Pen . |
| [setWidth(float value)](#setWidth-float-) | Устанавливает ширину этой  Pen , в единицах объекта Graphics, используемого для рисования. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Перемещает локальное геометрическое преобразование на указанные размеры. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


Инициализирует новый экземпляр класса Pen с указанным цветом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Структура  Color  , указывающая цвет этой  Pen . |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


Инициализирует новый экземпляр класса Pen с указанными свойствами Color и Pen.Width.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Структура  Color  , указывающая цвет этой  Pen . |
| ширина | float | Значение, указывающее ширину этой  Pen . |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


Инициализирует новый экземпляр класса Pen с указанным Brush.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush, определяющая свойства заливки этого Pen. |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


Инициализирует новый экземпляр класса Pen с указанными Brush и Pen.Width.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush, определяющая характеристики этого Pen. |
| ширина | float | Ширина нового Pen. |

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Возвращает выравнивание для этого Pen.

**Returns:**
int - PenAlignment, представляющий выравнивание для этого Pen.
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Возвращает Brush, определяющий атрибуты этого Pen.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Возвращает цвет этого Pen.

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Возвращает массив значений, определяющий составную ручку. Составная ручка рисует составную линию, состоящую из параллельных линий и пробелов.

**Returns:**
float[] - Массив действительных чисел, определяющий составной массив. Элементы массива должны быть в порядке возрастания, не меньше 0 и не больше 1.
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Возвращает пользовательскую заглушку, используемую в конце линий, нарисованных этим Pen.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Возвращает пользовательскую заглушку, используемую в начале линий, нарисованных этим Pen.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Возвращает стиль заглушки, используемый в конце штрихов, составляющих пунктирные линии, нарисованные этим Pen.

**Returns:**
int - Одно из значений DashCap, представляющее стиль наконечника, используемый в начале и в конце штрихов, составляющих пунктирные линии, нарисованные этим Pen.
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Возвращает расстояние от начала линии до начала шаблона штриха.

**Returns:**
float - Расстояние от начала линии до начала шаблона штриха.
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Возвращает массив пользовательских штрихов и пробелов.

**Returns:**
float[] - Массив действительных чисел, определяющий длины чередующихся штрихов и пробелов в пунктирных линиях.
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Возвращает стиль, используемый для пунктирных линий, нарисованных этим Pen.

**Returns:**
int - DashStyle, представляющий стиль, используемый для пунктирных линий, нарисованных этим Pen.
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Возвращает стиль заглушки, используемый в конце линий, нарисованных этим Pen.

**Returns:**
int - Одно из значений LineCap, представляющее стиль наконечника, используемый в конце линий, нарисованных этим Pen.
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Возвращает стиль соединения для концов двух последовательных линий, нарисованных этим Pen.

**Returns:**
int - LineJoin, представляющий стиль соединения концов двух последовательных линий, нарисованных этим Pen.
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Возвращает предел толщины соединения на скошенном угле.

**Returns:**
float - Предел толщины соединения на скошенном угле.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Получает непрозрачность объекта. Значение должно быть в диапазоне от 0 до 1. Значение 0 означает, что объект полностью видим, значение 1 означает, что объект полностью непрозрачный.

**Returns:**
float — значение непрозрачности.
### getPenType() {#getPenType--}
```
public int getPenType()
```


Возвращает стиль линий, нарисованных этим Pen.

**Returns:**
int - Перечисление PenType, определяющее стиль линий, нарисованных этим Pen.
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Возвращает стиль заглушки, используемый в начале линий, нарисованных этим Pen.

**Returns:**
int - Одно из значений LineCap, представляющее стиль наконечника, используемый в начале линий, нарисованных этим Pen.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Возвращает копию геометрического преобразования для этого Pen.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


Возвращает ширину этого Pen в единицах объекта Graphics, используемого для рисования.

**Returns:**
float - Ширина этого Pen.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Умножает матрицу преобразования для этого Pen на указанную Matrix.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Объект Matrix, которым умножается матрица преобразования. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Умножает матрицу преобразования для этого Pen на указанную Matrix в заданном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrix, которым умножается матрица преобразования. |
| порядок | int | Порядок выполнения операции умножения. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Сбрасывает матрицу геометрического преобразования для этого Pen к единичной.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Вращает локальное геометрическое преобразование на указанный угол. Этот метод добавляет вращение в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Поворачивает локальное геометрическое преобразование на указанный угол в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |
| порядок | int | MatrixOrder, определяющий, добавлять ли или предварять матрицу вращения. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Масштабирует локальное геометрическое преобразование на указанные коэффициенты. Этот метод добавляет матрицу масштабирования в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Коэффициент масштабирования преобразования по оси X. |
| sy | float | Коэффициент масштабирования преобразования по оси Y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Масштабирует локальное геометрическое преобразование по указанным коэффициентам в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Коэффициент масштабирования преобразования по оси X. |
| sy | float | Коэффициент масштабирования преобразования по оси Y. |
| порядок | int | MatrixOrder, определяющий, добавлять ли или предварять матрицу масштабирования. |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Устанавливает выравнивание для этой  Pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | PenAlignment, представляющий выравнивание для этой Pen. |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


Устанавливает  Brush  определяющий атрибуты этой  Pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | Brush, определяющий атрибуты этой Pen. |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Устанавливает цвет этой  Pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Структура Color, представляющая цвет этой Pen. |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Устанавливает массив значений, определяющий составную ручку. Составная ручка рисует составную линию, состоящую из параллельных линий и промежутков.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float[] | Массив вещественных чисел, определяющий составной массив. Элементы массива должны быть упорядочены по возрастанию, не меньше 0 и не больше 1. |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Устанавливает пользовательскую заглушку, используемую в конце линий, нарисованных этой  Pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | CustomLineCap, представляющий концевой элемент, используемый в конце линий, нарисованных этой Pen. |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Устанавливает пользовательскую заглушку, используемую в начале линий, нарисованных этой  Pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | CustomLineCap, представляющий концевой элемент, используемый в начале линий, нарисованных этой Pen. |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Устанавливает стиль заглушки, используемый в конце тире, составляющих пунктирные линии, нарисованные этой  Pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Одно из значений DashCap, представляющее стиль концевого элемента, используемый в начале и конце тире, составляющих пунктирные линии, нарисованные этой Pen. |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Устанавливает расстояние от начала линии до начала шаблона тире.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Расстояние от начала линии до начала шаблона тире. |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Устанавливает массив пользовательских тире и пробелов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float[] | Массив вещественных чисел, определяющий длины чередующихся тире и пробелов в пунктирных линиях. |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Устанавливает стиль, используемый для пунктирных линий, нарисованных этой  Pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | DashStyle, представляющий стиль, используемый для пунктирных линий, нарисованных этой Pen. |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Устанавливает стиль заглушки, используемый в конце линий, нарисованных этой  Pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Одно из значений LineCap, представляющее стиль концевого элемента, используемый в конце линий, нарисованных этой Pen. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Устанавливает значения, определяющие стиль заглушки, используемой для завершения линий, нарисованных этой  Pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startCap | int | LineCap, представляющий стиль концевого элемента, используемый в начале линий, нарисованных этой Pen. |
| endCap | int | LineCap, представляющий стиль концевого элемента, используемый в конце линий, нарисованных этой Pen. |
| dashCap | int | LineCap, представляющий стиль концевого элемента, используемый в начале или в конце пунктирных линий, нарисованных этой Pen. |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Устанавливает стиль соединения для концов двух последовательных линий, нарисованных этой  Pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | LineJoin, представляющий стиль соединения концов двух последовательных линий, нарисованных этой Pen. |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Устанавливает предел толщины соединения на скошенном угле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Предел толщины соединения на скошенном угле. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Устанавливает непрозрачность объекта. Значение должно быть в диапазоне от 0 до 1. Значение 0 означает, что объект полностью видим, значение 1 означает, что объект полностью непрозрачный.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Значение непрозрачности. |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Устанавливает стиль заглушки, используемый в начале линий, нарисованных этой  Pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Одно из значений LineCap, представляющее стиль концевого элемента, используемый в начале линий, нарисованных этой Pen. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Устанавливает копию геометрического преобразования для этой  Pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Копия Matrix, представляющая геометрическое преобразование для этой Pen. |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Устанавливает ширину этой  Pen , в единицах объекта Graphics, используемого для рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Ширина этой Pen. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Перемещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| порядок | int | Порядок (prepend или append), в котором применяется трансляция. |

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

