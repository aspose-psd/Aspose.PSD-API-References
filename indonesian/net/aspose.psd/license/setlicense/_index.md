---
title: License.SetLicense
second_title: Aspose.PSD untuk Referensi .NET API
description: License metode. Lisensi komponen.
type: docs
weight: 20
url: /id/net/aspose.psd/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Lisensi komponen.

```csharp
public void SetLicense(string licenseName)
```

### Perkataan

Mencoba menemukan lisensi di lokasi berikut:

1. Jalur eksplisit.

2. Folder yang berisi rakitan komponen Aspose.

3. Folder yang berisi rakitan panggilan klien.

4. Folder yang berisi rakitan entri (startup).

5. Sumber daya tertanam dalam perakitan panggilan klien.

**Catatan:**Di .NET Compact Framework, mencoba menemukan lisensi hanya di lokasi berikut:

1. Jalur eksplisit.

2. Sumber daya tertanam dalam perakitan panggilan klien.

### Contoh

Dalam contoh ini, upaya akan dilakukan untuk menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi rakitan pemanggil, di folder rakitan entri lalu di sumber daya tersemat dari rakitan pemanggil. Dapat berupa nama file lengkap atau pendek atau nama sumber daya tersemat. Gunakan string kosong untuk beralih ke mode evaluasi.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

### Lihat juga

* class [License](../)
* ruang nama [Aspose.PSD](../../license/)
* perakitan [Aspose.PSD](../../../)

---

## SetLicense(Stream) {#setlicense}

Lisensi komponen.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran yang berisi lisensi. |

### Perkataan

Gunakan metode ini untuk memuat lisensi dari aliran.

### Contoh

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Lihat juga

* class [License](../)
* ruang nama [Aspose.PSD](../../license/)
* perakitan [Aspose.PSD](../../../)


