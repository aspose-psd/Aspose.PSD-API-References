---
title: SectionDividerLayer.IsVisibleInGroup
second_title: Aspose.PSD for .NET API リファレンス
description: SectionDividerLayer 財産. このインスタンスがグループ内で可視かどうかを示す値を取得します レイヤーがグループ内にない場合はルート グループを意味します
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
## SectionDividerLayer.IsVisibleInGroup property

このインスタンスがグループ内で可視かどうかを示す値を取得します (レイヤーがグループ内にない場合は、ルート グループを意味します)。

```csharp
public override bool IsVisibleInGroup { get; }
```

### プロパティ値

`真実`このインスタンスがグループで表示されている場合。さもないと、`間違い` .

### 例

次のコードは、SectionDividerLayer レイヤーと、それに関連する LayerGroup を取得する方法を示しています。

```csharp
[C#]

// 次のコードは、SectionDividerLayer レイヤーとそれに関連する LayerGroup を取得する方法を示しています。

// レイヤー階層
// [0]: '</レイヤーグループ>'グループ 1 の SectionDividerLayer
// [1]: 'レイヤー 1' 通常のレイヤー
// [2]: '</レイヤーグループ>'グループ 2 の SectionDividerLayer
// [3]: '</レイヤーグループ>'グループ 3 の SectionDividerLayer
// [4]: 'グループ 3' GroupLayer
// [5]: 'グループ 2' GroupLayer
// [6]: 'グループ 1' GroupLayer

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
    // LayerGroup 'Group 1' を追加します
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // 通常のレイヤーを追加
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // LayerGroup 'Group 2' を追加します
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // LayerGroup 'Group 3' を追加します
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // SectionDividerLayer を取得します
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // SectionDividerLayer.GetRelatedLayerGroup() メソッドを使用して、関連する LayerGroup インスタンスを取得します。
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // 同じレイヤーグループ
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // 同じレイヤーグループ
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // 同じレイヤーグループ

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 「グループ 1」には 5 つのレイヤーが含まれます
}
```

### 関連項目

* class [SectionDividerLayer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../sectiondividerlayer/)
* 組み立て [Aspose.PSD](../../../)


