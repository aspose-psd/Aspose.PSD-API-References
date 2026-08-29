---
title: "Класс TransformBrush"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Brushes.TransformBrush. Кисть с возможностями трансформации"
type: docs
weight: 220
url: /ru/net/aspose.psd.brushes/transformbrush/
---
{{< psd/tize >}}
## TransformBrush class

Кисть [`Brush`](../../aspose.psd/brush/) с возможностями трансформации.

```csharp
public abstract class TransformBrush : Brush
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Получает значение, указывающее, были ли трансформации изменены каким-либо образом. Например, установка матрицы трансформации или вызов любого из методов, изменяющих матрицу трансформации. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Получает или задает копию [`Matrix`](../../aspose.psd/matrix/), определяющую локальное геометрическое преобразование для этого `TransformBrush`. |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Получает или задает перечисление [`WrapMode`](../../aspose.psd/wrapmode/), указывающее режим обтекания для этого `TransformBrush`. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Создает новый глубокий клон текущего [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform)(Matrix) | Умножает [`Matrix`](../../aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [`LinearGradientBrush`](../lineargradientbrush/), на указанную [`Matrix`](../../aspose.psd/matrix/), предварительно добавляя указанную [`Matrix`](../../aspose.psd/matrix/). |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Умножает [`Matrix`](../../aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [`LinearGradientBrush`](../lineargradientbrush/), на указанную [`Matrix`](../../aspose.psd/matrix/) в заданном порядке. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Сбрасывает свойство [`Transform`](./transform/) к единичному. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод предварительно добавляет вращение к преобразованию. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанную величину в заданном порядке. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты. Этот метод предварительно добавляет матрицу масштабирования к преобразованию. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в заданном порядке. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform)(float, float) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Смещает локальное геометрическое преобразование на указанные размеры в заданном порядке. |

### См. также

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


