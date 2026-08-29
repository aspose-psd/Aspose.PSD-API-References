---
title: "클래스 BaseFxResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BaseFxResource 클래스. 기본 효과 리소스"
type: docs
weight: 2550
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/basefxresource/
---
{{< psd/tize >}}
## BaseFxResource class

기본 효과 리소스

```csharp
public abstract class BaseFxResource : LayerResource
```

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

## 예제

다음 코드는 멀티 이펙트 리소스 지원을 보여줍니다.

```csharp
[C#]

// PSD 이미지에 2개의 Drop Shadow 효과가 포함되어 있습니다.
string sourceFile = "MultiExample.psd";
string outputFile1 = "export1.png";
string outputFile2 = "export2.png";
string outputFile3 = "export3.png";

using (PsdImage image = (PsdImage)Aspose.PSD.Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    // PSD 이미지를 2개의 Drop Shadow 효과와 함께 렌더링합니다.
    image.Save(outputFile1, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    var blendingOptions = image.Layers[0].BlendingOptions;

    // 세 번째 Drop Shadow 효과를 추가합니다.
    DropShadowEffect dropShadowEffect3 = blendingOptions.AddDropShadow();
    dropShadowEffect3.Color = Color.Red;
    dropShadowEffect3.Distance = 50;
    dropShadowEffect3.Angle = 0;

    // PSD 이미지를 3개의 Drop Shadow 효과와 함께 렌더링합니다.
    image.Save(outputFile2, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // 레이어에 동일 유형의 여러 효과가 포함된 경우 imfx 리소스를 사용합니다.
    var imfx = (ImfxResource)image.Layers[0].Resources[0];

    // 모든 효과를 지웁니다.
    blendingOptions.Effects = new ILayerEffect[0];

    DropShadowEffect dropShadowEffect1 = blendingOptions.AddDropShadow();
    dropShadowEffect1.Color = Color.Blue;
    dropShadowEffect1.Distance = 10;

    // PSD 이미지에 1개의 드롭 섀도우 효과를 적용합니다 (다른 효과는 삭제되었습니다)
    image.Save(outputFile3, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // 레이어에 동일 유형의 여러 효과가 포함되지 않은 경우 lfx2 리소스를 사용합니다.
    var lfx2 = (Lfx2Resource)image.Layers[0].Resources[14];
}
```

### 또 보기

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


