---
title: "Класс Matrix"
type: docs
weight: 3000
url: /ru/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Matrix()](#Matrix__1) | Инициализирует новый экземпляр класса Matrix как единичную матрицу. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Инициализирует новый экземпляр класса [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(origin)](#Matrix_origin_3) | Создаёт копию класса [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Инициализирует новый экземпляр класса [Matrix](/psd/python-net/aspose.psd/matrix/) геометрическим преобразованием, определённым указанным прямоугольником и массивом точек. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Инициализирует новый экземпляр класса [Matrix](/psd/python-net/aspose.psd/matrix/) геометрическим преобразованием, определённым указанным прямоугольником и массивом точек. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | Этот бит флага указывает, что преобразование, определённое этим объектом,<br/>            выполняет зеркальное отражение относительно некоторой оси, которое меняет<br/>            обычно правостороннюю систему координат на левостороннюю<br/>            в дополнение к преобразованиям, указанным другими битами флага.<br/>            Правосторонняя система координат — это система, в которой положительная ось X<br/>            вращается против часовой стрелки, накладываясь на положительную ось Y,<br/>            аналогично направлению, в котором изгибаются пальцы правой руки,<br/>            когда вы смотрите на большой палец спереди.<br/>            Левосторонняя система координат — это система, в которой положительная ось X<br/>            вращается по часовой стрелке, накладываясь на положительную ось Y, аналогично<br/>            направлению, в котором изгибаются пальцы левой руки.<br/>            Нет математического способа определить угол исходного отражения или зеркального преобразования, поскольку все углы отражения одинаковы при соответствующей корректирующей ротации.<br/>            ПРИМЕЧАНИЕ: TypeFlip был добавлен после того, как GENERAL_TRANSFORM стал публичным,<br/>            и биты флага больше нельзя было удобно перенумеровать без введения бинарной несовместимости во внешнем коде. |
| TYPE_GENERAL_ROTATION [static] | int | r | Этот бит флага указывает, что преобразование, определённое этим объектом,<br/>            выполняет вращение на произвольный угол в дополнение к<br/>            преобразованиям, указанным другими битами флага.<br/>            Вращение изменяет углы векторов на одинаковую величину<br/>            независимо от исходного направления вектора и без<br/>            изменения длины вектора.<br/>            Этот бит флага взаимно исключает |
| TYPE_GENERAL_SCALE [static] | int | r | Общий масштаб умножает длину векторов на разные<br/>            значения по осям x и y, не изменяя угол<br/>            между перпендикулярными векторами.<br/>            Этот бит флага взаимно исключает флаг TypeUniformScale. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | Эта константа указывает, что преобразование, определённое этим объектом,<br/>            выполняет произвольное преобразование входных координат.<br/>            Если это преобразование может быть классифицировано любой из вышеуказанных констант,<br/>            тип будет либо константой TypeIdentity, либо<br/>            комбинацией соответствующих битов флага для различных координатных<br/>            преобразований, которые выполняет это преобразование. |
| TYPE_IDENTITY [static] | int | r | Тождественное преобразование — это такое, в котором выходные координаты<br/>            всегда совпадают с входными координатами.<br/>            Если это преобразование отличается от тождественного преобразования,<br/>            тип будет либо константой GENERAL_TRANSFORM, либо<br/>            комбинацией соответствующих битов флага для различных координатных<br/>            преобразований, которые выполняет это преобразование. |
| TYPE_MASK_ROTATION [static] | int | r | Эта константа является битовой маской для любого из битов флага вращения. |
| TYPE_MASK_SCALE [static] | int | r | Эта константа является битовой маской для любого из битов флага масштабирования. |
| TYPE_QUADRANT_ROTATION [static] | int | r | Этот бит флага указывает, что преобразование, определённое этим объектом,<br/>            выполняет квадрантное вращение на некоторый кратный 90 градусам в<br/>            дополнение к преобразованиям, указанным другими битами флага.<br/>            Вращение изменяет углы векторов на одинаковую величину<br/>            независимо от исходного направления вектора и без<br/>            изменения длины вектора.<br/>            Этот бит флага взаимно исключает флаг TypeGeneralRotation. |
| TYPE_TRANSLATION [static] | int | r | Трансляция перемещает координаты на постоянное значение по x<br/>            и y, не изменяя длину или угол векторов. |
| TYPE_UNIFORM_SCALE [static] | int | r | Единообразное масштабирование умножает длину векторов на одинаковую величину<br/>            как по оси x, так и по оси y, не изменяя угол между<br/>            векторами.<br/>            Этот бит флага взаимно исключает бит TypeGeneralScale. |
| elements | float | r | Возвращает массив значений с плавающей запятой, представляющих элементы этого [Matrix](/psd/python-net/aspose.psd/matrix/). |
| m11 | float | r | Возвращает элемент матрицы в первой строке, первом столбце. Представляет масштабирование вдоль оси X. |
| m12 | float | r | Возвращает элемент матрицы в первой строке, втором столбце. Представляет сдвиг вдоль оси Y. |
| m21 | float | r | Возвращает элемент матрицы во второй строке, первом столбце. Представляет сдвиг вдоль оси X. |
| m22 | float | r | Возвращает элемент матрицы во второй строке, втором столбце. Представляет масштабирование вдоль оси Y. |
| m31 | float | r | Возвращает элемент матрицы в третьей строке, первом столбце. Представляет перемещение вдоль оси X. |
| m32 | float | r | Возвращает элемент матрицы в третьей строке, первом столбце. Представляет перемещение вдоль оси Y. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_elements()](#get_elements__1) | Возвращает копию элементов матрицы. |
| [multiply(tx)](#multiply_tx_2) | Умножает эту Matrix на матрицу, указанную в параметре matrix, используя (по умолчанию) порядок Prepend. |
| [multiply(tx, order)](#multiply_tx_order_3) | Умножает эту Matrix на матрицу, указанную в параметре matrix, в порядке, указанном в параметре order. |
| reset() | Сбрасывает эту Matrix, устанавливая элементы единичной матрицы. |
| [rotate(angle)](#rotate_angle_4) | Применяет вращение по часовой стрелке на угол, указанный в параметре angle, вокруг начала координат (нулевые x и y) к этой Matrix в порядке по умолчанию (Prepend). |
| [rotate(angle, order)](#rotate_angle_order_5) | Применяет вращение по часовой стрелке на угол, указанный в параметре angle, вокруг начала координат (нулевые x и y) к этой Matrix в указанном порядке. |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в порядке по умолчанию (Prepend). |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в указанном порядке. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | Применяет указанный вектор масштабирования (scaleX и scaleY) к этому [Matrix](/psd/python-net/aspose.psd/matrix/) с использованием указанного порядка. |
| [scale(sx, sy)](#scale_sx_sy_9) | Применяет указанный вектор масштабирования (scaleX и scaleY) к этой Matrix, используя (по умолчанию) порядок Prepend. |
| [transform_points(points)](#transform_points_points_10) | Применяет геометрическое преобразование, представленное этой [Matrix](/psd/python-net/aspose.psd/matrix/), к указанному массиву точек. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | Применяет указанный вектор трансляции к этой матрице в указанном порядке. |
| [translate(tx, ty)](#translate_tx_ty_12) | Применяет указанный вектор трансляции к этой [Matrix](/psd/python-net/aspose.psd/matrix/) с использованием (по умолчанию) порядка Prepend. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Инициализирует новый экземпляр класса Matrix как единичную матрицу.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Инициализирует новый экземпляр класса [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| m11 | float | m00     M11     Масштаб X |
| m12 | float | m10     M12     Сдвиг Y |
| m21 | float | m01     M21     Сдвиг X |
| m22 | float | m11     M22     Масштаб Y |
| m31 | float | m02     M31     Перемещение X |
| m32 | float | m12     M32     Перемещение Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

Создаёт копию класса [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | Базовая матрица для обработки. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Инициализирует новый экземпляр класса [Matrix](/psd/python-net/aspose.psd/matrix/) геометрическим преобразованием, определённым указанным прямоугольником и массивом точек.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющая прямоугольник, подлежащий трансформации. |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив из трёх структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих точки параллелограмма, к которому должны быть преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается первыми тремя углами. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Инициализирует новый экземпляр класса [Matrix](/psd/python-net/aspose.psd/matrix/) геометрическим преобразованием, определённым указанным прямоугольником и массивом точек.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющая прямоугольник, подлежащий трансформации. |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | Массив из трёх структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих точки параллелограмма, к которому должны быть преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается первыми тремя углами. |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

Возвращает копию элементов матрицы.

**Returns**

| Тип | Описание |
| :- | :- |
| float | Копия элементов матрицы. |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

Умножает эту Matrix на матрицу, указанную в параметре matrix, используя (по умолчанию) порядок Prepend.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | Матрица, с которой нужно умножить. |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

Умножает эту Matrix на матрицу, указанную в параметре matrix, в порядке, указанном в параметре order.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | tx. tx. tx. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Порядок. Порядок. Порядок. |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

Применяет вращение по часовой стрелке на угол, указанный в параметре angle, вокруг начала координат (нулевые x и y) к этой Matrix в порядке по умолчанию (Prepend).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

Применяет вращение по часовой стрелке на угол, указанный в параметре angle, вокруг начала координат (нулевые x и y) к этой Matrix в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Порядок матрицы. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в порядке по умолчанию (Prepend).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Точка. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Точка. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Порядок. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

Применяет указанный вектор масштабирования (scaleX и scaleY) к этому [Matrix](/psd/python-net/aspose.psd/matrix/) с использованием указанного порядка.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scale_x | float | Масштаб X. |
| scale_y | float | Масштаб Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Порядок. |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

Применяет указанный вектор масштабирования (scaleX и scaleY) к этой Matrix, используя (по умолчанию) порядок Prepend.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | sx. sx. sx. |
| sy | float | sy. sy. sy. |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

Применяет геометрическое преобразование, представленное этой [Matrix](/psd/python-net/aspose.psd/matrix/), к указанному массиву точек.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Точки. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

Применяет указанный вектор трансляции к этой матрице в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| offset_x | float | Смещение X. |
| offset_y | float | Смещение Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Порядок. |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

Применяет указанный вектор трансляции к этой [Matrix](/psd/python-net/aspose.psd/matrix/) с использованием (по умолчанию) порядка Prepend.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tx | float | tx. tx. tx. |
| ty | float | Ty. Ty. Ty. |

