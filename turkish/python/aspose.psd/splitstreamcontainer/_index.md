---
title: "SplitStreamContainer Sınıfı"
type: docs
weight: 4220
url: /tr/python-net/aspose.psd/splitstreamcontainer/
---

**Summary:** Represents split stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SplitStreamContainer

**Inheritance:** StreamContainer

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [SplitStreamContainer(stream)](#SplitStreamContainer_stream_1) | Yeni bir [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) sınıfının örneğini başlatır. |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_2) | Yeni bir [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) sınıfının örneğini başlatır. |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_3) | Yeni bir [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Sıralı okuma sırasında okuma ve yazma bayt sayısını belirtir. |
| can_read | bool | r | Akışın okuma desteği olup olmadığını gösteren bir değer alır. |
| can_seek | bool | r | Akışın konumlandırma desteği olup olmadığını gösteren bir değer alır. |
| can_write | bool | r | Akışın yazma desteği olup olmadığını gösteren bir değer alır. |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| is_stream_disposed_on_close | bool | r | Bu akışın kapatıldığında serbest bırakılıp bırakılmadığını gösteren bir değer alır. |
| uzunluk | long | r/w | Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumu tarafından belirlenen değerden küçüktür. |
| konum | long | r/w | Akış içindeki geçerli konumu alır veya ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan offset'i temsil eder. |
| akış | _io.BufferedRandom | r | Veri akışını alır. |
| sync_root | object | r | Eşzamanlı kaynağa erişimi senkronize etmek için kullanılabilecek bir nesne alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| flush() | Bu akış için tüm tamponları temizler ve tamponlanmış verilerin alt cihazına yazılmasını sağlar. |
| [insert(position, stream, dispose_stream)](#insert_position_stream_dispose_stream_1) | Akış konteynerini belirtilen konuma ekler. |
| [read(buffer, offset, count)](#read_buffer_offset_count_2) | Geçerli akıştan bir bayt dizisi okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir. |
| [read(bytes)](#read_bytes_3) | Belirtilen bayt tamponunu doldurmak için baytları okur. |
| [read_byte()](#read_byte__4) | Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir; akışın sonunda ise -1 döndürür. |
| [save(destination_stream)](#save_destination_stream_5) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) ve akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır. |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_6) | Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). Akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır. |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_7) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [save(file_path)](#save_file_path_8) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) ve akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır. |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_9) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değerini kullanır. |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_10) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [seek(offset, origin)](#seek_offset_origin_11) | Mevcut akış içindeki konumu ayarlar. |
| seek_begin() | Akış konumunu akışın başlangıcına ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder. |
| [to_bytes()](#to_bytes__12) | Akış verilerini int dizisine dönüştürür. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_13) | Akış verilerini int dizisine dönüştürür. |
| [write(buffer, offset, count)](#write_buffer_offset_count_14) | Bir bayt dizisini mevcut akışa yazar ve bu akıştaki mevcut konumu yazılan bayt sayısı kadar ilerletir. |
| [write(bytes)](#write_bytes_15) | Belirtilen tüm baytları akışa yazar. |
| [write_byte(value)](#write_byte_value_16) | Akıştaki mevcut konuma bir bayt yazar ve konumu bir bayt ilerletir. |
| [write_to(stream_container)](#write_to_stream_container_17) | İçerilen verileri başka bir [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) içine kopyalar. |
| [write_to(stream_container, length)](#write_to_stream_container_length_18) | İçerilen verileri başka bir [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) içine kopyalar. |


### Constructor: SplitStreamContainer(stream) {#SplitStreamContainer_stream_1}


```
 SplitStreamContainer(stream) 
```

Yeni bir [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) sınıfının örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_2}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Yeni bir [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) sınıfının örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Veri akışı. |
| dispose_stream | bool | Eğer <c>true</c> olarak ayarlanırsa, konteyner atıldığında akış da serbest bırakılır. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_3}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Yeni bir [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) sınıfının örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Veri akışı. |
| dispose_stream | bool | Eğer <c>true</c> olarak ayarlanırsa, konteyner atıldığında akış da serbest bırakılır. |

### Method: insert(position, stream, dispose_stream) {#insert_position_stream_dispose_stream_1}


```
 insert(position, stream, dispose_stream) 
```

Akış konteynerini belirtilen konuma ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | int | Eklenecek konum. |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Eklenecek akış konteyneri. |
| dispose_stream | bool | Eğer <c>true</c> olarak ayarlanırsa akışı serbest bırakır. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_2}


```
 read(buffer, offset, count) 
```

Geçerli akıştan bir bayt dizisi okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| arabellek | byte | Bir bayt dizisi. Bu yöntem döndüğünde, tampon belirtilen bayt dizisini içerir ve <paramref name="offset" /> ile (<paramref name="offset" /> + <paramref name="count" /> - 1) arasındaki değerler mevcut kaynaktan okunan baytlarla değiştirilir. |
| offset | int | <paramref name="buffer" /> içinde, mevcut akıştan okunan verilerin depolanmaya başlanacağı sıfır tabanlı bayt ofseti. |
| sayım | int | Mevcut akıştan okunacak azami bayt sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Tampona okunan toplam bayt sayısı. Bu, istenen bayt sayısından daha az olabilir eğer o kadar bayt mevcut değilse, ya da akışın sonuna gelinmişse sıfır (0) olabilir. |


### Method: read(bytes) {#read_bytes_3}


```
 read(bytes) 
```

Belirtilen bayt tamponunu doldurmak için baytları okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bayt | byte | Doldurulacak baytlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Okunan bayt sayısı. Bu değer, akışta yeterli bayt yoksa tampondaki bayt sayısından daha az olabilir. |


### Method: read_byte() {#read_byte__4}


```
 read_byte() 
```

Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir; akışın sonunda ise -1 döndürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Unsigned baytın Int32'ye dönüştürülmüş hali, ya da akışın sonunda ise -1. |


### Method: save(destination_stream) {#save_destination_stream_5}


```
 save(destination_stream) 
```

Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) ve akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Verilerin kaydedileceği akış. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_6}


```
 save(destination_stream, buffer_size) 
```

Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). Akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Verilerin kaydedileceği akış. |
| buffer_size | int | Tampon. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_7}


```
 save(destination_stream, buffer_size, length) 
```

Akışın verilerini belirtilen akışa kaydeder (kopyalar).

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Verilerin kaydedileceği akış. |
| buffer_size | int | Tampon boyutu. Varsayılan olarak ReadWriteBytesCount değeri kullanılır. |
| length | long | Kopyalanacak akış veri uzunluğu. Varsayılan olarak uzunluk, [SplitStreamContainer.length](/psd/python-net/aspose.psd/splitstreamcontainer/) değeri olarak ayarlanır. |

### Method: save(file_path) {#save_file_path_8}


```
 save(file_path) 
```

Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) ve akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Akış verisinin kaydedileceği dosya yolu. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_9}


```
 save(file_path, buffer_size) 
```

Akışın verilerini belirtilen akışa kaydeder (kopyalar). Akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değerini kullanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Akış verisinin kaydedileceği dosya yolu. |
| buffer_size | int | Arabellek boyutu. Varsayılan olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_10}


```
 save(file_path, buffer_size, length) 
```

Akışın verilerini belirtilen akışa kaydeder (kopyalar).

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Akış verisinin kaydedileceği dosya yolu. |
| buffer_size | int | Arabellek boyutu. Varsayılan olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır. |
| length | long | Kopyalanacak akış veri uzunluğu. Varsayılan olarak uzunluk, [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri olarak ayarlanır. |

### Method: seek(offset, origin) {#seek_offset_origin_11}


```
 seek(offset, origin) 
```

Mevcut akış içindeki konumu ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| offset | long | <paramref name=\"origin\" /> parametresine göre bir bayt ofseti. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder. |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | Yeni konumu elde etmek için kullanılan referans noktasını gösteren SeekOrigin tipinde bir değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| long | Mevcut akış içindeki yeni konum. |


### Method: to_bytes() {#to_bytes__12}


```
 to_bytes() 
```

Akış verilerini int dizisine dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | int dizisine dönüştürülmüş akış verisi. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_13}


```
 to_bytes(position, bytes_count) 
```

Akış verilerini int dizisine dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| konum | long | Baytların okunmaya başlanacağı konum. |
| bytes_count | long | Okunacak bayt sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | int dizisine dönüştürülmüş akış verisi. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_14}


```
 write(buffer, offset, count) 
```

Bir bayt dizisini mevcut akışa yazar ve bu akıştaki mevcut konumu yazılan bayt sayısı kadar ilerletir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| arabellek | byte | Bayt dizisi. Bu yöntem <paramref name=\"count\" /> baytı <paramref name=\"buffer\" />'dan mevcut akışa kopyalar. |
| offset | int | Mevcut akışa bayt kopyalamaya başlanacak <paramref name=\"buffer\" /> içindeki sıfır tabanlı bayt ofseti. |
| sayım | int | Mevcut akışa yazılacak bayt sayısı. |

### Method: write(bytes) {#write_bytes_15}


```
 write(bytes) 
```

Belirtilen tüm baytları akışa yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bayt | byte | Yazılacak baytlar. |

### Method: write_byte(value) {#write_byte_value_16}


```
 write_byte(value) 
```

Akıştaki mevcut konuma bir bayt yazar ve konumu bir bayt ilerletir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| değer | byte | Akışa yazılacak bayt. |

### Method: write_to(stream_container) {#write_to_stream_container_17}


```
 write_to(stream_container) 
```

İçerilen verileri başka bir [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) içine kopyalar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kopyalanacak akış konteyneri. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_18}


```
 write_to(stream_container, length) 
```

İçerilen verileri başka bir [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) içine kopyalar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kopyalanacak akış konteyneri. |
| uzunluk | long | Yazılacak bayt sayısı. |

