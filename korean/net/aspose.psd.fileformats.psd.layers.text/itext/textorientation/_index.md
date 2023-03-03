---
title: IText.TextOrientation
second_title: .NET API 참조용 Aspose.PSD
description: IText 재산. 텍스트 방향을 가져오거나 설정합니다.
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

텍스트 방향을 가져오거나 설정합니다.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### 자산 가치

텍스트 방향입니다.

### 예

다음 코드는 새 TextOrientation 속성을 편집하는 기능을 보여줍니다. 이것은 현재 렌더링에 영향을 미치지 않지만 속성 값을 편집할 수만 있습니다.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // 올바른 읽기
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }

    textLayer.TextData.TextOrientation = TextOrientation.Horizontal;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Horizontal)
    {
        // 올바른 읽기
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### 또한보십시오

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* 집회 [Aspose.PSD](../../../)


