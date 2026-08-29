---
title: "SectionDividerLayer.GetRelatedLayerGroup"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "SectionDividerLayer 메서드. 이 SectionDividerLayer 인스턴스와 관련된 LayerGroup을 가져옵니다."
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/getrelatedlayergroup/
---
{{< psd/tize >}}
## SectionDividerLayer.GetRelatedLayerGroup method

이 [`SectionDividerLayer`](../) 인스턴스와 관련된 [`LayerGroup`](../../layergroup/)을 가져옵니다.

```csharp
public LayerGroup GetRelatedLayerGroup()
```

### 반환 값

[`LayerGroup`](../../layergroup/) 인스턴스입니다.

## 예제

다음 코드는 SectionDividerLayer 레이어와 해당 LayerGroup을 가져오는 방법을 보여줍니다.

```csharp
[C#]

// 다음 코드는 SectionDividerLayer 레이어와 해당 LayerGroup을 가져오는 방법을 보여줍니다.

// 레이어 계층 구조
//    [0]: '</Layer group>' Group 1용 SectionDividerLayer
//    [1]: 'Layer 1' 일반 레이어
//    [2]: '</Layer group>' Group 2용 SectionDividerLayer
//    [3]: '</Layer group>' Group 3용 SectionDividerLayer
//    [4]: 'Group 3' GroupLayer
//    [5]: 'Group 2' GroupLayer
//    [6]: 'Group 1' GroupLayer

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // 레이어 계층 구조 만들기
    // LayerGroup 'Group 1' 추가
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // 일반 레이어 추가
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // LayerGroup 'Group 2' 추가
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // LayerGroup 'Group 3' 추가
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // SectionDividerLayer를 가져옵니다
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // SectionDividerLayer.GetRelatedLayerGroup() 메서드를 사용하여 관련 LayerGroup 인스턴스를 가져옵니다.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // the same LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' contains 5 layers
}
```

### 또 보기

* class [LayerGroup](../../layergroup/)
* class [SectionDividerLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


