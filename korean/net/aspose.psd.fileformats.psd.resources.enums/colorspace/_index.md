---
title: "Enum ColorSpace"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Resources.Enums.ColorSpace enum. 색상 공간 유형"
type: docs
weight: 4160
url: /ko/net/aspose.psd.fileformats.psd.resources.enums/colorspace/
---
{{< psd/tize >}}
## ColorSpace enumeration

색 공간 유형.

```csharp
public enum ColorSpace : ushort
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| RGB | `0` | RGB 색상 공간. |
| HSB | `1` | HSB 색상 공간. |
| CMYK | `2` | CMYK 색상 공간. |
| Lab | `7` | Lab 색상 공간. |
| GrayScale | `8` | GrayScale 색상 공간. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Resources.Enums](../../aspose.psd.fileformats.psd.resources.enums/)
* assembly [Aspose.PSD](../../)


