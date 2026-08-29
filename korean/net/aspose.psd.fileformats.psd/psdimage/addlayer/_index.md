---
title: "PsdImage.AddLayer"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdImage 메서드. 레이어를 추가합니다"
type: docs
weight: 390
url: /ko/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
{{< psd/tize >}}
## PsdImage.AddLayer method

레이어를 추가합니다.

```csharp
public void AddLayer(Layer layer)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 레이어 | 레이어 | 레이어. |

## 예제

다음 예제는 Aspose.PSD에서 단순 생성자 버전을 사용할 경우 새로 만든 레이어에 그릴 수 있는 방법을 보여줍니다

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // Pen 도구로 사각형을 그립니다
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // Solid Brush를 사용하여 파란색으로 또 다른 사각형을 그립니다
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### 또 보기

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


