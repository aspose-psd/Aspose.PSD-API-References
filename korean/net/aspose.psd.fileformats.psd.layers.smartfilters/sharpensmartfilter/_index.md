---
title: "클래스 SharpenSmartFilter"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SharpenSmartFilter 클래스. Sharpen 스마트 필터"
type: docs
weight: 3870
url: /ko/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter class

Sharpen 스마트 필터입니다.

```csharp
public sealed class SharpenSmartFilter : SmartFilter
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SharpenSmartFilter](sharpensmartfilter/#constructor)() | 새 `SharpenSmartFilter` 클래스 인스턴스를 초기화합니다. |
| [SharpenSmartFilter](sharpensmartfilter/#constructor_1)(DescriptorStructure) | 새 `SharpenSmartFilter` 클래스 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | 블렌딩 모드를 가져오거나 설정합니다. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filterid/) { get; } | 스마트 필터 유형 식별자를 가져옵니다. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | 스마트 필터의 활성화 상태를 가져오거나 설정합니다. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/name/) { get; } | 스마트 필터 이름을 가져옵니다. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | 스마트 필터의 불투명도 값을 가져오거나 설정합니다. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | 스마트 필터 데이터가 포함된 소스 디스크립터 구조체. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | 현재 필터를 입력 [`RasterImage`](../../aspose.psd/rasterimage/) 이미지에 적용합니다. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | 현재 필터를 입력 [`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) 마스크 데이터에 적용합니다. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | 해당 유형의 현재 인스턴스를 멤버별로 복제합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filtertype/) | 현재 스마트 필터의 식별자. |

## 예제

다음 코드는 SharpenSmartFilter의 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "sharpen_source.psd";
string outputPsd = "sharpen_output.psd";
string outputPng = "sharpen_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFile))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // 스마트 필터 편집
    SharpenSmartFilter sharpen = (SharpenSmartFilter)smartObj.SmartFilters.Filters[0];

    // 필터 값 확인
    AssertAreEqual(BlendMode.Normal, sharpen.BlendMode);
    AssertAreEqual(100d, sharpen.Opacity);
    AssertAreEqual(true, sharpen.IsEnabled);

    // 필터 값 업데이트
    sharpen.BlendMode = BlendMode.Divide;
    sharpen.Opacity = 75;
    sharpen.IsEnabled = false;

    // 새 필터 항목 추가
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new SharpenSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // 변경 사항 적용
    smartObj.SmartFilters.UpdateResourceValues();
    smartObj.UpdateModifiedContent();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### 또 보기

* class [SmartFilter](../smartfilter/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


