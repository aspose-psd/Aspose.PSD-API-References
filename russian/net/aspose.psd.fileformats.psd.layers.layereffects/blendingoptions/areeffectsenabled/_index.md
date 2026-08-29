---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство BlendingOptions. Получает или задает видимость всех эффектов слоёв"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

Получает или задает видимость всех эффектов слоёв.

```csharp
public bool AreEffectsEnabled { get; set; }
```

## Примеры

Показывает, как включать или отключать эффекты слоёв с помощью свойства AreEffectsEnabled.

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

### См. также

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


