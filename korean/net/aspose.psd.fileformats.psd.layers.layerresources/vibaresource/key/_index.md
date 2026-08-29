---
title: "VibAResource.Key"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "VibAResource 속성. 레이어 리소스 키를 가져옵니다"
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/key/
---
{{< psd/tize >}}
## VibAResource.Key property

레이어 리소스 키를 가져옵니다.

```csharp
public override int Key { get; }
```

## 예제

다음 코드 예제는 VibAResource 리소스의 지원을 보여줍니다.

```csharp
[C#]

// 런타임에서 Vibration 리소스를 읽고 쓰는 지원 예시입니다.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### 또 보기

* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


