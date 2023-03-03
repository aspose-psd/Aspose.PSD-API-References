---
title: SplitStreamContainer.Read
second_title: Aspose.PSD untuk Referensi .NET API
description: SplitStreamContainer metode. Membaca byte untuk mengisi buffer byte yang ditentukan.
type: docs
weight: 110
url: /id/net/aspose.psd/splitstreamcontainer/read/
---
## Read(byte[]) {#read}

Membaca byte untuk mengisi buffer byte yang ditentukan.

```csharp
public override int Read(byte[] bytes)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| bytes | Byte[] | Byte untuk diisi. |

### Nilai Pengembalian

Jumlah byte yang dibaca. Nilai ini bisa kurang dari jumlah byte dalam buffer jika byte dalam aliran tidak cukup.

### Lihat juga

* class [SplitStreamContainer](../)
* ruang nama [Aspose.PSD](../../splitstreamcontainer/)
* perakitan [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran dengan jumlah byte yang dibaca.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| buffer | Byte[] | Array byte. Saat metode ini kembali, buffer berisi array byte yang ditentukan dengan nilai di antaranya*offset* Dan (*offset* +*count* - 1) diganti dengan byte yang dibaca dari sumber saat ini. |
| offset | Int32 | Offset byte berbasis nol di*buffer* di mana untuk mulai menyimpan data yang dibaca dari aliran saat ini. |
| count | Int32 | Jumlah maksimum byte yang akan dibaca dari aliran saat ini. |

### Nilai Pengembalian

Jumlah total byte yang dibaca ke dalam buffer. Ini bisa kurang dari jumlah byte yang diminta jika banyak byte saat ini tidak tersedia, atau nol (0) jika akhir aliran telah tercapai.

### Lihat juga

* class [SplitStreamContainer](../)
* ruang nama [Aspose.PSD](../../splitstreamcontainer/)
* perakitan [Aspose.PSD](../../../)


