---
title: "IfxsResource.TypeToolKey"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "IfxsResource 필드. 타입 툴 정보 키"
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

타입 툴 정보 키.

```csharp
public const int TypeToolKey;
```

## 예제

다음 코드는 IfxsResource의 지원을 보여줍니다.

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
    // 예제에는 효과가 있는 2개의 그룹 레이어가 있습니다.
    // 하나의 효과가 있는 그룹 레이어
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // 여러 효과가 있는 그룹 레이어
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // 효과의 개수를 가져와서 수량을 확인합니다.
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // 그룹 레이어의 하나의 효과는 'IfxsResource' 리소스에 있습니다.
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // 그룹 레이어의 두 개 이상의 효과는 'ImfxResource' 리소스에 있습니다.
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // 다중 효과가 있는 그룹 레이어에 세 번째 그림자를 추가합니다
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### 또 보기

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


