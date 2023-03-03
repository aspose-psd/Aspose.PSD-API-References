---
title: Class LinearGradientBrushBase
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.Brushes.LinearGradientBrushBase сорт. ПредставляетBrush с возможностями градиента и соответствующими свойствами.
type: docs
weight: 150
url: /ru/net/aspose.psd.brushes/lineargradientbrushbase/
---
## LinearGradientBrushBase class

Представляет[`Brush`](../../aspose.psd/brush/) с возможностями градиента и соответствующими свойствами.

```csharp
public abstract class LinearGradientBrushBase : TransformBrush
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Получает или задает угол градиента. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Получает или задает значение, указывающее, включена ли гамма-коррекция для этого`LinearGradientBrushBase` . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Получает или задает значение, указывающее,[`Angle`](./angle/) изменяется во время трансформаций с этим`LinearGradientBrushBase` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видна, значение 1 означает, что кисть полностью непрозрачна. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Получает или задает прямоугольную область, определяющую начальную и конечную точки градиента. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Получает или устанавливает копию[`Matrix`](../../aspose.psd/matrix/) который определяет локальное геометрическое преобразование для этого[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Получает или задает[`WrapMode`](../../aspose.psd/wrapmode/) перечисление, указывающее режим переноса для этого[`TransformBrush`](../transformbrush/) . |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Создает новый глубокий клон текущего[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Удаляет текущий экземпляр. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Умножает[`Matrix`](../../aspose.psd/matrix/) который представляет собой локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush/) указанным[`Matrix`](../../aspose.psd/matrix/) путем добавления указанного[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Умножает[`Matrix`](../../aspose.psd/matrix/) который представляет собой локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush/) указанным[`Matrix`](../../aspose.psd/matrix/) в указанном порядке. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Сбрасывает[`Transform`](../transformbrush/transform/) свойство к личности. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет поворот к преобразованию. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования перед преобразованием. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Преобразует локальное геометрическое преобразование по указанным размерам. Этот метод добавляет перевод к transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Смотрите также

* class [TransformBrush](../transformbrush/)
* пространство имен [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* сборка [Aspose.PSD](../../)


