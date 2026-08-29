---
title: "Layer.DisplayName"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Layer 속성. 레이어의 표시 이름을 가져오거나 설정합니다"
type: docs
weight: 110
url: /ko/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
{{< psd/tize >}}
## Layer.DisplayName property

레이어의 표시 이름을 가져오거나 설정합니다.

```csharp
public string DisplayName { get; set; }
```

### Property Value

레이어의 표시 이름입니다.

## 예제

다음 예제는 DisplayName 값을 설정하는 기능을 보여주며, 레이어 이름이 올바르게 표시되는 것을 확인할 수 있습니다.

```csharp
[C#]

// 레이어 이름을 변경하고 저장합니다
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // DisplayName 속성에 새 값을 설정합니다
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### 또 보기

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


