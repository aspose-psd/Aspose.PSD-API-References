---
title: Class StreamSource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Sources.StreamSource 수업. 스트림 소스를 나타냅니다.
type: docs
weight: 5620
url: /ko/net/aspose.psd.sources/streamsource/
---
## StreamSource class

스트림 소스를 나타냅니다.

```csharp
public sealed class StreamSource : Source
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | 의 새 인스턴스를 초기화합니다.`StreamSource` 클래스. |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | 의 새 인스턴스를 초기화합니다.`StreamSource` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | 컨테이너가 폐기될 때마다 스트림을 폐기해야 하는지 여부를 나타내는 값을 가져옵니다. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | 스트림을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | 스트림 컨테이너를 가져옵니다. |

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

* class [Source](../../aspose.psd/source/)
* 네임스페이스 [Aspose.PSD.Sources](../../aspose.psd.sources/)
* 집회 [Aspose.PSD](../../)


