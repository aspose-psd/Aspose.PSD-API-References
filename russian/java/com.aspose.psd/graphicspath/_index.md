---
title: "GraphicsPath"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет серию соединённых линий и кривых."
type: docs
weight: 50
url: /ru/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Представляет серию соединённых линий и кривых. Этот класс нельзя наследовать.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Инициализирует новый экземпляр класса  GraphicsPath . |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | Инициализирует новый экземпляр класса  GraphicsPath . |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | Инициализирует новый экземпляр класса  GraphicsPath . |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Инициализирует новый экземпляр класса  GraphicsPath . |
## Методы

| Метод | Описание |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | Добавляет новую фигуру. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | Добавляет новые фигуры. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | Добавляет указанный  com.aspose.psd.GraphicsPath  к этому пути. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | Добавляет указанный  com.aspose.psd.GraphicsPath  к этому пути. |
| [deepClone()](#deepClone--) | Выполняет глубокое клонирование этого графического пути. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Преобразует каждую кривую в этом пути в последовательность соединённых отрезков. |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | Применяет указанное преобразование, а затем преобразует каждую кривую в этом  com.aspose.psd.GraphicsPath  в последовательность соединённых отрезков. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | Преобразует каждую кривую в этом  com.aspose.psd.GraphicsPath  в последовательность соединённых отрезков. |
| [getBounds()](#getBounds--) | Получает или задает границы объекта. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Получает границы объекта. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Получает границы объекта. |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | Получает фигуры пути. |
| [getFillMode()](#getFillMode--) | Получает перечисление  com.aspose.psd.FillMode , которое определяет, как заполняются внутренние части фигур в этом  com.aspose.psd.GraphicsPath . |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.pen . |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.Pen  и с использованием указанного  com.aspose.psd.graphics . |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.pen . |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.Pen  и с использованием указанного  com.aspose.psd.graphics . |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.pen . |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.Pen  и с использованием указанного  com.aspose.psd.graphics . |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.pen . |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.Pen  и с использованием указанного  com.aspose.psd.graphics . |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Указывает, находится ли указанная точка внутри этого  com.aspose.psd.graphicsPath . |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Указывает, находится ли указанная точка внутри этого  com.aspose.psd.graphicsPath . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Указывает, находится ли указанная точка внутри этого  com.aspose.psd.graphicsPath . |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Указывает, находится ли указанная точка внутри этого  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y)](#isVisible-float-float-) | Указывает, находится ли указанная точка внутри этого  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | Указывает, содержится ли указанная точка внутри этого  com.aspose.psd.GraphicsPath  в видимой области отсечения указанного  com.aspose.psd.graphics . |
| [isVisible(int x, int y)](#isVisible-int-int-) | Указывает, находится ли указанная точка внутри этого  com.aspose.psd.graphicsPath . |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | Указывает, содержится ли указанная точка внутри этого  com.aspose.psd.GraphicsPath , используя указанный  com.aspose.psd.graphics . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | Удаляет фигуру. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | Удаляет фигуры. |
| [reset()](#reset--) | Очищает графический путь и устанавливает  com.aspose.psd.FillMode  в  F:com.aspose.psd.fillMode.alternate . |
| [reverse()](#reverse--) | Изменяет порядок фигур, форм и точек в каждой форме этого  com.aspose.psd.graphicsPath . |
| [setFillMode(int value)](#setFillMode-int-) | Устанавливает перечисление  com.aspose.psd.FillMode , определяющее, как заполняются внутренности форм в этом  com.aspose.psd.GraphicsPath . |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Применяет указанное преобразование к форме. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому  com.aspose.psd.graphicsPath . |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | Добавляет дополнительный контур к пути. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | Добавляет дополнительный контур к  com.aspose.psd.graphicsPath . |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | Заменяет этот  com.aspose.psd.GraphicsPath  кривыми, которые охватывают область, заполняемую при отрисовке этого пути указанной ручкой. |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Инициализирует новый экземпляр класса  GraphicsPath .

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Инициализирует новый экземпляр класса  GraphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Фигуры, из которых инициализировать. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Инициализирует новый экземпляр класса  GraphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Фигуры, из которых инициализировать. |
| fillMode | int | Режим заполнения. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Инициализирует новый экземпляр класса  GraphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fillMode | int | Режим заполнения. |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


Добавляет новую фигуру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | Фигура для добавления. |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


Добавляет новые фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Фигуры для добавления. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Добавляет указанный  com.aspose.psd.GraphicsPath  к этому пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Графический путь  com.aspose.psd.GraphicsPath  для добавления. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Добавляет указанный  com.aspose.psd.GraphicsPath  к этому пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Графический путь  com.aspose.psd.GraphicsPath  для добавления. |
| connect | boolean | Булево значение, указывающее, является ли первая фигура в добавленном пути частью последней фигуры в этом пути. Значение true указывает, что первая фигура в добавленном пути является частью последней фигуры в этом пути. Значение false указывает, что первая фигура в добавленном пути отдельна от последней фигуры в этом пути. |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Выполняет глубокое клонирование этого графического пути.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flatten() {#flatten--}
```
public void flatten()
```


Преобразует каждую кривую в этом пути в последовательность соединённых отрезков.

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


Применяет указанное преобразование, а затем преобразует каждую кривую в этом  com.aspose.psd.GraphicsPath  в последовательность соединённых отрезков.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Матрица  com.aspose.psd.Matrix , с помощью которой преобразовать этот  com.aspose.psd.GraphicsPath  перед уплощением. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Преобразует каждую кривую в этом  com.aspose.psd.GraphicsPath  в последовательность соединённых отрезков.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Матрица  com.aspose.psd.Matrix , с помощью которой преобразовать этот  com.aspose.psd.GraphicsPath  перед уплощением. |
| flatness | float | Указывает максимальную допустимую погрешность между кривой и её уплощённым приближением. Значение 0.25 является значением по умолчанию. Уменьшение значения flatness увеличит количество отрезков линии в приближении. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Получает или задает границы объекта.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Получает границы объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Матрица, применяемая перед вычислением границ. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Получает границы объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Матрица, применяемая перед вычислением границ. |
| pen | [Pen](../../com.aspose.psd/pen) | Ручка, используемая для объекта. Это может влиять на размер границ объекта. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Получает фигуры пути.

**Returns:**
com.aspose.psd.Figure[] - Фигуры пути.
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Получает перечисление  com.aspose.psd.FillMode , которое определяет, как заполняются внутренние части фигур в этом  com.aspose.psd.GraphicsPath .

**Returns:**
int - Режим заполнения. Перечисление  com.aspose.psd.FillMode , определяющее, как заполняются внутренности форм в этом  com.aspose.psd.GraphicsPath .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Точка  com.aspose.psd.Point , указывающая местоположение для проверки. |
| pen | [Pen](../../com.aspose.psd/pen) | Класс  com.aspose.psd.Pen  для тестирования. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри контура этого  com.aspose.psd.GraphicsPath  при отрисовке указанным  com.aspose.psd.Pen ; в противном случае — false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.Pen  и с использованием указанного  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Точка  com.aspose.psd.Point , указывающая местоположение для проверки. |
| pen | [Pen](../../com.aspose.psd/pen) | Класс  com.aspose.psd.Pen  для тестирования. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics  для проверки видимости. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри контура этого  com.aspose.psd.GraphicsPath , отрисованного указанным  com.aspose.psd.Pen ; в противном случае — false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Объект  com.aspose.psd.PointF , указывающий местоположение для проверки. |
| pen | [Pen](../../com.aspose.psd/pen) | Класс  com.aspose.psd.Pen  для тестирования. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри контура этого  com.aspose.psd.GraphicsPath  при отрисовке указанным  com.aspose.psd.Pen ; в противном случае — false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.Pen  и с использованием указанного  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Объект  com.aspose.psd.PointF , указывающий местоположение для проверки. |
| pen | [Pen](../../com.aspose.psd/pen) | Класс  com.aspose.psd.Pen  для тестирования. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics  для проверки видимости. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри (под) контура этого  com.aspose.psd.GraphicsPath , отрисованного указанным  com.aspose.psd.Pen ; в противном случае — false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | X‑координата точки для проверки. |
| y | float | Y‑координата точки для проверки. |
| pen | [Pen](../../com.aspose.psd/pen) | Класс  com.aspose.psd.Pen  для тестирования. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри контура этого  com.aspose.psd.GraphicsPath  при отрисовке указанным  com.aspose.psd.Pen ; в противном случае — false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.Pen  и с использованием указанного  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | X‑координата точки для проверки. |
| y | float | Y‑координата точки для проверки. |
| pen | [Pen](../../com.aspose.psd/pen) | Класс  com.aspose.psd.Pen  для тестирования. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics  для проверки видимости. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри (под) контура этого  com.aspose.psd.GraphicsPath , отрисованного указанным  com.aspose.psd.Pen ; в противном случае — false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | X‑координата точки для проверки. |
| y | int | Y‑координата точки для проверки. |
| pen | [Pen](../../com.aspose.psd/pen) | Класс  com.aspose.psd.Pen  для тестирования. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри контура этого  com.aspose.psd.GraphicsPath  при отрисовке указанным  com.aspose.psd.Pen ; в противном случае — false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Указывает, находится ли указанная точка внутри (под) контура этого  com.aspose.psd.GraphicsPath , когда он отрисован с указанным  com.aspose.psd.Pen  и с использованием указанного  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | X‑координата точки для проверки. |
| y | int | Y‑координата точки для проверки. |
| pen | [Pen](../../com.aspose.psd/pen) | Класс  com.aspose.psd.Pen  для тестирования. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics  для проверки видимости. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри контура этого  com.aspose.psd.GraphicsPath , отрисованного указанным  com.aspose.psd.Pen ; в противном случае — false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Указывает, находится ли указанная точка внутри этого  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Объект  com.aspose.psd.Point , представляющий точку для проверки. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого  com.aspose.psd.GraphicsPath ; в противном случае — false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Указывает, находится ли указанная точка внутри этого  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Объект  com.aspose.psd.Point , представляющий точку для проверки. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics  для проверки видимости. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого  com.aspose.psd.GraphicsPath ; в противном случае — false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Указывает, находится ли указанная точка внутри этого  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Объект  com.aspose.psd.PointF , представляющий точку для проверки. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого  com.aspose.psd.GraphicsPath ; в противном случае — false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Указывает, находится ли указанная точка внутри этого  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Объект  com.aspose.psd.PointF , представляющий точку для проверки. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics  для проверки видимости. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого; в противном случае — false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Указывает, находится ли указанная точка внутри этого  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | X‑координата точки для проверки. |
| y | float | Y‑координата точки для проверки. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого  com.aspose.psd.GraphicsPath ; в противном случае — false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Указывает, содержится ли указанная точка внутри этого  com.aspose.psd.GraphicsPath  в видимой области отсечения указанного  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | X‑координата точки для проверки. |
| y | float | Y‑координата точки для проверки. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics  для проверки видимости. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого  com.aspose.psd.GraphicsPath ; в противном случае — false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Указывает, находится ли указанная точка внутри этого  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | X‑координата точки для проверки. |
| y | int | Y‑координата точки для проверки. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого  com.aspose.psd.GraphicsPath ; в противном случае — false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Указывает, содержится ли указанная точка внутри этого  com.aspose.psd.GraphicsPath , используя указанный  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | X‑координата точки для проверки. |
| y | int | Y‑координата точки для проверки. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics  для проверки видимости. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого  com.aspose.psd.GraphicsPath ; в противном случае — false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFigure(Figure figure) {#removeFigure-com.aspose.psd.Figure-}
```
public void removeFigure(Figure figure)
```


Удаляет фигуру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | Элемент для удаления. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


Удаляет фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Элементы для удаления. |

### reset() {#reset--}
```
public void reset()
```


Очищает графический путь и устанавливает  com.aspose.psd.FillMode  в  F:com.aspose.psd.fillMode.alternate .

### reverse() {#reverse--}
```
public void reverse()
```


Изменяет порядок фигур, форм и точек в каждой форме этого  com.aspose.psd.graphicsPath .

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Устанавливает перечисление  com.aspose.psd.FillMode , определяющее, как заполняются внутренности форм в этом  com.aspose.psd.GraphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Режим заполнения. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


Применяет указанное преобразование к форме.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | Преобразование, которое нужно применить. |

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

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  com.aspose.psd.PointF , определяющих параллелограмм, в который преобразуется прямоугольник, заданный  srcRect . Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Объект  com.aspose.psd.RectangleF , представляющий прямоугольник, преобразуемый в параллелограмм, определённый  destPoints . |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  com.aspose.psd.PointF , определяющих параллелограмм, в который преобразуется прямоугольник, заданный  srcRect . Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Объект  com.aspose.psd.RectangleF , представляющий прямоугольник, преобразуемый в параллелограмм, определённый  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Объект  com.aspose.psd.Matrix , задающий геометрическое преобразование, применяемое к пути. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  com.aspose.psd.PointF , определяющих параллелограмм, в который преобразуется прямоугольник, заданный  srcRect . Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Объект  com.aspose.psd.RectangleF , представляющий прямоугольник, преобразуемый в параллелограмм, определённый  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Объект  com.aspose.psd.Matrix , задающий геометрическое преобразование, применяемое к пути. |
| warpMode | int | Перечисление  com.aspose.psd.WarpMode , указывающее, использует ли операция искажения перспективный или билинейный режим. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  com.aspose.psd.PointF , определяющих параллелограмм, в который преобразуется прямоугольник, заданный  srcRect . Массив может содержать три или четыре элемента. Если массив содержит три элемента, нижний правый угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Объект  com.aspose.psd.RectangleF , представляющий прямоугольник, преобразуемый в параллелограмм, определённый  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Объект  com.aspose.psd.Matrix , задающий геометрическое преобразование, применяемое к пути. |
| warpMode | int | Перечисление  com.aspose.psd.WarpMode , указывающее, использует ли операция искажения перспективный или билинейный режим. |
| flatness | float | Значение от 0 до 1, определяющее степень плоскостности полученного пути. Для получения дополнительной информации см. методы  com.aspose.psd.GraphicsPath.flatten . |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


Добавляет дополнительный контур к пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Объект  com.aspose.psd.Pen , задающий ширину между оригинальным контуром пути и новым контуром, создаваемым этим методом. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Добавляет дополнительный контур к  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Объект  com.aspose.psd.Pen , задающий ширину между оригинальным контуром пути и новым контуром, создаваемым этим методом. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Объект  com.aspose.psd.Matrix , задающий преобразование, применяемое к пути перед расширением. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Заменяет этот  com.aspose.psd.GraphicsPath  кривыми, которые охватывают область, заполняемую при отрисовке этого пути указанной ручкой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Объект  com.aspose.psd.Pen , задающий ширину между оригинальным контуром пути и новым контуром, создаваемым этим методом. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Объект  com.aspose.psd.Matrix , задающий преобразование, применяемое к пути перед расширением. |
| flatness | float | Значение, определяющее степень плоскостности кривых. |

