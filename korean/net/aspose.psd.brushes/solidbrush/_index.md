---
title: Class SolidBrush
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Brushes.SolidBrush 수업. 단색 브러시는 특정 색상으로 연속적으로 그리기 위한 것입니다. 이 클래스는 상속될 수 없습니다.
type: docs
weight: 200
url: /ko/net/aspose.psd.brushes/solidbrush/
---
## SolidBrush class

단색 브러시는 특정 색상으로 연속적으로 그리기 위한 것입니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class SolidBrush : Brush
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | 의 새 인스턴스를 초기화합니다.`SolidBrush` 클래스. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | 의 새 인스턴스를 초기화합니다.`SolidBrush` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | 브러시 색상을 가져오거나 설정합니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 값이 0이면 브러시가 완전히 표시되고 값이 1이면 브러시가 완전히 불투명합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 현재의 새로운 딥 클론을 생성합니다.[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |

### 예

이 예제에서는 Graphics 클래스를 사용하여 이미지 표면에 기본 모양을 만듭니다. 작업을 시연하기 위해 예제에서는 PSD 형식의 새 이미지를 만들고 Graphics 클래스에 의해 노출된 Draw 메서드를 사용하여 이미지 표면에 기본 모양을 그린 다음 PSD 파일 형식으로 내보냅니다.

```csharp
[C#]

//이미지 인스턴스 생성 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics 클래스의 인스턴스 생성 및 초기화
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //그래픽 표면 지우기
    graphics.Clear(Color.Wheat);

    //검은 색의 Pen 객체를 지정하여 호를 그린다. 
    //호를 둘러싼 사각형, 시작 각도 및 스윕 각도
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Blue 색상과 좌표 Point를 갖는 Pen 객체를 지정하여 Bezier를 그립니다.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Green 색상의 Pen 객체와 Points의 배열을 지정하여 Curve를 그립니다.
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen 객체와 주변 Rectangle을 사용하여 Ellipse를 그립니다.
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //선을 그리다 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //파이 세그먼트 그리기
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //빨간색의 Pen 객체와 Points의 배열을 지정하여 Polygon을 그립니다.
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //직사각형 그리기
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //SolidBrush 개체를 만들고 다양한 속성을 설정합니다.
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush 객체와 Font를 사용하여 특정 Point에 String을 그립니다.
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions의 인스턴스를 만들고 다양한 속성을 설정합니다.
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // 모든 변경 사항을 저장합니다.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 또한보십시오

* class [Brush](../../aspose.psd/brush/)
* 네임스페이스 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 집회 [Aspose.PSD](../../)


