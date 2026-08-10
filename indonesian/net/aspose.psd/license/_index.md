---
title: "Kelas Aspose.PSD.License. Menyediakan metode untuk melisensikan komponen"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Menginisialisasi instance baru dari kelas ini."
type: docs
weight: 5540
url: /id/net/aspose.psd/license/
---
{{< psd/tize >}}
## License class

Menyediakan metode untuk melisensikan komponen.

```csharp
public class License
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [License](license/)() | Melisensikan komponen. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | Dalam contoh ini, akan dilakukan upaya untuk menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil. |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | Dalam contoh ini, akan dilakukan upaya untuk menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil. |

## Contoh

Dalam contoh ini, upaya akan dilakukan untuk menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tertanam dari assembly pemanggil.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


