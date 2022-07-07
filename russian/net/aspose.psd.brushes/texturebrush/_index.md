---
title: TextureBrush
second_title: Справочник по Aspose.PSD для .NET API
description: Каждое свойство классаTextureBrush./texturebrushявляетсяBrush../aspose.psd/brushобъект использующий изображение для заполнения внутренней части фигуры. Этот класс не может быть унаследован.
type: docs
weight: 210
url: /ru/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

Каждое свойство класса[`TextureBrush`](../texturebrush)является[`Brush`](../../aspose.psd/brush)объект, использующий изображение для заполнения внутренней части фигуры. Этот класс не может быть унаследован.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextureBrush](texturebrush#constructor)(Image) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение. |
| [TextureBrush](texturebrush#constructor_1)(Image, Rectangle) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush](texturebrush#constructor_3)(Image, RectangleF) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush](texturebrush#constructor_5)(Image, WrapMode) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение и режим переноса. |
| [TextureBrush](texturebrush#constructor_2)(Image, Rectangle, ImageAttributes) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение, ограничивающий прямоугольник и изображение атрибуты. |
| [TextureBrush](texturebrush#constructor_4)(Image, RectangleF, ImageAttributes) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение, ограничивающий прямоугольник и изображение атрибуты. |
| [TextureBrush](texturebrush#constructor_6)(Image, WrapMode, Rectangle) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение, режим переноса и границы прямоугольник. |
| [TextureBrush](texturebrush#constructor_7)(Image, WrapMode, RectangleF) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение, режим переноса и границы прямоугольник. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [Image](../../aspose.psd.brushes/texturebrush/image) { get; } | Получает объект[`Image`](../../aspose.psd/image), связанный с этим[`TextureBrush`](../texturebrush)объект. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes) { get; } | Получает атрибут[`ImageAttributes`](./imageattributes), связанный с этимТекстурнаякисть. |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle) { get; } | Получает[`Rectangle`](../../aspose.psd/rectangle)связанный с этим[`TextureBrush`](../texturebrush). |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged) { get; } | Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например, установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.psd/brush/opacity) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видна, значение 1 означает, что кисть полностью непрозрачна. |
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
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float) | Переносит локальное геометрическое преобразование на заданные размеры. Этот метод добавляет перевод к преобразованию. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Смотрите также

* class [TransformBrush](../transformbrush)
* пространство имен [Aspose.PSD.Brushes](../../aspose.psd.brushes)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
