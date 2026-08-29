---
title: "RectangleProjectedShape 클래스"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Shapes.RectangleProjectedShape 클래스. 특정 방향으로 회전된 사각형 위에 투영되는 형태를 나타냅니다. 네 개의 점으로 지정되며, 공간에서 회전시켜도 동일한 변 길이와 인접 변 사이 90도를 유지합니다."
type: docs
weight: 6020
url: /ko/net/aspose.psd.shapes/rectangleprojectedshape/
---
{{< psd/tize >}}
## RectangleProjectedShape class

특정 방향으로 회전된 사각형 위에 투사된 형태를 나타냅니다. 동일한 변 길이를 유지하고 인접 변 사이가 90도인 네 점으로 지정되어, 공간에서 회전될 수 있습니다.

```csharp
public abstract class RectangleProjectedShape : Shape
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RectangleProjectedShape](rectangleprojectedshape/#constructor)() | `RectangleProjectedShape` 클래스의 새 인스턴스를 초기화합니다. |
| [RectangleProjectedShape](rectangleprojectedshape/#constructor_1)(RectangleF) | `RectangleProjectedShape` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | 객체의 경계를 가져옵니다. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | 형태의 중심을 가져옵니다. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | 형태에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | 왼쪽 하단 사각형 점을 가져옵니다. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | 왼쪽 상단 사각형 점을 가져옵니다. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | 사각형 높이를 가져옵니다. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | 사각형 너비를 가져옵니다. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | 오른쪽 아래 사각형 점을 가져옵니다. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | 오른쪽 위 사각형 점을 가져옵니다. |
| abstract [Segments](../../aspose.psd/shape/segments/) { get; } | 모양 세그먼트를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/#getbounds)(Matrix) | 객체의 경계를 가져옵니다. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/#getbounds_1)(Matrix, Pen) | 객체의 경계를 가져옵니다. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | 지정된 변환을 모양에 적용합니다. |

### 또 보기

* class [Shape](../../aspose.psd/shape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


