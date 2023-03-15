---
title: LinkedLayersManager.GetLayersByLinkGroupId
second_title: .NET API 참조용 Aspose.PSD
description: LinkedLayersManager 방법. 링크 그룹 ID로 레이어를 가져옵니다.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/
---
## LinkedLayersManager.GetLayersByLinkGroupId method

링크 그룹 ID로 레이어를 가져옵니다.

```csharp
public Layer[] GetLayersByLinkGroupId(short linkGroupId)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| linkGroupId | Int16 | 링크 그룹 ID입니다. |

### 반환 값

레이어 배열입니다.

### 예

다음 예제는 Aspose.PSD에서 연결된 레이어를 조작하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // 하나의 연결된 그룹에 있는 모든 레이어를 연결합니다.
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // 하나의 레이어에 대한 ID를 얻습니다.
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // 링크 그룹 ID로 연결된 모든 레이어를 가져옵니다.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // 그룹에서 각 레이어 연결 해제
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // 그룹에 레이어가 없는 링크 그룹 ID에 대해 NULL을 검색합니다.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### 또한보십시오

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* 집회 [Aspose.PSD](../../../)


