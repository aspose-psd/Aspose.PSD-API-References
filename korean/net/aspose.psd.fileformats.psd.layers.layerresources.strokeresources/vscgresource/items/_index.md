---
title: "VscgResource.Items"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "VscgResource 속성. 구조 항목 배열을 가져오거나 설정합니다. 경고: Items 배열 값은 Items 내부 구조에 저장된 채우기 설정 유형을 결정하는 KeyForData 속성과 일치해야 합니다."
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/items/
---
{{< psd/tize >}}
## VscgResource.Items property

구조 항목 배열을 가져오거나 설정합니다. **Warning:** `Items` 배열 값은 `KeyForData` 속성과 일치해야 하며, 이는 `Items` 내부 구조에 저장된 채우기 설정 유형을 결정합니다.

```csharp
public OSTypeStructure[] Items { get; }
```

### Property Value

[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 항목의 배열입니다.

## 예제

다음 코드는 VscgResource 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "StrokeInternalFill_src.psd";
string outputFile = "StrokeInternalFill_res.psd";

void AreEqual(double expected, double current, double tolerance = 0.1)
{
    if (Math.Abs(expected - current) > tolerance)
    {
        throw new Exception(
            $"Values is not equal.\nExpected:{expected}\nResult:{current}\nDifference:{expected - current}");
    }
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(89.8, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(219.6, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(34.2, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);

    ((DoubleStructure)rgbColorStructure.Structures[0]).Value = 255d; // Red
    ((DoubleStructure)rgbColorStructure.Structures[1]).Value = 0d; // Green
    ((DoubleStructure)rgbColorStructure.Structures[2]).Value = 0d; // Blue

    image.Save(outputFile);
}

// 변경 사항 확인 중
using (PsdImage image = (PsdImage)Image.Load(outputFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(255, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);
}
```

### 또 보기

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* class [VscgResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


