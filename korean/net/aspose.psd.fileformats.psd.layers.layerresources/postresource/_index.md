---
title: "클래스 PostResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PostResource 클래스. PostResource 클래스. 포스터라이즈 레이어 설정"
type: docs
weight: 3300
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/
---
{{< psd/tize >}}
## PostResource class

PostResource 클래스. 포스터화 레이어 설정.

```csharp
public class PostResource : AdjustmentLayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PostResource](postresource/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [Levels](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/) { get; set; } | Posterize 레이어의 레벨. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/typetoolkey/) | 타입 툴 정보 키. |

## 예제

다음 코드는 PostResource 조작 기능을 보여줍니다.

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];

    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is PostResource)
        {
            ((PostResource)resource).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### 또 보기

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


