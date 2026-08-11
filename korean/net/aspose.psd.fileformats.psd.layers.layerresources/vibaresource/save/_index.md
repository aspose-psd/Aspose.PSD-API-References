---
title: "VibAResource.Save"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "VibAResource 메서드. 지정된 스트림 컨테이너에 리소스를 저장합니다"
type: docs
weight: 50
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
{{< psd/tize >}}
## VibAResource.Save method

리소스를 지정된 스트림 컨테이너에 저장합니다.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | StreamContainer | 저장할 스트림 컨테이너입니다. |
| psdVersion | Int32 | PSD 버전입니다. |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


