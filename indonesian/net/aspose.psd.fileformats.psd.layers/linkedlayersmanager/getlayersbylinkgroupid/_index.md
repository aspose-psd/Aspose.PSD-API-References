---
title: "LinkedLayersManager.GetLayersByLinkGroupId"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode LinkedLayersManager. Mendapatkan lapisan berdasarkan id grup tautan"
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/
---
{{< psd/tize >}}
## LinkedLayersManager.GetLayersByLinkGroupId method

Mendapatkan lapisan berdasarkan ID grup tautan.

```csharp
public Layer[] GetLayersByLinkGroupId(short linkGroupId)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| linkGroupId | Int16 | Id grup tautan. |

### Nilai Kembalian

Array lapisan.

## Contoh

Contoh berikut menunjukkan cara Anda dapat memanipulasi Linked Layers di Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Muat gambar yang ada ke dalam instance kelas PsdImage
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // tautkan semua lapisan dalam satu grup tertaut
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // mendapatkan id untuk satu lapisan
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // mendapatkan semua lapisan tertaut berdasarkan ID grup tautan.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // lepaskan tautan setiap lapisan dari grup
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // mengembalikan NULL untuk ID grup tautan yang tidak memiliki lapisan dalam grup.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Lihat Juga

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


