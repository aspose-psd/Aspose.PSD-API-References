---
title: "Enum TextOrientation"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.TextOrientation enum. テキスト方向モードの列挙体"
type: docs
weight: 4480
url: /ja/net/aspose.psd.fileformats.psd/textorientation/
---
{{< psd/tize >}}
## TextOrientation enumeration

テキスト方向モードの列挙体です。

```csharp
public enum TextOrientation
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Horizontal | `0` | 水平テキスト方向。 |
| Vertical | `2` | 垂直テキスト方向。 |

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

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


