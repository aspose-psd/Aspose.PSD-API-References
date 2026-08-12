---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad BlendingOptions. Obtiene o establece la visibilidad de todos los efectos de capa"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

Obtiene o establece la visibilidad de todos los efectos de capa.

```csharp
public bool AreEffectsEnabled { get; set; }
```

## Ejemplos

Demuestra cómo habilitar o deshabilitar los efectos de capa usando la propiedad AreEffectsEnabled.

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

### Ver también

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


