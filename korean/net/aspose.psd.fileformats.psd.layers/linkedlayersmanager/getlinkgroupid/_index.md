---
title: "LinkedLayersManager.GetLinkGroupId"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "LinkedLayersManager 메서드. 레이어와 연결된 링크 그룹 ID를 가져옵니다"
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/
---
{{< psd/tize >}}
## LinkedLayersManager.GetLinkGroupId method

레이어와 연결된 링크 그룹 ID를 가져옵니다.

```csharp
public short GetLinkGroupId(Layer layer)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 레이어 | 레이어 | 레이어. |

### 반환 값

링크 그룹 ID입니다.

## 예제

다음 예제는 Aspose.PSD에서 연결된 레이어를 조작하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // 모든 레이어를 하나의 연결 그룹으로 연결합니다.
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // 하나의 레이어에 대한 ID를 가져옵니다.
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // 링크 그룹 ID로 모든 연결된 레이어를 가져옵니다.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // 그룹에서 각 레이어의 연결을 해제합니다.
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // 그룹에 레이어가 없는 링크 그룹 ID에 대해 NULL을 반환합니다.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### 또 보기

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


