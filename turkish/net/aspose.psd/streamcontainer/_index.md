---
title: Class StreamContainer
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.StreamContainer sınıf. Akışı içeren ve akış işleme rutinleri sağlayan akış kapsayıcısını temsil eder.
type: docs
weight: 5640
url: /tr/net/aspose.psd/streamcontainer/
---
## StreamContainer class

Akışı içeren ve akış işleme rutinleri sağlayan akış kapsayıcısını temsil eder.

```csharp
public class StreamContainer : DisposableObject
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | Yeni bir örneğini başlatır.`StreamContainer` sınıf. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | Yeni bir örneğini başlatır.`StreamContainer` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Akışın okumayı destekleyip desteklemediğini gösteren bir değer alır. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Akışın aramayı destekleyip desteklemediğini gösteren bir değer alır. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Akışın yazmayı destekleyip desteklemediğini gösteren bir değer alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Bu akışın kapanışta atılıp atılmadığını gösteren bir değer alır. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer,LengthStreamContainer yapıcısında iletilen başlangıç akışı konumuna göre. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Akış içindeki geçerli konumu alır veya ayarlar. Bu değer, StreamContainer yapıcısında iletilen başlangıç akış konumundan sapmayı temsil eder. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Veri akışını alır. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Eşitlenen kaynağa erişimi eşitlemek için kullanılabilecek bir nesne alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Bu akış için tüm arabellekleri temizler ve arabelleğe alınan tüm verilerin alttaki aygıta yazılmasına neden olur. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | Belirtilen bayt arabelleğini doldurmak için bayt okur. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | Geçerli akıştan bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısına göre ilerletir. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir veya akışın sonunda ise -1 döndürür. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan arabellek boyutunu kullanır[`ReadWriteBytesCount`](./readwritebytescount/) ve akış[`Length`](./length/) değer. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan arabellek boyutunu kullanır[`ReadWriteBytesCount`](./readwritebytescount/) ve akış[`Length`](./length/) değer. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). akışı kullanır[`Length`](./length/) değer. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). akışı kullanır[`Length`](./length/) değer. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Geçerli akış içindeki konumu ayarlar. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Akış konumunu akışın başlangıcına ayarlar. Bu değer, StreamContainer yapıcısında iletilen başlangıç akış konumundan sapmayı temsil eder. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | Akış verilerini şuna dönüştürür:Byte dizi. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | Akış verilerini şuna dönüştürür:Byte dizi. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | Belirtilen tüm baytları akışa yazar. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | Geçerli akışa bir bayt dizisi yazar ve bu akış içindeki geçerli konumu yazılan bayt sayısı kadar ilerletir. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Akıştaki geçerli konuma bir bayt yazar ve akış içindeki konumu bir bayt ilerletir. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | İçerilen verileri bir başkasına kopyalar`StreamContainer` . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | İçerilen verileri bir başkasına kopyalar`StreamContainer` . |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | Şuradan açık bir dönüştürme gerçekleştirir:`StreamContainer` ileStream . |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | Sıralı olarak okurken okuma ve yazma bayt sayısını belirtir. |

### Ayrıca bakınız

* class [DisposableObject](../disposableobject/)
* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


