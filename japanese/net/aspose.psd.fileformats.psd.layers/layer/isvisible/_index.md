---
title: "Layer.IsVisible"
second_title: "Aspose.PSD for .NET API Reference"
description: "Layer プロパティ。レイヤーが表示されているかどうかを示す値を取得または設定します"
type: docs
weight: 180
url: /ja/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

レイヤーが表示されているかどうかを示す値を取得または設定します

```csharp
public bool IsVisible { get; set; }
```

### Property Value

このインスタンスが表示されている場合は `true`、それ以外の場合は `false`。

## 例

次の例は、Aspose.PSD で LayerGroup の表示状態を変更する方法を示しています。

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// レイヤー名を変更して保存します
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // グループ内のすべてをオフにします
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


