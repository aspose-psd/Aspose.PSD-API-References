---
title: "XmpBasicPackage.Item"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti XmpBasicPackage. Mendapatkan atau mengatur Object dengan kunci yang ditentukan"
type: docs
weight: 20
url: /id/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

Mendapatkan atau mengatur Objek dengan kunci yang ditentukan.

```csharp
public override object this[string key] { get; set; }
```

| Parameter | Deskripsi |
| --- | --- |
| kunci | Kunci yang mengidentifikasi nilai. |

### Nilai Kembalian

Mengembalikan Object dengan kunci yang ditentukan.

### Property Value

Object.

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


