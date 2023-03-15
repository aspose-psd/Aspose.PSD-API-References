---
title: Class XmpResource
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Resources.XmpResource kelas. Mewakili sumber daya metadata XMP.
type: docs
weight: 3990
url: /id/net/aspose.psd.fileformats.psd.resources/xmpresource/
---
## XmpResource class

Mewakili sumber daya metadata XMP.

```csharp
public sealed class XmpResource : ResourceBlock
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XmpResource](xmpresource/)() | Konstruktor default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/xmpresource/datasize/) { get; } | Mendapatkan ukuran data sumber daya dalam byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Mendapat atau menyetel pengidentifikasi unik untuk sumber daya. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/xmpresource/minimalversion/) { get; } | Mendapat versi psd minimal yang diperlukan. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Mendapat atau menetapkan nama sumber daya. String Pascal, diisi untuk membuat ukurannya rata (nama null terdiri dari dua byte 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Mendapat tanda tangan sumber daya. Harus selalu '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Mendapat ukuran blok sumber daya dalam byte termasuk datanya. |
| [XmpData](../../aspose.psd.fileformats.psd.resources/xmpresource/xmpdata/) { get; set; } | Dapatkan atau setel penampung data XMP |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Menyimpan blok sumber daya ke aliran yang ditentukan. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Memvalidasi nilai sumber daya. |

### Lihat juga

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* perakitan [Aspose.PSD](../../)


