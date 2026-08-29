---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα BlendingOptions. Λαμβάνει ή ορίζει την ορατότητα όλων των εφέ στρώσεων"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

Λαμβάνει ή ορίζει την ορατότητα όλων των εφέ στρώσης.

```csharp
public bool AreEffectsEnabled { get; set; }
```

## Παραδείγματα

Δείχνει πώς να ενεργοποιήσετε ή να απενεργοποιήσετε τα εφέ στρώσεων χρησιμοποιώντας την ιδιότητα AreEffectsEnabled.

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

### Δείτε επίσης

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


