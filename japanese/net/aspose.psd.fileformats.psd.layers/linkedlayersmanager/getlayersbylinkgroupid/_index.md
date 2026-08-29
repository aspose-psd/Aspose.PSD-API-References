---
title: "LinkedLayersManager.GetLayersByLinkGroupId"
second_title: "Aspose.PSD for .NET API Reference"
description: "LinkedLayersManager メソッド。リンク グループ ID によってレイヤーを取得します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/
---
{{< psd/tize >}}
## LinkedLayersManager.GetLayersByLinkGroupId method

リンクグループIDでレイヤーを取得します。

```csharp
public Layer[] GetLayersByLinkGroupId(short linkGroupId)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| linkGroupId | Int16 | リンク グループ IDです。 |

### 戻り値

レイヤー配列です。

## 例

以下の例は、Aspose.PSD でリンクされたレイヤーを操作する方法を示しています。

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします。
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // すべてのレイヤーを1つのリンクグループにリンクします。
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // 1つのレイヤーの ID を取得します。
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // リンクグループIDで全てのリンクされたレイヤーを取得します。
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // 各レイヤーをグループからリンク解除します。
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // グループにレイヤーが存在しないリンクグループIDに対して NULL を返します。
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


