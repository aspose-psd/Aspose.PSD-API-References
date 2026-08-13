---
title: "Sınıf FileStreamContainer"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileStreamContainer sınıfı. Dosya akışı işleme için yardımcı."
type: docs
weight: 4750
url: /tr/net/aspose.psd/filestreamcontainer/
---
{{< psd/tize >}}
## FileStreamContainer class

Dosya akışı işleme için yardımcı.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Akışın okuma desteği olup olmadığını gösteren bir değer alır. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Akışın ileri/geri sarma desteği olup olmadığını gösteren bir değer alır. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Akışın yazma desteği olup olmadığını gösteren bir değer alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | Dosya yolunu alır. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | Akışın açıkça oluşturulup oluşturulmadığını gösteren bir değeri alır. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Bu akışın kapatıldığında serbest bırakılıp bırakılmadığını gösteren bir değer alır. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | Akışın geçici olup olmadığını gösteren bir değeri alır veya ayarlar. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer, StreamContainer yapıcıya geçirilen başlangıç akış konumu nedeniyle Length değerinden daha küçüktür. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Akış içindeki mevcut konumu alır veya ayarlar. Bu değer, StreamContainer yapıcıya geçirilen başlangıç akış konumundan offset'i temsil eder. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Veri akışını alır. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Senkronize edilmiş kaynağa erişimi senkronize etmek için kullanılabilecek bir nesne alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | Yeni bir dosya akışı oluşturur. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | Mevcut bir dosya akışını açar. Dosya akışı mevcut değilse uygun istisna fırlatılır. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Bu akış için tüm tamponları temizler ve tamponlanmış verilerin temel cihaza yazılmasını sağlar. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | Belirtilen bayt tamponunu doldurmak için baytları okur. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | Geçerli akıştan bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir, ya da akışın sonunda ise -1 döndürür. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutunu [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) ve akış [`Length`](../streamcontainer/length/) değerini kullanır. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutunu [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) ve akış [`Length`](../streamcontainer/length/) değerini kullanır. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). Akış [`Length`](../streamcontainer/length/) değerini kullanır. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Akış [`Length`](../streamcontainer/length/) değerini kullanır. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Geçerli akış içindeki konumu ayarlar. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Akış konumunu akışın başına ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | Akış verilerini Bayt dizisine dönüştürür. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | Akış verilerini Bayt dizisine dönüştürür. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | Belirtilen tüm baytları akışa yazar. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | Bir bayt dizisini geçerli akışa yazar ve bu akış içindeki mevcut konumu yazılan bayt sayısı kadar ilerletir. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Akıştaki mevcut konuma bir bayt yazar ve akış içindeki konumu bir bayt ilerletir. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | İçerilen verileri başka bir [`StreamContainer`](../streamcontainer/) içine kopyalar. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | İçerilen verileri başka bir [`StreamContainer`](../streamcontainer/) içine kopyalar. |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | `FileStreamContainer`'dan Stream'e açık bir dönüşüm gerçekleştirir. (2 operatör) |

### Ayrıca Bakınız

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


