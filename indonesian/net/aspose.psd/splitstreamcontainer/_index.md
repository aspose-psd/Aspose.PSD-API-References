---
title: "Kelas SplitStreamContainer"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.SplitStreamContainer. Mewakili kontainer aliran terpisah yang berisi aliran dan menyediakan rutin pemrosesan aliran."
type: docs
weight: 6130
url: /id/net/aspose.psd/splitstreamcontainer/
---
{{< psd/tize >}}
## SplitStreamContainer class

Mewakili kontainer aliran terpisah yang berisi aliran dan menyediakan rutinitas pemrosesan aliran.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Menginisialisasi instance baru dari kelas `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Menginisialisasi instance baru dari kelas `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Menginisialisasi instance baru dari kelas `SplitStreamContainer`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Mendapatkan nilai yang menunjukkan apakah aliran mendukung pembacaan. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Mendapatkan nilai yang menunjukkan apakah aliran mendukung pencarian. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Mendapatkan nilai yang menunjukkan apakah aliran mendukung penulisan. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Mendapatkan nilai yang menunjukkan apakah aliran ini dibuang saat ditutup. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Mendapatkan atau mengatur panjang aliran dalam byte. Nilai ini kurang dari Length sebesar posisi awal aliran yang diberikan dalam konstruktor StreamContainer. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Mendapatkan atau mengatur posisi saat ini dalam aliran. Nilai ini mewakili offset dari posisi awal aliran yang diberikan dalam konstruktor StreamContainer. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Mendapatkan aliran data. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke sumber daya yang disinkronkan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Menghapus semua buffer untuk aliran ini dan menyebabkan data yang di-buffer ditulis ke perangkat dasar. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Menyisipkan kontainer aliran ke posisi yang ditentukan. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Membaca byte untuk mengisi buffer byte yang ditentukan. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran sebesar jumlah byte yang dibaca. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Membaca satu byte dari aliran dan memajukan posisi dalam aliran satu byte, atau mengembalikan -1 jika berada di akhir aliran. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) dan nilai aliran [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) dan nilai aliran [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Menyimpan (menyalin) semua data aliran ke aliran yang ditentukan. Menggunakan nilai aliran [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan nilai aliran [`Length`](../streamcontainer/length/). |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Mengatur posisi dalam aliran saat ini. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Mengatur posisi aliran ke awal aliran. Nilai ini mewakili offset dari posisi aliran awal yang diberikan dalam konstruktor StreamContainer. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Mengonversi data aliran menjadi array Byte. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Mengonversi data aliran menjadi array Byte. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Menulis semua byte yang ditentukan ke aliran. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Menulis urutan byte ke aliran saat ini dan memajukan posisi saat ini dalam aliran ini sebesar jumlah byte yang ditulis. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Menulis satu byte ke posisi saat ini dalam aliran dan memajukan posisi dalam aliran satu byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Menyalin data yang terkandung ke [`StreamContainer`](../streamcontainer/) lain. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Menyalin data yang terkandung ke [`StreamContainer`](../streamcontainer/) lain. |

### Lihat Juga

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


