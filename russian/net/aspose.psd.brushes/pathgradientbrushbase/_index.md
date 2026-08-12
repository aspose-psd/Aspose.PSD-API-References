---
title: "Класс PathGradientBrushBase"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Brushes.PathGradientBrushBase. Представляет кисть с базовой функциональностью градиента по пути."
type: docs
weight: 180
url: /ru/net/aspose.psd.brushes/pathgradientbrushbase/
---
{{< psd/tize >}}
## PathGradientBrushBase class

Представляет [`Brush`](../../aspose.psd/brush/) с базовой функциональностью градиента по пути.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Свойства

| Имя | Описание |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Получает или задает центральную точку градиента по пути. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Получает или задает точку фокуса для падения градиента. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Получает графический путь, на котором построена эта кисть. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Получает значение, указывающее, были ли трансформации изменены каким-либо образом. Например, установка матрицы трансформации или вызов любого из методов, изменяющих матрицу трансформации. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Получает точки пути, на котором построена эта кисть. |
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
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод предварительно добавляет трансляцию к преобразованию. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Смещает локальное геометрическое преобразование на указанные размеры в заданном порядке. |

## Примечания

Обратите внимание, что при создании класса `PathGradientBrushBase` его следует инициализировать как минимум двумя точками. Внутренний путь всегда будет замкнутой фигурой, последняя точка соединяется с первой. Эта форма заполняется этим `PathGradientBrushBase`. Реализация GDI+ генерирует OutOfMemoryException при передаче пустых массивов или наборов точек с одинаковыми координатами. `PathGradientBrushBase` генерирует исключение, если массив точек содержит менее двух точек; в этом случае бросается ArgumentException, а не OutOfMemoryException, когда массив точек недопустим. Центральная точка рассчитывается как центр масс переданных точек по умолчанию. Пользователь может изменить эту точку позже. Масштаб фокуса по умолчанию — пустая точка (0.0, 0.0).

### См. также

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


