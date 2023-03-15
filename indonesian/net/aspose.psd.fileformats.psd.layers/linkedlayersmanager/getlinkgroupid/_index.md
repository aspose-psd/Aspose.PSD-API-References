---
title: LinkedLayersManager.GetLinkGroupId
second_title: Aspose.PSD untuk Referensi .NET API
description: LinkedLayersManager metode. Mendapat ID grup tautan yang terkait dengan lapisan.
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/
---
## LinkedLayersManager.GetLinkGroupId method

Mendapat ID grup tautan yang terkait dengan lapisan.

```csharp
public short GetLinkGroupId(Layer layer)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| layer | Layer | Lapisan. |

### Nilai Pengembalian

ID grup tautan.

### Contoh

Contoh berikut menunjukkan bagaimana Anda dapat memanipulasi Linked Layers di Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Memuat gambar yang ada ke dalam instance kelas PsdImage
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // tautkan semua layer dalam satu grup tertaut
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // mendapatkan id untuk satu lapisan
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // dapatkan semua lapisan tertaut dengan id grup tautan.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // batalkan tautan setiap lapisan dari grup
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // mengambil NULL untuk ID grup tautan yang tidak memiliki lapisan dalam grup.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Lihat juga

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* perakitan [Aspose.PSD](../../../)


