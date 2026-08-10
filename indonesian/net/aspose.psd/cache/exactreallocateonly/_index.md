---
title: "Cache.ExactReallocateOnly"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Cache properti. Mendapatkan atau mengatur nilai yang menunjukkan apakah alokasi ulang harus tepat atau tidak. Jika alokasi ulang tidak tepat, kinerja harus lebih tinggi."
type: docs
weight: 50
url: /id/net/aspose.psd/cache/exactreallocateonly/
---
{{< psd/tize >}}
## Cache.ExactReallocateOnly property

Mendapatkan atau mengatur nilai yang menunjukkan apakah alokasi ulang harus tepat atau tidak. Jika alokasi ulang tidak tepat, kinerja seharusnya lebih tinggi.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Property Value

`true` jika alokasi ulang tepat; jika tidak, `false`.

## Catatan

Alokasi ulang tepat akan melakukan alokasi ulang memori tambahan hanya hingga batas atas yang ditentukan. Saat memberikan batas atas untuk memori dalam proses alokasi ulang, data yang di-cache akan disalin ke disk jika memungkinkan. Saat memberikan batas atas untuk memori disk selama alokasi ulang, pengecualian yang sesuai akan dilempar. Kinerja seharusnya lebih tinggi jika opsi ini dimatikan karena tidak ada penyalinan tambahan yang akan dilakukan jika memungkinkan, namun hal ini juga dapat menyebabkan melewati batas atas yang ditentukan untuk memori atau disk.

### Lihat Juga

* class [Cache](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


