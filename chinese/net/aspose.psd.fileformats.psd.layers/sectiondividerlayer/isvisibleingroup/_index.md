---
title: "SectionDividerLayer.IsVisibleInGroup"
second_title: "Aspose.PSD for .NET API 参考"
description: "SectionDividerLayer 属性。获取指示此实例在组中是否可见的值。如果图层不在组中，则表示根组"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
{{< psd/tize >}}
## SectionDividerLayer.IsVisibleInGroup property

获取一个值，指示此实例在组中是否可见（如果图层不在组中，则表示根组）。

```csharp
public override bool IsVisibleInGroup { get; }
```

### Property Value

`true` 表示此实例在组中可见；否则为 `false`。

## 示例

以下代码演示 SectionDividerLayer 图层以及如何获取与其关联的 LayerGroup。

```csharp
[C#]

// 以下代码演示 SectionDividerLayer 图层以及如何获取与其关联的 LayerGroup。

// 图层层次结构
//    [0]: '</Layer group>' 用于组 1 的 SectionDividerLayer
//    [1]: 'Layer 1' 常规图层
//    [2]: '</Layer group>' 用于组 2 的 SectionDividerLayer
//    [3]: '</Layer group>' 用于组 3 的 SectionDividerLayer
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
    // 创建图层层次结构
    // 添加 LayerGroup 'Group 1'
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // 添加普通图层
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // 添加 LayerGroup 'Group 2'
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // 添加 LayerGroup 'Group 3'
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // 获取 SectionDividerLayer 的
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // 使用 SectionDividerLayer.GetRelatedLayerGroup() 方法，获取相关的 LayerGroup 实例。
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // the same LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' contains 5 layers
}
```

### 另请参阅

* class [SectionDividerLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


