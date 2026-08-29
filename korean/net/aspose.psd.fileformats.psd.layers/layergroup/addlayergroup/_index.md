---
title: "LayerGroup.AddLayerGroup"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "LayerGroup 메서드. 레이어 그룹을 추가합니다."
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
{{< psd/tize >}}
## LayerGroup.AddLayerGroup method

레이어 그룹을 추가합니다.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| groupName | String | 그룹의 이름입니다. |
| index | Int32 | 삽입할 레이어 뒤의 인덱스입니다. |

### 반환 값

그룹 레이어 열기

## 예제

다음 예제는 LayerGroup을 다른 LayerGroup에 추가하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// 다음과 같이 레이어 계층 구조를 만듭니다:
// -그룹 1
// --레이어 1
// --그룹 2
// ---레이어 2
// ---레이어 3
// --레이어 4

var createOptions = new PsdOptions();
createOptions.Source = new FileCreateSource(sourceFileName, false);
createOptions.Palette = new PsdColorPalette(new Color[] { Color.Green });

using (var psdImage = (PsdImage)Image.Create(createOptions, 500, 500))
{
    LayerGroup group1 = psdImage.AddLayerGroup("Group 1", 0, false);

    Layer layer1 = new Layer(psdImage);
    layer1.Name = "Layer 1";
    group1.AddLayer(layer1);

    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);

    Layer layer2 = new Layer(psdImage);
    layer2.Name = "Layer 2";
    group2.AddLayer(layer2);

    Layer layer3 = new Layer(psdImage);
    layer3.Name = "Layer 3";
    group2.AddLayer(layer3);

    Layer layer4 = new Layer(psdImage);
    layer4.Name = "Layer 4";
    group1.AddLayer(layer4);

    psdImage.Save();
}
```

### 또 보기

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


