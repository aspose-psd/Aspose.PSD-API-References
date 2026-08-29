---
title: "Layer.BlendClippedElements"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Layer 속성. 클리핑된 요소의 블렌딩을 가져오거나 설정합니다"
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

클리핑된 요소의 블렌딩을 가져오거나 설정합니다.

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

클리핑된 요소의 블렌딩.

## 예제

다음 코드는 BlendClippedElements 속성 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "example_source.psd";
string outputPsd = "example_output.psd";
string outputPng = "example_output.png";

using (var image = (PsdImage)Image.Load(sourceFile))
{
    image.Layers[1].BlendClippedElements = false;
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### 또 보기

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


