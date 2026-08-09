---
title: "IfxsResource.TypeToolKey"
second_title: "Aspose.PSD for .NET API 参考"
description: "IfxsResource 字段。类型工具信息键"
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

类型工具信息键。

```csharp
public const int TypeToolKey;
```

## 示例

以下代码演示了 IfxsResource 的支持。

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // 示例包含 2 个带效果的组图层
    // 带单个效果的组图层
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // 带多个效果的组图层
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // 获取效果数量并验证其数量
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // 组图层中的一个效果位于资源 'IfxsResource' 中
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // 组图层中的两个或更多效果位于资源 'ImfxResource' 中
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // 为具有多重效果的组图层添加第三个阴影
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### 另请参阅

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


