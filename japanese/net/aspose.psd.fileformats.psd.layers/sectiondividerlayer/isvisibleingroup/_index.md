---
title: "SectionDividerLayer.IsVisibleInGroup"
second_title: "Aspose.PSD for .NET API Reference"
description: "SectionDividerLayer プロパティ。このインスタンスがグループ内で表示されているかどうかを示す値を取得します。レイヤーがグループに属していない場合はルートグループを意味します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
{{< psd/tize >}}
## SectionDividerLayer.IsVisibleInGroup property

このインスタンスがグループ内で表示されているかどうかを示す値を取得します（レイヤーがグループに属していない場合はルートグループを意味します）。

```csharp
public override bool IsVisibleInGroup { get; }
```

### Property Value

このインスタンスがグループ内で可視の場合は `true`、それ以外の場合は `false`。

## 例

以下のコードは SectionDividerLayer のレイヤーと、それに関連する LayerGroup の取得方法を示しています。

```csharp
[C#]

// 以下のコードは SectionDividerLayer のレイヤーと、それに関連する LayerGroup の取得方法を示しています。

// レイヤー階層
//    [0]: '</Layer group>' Group 1 の SectionDividerLayer
//    [1]: 'Layer 1' 通常レイヤー
//    [2]: '</Layer group>' Group 2 の SectionDividerLayer
//    [3]: '</Layer group>' Group 3 の SectionDividerLayer
//    [4]: 'Group 3' GroupLayer
//    [5]: 'Group 2' GroupLayer
//    [6]: 'Group 1' GroupLayer

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // レイヤー階層の作成
    // レイヤー グループ 'Group 1' を追加
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // 通常レイヤーを追加
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // レイヤー グループ 'Group 2' を追加
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // レイヤー グループ 'Group 3' を追加
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // SectionDividerLayer の取得
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // SectionDividerLayer.GetRelatedLayerGroup() メソッドを使用して、関連する LayerGroup インスタンスを取得します。
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // the same LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' contains 5 layers
}
```

### 関連項目

* class [SectionDividerLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


