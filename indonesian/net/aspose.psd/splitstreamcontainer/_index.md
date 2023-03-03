---
title: Class SplitStreamContainer
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.SplitStreamContainer kelas. Mewakili wadah aliran terpisah yang berisi aliran dan menyediakan rutinitas pemrosesan aliran.
type: docs
weight: 5630
url: /id/net/aspose.psd/splitstreamcontainer/
---
## SplitStreamContainer class

Mewakili wadah aliran terpisah yang berisi aliran dan menyediakan rutinitas pemrosesan aliran.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Menginisialisasi instance baru dari`SplitStreamContainer` kelas. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Menginisialisasi instance baru dari`SplitStreamContainer` kelas. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Menginisialisasi instance baru dari`SplitStreamContainer` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Mendapat nilai yang menunjukkan apakah aliran mendukung membaca. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Mendapat nilai yang menunjukkan apakah streaming mendukung pencarian. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Mendapat nilai yang menunjukkan apakah streaming mendukung penulisan. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Mendapat nilai yang menunjukkan apakah aliran ini dibuang pada penutupan. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Mendapat atau menyetel panjang aliran dalam byte. Nilai ini kurang dariLengthdengan posisi aliran awal yang diteruskan dalam konstruktor StreamContainer. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Mendapat atau menetapkan posisi saat ini dalam aliran. Nilai ini mewakili offset dari posisi aliran awal yang diteruskan dalam konstruktor StreamContainer. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Mendapatkan aliran data. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke sumber daya yang disinkronkan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Menghapus semua buffer untuk streaming ini dan menyebabkan semua data buffer ditulis ke perangkat pokok. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Menyisipkan wadah aliran ke posisi yang ditentukan. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Membaca byte untuk mengisi buffer byte yang ditentukan. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran dengan jumlah byte yang dibaca. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Membaca satu byte dari aliran dan memajukan posisi dalam aliran sebanyak satu byte, atau mengembalikan -1 jika di akhir aliran. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) dan streaming[`Length`](../streamcontainer/length/) nilai. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) dan streaming[`Length`](../streamcontainer/length/) nilai. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Menyimpan (menyalin) semua data aliran ke aliran yang ditentukan. Menggunakan aliran[`Length`](../streamcontainer/length/) nilai. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan aliran[`Length`](../streamcontainer/length/) nilai. |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Mengatur posisi dalam aliran saat ini. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Mengatur posisi aliran ke awal aliran. Nilai ini mewakili offset dari posisi aliran awal yang diteruskan dalam konstruktor StreamContainer. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Mengonversi data aliran keByte larik. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Mengonversi data aliran keByte larik. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Menulis semua byte yang ditentukan ke aliran. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Menulis urutan byte ke aliran saat ini dan memajukan posisi saat ini dalam aliran ini dengan jumlah byte yang ditulis. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Menulis satu byte ke posisi saat ini dalam aliran dan memajukan posisi dalam aliran sebanyak satu byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Menyalin data yang ada ke yang lain[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Menyalin data yang ada ke yang lain[`StreamContainer`](../streamcontainer/) . |

### Lihat juga

* class [StreamContainer](../streamcontainer/)
* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


