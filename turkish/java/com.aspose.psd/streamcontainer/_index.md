---
title: "StreamContainer"
second_title: "Java için Aspose.PSD API Referansı"
description: "Akışı içeren ve akış işleme rutinleri sağlayan akış konteynerini temsil eder."
type: docs
weight: 103
url: /tr/java/com.aspose.psd/streamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

Akışı içeren ve akış işleme rutinleri sağlayan akış konteynerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | StreamContainer sınıfının yeni bir örneğini başlatır. |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) |  |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | StreamContainer sınıfının yeni bir örneğini başlatır. |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Sıralı okuma sırasında okuma ve yazma bayt sayısını belirtir. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [canRead()](#canRead--) | Akışın okuma desteği olup olmadığını gösteren bir değer alır. |
| [canSeek()](#canSeek--) | Akışın konumlandırma desteği olup olmadığını gösteren bir değer alır. |
| [canWrite()](#canWrite--) | Akışın yazma desteği olup olmadığını gösteren bir değer alır. |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Bu akış için tüm arabellekleri temizler ve tamponlanmış verilerin alt cihazına yazılmasını sağlar. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getLength()](#getLength--) | Akış uzunluğunu bayt cinsinden alır veya ayarlar. |
| [getPosition()](#getPosition--) | Akış içindeki geçerli konumu alır veya ayarlar. |
| [getStream()](#getStream--) | Veri akışını alır. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Senkronize edilmiş kaynağa erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
| [hashCode()](#hashCode--) |  |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Bu akışın kapatıldığında serbest bırakılıp bırakılmadığını gösteren değeri alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] bytes)](#read-byte---) | Belirtilen bayt tamponunu doldurmak için baytları okur. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Mevcut akıştan bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir. |
| [readByte()](#readByte--) | Akıştan bir bayt okur ve konumu bir bayt ilerletir; akışın sonundaysa -1 döndürür. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [save(String filePath)](#save-java.lang.String-) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [seek(long offset, int origin)](#seek-long-int-) | Mevcut akış içindeki konumu ayarlar. |
| [seekBegin()](#seekBegin--) | Akış konumunu akışın başına ayarlar. |
| [setLength(long value)](#setLength-long-) | Akış uzunluğunu bayt cinsinden alır veya ayarlar. |
| [setPosition(long value)](#setPosition-long-) | Akış içindeki geçerli konumu alır veya ayarlar. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Akış verilerini  byte  dizisine dönüştürür. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Akış verilerini  byte  dizisine dönüştürür. |
| [toString()](#toString--) |  |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) |   com.aspose.imaging.StreamContainer  'den  System.IO.Stream 'e açık bir dönüşüm gerçekleştirir. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Belirtilen tüm baytları akışa yazar. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Bir bayt dizisini mevcut akışa yazar ve bu akıştaki konumu yazılan bayt sayısı kadar ilerletir. |
| [writeByte(byte value)](#writeByte-byte-) | Akıştaki mevcut konuma bir bayt yazar ve konumu bir bayt ilerletir. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | İçerilen verileri başka bir  StreamContainer 'a kopyalar. |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | İçerilen verileri başka bir  StreamContainer 'a kopyalar. |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


StreamContainer sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Akış. |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


StreamContainer sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Veri akışı. |
| disposeStream | boolean | true olarak ayarlanırsa akış, kapsayıcı atıldığında serbest bırakılır. |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| disposeStream | boolean |  |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Sıralı okuma sırasında okuma ve yazma bayt sayısını belirtir.

### canRead() {#canRead--}
```
public boolean canRead()
```


Akışın okuma desteği olup olmadığını gösteren bir değer alır.

Değer:  true  akış okuma destekliyorsa; aksi takdirde,  false .

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Akışın konumlandırma desteği olup olmadığını gösteren bir değer alır.

Değer:  true  akış arama destekliyorsa; aksi takdirde,  false .

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Akışın yazma desteği olup olmadığını gösteren bir değer alır.

Değer:  true  akış yazma destekliyorsa; aksi takdirde,  false .

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. Bu yöntem sadece dispose yöntemini çağırır.

### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| startPosition | long |  |
| disposeStream | boolean |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### dispose() {#dispose--}
```
public final void dispose()
```


Mevcut örneği serbest bırakır.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```


Bu akış için tüm arabellekleri temizler ve tamponlanmış verilerin alt cihazına yazılmasını sağlar.

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Bu örneğin atılmış olup olmadığını gösteren bir değer alır.

**Returns:**
boolean -  true  ise disposed; aksi takdirde,  false .
### getLength() {#getLength--}
```
public long getLength()
```


Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer,  System.IO.Stream.Length  değerinden, StreamContainer yapıcısına geçirilen başlangıç akış konumu kadar daha küçüktür.

Değer: Akış uzunluğu.

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


Akış içindeki geçerli konumu alır veya ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder.

Değer: Geçerli akış konumu.

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


Veri akışını alır.

Değer: Veri akışı.

**Returns:**
java.io.InputStream
### getStream_internalized() {#getStream-internalized--}
```
public System.IO.Stream getStream_internalized()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Senkronize edilmiş kaynağa erişimi senkronize etmek için kullanılabilecek bir nesneyi alır.

Değer: Eşzamanlı kaynağa erişimi senkronize etmek için kullanılabilecek nesne.

**Returns:**
java.lang.Object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Bu akışın kapatıldığında serbest bırakılıp bırakılmadığını gösteren değeri alır.

Değer: Akış kapatıldığında serbest bırakıldıysa  true , aksi takdirde  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Belirtilen bayt tamponunu doldurmak için baytları okur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | byte[] | Doldurulacak baytlar. |

**Returns:**
int - Okunan bayt sayısı. Bu değer, akışta yeterli bayt yoksa tampondaki bayt sayısından daha az olabilir.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Mevcut akıştan bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arabellek | byte[] | Bir bayt dizisi. Bu yöntem döndüğünde, tampon belirtilen bayt dizisini içerir ve  offset  ile ( offset  +  count  - 1) arasındaki değerler, geçerli kaynaktan okunan baytlarla değiştirilir. |
| offset | int | Geçerli akıştan okunan verilerin saklanmaya başlanacağı  buffer  içindeki sıfır tabanlı bayt ofseti. |
| count | int | Geçerli akıştan okunacak maksimum bayt sayısı. |

**Returns:**
int - Tampona okunan toplam bayt sayısı. İstenen bayt sayısı mevcut değilse bu değer daha az olabilir veya akışın sonuna gelinmişse sıfır (0) olabilir.
### readByte() {#readByte--}
```
public int readByte()
```


Akıştan bir bayt okur ve konumu bir bayt ilerletir; akışın sonundaysa -1 döndürür.

**Returns:**
int - Unsigned bayt, Int32'ye dönüştürülmüş hali veya akışın sonunda ise -1.
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu  ReadWriteBytesCount  ve akış  Length  değeri kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Verilerin kaydedileceği akış. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). Akış  Length  değeri kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Verilerin kaydedileceği akış. |
| bufferSize | int | Tampon. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Akışın verilerini belirtilen akışa kaydeder (kopyalar).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Verilerin kaydedileceği akış. |
| bufferSize | int | Tampon boyutu. Varsayılan olarak  ReadWriteBytesCount  değeri kullanılır. |
| length | long | Kopyalanacak akış veri uzunluğu. Varsayılan olarak uzunluk  Length  değerine ayarlanmıştır. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu  ReadWriteBytesCount  ve akış  Length  değeri kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Akış verilerinin kaydedileceği dosya yolu. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Akışın verilerini belirtilen akışa kaydeder (kopyalar). Akış  Length  değeri kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Akış verilerinin kaydedileceği dosya yolu. |
| bufferSize | int | Tampon boyutu. Varsayılan olarak  ReadWriteBytesCount  değeri kullanılır. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Akışın verilerini belirtilen akışa kaydeder (kopyalar).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Akış verilerinin kaydedileceği dosya yolu. |
| bufferSize | int | Tampon boyutu. Varsayılan olarak  ReadWriteBytesCount  değeri kullanılır. |
| length | long | Kopyalanacak akış veri uzunluğu. Varsayılan olarak uzunluk  Length  değerine ayarlanmıştır. |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Mevcut akış içindeki konumu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| offset | long |   origin  parametresine göre bir bayt ofseti. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder. |
| origin | int | Yeni konumu elde etmek için kullanılan referans noktasını gösteren System.IO.SeekOrigin tipinde bir değer. |

**Returns:**
long - Mevcut akış içindeki yeni konum.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Akış konumunu akışın başına ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder.

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer,  System.IO.Stream.Length  değerinden, StreamContainer yapıcısına geçirilen başlangıç akış konumu kadar daha küçüktür.

Değer: Akış uzunluğu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Akış içindeki geçerli konumu alır veya ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder.

Değer: Geçerli akış konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Akış verilerini  byte  dizisine dönüştürür.

**Returns:**
byte[] - Akış verisinin  byte  dizisine dönüştürülmüş hali.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Akış verilerini  byte  dizisine dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | long | Baytları okumaya başlanacak konum. |
| bytesCount | long | Okunacak bayt sayısı. |

**Returns:**
byte[] - Akış verisinin  byte  dizisine dönüştürülmüş hali.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.psd.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


  com.aspose.imaging.StreamContainer  'den  System.IO.Stream 'e açık bir dönüşüm gerçekleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |

**Returns:**
com.aspose.ms.System.IO.Stream - Dönüşümün sonucu.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Belirtilen tüm baytları akışa yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | byte[] | Yazılacak baytlar. |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Bir bayt dizisini mevcut akışa yazar ve bu akıştaki konumu yazılan bayt sayısı kadar ilerletir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arabellek | byte[] | Bir bayt dizisi. Bu yöntem,  count  baytı  buffer  dizisinden mevcut akışa kopyalar. |
| offset | int | Mevcut akışa bayt kopyalamaya başlanacak  buffer  içindeki sıfır tabanlı bayt ofseti. |
| count | int | Mevcut akışa yazılacak bayt sayısı. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Akıştaki mevcut konuma bir bayt yazar ve konumu bir bayt ilerletir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | Akışa yazılacak bayt. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


İçerilen verileri başka bir  StreamContainer 'a kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kopyalanacak akış konteyneri. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


İçerilen verileri başka bir  StreamContainer 'a kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kopyalanacak akış konteyneri. |
| length | long | Yazılacak bayt sayısı. |

