---
title: Class BackgroundColorResource
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Resources.BackgroundColorResource kelas. Sumber daya dengan informasi batas pengaturan cetak gambar.
type: docs
weight: 3640
url: /id/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/
---
## BackgroundColorResource class

Sumber daya dengan informasi batas pengaturan cetak gambar.

```csharp
public sealed class BackgroundColorResource : ResourceBlock
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [BackgroundColorResource](backgroundcolorresource/)() | Konstruktor default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/) { get; set; } | Mendapat atau mengatur warna latar belakang. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/) { get; } | Mendapatkan ukuran data sumber daya dalam byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Mendapat atau menyetel pengidentifikasi unik untuk sumber daya. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/) { get; } | Mendapatkan versi PSD minimal yang diperlukan. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Mendapat atau menetapkan nama sumber daya. String Pascal, diisi untuk membuat ukurannya rata (nama null terdiri dari dua byte 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Mendapat tanda tangan sumber daya. Harus selalu '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Mendapat ukuran blok sumber daya dalam byte termasuk datanya. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Menyimpan blok sumber daya ke aliran yang ditentukan. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Memvalidasi nilai sumber daya. |

### Contoh

Contoh berikut menunjukkan dukungan sumber daya BackgroundColorResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // perbarui BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Lihat juga

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* perakitan [Aspose.PSD](../../)


