---
title: "Sınıf SplitStreamContainer"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.SplitStreamContainer sınıfı. Akışı içeren ve akış işleme rutinleri sağlayan bölünmüş akış konteynerini temsil eder"
type: docs
weight: 6160
url: /tr/net/aspose.psd/splitstreamcontainer/
---
{{< psd/tize >}}
## SplitStreamContainer class

Akışı içeren ve akış işleme rutinleri sağlayan bölünmüş akış konteynerini temsil eder.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Yeni bir `SplitStreamContainer` sınıfı örneği başlatır. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Yeni bir `SplitStreamContainer` sınıfı örneği başlatır. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Yeni bir `SplitStreamContainer` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Akışın okuma desteği olup olmadığını gösteren bir değer alır. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Akışın ileri/geri sarma desteği olup olmadığını gösteren bir değer alır. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Akışın yazma desteği olup olmadığını gösteren bir değer alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Bu akışın kapatıldığında serbest bırakılıp bırakılmadığını gösteren bir değer alır. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer, StreamContainer yapıcıya geçirilen başlangıç akış konumu nedeniyle Length değerinden daha küçüktür. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Akış içindeki mevcut konumu alır veya ayarlar. Bu değer, StreamContainer yapıcıya geçirilen başlangıç akış konumundan offset'i temsil eder. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Veri akışını alır. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Senkronize edilmiş kaynağa erişimi senkronize etmek için kullanılabilecek bir nesne alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Bu akış için tüm tamponları temizler ve tamponlanmış verilerin temel cihaza yazılmasını sağlar. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Akış konteynerini belirtilen konuma ekler. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Belirtilen bayt tamponunu doldurmak için baytları okur. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Geçerli akıştan bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir, ya da akışın sonunda ise -1 döndürür. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutunu [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) ve akış [`Length`](../streamcontainer/length/) değerini kullanır. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutunu [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) ve akış [`Length`](../streamcontainer/length/) değerini kullanır. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). Akış [`Length`](../streamcontainer/length/) değerini kullanır. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Akış [`Length`](../streamcontainer/length/) değerini kullanır. |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Geçerli akış içindeki konumu ayarlar. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Akış konumunu akışın başına ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Akış verilerini Bayt dizisine dönüştürür. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Akış verilerini Bayt dizisine dönüştürür. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Belirtilen tüm baytları akışa yazar. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Bir bayt dizisini geçerli akışa yazar ve bu akış içindeki mevcut konumu yazılan bayt sayısı kadar ilerletir. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Akıştaki mevcut konuma bir bayt yazar ve akış içindeki konumu bir bayt ilerletir. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | İçerilen verileri başka bir [`StreamContainer`](../streamcontainer/) içine kopyalar. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | İçerilen verileri başka bir [`StreamContainer`](../streamcontainer/) içine kopyalar. |

### Ayrıca Bakınız

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


