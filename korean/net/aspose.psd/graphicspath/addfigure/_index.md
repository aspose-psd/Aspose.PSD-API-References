---
title: "GraphicsPath.AddFigure"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "GraphicsPath 메서드. 새 도형을 추가합니다."
type: docs
weight: 50
url: /ko/net/aspose.psd/graphicspath/addfigure/
---
{{< psd/tize >}}
## GraphicsPath.AddFigure method

새 도형을 추가합니다.

```csharp
public void AddFigure(Figure figure)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 도형 | 도형 | 추가할 도형입니다. |

## 예제

이 예제는 GraphicsPath와 Graphics 클래스를 사용하여 이미지 표면에 도형(Figures)을 생성하고 조작합니다. 예제에서는 새 이미지를 생성하고 GraphicsPath 클래스를 이용해 경로를 그립니다. 마지막에 Graphics 클래스에서 제공하는 DrawPath 메서드를 호출하여 표면에 경로를 렌더링합니다. 최종적으로 이미지는 Tiff 파일 형식으로 내보내집니다.

```csharp
[C#]

//Image 인스턴스를 생성합니다.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics 클래스의 인스턴스를 생성하고 초기화합니다.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics 표면을 지웁니다.
    graphics.Clear(Color.Wheat);

    //GraphicsPath 클래스의 인스턴스를 생성합니다.
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Figure 클래스의 인스턴스를 생성합니다.
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Figure 객체에 도형을 추가합니다.
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Figure 객체를 GraphicsPath에 추가합니다.
    graphicspath.AddFigure(figure);

    //검은색 Pen 객체로 경로를 그립니다.
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //TiffOptions 인스턴스를 생성하고 다양한 속성을 설정합니다.
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // 모든 변경 사항을 저장합니다.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 또 보기

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


