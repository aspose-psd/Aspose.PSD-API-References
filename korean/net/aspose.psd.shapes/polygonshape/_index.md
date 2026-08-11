---
title: "클래스 PolygonShape"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Shapes.PolygonShape 클래스. 다각형 모양을 나타냅니다."
type: docs
weight: 6010
url: /ko/net/aspose.psd.shapes/polygonshape/
---
{{< psd/tize >}}
## PolygonShape class

다각형 형태를 나타냅니다.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | `PolygonShape` 클래스의 새 인스턴스를 초기화합니다. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | `PolygonShape` 클래스의 새 인스턴스를 초기화합니다. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | `PolygonShape` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | 객체의 경계를 가져옵니다. |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | 형태의 중심을 가져옵니다. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | 끝 모양 점을 가져옵니다. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | 형태에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | 모양이 닫혀 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | 곡선 점을 가져오거나 설정합니다. |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | 모양 세그먼트를 가져옵니다. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | 시작 모양 점을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | 객체의 경계를 가져옵니다. |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | 객체의 경계를 가져옵니다. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | 이 모양의 점 순서를 반전시킵니다. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | 지정된 변환을 모양에 적용합니다. |

## 예제

이 예제는 새 Image를 생성하고 Image 표면에 Figures와 GraphicsPath를 사용하여 다양한 모양을 그립니다.

```csharp
[C#]

//Image의 인스턴스를 생성합니다.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics 클래스의 인스턴스를 생성하고 초기화합니다.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics 표면을 지웁니다.
    graphics.Clear(Color.Wheat);

    //GraphicsPath 클래스의 인스턴스를 생성합니다.
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Figure 클래스의 인스턴스를 생성합니다.
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Figure 객체에 Shape를 추가합니다.
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Figure 클래스의 인스턴스를 생성합니다.
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Figure 객체에 Shape를 추가합니다.
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Figure 객체를 GraphicsPath에 추가합니다.
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //검은색 Pen 객체로 경로를 그립니다.
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // 내보내기 옵션을 생성하고 초기화합니다.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // 모든 변경 사항을 저장합니다.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### 또 보기

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


