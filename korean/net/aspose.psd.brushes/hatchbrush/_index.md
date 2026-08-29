---
title: "클래스 HatchBrush"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Brushes.HatchBrush 클래스. 해치 스타일, 전경 색 및 배경 색을 가진 사각형 브러시를 정의합니다. 이 클래스는 상속할 수 없습니다."
type: docs
weight: 130
url: /ko/net/aspose.psd.brushes/hatchbrush/
---
{{< psd/tize >}}
## HatchBrush class

해치 스타일, 전경 색 및 배경 색을 가진 사각형 브러시를 정의합니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class HatchBrush : Brush
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HatchBrush](hatchbrush/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | 해치 선 사이의 공간 색을 가져오거나 설정합니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | 해치 선의 색을 가져오거나 설정합니다. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | 이 브러시의 해치 스타일을 가져오거나 설정합니다. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 현재 [`Brush`](../../aspose.psd/brush/)의 새로운 깊은 복제본을 생성합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |

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

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


