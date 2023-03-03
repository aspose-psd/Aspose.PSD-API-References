---
title: LayerGroup.IsOpen
second_title: Aspose.PSD for .NET API リファレンス
description: LayerGroup 財産. フォルダーが開かれていることを取得または設定します に設定されている場合真実グループは起動時に開いた状態になりそれ以外の場合は最小化された状態になります.
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
## LayerGroup.IsOpen property

フォルダーが開かれていることを取得または設定します に設定されている場合`真実`グループは起動時に開いた状態になり、それ以外の場合は最小化された状態になります.

```csharp
public bool IsOpen { get; set; }
```

### 例

次のコードは、IsOpen プロパティを使用して LayerGroup (フォルダー) を開いたり閉じたりする方法を示しています。

```csharp
[C#]

// 実行時に IsOpen プロパティを読み書きする例。
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
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* 組み立て [Aspose.PSD](../../../)


