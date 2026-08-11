---
title: "VibAResource.VibAResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "VibAResource 생성자. VibAResource 클래스의 새 인스턴스를 초기화합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibaresource/
---
{{< psd/tize >}}
## VibAResource constructor

[`VibAResource`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public VibAResource()
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


