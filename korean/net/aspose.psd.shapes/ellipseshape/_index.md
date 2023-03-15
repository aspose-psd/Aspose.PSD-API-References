---
title: Class EllipseShape
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Shapes.EllipseShape 수업. 타원 모양을 나타냅니다.
type: docs
weight: 5490
url: /ko/net/aspose.psd.shapes/ellipseshape/
---
## EllipseShape class

타원 모양을 나타냅니다.

```csharp
public class EllipseShape : RectangleShape
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [EllipseShape](ellipseshape/#constructor)() | 의 새 인스턴스를 초기화합니다.`EllipseShape` 클래스. |
| [EllipseShape](ellipseshape/#constructor_1)(RectangleF) | 의 새 인스턴스를 초기화합니다.`EllipseShape` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | 개체의 범위를 가져옵니다. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | 모양의 중심을 가져옵니다. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | 모양에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | 왼쪽 하단 사각형 점을 가져옵니다. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | 왼쪽 상단 사각형 점을 가져옵니다. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | 직사각형 높이를 가져옵니다. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | 사각형 너비를 가져옵니다. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | 오른쪽 아래 직사각형 점을 가져옵니다. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | 오른쪽 상단 사각형 점을 가져옵니다. |
| override [Segments](../../aspose.psd.shapes/ellipseshape/segments/) { get; } | 모양 세그먼트를 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | 개체의 범위를 가져옵니다. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | 개체의 범위를 가져옵니다. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | 지정된 변환을 모양에 적용합니다. |

### 예

이 예제는 이미지 표면에서 Figures 및 GraphicsPath를 사용하여 새 이미지를 만들고 다양한 모양을 그립니다.

```csharp
[C#]

//이미지 인스턴스 생성
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics 클래스의 인스턴스 생성 및 초기화
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //그래픽 표면 지우기
    graphics.Clear(Color.Wheat);

    // GraphicsPath 클래스의 인스턴스 생성
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Figure 클래스의 인스턴스 생성
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //도형 객체에 도형 추가
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Figure 클래스의 인스턴스 생성
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //도형 객체에 도형 추가
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    // GraphicsPath에 Figure 객체 추가
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //검은색의 Pen 객체로 경로를 그립니다.
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // 내보내기 옵션을 만들고 초기화합니다.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // 모든 변경 사항을 저장합니다.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### 또한보십시오

* class [RectangleShape](../rectangleshape/)
* 네임스페이스 [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* 집회 [Aspose.PSD](../../)


