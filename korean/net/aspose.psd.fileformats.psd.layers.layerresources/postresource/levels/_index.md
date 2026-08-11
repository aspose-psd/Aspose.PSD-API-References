---
title: "PostResource.Levels"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PostResource 속성. 포스터라이즈 레이어의 레벨"
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/
---
{{< psd/tize >}}
## PostResource.Levels property

Posterize 레이어의 레벨.

```csharp
public short Levels { get; set; }
```

### 반환 값

Levels 정수 값

## 예제

다음 코드는 PostResource 조작 기능을 보여줍니다.

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];

    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is PostResource)
        {
            ((PostResource)resource).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### 또 보기

* class [PostResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


