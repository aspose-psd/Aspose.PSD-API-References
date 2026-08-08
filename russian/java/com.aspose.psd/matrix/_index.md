---
title: "Matrix"
second_title: "Aspose.PSD for Java API Справочник"
description: "Заменяет матрицу GDI."
type: docs
weight: 69
url: /ru/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

Заменяет матрицу GDI+.

Большинство алгоритмов взяты из Sun's AffineTransform.java. Имена элементов матрицы из Java используются внутри. Сопоставление имён Java с .net и их описание: m00 M11 Масштаб X m10 M12 Сдвиг Y m01 M21 Сдвиг X m11 M22 Масштаб Y m02 M31 Перемещение X m12 M32 Перемещение Y
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Matrix()](#Matrix--) | Инициализирует новый экземпляр класса Matrix как единичную матрицу. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Инициализирует новый экземпляр класса Matrix. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | Создаёт копию класса Matrix. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | Инициализирует новый экземпляр класса Aspose.Imaging.Matrix геометрическим преобразованием, определённым указанным прямоугольником и массивом точек. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | Инициализирует новый экземпляр класса Aspose.Imaging.Matrix геометрическим преобразованием, определённым указанным прямоугольником и массивом точек. |
## Поля

| Поле | Описание |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | Этот бит флага указывает, что преобразование, определённое этим объектом, выполняет зеркальное отражение относительно некоторой оси, что меняет обычно правостороннюю систему координат на левостороннюю, в дополнение к преобразованиям, указанным другими битами флага. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Этот бит флага указывает, что преобразование, определённое этим объектом, выполняет вращение на произвольный угол, в дополнение к преобразованиям, указанным другими битами флага. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Общее масштабирование умножает длину векторов на разные величины по осям X и Y, не изменяя угол между перпендикулярными векторами. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Эта константа указывает, что преобразование, определённое этим объектом, выполняет произвольное преобразование входных координат. |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Трансформация идентичности — это такая, в которой выходные координаты всегда совпадают с входными координатами. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Эта константа является битовой маской для любого из битов флага вращения. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Эта константа является битовой маской для любого из битов флага масштабирования. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Этот бит флага указывает, что трансформация, определённая этим объектом, выполняет квадрантное вращение на кратное 90 градусов в дополнение к преобразованиям, указанным другими битами флага. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Трансляция перемещает координаты на постоянное значение по осям x и y, не изменяя длину и угол векторов. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Однородное масштабирование умножает длину векторов на одинаковое значение как по оси x, так и по оси y, не изменяя угол между векторами. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный  System.Object  этому экземпляру. |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | Получает копию элементов матрицы. |
| [getM11()](#getM11--) | Получает элемент матрицы в первой строке, первом столбце. |
| [getM12()](#getM12--) | Получает элемент матрицы в первой строке, втором столбце. |
| [getM21()](#getM21--) | Получает элемент матрицы во второй строке, первом столбце. |
| [getM22()](#getM22--) | Получает элемент матрицы во второй строке, втором столбце. |
| [getM31()](#getM31--) | Получает элемент матрицы в третьей строке, первом столбце. |
| [getM32()](#getM32--) | Получает элемент матрицы в третьей строке, первом столбце. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | Определяет, равны ли две матрицы. |
| [isIdentity()](#isIdentity--) | Возвращает `true`, если этот `AffineTransform` является трансформацией идентичности. |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | Умножает эту Matrix на матрицу, указанную в параметре matrix, используя (по умолчанию) порядок Prepend. |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | Умножает эту Matrix на матрицу, указанную в параметре matrix, и в порядке, указанном в параметре order. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Сбрасывает эту Matrix, чтобы она содержала элементы единичной матрицы. |
| [rotate(float angle)](#rotate-float-) | Применяет вращение по часовой стрелке на величину, указанную в параметре angle, вокруг начала координат (ноль по x и y) для этой Matrix в порядке по умолчанию (Prepend). |
| [rotate(float angle, int order)](#rotate-float-int-) | Применяет вращение по часовой стрелке на величину, указанную в параметре angle, вокруг начала координат (ноль по x и y) для этой Matrix в указанном порядке. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в порядке по умолчанию (Prepend). |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в указанном порядке. |
| [scale(float sx, float sy)](#scale-float-float-) | Применяет указанный вектор масштабирования (scaleX и scaleY) к этой Matrix, используя (по умолчанию) порядок Prepend. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Применяет указанный вектор масштабирования (scaleX и scaleY) к этой  Matrix  используя указанный порядок. |
| [toString()](#toString--) | Возвращает  System.String  который представляет этот экземпляр. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | Применяет геометрическую трансформацию, представленную этой  Matrix , к указанному массиву точек. |
| [translate(float tx, float ty)](#translate-float-float-) | Применяет указанный вектор трансляции к этой  Matrix , используя (по умолчанию) порядок Prepend. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Применяет указанный вектор трансляции к этой матрице в указанном порядке. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


Инициализирует новый экземпляр класса Matrix как единичную матрицу.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Инициализирует новый экземпляр класса Matrix.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| m11 | float | m00 M11 Масштаб X |
| m12 | float | m10 M12 Сдвиг Y |
| m21 | float | m01 M21 Сдвиг X |
| m22 | float | m11 M22 Масштаб Y |
| m31 | float | m02 M31 Трансляция X |
| m32 | float | m12 M32 Трансляция Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


Создаёт копию класса Matrix.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | базовая матрица для копирования |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Инициализирует новый экземпляр класса Aspose.Imaging.Matrix геометрическим преобразованием, определённым указанным прямоугольником и массивом точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура Aspose.Imaging.RectangleF, представляющая прямоугольник, который будет преобразован. |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | Массив из трёх структур Aspose.Imaging.PointF, представляющих точки параллелограмма, в который будут преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается третьими углами. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Инициализирует новый экземпляр класса Aspose.Imaging.Matrix геометрическим преобразованием, определённым указанным прямоугольником и массивом точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура Aspose.Imaging.Rectangle, представляющая прямоугольник, который будет преобразован. |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | Массив из трёх структур Aspose.Imaging.Point, представляющих точки параллелограмма, в который будут преобразованы верхний‑левый, верхний‑правый и нижний‑левый углы прямоугольника. Нижний‑правый угол параллелограмма подразумевается третьими углами. |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Этот бит флага указывает, что преобразование, определённое этим объектом, выполняет отражение зеркального изображения относительно некоторой оси, что меняет обычно правостороннюю систему координат на левостороннюю, в дополнение к преобразованиям, указанным другими битами флага. Правосторонняя система координат — это система, в которой положительная ось X вращается против часовой стрелки, накладываясь на положительную ось Y, аналогично направлению, в котором изгибаются пальцы правой руки, когда вы смотрите на большой палец. Левосторонняя система координат — это система, в которой положительная ось X вращается по часовой стрелке, накладываясь на положительную ось Y, аналогично изгибу пальцев левой руки. Нет математического способа определить угол исходного отражения или зеркального преобразования, поскольку все углы отражения идентичны при соответствующем корректирующем вращении. ПРИМЕЧАНИЕ: TypeFlip был добавлен после того, как GENERAL\_TRANSFORM стал общедоступным, и биты флага больше нельзя было удобно перенумеровать без введения бинарной несовместимости во внешнем коде.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Этот бит флага указывает, что преобразование, определённое этим объектом, выполняет вращение на произвольный угол в дополнение к преобразованиям, указанным другими битами флага. Вращение изменяет углы векторов на одинаковую величину независимо от исходного направления вектора и без изменения длины вектора. Этот бит флага взаимно исключает с

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Общий масштаб умножает длину векторов на разные значения по осям x и y, не изменяя угол между перпендикулярными векторами. Этот бит флага взаимно исключает флаг TypeUniformScale.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Эта константа указывает, что преобразование, определённое этим объектом, выполняет произвольное преобразование входных координат. Если данное преобразование может быть классифицировано любой из вышеуказанных констант, тип будет либо константой TypeIdentity, либо комбинацией соответствующих битов флага для различных преобразований координат, которые выполняет это преобразование.

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Тождественное преобразование — это такое, при котором выходные координаты всегда совпадают с входными координатами. Если данное преобразование отличается от тождественного, тип будет либо константой GENERAL\_TRANSFORM, либо комбинацией соответствующих битов флага для различных преобразований координат, которые выполняет это преобразование.

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Эта константа является битовой маской для любого из битов флага вращения.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Эта константа является битовой маской для любого из битов флага масштабирования.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Этот бит флага указывает, что преобразование, определённое этим объектом, выполняет квадрантное вращение на кратное 90‑градусам значение в дополнение к преобразованиям, указанным другими битами флага. Вращение изменяет углы векторов на одинаковую величину независимо от исходного направления вектора и без изменения длины вектора. Этот бит флага взаимно исключает флаг TypeGeneralRotation.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Трансляция перемещает координаты на постоянное значение по осям x и y, не изменяя длину и угол векторов.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Униформный масштаб умножает длину векторов на одинаковое значение как по оси x, так и по оси y, не изменяя угол между векторами. Этот бит флага взаимно исключает флаг TypeGeneralScale.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный  System.Object  этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект  System.Object  для сравнения с этим экземпляром. |

**Returns:**
boolean -  true  если указанный  System.Object  равен этому экземпляру; иначе,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public float[] getElements()
```


Получает копию элементов матрицы.

**Returns:**
float[] - Копия элементов матрицы.
### getM11() {#getM11--}
```
public float getM11()
```


Получает элемент матрицы в первой строке первой колонке. Представляет масштаб вдоль оси X.

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


Получает элемент матрицы в первой строке второй колонке. Представляет сдвиг вдоль оси Y.

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


Получает элемент матрицы во второй строке первой колонке. Представляет сдвиг вдоль оси X.

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


Получает элемент матрицы во второй строке второй колонке. Представляет масштаб вдоль оси Y.

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


Получает элемент матрицы в третьей строке первой колонке. Представляет трансляцию вдоль оси X.

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


Получает элемент матрицы в третьей строке первой колонке. Представляет трансляцию вдоль оси Y.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int - Хеш-код для этого экземпляра, подходящий для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Определяет, равны ли две матрицы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | Первая матрица для сравнения. |
| b | [Matrix](../../com.aspose.psd/matrix) | Вторая матрица для сравнения. |

**Returns:**
boolean - Истина, если матрицы равны.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Возвращает `true`, если этот `AffineTransform` является трансформацией идентичности.

**Returns:**
boolean - `true`, если этот `AffineTransform` является единичным преобразованием; `false` в противном случае.
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


Умножает эту Matrix на матрицу, указанную в параметре matrix, используя (по умолчанию) порядок Prepend.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | Матрица, с которой производится умножение. |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


Умножает эту Matrix на матрицу, указанную в параметре matrix, и в порядке, указанном в параметре order.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | tx. tx. tx. |
| порядок | int | порядок. порядок. порядок. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


Сбрасывает эту Matrix, чтобы она содержала элементы единичной матрицы.

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Применяет вращение по часовой стрелке на величину, указанную в параметре angle, вокруг начала координат (ноль по x и y) для этой Matrix в порядке по умолчанию (Prepend).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Применяет вращение по часовой стрелке на величину, указанную в параметре angle, вокруг начала координат (ноль по x и y) для этой Matrix в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |
| порядок | int | Порядок матрицы. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в порядке по умолчанию (Prepend).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол. |
| point | [PointF](../../com.aspose.psd/pointf) | Точка. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Применяет вращение по часовой стрелке вокруг указанной точки к этой Matrix в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол. |
| point | [PointF](../../com.aspose.psd/pointf) | Точка. |
| порядок | int | Порядок. |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


Применяет указанный вектор масштабирования (scaleX и scaleY) к этой Matrix, используя (по умолчанию) порядок Prepend.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | sx. sx. sx. |
| sy | float | sy. sy. sy. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Применяет указанный вектор масштабирования (scaleX и scaleY) к этой  Matrix  используя указанный порядок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | float | Масштаб X. |
| scaleY | float | Масштаб Y. |
| порядок | int | Порядок. |

### toString() {#toString--}
```
public String toString()
```


Возвращает  System.String  который представляет этот экземпляр.

**Returns:**
java.lang.String -  System.String  представляющий этот экземпляр.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


Применяет геометрическую трансформацию, представленную этой  Matrix , к указанному массиву точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Точки. |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


Применяет указанный вектор трансляции к этой  Matrix , используя (по умолчанию) порядок Prepend.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tx | float | tx. tx. tx. |
| ty | float | ty. ty. ty. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Применяет указанный вектор трансляции к этой матрице в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| offsetX | float | Смещение X. |
| offsetY | float | Смещение Y. |
| порядок | int | Порядок. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

