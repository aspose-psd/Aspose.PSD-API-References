---
title: "클래스 SolidBrush"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Brushes.SolidBrush 클래스. Solid brush는 특정 색상으로 지속적으로 그리기 위해 설계되었습니다. 이 클래스는 상속할 수 없습니다."
type: docs
weight: 200
url: /ko/net/aspose.psd.brushes/solidbrush/
---
{{< psd/tize >}}
## SolidBrush class

솔리드 브러시는 특정 색상으로 지속적으로 그리기 위해 설계되었습니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class SolidBrush : Brush
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | `SolidBrush` 클래스의 새 인스턴스를 초기화합니다. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | `SolidBrush` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | 브러시 색상을 가져오거나 설정합니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 현재 [`Brush`](../../aspose.psd/brush/)의 새로운 깊은 복제본을 생성합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |

## 예제

이 예제는 Graphics 클래스를 사용하여 이미지 표면에 기본 도형을 생성합니다. 동작을 보여주기 위해, 예제는 PSD 형식의 새 이미지를 만들고 Graphics 클래스가 제공하는 Draw 메서드를 사용하여 이미지 표면에 기본 도형을 그린 다음 PSD 파일 형식으로 내보냅니다.

```csharp
[C#]

//Image 인스턴스를 생성합니다.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics 클래스의 인스턴스를 생성하고 초기화합니다.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics 표면을 지웁니다.
    graphics.Clear(Color.Wheat);

    //검은 색을 가진 Pen 객체를 지정하여 호를 그립니다, 
    //호를 둘러싼 사각형, 시작 각도 및 스윕 각도
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //파란 색을 가진 Pen 객체와 좌표 포인트를 지정하여 베지어 곡선을 그립니다.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //녹색을 가진 Pen 객체와 포인트 배열을 지정하여 곡선을 그립니다
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen 객체와 둘러싼 사각형을 사용하여 타원을 그립니다
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //선을 그립니다 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //파이 조각을 그립니다
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //빨간 색을 가진 Pen 객체와 포인트 배열을 지정하여 다각형을 그립니다
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //사각형을 그립니다
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //SolidBrush 객체를 생성하고 다양한 속성을 설정합니다
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush 객체와 폰트를 사용하여 특정 지점에 문자열을 그립니다
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions의 인스턴스를 생성하고 다양한 속성을 설정합니다
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // 모든 변경 사항을 저장합니다.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 또 보기

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


