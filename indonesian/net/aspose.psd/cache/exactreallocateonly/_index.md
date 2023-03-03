---
title: Cache.ExactReallocateOnly
second_title: Aspose.PSD untuk Referensi .NET API
description: Cache Properti. Mendapat atau menetapkan nilai yang menunjukkan apakah realokasi harus tepat atau tidak. Jika realokasi tidak tepat kinerjanya harus lebih tinggi.
type: docs
weight: 50
url: /id/net/aspose.psd/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

Mendapat atau menetapkan nilai yang menunjukkan apakah realokasi harus tepat atau tidak. Jika realokasi tidak tepat, kinerjanya harus lebih tinggi.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Nilai properti

`BENAR` jika realokasi tepat; jika tidak,`PALSU` .

### Perkataan

Realokasi yang tepat akan melakukan realokasi memori tambahan hanya hingga batas atas yang ditentukan. Ketika melewati batas atas untuk memori dalam selama realokasi, data yang di-cache akan disalin ke disk jika memungkinkan. Ketika melewati batas atas untuk memori disk selama realokasi pengecualian yang sesuai dilemparkan. Kinerja harus lebih tinggi jika opsi ini dimatikan karena tidak ada penyalinan tambahan yang akan dilakukan jika memungkinkan, namun hal ini juga dapat menyebabkan melewati batas atas yang ditentukan untuk memori atau disk.

### Lihat juga

* class [Cache](../)
* ruang nama [Aspose.PSD](../../cache/)
* perakitan [Aspose.PSD](../../../)


