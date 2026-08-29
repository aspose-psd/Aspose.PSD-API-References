---
title: "FileStreamContainer Sınıfı"
type: docs
weight: 1270
url: /tr/python-net/aspose.psd/filestreamcontainer/
---

**Summary:** Helper for file stream processing.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FileStreamContainer

**Inheritance:** StreamContainer

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Sıralı okuma sırasında okuma ve yazma bayt sayısını belirtir. |
| can_read | bool | r | Akışın okuma desteği olup olmadığını gösteren bir değer alır. |
| can_seek | bool | r | Akışın konumlandırma desteği olup olmadığını gösteren bir değer alır. |
| can_write | bool | r | Akışın yazma desteği olup olmadığını gösteren bir değer alır. |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| file_path | string | r | Dosya yolunu alır. |
| is_created | bool | r | Akışın açıkça oluşturulup oluşturulmadığını gösteren bir değeri alır. |
| is_stream_disposed_on_close | bool | r | Bu akışın kapatıldığında serbest bırakılıp bırakılmadığını gösteren bir değer alır. |
| is_temporal | bool | r/w | Akışın geçici olup olmadığını gösteren bir değeri alır veya ayarlar. |
| uzunluk | long | r/w | Akış uzunluğunu bayt cinsinden alır veya ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumu tarafından belirlenen değerden küçüktür. |
| konum | long | r/w | Akış içindeki geçerli konumu alır veya ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan offset'i temsil eder. |
| akış | _io.BufferedRandom | r | Veri akışını alır. |
| sync_root | object | r | Eşzamanlı kaynağa erişimi senkronize etmek için kullanılabilecek bir nesne alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_file_stream(file_location, is_temporal)](#create_file_stream_file_location_is_temporal_1) | Yeni bir dosya akışı oluşturur. |
| flush() | Bu akış için tüm tamponları temizler ve tamponlanmış verilerin alt cihazına yazılmasını sağlar. |
| [open_file_stream(file_location)](#open_file_stream_file_location_2) | Mevcut bir dosya akışını açar. Dosya akışı mevcut değilse uygun istisna fırlatılır. |
| [read(buffer, offset, count)](#read_buffer_offset_count_3) | Geçerli akıştan bir bayt dizisi okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir. |
| [read(bytes)](#read_bytes_4) | Belirtilen bayt tamponunu doldurmak için baytları okur. |
| [read_byte()](#read_byte__5) | Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir; akışın sonunda ise -1 döndürür. |
| [save(destination_stream)](#save_destination_stream_6) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) ve akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır. |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_7) | Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). Akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır. |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_8) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [save(file_path)](#save_file_path_9) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) ve akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır. |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_10) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). Akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değerini kullanır. |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_11) | Akışın verilerini belirtilen akışa kaydeder (kopyalar). |
| [seek(offset, origin)](#seek_offset_origin_12) | Mevcut akış içindeki konumu ayarlar. |
| seek_begin() | Akış konumunu akışın başlangıcına ayarlar. Bu değer, StreamContainer yapıcısına geçirilen başlangıç akış konumundan ofseti temsil eder. |
| [to_bytes()](#to_bytes__13) | Akış verilerini int dizisine dönüştürür. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_14) | Akış verilerini int dizisine dönüştürür. |
| [write(buffer, offset, count)](#write_buffer_offset_count_15) | Bir bayt dizisini mevcut akışa yazar ve bu akıştaki mevcut konumu yazılan bayt sayısı kadar ilerletir. |
| [write(bytes)](#write_bytes_16) | Belirtilen tüm baytları akışa yazar. |
| [write_byte(value)](#write_byte_value_17) | Akıştaki mevcut konuma bir bayt yazar ve konumu bir bayt ilerletir. |
| [write_to(stream_container)](#write_to_stream_container_18) | İçerilen verileri başka bir [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) içine kopyalar. |
| [write_to(stream_container, length)](#write_to_stream_container_length_19) | İçerilen verileri başka bir [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) içine kopyalar. |


### Method: create_file_stream(file_location, is_temporal)  [static] {#create_file_stream_file_location_is_temporal_1}


```
 create_file_stream(file_location, is_temporal) 
```

Yeni bir dosya akışı oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_location | string | Dosya konumu. |
| is_temporal | bool | Eğer <c>true</c> olarak ayarlanırsa dosya akışı konteyneri geçicidir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer) | Dosya akışı konteyneri. |


### Method: open_file_stream(file_location)  [static] {#open_file_stream_file_location_2}


```
 open_file_stream(file_location) 
```

Mevcut bir dosya akışını açar. Dosya akışı mevcut değilse uygun istisna fırlatılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_location | string | Dosya konumu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer) | Dosya akışı konteyneri. |


### Method: read(buffer, offset, count) {#read_buffer_offset_count_3}


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


### Method: read(bytes) {#read_bytes_4}


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


### Method: read_byte() {#read_byte__5}


```
 read_byte() 
```

Akıştan bir bayt okur ve akış içindeki konumu bir bayt ilerletir; akışın sonunda ise -1 döndürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Unsigned baytın Int32'ye dönüştürülmüş hali, ya da akışın sonunda ise -1. |


### Method: save(destination_stream) {#save_destination_stream_6}


```
 save(destination_stream) 
```

Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) ve akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Verilerin kaydedileceği akış. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_7}


```
 save(destination_stream, buffer_size) 
```

Akışın tüm verilerini belirtilen akışa kaydeder (kopyalar). Akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Verilerin kaydedileceği akış. |
| buffer_size | int | Tampon. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_8}


```
 save(destination_stream, buffer_size, length) 
```

Akışın verilerini belirtilen akışa kaydeder (kopyalar).

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Verilerin kaydedileceği akış. |
| buffer_size | int | Arabellek boyutu. Varsayılan olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır. |
| length | long | Kopyalanacak akış veri uzunluğu. Varsayılan olarak uzunluk, [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri olarak ayarlanır. |

### Method: save(file_path) {#save_file_path_9}


```
 save(file_path) 
```

Akışın verilerini belirtilen akışa kaydeder (kopyalar). Varsayılan tampon boyutu olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) ve akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Akış verisinin kaydedileceği dosya yolu. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_10}


```
 save(file_path, buffer_size) 
```

Akışın verilerini belirtilen akışa kaydeder (kopyalar). Akış [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) değerini kullanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Akış verisinin kaydedileceği dosya yolu. |
| buffer_size | int | Arabellek boyutu. Varsayılan olarak [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) değeri kullanılır. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_11}


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

### Method: seek(offset, origin) {#seek_offset_origin_12}


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


### Method: to_bytes() {#to_bytes__13}


```
 to_bytes() 
```

Akış verilerini int dizisine dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | int dizisine dönüştürülmüş akış verisi. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_14}


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


### Method: write(buffer, offset, count) {#write_buffer_offset_count_15}


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

### Method: write(bytes) {#write_bytes_16}


```
 write(bytes) 
```

Belirtilen tüm baytları akışa yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bayt | byte | Yazılacak baytlar. |

### Method: write_byte(value) {#write_byte_value_17}


```
 write_byte(value) 
```

Akıştaki mevcut konuma bir bayt yazar ve konumu bir bayt ilerletir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| değer | byte | Akışa yazılacak bayt. |

### Method: write_to(stream_container) {#write_to_stream_container_18}


```
 write_to(stream_container) 
```

İçerilen verileri başka bir [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) içine kopyalar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kopyalanacak akış konteyneri. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_19}


```
 write_to(stream_container, length) 
```

İçerilen verileri başka bir [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) içine kopyalar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kopyalanacak akış konteyneri. |
| uzunluk | long | Yazılacak bayt sayısı. |

