---
title: "SharpenSmartFilter.SharpenSmartFilter"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "SharpenSmartFilter 생성자. SharpenSmartFilter 클래스의 새 인스턴스를 초기화합니다."
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter() {#constructor}

`[`SharpenSmartFilter`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public SharpenSmartFilter()
```

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

* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)

---

## SharpenSmartFilter(DescriptorStructure) {#constructor_1}

`[`SharpenSmartFilter`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public SharpenSmartFilter(DescriptorStructure sourceDescriptor)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceDescriptor | DescriptorStructure | 스마트 필터 정보가 포함된 디스크립터 구조입니다. |

### 또 보기

* class [DescriptorStructure](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/)
* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)


