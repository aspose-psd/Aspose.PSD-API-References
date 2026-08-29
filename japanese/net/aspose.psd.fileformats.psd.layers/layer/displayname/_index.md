---
title: "Layer.DisplayName"
second_title: "Aspose.PSD for .NET API Reference"
description: "Layer プロパティ。レイヤーの表示名を取得または設定します"
type: docs
weight: 110
url: /ja/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
{{< psd/tize >}}
## Layer.DisplayName property

レイヤーの表示名を取得または設定します。

```csharp
public string DisplayName { get; set; }
```

### Property Value

レイヤーの表示名です。

## 例

以下の例は、DisplayName の値を設定する機能を示し、レイヤー名が正しく表示されることを示します。

```csharp
[C#]

// レイヤー名を変更して保存します
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // DisplayName プロパティに新しい値を設定する
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### 関連項目

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


