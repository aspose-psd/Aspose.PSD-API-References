---
title: SectionDividerLayer.IsVisibleInGroup
second_title: .NET API 참조용 Aspose.PSD
description: SectionDividerLayer 재산. 이 인스턴스가 그룹에 있는지 여부를 나타내는 값을 가져옵니다레이어가 그룹에 없으면 루트 그룹을 의미합니다.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
## SectionDividerLayer.IsVisibleInGroup property

이 인스턴스가 그룹에 있는지 여부를 나타내는 값을 가져옵니다(레이어가 그룹에 없으면 루트 그룹을 의미합니다).

```csharp
public override bool IsVisibleInGroup { get; }
```

### 자산 가치

`진실` 이 인스턴스가 그룹에서 보이는 경우; 그렇지 않으면,`거짓` .

### 예

다음 코드는 SectionDividerLayer 레이어와 관련된 LayerGroup을 가져오는 방법을 보여줍니다.

```csharp
[C#]

// 다음 코드는 SectionDividerLayer 레이어와 관련 LayerGroup을 가져오는 방법을 보여줍니다.

// 레이어 계층
// [0]: '</레이어 그룹>' 그룹 1의 SectionDividerLayer
// [1]: '레이어 1' 일반 레이어
// [2]: '</레이어 그룹>' 그룹 2의 SectionDividerLayer
// [3]: '</레이어 그룹>' 그룹 3의 SectionDividerLayer
// [4]: '그룹 3' GroupLayer
// [5]: '그룹 2' GroupLayer
// [6]: '그룹 1' GroupLayer

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // 레이어 계층 생성
    // LayerGroup '그룹 1' 추가
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // 일반 레이어 추가
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // LayerGroup '그룹 2' 추가
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // LayerGroup '그룹 3' 추가
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // SectionDividerLayer의
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // SectionDividerLayer.GetRelatedLayerGroup() 메서드를 사용하여 관련 LayerGroup 인스턴스를 가져옵니다.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // 같은 레이어 그룹
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // 같은 레이어 그룹
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // 같은 레이어 그룹

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // '그룹 1'은 5개의 레이어를 포함합니다.
}
```

### 또한보십시오

* class [SectionDividerLayer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../sectiondividerlayer/)
* 집회 [Aspose.PSD](../../../)


