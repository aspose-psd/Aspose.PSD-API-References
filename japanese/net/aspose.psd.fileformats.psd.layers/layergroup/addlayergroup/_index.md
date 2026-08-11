---
title: "LayerGroup.AddLayerGroup"
second_title: "Aspose.PSD for .NET API Reference"
description: "LayerGroup メソッド。レイヤー グループを追加します"
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
{{< psd/tize >}}
## LayerGroup.AddLayerGroup method

レイヤー グループを追加します。

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| groupName | 文字列 | グループの名前です。 |
| インデックス | Int32 | 挿入後のレイヤーのインデックスです。 |

### 戻り値

グループレイヤーを開く

## 例

次の例は、LayerGroup を別の LayerGroup に追加する方法を示しています

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// 以下のようにレイヤー階層を作成します：
// -グループ 1
// --レイヤー 1
// --グループ 2
// ---レイヤー 2
// ---レイヤー 3
// --レイヤー 4

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


