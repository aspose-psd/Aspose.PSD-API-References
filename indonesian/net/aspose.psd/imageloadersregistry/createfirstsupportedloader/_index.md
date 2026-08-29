---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "ImageLoadersRegistry method. Membuat pemuat pertama yang ditemukan yang cocok untuk stream yang ditentukan dan opsional loadOptions"
type: docs
weight: 30
url: /id/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Membuat pemuat pertama yang ditemukan yang cocok untuk *stream* yang ditentukan dan opsional *loadOptions*.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran. |
| loadOptions | LoadOptions | Opsi pemuatan. |

### Nilai Kembalian

Pemuat yang mendukung *stream* dan *loadOptions* yang ditentukan atau null jika tidak ada pemuat seperti itu yang ditemukan.

## Catatan

Pemuat pertama sebenarnya akan menjadi yang terakhir terdaftar.

### Lihat Juga

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


