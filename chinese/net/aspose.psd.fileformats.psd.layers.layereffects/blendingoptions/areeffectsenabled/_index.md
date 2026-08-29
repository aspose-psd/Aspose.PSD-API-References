---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Aspose.PSD for .NET API 参考"
description: "BlendingOptions 属性。获取或设置所有图层效果的可见性"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

获取或设置所有图层效果的可见性。

```csharp
public bool AreEffectsEnabled { get; set; }
```

## 示例

演示如何使用 AreEffectsEnabled 属性启用或禁用图层效果。

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

### 另请参阅

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


