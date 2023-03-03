---
title: Enum TextOrientation
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.TextOrientation 列挙. テキスト方向モードの列挙
type: docs
weight: 4010
url: /ja/net/aspose.psd.fileformats.psd/textorientation/
---
## TextOrientation enumeration

テキスト方向モードの列挙。

```csharp
public enum TextOrientation
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| Horizontal | `0` | テキストの水平方向。 |
| Vertical | `2` | テキストの縦方向。 |

### 例

次のコードは、新しい TextOrientation プロパティを編集する機能を示しています。これは現時点ではレンダリングには影響しませんが、プロパティ値の編集のみ可能です。

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // 正しい読み方
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
        // 正しい読み方
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 組み立て [Aspose.PSD](../../)


