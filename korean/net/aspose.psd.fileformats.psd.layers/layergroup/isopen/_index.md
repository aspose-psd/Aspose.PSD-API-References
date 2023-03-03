---
title: LayerGroup.IsOpen
second_title: .NET API 참조용 Aspose.PSD
description: LayerGroup 재산. 가져오거나 설정하면 폴더가 열림 로 설정된 경우진실 시작 시 그룹이 열린 상태가 되고 그렇지 않으면 최소화된 상태가 됩니다.
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
## LayerGroup.IsOpen property

가져오거나 설정하면 폴더가 열림 로 설정된 경우`진실` 시작 시 그룹이 열린 상태가 되고 그렇지 않으면 최소화된 상태가 됩니다.

```csharp
public bool IsOpen { get; set; }
```

### 예

다음 코드는 IsOpen 속성을 사용하여 LayerGroup(폴더)을 열고 닫는 방법을 보여줍니다.

```csharp
[C#]

// 런타임에 IsOpen 속성을 읽고 쓰는 예제.
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

### 또한보십시오

* class [LayerGroup](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* 집회 [Aspose.PSD](../../../)


