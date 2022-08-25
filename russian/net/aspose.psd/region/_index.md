---
title: Region
second_title: Справочник по Aspose.PSD для .NET API
description: Описывает внутреннюю часть графической фигуры состоящей из прямоугольников и путей. Этот класс не может быть унаследован.
type: docs
weight: 5290
url: /ru/net/aspose.psd/region/
---
## Region class

Описывает внутреннюю часть графической фигуры, состоящей из прямоугольников и путей. Этот класс не может быть унаследован.

```csharp
public sealed class Region
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Region](region#constructor)() | Инициализирует новый[`Region`](../region) . |
| [Region](region#constructor_1)(GraphicsPath) | Инициализирует новый[`Region`](../region) с указанным[`GraphicsPath`](../graphicspath) . |
| [Region](region#constructor_2)(Rectangle) | Инициализирует новый[`Region`](../region) из указанного[`Rectangle`](../rectangle)структура. |
| [Region](region#constructor_3)(RectangleF) | Инициализирует новый[`Region`](../region) из указанного[`RectangleF`](../rectanglef)структура. |

## Методы

| Имя | Описание |
| --- | --- |
| [Complement](../../aspose.psd/region/complement#complement)(GraphicsPath) | Обновляет это[`Region`](../region) содержать часть указанного[`GraphicsPath`](../graphicspath) что не пересекается с этим[`Region`](../region) . |
| [Complement](../../aspose.psd/region/complement#complement_1)(Rectangle) | Обновляет это[`Region`](../region) содержать часть указанного[`Rectangle`](../rectangle) структура, которая не пересекается с этим[`Region`](../region) . |
| [Complement](../../aspose.psd/region/complement#complement_2)(RectangleF) | Обновляет это[`Region`](../region) содержать часть указанного[`RectangleF`](../rectanglef) структура, которая не пересекается с этим[`Region`](../region) . |
| [Complement](../../aspose.psd/region/complement#complement_3)(Region) | Обновляет это[`Region`](../region) содержать часть указанного[`Region`](../region) что не пересекается с этим[`Region`](../region) . |
| [DeepClone](../../aspose.psd/region/deepclone)() | Создает точную глубокую копию этого[`Region`](../region) . |
| [Equals](../../aspose.psd/region/equals#equals)(Region, Graphics) | Проверяет, указанный[`Region`](../region) идентичен этому[`Region`](../region) на указанной поверхности рисования. |
| [Exclude](../../aspose.psd/region/exclude#exclude)(GraphicsPath) | Обновляет это[`Region`](../region) содержать только ту часть его внутренней части, которая не пересекается с указанным[`GraphicsPath`](../graphicspath) . |
| [Exclude](../../aspose.psd/region/exclude#exclude_1)(Rectangle) | Обновляет это[`Region`](../region) содержать только ту часть его внутренней части, которая не пересекается с указанным[`Rectangle`](../rectangle)структура. |
| [Exclude](../../aspose.psd/region/exclude#exclude_2)(RectangleF) | Обновляет это[`Region`](../region) содержать только ту часть его внутренней части, которая не пересекается с указанным[`RectangleF`](../rectanglef)структура. |
| [Exclude](../../aspose.psd/region/exclude#exclude_3)(Region) | Обновляет это[`Region`](../region) содержать только ту часть его внутренней части, которая не пересекается с указанным[`Region`](../region) . |
| [Intersect](../../aspose.psd/region/intersect#intersect)(GraphicsPath) | Обновляет это[`Region`](../region) до пересечения себя с указанным[`GraphicsPath`](../graphicspath) . |
| [Intersect](../../aspose.psd/region/intersect#intersect_1)(Rectangle) | Обновляет это[`Region`](../region) до пересечения себя с указанным[`Rectangle`](../rectangle)структура. |
| [Intersect](../../aspose.psd/region/intersect#intersect_2)(RectangleF) | Обновляет это[`Region`](../region) до пересечения себя с указанным[`RectangleF`](../rectanglef)структура. |
| [Intersect](../../aspose.psd/region/intersect#intersect_3)(Region) | Обновляет это[`Region`](../region) до пересечения себя с указанным[`Region`](../region) . |
| [IsEmpty](../../aspose.psd/region/isempty)(Graphics) | Проверяет, является ли это[`Region`](../region) имеет пустую внутреннюю часть на указанной поверхности рисования. |
| [IsInfinite](../../aspose.psd/region/isinfinite)(Graphics) | Проверяет, является ли это[`Region`](../region) имеет бесконечную внутреннюю часть на указанной поверхности рисования. |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible)(Point) | Проверяет, указанный[`Point`](../point)структура содержится в этом[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_2)(PointF) | Проверяет, указанный[`PointF`](../pointf)структура содержится в этом[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_4)(Rectangle) | Проверяет, является ли какая-либо часть указанного[`Rectangle`](../rectangle)структура содержится в этом[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_6)(RectangleF) | Проверяет, является ли какая-либо часть указанного[`RectangleF`](../rectanglef)структура содержится в этом[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_11)(float, float) | Проверяет, содержится ли указанная точка в этом[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_1)(Point, Graphics) | Проверяет, указанный[`Point`](../point)структура содержится в этом[`Region`](../region) при рисовании с использованием указанного[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_3)(PointF, Graphics) | Проверяет, указанный[`PointF`](../pointf)структура содержится в этом[`Region`](../region) при рисовании с использованием указанного[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_5)(Rectangle, Graphics) | Проверяет, является ли какая-либо часть указанного[`Rectangle`](../rectangle)структура содержится в этом[`Region`](../region) при рисовании с использованием указанного[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_7)(RectangleF, Graphics) | Проверяет, является ли какая-либо часть указанного[`RectangleF`](../rectanglef)структура содержится в этом[`Region`](../region) при рисовании с использованием указанного[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_12)(float, float, Graphics) | Проверяет, содержится ли указанная точка в этом[`Region`](../region) при рисовании с использованием указанного[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_8)(int, int, Graphics) | Проверяет, содержится ли указанная точка в этом[`Region`](../region) объект при рисовании с использованием указанного[`Graphics`](../graphics) объект. |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_13)(float, float, float, float) | Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_9)(int, int, int, int) | Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../region) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_14)(float, float, float, float, Graphics) | Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../region) при рисовании с использованием указанного[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_10)(int, int, int, int, Graphics) | Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../region) при рисовании с использованием указанного[`Graphics`](../graphics) . |
| [MakeEmpty](../../aspose.psd/region/makeempty)() | Инициализирует это[`Region`](../region) в пустой интерьер. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite)() | Инициализирует это[`Region`](../region) объект в бесконечный интерьер. |
| [Transform](../../aspose.psd/region/transform)(Matrix) | Преобразует это[`Region`](../region) указанным[`Matrix`](../matrix) . |
| [Translate](../../aspose.psd/region/translate#translate_1)(float, float) | Смещает координаты этого[`Region`](../region) на указанную сумму. |
| [Translate](../../aspose.psd/region/translate#translate)(int, int) | Смещает координаты этого[`Region`](../region) на указанную сумму. |
| [Union](../../aspose.psd/region/union#union)(GraphicsPath) | Обновляет это[`Region`](../region) к союзу самого себя и указанного[`GraphicsPath`](../graphicspath) . |
| [Union](../../aspose.psd/region/union#union_1)(Rectangle) | Обновляет это[`Region`](../region) к союзу самого себя и указанного[`Rectangle`](../rectangle)структура. |
| [Union](../../aspose.psd/region/union#union_2)(RectangleF) | Обновляет это[`Region`](../region) к союзу самого себя и указанного[`RectangleF`](../rectanglef)структура. |
| [Union](../../aspose.psd/region/union#union_3)(Region) | Обновляет это[`Region`](../region) к союзу самого себя и указанного[`Region`](../region) . |
| [Xor](../../aspose.psd/region/xor#xor)(GraphicsPath) | Обновляет это[`Region`](../region) на объединение минус пересечение себя с указанным[`GraphicsPath`](../graphicspath) . |
| [Xor](../../aspose.psd/region/xor#xor_1)(Rectangle) | Обновляет это[`Region`](../region) на объединение минус пересечение себя с указанным[`Rectangle`](../rectangle)структура. |
| [Xor](../../aspose.psd/region/xor#xor_2)(RectangleF) | Обновляет это[`Region`](../region) на объединение минус пересечение себя с указанным[`RectangleF`](../rectanglef)структура. |
| [Xor](../../aspose.psd/region/xor#xor_3)(Region) | Обновляет это[`Region`](../region) на объединение минус пересечение себя с указанным[`Region`](../region) . |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
