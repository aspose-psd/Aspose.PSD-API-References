---
title: FilterEffectMaskData.GUID
second_title: .NET API 참조용 Aspose.PSD
description: FilterEffectMaskData 재산. GUID를 가져옵니다.
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/guid/
---
## FilterEffectMaskData.GUID property

GUID를 가져옵니다.

```csharp
public string GUID { get; }
```

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

* class [FilterEffectMaskData](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* 집회 [Aspose.PSD](../../../)


