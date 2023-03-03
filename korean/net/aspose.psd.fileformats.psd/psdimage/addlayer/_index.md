---
title: PsdImage.AddLayer
second_title: .NET API 참조용 Aspose.PSD
description: PsdImage 방법. 레이어를 추가합니다.
type: docs
weight: 370
url: /ko/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
## PsdImage.AddLayer method

레이어를 추가합니다.

```csharp
public void AddLayer(Layer layer)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| layer | Layer | 레이어. |

### 예

다음 예제는 Aspose.PSD에서 간단한 생성자 버전을 사용하는 경우 새로 만든 레이어에 그릴 수 있는 방법을 보여줍니다.

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

    // 펜 도구로 사각형 그리기
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // 단색 브러시로 파란색의 다른 사각형을 그립니다.
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### 또한보십시오

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)


