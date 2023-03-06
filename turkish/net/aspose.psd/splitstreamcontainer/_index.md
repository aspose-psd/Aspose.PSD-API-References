---
title: Class SplitStreamContainer
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.SplitStreamContainer sınıf. Akışı içeren ve akış işleme rutinleri sağlayan bölünmüş akış kapsayıcısını temsil eder.
type: docs
weight: 5630
url: /tr/net/aspose.psd/splitstreamcontainer/
---
## SplitStreamContainer class

Akışı içeren ve akış işleme rutinleri sağlayan bölünmüş akış kapsayıcısını temsil eder.

```csharp
public class SplitStreamContainer : StreamContainer
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Yeni bir örneğini başlatır.`SplitStreamContainer` sınıf. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Yeni bir örneğini başlatır.`SplitStreamContainer` sınıf. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Yeni bir örneğini başlatır.`SplitStreamContainer` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Akışın okumayı destekleyip desteklemediğini gösteren bir değer alır. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Akışın aramayı destekleyip desteklemediğini gösteren bir değer alır. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Akışın yazmayı destekleyip desteklemediğini gösteren bir değer alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Bu akışın kapanışta atılıp atılmadığını gösteren bir değer alır. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer,LengthStreamContainer yapıcısında iletilen başlangıç akışı konumuna göre. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Akış içindeki geçerli konumu alır veya ayarlar. Bu değer, StreamContainer yapıcısında iletilen başlangıç akış konumundan sapmayı temsil eder. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Veri akışını alır. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Eşitlenen kaynağa erişimi eşitlemek için kullanılabilecek bir nesne alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Bu akış için tüm arabellekleri temizler ve arabelleğe alınan tüm verilerin alttaki aygıta yazılmasına neden olur. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Akış kabını belirtilen konuma ekler. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Belirtilen bayt arabelleğini doldurmak için bayt okur. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Geçerli akıştan bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısına göre ilerletir. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir veya akışın sonunda ise -1 döndürür. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan arabellek boyutunu kullanır[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) ve akış[`Length`](../streamcontainer/length/) değer. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan arabellek boyutunu kullanır[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) ve akış[`Length`](../streamcontainer/length/) değer. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). akışı kullanır[`Length`](../streamcontainer/length/) değer. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). akışı kullanır[`Length`](../streamcontainer/length/) değer. |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Geçerli akış içindeki konumu ayarlar. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Akış konumunu akışın başlangıcına ayarlar. Bu değer, StreamContainer yapıcısında iletilen başlangıç akış konumundan sapmayı temsil eder. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Akış verilerini şuna dönüştürür:Byte dizi. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Akış verilerini şuna dönüştürür:Byte dizi. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Belirtilen tüm baytları akışa yazar. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Geçerli akışa bir bayt dizisi yazar ve bu akış içindeki geçerli konumu yazılan bayt sayısı kadar ilerletir. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Akıştaki geçerli konuma bir bayt yazar ve akış içindeki konumu bir bayt ilerletir. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | İçerilen verileri bir başkasına kopyalar[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | İçerilen verileri bir başkasına kopyalar[`StreamContainer`](../streamcontainer/) . |

### Ayrıca bakınız

* class [StreamContainer](../streamcontainer/)
* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


