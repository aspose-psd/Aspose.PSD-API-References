---
title: "Класс TextureBrush"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Brushes.TextureBrush. Каждое свойство класса TextureBrush является объектом Brush, который использует изображение для заполнения внутренней части фигуры. Этот класс не может быть наследован"
type: docs
weight: 210
url: /ru/net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

Каждое свойство класса `TextureBrush` является объектом [`Brush`](../../aspose.psd/brush/), который использует изображение для заполнения внутренней части фигуры. Этот класс не может быть наследован.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Инициализирует новый экземпляр класса `TextureBrush`, использующий указанное изображение. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Инициализирует новый экземпляр класса `TextureBrush`, использующий указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Инициализирует новый экземпляр класса `TextureBrush`, использующий указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Инициализирует новый экземпляр класса `TextureBrush`, использующий указанное изображение и режим обтекания. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Инициализирует новый экземпляр класса `TextureBrush`, использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Инициализирует новый экземпляр класса `TextureBrush`, использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Инициализирует новый экземпляр класса `TextureBrush`, использующий указанное изображение, режим обтекания и ограничивающий прямоугольник. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Инициализирует новый экземпляр класса `TextureBrush`, использующий указанное изображение, режим обтекания и ограничивающий прямоугольник. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Получает объект [`Image`](../../aspose.psd/image/), связанный с этим объектом `TextureBrush`. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Получает [`ImageAttributes`](./imageattributes/), связанные с этим `TextureBrush`. |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Получает [`Rectangle`](../../aspose.psd/rectangle/), связанный с этим `TextureBrush`. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Получает значение, указывающее, были ли трансформации изменены каким-либо образом. Например, установка матрицы трансформации или вызов любого из методов, изменяющих матрицу трансформации. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |
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

### См. также

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


