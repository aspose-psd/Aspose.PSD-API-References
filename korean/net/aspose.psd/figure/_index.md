---
title: "클래스 Figure"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Figure 클래스. 도형. 도형을 위한 컨테이너"
type: docs
weight: 1210
url: /ko/net/aspose.psd/figure/
---
{{< psd/tize >}}
## Figure class

도형. 도형을 위한 컨테이너.

```csharp
public class Figure : ObjectWithBounds
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Figure](figure/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | 객체의 경계를 가져오거나 설정합니다. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | 이 도형이 닫혀 있는지 여부를 나타내는 값을 가져오거나 설정합니다. 닫힌 도형은 첫 번째와 마지막 도형의 모양이 연속적인 경우에만 차이가 있습니다. 이러한 경우 첫 번째 모양의 첫 번째 점이 마지막 모양의 마지막 점에서 직선으로 연결됩니다. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | 전체 도형 세그먼트를 가져옵니다. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | 도형의 모양들을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | 도형에 모양을 추가합니다. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | 도형에 여러 모양을 추가합니다. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | 객체의 경계를 가져옵니다. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | 객체의 경계를 가져옵니다. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | 도형에서 모양을 제거합니다. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | 도형에서 여러 모양을 제거합니다. |
| [Reverse](../../aspose.psd/figure/reverse/)() | 이 도형의 모양 순서와 점 순서를 반전시킵니다. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | 지정된 변환을 모양에 적용합니다. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


