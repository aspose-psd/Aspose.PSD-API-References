---
title: "클래스 LmskResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LmskResource 클래스. LMsk 리소스"
type: docs
weight: 3020
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---
{{< psd/tize >}}
## LmskResource class

LMsk 리소스.

```csharp
public class LmskResource : LayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LmskResource](lmskresource/)() | `LmskResource` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ColorComponent1](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent1/) { get; set; } | 색상 구성 요소 1을 가져옵니다. |
| [ColorComponent2](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/) { get; set; } | 색상 구성 요소 2를 가져옵니다. |
| [ColorComponent3](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/) { get; set; } | 색상 구성 요소 3을 가져옵니다. |
| [ColorComponent4](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/) { get; set; } | 색상 구성 요소 4를 가져옵니다. |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/) { get; set; } | 색상 공간을 가져옵니다. |
| [Flag](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/) { get; } | 플래그를 가져옵니다. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/) { get; set; } | 불투명도를 가져옵니다. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/typetoolkey/) | 타입 툴 정보 키. |

## 비고

이 리소스에는 특정 색상 공간 유형을 나타내는 color space ID와 4개의 색상 구성 요소가 포함되어 있습니다. ID에 따라 색상 구성 요소의 의미가 달라집니다. 색상 공간 유형이 네 개의 값을 필요로 하지 않으면, 추가 구성 요소는 정의되지 않으며 항상 0으로 기록됩니다. 색상 공간 유형별 색상 구성 요소: RGB - 처음 세 구성 요소는 빨강, 초록, 파랑입니다. HSB - 처음 세 구성 요소는 색조, 채도, 밝기입니다. CMYK - 네 구성 요소는 시안, 마젠타, 노랑, 검정입니다. Lab - 처음 세 구성 요소는 명도, a 크로미넌스, b 크로미넌스입니다. Grayscale - 첫 번째 구성 요소는 회색 값이며, 0...10000 범위입니다.

## 예제

다음 코드는 16비트 이미지에서 LmskResource 속성을 변경하여 레이어 마스크 표시 옵션을 변경하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// 16비트 이미지를 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // LmskResource를 찾습니다.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // LmskResource 속성을 확인합니다.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // LmskResource 속성을 변경합니다.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // 이미지를 저장합니다.
    image.Save(outputPsd);
}
```

### 또 보기

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


