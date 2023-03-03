---
title: Graphics.DrawPath
second_title: .NET API 참조용 Aspose.PSD
description: Graphics 방법. 그리기GraphicsPath .
type: docs
weight: 270
url: /ko/net/aspose.psd/graphics/drawpath/
---
## Graphics.DrawPath method

그리기[`GraphicsPath`](../../graphicspath/) .

```csharp
public void DrawPath(Pen pen, GraphicsPath path)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 경로의 색상, 너비 및 스타일을 결정합니다. |
| path | GraphicsPath | [`GraphicsPath`](../../graphicspath/) 그릴. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *pen* null입니다. -또는- *path* null입니다. |

### 예

이 예제에서는 GraphicsPath 및 Graphics 클래스를 사용하여 이미지 표면에서 그림을 만들고 조작합니다. 예제에서는 새 이미지를 만들고 GraphicsPath 클래스의 도움으로 경로를 그립니다. 마지막에 Graphics 클래스에 의해 노출된 DrawPath 메서드가 호출되어 표면에 경로를 렌더링합니다. 마지막으로 이미지를 Tiff 파일 형식으로 내보냅니다.

```csharp
[C#]

//이미지 인스턴스 생성 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics 클래스의 인스턴스 생성 및 초기화
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //그래픽 표면 지우기
    graphics.Clear(Color.Wheat);

    // GraphicsPath 클래스의 인스턴스 생성
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Figure 클래스의 인스턴스 생성
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //도형 객체에 도형 추가
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    // GraphicsPath에 Figure 객체 추가
    graphicspath.AddFigure(figure);

    //검은색의 Pen 객체로 경로를 그립니다.
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //TiffOptions의 인스턴스를 만들고 다양한 속성을 설정합니다.
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // 모든 변경 사항을 저장합니다.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 또한보십시오

* class [Pen](../../pen/)
* class [GraphicsPath](../../graphicspath/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)


