---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "BlendingOptions-Eigenschaft. Gibt die Sichtbarkeit aller Ebeneneffekte zurück oder legt sie fest."
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

Liest oder setzt die Sichtbarkeit aller Ebeneneffekte.

```csharp
public bool AreEffectsEnabled { get; set; }
```

## Beispiele

Demonstriert, wie man Ebeneneffekte mit der Eigenschaft AreEffectsEnabled aktiviert oder deaktiviert.

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

### Siehe auch

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


