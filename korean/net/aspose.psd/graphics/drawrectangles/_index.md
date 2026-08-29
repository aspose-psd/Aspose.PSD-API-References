---
title: "Graphics.DrawRectangles"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Graphics 메서드. RectangleF 구조체로 지정된 일련의 사각형을 그립니다."
type: docs
weight: 320
url: /ko/net/aspose.psd/graphics/drawrectangles/
---
{{< psd/tize >}}
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

[`RectangleF`](../../rectanglef/) 구조체로 지정된 일련의 사각형을 그립니다.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)은 사각형 윤곽선의 색상, 너비 및 스타일을 결정합니다. |
| rects | RectangleF[] | 그릴 사각형을 나타내는 [`RectangleF`](../../rectanglef/) 구조체 배열입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. -or- *rects*가 null입니다. |

### 또 보기

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

[`Rectangle`](../../rectangle/) 구조체로 지정된 일련의 사각형을 그립니다.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)은 사각형 윤곽선의 색상, 너비 및 스타일을 결정합니다. |
| rects | Rectangle[] | 그릴 사각형을 나타내는 [`Rectangle`](../../rectangle/) 구조체 배열입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pen*이 null입니다. -or- *rects*가 null입니다. |

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

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


