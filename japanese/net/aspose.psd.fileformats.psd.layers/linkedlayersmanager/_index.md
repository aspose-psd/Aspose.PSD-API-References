---
title: Class LinkedLayersManager
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LinkedLayersManager クラス. リンクされたレイヤ マネージャ クラス.
type: docs
weight: 3400
url: /ja/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---
## LinkedLayersManager class

リンクされたレイヤ マネージャ クラス.

```csharp
public sealed class LinkedLayersManager
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetLayersByLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/)(short) | リンク グループ ID でレイヤーを取得します。 |
| [GetLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/)(Layer) | レイヤーに関連付けられたリンク グループ ID を取得します。 |
| [LinkLayers](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/)(Layer[]) | 入力レイヤーをリンクし、LingGroupId. を返します |
| [UnlinkLayer](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/)(Layer) | レイヤーのリンクを解除します.. |

### 例

次の例は、Aspose.PSD でリンク レイヤーを操作する方法を示しています。

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // 1 つのリンクされたグループ内のすべてのレイヤーをリンクします
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // 1 つのレイヤーの ID を取得します
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // リンク グループ ID でリンクされたすべてのレイヤーを取得します。
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // グループから各レイヤーのリンクを解除
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // グループ内にレイヤーがないリンク グループ ID の場合は NULL を取得します。
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 組み立て [Aspose.PSD](../../)


