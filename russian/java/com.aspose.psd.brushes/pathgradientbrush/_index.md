---
title: "PathGradientBrush"
second_title: "Aspose.PSD for Java API Справочник"
description: "Инкапсулирует объект Aspose.Imaging.Brush с градиентом."
type: docs
weight: 14
url: /ru/java/com.aspose.psd.brushes/pathgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Инкапсулирует объект  Aspose.Imaging.Brush  с градиентом. Этот класс не может быть унаследован.

Цвет центра по умолчанию белый. Пользователь может изменить это значение в любой момент позже.

Массив окружающих цветов инициализируется одним элементом, содержащим белый цвет, по умолчанию. Окружающие цвета могут быть изменены позже, однако при настройке массива окружающих цветов требуется как минимум один элемент.

Смотрите  Blend  для получения более подробной информации об его инициализации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.psd.PointF---) | Инициализирует новый экземпляр класса  PathGradientBrush  с указанными точками. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.PointF---int-) | Инициализирует новый экземпляр класса  PathGradientBrush  с указанными точками и режимом обтекания. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.psd.Point---) | Инициализирует новый экземпляр класса  PathGradientBrush  с указанными точками. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.Point---int-) | Инициализирует новый экземпляр класса  PathGradientBrush  с указанными точками и режимом обтекания. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.psd.GraphicsPath-) | Инициализирует новый экземпляр класса  PathGradientBrush  с указанным путем. |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [deepClone()](#deepClone--) | Создаёт глубокую копию текущего Brush. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlend()](#getBlend--) | Получает объект  Aspose.Imaging.Blend , который задаёт позиции и коэффициенты, определяющие пользовательское затухание градиента. |
| [getCenterColor()](#getCenterColor--) | Получает цвет в центре градиента пути. |
| [getCenterPoint()](#getCenterPoint--) | Получает или задает центральную точку градиента по пути. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getFocusScales()](#getFocusScales--) | Получает точку фокуса для падения градиента. |
| [getGraphicsPath()](#getGraphicsPath--) | Получает графический путь, на основе которого построена эта кисть. |
| [getInterpolationColors()](#getInterpolationColors--) | Получает объект com.aspose.psd.ColorBlend, определяющий многокрасочный линейный градиент. |
| [getOpacity()](#getOpacity--) | Получает непрозрачность кисти. |
| [getPathPoints()](#getPathPoints--) | Получает точки пути, на котором построена эта кисть. |
| [getSurroundColors()](#getSurroundColors--) | Получает массив цветов, соответствующих точкам пути, который заполняет этот  PathGradientBrush . |
| [getTransform()](#getTransform--) | Получает или задаёт копию Aspose.Imaging.Matrix, определяющую локальное геометрическое преобразование для этого TransformBrush. |
| [getWrapMode()](#getWrapMode--) | Получает или задаёт перечисление Aspose.Imaging.WrapMode, указывающее режим обтекания для этого TransformBrush. |
| [hashCode()](#hashCode--) |  |
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
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Устанавливает объект  Aspose.Imaging.Blend , который задаёт позиции и коэффициенты, определяющие пользовательское затухание градиента. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Создаёт градиент с центральным цветом и линейным переходом к одному окружающему цвету. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Создаёт градиент с центральным цветом и линейным переходом к каждому окружающему цвету. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.psd.Color-) | Устанавливает цвет в центре градиента пути. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | Получает или задает центральную точку градиента по пути. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | Получает или задает точку фокуса для падения градиента. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Устанавливает объект com.aspose.psd.ColorBlend, определяющий многокрасочный линейный градиент. |
| [setOpacity(float value)](#setOpacity-float-) | Устанавливает непрозрачность кисти. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Создаёт кисть градиента, меняющую цвет, начиная от центра пути и наружу до границы пути. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Создаёт кисть градиента, меняющую цвет, начиная от центра пути и наружу до границы пути. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.psd.Color---) | Устанавливает массив цветов, соответствующих точкам пути, который заполняет этот  PathGradientBrush . |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Получает или задаёт копию Aspose.Imaging.Matrix, определяющую локальное геометрическое преобразование для этого TransformBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Получает или задаёт перечисление Aspose.Imaging.WrapMode, указывающее режим обтекания для этого TransformBrush. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Перемещает локальное геометрическое преобразование на указанные размеры. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.psd.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Инициализирует новый экземпляр класса  PathGradientBrush  с указанными точками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  Aspose.Imaging.PointF , представляющих точки, образующие вершины пути. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Инициализирует новый экземпляр класса  PathGradientBrush  с указанными точками и режимом обтекания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  Aspose.Imaging.PointF , представляющих точки, образующие вершины пути. |
| wrapMode | int | Тип  Aspose.Imaging.WrapMode , который определяет, как заполняющие элементы, нарисованные этой  PathGradientBrush , размещаются плиткой. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.psd.Point---}
```
public PathGradientBrush(Point[] points)
```


Инициализирует новый экземпляр класса  PathGradientBrush  с указанными точками.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур  Aspose.Imaging.Point , представляющих точки, образующие вершины пути. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Инициализирует новый экземпляр класса  PathGradientBrush  с указанными точками и режимом обтекания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур  Aspose.Imaging.Point , представляющих точки, образующие вершины пути. |
| wrapMode | int | Тип  Aspose.Imaging.WrapMode , который определяет, как заполняющие элементы, нарисованные этой  PathGradientBrush , размещаются плиткой. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Инициализирует новый экземпляр класса  PathGradientBrush  с указанным путем.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект  GraphicsPath , определяющий область, заполняемую этой  PathGradientBrush . |

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Получает объект  Aspose.Imaging.Blend , который задаёт позиции и коэффициенты, определяющие пользовательское затухание градиента.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Получает цвет в центре градиента пути.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  that represents the color at the center of the path gradient.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Получает или задает центральную точку градиента по пути.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the center point of the path gradient.
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
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Получает точку фокуса для падения градиента.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Получает графический путь, на основе которого построена эта кисть.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Получает объект com.aspose.psd.ColorBlend, определяющий многокрасочный линейный градиент.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Получает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 — кисть полностью непрозрачна.

**Returns:**
float — значение непрозрачности кисти.
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Получает точки пути, на котором построена эта кисть.

**Returns:**
com.aspose.psd.PointF[] — точки пути.
### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Получает массив цветов, соответствующих точкам пути, который заполняет этот  PathGradientBrush .

**Returns:**
com.aspose.psd.Color[] - Массив структур  com.aspose.psd.Color , представляющих цвета, связанные с каждой точкой пути, который заполняет этот  PathGradientBrush .
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


Создаёт градиент с центральным цветом и линейным переходом к одному окружающему цвету.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| focus | float | Значение от 0 до 1, указывающее, где вдоль любого радиуса от центра пути до его границы центральный цвет будет иметь наибольшую интенсивность. Значение 1 (по умолчанию) размещает наибольшую интенсивность в центре пути. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Создаёт градиент с центральным цветом и линейным переходом к каждому окружающему цвету.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| focus | float | Значение от 0 до 1, указывающее, где вдоль любого радиуса от центра пути до его границы центральный цвет будет иметь наибольшую интенсивность. Значение 1 (по умолчанию) размещает наибольшую интенсивность в центре пути. |
| scale | float | Значение от 0 до 1, определяющее максимальную интенсивность центрального цвета, смешиваемого с цветом границы. Значение 1 приводит к максимально возможной интенсивности центрального цвета и является значением по умолчанию. |

### setCenterColor(Color value) {#setCenterColor-com.aspose.psd.Color-}
```
public void setCenterColor(Color value)
```


Устанавливает цвет в центре градиента пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Объект  com.aspose.psd.Color , представляющий цвет в центре градиента пути. |

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


Получает или задает центральную точку градиента по пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Объект  Aspose.Imaging.PointF , представляющий центральную точку градиента пути. |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


Получает или задает точку фокуса для падения градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Объект  Aspose.Imaging.PointF , представляющий точку фокуса для падения градиента. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Устанавливает объект com.aspose.psd.ColorBlend, определяющий многокрасочный линейный градиент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | Объект  com.aspose.psd.ColorBlend , определяющий многокрасочный линейный градиент. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Устанавливает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 — кисть полностью непрозрачна.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Значение непрозрачности кисти. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Создаёт кисть градиента, меняющую цвет, начиная от центра пути и наружу до границы пути. Переход от одного цвета к другому основан на колоколообразной кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| focus | float | Значение от 0 до 1, указывающее, где вдоль любого радиуса от центра пути до его границы центральный цвет будет иметь наибольшую интенсивность. Значение 1 (по умолчанию) размещает наибольшую интенсивность в центре пути. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Создаёт кисть градиента, меняющую цвет, начиная от центра пути и наружу до границы пути. Переход от одного цвета к другому основан на колоколообразной кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| focus | float | Значение от 0 до 1, указывающее, где вдоль любого радиуса от центра пути до его границы центральный цвет будет иметь наибольшую интенсивность. Значение 1 (по умолчанию) размещает наибольшую интенсивность в центре пути. |
| scale | float | Значение от 0 до 1, определяющее максимальную интенсивность центрального цвета, смешиваемого с цветом границы. Значение 1 приводит к максимально возможной интенсивности центрального цвета и является значением по умолчанию. |

### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.psd.Color---}
```
public void setSurroundColors(Color[] value)
```


Устанавливает массив цветов, соответствующих точкам пути, который заполняет этот  PathGradientBrush .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Массив структур  com.aspose.psd.Color , представляющих цвета, связанные с каждой точкой пути, который заполняет этот  PathGradientBrush . |

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

