---
title: Layer.DisplayName
second_title: .NET API 참조용 Aspose.PSD
description: Layer 재산. 레이어의 표시 이름을 가져오거나 설정합니다.
type: docs
weight: 100
url: /ko/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

레이어의 표시 이름을 가져오거나 설정합니다.

```csharp
public string DisplayName { get; set; }
```

### 자산 가치

레이어의 표시 이름입니다.

### 예

다음 예제는 레이어 이름이 올바르게 표시되는 DisplayName 값을 설정하는 기능을 보여줍니다.

```csharp
[C#]

// 레이어 이름을 변경하고 저장
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // DisplayName 속성에 새 값을 설정합니다.
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### 또한보십시오

* class [Layer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 집회 [Aspose.PSD](../../../)


