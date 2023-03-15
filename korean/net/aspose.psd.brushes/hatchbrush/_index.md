---
title: Class HatchBrush
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Brushes.HatchBrush 수업. 해치 스타일 전경색 및 배경색으로 사각형 브러시를 정의합니다. 이 클래스는 상속될 수 없습니다.
type: docs
weight: 130
url: /ko/net/aspose.psd.brushes/hatchbrush/
---
## HatchBrush class

해치 스타일, 전경색 및 배경색으로 사각형 브러시를 정의합니다. 이 클래스는 상속될 수 없습니다.

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
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | 해치 선 사이의 공간 색상을 가져오거나 설정합니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | 해치 선의 색상을 가져오거나 설정합니다. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | 이 브러시의 해치 스타일을 가져오거나 설정합니다. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 값이 0이면 브러시가 완전히 표시되고 값이 1이면 브러시가 완전히 불투명합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 현재의 새로운 딥 클론을 생성합니다.[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |

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

* class [Brush](../../aspose.psd/brush/)
* 네임스페이스 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 집회 [Aspose.PSD](../../)


