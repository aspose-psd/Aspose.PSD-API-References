---
title: "LinearGradientBrush"
second_title: "Aspose.PSD for Java API Справочник"
description: "Инкапсулирует объект Aspose.Imaging.Brush с линейным градиентом."
type: docs
weight: 11
url: /ru/java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd/brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd/brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Инкапсулирует объект  Aspose.Imaging.Brush  с линейным градиентом. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | Инициализирует новый экземпляр класса  LinearGradientBrush  с параметрами по умолчанию. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | Инициализирует новый экземпляр класса  LinearGradientBrush  с указанными точками и цветами. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | Инициализирует новый экземпляр класса  LinearGradientBrush  с указанными точками и цветами. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Инициализирует новый экземпляр класса  LinearGradientBrush  на основе прямоугольника, начального и конечного цветов и угла ориентации. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Инициализирует новый экземпляр класса  LinearGradientBrush  на основе прямоугольника, начального и конечного цветов и угла ориентации. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Инициализирует новый экземпляр класса  LinearGradientBrush  на основе прямоугольника, начального и конечного цветов и угла ориентации. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Инициализирует новый экземпляр класса  LinearGradientBrush  на основе прямоугольника, начального и конечного цветов и угла ориентации. |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [deepClone()](#deepClone--) | Создаёт глубокую копию текущего Brush. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Получает угол градиента. |
| [getBlend()](#getBlend--) | Получает объект  Aspose.Imaging.Blend , который задаёт позиции и коэффициенты, определяющие пользовательское затухание градиента. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getEndColor()](#getEndColor--) | Получает конечный цвет градиента. |
| [getGammaCorrection()](#getGammaCorrection--) | Получает значение, указывающее, включена ли гамма‑коррекция для этого LinearGradientBrushBase. |
| [getInterpolationColors()](#getInterpolationColors--) | Получает объект com.aspose.psd.ColorBlend, определяющий многокрасочный линейный градиент. |
| [getLinearColors()](#getLinearColors--) | Получает начальный и конечный цвета градиента. |
| [getOpacity()](#getOpacity--) | Получает непрозрачность кисти. |
| [getRectangle()](#getRectangle--) | Получает прямоугольную область, определяющую начальную и конечную точки градиента. |
| [getStartColor()](#getStartColor--) | Получает начальный цвет градиента. |
| [getTransform()](#getTransform--) | Получает или задаёт копию Aspose.Imaging.Matrix, определяющую локальное геометрическое преобразование для этого TransformBrush. |
| [getWrapMode()](#getWrapMode--) | Получает или задаёт перечисление Aspose.Imaging.WrapMode, указывающее режим обтекания для этого TransformBrush. |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | Получает значение, указывающее, изменяется ли LinearGradientBrushBase.Angle во время преобразований с этим LinearGradientBrushBase. |
| [isTransformChanged()](#isTransformChanged--) | Получает значение, указывающее, были ли преобразования изменены каким-либо образом. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Умножает Aspose.Imaging.Matrix, представляющий локальное геометрическое преобразование этого LinearGradientBrush, на указанный Aspose.Imaging.Matrix, предварительно добавляя указанный Aspose.Imaging.Matrix. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Умножает Aspose.Imaging.Matrix, представляющий локальное геометрическое преобразование этого LinearGradientBrush, на указанный Aspose.Imaging.Matrix в указанном порядке. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Сбрасывает свойство TransformBrush.Transform к единичному преобразованию. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Поворачивает локальное геометрическое преобразование на указанную величину. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке. |
| [setAngle(float value)](#setAngle-float-) | Устанавливает угол градиента. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Устанавливает значение, указывающее, изменяется ли LinearGradientBrushBase.Angle во время преобразований с этим LinearGradientBrushBase. |
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Устанавливает объект  Aspose.Imaging.Blend , который задаёт позиции и коэффициенты, определяющие пользовательское затухание градиента. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Создаёт линейный градиент с центральным цветом и линейным затуханием к одному цвету с обеих сторон. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Создаёт линейный градиент с центральным цветом и линейным затуханием к одному цвету с обеих сторон. |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | Устанавливает конечный цвет градиента. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Устанавливает значение, указывающее, включена ли гамма‑коррекция для этого LinearGradientBrushBase. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Устанавливает объект com.aspose.psd.ColorBlend, определяющий многокрасочный линейный градиент. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | Устанавливает начальный и конечный цвета градиента. |
| [setOpacity(float value)](#setOpacity-float-) | Устанавливает непрозрачность кисти. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Устанавливает прямоугольную область, определяющую начальную и конечную точки градиента. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Создаёт затухание градиента, основанное на колоколообразной кривой. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Создаёт затухание градиента, основанное на колоколообразной кривой. |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | Устанавливает начальный цвет градиента. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Получает или задаёт копию Aspose.Imaging.Matrix, определяющую локальное геометрическое преобразование для этого TransformBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Получает или задаёт перечисление Aspose.Imaging.WrapMode, указывающее режим обтекания для этого TransformBrush. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Перемещает локальное геометрическое преобразование на указанные размеры. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Инициализирует новый экземпляр класса  LinearGradientBrush  с параметрами по умолчанию. Начальный цвет — чёрный, конечный цвет — белый, угол — 45 градусов, а прямоугольник расположен в (0,0) размером (1,1).

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Инициализирует новый экземпляр класса  LinearGradientBrush  с указанными точками и цветами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Структура **Aspose.Imaging.Point**, представляющая начальную точку линейного градиента. |
| point2 | [Point](../../com.aspose.psd/point) | Структура **Aspose.Imaging.Point**, представляющая конечную точку линейного градиента. |
| color1 | [Color](../../com.aspose.psd/color) | Структура  com.aspose.psd.Color  представляет начальный цвет линейного градиента. |
| color2 | [Color](../../com.aspose.psd/color) | Структура  com.aspose.psd.Color  представляет конечный цвет линейного градиента. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Инициализирует новый экземпляр класса  LinearGradientBrush  с указанными точками и цветами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Структура **Aspose.Imaging.PointF**, представляющая начальную точку линейного градиента. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Структура **Aspose.Imaging.PointF**, представляющая конечную точку линейного градиента. |
| color1 | [Color](../../com.aspose.psd/color) | Структура  com.aspose.psd.Color  представляет начальный цвет линейного градиента. |
| color2 | [Color](../../com.aspose.psd/color) | Структура  com.aspose.psd.Color  представляет конечный цвет линейного градиента. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Инициализирует новый экземпляр класса  LinearGradientBrush  на основе прямоугольника, начального и конечного цветов и угла ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура **Aspose.Imaging.RectangleF**, задающая границы линейного градиента. |
| color1 | [Color](../../com.aspose.psd/color) | Структура  com.aspose.psd.Color  представляет начальный цвет градиента. |
| color2 | [Color](../../com.aspose.psd/color) | Структура  com.aspose.psd.Color  представляет конечный цвет градиента. |
| angle | float | Угол, измеряемый в градусах по часовой стрелке от оси X, линии ориентации градиента. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Инициализирует новый экземпляр класса  LinearGradientBrush  на основе прямоугольника, начального и конечного цветов и угла ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура **Aspose.Imaging.RectangleF**, задающая границы линейного градиента. |
| color1 | [Color](../../com.aspose.psd/color) | Структура  com.aspose.psd.Color  представляет начальный цвет градиента. |
| color2 | [Color](../../com.aspose.psd/color) | Структура  com.aspose.psd.Color  представляет конечный цвет градиента. |
| angle | float | Угол, измеряемый в градусах по часовой стрелке от оси X, линии ориентации градиента. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Инициализирует новый экземпляр класса  LinearGradientBrush  на основе прямоугольника, начального и конечного цветов и угла ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура **Aspose.Imaging.RectangleF**, задающая границы линейного градиента. |
| color1 | [Color](../../com.aspose.psd/color) | Структура  com.aspose.psd.Color  представляет начальный цвет градиента. |
| color2 | [Color](../../com.aspose.psd/color) | Структура  com.aspose.psd.Color  представляет конечный цвет градиента. |
| angle | float | Угол, измеряемый в градусах по часовой стрелке от оси X, линии ориентации градиента. |
| isAngleScalable | boolean | Если установить значение  true , угол изменяется при трансформациях с этим  LinearGradientBrush . |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Инициализирует новый экземпляр класса  LinearGradientBrush  на основе прямоугольника, начального и конечного цветов и угла ориентации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура **Aspose.Imaging.RectangleF**, задающая границы линейного градиента. |
| color1 | [Color](../../com.aspose.psd/color) | Структура  com.aspose.psd.Color  представляет начальный цвет градиента. |
| color2 | [Color](../../com.aspose.psd/color) | Структура  com.aspose.psd.Color  представляет конечный цвет градиента. |
| angle | float | Угол, измеряемый в градусах по часовой стрелке от оси X, линии ориентации градиента. |
| isAngleScalable | boolean | Если установить значение  true , угол изменяется при трансформациях с этим  LinearGradientBrush . |

### close() {#close--}
```
public void close()
```


Реализует интерфейс Closable и может использоваться в операторе try-with-resources, начиная с JDK 1.7. Этот метод просто вызывает метод dispose.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Создаёт глубокую копию текущего Brush.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает текущий экземпляр.

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


Получает угол градиента.

**Returns:**
float — угол градиента.
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Получает объект  Aspose.Imaging.Blend , который задаёт позиции и коэффициенты, определяющие пользовательское затухание градиента.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Получает значение, указывающее, освобожден ли этот экземпляр.

**Returns:**
boolean -  true  если освобождено; иначе,  false .
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Получает конечный цвет градиента.

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Получает значение, указывающее, включена ли гамма‑коррекция для этого LinearGradientBrushBase.

**Returns:**
boolean — значение true, если для этого **LinearGradientBrushBase** включена гамма‑коррекция; иначе false.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Получает объект com.aspose.psd.ColorBlend, определяющий многокрасочный линейный градиент.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Получает начальный и конечный цвета градиента.

**Returns:**
com.aspose.psd.Color[] - Массив из двух структур  Color , представляющих начальный и конечный цвета градиента.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Получает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 — кисть полностью непрозрачна.

**Returns:**
float — значение непрозрачности кисти.
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Получает прямоугольную область, определяющую начальную и конечную точки градиента.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Получает начальный цвет градиента.

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Получает или задаёт копию Aspose.Imaging.Matrix, определяющую локальное геометрическое преобразование для этого TransformBrush.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Получает или задаёт перечисление Aspose.Imaging.WrapMode, указывающее режим обтекания для этого TransformBrush.

**Returns:**
int — **Aspose.Imaging.WrapMode**, определяющий способ заполнения, выполненного этим **TransformBrush**, при тайлинге.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Получает значение, указывающее, изменяется ли LinearGradientBrushBase.Angle во время преобразований с этим LinearGradientBrushBase.

**Returns:**
boolean — true, если **LinearGradientBrushBase.Angle** изменяется во время преобразований с этим **LinearGradientBrushBase**; иначе false.
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например, установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+.

Значение: True, если преобразование было изменено; иначе false.

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Умножает Aspose.Imaging.Matrix, представляющий локальное геометрическое преобразование этого LinearGradientBrush, на указанный Aspose.Imaging.Matrix, предварительно добавляя указанный Aspose.Imaging.Matrix.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Матрица **Aspose.Imaging.Matrix**, на которую умножается геометрическое преобразование. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Умножает Aspose.Imaging.Matrix, представляющий локальное геометрическое преобразование этого LinearGradientBrush, на указанный Aspose.Imaging.Matrix в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Матрица **Aspose.Imaging.Matrix**, на которую умножается геометрическое преобразование. |
| порядок | int | **Aspose.Imaging.MatrixOrder**, указывающий порядок умножения двух матриц. |

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


Сбрасывает свойство TransformBrush.Transform к единичному преобразованию.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Вращает локальное геометрическое преобразование на указанную величину. Этот метод добавляет вращение в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |
| порядок | int | **Aspose.Imaging.MatrixOrder**, указывающий, добавлять ли матрицу вращения в конец или в начало. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Величина, на которую масштабировать преобразование по оси x. |
| sy | float | Величина, на которую масштабировать преобразование по оси y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Величина, на которую масштабировать преобразование по оси x. |
| sy | float | Величина, на которую масштабировать преобразование по оси y. |
| порядок | int | Объект  Aspose.Imaging.MatrixOrder , который указывает, добавлять ли матрицу масштабирования в конец или в начало. |

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Устанавливает угол градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Угол градиента. |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Устанавливает значение, указывающее, изменяется ли LinearGradientBrushBase.Angle во время преобразований с этим LinearGradientBrushBase.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | true, если LinearGradientBrushBase.Angle изменяется во время преобразований с этим LinearGradientBrushBase; иначе false. |

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


Устанавливает объект  Aspose.Imaging.Blend , который задаёт позиции и коэффициенты, определяющие пользовательское затухание градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | Объект  Aspose.Imaging.Blend , представляющий пользовательское затухание градиента. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Создаёт линейный градиент с центральным цветом и линейным затуханием к одному цвету с обеих сторон.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| focus | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Создаёт линейный градиент с центральным цветом и линейным затуханием к одному цвету с обеих сторон.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| focus | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |
| scale | float | Значение от 0 до1, указывающее, насколько быстро цвета переходят от начального цвета к  focus  (конечный цвет) |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


Устанавливает конечный цвет градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Конечный цвет градиента. |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Устанавливает значение, указывающее, включена ли гамма‑коррекция для этого LinearGradientBrushBase.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Значение равно true, если для этого LinearGradientBrushBase включена гамма‑коррекция; иначе false. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Устанавливает объект com.aspose.psd.ColorBlend, определяющий многокрасочный линейный градиент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | Объект  com.aspose.psd.ColorBlend , определяющий многокрасочный линейный градиент. |

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


Устанавливает начальный и конечный цвета градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Массив из двух структур  Color , представляющих начальный и конечный цвета градиента. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Устанавливает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 — кисть полностью непрозрачна.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Значение непрозрачности кисти. |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Устанавливает прямоугольную область, определяющую начальную и конечную точки градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  com.aspose.psd.RectangleF , определяющая начальную и конечную точки градиента. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Создаёт затухание градиента, основанное на колоколообразной кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| focus | float | Значение от 0 до 1, указывающее центр градиента (точка, где начальный и конечный цвета смешиваются поровну). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Создаёт затухание градиента, основанное на колоколообразной кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| focus | float | Значение от 0 до 1, указывающее центр градиента (точка, где градиент состоит только из конечного цвета). |
| scale | float | Значение от 0 до 1, указывающее, насколько быстро цвета затухают от  focus . |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


Устанавливает начальный цвет градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Начальный цвет градиента. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Получает или задаёт копию Aspose.Imaging.Matrix, определяющую локальное геометрическое преобразование для этого TransformBrush.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Получает или задаёт перечисление Aspose.Imaging.WrapMode, указывающее режим обтекания для этого TransformBrush.

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

