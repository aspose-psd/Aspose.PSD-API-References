---
title: "Kelas Metered"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Metered. Menyediakan metode untuk mengatur kunci bermeter."
type: docs
weight: 5610
url: /id/net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

Menyediakan metode untuk mengatur kunci bermeter.

```csharp
public class Metered
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Metered](metered/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | Menentukan apakah Object yang ditentukan, sama dengan instance ini. |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | Mendapatkan nama produk. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | Mengatur kunci publik dan privat bermeter. Jika Anda membeli lisensi bermeter, saat memulai aplikasi, API ini harus dipanggil, biasanya ini sudah cukup. Namun, jika selalu gagal mengunggah data konsumsi dan melebihi 24 jam, lisensi akan diubah menjadi status evaluasi; untuk menghindari hal tersebut, Anda harus secara teratur memeriksa status lisensi, jika statusnya evaluasi, panggil kembali API ini. |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | Mendapatkan kredit konsumsi |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | Mendapatkan ukuran file konsumsi |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | Periksa apakah bermeter telah dilisensikan |

## Contoh

Dalam contoh ini, akan dilakukan upaya untuk mengatur kunci publik dan privat bermeter

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


