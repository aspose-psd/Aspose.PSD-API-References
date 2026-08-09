---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété BlendingOptions. Obtient ou définit la visibilité de tous les effets de calque"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

Obtient ou définit la visibilité de tous les effets de calque.

```csharp
public bool AreEffectsEnabled { get; set; }
```

## Exemples

Démontre comment activer ou désactiver les effets de calque en utilisant la propriété AreEffectsEnabled.

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

### Voir aussi

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


