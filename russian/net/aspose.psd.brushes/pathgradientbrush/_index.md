---
title: "Класс PathGradientBrush"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Brushes.PathGradientBrush. Инкапсулирует объект кисти с градиентом. Этот класс не может быть наследован."
type: docs
weight: 170
url: /ru/net/aspose.psd.brushes/pathgradientbrush/
---
{{< psd/tize >}}
## PathGradientBrush class

Инкапсулирует объект [`Brush`](../../aspose.psd/brush/) с градиентом. Этот класс не может быть наследован.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | Инициализирует новый экземпляр класса `PathGradientBrush` с указанным путем. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | Инициализирует новый экземпляр класса `PathGradientBrush` с указанными точками. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | Инициализирует новый экземпляр класса `PathGradientBrush` с указанными точками. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | Инициализирует новый экземпляр класса `PathGradientBrush` с указанными точками и режимом обтекания. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | Инициализирует новый экземпляр класса `PathGradientBrush` с указанными точками и режимом обтекания. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | Получает или задает [`Blend`](../../aspose.psd/blend/), который определяет позиции и коэффициенты, задающие пользовательское затухание градиента. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | Получает или задает цвет в центре градиента пути. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Получает или задает центральную точку градиента по пути. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Получает или задает точку фокуса для падения градиента. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Получает графический путь, на котором построена эта кисть. |
| [InterpolationColors](../../aspose.psd.brushes/pathgradientbrush/interpolationcolors/) { get; set; } | Получает или задаёт [`ColorBlend`](../../aspose.psd/colorblend/), определяющий многокрасочный линейный градиент. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Получает значение, указывающее, были ли трансформации изменены каким-либо образом. Например, установка матрицы трансформации или вызов любого из методов, изменяющих матрицу трансформации. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Получает точки пути, на котором построена эта кисть. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | Получает или задает массив цветов, соответствующих точкам пути, который заполняет этот `PathGradientBrush`. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Получает или задает копию [`Matrix`](../../aspose.psd/matrix/), определяющую локальное геометрическое преобразование для этого [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Получает или задает перечисление [`WrapMode`](../../aspose.psd/wrapmode/), указывающее режим обтекания для этого [`TransformBrush`](../transformbrush/). |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Создает новый глубокий клон текущего [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Умножает [`Matrix`](../../aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [`LinearGradientBrush`](../lineargradientbrush/), на указанную [`Matrix`](../../aspose.psd/matrix/), предварительно добавляя указанную [`Matrix`](../../aspose.psd/matrix/). |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Умножает [`Matrix`](../../aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [`LinearGradientBrush`](../lineargradientbrush/), на указанную [`Matrix`](../../aspose.psd/matrix/) в заданном порядке. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Сбрасывает свойство [`Transform`](../transformbrush/transform/) к единичному. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод предварительно добавляет вращение к преобразованию. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанную величину в заданном порядке. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты. Этот метод предварительно добавляет матрицу масштабирования к преобразованию. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в заданном порядке. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Создает градиент с центральным цветом и линейным спадом к одному окружающему цвету. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Создает градиент с центральным цветом и линейным спадом к каждому окружающему цвету. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Создает кисть градиента, меняющую цвет, начиная от центра пути к его границе. Переход от одного цвета к другому основан на колоколообразной кривой. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Создает кисть градиента, меняющую цвет, начиная от центра пути к его границе. Переход от одного цвета к другому основан на колоколообразной кривой. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Смещает локальное геометрическое преобразование на указанные размеры в заданном порядке. |

## Примечания

Центральный цвет по умолчанию белый. Пользователь может изменить это значение в любой момент позже.

Массив окружающих цветов инициализируется одним элементом, содержащим белый цвет, по умолчанию. Окружающие цвета могут быть изменены позже, однако при настройке требуется как минимум один элемент.

Смотрите [`Blend`](./blend/) для получения более подробной информации об его инициализации.

### См. также

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


