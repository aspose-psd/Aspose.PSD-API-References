---
title: "클래스 CurveShape"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Shapes.CurveShape 클래스. 곡선 스플라인 모양을 나타냅니다."
type: docs
weight: 5980
url: /ko/net/aspose.psd.shapes/curveshape/
---
{{< psd/tize >}}
## CurveShape class

곡선 스플라인 형태를 나타냅니다.

```csharp
public sealed class CurveShape : PolygonShape
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | `CurveShape` 클래스의 새 인스턴스를 초기화합니다. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | `CurveShape` 클래스의 새 인스턴스를 초기화합니다. 기본 장력 0.5가 사용됩니다. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | `CurveShape` 클래스의 새 인스턴스를 초기화합니다. 기본 장력 0.5가 사용됩니다. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | `CurveShape` 클래스의 새 인스턴스를 초기화합니다. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | `CurveShape` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | 객체의 경계를 가져옵니다. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | 형태의 중심을 가져옵니다. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | 끝 모양 점을 가져옵니다. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | 형태에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | 모양이 닫혀 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | 곡선 점을 가져오거나 설정합니다. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | 모양 세그먼트를 가져옵니다. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | 시작 모양 점을 가져옵니다. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | 곡선 장력을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | 객체의 경계를 가져옵니다. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | 객체의 경계를 가져옵니다. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | 이 모양의 점 순서를 반전시킵니다. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | 지정된 변환을 모양에 적용합니다. |

### 또 보기

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


