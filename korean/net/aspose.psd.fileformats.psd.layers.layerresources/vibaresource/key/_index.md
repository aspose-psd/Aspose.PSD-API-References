---
title: VibAResource.Key
second_title: .NET API 참조용 Aspose.PSD
description: VibAResource 재산. 레이어 리소스 키를 가져옵니다.
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/key/
---
## VibAResource.Key property

레이어 리소스 키를 가져옵니다.

```csharp
public override int Key { get; }
```

### 예

다음 코드 예제는 VibAResource 리소스의 지원을 보여줍니다.

```csharp
[C#]

// 런타임 시 Vibration Resource 읽기 및 쓰기 지원의 예.
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

### 또한보십시오

* class [VibAResource](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* 집회 [Aspose.PSD](../../../)


