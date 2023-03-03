---
title: PsdImage.AddRegularLayer
second_title: .NET API 참조용 Aspose.PSD
description: PsdImage 방법. 새 일반 레이어를 추가합니다.
type: docs
weight: 410
url: /ko/net/aspose.psd.fileformats.psd/psdimage/addregularlayer/
---
## PsdImage.AddRegularLayer method

새 일반 레이어를 추가합니다.

```csharp
public Layer AddRegularLayer()
```

### 반환 값

일반 레이어를 생성했습니다.

### 예

다음 코드는 새로 생성된 일반 레이어를 PsdImage에 추가하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFileName = "OneLayer.psd";
string exportPath = "OneLayerEdited.psd";
string exportPathPng = "OneLayerEdited.png";

using (var im = (PsdImage)Image.Load(sourceFileName))
{
    // 두 개의 int 배열 준비
    var data1 = new int[2500];
    var data2 = new int[2500];

    var rect1 = new Rectangle(0, 0, 50, 50);
    var rect2 = new Rectangle(0, 0, 100, 25);

    for (int i = 0; i < 2500; i++)
    {
        data1[i] = -10000000;
        data2[i] = -10000000;
    }

    var layer1 = im.AddRegularLayer();
    layer1.Left = 25;
    layer1.Top = 25;
    layer1.Right = 75;
    layer1.Bottom = 75;
    layer1.SaveArgb32Pixels(rect1, data1);

    var layer2 = im.AddRegularLayer();
    layer2.Left = 25;
    layer2.Top = 150;
    layer2.Right = 125;
    layer2.Bottom = 175;
    layer2.SaveArgb32Pixels(rect2, data2);

    // psd 저장
    im.Save(exportPath, new PsdOptions());

    // png 저장
    im.Save(exportPathPng, new PngOptions());
}
```

### 또한보십시오

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)


