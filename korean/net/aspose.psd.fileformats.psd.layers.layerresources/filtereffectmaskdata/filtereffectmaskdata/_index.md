---
title: "FilterEffectMaskData.FilterEffectMaskData"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "FilterEffectMaskData 생성자. FilterEffectMaskData 클래스의 새 인스턴스를 초기화합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData constructor

새 인스턴스를 초기화합니다 [`FilterEffectMaskData`](../) 클래스의.

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| guid | String | 리소스 GUID. |
| 사각형 | Rectangle | 채널 사각형. |
| pixelsDepth | Int32 | 픽셀 깊이. |
| maxChannels | Int32 | 최대 채널 값. |
| channels | ChannelInformation[] | 채널들. |
| userMask | ChannelInformation | 사용자 마스크. |
| maskRectangle | Rectangle | 시트 마스크 사각형. |
| sheetMask | ChannelInformation | 시트 마스크. |

## 예제

이 예제는 FXidResource 리소스의 속성을 가져오고 설정하는 방법을 보여줍니다.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
long maskLength = 369;

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

### 또 보기

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


