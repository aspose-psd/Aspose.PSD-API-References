---
title: "ShmdResource.SubResources"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ShmdResource 속성. shmd 리소스의 하위 리소스를 가져옵니다"
type: docs
weight: 40
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
{{< psd/tize >}}
## ShmdResource.SubResources property

shmd 리소스의 하위 리소스를 가져옵니다.

```csharp
public LayerResource[] SubResources { get; }
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

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


