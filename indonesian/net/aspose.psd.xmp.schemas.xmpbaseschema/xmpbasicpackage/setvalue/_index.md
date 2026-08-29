---
title: "XmpBasicPackage.SetValue"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode XmpBasicPackage. Mengatur nilai"
type: docs
weight: 120
url: /id/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

Mengatur nilai.

```csharp
public override void SetValue(string key, IXmlValue value)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kunci | String | Representasi string dari kunci yang diidentifikasi dengan nilai yang ditambahkan. |
| nilai | IXmlValue | Nilai yang akan ditambahkan. |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


