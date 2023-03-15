---
title: LinkedLayersManager.LinkLayers
second_title: Aspose.PSD for .NET API リファレンス
description: LinkedLayersManager 方法. 入力レイヤーをリンクしLingGroupId. を返します
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/
---
## LinkedLayersManager.LinkLayers method

入力レイヤーをリンクし、LingGroupId. を返します

```csharp
public short LinkLayers(Layer[] layers)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| layers | Layer[] | レイヤー。 |

### 戻り値

リンク グループ ID。

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | レイヤーはヌルです。 |
| ArgumentException | レイヤーの数は 1 より大きくなければなりません。 |
| ArgumentException | 各レイヤーのコンテナーは、現在の PsdImage と同じである必要があります。 |

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

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* 組み立て [Aspose.PSD](../../../)


