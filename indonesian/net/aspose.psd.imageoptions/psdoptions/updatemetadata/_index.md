---
title: "PsdOptions.UpdateMetadata"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "PsdOptions property. Mendapatkan atau mengatur nilai yang menunjukkan apakah memperbarui metadata. Jika nilai true, metadata akan diperbarui saat menyimpan gambar"
type: docs
weight: 110
url: /id/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

Mendapatkan atau mengatur nilai yang menunjukkan apakah [update metadata]. Jika nilai true, metadata akan diperbarui saat menyimpan gambar.

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` jika [update metadata]; selain itu, `false`.

## Contoh

Kode berikut menunjukkan penggunaan opsi UpdateMetadata untuk memperbarui nilai CreatorTool dalam data xmp.

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // Jika Anda ingin alat pembuat berubah, pastikan properti \"UpdateMetadata\" disetel ke true. Nilainya secara default disetel ke true.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // Menyimpan gambar. 
    image.Save(path, psdOptions);

    // Memeriksa alat pembuat dalam kode.
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // Di sini akan diperbarui info alat pembuat.
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### Lihat Juga

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


