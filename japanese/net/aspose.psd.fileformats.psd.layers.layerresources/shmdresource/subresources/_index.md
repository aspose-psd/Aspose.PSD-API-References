---
title: "ShmdResource.SubResources"
second_title: "Aspose.PSD for .NET API Reference"
description: "ShmdResource プロパティ。shmd リソースのサブリソースを取得します"
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
{{< psd/tize >}}
## ShmdResource.SubResources property

shmd リソースのサブリソースを取得します。

```csharp
public LayerResource[] SubResources { get; }
```

## 例

次のコードは、レイヤー状態を操作するための低レベルメカニズムを提供する MlstResource リソースのサポートを示しています

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

    // フレーム 1 でレイヤー 1 を無効にする
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### 関連項目

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


