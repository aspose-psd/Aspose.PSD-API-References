---
title: Layer.IsVisible
second_title: .NET API 참조용 Aspose.PSD
description: Layer 재산. 레이어가 보이는지 나타내는 값을 가져오거나 설정합니다
type: docs
weight: 170
url: /ko/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
## Layer.IsVisible property

레이어가 보이는지 나타내는 값을 가져오거나 설정합니다

```csharp
public bool IsVisible { get; set; }
```

### 자산 가치

`진실` 이 인스턴스가 표시되면; 그렇지 않으면,`거짓` .

### 예

다음 예는 Aspose.PSD에서 LayerGroup 가시성을 변경하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// 레이어 이름을 변경하고 저장
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // 그룹 내부의 모든 항목을 끕니다.
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### 또한보십시오

* class [Layer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 집회 [Aspose.PSD](../../../)


