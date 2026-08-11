---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "BlendingOptions 속성. 모든 레이어 효과의 가시성을 가져오거나 설정합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

모든 레이어 효과의 가시성을 가져오거나 설정합니다.

```csharp
public bool AreEffectsEnabled { get; set; }
```

## 예제

AreEffectsEnabled 속성을 사용하여 레이어 효과를 활성화하거나 비활성화하는 방법을 보여줍니다

```csharp
[C#]

string srcFile = "2485.psd";
string outputOnFile = "on_2485.png";
string outputOffFile = "off_2485.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Save(outputOnFile);

    psdImage.Layers[1].BlendingOptions.AreEffectsEnabled = false;

    psdImage.Save(outputOffFile);
}
```

### 또 보기

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


