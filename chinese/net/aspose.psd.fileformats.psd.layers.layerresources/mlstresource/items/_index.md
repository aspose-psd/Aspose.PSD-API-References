---
title: MlstResource.Items
second_title: Aspose.PSD for .NET API 参考
description: MlstResource 财产. 获取或设置结构
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
## MlstResource.Items property

获取或设置结构。

```csharp
public OSTypeStructure[] Items { get; }
```

### 例子

以下代码演示了对 MlstResource 资源的支持，该资源提供了一种操纵层状态的低级机制。

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // 在第 1 帧禁用第 1 层
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### 也可以看看

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../mlstresource/)
* 部件 [Aspose.PSD](../../../)


