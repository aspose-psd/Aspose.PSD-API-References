---
title: "LayerGroup.IsOpen"
second_title: "Aspose.PSD for .NET API Reference"
description: "LayerGroup プロパティ。フォルダーが開いているかどうかを取得または設定します。true に設定すると、起動時にグループは開いた状態になり、そうでなければ最小化された状態になります。"
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
{{< psd/tize >}}
## LayerGroup.IsOpen property

フォルダーが開いているかどうかを取得または設定します。`true` に設定すると、起動時にグループは開いた状態になり、そうでなければ最小化された状態になります。

```csharp
public bool IsOpen { get; set; }
```

## 例

以下のコードは、IsOpen プロパティを使用して LayerGroup（フォルダー）を開閉する方法を示しています。

```csharp
[C#]

// 実行時に IsOpen プロパティを読み書きする例です。
string sourceFileName = "LayerGroupOpenClose.psd";
string outputFileName = "OutputLayerGroupOpenClose.psd";

using (var image = (PsdImage) Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        if (layer is LayerGroup && layer.Name == "Group 1")
        {
            bool isOpenedGroup1 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup1;
        }

        if (layer is LayerGroup && layer.Name == "Group 2")
        {
            bool isOpenedGroup2 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup2;
        }
    }

    image.Save(outputFileName);
}
```

### 関連項目

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


