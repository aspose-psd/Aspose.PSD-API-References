---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà BlendingOptions. Ottiene o imposta la visibilità di tutti gli effetti di livello"
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

Ottiene o imposta la visibilità di tutti gli effetti di livello.

```csharp
public bool AreEffectsEnabled { get; set; }
```

## Esempi

Dimostra come abilitare o disabilitare gli effetti di livello usando la proprietà AreEffectsEnabled.

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

### Vedi anche

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


