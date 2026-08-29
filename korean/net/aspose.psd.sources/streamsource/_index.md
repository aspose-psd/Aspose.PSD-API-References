---
title: "클래스 StreamSource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Sources.StreamSource 클래스. 스트림 소스를 나타냅니다."
type: docs
weight: 6120
url: /ko/net/aspose.psd.sources/streamsource/
---
{{< psd/tize >}}
## StreamSource class

스트림 소스를 나타냅니다.

```csharp
public sealed class StreamSource : Source
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | `StreamSource` 클래스의 새 인스턴스를 초기화합니다. |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | `StreamSource` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | 컨테이너가 폐기될 때 스트림을 폐기해야 하는지 여부를 나타내는 값을 가져옵니다. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | 스트림을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | 스트림 컨테이너를 가져옵니다. |

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

* class [Source](../../aspose.psd/source/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


