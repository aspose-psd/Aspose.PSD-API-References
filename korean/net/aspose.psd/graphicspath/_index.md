---
title: "클래스 GraphicsPath"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.GraphicsPath 클래스. 연결된 선과 곡선의 시리즈를 나타냅니다. 이 클래스는 상속될 수 없습니다"
type: docs
weight: 4790
url: /ko/net/aspose.psd/graphicspath/
---
{{< psd/tize >}}
## GraphicsPath class

연결된 선과 곡선의 시리즈를 나타냅니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | `GraphicsPath` 클래스의 새 인스턴스를 초기화합니다. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | `GraphicsPath` 클래스의 새 인스턴스를 초기화합니다. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | `GraphicsPath` 클래스의 새 인스턴스를 초기화합니다. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | `GraphicsPath` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | 객체의 경계를 가져오거나 설정합니다. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | 경로 도형을 가져옵니다. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | 이 `GraphicsPath`의 도형 내부가 어떻게 채워지는지를 결정하는 [`FillMode`](../fillmode/) 열거형을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | 새 도형을 추가합니다. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | 새 도형들을 추가합니다. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | 지정된 `GraphicsPath`를 이 경로에 추가합니다. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | 지정된 `GraphicsPath`를 이 경로에 추가합니다. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | 이 그래픽 경로를 깊게 복제합니다. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | 이 경로의 각 곡선을 연결된 선분 시퀀스로 변환합니다. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | 지정된 변환을 적용한 다음 이 `GraphicsPath`의 각 곡선을 연결된 선분 시퀀스로 변환합니다. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | 이 `GraphicsPath`의 각 곡선을 연결된 선분 시퀀스로 변환합니다. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | 객체의 경계를 가져옵니다. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | 객체의 경계를 가져옵니다. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | 지정된 [`Pen`](../pen/)으로 그릴 때 이 `GraphicsPath`의 외곽선(아래)에 지정된 점이 포함되는지 여부를 나타냅니다. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | 지정된 [`Pen`](../pen/)으로 그릴 때 이 `GraphicsPath`의 외곽선(아래)에 지정된 점이 포함되는지 여부를 나타냅니다. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | 지정된 [`Pen`](../pen/)으로 그릴 때 이 `GraphicsPath`의 외곽선(아래)에 지정된 점이 포함되는지 여부를 나타냅니다. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | 지정된 [`Pen`](../pen/)으로 그릴 때 이 `GraphicsPath`의 외곽선(아래)에 지정된 점이 포함되는지 여부를 나타냅니다. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | 지정된 [`Pen`](../pen/)과 지정된 [`Graphics`](../graphics/)를 사용하여 그릴 때 이 `GraphicsPath`의 외곽선(아래)에 지정된 점이 포함되는지 여부를 나타냅니다. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | 지정된 [`Pen`](../pen/)과 지정된 [`Graphics`](../graphics/)를 사용하여 그릴 때 이 `GraphicsPath`의 외곽선(아래)에 지정된 점이 포함되는지 여부를 나타냅니다. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | 지정된 [`Pen`](../pen/)과 지정된 [`Graphics`](../graphics/)를 사용하여 그릴 때 이 `GraphicsPath`의 외곽선(아래)에 지정된 점이 포함되는지 여부를 나타냅니다. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | 지정된 [`Pen`](../pen/)과 지정된 [`Graphics`](../graphics/)를 사용하여 그릴 때 이 `GraphicsPath`의 외곽선(아래)에 지정된 점이 포함되는지 여부를 나타냅니다. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | 지정된 점이 이 `GraphicsPath` 내부에 포함되는지 여부를 나타냅니다. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | 지정된 점이 이 `GraphicsPath` 내부에 포함되는지 여부를 나타냅니다. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | 지정된 점이 이 `GraphicsPath` 내부에 포함되는지 여부를 나타냅니다. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | 지정된 점이 이 `GraphicsPath` 내부에 포함되는지 여부를 나타냅니다. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | 지정된 점이 이 `GraphicsPath` 내부에 포함되는지 여부를 나타냅니다. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | 지정된 점이 이 `GraphicsPath` 내부에 포함되는지 여부를 나타냅니다. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | 지정된 [`Graphics`](../graphics/)의 보이는 클립 영역 내에서 이 `GraphicsPath`에 지정된 점이 포함되는지 여부를 나타냅니다. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | 지정된 [`Graphics`](../graphics/)를 사용하여 이 `GraphicsPath`에 지정된 점이 포함되는지 여부를 나타냅니다. |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | 도형을 제거합니다. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | 도형들을 제거합니다. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | 그래픽 경로를 비우고 [`FillMode`](../fillmode/)을 Alternate로 설정합니다. |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | 이 `GraphicsPath`의 각 도형에서 도형, 형태 및 점의 순서를 반대로 합니다. |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | 지정된 변환을 모양에 적용합니다. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | 사각형과 평행사변형으로 정의된 워프 변환을 이 `GraphicsPath`에 적용합니다. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | 사각형과 평행사변형으로 정의된 워프 변환을 이 `GraphicsPath`에 적용합니다. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | 사각형과 평행사변형으로 정의된 워프 변환을 이 `GraphicsPath`에 적용합니다. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | 사각형과 평행사변형으로 정의된 워프 변환을 이 `GraphicsPath`에 적용합니다. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | 경로에 추가 외곽선을 추가합니다. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | `GraphicsPath`에 추가 외곽선을 추가합니다. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | 이 경로를 지정된 펜으로 그릴 때 채워지는 영역을 둘러싸는 곡선으로 이 `GraphicsPath`를 교체합니다. |

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


