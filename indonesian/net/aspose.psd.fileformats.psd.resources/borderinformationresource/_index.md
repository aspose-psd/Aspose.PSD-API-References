---
title: Class BorderInformationResource
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Resources.BorderInformationResource kelas. Sumber daya dengan informasi batas pengaturan cetak gambar.
type: docs
weight: 3650
url: /id/net/aspose.psd.fileformats.psd.resources/borderinformationresource/
---
## BorderInformationResource class

Sumber daya dengan informasi batas pengaturan cetak gambar.

```csharp
public sealed class BorderInformationResource : ResourceBlock
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [BorderInformationResource](borderinformationresource/)() | Konstruktor default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/) { get; } | Mendapatkan ukuran data sumber daya dalam byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Mendapat atau menyetel pengidentifikasi unik untuk sumber daya. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/) { get; } | Mendapatkan versi PSD minimal yang diperlukan. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Mendapat atau menetapkan nama sumber daya. String Pascal, diisi untuk membuat ukurannya rata (nama null terdiri dari dua byte 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Mendapat tanda tangan sumber daya. Harus selalu '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Mendapat ukuran blok sumber daya dalam byte termasuk datanya. |
| [Unit](../../aspose.psd.fileformats.psd.resources/borderinformationresource/unit/) { get; set; } | Mendapat atau mengatur unit perbatasan. |
| [Width](../../aspose.psd.fileformats.psd.resources/borderinformationresource/width/) { get; set; } | Mendapat atau mengatur lebar perbatasan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Menyimpan blok sumber daya ke aliran yang ditentukan. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Memvalidasi nilai sumber daya. |

### Contoh

Contoh berikut menunjukkan dukungan sumber daya BorderInformationResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // perbarui BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Lihat juga

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* perakitan [Aspose.PSD](../../)


