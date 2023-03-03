---
title: Class StreamContainer
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.StreamContainer kelas. Mewakili wadah aliran yang berisi aliran dan menyediakan rutinitas pemrosesan aliran.
type: docs
weight: 5640
url: /id/net/aspose.psd/streamcontainer/
---
## StreamContainer class

Mewakili wadah aliran yang berisi aliran dan menyediakan rutinitas pemrosesan aliran.

```csharp
public class StreamContainer : DisposableObject
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | Menginisialisasi instance baru dari`StreamContainer` kelas. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | Menginisialisasi instance baru dari`StreamContainer` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Mendapat nilai yang menunjukkan apakah aliran mendukung membaca. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Mendapat nilai yang menunjukkan apakah streaming mendukung pencarian. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Mendapat nilai yang menunjukkan apakah streaming mendukung penulisan. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Mendapat nilai yang menunjukkan apakah aliran ini dibuang pada penutupan. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Mendapat atau menyetel panjang aliran dalam byte. Nilai ini kurang dariLengthdengan posisi aliran awal yang diteruskan dalam konstruktor StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Mendapat atau menetapkan posisi saat ini dalam aliran. Nilai ini mewakili offset dari posisi aliran awal yang diteruskan dalam konstruktor StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Mendapatkan aliran data. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke sumber daya yang disinkronkan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Menghapus semua buffer untuk streaming ini dan menyebabkan semua data buffer ditulis ke perangkat pokok. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | Membaca byte untuk mengisi buffer byte yang ditentukan. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | Membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran dengan jumlah byte yang dibaca. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Membaca satu byte dari aliran dan memajukan posisi dalam aliran sebanyak satu byte, atau mengembalikan -1 jika di akhir aliran. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default[`ReadWriteBytesCount`](./readwritebytescount/) dan streaming[`Length`](./length/) nilai. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default[`ReadWriteBytesCount`](./readwritebytescount/) dan streaming[`Length`](./length/) nilai. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | Menyimpan (menyalin) semua data aliran ke aliran yang ditentukan. Menggunakan aliran[`Length`](./length/) nilai. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan aliran[`Length`](./length/) nilai. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Mengatur posisi dalam aliran saat ini. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Mengatur posisi aliran ke awal aliran. Nilai ini mewakili offset dari posisi aliran awal yang diteruskan dalam konstruktor StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | Mengonversi data aliran keByte larik. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | Mengonversi data aliran keByte larik. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | Menulis semua byte yang ditentukan ke aliran. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | Menulis urutan byte ke aliran saat ini dan memajukan posisi saat ini dalam aliran ini dengan jumlah byte yang ditulis. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Menulis satu byte ke posisi saat ini dalam aliran dan memajukan posisi dalam aliran sebanyak satu byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | Menyalin data yang ada ke yang lain`StreamContainer` . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | Menyalin data yang ada ke yang lain`StreamContainer` . |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | Melakukan konversi eksplisit dari`StreamContainer` keStream . |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | Menentukan jumlah byte baca dan tulis saat membaca secara berurutan. |

### Lihat juga

* class [DisposableObject](../disposableobject/)
* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


