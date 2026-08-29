---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Aspose.PSD för .NET API‑referens"
description: "BlendingOptions-egenskap. Hämtar eller anger synligheten för alla lagerseffekter"
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

Hämtar eller anger synligheten för alla lager-effekter.

```csharp
public bool AreEffectsEnabled { get; set; }
```

## Exempel

Visar hur man aktiverar eller inaktiverar lagerseffekter med AreEffectsEnabled-egenskapen.

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

### Se även

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


