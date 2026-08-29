---
title: "Layer.IsVisible"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Layer 속성. 레이어가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다."
type: docs
weight: 180
url: /ko/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

레이어가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다.

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true`이면 이 인스턴스가 표시됩니다; 그렇지 않으면 `false`.

## 예제

다음 예제는 Aspose.PSD에서 LayerGroup 가시성을 변경하는 방법을 보여줍니다

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// 레이어 이름을 변경하고 저장합니다
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // 그룹 내부의 모든 것을 끕니다
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### 또 보기

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


