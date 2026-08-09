---
title: "MlstResource.Items"
second_title: "Aspose.PSD for .NET API 参考"
description: "MlstResource 属性。获取或设置结构"
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
{{< psd/tize >}}
## MlstResource.Items property

获取或设置结构。

```csharp
public OSTypeStructure[] Items { get; }
```

## 示例

以下代码演示了对 MlstResource 资源的支持，该资源提供了操作图层状态的底层机制。

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

    // 在第 1 帧上禁用第 1 图层
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### 另请参阅

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


