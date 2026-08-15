---
title: "Класс TextureBrush"
type: docs
weight: 90
url: /ru/python-net/aspose.psd.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class is a [Brush](/psd/python-net/aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.TextureBrush

**Inheritance:** TransformBrush

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение и режим обтекания. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Получает объект [Image](/psd/python-net/aspose.psd/image/), связанный с этим объектом [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | r | Получает [TextureBrush.image_attributes](/psd/python-net/aspose.psd.brushes/texturebrush/), связанные с этим [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Получает объект [Rectangle](/psd/python-net/aspose.psd/rectangle/), связанный с этим [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| is_transform_changed | bool | r | Получает значение, указывающее, были ли преобразования изменены каким-либо образом. Например, установка матрицы преобразования или<br/>            вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| opacity | float | r/w | Получает или задаёт непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Получает или задаёт копию [Matrix](/psd/python-net/aspose.psd/matrix/), определяющую локальное геометрическое преобразование для этого [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Получает или задаёт перечисление [WrapMode](/psd/python-net/aspose.psd/wrapmode/), указывающее режим обтекания для этого [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Создаёт новую глубокую копию текущего [Brush](/psd/python-net/aspose.psd/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Умножает [Matrix](/psd/python-net/aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/), на указанную [Matrix](/psd/python-net/aspose.psd/matrix/), предварительно добавляя указанную [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Умножает [Matrix](/psd/python-net/aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/), на указанную [Matrix](/psd/python-net/aspose.psd/matrix/) в указанном порядке. |
| reset_transform() | Сбрасывает свойство [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) к единичному. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет вращение в начало преобразования. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Масштабирует локальное геометрическое преобразование на указанные значения. Этот метод добавляет матрицу масштабирования в начало преобразования. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Масштабирует локальное геометрическое преобразование на указанные значения в указанном порядке. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Объект [Image](/psd/python-net/aspose.psd/image/), которым этот объект [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) заполняет внутренние области. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение и ограничивающий прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Объект [Image](/psd/python-net/aspose.psd/image/), которым этот объект [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) заполняет внутренние области. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющая ограничивающий прямоугольник для этого объекта [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение и ограничивающий прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Объект [Image](/psd/python-net/aspose.psd/image/), которым этот объект [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) заполняет внутренние области. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющая ограничивающий прямоугольник для этого объекта [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Объект [Image](/psd/python-net/aspose.psd/image/), которым этот объект [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) заполняет внутренние области. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющая ограничивающий прямоугольник для этого объекта [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Объект [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/), содержащий дополнительную информацию об изображении, используемом этим объектом [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение, ограничивающий прямоугольник и атрибуты изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Объект [Image](/psd/python-net/aspose.psd/image/), которым этот объект [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) заполняет внутренние области. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющая ограничивающий прямоугольник для этого объекта [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Объект [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/), содержащий дополнительную информацию об изображении, используемом этим объектом [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение и режим обтекания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Объект [Image](/psd/python-net/aspose.psd/image/), которым этот объект [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) заполняет внутренние области. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Перечисление [WrapMode](/psd/python-net/aspose.psd/wrapmode/), которое указывает, как будет заполняться объект [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Объект [Image](/psd/python-net/aspose.psd/image/), которым этот объект [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) заполняет внутренние области. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Перечисление [WrapMode](/psd/python-net/aspose.psd/wrapmode/), которое указывает, как будет заполняться объект [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющая ограничивающий прямоугольник для этого объекта [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Инициализирует новый экземпляр класса [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/), использующий указанное изображение, режим обтекания и ограничивающий прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Объект [Image](/psd/python-net/aspose.psd/image/), которым этот объект [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) заполняет внутренние области. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Перечисление [WrapMode](/psd/python-net/aspose.psd/wrapmode/), которое указывает, как будет заполняться объект [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющая ограничивающий прямоугольник для этого объекта [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Создаёт новую глубокую копию текущего [Brush](/psd/python-net/aspose.psd/brush/).

**Returns**

| Тип | Описание |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | Новый [Brush](/psd/python-net/aspose.psd/brush/), являющийся глубоким клоном данного экземпляра [Brush](/psd/python-net/aspose.psd/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Умножает [Matrix](/psd/python-net/aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/), на указанную [Matrix](/psd/python-net/aspose.psd/matrix/), предварительно добавляя указанную [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/), используемая для умножения геометрического преобразования. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Умножает [Matrix](/psd/python-net/aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/), на указанную [Matrix](/psd/python-net/aspose.psd/matrix/) в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/), используемая для умножения геометрического преобразования. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), определяющий порядок умножения двух матриц. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет вращение в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), определяющий, добавлять ли матрицу вращения в конец или в начало. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Масштабирует локальное геометрическое преобразование на указанные значения. Этот метод добавляет матрицу масштабирования в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Величина масштабирования преобразования по оси x. |
| sy | float | Величина масштабирования преобразования по оси y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Масштабирует локальное геометрическое преобразование на указанные значения в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Величина масштабирования преобразования по оси x. |
| sy | float | Величина масштабирования преобразования по оси y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), определяющий, добавлять ли матрицу масштабирования в конец или в начало. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Смещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Порядок (добавление в начало или в конец), в котором применять трансляцию. |

