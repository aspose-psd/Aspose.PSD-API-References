---
title: "Kelas FileStreamContainer"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileStreamContainer. Pembantu untuk pemrosesan aliran file"
type: docs
weight: 4720
url: /id/net/aspose.psd/filestreamcontainer/
---
{{< psd/tize >}}
## FileStreamContainer class

Pembantu untuk pemrosesan aliran file.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Mendapatkan nilai yang menunjukkan apakah aliran mendukung pembacaan. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Mendapatkan nilai yang menunjukkan apakah aliran mendukung pencarian. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Mendapatkan nilai yang menunjukkan apakah aliran mendukung penulisan. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | Mendapatkan nilai yang menunjukkan apakah aliran dibuat secara eksplisit. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | Mendapatkan nilai yang menunjukkan apakah aliran bersifat temporer. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Mendapatkan nilai yang menunjukkan apakah aliran ini dibuang saat ditutup. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | Membuat aliran file baru. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Mendapatkan atau mengatur panjang aliran dalam byte. Nilai ini kurang dari Length sebesar posisi awal aliran yang diberikan dalam konstruktor StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Mendapatkan atau mengatur posisi saat ini dalam aliran. Nilai ini mewakili offset dari posisi awal aliran yang diberikan dalam konstruktor StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Mendapatkan aliran data. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke sumber daya yang disinkronkan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | Membuka aliran file yang ada. Jika aliran file tidak ada, pengecualian yang sesuai akan dilempar. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | Melakukan konversi eksplisit dari `FileStreamContainer` ke Stream. (2 operator) |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Menghapus semua buffer untuk aliran ini dan menyebabkan data yang di-buffer ditulis ke perangkat dasar. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | Membaca byte untuk mengisi buffer byte yang ditentukan. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | Membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran sebesar jumlah byte yang dibaca. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Membaca satu byte dari aliran dan memajukan posisi dalam aliran satu byte, atau mengembalikan -1 jika berada di akhir aliran. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) dan nilai aliran [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) dan nilai aliran [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Menyimpan (menyalin) semua data aliran ke aliran yang ditentukan. Menggunakan nilai aliran [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan nilai aliran [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Mengatur posisi dalam aliran saat ini. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Mengatur posisi aliran ke awal aliran. Nilai ini mewakili offset dari posisi aliran awal yang diberikan dalam konstruktor StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | Mengonversi data aliran menjadi array Byte. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | Mengonversi data aliran menjadi array Byte. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | Menulis semua byte yang ditentukan ke aliran. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | Menulis urutan byte ke aliran saat ini dan memajukan posisi saat ini dalam aliran ini sebesar jumlah byte yang ditulis. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Menulis satu byte ke posisi saat ini dalam aliran dan memajukan posisi dalam aliran satu byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Menyalin data yang terkandung ke [`StreamContainer`](../streamcontainer/) lain. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Menyalin data yang terkandung ke [`StreamContainer`](../streamcontainer/) lain. |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | Antarmuka IImageExporterDescriptor |

### Lihat Juga

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


