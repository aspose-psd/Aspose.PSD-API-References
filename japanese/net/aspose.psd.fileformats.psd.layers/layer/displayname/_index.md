---
title: Layer.DisplayName
second_title: Aspose.PSD for .NET API リファレンス
description: Layer 財産. レイヤーの表示名を取得または設定します
type: docs
weight: 100
url: /ja/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

レイヤーの表示名を取得または設定します。

```csharp
public string DisplayName { get; set; }
```

### プロパティ値

レイヤーの表示名。

### 例

次の例は、レイヤー名が正しく表示されるように、DisplayName 値を設定する機能を示しています。

```csharp
[C#]

// レイヤー名を変更して保存
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // 新しい値を DisplayName プロパティに設定します
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### 関連項目

* class [Layer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 組み立て [Aspose.PSD](../../../)


