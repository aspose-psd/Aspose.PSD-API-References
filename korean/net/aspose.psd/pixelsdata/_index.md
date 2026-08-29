---
title: "클래스 PixelsData"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.PixelsData 클래스. 이미지 픽셀 데이터와 그 경계를 저장하는 클래스"
type: docs
weight: 5740
url: /ko/net/aspose.psd/pixelsdata/
---
{{< psd/tize >}}
## PixelsData class

이미지 픽셀 데이터와 그 경계를 저장하는 클래스입니다.

```csharp
public sealed class PixelsData : ICloneable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PixelsData](pixelsdata/#constructor)() | `PixelsData` 클래스의 새 인스턴스를 초기화합니다. |
| [PixelsData](pixelsdata/#constructor_1)(int[], Rectangle) | `PixelsData` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds/) { get; set; } | 픽셀 데이터의 경계를 가져오거나 설정합니다. |
| [Pixels](../../aspose.psd/pixelsdata/pixels/) { get; set; } | 픽셀 데이터를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Clone](../../aspose.psd/pixelsdata/clone/)() | 인스턴스의 전체 복사본을 생성합니다. |

## 예제

다음 코드는 사용자 지정 렌더러를 가진 커스텀 스마트 필터를 만드는 방법을 보여줍니다.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // 지원되지 않는 'Crystallize' 스마트 필터를 입력 배열에 초기화합니다.
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // 'Crystallize' 스마트 필터 ID.
        int id = 1131574132;

        for (int i = 0; i < smartFilters.Length; i++)
        {
            var smartFilter = smartFilters[i];
            if (smartFilter is UnknownSmartFilter && smartFilter.FilterId == id)
            {
                var customSmartFilterInstance = new CustomSmartFilterWithRenderer();
                customSmartFilterInstance.SourceDescriptor.Structures = smartFilter.SourceDescriptor.Structures;
                smartFilters[i] = customSmartFilterInstance;
            }
        }

        return smartFilters;
    }

    using (var image = (PsdImage) Image.Load(sourceFile))
    {
        SmartObjectLayer smartLayer = (SmartObjectLayer) image.Layers[1];
        Layer maskLayer = image.Layers[2];
        Layer regularLayer = image.Layers[3];

        smartLayer.SmartFilters.Filters = InitUnknownSmartFilters(smartLayer.SmartFilters.Filters);
        var smartFilter = smartLayer.SmartFilters.Filters[0];

        // SmartObject에 필터 적용
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // 레이어 마스크에 필터 적용
        smartFilter.ApplyToMask(maskLayer);

        //레이어에 필터 적용
        smartFilter.Apply(regularLayer);

        image.Save(outputPsd);
        image.Save(outputPng, new PngOptions());
    }
}

public sealed class CustomSmartFilterWithRenderer : SmartFilter, ISmartFilterRenderer
{
    public override string Name
    {
        get { return "Custom 'Crystallize' smart filter\0"; }
    }

    public override int FilterId
    {
        // 'Crystallize' 스마트 필터 ID.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // 필터 구조 가져오기
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // Crystallize Size 값 가져오기
        var valueStructure = (IntegerStructure) filterDescriptor.Structures[0];

        for (int i = 0; i < pixelsData.Pixels.Length; i++)
        {
            if (i % valueStructure.Value == 0)
            {
                pixelsData.Pixels[i] = 0;
            }
        }

        return pixelsData;
    }
}
```

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


