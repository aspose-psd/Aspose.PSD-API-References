---
title: "Класс CurveShape"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.Shapes.CurveShape класс. Представляет изогнутую сплайн‑форму"
type: docs
weight: 5980
url: /ru/net/aspose.psd.shapes/curveshape/
---
{{< psd/tize >}}
## CurveShape class

Представляет изогнутую форму сплайна.

```csharp
public sealed class CurveShape : PolygonShape
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | Инициализирует новый экземпляр класса `CurveShape`. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | Инициализирует новый экземпляр класса `CurveShape`. Используется напряжение по умолчанию 0,5. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | Инициализирует новый экземпляр класса `CurveShape`. Используется напряжение по умолчанию 0,5. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | Инициализирует новый экземпляр класса `CurveShape`. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | Инициализирует новый экземпляр класса `CurveShape`. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | Получает границы объекта. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | Получает центр формы. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Получает конечную точку фигуры. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Получает значение, указывающее, имеет ли форма сегменты. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Получает или задает значение, указывающее, закрыта ли фигура. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Получает или задает точки кривой. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | Получает сегменты фигуры. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Получает начальную точку фигуры. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | Получает или задает напряжение кривой. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | Получает границы объекта. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Изменяет порядок точек для этой фигуры. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Применяет указанное преобразование к фигуре. |

### См. также

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


