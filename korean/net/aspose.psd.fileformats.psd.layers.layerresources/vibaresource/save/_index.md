---
title: VibAResource.Save
second_title: .NET API 참조용 Aspose.PSD
description: VibAResource 방법. 리소스를 지정된 스트림 컨테이너에 저장합니다.
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
## VibAResource.Save method

리소스를 지정된 스트림 컨테이너에 저장합니다.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| streamContainer | StreamContainer | 저장할 스트림 컨테이너입니다. |
| psdVersion | Int32 | PSD 버전입니다. |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* 집회 [Aspose.PSD](../../../)


