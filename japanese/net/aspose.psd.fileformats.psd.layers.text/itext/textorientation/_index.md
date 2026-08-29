---
title: "IText.TextOrientation"
second_title: "Aspose.PSD for .NET API Reference"
description: "IText プロパティ。テキストの向きを取得または設定します"
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
{{< psd/tize >}}
## IText.TextOrientation property

テキストの向きを取得または設定します。

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Property Value

テキストの向きです。

## 例

以下のコードは、新しい TextOrientation プロパティを編集できることを示しています。これは現在のレンダリングには影響せず、プロパティ値を編集できるだけです。

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // 正しい読み取り
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
        // 正しい読み取り
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### 関連項目

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


