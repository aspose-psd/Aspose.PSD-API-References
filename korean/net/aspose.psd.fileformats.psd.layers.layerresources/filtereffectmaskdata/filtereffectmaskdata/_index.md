---
title: FilterEffectMaskData.FilterEffectMaskData
second_title: .NET API 참조용 Aspose.PSD
description: FilterEffectMaskData 건설자. 의 새 인스턴스를 초기화합니다.FilterEffectMaskData 클래스.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
## FilterEffectMaskData constructor

의 새 인스턴스를 초기화합니다.[`FilterEffectMaskData`](../) 클래스.

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| guid | String | 리소스 가이드입니다. |
| rectangle | Rectangle | 채널 직사각형. |
| pixelsDepth | Int32 | 픽셀 깊이입니다. |
| maxChannels | Int32 | 최대 채널 값입니다. |
| channels | ChannelInformation[] | 채널. |
| userMask | ChannelInformation | 사용자 마스크입니다. |
| maskRectangle | Rectangle | 시트 마스크 사각형. |
| sheetMask | ChannelInformation | 시트 마스크입니다. |

### 예

이 예제는 FXidResource 리소스의 속성을 가져오고 설정하는 방법을 보여줍니다.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
int maskLength = 369;

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

using (var psdImage = (PsdImage)Image.Load(inputFilePath))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }

    psdImage.Save(output);
}

// 저장 후 확인
using (var psdImage = (PsdImage)Image.Load(output))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }
}
```

### 또한보십시오

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* 집회 [Aspose.PSD](../../../)


