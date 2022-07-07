---
title: Region
second_title: Справочник по Aspose.PSD для .NET API
description: Описывает внутреннюю часть графической фигуры состоящей из прямоугольников и путей. Этот класс не может быть унаследован.
type: docs
weight: 5240
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
| [Region](region#constructor)() | Инициализирует новый[`Region`](../region). |
| [Region](region#constructor_1)(GraphicsPath) | Инициализирует новый[`Region`](../region)с указанным[`GraphicsPath`](../graphicspath). |
| [Region](region#constructor_2)(Rectangle) | Инициализирует новый[`Region`](../region)из указанного[`Rectangle`](../rectangle)структура. |
| [Region](region#constructor_3)(RectangleF) | Инициализирует новый[`Region`](../region)из указанного[`RectangleF`](../rectanglef)структура. |

## Методы

| Имя | Описание |
| --- | --- |
| [Complement](../../aspose.psd/region/complement#complement)(GraphicsPath) | Обновляет этот файл[`Region`](../region), чтобы он содержал часть указанного[`GraphicsPath`](../graphicspath)который не пересекается с этим[`Region`](../region). |
| [Complement](../../aspose.psd/region/complement#complement_1)(Rectangle) | Обновляет этот файл[`Region`](../region), чтобы он содержал часть указанногоСтруктураRectangle, которая не пересекается с этой[`Region`](../region). |
| [Complement](../../aspose.psd/region/complement#complement_2)(RectangleF) | Обновляет этот файл[`Region`](../region), чтобы он содержал часть указанногоСтруктураRectangleF, которая не пересекается с этой[`Region`](../region). |
| [Complement](../../aspose.psd/region/complement#complement_3)(Region) | Обновляет этот файл[`Region`](../region), чтобы он содержал часть указанного[`Region`](../region)который не пересекается с этим[`Region`](../region). |
| [DeepClone](../../aspose.psd/region/deepclone)() | Создает точную глубокую копию этого[`Region`](../region). |
| [Equals](../../aspose.psd/region/equals#equals)(Region, Graphics) | Проверяет, идентичен ли указанный[`Region`](../region)этому[`Region`](../region)на указанной поверхности рисования. |
| [Exclude](../../aspose.psd/region/exclude#exclude)(GraphicsPath) | Обновляет этот[`Region`](../region), чтобы он содержал только ту часть его внутренней части, которая не пересекается с указанным[`GraphicsPath`](../graphicspath). |
| [Exclude](../../aspose.psd/region/exclude#exclude_1)(Rectangle) | Обновляет этот[`Region`](../region), чтобы он содержал только ту часть его внутренней части, которая не пересекается с указанным[`Rectangle`](../rectangle)структура. |
| [Exclude](../../aspose.psd/region/exclude#exclude_2)(RectangleF) | Обновляет этот[`Region`](../region), чтобы он содержал только ту часть его внутренней части, которая не пересекается с указанным[`RectangleF`](../rectanglef)структура. |
| [Exclude](../../aspose.psd/region/exclude#exclude_3)(Region) | Обновляет этот[`Region`](../region), чтобы он содержал только ту часть его внутренней части, которая не пересекается с указанным[`Region`](../region). |
| [Intersect](../../aspose.psd/region/intersect#intersect)(GraphicsPath) | Обновляет этот[`Region`](../region)до пересечения себя с указаннымПутькграфике. |
| [Intersect](../../aspose.psd/region/intersect#intersect_1)(Rectangle) | Обновляет этот[`Region`](../region)до пересечения себя с указанным[`Rectangle`](../rectangle)структура. |
| [Intersect](../../aspose.psd/region/intersect#intersect_2)(RectangleF) | Обновляет этот[`Region`](../region)до пересечения себя с указанным[`RectangleF`](../rectanglef)структура. |
| [Intersect](../../aspose.psd/region/intersect#intersect_3)(Region) | Обновляет этот[`Region`](../region)до пересечения себя с указаннымОбласть,край. |
| [IsEmpty](../../aspose.psd/region/isempty)(Graphics) | Проверяет, имеет ли этот[`Region`](../region)пустую внутреннюю часть на указанной поверхности рисования. |
| [IsInfinite](../../aspose.psd/region/isinfinite)(Graphics) | Проверяет, имеет ли этот[`Region`](../region)бесконечный внутренний объем на указанной поверхности рисования. |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible)(Point) | Проверяет, содержится ли указанная структура[`Point`](../point)в этомОбласть,край. |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_2)(PointF) | Проверяет, содержится ли указанная структура[`PointF`](../pointf)в этомОбласть,край. |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_4)(Rectangle) | Проверяет, содержится ли какая-либо часть указанной[`Rectangle`](../rectangle)структуры в этомРегион. |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_6)(RectangleF) | Проверяет, содержится ли какая-либо часть указанной структуры[`RectangleF`](../rectanglef)внутри этойРегион. |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_11)(float, float) | Проверяет, содержится ли указанная точка в этом[`Region`](../region). |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_1)(Point, Graphics) | Проверяет, содержится ли указанная структура[`Point`](../point)в этом[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_3)(PointF, Graphics) | Проверяет, содержится ли указанная структура[`PointF`](../pointf)в этом[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_5)(Rectangle, Graphics) | Проверяет, содержится ли какая-либо часть указанной[`Rectangle`](../rectangle)структуры в этом[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_7)(RectangleF, Graphics) | Проверяет, содержится ли какая-либо часть указанной структуры[`RectangleF`](../rectanglef)внутри этой[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_12)(float, float, Graphics) | Проверяет, содержится ли указанная точка в этом[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_8)(int, int, Graphics) | Проверяет, содержится ли указанная точка в этом объекте[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics)объект. |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_13)(float, float, float, float) | Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../region). |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_9)(int, int, int, int) | Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../region). |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_14)(float, float, float, float, Graphics) | Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_10)(int, int, int, int, Graphics) | Проверяет, содержится ли какая-либо часть указанного прямоугольника в этом[`Region`](../region)при рисовании с использованием указанного[`Graphics`](../graphics). |
| [MakeEmpty](../../aspose.psd/region/makeempty)() | Инициализирует этот[`Region`](../region)пустым внутренним пространством. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite)() | Инициализирует этот[`Region`](../region)объект бесконечной внутренней частью. |
| [Transform](../../aspose.psd/region/transform)(Matrix) | Преобразует этот[`Region`](../region)по указанному[`Matrix`](../matrix). |
| [Translate](../../aspose.psd/region/translate#translate_1)(float, float) | Смещает координаты этого[`Region`](../region)на указанную величину. |
| [Translate](../../aspose.psd/region/translate#translate)(int, int) | Смещает координаты этого[`Region`](../region)на указанную величину. |
| [Union](../../aspose.psd/region/union#union)(GraphicsPath) | Обновляет этот[`Region`](../region)до объединения самого себя и указанногоПутькграфике. |
| [Union](../../aspose.psd/region/union#union_1)(Rectangle) | Обновляет этот[`Region`](../region)до объединения самого себя и указанного[`Rectangle`](../rectangle)структура. |
| [Union](../../aspose.psd/region/union#union_2)(RectangleF) | Обновляет этот[`Region`](../region)до объединения самого себя и указанного[`RectangleF`](../rectanglef)структура. |
| [Union](../../aspose.psd/region/union#union_3)(Region) | Обновляет этот[`Region`](../region)до объединения самого себя и указанногоОбласть,край. |
| [Xor](../../aspose.psd/region/xor#xor)(GraphicsPath) | Обновляет этот[`Region`](../region)до объединения минус пересечение самого себя с указанным[`GraphicsPath`](../graphicspath). |
| [Xor](../../aspose.psd/region/xor#xor_1)(Rectangle) | Обновляет этот[`Region`](../region)до объединения минус пересечение самого себя с указанным[`Rectangle`](../rectangle)структура. |
| [Xor](../../aspose.psd/region/xor#xor_2)(RectangleF) | Обновляет этот[`Region`](../region)до объединения минус пересечение самого себя с указанным[`RectangleF`](../rectanglef)структура. |
| [Xor](../../aspose.psd/region/xor#xor_3)(Region) | Обновляет этот[`Region`](../region)до объединения минус пересечение самого себя с указанным[`Region`](../region). |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
