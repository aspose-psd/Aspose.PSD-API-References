---
title: Class SoCoResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoCoResource 수업. 클래스 SoCoResource. 이 리소스에는 색상 채우기 레이어 에 대한 정보가 포함되어 있습니다.
type: docs
weight: 3010
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
## SoCoResource class

클래스 SoCoResource. 이 리소스에는 색상 채우기 레이어 에 대한 정보가 포함되어 있습니다.

```csharp
public class SoCoResource : FillLayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SoCoResource](socoresource/)() | 의 새 인스턴스를 초기화합니다.`SoCoResource` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/) { get; set; } | RGB 색상을 가져옵니다. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 psd 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/signature/) { get; } | 레이어 리소스 서명을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey/) | 유형 도구 정보 키입니다. |

### 예

다음 예는 SoCoResource(색상 채우기 레이어의 레이어 리소스)를 편집하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // FillLayer 찾기
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Layer Resource List에서 SoCoResource 찾기
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // SoCoResource 색상 속성 설정
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### 또한보십시오

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 집회 [Aspose.PSD](../../)


