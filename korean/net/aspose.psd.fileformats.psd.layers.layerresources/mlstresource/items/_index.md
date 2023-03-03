---
title: MlstResource.Items
second_title: .NET API 참조용 Aspose.PSD
description: MlstResource 재산. 구조를 가져오거나 설정합니다.
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
## MlstResource.Items property

구조를 가져오거나 설정합니다.

```csharp
public OSTypeStructure[] Items { get; }
```

### 예

다음 코드는 레이어 상태를 조작하기 위한 하위 수준 메커니즘을 제공하는 MlstResource 리소스 지원을 보여줍니다.

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

    // 프레임 1에서 레이어 1 비활성화
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### 또한보십시오

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../mlstresource/)
* 집회 [Aspose.PSD](../../../)


