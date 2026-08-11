---
title: "LmskResource.Flag"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "LmskResource property. 플래그를 가져옵니다"
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/
---
{{< psd/tize >}}
## LmskResource.Flag property

플래그를 가져옵니다.

```csharp
public byte Flag { get; }
```

### Property Value

플래그.

## 예제

다음 코드는 16비트 이미지에서 LmskResource 속성을 변경하여 레이어 마스크 표시 옵션을 변경하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// 16비트 이미지를 로드합니다.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // LmskResource를 찾습니다.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // LmskResource 속성을 확인합니다.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // LmskResource 속성을 변경합니다.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // 이미지를 저장합니다.
    image.Save(outputPsd);
}
```

### 또 보기

* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


