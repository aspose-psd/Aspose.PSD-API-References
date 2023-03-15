---
title: Class FileStreamContainer
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileStreamContainer kelas. Pembantu untuk pemrosesan aliran file.
type: docs
weight: 4250
url: /id/net/aspose.psd/filestreamcontainer/
---
## FileStreamContainer class

Pembantu untuk pemrosesan aliran file.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Properti

| Nama | Keterangan |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Mendapat nilai yang menunjukkan apakah aliran mendukung membaca. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Mendapat nilai yang menunjukkan apakah streaming mendukung pencarian. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Mendapat nilai yang menunjukkan apakah streaming mendukung penulisan. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | Mendapat jalur file. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | Mendapat nilai yang menunjukkan apakah streaming dibuat secara eksplisit. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Mendapat nilai yang menunjukkan apakah aliran ini dibuang pada penutupan. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah streaming bersifat temporal. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Mendapat atau menyetel panjang aliran dalam byte. Nilai ini kurang dariLengthdengan posisi aliran awal yang diteruskan dalam konstruktor StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Mendapat atau menetapkan posisi saat ini dalam aliran. Nilai ini mewakili offset dari posisi aliran awal yang diteruskan dalam konstruktor StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Mendapatkan aliran data. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke sumber daya yang disinkronkan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | Membuat aliran file baru. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | Membuka aliran file yang ada. Jika aliran file tidak ada, pengecualian yang sesuai akan dilemparkan. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Menghapus semua buffer untuk streaming ini dan menyebabkan semua data buffer ditulis ke perangkat pokok. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | Membaca byte untuk mengisi buffer byte yang ditentukan. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | Membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran dengan jumlah byte yang dibaca. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Membaca satu byte dari aliran dan memajukan posisi dalam aliran sebanyak satu byte, atau mengembalikan -1 jika di akhir aliran. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) dan streaming[`Length`](../streamcontainer/length/) nilai. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) dan streaming[`Length`](../streamcontainer/length/) nilai. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Menyimpan (menyalin) semua data aliran ke aliran yang ditentukan. Menggunakan aliran[`Length`](../streamcontainer/length/) nilai. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan aliran[`Length`](../streamcontainer/length/) nilai. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Mengatur posisi dalam aliran saat ini. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Mengatur posisi aliran ke awal aliran. Nilai ini mewakili offset dari posisi aliran awal yang diteruskan dalam konstruktor StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | Mengonversi data aliran keByte larik. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | Mengonversi data aliran keByte larik. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | Menulis semua byte yang ditentukan ke aliran. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | Menulis urutan byte ke aliran saat ini dan memajukan posisi saat ini dalam aliran ini dengan jumlah byte yang ditulis. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Menulis satu byte ke posisi saat ini dalam aliran dan memajukan posisi dalam aliran sebanyak satu byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Menyalin data yang ada ke yang lain[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Menyalin data yang ada ke yang lain[`StreamContainer`](../streamcontainer/) . |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | Melakukan konversi eksplisit dari`FileStreamContainer` keStream . (2 operators) |

### Lihat juga

* class [StreamContainer](../streamcontainer/)
* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


