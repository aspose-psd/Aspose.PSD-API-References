---
title: Graphics.DrawRectangles
second_title: .NET API 참조용 Aspose.PSD
description: Graphics 방법. 에 의해 지정된 일련의 사각형을 그립니다.RectangleF 구조.
type: docs
weight: 310
url: /ko/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

에 의해 지정된 일련의 사각형을 그립니다.[`RectangleF`](../../rectanglef/) 구조.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 사각형 외곽선의 색상, 너비 및 스타일을 결정합니다. |
| rects | RectangleF[] | 의 배열[`RectangleF`](../../rectanglef/) 그릴 사각형을 나타내는 구조체입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. -또는- *rects* null입니다. |

### 또한보십시오

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

에 의해 지정된 일련의 사각형을 그립니다.[`Rectangle`](../../rectangle/) 구조.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 사각형 외곽선의 색상, 너비 및 스타일을 결정합니다. |
| rects | Rectangle[] | 의 배열[`Rectangle`](../../rectangle/) 그릴 사각형을 나타내는 구조체입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. -또는- *rects* null입니다. |

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

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)


