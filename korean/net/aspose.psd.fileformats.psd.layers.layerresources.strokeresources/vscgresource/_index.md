---
title: "클래스 VscgResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.VscgResource class. 벡터 스트로크 콘텐츠 데이터 리소스"
type: docs
weight: 3430
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---
{{< psd/tize >}}
## VscgResource class

벡터 스트로크 콘텐츠 데이터 리소스.

```csharp
public class VscgResource : LayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [VscgResource](vscgresource/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/items/) { get; } | 구조 항목 배열을 가져오거나 설정합니다. **Warning:** `Items` 배열 값은 `KeyForData` 속성과 일치해야 하며, 이는 `Items` 내부 구조에 저장된 채우기 설정 유형을 결정합니다. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| [KeyForData](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/keyfordata/) { get; } | 리소스에 저장된 채우기 설정 종류를 정의하는 정수 키를 가져옵니다: * Color - 0x536f436f - SoCoResource.TypeToolKey * Gradient - 0x4764466c - GdFlResource.TypeToolKey * Pattern - 0x5074466c - PtFlResource.TypeToolKey 경고! 속성 KeyForData의 값은 Items 구조에 저장된 Fill 설정 유형과 일치해야 합니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/typetoolkey/) | 타입 툴 정보 키. |

## 예제

다음 코드는 VscgResource 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "StrokeInternalFill_src.psd";
string outputFile = "StrokeInternalFill_res.psd";

void AreEqual(double expected, double current, double tolerance = 0.1)
{
    if (Math.Abs(expected - current) > tolerance)
    {
        throw new Exception(
            $"Values is not equal.\nExpected:{expected}\nResult:{current}\nDifference:{expected - current}");
    }
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(89.8, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(219.6, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(34.2, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);

    ((DoubleStructure)rgbColorStructure.Structures[0]).Value = 255d; // Red
    ((DoubleStructure)rgbColorStructure.Structures[1]).Value = 0d; // Green
    ((DoubleStructure)rgbColorStructure.Structures[2]).Value = 0d; // Blue

    image.Save(outputFile);
}

// 변경 사항 확인 중
using (PsdImage image = (PsdImage)Image.Load(outputFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(255, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);
}
```

### 또 보기

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


