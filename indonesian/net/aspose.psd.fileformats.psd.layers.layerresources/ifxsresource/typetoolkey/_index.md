---
title: "IfxsResource.TypeToolKey"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "IfxsResource bidang. Kunci info alat tipe"
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

Kunci info alat tipe.

```csharp
public const int TypeToolKey;
```

## Contoh

Kode berikut menunjukkan dukungan untuk IfxsResource.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // Contoh memiliki 2 lapisan grup dengan efek
    // Lapisan grup dengan satu efek
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Lapisan grup dengan banyak efek
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Dapatkan jumlah efek dan verifikasi kuantitasnya
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // Satu efek dalam lapisan grup berada di sumber daya 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Dua atau lebih efek dalam lapisan grup berada di sumber daya 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Tambahkan bayangan ketiga ke lapisan grup dengan beberapa efek
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### Lihat Juga

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


