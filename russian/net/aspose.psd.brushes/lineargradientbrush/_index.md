---
title: LinearGradientBrush
second_title: Справочник по Aspose.PSD для .NET API
description: ИнкапсулируетBrush../aspose.psd/brushс линейным градиентом. Этот класс не может быть унаследован.
type: docs
weight: 140
url: /ru/net/aspose.psd.brushes/lineargradientbrush/
---
## LinearGradientBrush class

Инкапсулирует[`Brush`](../../aspose.psd/brush)с линейным градиентом. Этот класс не может быть унаследован.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush#constructor)() | Инициализирует новый экземпляр класса[`LinearGradientBrush`](../lineargradientbrush)с параметрами по умолчанию. Начальный цвет черный, конечный цвет белый, угол 45 градусов и прямоугольник расположен в (0,0) с размером (1,1). |
| [LinearGradientBrush](lineargradientbrush#constructor_1)(Point, Point, Color, Color) | Инициализирует новый экземпляр класса[`LinearGradientBrush`](../lineargradientbrush)с указанными точками и цветами. |
| [LinearGradientBrush](lineargradientbrush#constructor_2)(PointF, PointF, Color, Color) | Инициализирует новый экземпляр класса[`LinearGradientBrush`](../lineargradientbrush)с указанными точками и цветами. |
| [LinearGradientBrush](lineargradientbrush#constructor_3)(Rectangle, Color, Color, float) | Инициализирует новый экземпляр класса[`LinearGradientBrush`](../lineargradientbrush)на основе прямоугольника, начального и конечного цветов и угол ориентации. |
| [LinearGradientBrush](lineargradientbrush#constructor_5)(RectangleF, Color, Color, float) | Инициализирует новый экземпляр класса[`LinearGradientBrush`](../lineargradientbrush)на основе прямоугольника, начального и конечного цветов и угол ориентации. |
| [LinearGradientBrush](lineargradientbrush#constructor_4)(Rectangle, Color, Color, float, bool) | Инициализирует новый экземпляр класса[`LinearGradientBrush`](../lineargradientbrush)на основе прямоугольника, начального и конечного цветов и угол ориентации. |
| [LinearGradientBrush](lineargradientbrush#constructor_6)(RectangleF, Color, Color, float, bool) | Инициализирует новый экземпляр класса[`LinearGradientBrush`](../lineargradientbrush)на основе прямоугольника, начального и конечного цветов и угол ориентации. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle) { get; set; } | Получает или задает угол градиента. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend) { get; set; } | Получает или задает[`Blend`](../../aspose.psd/blend), который указывает позиции и факторы, определяющие пользовательский спад для градиента. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor) { get; set; } | Получает или задает конечный цвет градиента. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | Получает или задает значение, указывающее, включена ли гамма-коррекция для этого[`LinearGradientBrushBase`](../lineargradientbrushbase). |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | Получает или задает значение, указывающее, изменяется ли[`Angle`](../lineargradientbrushbase/angle)во время преобразований с этим[`LinearGradientBrushBase`](../lineargradientbrushbase). |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged) { get; } | Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например, установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.psd/brush/opacity) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видна, значение 1 означает, что кисть полностью непрозрачна. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle) { get; set; } | Получает или задает прямоугольную область, определяющую начальную и конечную точки градиента. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor) { get; set; } | Получает или задает начальный цвет градиента. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform) { get; set; } | Получает или задает копию[`Matrix`](../../aspose.psd/matrix), которая определяет локальное геометрическое преобразование для этого[`TransformBrush`](../transformbrush). |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode) { get; set; } | Получает или задает перечисление[`WrapMode`](../../aspose.psd/wrapmode), указывающее режим переноса для этогоTransformBrush. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone)() | Создает новый глубокий клон текущего[`Brush`](../../aspose.psd/brush). |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform)(Matrix) | Умножает[`Matrix`](../../aspose.psd/matrix), которая представляет локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush)указанным[`Matrix`](../../aspose.psd/matrix)путем добавления указанного[`Matrix`](../../aspose.psd/matrix). |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Умножает[`Matrix`](../../aspose.psd/matrix), которая представляет локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush)указанным[`Matrix`](../../aspose.psd/matrix)в указанном порядке. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform)() | Сбрасывает свойство[`Transform`](../transformbrush/transform)в идентичность. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет поворот к преобразованию. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования к преобразованию. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | Создает линейный градиент с центральным цветом и линейным спадом к одному цвету на обоих концах. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | Создает линейный градиент с центральным цветом и линейным спадом к одному цвету на обоих концах. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape)(float) | Создает спад градиента на основе колоколообразной кривой. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | Создает спад градиента на основе колоколообразной кривой. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float) | Переносит локальное геометрическое преобразование на заданные размеры. Этот метод добавляет перевод к преобразованию. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Смотрите также

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* пространство имен [Aspose.PSD.Brushes](../../aspose.psd.brushes)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
