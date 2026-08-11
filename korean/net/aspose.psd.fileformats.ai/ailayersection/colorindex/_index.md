---
title: "AiLayerSection.ColorIndex"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "AiLayerSection 속성. 색상의 인덱스를 가져오거나 설정합니다. 이 인자는 1에서 26 사이의 값을 가질 수 있습니다. 각 정수는 사용자 식별을 위해 레이어에 할당될 수 있는 색상을 나타냅니다"
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

색상의 인덱스를 가져오거나 설정합니다. 이 인수는 –1에서 26 사이의 값을 가질 수 있습니다. 각 정수는 사용자 식별을 위해 레이어에 할당될 수 있는 색상을 나타냅니다.

```csharp
public int ColorIndex { get; set; }
```

### Property Value

색상의 인덱스.

## 예제

다음 코드는 AiLayerSection에서 HasMultiLayerMasks 및 ColorIndex 속성 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "example.ai";
string outputFilePath = "example.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AssertAreEqual(image.Layers.Length, 2);
    AssertAreEqual(image.Layers[0].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[0].ColorIndex, -1);
    AssertAreEqual(image.Layers[1].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[1].ColorIndex, -1);

    image.Save(outputFilePath, new PngOptions());
}
```

### 또 보기

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


