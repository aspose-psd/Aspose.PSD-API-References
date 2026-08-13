---
title: "Sınıf StreamContainer"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.StreamContainer sınıfı. Akışı içeren ve akış işleme rutinleri sağlayan akış konteynerini temsil eder"
type: docs
weight: 6170
url: /tr/net/aspose.psd/streamcontainer/
---
{{< psd/tize >}}
## StreamContainer class

Akışı içeren ve akış işleme rutinleri sağlayan akış konteynerini temsil eder.

```csharp
public class StreamContainer : DisposableObject
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | `StreamContainer` sınıfının yeni bir örneğini başlatır. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | `StreamContainer` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Akışın okuma desteği olup olmadığını gösteren bir değer alır. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Akışın ileri/geri sarma desteği olup olmadığını gösteren bir değer alır. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Akışın yazma desteği olup olmadığını gösteren bir değer alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Bu akışın kapatıldığında serbest bırakılıp bırakılmadığını gösteren bir değer alır. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer, StreamContainer yapıcıya geçirilen başlangıç akış konumu nedeniyle Length değerinden daha küçüktür. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Akış içindeki mevcut konumu alır veya ayarlar. Bu değer, StreamContainer yapıcıya geçirilen başlangıç akış konumundan offset'i temsil eder. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Veri akışını alır. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Senkronize edilmiş kaynağa erişimi senkronize etmek için kullanılabilecek bir nesne alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Bu akış için tüm tamponları temizler ve tamponlanmış verilerin temel cihaza yazılmasını sağlar. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | Belirtilen bayt tamponunu doldurmak için baytları okur. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | Geçerli akıştan bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir, ya da akışın sonunda ise -1 döndürür. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu [`ReadWriteBytesCount`](./readwritebytescount/) ve akış [`Length`](./length/) değeri kullanılır. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu [`ReadWriteBytesCount`](./readwritebytescount/) ve akış [`Length`](./length/) değeri kullanılır. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). Akış [`Length`](./length/) değeri kullanılır. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Akış [`Length`](./length/) değeri kullanılır. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Geçerli akış içindeki konumu ayarlar. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Akış konumunu akışın başına ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | Akış verilerini Bayt dizisine dönüştürür. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | Akış verilerini Bayt dizisine dönüştürür. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | Belirtilen tüm baytları akışa yazar. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | Bir bayt dizisini geçerli akışa yazar ve bu akış içindeki mevcut konumu yazılan bayt sayısı kadar ilerletir. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Akıştaki mevcut konuma bir bayt yazar ve akış içindeki konumu bir bayt ilerletir. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | İçerilen verileri başka bir `StreamContainer`'a kopyalar. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | İçerilen verileri başka bir `StreamContainer`'a kopyalar. |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | `StreamContainer`'dan Stream'e açık bir dönüşüm gerçekleştirir. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | Sıralı okuma sırasında okuma ve yazma bayt sayısını belirtir. |

### Ayrıca Bakınız

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


