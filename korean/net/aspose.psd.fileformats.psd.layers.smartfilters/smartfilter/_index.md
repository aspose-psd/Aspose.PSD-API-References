---
title: "클래스 SmartFilter"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SmartFilter 클래스. 스마트 필터의 기본 로직을 처리하는 클래스"
type: docs
weight: 3880
url: /ko/net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/
---
{{< psd/tize >}}
## SmartFilter class

스마트 필터의 기본 로직을 처리하는 클래스입니다.

```csharp
public abstract class SmartFilter : ICloneable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SmartFilter](smartfilter/)() | `SmartFilter` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | 블렌딩 모드를 가져오거나 설정합니다. |
| abstract [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/filterid/) { get; } | 스마트 필터 유형 식별자를 가져옵니다. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | 스마트 필터의 활성화 상태를 가져오거나 설정합니다. |
| abstract [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/name/) { get; } | 스마트 필터 이름을 가져옵니다. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | 스마트 필터의 불투명도 값을 가져오거나 설정합니다. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | 스마트 필터 데이터가 포함된 소스 디스크립터 구조체. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | 현재 필터를 입력 [`RasterImage`](../../aspose.psd/rasterimage/) 이미지에 적용합니다. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | 현재 필터를 입력 [`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) 마스크 데이터에 적용합니다. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | 해당 유형의 현재 인스턴스를 멤버별로 복제합니다. |

## 예제

이 예제는 스마트 필터 인터페이스의 지원을 보여줍니다.

```csharp
[C#]

string sourceFilte = "r2_SmartFilters.psd";
string outputPsd = "out_r2_SmartFilters.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFilte))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // 스마트 필터 편집
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // 필터 값 확인
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // 필터 값 업데이트
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // 새 필터 항목 추가
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // 변경 사항 적용
    smartObj.SmartFilters.UpdateResourceValues();

    // 필터 적용
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // 필터 값 확인
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


