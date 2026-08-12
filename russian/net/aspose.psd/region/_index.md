---
title: "Класс Region"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Region. Описывает внутреннюю часть графической фигуры, состоящей из прямоугольников и путей. Этот класс не может быть наследован."
type: docs
weight: 5860
url: /ru/net/aspose.psd/region/
---
{{< psd/tize >}}
## Region class

Описывает внутреннюю часть графической формы, состоящей из прямоугольников и путей. Этот класс не может быть наследован.

```csharp
public sealed class Region
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Region](region/#constructor)() | Инициализирует новый `Region`. |
| [Region](region/#constructor_1)(GraphicsPath) | Инициализирует новый `Region` с указанным [`GraphicsPath`](../graphicspath/). |
| [Region](region/#constructor_2)(Rectangle) | Инициализирует новый `Region` из указанной структуры [`Rectangle`](../rectangle/). |
| [Region](region/#constructor_3)(RectangleF) | Инициализирует новый `Region` из указанной структуры [`RectangleF`](../rectanglef/). |

## Методы

| Имя | Описание |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | Обновляет этот `Region`, чтобы он содержал часть указанного [`GraphicsPath`](../graphicspath/), которая не пересекается с этим `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | Обновляет этот `Region`, чтобы он содержал часть указанного [`Rectangle`](../rectangle/) структуры, которая не пересекается с этим `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | Обновляет этот `Region`, чтобы он содержал часть указанного [`RectangleF`](../rectanglef/) структуры, которая не пересекается с этим `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | Обновляет этот `Region`, чтобы он содержал часть указанного `Region`, которая не пересекается с этим `Region`. |
| [DeepClone](../../aspose.psd/region/deepclone/)() | Создаёт точную глубокую копию этого `Region`. |
| override [Equals](../../aspose.psd/region/equals/#equals_1)(object) | Проверьте, равны ли объекты. |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | Проверяет, является ли указанный `Region` идентичным этому `Region` на указанной поверхности рисования. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | Обновляет этот `Region`, чтобы он содержал только ту часть своего внутреннего пространства, которая не пересекается с указанным [`GraphicsPath`](../graphicspath/). |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | Обновляет этот `Region`, чтобы он содержал только ту часть своего внутреннего пространства, которая не пересекается с указанной структурой [`Rectangle`](../rectangle/). |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | Обновляет этот `Region`, чтобы он содержал только ту часть своего внутреннего пространства, которая не пересекается с указанной структурой [`RectangleF`](../rectanglef/). |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | Обновляет этот `Region`, чтобы он содержал только ту часть своего внутреннего пространства, которая не пересекается с указанным `Region`. |
| override [GetHashCode](../../aspose.psd/region/gethashcode/)() | Получите хеш‑код текущего объекта. |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | Обновляет этот `Region`, делая его пересечением с указанным [`GraphicsPath`](../graphicspath/). |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | Обновляет этот `Region`, делая его пересечением с указанной структурой [`Rectangle`](../rectangle/). |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | Обновляет этот `Region`, делая его пересечением с указанной структурой [`RectangleF`](../rectanglef/). |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | Обновляет этот `Region`, делая его пересечением с указанным `Region`. |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | Проверяет, имеет ли этот `Region` пустое внутреннее пространство на указанной поверхности рисования. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | Проверяет, имеет ли этот `Region` бесконечное внутреннее пространство на указанной поверхности рисования. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | Проверяет, содержится ли указанная структура [`Point`](../point/) внутри этого `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | Проверяет, содержится ли указанная структура [`PointF`](../pointf/) внутри этого `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | Проверяет, содержится ли какая-либо часть указанной структуры [`Rectangle`](../rectangle/) внутри этого `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | Проверяет, содержится ли какая-либо часть указанной структуры [`RectangleF`](../rectanglef/) внутри этого `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | Проверяет, содержится ли указанная точка внутри этого `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | Проверяет, содержится ли указанная структура [`Point`](../point/) внутри этого `Region`, когда она отрисована с использованием указанного [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | Проверяет, содержится ли указанная структура [`PointF`](../pointf/) внутри этого `Region`, когда она отрисована с использованием указанного [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | Проверяет, содержится ли какая-либо часть указанной структуры [`Rectangle`](../rectangle/) внутри этого `Region`, когда она отрисована с использованием указанного [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | Проверяет, содержит ли эта `Region` любую часть указанной структуры [`RectangleF`](../rectanglef/) при отрисовке с использованием указанного [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | Проверяет, содержится ли указанная точка в этой `Region` при отрисовке с использованием указанного [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | Проверяет, содержится ли указанная точка в объекте `Region` при отрисовке с использованием указанного объекта [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | Проверяет, содержит ли эта `Region` любую часть указанного прямоугольника. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | Проверяет, содержит ли эта `Region` любую часть указанного прямоугольника. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | Проверяет, содержит ли эта `Region` любую часть указанного прямоугольника при отрисовке с использованием указанного [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | Проверяет, содержит ли эта `Region` любую часть указанного прямоугольника при отрисовке с использованием указанного [`Graphics`](../graphics/). |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | Инициализирует эту `Region` пустым внутренним пространством. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | Инициализирует объект `Region` бесконечным внутренним пространством. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | Трансформирует эту `Region` с помощью указанной [`Matrix`](../matrix/). |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | Смещает координаты этой `Region` на указанную величину. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | Смещает координаты этой `Region` на указанную величину. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | Обновляет эту `Region`, объединяя её с указанным [`GraphicsPath`](../graphicspath/). |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | Обновляет эту `Region`, объединяя её с указанной структурой [`Rectangle`](../rectangle/). |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | Обновляет эту `Region`, объединяя её с указанной структурой [`RectangleF`](../rectanglef/). |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | Обновляет эту `Region`, объединяя её с указанной `Region`. |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | Обновляет эту `Region`, объединяя её за вычетом пересечения с указанным [`GraphicsPath`](../graphicspath/). |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | Обновляет эту `Region`, объединяя её за вычетом пересечения с указанной структурой [`Rectangle`](../rectangle/). |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | Обновляет эту `Region`, объединяя её за вычетом пересечения с указанной структурой [`RectangleF`](../rectanglef/). |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | Обновляет эту `Region`, объединяя её за вычетом пересечения с указанной `Region`. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


