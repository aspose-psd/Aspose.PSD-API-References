---
title: "클래스 ArtBResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ArtBResource 클래스. Resources에 대한 아트보드 정보 데이터"
type: docs
weight: 2520
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/
---
{{< psd/tize >}}
## ArtBResource class

[`Resources`](../../aspose.psd.fileformats.psd.layers/layer/resources/)에 대한 아트보드 정보 데이터.

```csharp
public sealed class ArtBResource : BaseArtboardInfoResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ArtBResource](artbresource/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ArtboardBackgroundType](../../aspose.psd.fileformats.psd.layers.layerresources/artbresource/artboardbackgroundtype/) { get; set; } | [`ArtboardBackgroundType`](./artboardbackgroundtype/)를 가져오거나 설정합니다. |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/artbresource/color/) { get; set; } | [`Color`](./color/)를 가져오거나 설정합니다. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/items/) { get; set; } | [`OSTypeStructure`](../ostypestructure/) 항목을 가져오거나 설정합니다. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/length/) { get; } |  |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/artbresource/typetoolkey/) | 타입 툴 정보 키. |

## 예제

다음 코드는 아트보드 리소스 지원을 보여줍니다.

```csharp
[C#]

string srcFile = "artboard1.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    ArtDResource artDResource = (ArtDResource)psdImage.GlobalLayerResources[2];

    ArtBResource artBResource1 = (ArtBResource)psdImage.Layers[2].Resources[7];
    ArtBResource artBResource2 = (ArtBResource)psdImage.Layers[5].Resources[7];

    LyvrResource lyvrResource1 = (LyvrResource)psdImage.Layers[2].Resources[9];
    LyvrResource lyvrResource2 = (LyvrResource)psdImage.Layers[5].Resources[9];

    var countStruct = (IntegerStructure)artDResource.Items[0];
    AssertAreEqual(2, countStruct.Value);

    var presetNameStruct1 = (StringStructure)artBResource1.Items[2];
    AssertAreEqual("iPhone X\0", presetNameStruct1.Value);

    var presetNameStruct2 = (StringStructure)artBResource2.Items[2];
    AssertAreEqual("iPhone X\0", presetNameStruct2.Value);

    AssertAreEqual(160, lyvrResource1.Version);
    AssertAreEqual(160, lyvrResource2.Version);
}

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}
```

### 또 보기

* class [BaseArtboardInfoResource](../baseartboardinforesource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


