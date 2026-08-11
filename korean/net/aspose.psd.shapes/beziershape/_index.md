---
title: "클래스 BezierShape"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Shapes.BezierShape 클래스. 베지어 스플라인을 나타냅니다"
type: docs
weight: 5970
url: /ko/net/aspose.psd.shapes/beziershape/
---
{{< psd/tize >}}
## BezierShape class

베지어 스플라인을 나타냅니다.

```csharp
public sealed class BezierShape : PolygonShape
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BezierShape](beziershape/#constructor)() | `BezierShape` 클래스의 새 인스턴스를 초기화합니다. |
| [BezierShape](beziershape/#constructor_1)(PointF[]) | `BezierShape` 클래스의 새 인스턴스를 초기화합니다. |
| [BezierShape](beziershape/#constructor_2)(PointF[], bool) | `BezierShape` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/beziershape/bounds/) { get; } | 객체의 경계를 가져옵니다. |
| override [Center](../../aspose.psd.shapes/beziershape/center/) { get; } | 형태의 중심을 가져옵니다. |
| override [EndPoint](../../aspose.psd.shapes/beziershape/endpoint/) { get; } | 끝 모양 점을 가져옵니다. |
| override [HasSegments](../../aspose.psd.shapes/beziershape/hassegments/) { get; } | 형태에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | 모양이 닫혀 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | 곡선 점을 가져오거나 설정합니다. |
| override [Segments](../../aspose.psd.shapes/beziershape/segments/) { get; } | 모양 세그먼트를 가져옵니다. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | 시작 모양 점을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/beziershape/getbounds/#getbounds)(Matrix) | 객체의 경계를 가져옵니다. |
| override [GetBounds](../../aspose.psd.shapes/beziershape/getbounds/#getbounds_1)(Matrix, Pen) | 객체의 경계를 가져옵니다. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | 이 모양의 점 순서를 반전시킵니다. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | 지정된 변환을 모양에 적용합니다. |

### 또 보기

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


