---
title: LayerGroup.AddLayerGroup
second_title: Aspose.PSD for .NET API リファレンス
description: LayerGroup 方法. 画層グループを追加します
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
## LayerGroup.AddLayerGroup method

画層グループを追加します。

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| groupName | String | グループの名前。 |
| index | Int32 | 後に挿入するレイヤーのインデックス。 |

### 戻り値

グループレイヤーを開く

### 例

次の例は、LayerGroup を別の LayerGroup に追加する方法を示しています。

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// レイヤ階層を次のように作成します:
// -グループ 1
// -- レイヤー 1
// -- グループ 2
// --- レイヤー 2
// --- レイヤ 3
// -- レイヤ 4

var createOptions = new PsdOptions();
createOptions.Source = new FileCreateSource(sourceFileName, false);
createOptions.Palette = new PsdColorPalette(new Color[] { Color.Green });

using (var psdImage = (PsdImage)Image.Create(createOptions, 500, 500))
{
    LayerGroup group1 = psdImage.AddLayerGroup("Group 1", 0, false);

    Layer layer1 = new Layer(psdImage);
    layer1.Name = "Layer 1";
    group1.AddLayer(layer1);

    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);

    Layer layer2 = new Layer(psdImage);
    layer2.Name = "Layer 2";
    group2.AddLayer(layer2);

    Layer layer3 = new Layer(psdImage);
    layer3.Name = "Layer 3";
    group2.AddLayer(layer3);

    Layer layer4 = new Layer(psdImage);
    layer4.Name = "Layer 4";
    group1.AddLayer(layer4);

    psdImage.Save();
}
```

### 関連項目

* class [LayerGroup](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* 組み立て [Aspose.PSD](../../../)


