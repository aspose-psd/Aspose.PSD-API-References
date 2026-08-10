---
title: "Kelas IfxsResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IfxsResource class. Sumber daya grup Ifxs untuk efek layer"
type: docs
weight: 2840
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---
{{< psd/tize >}}
## IfxsResource class

Sumber daya Ifxs (sumber daya efek lapisan grup)

```csharp
public sealed class IfxsResource : BaseFxResource
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [IfxsResource](ifxsresource/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | Mendapatkan versi deskriptor. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Mendapatkan kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Mendapatkan tanda tangan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan String yang mewakili instance ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/) | Kunci info alat tipe. |

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

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


