---
title: Class Pen
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Pen 수업. 선 곡선 및 도형을 그리는 데 사용되는 개체를 정의합니다.
type: docs
weight: 5200
url: /ko/net/aspose.psd/pen/
---
## Pen class

선, 곡선 및 도형을 그리는 데 사용되는 개체를 정의합니다.

```csharp
public class Pen : TransparencySupporter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | 의 새 인스턴스를 초기화합니다.`Pen` 지정된 클래스[`Brush`](./brush/) . |
| [Pen](pen/#constructor_2)(Color) | 의 새 인스턴스를 초기화합니다.`Pen` 지정된 색상의 클래스. |
| [Pen](pen/#constructor_1)(Brush, float) | 의 새 인스턴스를 초기화합니다.`Pen` 지정된 클래스[`Brush`](./brush/) 그리고[`Width`](./width/) . |
| [Pen](pen/#constructor_3)(Color, float) | 의 새 인스턴스를 초기화합니다.`Pen` 지정된 클래스[`Color`](./color/) 그리고[`Width`](./width/) 속성. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | 이에 대한 정렬을 가져오거나 설정합니다.`Pen` . |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | 가져오거나 설정합니다.[`Brush`](./brush/) 이것의 속성을 결정하는`Pen` . |
| [Color](../../aspose.psd/pen/color/) { get; set; } | 이 색상을 가져오거나 설정합니다.`Pen` . |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | 복합 펜을 지정하는 값의 배열을 가져오거나 설정합니다. 복합펜은 평행선과 공백으로 구성된 복합선을 그립니다. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | 이 항목으로 그린 줄의 끝에서 사용할 사용자 지정 캡을 가져오거나 설정합니다.`Pen` . |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | 이 항목으로 그린 선의 시작 부분에 사용할 사용자 지정 캡을 가져오거나 설정합니다.`Pen` . |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | 이 항목으로 그린 파선을 구성하는 대시의 끝에 사용되는 캡 스타일을 가져오거나 설정합니다.`Pen` . |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | 선의 시작부터 대시 패턴의 시작까지의 거리를 가져오거나 설정합니다. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | 사용자 지정 대시 및 공백의 배열을 가져오거나 설정합니다. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | 이 항목으로 그린 점선에 사용되는 스타일을 가져오거나 설정합니다.`Pen` . |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | 이 항목으로 그린 선의 끝에 사용되는 캡 스타일을 가져오거나 설정합니다.`Pen` . |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | 이 항목으로 그린 두 연속 선의 끝에 대한 조인 스타일을 가져오거나 설정합니다.`Pen` . |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | 연귀 모서리의 결합 두께 제한을 가져오거나 설정합니다. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | 개체의 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 값 0은 개체가 완전히 표시됨을 의미하고 값 1은 개체가 완전히 불투명함을 의미합니다. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | 이것으로 그린 선의 스타일을 가져옵니다.`Pen` . |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | 이 항목으로 그린 선의 시작 부분에 사용된 캡 스타일을 가져오거나 설정합니다.`Pen` . |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | 이에 대한 기하 변환의 복사본을 가져오거나 설정합니다.`Pen` . |
| [Width](../../aspose.psd/pen/width/) { get; set; } | 이 너비를 가져오거나 설정합니다.`Pen` , drawing. 에 사용되는 Graphics 객체 단위 |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | 이에 대한 변환 행렬을 곱합니다.`Pen` 지정된[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | 이에 대한 변환 행렬을 곱합니다.`Pen` 지정된[`Matrix`](../matrix/) 지정된 order. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | 이에 대한 기하 변환 행렬을 재설정합니다.`Pen` 정체성에. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | 지정된 각도만큼 로컬 기하 변환을 회전합니다. 이 방법은 변환 앞에 회전을 추가합니다. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | 지정된 순서로 지정된 각도만큼 로컬 기하 변환을 회전합니다. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | 지정된 계수로 로컬 기하 변환을 조정합니다. 이 방법은 스케일링 행렬을 변환 앞에 추가합니다. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | 지정된 순서로 지정된 요소로 로컬 기하 변환의 크기를 조정합니다. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | 이것에 의해 그려진 선을 끝내는 데 사용되는 캡 스타일을 결정하는 값을 설정합니다.`Pen` . |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | 지정된 치수로 로컬 기하 변환을 변환합니다. 이 방법은 변환을 변환 앞에 추가합니다. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | 지정된 순서로 지정된 치수로 로컬 기하 변환을 변환합니다. |

### 예

이 예제는 Pen 객체 생성 및 사용을 보여줍니다. 이 예제에서는 새 이미지를 만들고 이미지 표면에 사각형을 그립니다.

```csharp
[C#]

//이미지 인스턴스 생성
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics의 인스턴스를 생성하고 Image 객체로 초기화합니다.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //하얀 색으로 그래픽 표면을 지웁니다.
    graphics.Clear(Aspose.PSD.Color.White);

    // 빨간색과 너비가 5인 Pen 인스턴스 생성
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //HatchBrush의 인스턴스를 만들고 속성을 설정합니다.
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Pen 인스턴스 생성
    //HatchBrush 객체와 너비로 초기화
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Pen 객체를 지정하여 사각형 그리기
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Pen 객체를 지정하여 사각형 그리기
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // 내보내기 옵션을 만들고 초기화합니다.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // 모든 변경 사항을 저장합니다.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### 또한보십시오

* class [TransparencySupporter](../transparencysupporter/)
* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


