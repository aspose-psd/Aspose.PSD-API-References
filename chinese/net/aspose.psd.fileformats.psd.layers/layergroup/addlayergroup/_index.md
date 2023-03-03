---
title: LayerGroup.AddLayerGroup
second_title: Aspose.PSD for .NET API 参考
description: LayerGroup 方法. 添加层组
type: docs
weight: 70
url: /zh/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
## LayerGroup.AddLayerGroup method

添加层组。

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| groupName | String | 组的名称。 |
| index | Int32 | 要在其后插入的层的索引。 |

### 返回值

打开图层组

### 例子

以下示例演示将 LayerGroup 添加到另一个 LayerGroup 中。

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// 像这样制作图层层次结构：
// - 第 1 组
// --第一层
// -- 第 2 组
// ---第 2 层
// ---第 3 层
// --第4层

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

### 也可以看看

* class [LayerGroup](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* 部件 [Aspose.PSD](../../../)


