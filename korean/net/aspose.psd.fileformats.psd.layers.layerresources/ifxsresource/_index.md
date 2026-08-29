---
title: "클래스 IfxsResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IfxsResource 클래스. Ifxs 리소스 그룹 레이어 효과 리소스"
type: docs
weight: 2840
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---
{{< psd/tize >}}
## IfxsResource class

Ifxs 리소스 (그룹 레이어 효과 리소스)

```csharp
public sealed class IfxsResource : BaseFxResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [IfxsResource](ifxsresource/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | 디스크립터 버전을 가져옵니다. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/) | 타입 툴 정보 키. |

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

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


