---
title: "Region.IsVisible"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Region. Проверяет, содержится ли указанная точка внутри этого Region"
type: docs
weight: 100
url: /ru/net/aspose.psd/region/isvisible/
---
{{< psd/tize >}}
## IsVisible(float, float) {#isvisible_11}

Проверяет, содержится ли указанная точка внутри этого [`Region`](../).

```csharp
public bool IsVisible(float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Single | Координата x проверяемой точки. |
| y | Single | Координата y проверяемой точки. |

### Возвращаемое значение

Истина, если указанная точка содержится внутри этого [`Region`](../); иначе — ложь.

### См. также

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(PointF) {#isvisible_2}

Проверяет, содержится ли указанная структура [`PointF`](../../pointf/) внутри этого [`Region`](../).

```csharp
public bool IsVisible(PointF point)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | PointF | Структура [`PointF`](../../pointf/) для проверки. |

### Возвращаемое значение

истина, если *point* содержится внутри этого [`Region`](../); иначе — ложь.

### См. также

* struct [PointF](../../pointf/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, Graphics) {#isvisible_12}

Проверяет, содержится ли указанная точка внутри этого [`Region`](../), когда он отрисован с использованием указанного [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(float x, float y, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Single | Координата x проверяемой точки. |
| y | Single | Координата y проверяемой точки. |
| g | Graphics | [`Graphics`](../../graphics/) — объект, представляющий графический контекст. |

### Возвращаемое значение

Истина, если указанная точка содержится внутри этого [`Region`](../); иначе — ложь.

### См. также

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(PointF, Graphics) {#isvisible_3}

Проверяет, содержится ли указанная структура [`PointF`](../../pointf/) внутри этого [`Region`](../), когда он отрисован с использованием указанного [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(PointF point, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | PointF | Структура [`PointF`](../../pointf/) для проверки. |
| g | Graphics | [`Graphics`](../../graphics/) — объект, представляющий графический контекст. |

### Возвращаемое значение

истина, если *point* содержится внутри этого [`Region`](../); иначе — ложь.

### См. также

* struct [PointF](../../pointf/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, float, float) {#isvisible_13}

Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого [`Region`](../).

```csharp
public bool IsVisible(float x, float y, float width, float height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Single | Координата x левого верхнего угла проверяемого прямоугольника. |
| y | Single | Координата y левого верхнего угла проверяемого прямоугольника. |
| width | Single | Ширина проверяемого прямоугольника. |
| height | Single | Высота проверяемого прямоугольника. |

### Возвращаемое значение

истина, если какая-либо часть указанного прямоугольника содержится внутри объекта [`Region`](../); иначе — ложь.

### См. также

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(RectangleF) {#isvisible_6}

Проверяет, содержится ли какая-либо часть указанной структуры [`RectangleF`](../../rectanglef/) внутри этого [`Region`](../).

```csharp
public bool IsVisible(RectangleF rect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | RectangleF | Структура [`RectangleF`](../../rectanglef/) для проверки. |

### Возвращаемое значение

true, когда любая часть *rect* содержится в этом [`Region`](../); в противном случае — false.

### См. также

* struct [RectangleF](../../rectanglef/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, float, float, Graphics) {#isvisible_14}

Проверяет, содержится ли любая часть указанного прямоугольника в этом [`Region`](../), когда он отрисован с использованием указанного [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(float x, float y, float width, float height, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Single | Координата x левого верхнего угла проверяемого прямоугольника. |
| y | Single | Координата y левого верхнего угла проверяемого прямоугольника. |
| width | Single | Ширина проверяемого прямоугольника. |
| height | Single | Высота проверяемого прямоугольника. |
| g | Graphics | [`Graphics`](../../graphics/) — объект, представляющий графический контекст. |

### Возвращаемое значение

true, когда любая часть указанного прямоугольника содержится в этом [`Region`](../); в противном случае — false.

### См. также

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(RectangleF, Graphics) {#isvisible_7}

Проверяет, содержится ли любая часть указанной структуры [`RectangleF`](../../rectanglef/) в этом [`Region`](../), когда он отрисован с использованием указанного [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(RectangleF rect, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | RectangleF | Структура [`RectangleF`](../../rectanglef/) для проверки. |
| g | Graphics | [`Graphics`](../../graphics/) — объект, представляющий графический контекст. |

### Возвращаемое значение

true, когда *rect* содержится в этом [`Region`](../); в противном случае — false.

### См. также

* struct [RectangleF](../../rectanglef/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, Graphics) {#isvisible_8}

Проверяет, содержится ли указанная точка в объекте [`Region`](../), когда он отрисован с использованием указанного объекта [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(int x, int y, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Int32 | Координата x проверяемой точки. |
| y | Int32 | Координата y проверяемой точки. |
| g | Graphics | [`Graphics`](../../graphics/) — объект, представляющий графический контекст. |

### Возвращаемое значение

true, когда указанная точка содержится в этом [`Region`](../); в противном случае — false.

### См. также

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Point) {#isvisible}

Проверяет, содержится ли указанная структура [`Point`](../../point/) в этом [`Region`](../).

```csharp
public bool IsVisible(Point point)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | Point | Структура [`Point`](../../point/) для проверки. |

### Возвращаемое значение

истина, если *point* содержится внутри этого [`Region`](../); иначе — ложь.

### См. также

* struct [Point](../../point/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Point, Graphics) {#isvisible_1}

Проверяет, содержится ли указанная структура [`Point`](../../point/) в этом [`Region`](../), когда он отрисован с использованием указанного [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(Point point, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | Point | Структура [`Point`](../../point/) для проверки. |
| g | Graphics | [`Graphics`](../../graphics/) — объект, представляющий графический контекст. |

### Возвращаемое значение

истина, если *point* содержится внутри этого [`Region`](../); иначе — ложь.

### См. также

* struct [Point](../../point/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, int, int) {#isvisible_9}

Проверяет, содержится ли какая-либо часть указанного прямоугольника внутри этого [`Region`](../).

```csharp
public bool IsVisible(int x, int y, int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Int32 | Координата x левого верхнего угла проверяемого прямоугольника. |
| y | Int32 | Координата y левого верхнего угла проверяемого прямоугольника. |
| width | Int32 | Ширина проверяемого прямоугольника. |
| height | Int32 | Высота проверяемого прямоугольника. |

### Возвращаемое значение

true, когда любая часть указанного прямоугольника содержится в этом [`Region`](../); в противном случае — false.

### См. также

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Rectangle) {#isvisible_4}

Проверяет, содержится ли любая часть указанной структуры [`Rectangle`](../../rectangle/) в этом [`Region`](../).

```csharp
public bool IsVisible(Rectangle rect)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Структура [`Rectangle`](../../rectangle/) для проверки. |

### Возвращаемое значение

Этот метод возвращает true, когда любая часть *rect* содержится в этом [`Region`](../); в противном случае — false.

### См. также

* struct [Rectangle](../../rectangle/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, int, int, Graphics) {#isvisible_10}

Проверяет, содержится ли любая часть указанного прямоугольника в этом [`Region`](../), когда он отрисован с использованием указанного [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(int x, int y, int width, int height, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Int32 | Координата x левого верхнего угла проверяемого прямоугольника. |
| y | Int32 | Координата y левого верхнего угла проверяемого прямоугольника. |
| width | Int32 | Ширина проверяемого прямоугольника. |
| height | Int32 | Высота проверяемого прямоугольника. |
| g | Graphics | [`Graphics`](../../graphics/) — объект, представляющий графический контекст. |

### Возвращаемое значение

true, когда любая часть указанного прямоугольника содержится в этом [`Region`](../); в противном случае — false.

### См. также

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Rectangle, Graphics) {#isvisible_5}

Проверяет, содержится ли любая часть указанной структуры [`Rectangle`](../../rectangle/) в этом [`Region`](../), когда он отрисован с использованием указанного [`Graphics`](../../graphics/).

```csharp
public bool IsVisible(Rectangle rect, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Структура [`Rectangle`](../../rectangle/) для проверки. |
| g | Graphics | [`Graphics`](../../graphics/) — объект, представляющий графический контекст. |

### Возвращаемое значение

true, когда любая часть *rect* содержится в этом [`Region`](../); в противном случае — false.

### См. также

* struct [Rectangle](../../rectangle/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


