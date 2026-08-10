---
title: "Kelas XmpResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.Resources.XmpResource. Mewakili sumber daya metadata XMP"
type: docs
weight: 4460
url: /id/net/aspose.psd.fileformats.psd.resources/xmpresource/
---
{{< psd/tize >}}
## XmpResource class

Mewakili sumber daya metadata XMP.

```csharp
public sealed class XmpResource : ResourceBlock
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XmpResource](xmpresource/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/xmpresource/datasize/) { get; } | Mendapatkan ukuran data sumber daya dalam byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/xmpresource/minimalversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Mendapatkan atau mengatur nama sumber daya. String Pascal, dipadding agar ukuran genap (nama null terdiri dari dua byte 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Mendapatkan tanda tangan sumber daya. Harus selalu '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Mendapatkan ukuran blok sumber daya dalam byte termasuk datanya. |
| [XmpData](../../aspose.psd.fileformats.psd.resources/xmpresource/xmpdata/) { get; set; } | Dapatkan atau atur kontainer data XMP |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Menyimpan blok sumber daya ke aliran yang ditentukan. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Memvalidasi nilai-nilai sumber daya. |

### Lihat Juga

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


