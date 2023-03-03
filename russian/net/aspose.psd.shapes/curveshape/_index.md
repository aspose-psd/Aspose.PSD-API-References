---
title: Class CurveShape
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.Shapes.CurveShape сорт. Представляет форму изогнутого сплайна.
type: docs
weight: 5480
url: /ru/net/aspose.psd.shapes/curveshape/
---
## CurveShape class

Представляет форму изогнутого сплайна.

```csharp
public sealed class CurveShape : PolygonShape
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | Инициализирует новый экземпляр`CurveShape` класс. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | Инициализирует новый экземпляр`CurveShape` сорт. Используется натяжение по умолчанию 0,5. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | Инициализирует новый экземпляр`CurveShape` сорт. Используется натяжение по умолчанию 0,5. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | Инициализирует новый экземпляр`CurveShape` класс. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | Инициализирует новый экземпляр`CurveShape` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | Получает границы объекта. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | Получает центр фигуры. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Получает конечную точку формы. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Получает значение, указывающее, есть ли у фигуры сегменты. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Получает или задает значение, указывающее, закрыта ли фигура. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Получает или задает точки кривой. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | Получает сегменты формы. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Получает начальную точку формы. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | Получает или задает натяжение кривой. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | Получает границы объекта. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Меняет порядок точек этой фигуры на обратный. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Применяет указанное преобразование к фигуре. |

### Смотрите также

* class [PolygonShape](../polygonshape/)
* пространство имен [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* сборка [Aspose.PSD](../../)


