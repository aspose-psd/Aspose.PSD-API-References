---
title: IText.TextOrientation
second_title: Aspose.PSD for .NET API リファレンス
description: IText 財産. テキストの向きを取得または設定します
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

テキストの向きを取得または設定します。

```csharp
public TextOrientation TextOrientation { get; set; }
```

### プロパティ値

テキストの向き。

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

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* 組み立て [Aspose.PSD](../../../)


