---
title: "XmpBasicPackage.ContainsKey"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode XmpBasicPackage. Menentukan apakah kunci yang ditentukan berisi kunci"
type: docs
weight: 40
url: /id/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/containskey/
---
{{< psd/tize >}}
## XmpBasicPackage.ContainsKey method

Menentukan apakah kunci yang ditentukan mengandung kunci.

```csharp
public override bool ContainsKey(string key)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kunci | String | Kunci yang akan diperiksa. |

### Nilai Kembalian

Mengembalikan true jika kunci yang ditentukan berisi kunci.

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

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


