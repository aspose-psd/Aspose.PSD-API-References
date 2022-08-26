---
title: PathGradientBrush
second_title: Справочник по Aspose.PSD для .NET API
description: ИнкапсулируетBrush../aspose.psd/brush объект с градиентом. Этот класс не может быть унаследован.
type: docs
weight: 170
url: /ru/net/aspose.psd.brushes/pathgradientbrush/
---
## PathGradientBrush class

Инкапсулирует[`Brush`](../../aspose.psd/brush) объект с градиентом. Этот класс не может быть унаследован.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PathGradientBrush](pathgradientbrush#constructor)(GraphicsPath) | Инициализирует новый экземпляр[`PathGradientBrush`](../pathgradientbrush) класс с указанным путем. |
| [PathGradientBrush](pathgradientbrush#constructor_1)(PointF[]) | Инициализирует новый экземпляр[`PathGradientBrush`](../pathgradientbrush) класс с указанными баллами. |
| [PathGradientBrush](pathgradientbrush#constructor_3)(Point[]) | Инициализирует новый экземпляр[`PathGradientBrush`](../pathgradientbrush) класс с указанными баллами. |
| [PathGradientBrush](pathgradientbrush#constructor_2)(PointF[], WrapMode) | Инициализирует новый экземпляр[`PathGradientBrush`](../pathgradientbrush) class с указанными точками и режимом переноса. |
| [PathGradientBrush](pathgradientbrush#constructor_4)(Point[], WrapMode) | Инициализирует новый экземпляр[`PathGradientBrush`](../pathgradientbrush) class с указанными точками и режимом переноса. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend) { get; set; } | Получает или задает[`Blend`](../../aspose.psd/blend) который указывает позиции и факторы, которые определяют пользовательский спад для градиента. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor) { get; set; } | Получает или задает цвет в центре градиента контура. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Получает или задает центральную точку градиента пути. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales) { get; set; } | Получает или задает точку фокусировки для спада градиента. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath) { get; } | Получает графический путь, на котором построена эта кисть. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged) { get; } | Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.psd/brush/opacity) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видна, значение 1 означает, что кисть полностью непрозрачна. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints) { get; } | Получает точки пути, на которых построена эта кисть. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors) { get; set; } | Получает или задает массив цветов, соответствующих точкам пути,[`PathGradientBrush`](../pathgradientbrush) заполняет. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform) { get; set; } | Получает или устанавливает копию[`Matrix`](../../aspose.psd/matrix) который определяет локальное геометрическое преобразование для этого[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode) { get; set; } | Получает или задает[`WrapMode`](../../aspose.psd/wrapmode) перечисление, указывающее режим переноса для этого[`TransformBrush`](../transformbrush) . |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone)() | Создает новый глубокий клон текущего[`Brush`](../../aspose.psd/brush) . |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform)(Matrix) | Умножает[`Matrix`](../../aspose.psd/matrix) который представляет собой локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush) указанным[`Matrix`](../../aspose.psd/matrix) путем добавления указанного[`Matrix`](../../aspose.psd/matrix) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Умножает[`Matrix`](../../aspose.psd/matrix) который представляет собой локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush) указанным[`Matrix`](../../aspose.psd/matrix) в указанном порядке. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform)() | Сбрасывает[`Transform`](../transformbrush/transform) свойство к личности. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет поворот к преобразованию. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования перед преобразованием. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | Создает градиент с центральным цветом и линейным переходом к одному окружающему цвету. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | Создает градиент с центральным цветом и линейным спадом для каждого окружающего цвета. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape)(float) | Создает градиентную кисть, которая меняет цвет, начиная с центра пути наружу и заканчивая его границей. Переход от одного цвета к другому основан на колоколообразной кривой. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | Создает градиентную кисть, которая меняет цвет, начиная с центра пути наружу и заканчивая его границей. Переход от одного цвета к другому основан на колоколообразной кривой. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float) | Преобразует локальное геометрическое преобразование по указанным размерам. Этот метод добавляет перевод к transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Примечания

Центральный цвет по умолчанию белый. Пользователь может изменить это значение в любое время позже.

Массив объемных цветов по умолчанию инициализируется одним элементом, содержащим белый цвет. Цвета объемного звучания можно изменить позже, однако при настройке цветов объемного звучания требуется хотя бы один элемент.

См.[`Blend`](./blend) для получения более подробной информации о его инициализации.

### Смотрите также

* class [PathGradientBrushBase](../pathgradientbrushbase)
* пространство имен [Aspose.PSD.Brushes](../../aspose.psd.brushes)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
