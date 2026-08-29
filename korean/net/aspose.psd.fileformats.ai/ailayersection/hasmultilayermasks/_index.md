---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "AiLayerSection 속성. 이 인스턴스에 멀티 레이어 마스크가 있는지 여부를 나타내는 값을 가져오거나 설정합니다"
type: docs
weight: 60
url: /ko/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

이 인스턴스에 다중 레이어 마스크가 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` 이 인스턴스에 멀티 레이어 마스크가 있는 경우; 그렇지 않으면 `false`.

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


