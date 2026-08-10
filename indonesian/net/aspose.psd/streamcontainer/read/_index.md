---
title: "StreamContainer.Read"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode StreamContainer. Membaca byte untuk mengisi buffer byte yang ditentukan"
type: docs
weight: 110
url: /id/net/aspose.psd/streamcontainer/read/
---
{{< psd/tize >}}
## Read(byte[]) {#read}

Membaca byte untuk mengisi buffer byte yang ditentukan.

```csharp
public virtual int Read(byte[] bytes)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| byte | Byte[] | Byte yang akan diisi. |

### Nilai Kembalian

Jumlah byte yang dibaca. Nilai ini dapat lebih kecil daripada jumlah byte dalam buffer jika tidak cukup byte dalam aliran.

### Lihat Juga

* class [StreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran sebesar jumlah byte yang dibaca.

```csharp
public virtual int Read(byte[] buffer, int offset, int count)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | Byte[] | Sebuah array byte. Ketika metode ini mengembalikan, buffer berisi array byte yang ditentukan dengan nilai antara *offset* dan (*offset* + *count* - 1) digantikan oleh byte yang dibaca dari sumber saat ini. |
| offset | Int32 | Offset byte berbasis nol dalam *buffer* tempat mulai menyimpan data yang dibaca dari aliran saat ini. |
| jumlah | Int32 | Jumlah maksimum byte yang akan dibaca dari aliran saat ini. |

### Nilai Kembalian

Total jumlah byte yang dibaca ke dalam buffer. Ini dapat lebih kecil daripada jumlah byte yang diminta jika byte tersebut tidak tersedia saat ini, atau nol (0) jika akhir aliran telah tercapai.

### Lihat Juga

* class [StreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


