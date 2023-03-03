---
title: ISmartFilterRenderer.Render
second_title: .NET API 참조용 Aspose.PSD
description: ISmartFilterRenderer 방법. 픽셀 데이터에 현재 스마트 필터를 렌더링합니다.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/render/
---
## ISmartFilterRenderer.Render method

픽셀 데이터에 현재 스마트 필터를 렌더링합니다.

```csharp
public PixelsData Render(PixelsData pixelsData)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pixelsData | PixelsData | 픽셀 데이터입니다. |

### 반환 값

처리된 픽셀 데이터를 반환합니다.

### 예

다음 코드는 사용자 지정 렌더러가 있는 사용자 지정 스마트 필터를 만드는 방법을 보여줍니다.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // 입력 배열에서 지원되지 않는 'Crystallize' 스마트 필터를 초기화합니다.
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // 'Crystallize' 스마트 필터 ID입니다.
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
        // 'Crystallize' 스마트 필터 ID입니다.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // 필터 구조 얻기
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // Crystallize Size의 값을 얻습니다.
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

### 또한보십시오

* class [PixelsData](../../../aspose.psd/pixelsdata/)
* interface [ISmartFilterRenderer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering](../../ismartfilterrenderer/)
* 집회 [Aspose.PSD](../../../)


