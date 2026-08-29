---
title: "클래스 VibAResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VibAResource 클래스. VibA 리소스"
type: docs
weight: 3750
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/
---
{{< psd/tize >}}
## VibAResource class

VibA 리소스.

```csharp
public class VibAResource : AdjustmentLayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [VibAResource](vibaresource/)() | `VibAResource` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| [Saturation](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/saturation/) { get; set; } | 채도 값을 가져오거나 설정합니다 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |
| [Vibrance](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance/) { get; set; } | 생동감 값을 가져오거나 설정합니다 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/) | 타입 툴 정보 키. |

## 예제

다음 코드 예제는 VibAResource 리소스의 지원을 보여줍니다.

```csharp
[C#]

// 런타임에서 Vibration 리소스를 읽고 쓰는 지원 예시입니다.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### 또 보기

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


