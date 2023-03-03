---
title: Layer.IsVisible
second_title: Aspose.PSD for .NET API リファレンス
description: Layer 財産. レイヤーが可視かどうかを示す値を取得または設定します
type: docs
weight: 170
url: /ja/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
## Layer.IsVisible property

レイヤーが可視かどうかを示す値を取得または設定します

```csharp
public bool IsVisible { get; set; }
```

### プロパティ値

`真実`このインスタンスが表示されている場合。さもないと、`間違い` .

### 例

次の例は、Aspose.PSD で LayerGroup の可視性を変更する方法を示しています。

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// レイヤー名を変更して保存
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // グループ内のすべてを無効にする
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### 関連項目

* class [Layer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 組み立て [Aspose.PSD](../../../)


