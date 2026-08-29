---
title: "MlstResource.Items"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "MlstResource 속성. 구조를 가져오거나 설정합니다"
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
{{< psd/tize >}}
## MlstResource.Items property

구조를 가져오거나 설정합니다.

```csharp
public OSTypeStructure[] Items { get; }
```

## 예제

다음 코드는 레이어 상태를 조작하기 위한 저수준 메커니즘을 제공하는 MlstResource 리소스 지원을 보여줍니다

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

    // 프레임 1에서 레이어 1을 비활성화합니다
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### 또 보기

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


