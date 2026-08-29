---
title: "클래스 MlstResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource 클래스. mlst 리소스. 이 클래스는 다른 것들 중에서도 레이어가 타임라인에서 위치하는 정보 등을 포함합니다"
type: docs
weight: 3170
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
{{< psd/tize >}}
## MlstResource class

mlst 리소스. 이 클래스는 기타 항목 중 레이어가 타임라인에 위치하는 정보 등을 포함합니다.

```csharp
public class MlstResource : LayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MlstResource](mlstresource/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | 디스크립터 버전을 가져오거나 설정합니다. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | 구조를 가져오거나 설정합니다. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | 지정된 스트림 컨테이너를 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | 타입 툴 정보 키. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


