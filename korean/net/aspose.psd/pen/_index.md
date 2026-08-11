---
title: "클래스 Pen"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Pen 클래스. 선, 곡선 및 도형을 그리는 데 사용되는 객체를 정의합니다."
type: docs
weight: 5690
url: /ko/net/aspose.psd/pen/
---
{{< psd/tize >}}
## Pen class

선, 곡선 및 도형을 그리는 데 사용되는 객체를 정의합니다.

```csharp
public class Pen : TransparencySupporter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | `Pen` 클래스의 새 인스턴스를 지정된 [`Brush`](./brush/)로 초기화합니다. |
| [Pen](pen/#constructor_2)(Color) | 지정된 색상으로 `Pen` 클래스의 새 인스턴스를 초기화합니다. |
| [Pen](pen/#constructor_1)(Brush, float) | 지정된 [`Brush`](./brush/)와 [`Width`](./width/)를 사용하여 `Pen` 클래스의 새 인스턴스를 초기화합니다. |
| [Pen](pen/#constructor_3)(Color, float) | 지정된 [`Color`](./color/) 및 [`Width`](./width/) 속성을 사용하여 `Pen` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | 이 `Pen`의 정렬을 가져오거나 설정합니다. |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | 이 `Pen`의 속성을 결정하는 [`Brush`](./brush/)를 가져오거나 설정합니다. |
| [Color](../../aspose.psd/pen/color/) { get; set; } | 이 `Pen`의 색상을 가져오거나 설정합니다. |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | 복합 펜을 지정하는 값 배열을 가져오거나 설정합니다. 복합 펜은 평행선과 간격으로 구성된 복합 라인을 그립니다. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | 이 `Pen`으로 그린 선의 끝에 사용할 사용자 정의 캡을 가져오거나 설정합니다. |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | 이 `Pen`으로 그린 선의 시작에 사용할 사용자 정의 캡을 가져오거나 설정합니다. |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | 이 `Pen`으로 그린 점선의 대시 끝에 사용되는 캡 스타일을 가져오거나 설정합니다. |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | 선 시작점부터 대시 패턴 시작점까지의 거리를 가져오거나 설정합니다. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | 사용자 정의 대시와 간격의 배열을 가져오거나 설정합니다. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | 이 `Pen`으로 그린 점선에 사용되는 스타일을 가져오거나 설정합니다. |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | 이 `Pen`으로 그린 선의 끝에 사용되는 캡 스타일을 가져오거나 설정합니다. |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | 이 `Pen`으로 그린 두 연속 선의 끝에 대한 조인 스타일을 가져오거나 설정합니다. |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | 각진 모서리에서 조인의 두께 제한을 가져오거나 설정합니다. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | 객체의 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 0 값은 객체가 완전히 투명함을 의미하고, 1 값은 객체가 완전히 불투명함을 의미합니다. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | 이 `Pen`으로 그린 선의 스타일을 가져옵니다. |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | 이 `Pen`으로 그린 선의 시작 부분에 사용되는 캡 스타일을 가져오거나 설정합니다. |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | 이 `Pen`에 대한 기하학적 변환의 복사본을 가져오거나 설정합니다. |
| [Width](../../aspose.psd/pen/width/) { get; set; } | 그리기에 사용되는 Graphics 객체의 단위로 이 `Pen`의 너비를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | 이 `Pen`의 변환 행렬에 지정된 [`Matrix`](../matrix/)를 곱합니다. |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | 이 `Pen`의 변환 행렬에 지정된 순서대로 지정된 [`Matrix`](../matrix/)를 곱합니다. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | 이 `Pen`의 기하학적 변환 행렬을 단위 행렬로 재설정합니다. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | 지정된 각도만큼 로컬 기하학적 변환을 회전합니다. 이 메서드는 회전을 변환 앞에 추가합니다. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | 지정된 순서대로 지정된 각도만큼 로컬 기하학적 변환을 회전합니다. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | 지정된 계수만큼 로컬 기하학적 변환을 스케일링합니다. 이 메서드는 스케일링 행렬을 변환 앞에 추가합니다. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | 지정된 순서대로 지정된 계수만큼 로컬 기하학적 변환을 스케일링합니다. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | 이 `Pen`으로 그린 선을 끝낼 때 사용되는 캡 스타일을 결정하는 값을 설정합니다. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | 지정된 치수만큼 로컬 기하학적 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | 지정된 순서대로 지정된 치수만큼 로컬 기하학적 변환을 평행 이동합니다. |

## 예제

이 예제는 Pen 객체의 생성 및 사용을 보여줍니다. 예제에서는 새 Image를 생성하고 Image 표면에 사각형을 그립니다.

```csharp
[C#]

//Image의 인스턴스를 생성합니다.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics 인스턴스를 생성하고 Image 객체로 초기화합니다.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics 표면을 흰색으로 지웁니다.
    graphics.Clear(Aspose.PSD.Color.White);

    //색상 Red와 너비 5인 Pen 인스턴스를 생성합니다.
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //HatchBrush 인스턴스를 생성하고 해당 속성을 설정합니다.
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Pen 인스턴스를 생성합니다.
    //HatchBrush 객체와 너비를 사용하여 초기화합니다.
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Pen 객체를 지정하여 사각형을 그립니다.
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Pen 객체를 지정하여 사각형을 그립니다.
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // 내보내기 옵션을 생성하고 초기화합니다.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // 모든 변경 사항을 저장합니다.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### 또 보기

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


