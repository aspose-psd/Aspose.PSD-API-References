---
title: Class TransformBrush
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.Brushes.TransformBrush сорт. АBrush с возможностями трансформации.
type: docs
weight: 220
url: /ru/net/aspose.psd.brushes/transformbrush/
---
## TransformBrush class

А[`Brush`](../../aspose.psd/brush/) с возможностями трансформации.

```csharp
public abstract class TransformBrush : Brush
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видна, значение 1 означает, что кисть полностью непрозрачна. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Получает или устанавливает копию[`Matrix`](../../aspose.psd/matrix/) который определяет локальное геометрическое преобразование для этого`TransformBrush` . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Получает или задает[`WrapMode`](../../aspose.psd/wrapmode/) перечисление, указывающее режим переноса для этого`TransformBrush` . |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Создает новый глубокий клон текущего[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Удаляет текущий экземпляр. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform)(Matrix) | Умножает[`Matrix`](../../aspose.psd/matrix/) который представляет собой локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush/) указанным[`Matrix`](../../aspose.psd/matrix/) путем добавления указанного[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Умножает[`Matrix`](../../aspose.psd/matrix/) который представляет собой локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush/) указанным[`Matrix`](../../aspose.psd/matrix/) в указанном порядке. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Сбрасывает[`Transform`](./transform/) свойство к личности. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет поворот к преобразованию. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования перед преобразованием. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform)(float, float) | Преобразует локальное геометрическое преобразование по указанным размерам. Этот метод добавляет перевод к transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Смотрите также

* class [Brush](../../aspose.psd/brush/)
* пространство имен [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* сборка [Aspose.PSD](../../)


