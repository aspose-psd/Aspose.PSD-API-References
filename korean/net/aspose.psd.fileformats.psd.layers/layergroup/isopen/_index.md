---
title: "LayerGroup.IsOpen"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "LayerGroup 속성. 폴더가 열려 있는지 여부를 가져오거나 설정합니다. true로 설정하면 시작 시 그룹이 열린 상태가 되고, 그렇지 않으면 최소화된 상태가 됩니다."
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
{{< psd/tize >}}
## LayerGroup.IsOpen property

폴더가 열려 있는지 여부를 가져오거나 설정합니다. `true` 로 설정하면 시작 시 그룹이 열려 있는 상태가 되고, 그렇지 않으면 최소화된 상태가 됩니다.

```csharp
public bool IsOpen { get; set; }
```

## 예제

다음 코드는 IsOpen 속성을 사용하여 LayerGroup(폴더)를 열고 닫는 방법을 보여줍니다.

```csharp
[C#]

// 런타임에서 IsOpen 속성을 읽고 쓰는 예제입니다.
string sourceFileName = "LayerGroupOpenClose.psd";
string outputFileName = "OutputLayerGroupOpenClose.psd";

using (var image = (PsdImage) Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        if (layer is LayerGroup && layer.Name == "Group 1")
        {
            bool isOpenedGroup1 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup1;
        }

        if (layer is LayerGroup && layer.Name == "Group 2")
        {
            bool isOpenedGroup2 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup2;
        }
    }

    image.Save(outputFileName);
}
```

### 또 보기

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


