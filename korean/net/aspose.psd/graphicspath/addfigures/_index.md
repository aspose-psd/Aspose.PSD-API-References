---
title: "GraphicsPath.AddFigures"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "GraphicsPath 메서드. 새 도형들을 추가합니다."
type: docs
weight: 60
url: /ko/net/aspose.psd/graphicspath/addfigures/
---
{{< psd/tize >}}
## GraphicsPath.AddFigures method

새 도형들을 추가합니다.

```csharp
public void AddFigures(Figure[] figures)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 도형 | Figure[] | 추가할 도형들입니다. |

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

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


