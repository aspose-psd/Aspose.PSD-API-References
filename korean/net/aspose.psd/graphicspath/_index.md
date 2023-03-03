---
title: Class GraphicsPath
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.GraphicsPath 수업. 일련의 연결된 선과 곡선을 나타냅니다. 이 클래스는 상속될 수 없습니다.
type: docs
weight: 4320
url: /ko/net/aspose.psd/graphicspath/
---
## GraphicsPath class

일련의 연결된 선과 곡선을 나타냅니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | 의 새 인스턴스를 초기화합니다.`GraphicsPath` 클래스. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | 의 새 인스턴스를 초기화합니다.`GraphicsPath` 클래스. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | 의 새 인스턴스를 초기화합니다.`GraphicsPath` 클래스. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | 의 새 인스턴스를 초기화합니다.`GraphicsPath` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | 개체의 범위를 가져오거나 설정합니다. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | 경로 수치를 가져옵니다. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | 가져오거나 설정합니다.[`FillMode`](../fillmode/) 이에서 모양의 내부가 어떻게 결정되는지를 결정하는 열거`GraphicsPath` 채워집니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | 새 그림을 추가합니다. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | 새 수치를 추가합니다. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | 지정된`GraphicsPath` 이 경로로. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | 지정된`GraphicsPath` 이 경로로. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | 이 그래픽 경로의 전체 복제를 수행합니다. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | 이 경로의 각 곡선을 일련의 연결된 선 세그먼트로 변환합니다. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | 지정된 변환을 적용한 다음 이 안에 있는 각 곡선을 변환합니다.`GraphicsPath` 연결된 라인 세그먼트의 시퀀스로. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | 이 안에 있는 각 곡선을 변환합니다.`GraphicsPath` 연결된 라인 세그먼트의 시퀀스로. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | 개체의 범위를 가져옵니다. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | 개체의 범위를 가져옵니다. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | 지정된 점이 이 윤곽선 안에(아래) 포함되는지 여부를 나타냅니다.`GraphicsPath` 지정된 것으로 그릴 때[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | 지정된 점이 이 윤곽선 안에(아래) 포함되는지 여부를 나타냅니다.`GraphicsPath` 지정된 것으로 그릴 때[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | 지정된 점이 이 윤곽선 안에(아래) 포함되는지 여부를 나타냅니다.`GraphicsPath` 지정된 것으로 그릴 때[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | 지정된 점이 이 윤곽선 안에(아래) 포함되는지 여부를 나타냅니다.`GraphicsPath` 지정된 것으로 그릴 때[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | 지정된 점이 이 윤곽선 안에(아래) 포함되는지 여부를 나타냅니다.`GraphicsPath` 지정된 것으로 그릴 때[`Pen`](../pen/) 그리고 지정된[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | 지정된 점이 이 윤곽선 안에(아래) 포함되는지 여부를 나타냅니다.`GraphicsPath` 지정된 것으로 그릴 때[`Pen`](../pen/) 그리고 지정된[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | 지정된 점이 이 윤곽선 안에(아래) 포함되는지 여부를 나타냅니다.`GraphicsPath` 지정된 것으로 그릴 때[`Pen`](../pen/) 그리고 지정된[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | 지정된 점이 이 윤곽선 안에(아래) 포함되는지 여부를 나타냅니다.`GraphicsPath` 지정된 것으로 그릴 때[`Pen`](../pen/) 그리고 지정된[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | 지정된 점이 이 안에 포함되는지 여부를 나타냅니다.`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | 지정된 점이 이 안에 포함되는지 여부를 나타냅니다.`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | 지정된 점이 이 안에 포함되는지 여부를 나타냅니다.`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | 지정된 점이 이 안에 포함되는지 여부를 나타냅니다.`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | 지정된 점이 이 안에 포함되는지 여부를 나타냅니다.`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | 지정된 점이 이 안에 포함되는지 여부를 나타냅니다.`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | 지정된 점이 이 안에 포함되는지 여부를 나타냅니다.`GraphicsPath` 지정된 클립의 보이는 클립 영역에서[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | 지정된 점이 이 안에 포함되는지 여부를 나타냅니다.`GraphicsPath` , 지정된 사용[`Graphics`](../graphics/) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | 그림을 제거합니다. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | 그림을 제거합니다. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | 그래픽 경로를 비우고[`FillMode`](../fillmode/) 에게Alternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | 이 도형의 각 도형에서 도형, 도형 및 점의 순서를 반대로 바꿉니다.`GraphicsPath` . |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | 지정된 변환을 모양에 적용합니다. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | 사각형과 평행사변형으로 정의된 워프 변환을 여기에 적용합니다.`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | 사각형과 평행사변형으로 정의된 워프 변환을 여기에 적용합니다.`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | 사각형과 평행사변형으로 정의된 워프 변환을 여기에 적용합니다.`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | 사각형과 평행사변형으로 정의된 워프 변환을 여기에 적용합니다.`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | 경로에 윤곽선을 추가합니다. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | 에 윤곽을 추가합니다.`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | 이것을 대체합니다.`GraphicsPath` 지정된 펜으로 이 경로를 그릴 때 채워지는 영역을 둘러싸는 곡선으로. |

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


