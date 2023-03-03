---
title: MlstResource.Items
second_title: Aspose.PSD for .NET API リファレンス
description: MlstResource 財産. 構造体を取得または設定します
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
## MlstResource.Items property

構造体を取得または設定します。

```csharp
public OSTypeStructure[] Items { get; }
```

### 例

次のコードは、層の状態を操作する低レベルのメカニズムを提供する MlstResource リソースのサポートを示しています。

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

    // フレーム 1 のレイヤー 1 を無効にする
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### 関連項目

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../mlstresource/)
* 組み立て [Aspose.PSD](../../../)


