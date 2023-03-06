---
title: Class FileStreamContainer
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileStreamContainer sınıf. Dosya akışı işleme için yardımcı.
type: docs
weight: 4250
url: /tr/net/aspose.psd/filestreamcontainer/
---
## FileStreamContainer class

Dosya akışı işleme için yardımcı.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Akışın okumayı destekleyip desteklemediğini gösteren bir değer alır. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Akışın aramayı destekleyip desteklemediğini gösteren bir değer alır. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Akışın yazmayı destekleyip desteklemediğini gösteren bir değer alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | Dosya yolunu alır. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | Akışın açıkça oluşturulup oluşturulmadığını gösteren bir değer alır. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Bu akışın kapanışta atılıp atılmadığını gösteren bir değer alır. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | Akışın geçici olup olmadığını gösteren bir değer alır veya ayarlar. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer,LengthStreamContainer yapıcısında iletilen başlangıç akışı konumuna göre. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Akış içindeki geçerli konumu alır veya ayarlar. Bu değer, StreamContainer yapıcısında iletilen başlangıç akış konumundan sapmayı temsil eder. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Veri akışını alır. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Eşitlenen kaynağa erişimi eşitlemek için kullanılabilecek bir nesne alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | Yeni bir dosya akışı oluşturur. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | Mevcut bir dosya akışını açar. Dosya akışı yoksa uygun istisna atılır. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Bu akış için tüm arabellekleri temizler ve arabelleğe alınan tüm verilerin alttaki aygıta yazılmasına neden olur. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | Belirtilen bayt arabelleğini doldurmak için bayt okur. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | Geçerli akıştan bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısına göre ilerletir. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir veya akışın sonunda ise -1 döndürür. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan arabellek boyutunu kullanır[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) ve akış[`Length`](../streamcontainer/length/) değer. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan arabellek boyutunu kullanır[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) ve akış[`Length`](../streamcontainer/length/) değer. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). akışı kullanır[`Length`](../streamcontainer/length/) değer. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). akışı kullanır[`Length`](../streamcontainer/length/) değer. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Geçerli akış içindeki konumu ayarlar. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Akış konumunu akışın başlangıcına ayarlar. Bu değer, StreamContainer yapıcısında iletilen başlangıç akış konumundan sapmayı temsil eder. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | Akış verilerini şuna dönüştürür:Byte dizi. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | Akış verilerini şuna dönüştürür:Byte dizi. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | Belirtilen tüm baytları akışa yazar. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | Geçerli akışa bir bayt dizisi yazar ve bu akış içindeki geçerli konumu yazılan bayt sayısı kadar ilerletir. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Akıştaki geçerli konuma bir bayt yazar ve akış içindeki konumu bir bayt ilerletir. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | İçerilen verileri bir başkasına kopyalar[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | İçerilen verileri bir başkasına kopyalar[`StreamContainer`](../streamcontainer/) . |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | Şuradan açık bir dönüştürme gerçekleştirir:`FileStreamContainer` ileStream . (2 operators) |

### Ayrıca bakınız

* class [StreamContainer](../streamcontainer/)
* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


