---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti BlendingOptions. Mendapatkan atau mengatur visibilitas semua efek lapisan"
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

Mendapatkan atau mengatur visibilitas semua efek lapisan.

```csharp
public bool AreEffectsEnabled { get; set; }
```

## Contoh

Menunjukkan cara mengaktifkan atau menonaktifkan efek lapisan menggunakan properti AreEffectsEnabled.

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

### Lihat Juga

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


