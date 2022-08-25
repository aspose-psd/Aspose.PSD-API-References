---
title: TextureBrush
second_title: Справочник по Aspose.PSD для .NET API
description: Каждое свойствоTextureBrush./texturebrush класс этоBrush../aspose.psd/brush объект использующий изображение для заполнения внутренней части фигуры. Этот класс не может быть унаследован.
type: docs
weight: 210
url: /ru/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

Каждое свойство[`TextureBrush`](../texturebrush) класс это[`Brush`](../../aspose.psd/brush) объект, использующий изображение для заполнения внутренней части фигуры. Этот класс не может быть унаследован.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextureBrush](texturebrush#constructor)(Image) | Инициализирует новый экземпляр[`TextureBrush`](../texturebrush) класс, использующий указанное изображение. |
| [TextureBrush](texturebrush#constructor_1)(Image, Rectangle) | Инициализирует новый экземпляр[`TextureBrush`](../texturebrush) класс, который использует указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush](texturebrush#constructor_3)(Image, RectangleF) | Инициализирует новый экземпляр[`TextureBrush`](../texturebrush) класс, который использует указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush](texturebrush#constructor_5)(Image, WrapMode) | Инициализирует новый экземпляр[`TextureBrush`](../texturebrush) класс, который использует указанное изображение и режим переноса. |
| [TextureBrush](texturebrush#constructor_2)(Image, Rectangle, ImageAttributes) | Инициализирует новый экземпляр[`TextureBrush`](../texturebrush) класс, который использует указанное изображение, ограничивающий прямоугольник и атрибуты изображения. |
| [TextureBrush](texturebrush#constructor_4)(Image, RectangleF, ImageAttributes) | Инициализирует новый экземпляр[`TextureBrush`](../texturebrush) класс, который использует указанное изображение, ограничивающий прямоугольник и атрибуты изображения. |
| [TextureBrush](texturebrush#constructor_6)(Image, WrapMode, Rectangle) | Инициализирует новый экземпляр[`TextureBrush`](../texturebrush)класс, который использует указанное изображение, режим переноса и ограничивающий прямоугольник. |
| [TextureBrush](texturebrush#constructor_7)(Image, WrapMode, RectangleF) | Инициализирует новый экземпляр[`TextureBrush`](../texturebrush)класс, который использует указанное изображение, режим переноса и ограничивающий прямоугольник. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [Image](../../aspose.psd.brushes/texturebrush/image) { get; } | Получает[`Image`](../../aspose.psd/image) объект, связанный с этим[`TextureBrush`](../texturebrush) объект. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes) { get; } | Получает[`ImageAttributes`](./imageattributes) связанные с этим[`TextureBrush`](../texturebrush) . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle) { get; } | Получает[`Rectangle`](../../aspose.psd/rectangle) связанные с этим[`TextureBrush`](../texturebrush) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged) { get; } | Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.psd/brush/opacity) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видна, значение 1 означает, что кисть полностью непрозрачна. |
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
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float) | Преобразует локальное геометрическое преобразование по указанным размерам. Этот метод добавляет перевод к transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Смотрите также

* class [TransformBrush](../transformbrush)
* пространство имен [Aspose.PSD.Brushes](../../aspose.psd.brushes)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
