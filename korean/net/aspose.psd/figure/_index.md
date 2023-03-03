---
title: Class Figure
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Figure 수업. 그림. 모양을 담는 용기.
type: docs
weight: 1200
url: /ko/net/aspose.psd/figure/
---
## Figure class

그림. 모양을 담는 용기.

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
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | 개체의 범위를 가져오거나 설정합니다. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | 이 그림이 닫혀 있는지 여부를 나타내는 값을 가져오거나 설정합니다. 닫힌 도형은 where 첫 번째 도형과 마지막 도형이 연속 도형인 경우에만 차이가 있습니다. 이 경우 첫 번째 도형의 첫 번째 점은 마지막 도형의 마지막 점에서 직선으로 연결됩니다. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | 전체 그림 세그먼트를 가져옵니다. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | 그림 모양을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | 그림에 모양을 추가합니다. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | 도형에 다양한 도형을 추가합니다. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | 개체의 범위를 가져옵니다. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | 개체의 범위를 가져옵니다. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | 그림에서 모양을 제거합니다. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | 그림에서 모양의 범위를 제거합니다. |
| [Reverse](../../aspose.psd/figure/reverse/)() | 이 그림 모양 순서를 반대로 하고 점 순서를 모양 지정합니다. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | 지정된 변환을 모양에 적용합니다. |

### 예

이 예제에서는 GraphicsPath 및 Graphics 클래스를 사용하여 이미지 표면에서 그림을 만들고 조작합니다. 예제에서는 새 이미지를 만들고 GraphicsPath 클래스의 도움으로 경로를 그립니다. 마지막에 Graphics 클래스에 의해 노출된 DrawPath 메서드가 호출되어 표면에 경로를 렌더링합니다. 마지막으로 이미지를 Tiff 파일 형식으로 내보냅니다.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //도형 객체에 도형 추가
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    // GraphicsPath에 Figure 객체 추가
    graphicspath.AddFigure(figure);

    //검은색의 Pen 객체로 경로를 그립니다.
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //TiffOptions의 인스턴스를 만들고 다양한 속성을 설정합니다.
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // 모든 변경 사항을 저장합니다.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 또한보십시오

* class [ObjectWithBounds](../objectwithbounds/)
* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


