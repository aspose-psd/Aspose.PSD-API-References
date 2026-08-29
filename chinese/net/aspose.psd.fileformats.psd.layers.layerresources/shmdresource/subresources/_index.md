---
title: "ShmdResource.SubResources"
second_title: "Aspose.PSD for .NET API 参考"
description: "ShmdResource 属性。获取 shmd 资源的子资源"
type: docs
weight: 40
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
{{< psd/tize >}}
## ShmdResource.SubResources property

获取 shmd 资源的子资源。

```csharp
public LayerResource[] SubResources { get; }
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

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


