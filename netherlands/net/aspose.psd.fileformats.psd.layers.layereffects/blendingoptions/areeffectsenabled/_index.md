---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "BlendingOptions-eigenschap. Haalt op of stelt de zichtbaarheid van alle laageffecten in"
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

Haalt op of stelt de zichtbaarheid van alle laageffecten in.

```csharp
public bool AreEffectsEnabled { get; set; }
```

## Voorbeelden

Toont hoe laageffecten in of uit te schakelen met de AreEffectsEnabled-eigenschap.

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

### Zie ook

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


