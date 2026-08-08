---
title: "Region"
second_title: "Aspose.PSD for Java API Справочник"
description: "Описывает внутреннюю часть графической формы, состоящей из прямоугольников и путей."
type: docs
weight: 90
url: /ru/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

Описывает внутреннюю часть графической фигуры, состоящей из прямоугольников и путей. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Region()](#Region--) | Инициализирует новый T:Aspose.Imaging.Region. |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | Инициализирует новый T:Aspose.Imaging.Region из указанной структуры T:Aspose.Imaging.RectangleF. |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | Инициализирует новый T:Aspose.Imaging.Region из указанной структуры T:Aspose.Imaging.Rectangle. |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | Инициализирует новый T:Aspose.Imaging.Region с указанным T:Aspose.Imaging.GraphicsPath. |
## Методы

| Метод | Описание |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | Обновляет этот com.aspose.psd.Region, чтобы он содержал часть указанного com.aspose.psd.GraphicsPath, не пересекающуюся с этим com.aspose.psd.region. |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | Обновляет этот com.aspose.psd.Region, чтобы он содержал часть указанной структуры com.aspose.psd.Rectangle, не пересекающуюся с этим com.aspose.psd.region. |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | Обновляет этот com.aspose.psd.Region, чтобы он содержал часть указанной структуры com.aspose.psd.RectangleF, не пересекающуюся с этим com.aspose.psd.region. |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | Обновляет этот  com.aspose.psd.Region  так, чтобы он содержал часть указанного  com.aspose.psd.Region , не пересекающуюся с этим  com.aspose.psd.region . |
| [deepClone()](#deepClone--) | Создаёт точную глубокую копию этого  com.aspose.psd.region . |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | Обновляет этот  com.aspose.psd.Region  так, чтобы он содержал только часть его внутренней области, не пересекающуюся с указанным  com.aspose.psd.graphicsPath . |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | Обновляет этот  com.aspose.psd.Region  так, чтобы он содержал только часть его внутренней области, не пересекающуюся с указанной структурой  com.aspose.psd.Rectangle . |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | Обновляет этот  com.aspose.psd.Region  так, чтобы он содержал только часть его внутренней области, не пересекающуюся с указанной структурой  com.aspose.psd.RectangleF . |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | Обновляет этот  com.aspose.psd.Region  так, чтобы он содержал только часть его внутренней области, не пересекающуюся с указанным  com.aspose.psd.region . |
| [getActions_internalized()](#getActions-internalized--) | Получает действия области. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | Обновляет этот  com.aspose.psd.Region  до пересечения с указанным  com.aspose.psd.graphicsPath . |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Обновляет этот  com.aspose.psd.Region  до пересечения с указанной структурой  com.aspose.psd.Rectangle . |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Обновляет этот  com.aspose.psd.Region  до пересечения с указанной структурой  com.aspose.psd.RectangleF . |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | Обновляет этот  com.aspose.psd.Region  до пересечения с указанным  com.aspose.psd.region . |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | Проверяет, имеет ли этот  com.aspose.psd.Region  пустую внутреннюю область на указанной поверхности рисования. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | Проверяет, идентичен ли указанный  com.aspose.psd.Region  этому  com.aspose.psd.Region  на указанной поверхности рисования. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | Проверяет, имеет ли этот  com.aspose.psd.Region  бесконечную внутреннюю область на указанной поверхности рисования. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Проверяет, содержится ли указанная структура  com.aspose.psd.Point  в этом  com.aspose.psd.region . |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Проверяет, содержится ли указанная структура  com.aspose.psd.Point  в этом  com.aspose.psd.Region , когда он отрисован с использованием указанного  com.aspose.psd.graphics . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Проверяет, содержится ли указанная структура  com.aspose.psd.PointF  в этом  com.aspose.psd.region . |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Проверяет, содержится ли указанная структура  com.aspose.psd.PointF  в этом  com.aspose.psd.Region , когда он отрисован с использованием указанного  com.aspose.psd.graphics . |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | Проверяет, содержится ли какая‑либо часть указанной структуры  com.aspose.psd.Rectangle  в этом  com.aspose.psd.region . |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | Проверяет, содержится ли какая‑либо часть указанной структуры  com.aspose.psd.Rectangle  в этом  com.aspose.psd.Region , когда он отрисован с использованием указанного  com.aspose.psd.graphics . |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | Проверяет, содержится ли какая‑либо часть указанной структуры  com.aspose.psd.RectangleF  в этом  com.aspose.psd.region . |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | Проверяет, содержится ли какая‑либо часть указанной структуры  com.aspose.psd.RectangleF  в этом  com.aspose.psd.Region , когда он отрисован с использованием указанного  com.aspose.psd.graphics . |
| [isVisible(float x, float y)](#isVisible-float-float-) | Проверяет, содержится ли указанная точка в этом  com.aspose.psd.region . |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | Проверяет, содержится ли указанная точка в этом  com.aspose.psd.Region , когда он отрисован с использованием указанного  com.aspose.psd.graphics . |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника в этом  com.aspose.psd.region . |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого  com.aspose.psd.Region  при отрисовке с использованием указанного  com.aspose.psd.graphics . |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | Проверяет, содержится ли указанная точка внутри этого  com.aspose.psd.Region  объекта при отрисовке с использованием указанного  com.aspose.psd.Graphics  объекта. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Проверяет, содержится ли какая‑либо часть указанного прямоугольника в этом  com.aspose.psd.region . |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого  com.aspose.psd.Region  при отрисовке с использованием указанного  com.aspose.psd.graphics . |
| [makeEmpty()](#makeEmpty--) | Инициализирует этот  com.aspose.psd.Region  пустой внутренней областью. |
| [makeInfinite()](#makeInfinite--) | Инициализирует этот объект  com.aspose.psd.Region  бесконечной внутренней областью. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | Получает или задает регион при изменении. |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | Трансформирует этот  com.aspose.psd.Region  с помощью указанной  com.aspose.psd.matrix . |
| [translate(float dx, float dy)](#translate-float-float-) | Смещает координаты этого  com.aspose.psd.Region  на указанную величину. |
| [translate(int dx, int dy)](#translate-int-int-) | Смещает координаты этого  com.aspose.psd.Region  на указанную величину. |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | Обновляет этот  com.aspose.psd.Region  до объединения его с указанным  com.aspose.psd.graphicsPath . |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | Обновляет этот  com.aspose.psd.Region  до объединения его с указанной структурой  com.aspose.psd.Rectangle . |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | Обновляет этот  com.aspose.psd.Region  до объединения его с указанной структурой  com.aspose.psd.RectangleF . |
| [union(Region region)](#union-com.aspose.psd.Region-) | Обновляет этот  com.aspose.psd.Region  до объединения его с указанным  com.aspose.psd.region . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | Обновляет этот  com.aspose.psd.Region  до объединения за вычетом пересечения его с указанным  com.aspose.psd.graphicsPath . |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | Обновляет этот  com.aspose.psd.Region  до объединения за вычетом пересечения его с указанной структурой  com.aspose.psd.Rectangle . |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | Обновляет этот  com.aspose.psd.Region  до объединения за вычетом пересечения его с указанной структурой  com.aspose.psd.RectangleF . |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | Обновляет этот  com.aspose.psd.Region  до объединения за вычетом пересечения его с указанным  com.aspose.psd.region . |
### Region() {#Region--}
```
public Region()
```


Инициализирует новый T:Aspose.Imaging.Region.

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


Инициализирует новый T:Aspose.Imaging.Region из указанной структуры T:Aspose.Imaging.RectangleF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  T:Aspose.Imaging.RectangleF , определяющая внутреннюю часть нового  T:Aspose.Imaging.Region . |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


Инициализирует новый T:Aspose.Imaging.Region из указанной структуры T:Aspose.Imaging.Rectangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура  T:Aspose.Imaging.Rectangle , определяющая внутреннюю часть нового  T:Aspose.Imaging.Region . |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Инициализирует новый T:Aspose.Imaging.Region с указанным T:Aspose.Imaging.GraphicsPath.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект  T:Aspose.Imaging.GraphicsPath , определяющий новый  T:Aspose.Imaging.Region . |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Обновляет этот com.aspose.psd.Region, чтобы он содержал часть указанного com.aspose.psd.GraphicsPath, не пересекающуюся с этим com.aspose.psd.region.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект  com.aspose.psd.GraphicsPath  для дополнения этого  com.aspose.psd.region . |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


Обновляет этот com.aspose.psd.Region, чтобы он содержал часть указанной структуры com.aspose.psd.Rectangle, не пересекающуюся с этим com.aspose.psd.region.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle  для дополнения этого  com.aspose.psd.region . |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


Обновляет этот com.aspose.psd.Region, чтобы он содержал часть указанной структуры com.aspose.psd.RectangleF, не пересекающуюся с этим com.aspose.psd.region.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  com.aspose.psd.RectangleF  для дополнения этого  com.aspose.psd.region . |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


Обновляет этот  com.aspose.psd.Region  так, чтобы он содержал часть указанного  com.aspose.psd.Region , не пересекающуюся с этим  com.aspose.psd.region .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Объект  com.aspose.psd.Region  для дополнения этого объекта  com.aspose.psd.Region . |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Создаёт точную глубокую копию этого  com.aspose.psd.region .

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Обновляет этот  com.aspose.psd.Region  так, чтобы он содержал только часть его внутренней области, не пересекающуюся с указанным  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект  com.aspose.psd.GraphicsPath  для исключения из этого  com.aspose.psd.region . |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


Обновляет этот  com.aspose.psd.Region  так, чтобы он содержал только часть его внутренней области, не пересекающуюся с указанной структурой  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle  для исключения из этого  com.aspose.psd.region . |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


Обновляет этот  com.aspose.psd.Region  так, чтобы он содержал только часть его внутренней области, не пересекающуюся с указанной структурой  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  com.aspose.psd.RectangleF  для исключения из этого  com.aspose.psd.region . |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


Обновляет этот  com.aspose.psd.Region  так, чтобы он содержал только часть его внутренней области, не пересекающуюся с указанным  com.aspose.psd.region .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Объект  com.aspose.psd.Region  для исключения из этого  com.aspose.psd.region . |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


Получает действия области.

**Returns:**
com.aspose.internal.RegionAction[] - Действия региона.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(GraphicsPath path) {#intersect-com.aspose.psd.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Обновляет этот  com.aspose.psd.Region  до пересечения с указанным  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект  com.aspose.psd.GraphicsPath  для пересечения с этим  com.aspose.psd.region . |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Обновляет этот  com.aspose.psd.Region  до пересечения с указанной структурой  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle  для пересечения с этим  com.aspose.psd.region . |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Обновляет этот  com.aspose.psd.Region  до пересечения с указанной структурой  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  com.aspose.psd.RectangleF  для пересечения с этим  com.aspose.psd.region . |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


Обновляет этот  com.aspose.psd.Region  до пересечения с указанным  com.aspose.psd.region .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Объект  com.aspose.psd.Region  для пересечения с этим  com.aspose.psd.region . |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Проверяет, имеет ли этот  com.aspose.psd.Region  пустую внутреннюю область на указанной поверхности рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics, представляющий поверхность рисования. |

**Returns:**
boolean - true, если внутреннее пространство этого  com.aspose.psd.Region  пусто при применении преобразования, связанного с  g ; иначе false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Проверяет, идентичен ли указанный  com.aspose.psd.Region  этому  com.aspose.psd.Region  на указанной поверхности рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Объект  com.aspose.psd.Region  для тестирования. |
| g | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics, представляющий поверхность рисования. |

**Returns:**
boolean - True, если внутреннее пространство региона идентично внутреннему пространству этого региона при применении преобразования, связанного с параметром  g ; иначе false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Проверяет, имеет ли этот  com.aspose.psd.Region  бесконечную внутреннюю область на указанной поверхности рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics, представляющий поверхность рисования. |

**Returns:**
boolean - true, если внутреннее пространство этого  com.aspose.psd.Region  бесконечно при применении преобразования, связанного с  g ; иначе false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Проверяет, содержится ли указанная структура  com.aspose.psd.Point  в этом  com.aspose.psd.region .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Структура  com.aspose.psd.Point  для тестирования. |

**Returns:**
boolean - true, когда  point  содержится в этом  com.aspose.psd.Region ; иначе false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Проверяет, содержится ли указанная структура  com.aspose.psd.Point  в этом  com.aspose.psd.Region , когда он отрисован с использованием указанного  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Структура  com.aspose.psd.Point  для тестирования. |
| g | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics, представляющий графический контекст. |

**Returns:**
boolean - true, когда  point  содержится в этом  com.aspose.psd.Region ; иначе false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Проверяет, содержится ли указанная структура  com.aspose.psd.PointF  в этом  com.aspose.psd.region .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Структура  com.aspose.psd.PointF  для тестирования. |

**Returns:**
boolean - true, когда  point  содержится в этом  com.aspose.psd.Region ; иначе false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Проверяет, содержится ли указанная структура  com.aspose.psd.PointF  в этом  com.aspose.psd.Region , когда он отрисован с использованием указанного  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Структура  com.aspose.psd.PointF  для тестирования. |
| g | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics, представляющий графический контекст. |

**Returns:**
boolean - true, когда  point  содержится в этом  com.aspose.psd.Region ; иначе false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Проверяет, содержится ли какая‑либо часть указанной структуры  com.aspose.psd.Rectangle  в этом  com.aspose.psd.region .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle  для тестирования. |

**Returns:**
boolean - Этот метод возвращает true, когда любая часть  rect  содержится в этом  com.aspose.psd.Region ; иначе false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Проверяет, содержится ли какая‑либо часть указанной структуры  com.aspose.psd.Rectangle  в этом  com.aspose.psd.Region , когда он отрисован с использованием указанного  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle  для тестирования. |
| g | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics, представляющий графический контекст. |

**Returns:**
boolean - true, когда любая часть  rect  содержится в этом  com.aspose.psd.Region ; иначе false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Проверяет, содержится ли какая‑либо часть указанной структуры  com.aspose.psd.RectangleF  в этом  com.aspose.psd.region .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  com.aspose.psd.RectangleF  для тестирования. |

**Returns:**
boolean - true, когда любая часть  rect  содержится в этом  com.aspose.psd.Region ; иначе false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Проверяет, содержится ли какая‑либо часть указанной структуры  com.aspose.psd.RectangleF  в этом  com.aspose.psd.Region , когда он отрисован с использованием указанного  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  com.aspose.psd.RectangleF  для тестирования. |
| g | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics, представляющий графический контекст. |

**Returns:**
boolean - true, когда  rect  содержится в этом  com.aspose.psd.Region ; иначе false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Проверяет, содержится ли указанная точка в этом  com.aspose.psd.region .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | X‑координата точки для проверки. |
| y | float | Y‑координата точки для проверки. |

**Returns:**
boolean - True, когда указанный point содержится в этом  com.aspose.psd.Region ; иначе false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Проверяет, содержится ли указанная точка в этом  com.aspose.psd.Region , когда он отрисован с использованием указанного  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | X‑координата точки для проверки. |
| y | float | Y‑координата точки для проверки. |
| g | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics, представляющий графический контекст. |

**Returns:**
boolean - True, когда указанный point содержится в этом  com.aspose.psd.Region ; иначе false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Проверяет, содержится ли какая‑либо часть указанного прямоугольника в этом  com.aspose.psd.region .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x верхнего левого угла прямоугольника для тестирования. |
| y | float | Координата y верхнего левого угла прямоугольника для тестирования. |
| ширина | float | Ширина прямоугольника для тестирования. |
| высота | float | Высота прямоугольника для тестирования. |

**Returns:**
логический - true, когда любая часть указанного прямоугольника содержится в этом объекте com.aspose.psd.Region; иначе false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого  com.aspose.psd.Region  при отрисовке с использованием указанного  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x верхнего левого угла прямоугольника для тестирования. |
| y | float | Координата y верхнего левого угла прямоугольника для тестирования. |
| ширина | float | Ширина прямоугольника для тестирования. |
| высота | float | Высота прямоугольника для тестирования. |
| g | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics, представляющий графический контекст. |

**Returns:**
логический - true, когда любая часть указанного прямоугольника содержится в этом com.aspose.psd.Region; иначе false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Проверяет, содержится ли указанная точка внутри этого  com.aspose.psd.Region  объекта при отрисовке с использованием указанного  com.aspose.psd.Graphics  объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | X‑координата точки для проверки. |
| y | int | Y‑координата точки для проверки. |
| g | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics, представляющий графический контекст. |

**Returns:**
логический - true, когда указанная точка содержится в этом com.aspose.psd.Region; иначе false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Проверяет, содержится ли какая‑либо часть указанного прямоугольника в этом  com.aspose.psd.region .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x верхнего левого угла прямоугольника для тестирования. |
| y | int | Координата y верхнего левого угла прямоугольника для тестирования. |
| ширина | int | Ширина прямоугольника для тестирования. |
| высота | int | Высота прямоугольника для тестирования. |

**Returns:**
логический - true, когда любая часть указанного прямоугольника содержится в этом com.aspose.psd.Region; иначе false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого  com.aspose.psd.Region  при отрисовке с использованием указанного  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x верхнего левого угла прямоугольника для тестирования. |
| y | int | Координата y верхнего левого угла прямоугольника для тестирования. |
| ширина | int | Ширина прямоугольника для тестирования. |
| высота | int | Высота прямоугольника для тестирования. |
| g | [Graphics](../../com.aspose.psd/graphics) | Объект  com.aspose.psd.Graphics, представляющий графический контекст. |

**Returns:**
логический - true, когда любая часть указанного прямоугольника содержится в этом com.aspose.psd.Region; иначе false.
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Инициализирует этот  com.aspose.psd.Region  пустой внутренней областью.

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Инициализирует этот объект  com.aspose.psd.Region  бесконечной внутренней областью.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOnChangeRegion_internalized(ChangeActionList value) {#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-}
```
public final void setOnChangeRegion_internalized(ChangeActionList value)
```


Получает или задает регион при изменении.

Значение: Регион при изменении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.internal.ChangeActionList |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix matrix) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix matrix)
```


Трансформирует этот  com.aspose.psd.Region  с помощью указанной  com.aspose.psd.matrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Матрица com.aspose.psd.Matrix, с помощью которой преобразовать этот com.aspose.psd.region. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Смещает координаты этого  com.aspose.psd.Region  на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Величина смещения этого com.aspose.psd.Region по горизонтали. |
| dy | float | Величина смещения этого com.aspose.psd.Region по вертикали. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Смещает координаты этого  com.aspose.psd.Region  на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | int | Величина смещения этого com.aspose.psd.Region по горизонтали. |
| dy | int | Величина смещения этого com.aspose.psd.Region по вертикали. |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Обновляет этот  com.aspose.psd.Region  до объединения его с указанным  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект com.aspose.psd.GraphicsPath для объединения с этим com.aspose.psd.region. |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


Обновляет этот  com.aspose.psd.Region  до объединения его с указанной структурой  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура com.aspose.psd.Rectangle для объединения с этим com.aspose.psd.region. |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


Обновляет этот  com.aspose.psd.Region  до объединения его с указанной структурой  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура com.aspose.psd.RectangleF для объединения с этим com.aspose.psd.region. |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


Обновляет этот  com.aspose.psd.Region  до объединения его с указанным  com.aspose.psd.region .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Объект com.aspose.psd.Region для объединения с этим com.aspose.psd.region. |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Обновляет этот  com.aspose.psd.Region  до объединения за вычетом пересечения его с указанным  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект com.aspose.psd.GraphicsPath для операции XOR с этим com.aspose.psd.region. |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


Обновляет этот  com.aspose.psd.Region  до объединения за вычетом пересечения его с указанной структурой  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура com.aspose.psd.Rectangle для операции XOR с этим com.aspose.psd.region. |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


Обновляет этот  com.aspose.psd.Region  до объединения за вычетом пересечения его с указанной структурой  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура com.aspose.psd.RectangleF для операции XOR с этим com.aspose.psd.region. |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


Обновляет этот  com.aspose.psd.Region  до объединения за вычетом пересечения его с указанным  com.aspose.psd.region .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Объект com.aspose.psd.Region для операции XOR с этим com.aspose.psd.region. |

