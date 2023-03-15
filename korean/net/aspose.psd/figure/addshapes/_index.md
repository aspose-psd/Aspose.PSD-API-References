---
title: Figure.AddShapes
second_title: .NET API 참조용 Aspose.PSD
description: Figure 방법. 도형에 다양한 도형을 추가합니다.
type: docs
weight: 70
url: /ko/net/aspose.psd/figure/addshapes/
---
## Figure.AddShapes method

도형에 다양한 도형을 추가합니다.

```csharp
public void AddShapes(Shape[] shapes)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| shapes | Shape[] | 추가할 셰이프입니다. |

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

* class [Shape](../../shape/)
* class [Figure](../)
* 네임스페이스 [Aspose.PSD](../../figure/)
* 집회 [Aspose.PSD](../../../)


