---
title: "Kelas StreamContainer"
type: docs
weight: 4230
url: /id/python-net/aspose.psd/streamcontainer/
---

**Summary:** Represents stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StreamContainer

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [StreamContainer(stream)](#StreamContainer_stream_1) | Menginisialisasi sebuah instance baru dari kelas [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [StreamContainer(stream, dispose_stream)](#StreamContainer_stream_dispose_stream_2) | Menginisialisasi sebuah instance baru dari kelas [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Menentukan jumlah byte baca dan tulis saat membaca secara berurutan. |
| can_read | bool | r | Mendapatkan nilai yang menunjukkan apakah aliran mendukung pembacaan. |
| can_seek | bool | r | Mendapatkan nilai yang menunjukkan apakah aliran mendukung pencarian. |
| can_write | bool | r | Mendapatkan nilai yang menunjukkan apakah aliran mendukung penulisan. |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| is_stream_disposed_on_close | bool | r | Mendapatkan nilai yang menunjukkan apakah aliran ini dibuang saat ditutup. |
| panjang | long | r/w | Mendapatkan atau mengatur panjang aliran dalam byte. Nilai ini lebih kecil dari  oleh posisi aliran awal yang diberikan pada konstruktor StreamContainer. |
| posisi | long | r/w | Mendapatkan atau mengatur posisi saat ini dalam aliran. Nilai ini mewakili offset dari posisi aliran awal yang diberikan pada konstruktor StreamContainer. |
| aliran | _io.BufferedRandom | r | Mendapatkan aliran data. |
| sync_root | object | r | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke sumber daya yang disinkronkan. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| flush() | Mengosongkan semua buffer untuk aliran ini dan menyebabkan data yang di-buffer ditulis ke perangkat dasar. |
| [read(buffer, offset, count)](#read_buffer_offset_count_1) | Membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran sebesar jumlah byte yang dibaca. |
| [read(bytes)](#read_bytes_2) | Membaca byte untuk mengisi buffer byte yang ditentukan. |
| [read_byte()](#read_byte__3) | Membaca satu byte dari aliran dan memajukan posisi dalam aliran satu byte, atau mengembalikan -1 jika berada di akhir aliran. |
| [save(destination_stream)](#save_destination_stream_4) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) dan nilai [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) aliran. |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_5) | Menyimpan (menyalin) semua data aliran ke aliran yang ditentukan. Menggunakan nilai [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) aliran. |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_6) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| [save(file_path)](#save_file_path_7) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) dan nilai [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) aliran. |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_8) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan nilai aliran [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_9) | Menyimpan (menyalin) data aliran ke aliran yang ditentukan. |
| [seek(offset, origin)](#seek_offset_origin_10) | Menetapkan posisi dalam aliran saat ini. |
| seek_begin() | Menetapkan posisi aliran ke awal aliran. Nilai ini mewakili offset dari posisi aliran awal yang diberikan dalam konstruktor StreamContainer. |
| [to_bytes()](#to_bytes__11) | Mengonversi data aliran menjadi array int. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_12) | Mengonversi data aliran menjadi array int. |
| [write(buffer, offset, count)](#write_buffer_offset_count_13) | Menulis urutan byte ke aliran saat ini dan memajukan posisi saat ini dalam aliran ini sebesar jumlah byte yang ditulis. |
| [write(bytes)](#write_bytes_14) | Menulis semua byte yang ditentukan ke aliran. |
| [write_byte(value)](#write_byte_value_15) | Menulis satu byte ke posisi saat ini dalam aliran dan memajukan posisi dalam aliran sebesar satu byte. |
| [write_to(stream_container)](#write_to_stream_container_16) | Mengopi data yang terkandung ke [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) lain. |
| [write_to(stream_container, length)](#write_to_stream_container_length_17) | Mengopi data yang terkandung ke [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) lain. |


### Constructor: StreamContainer(stream) {#StreamContainer_stream_1}


```
 StreamContainer(stream) 
```

Menginisialisasi sebuah instance baru dari kelas [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran. |

### Constructor: StreamContainer(stream, dispose_stream) {#StreamContainer_stream_dispose_stream_2}


```
 StreamContainer(stream, dispose_stream) 
```

Menginisialisasi sebuah instance baru dari kelas [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran data. |
| dispose_stream | bool | Jika diatur ke <c>true</c> aliran akan dibuang ketika kontainer dibuang. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_1}


```
 read(buffer, offset, count) 
```

Membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran sebesar jumlah byte yang dibaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| buffer | byte | Array byte. Ketika metode ini mengembalikan, buffer berisi array byte yang ditentukan dengan nilai antara <paramref name="offset" /> dan (<paramref name="offset" /> + <paramref name="count" /> - 1) digantikan oleh byte yang dibaca dari sumber saat ini. |
| offset | int | Offset byte berbasis nol dalam <paramref name="buffer" /> di mana mulai menyimpan data yang dibaca dari aliran saat ini. |
| jumlah | int | Jumlah maksimum byte yang akan dibaca dari aliran saat ini. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Total jumlah byte yang dibaca ke dalam buffer. Ini dapat lebih sedikit daripada jumlah byte yang diminta jika byte sebanyak itu tidak tersedia saat ini, atau nol (0) jika akhir aliran telah tercapai. |


### Method: read(bytes) {#read_bytes_2}


```
 read(bytes) 
```

Membaca byte untuk mengisi buffer byte yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| byte | byte | Byte yang akan diisi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Jumlah byte yang dibaca. Nilai ini dapat lebih sedikit daripada jumlah byte dalam buffer jika tidak ada cukup byte dalam aliran. |


### Method: read_byte() {#read_byte__3}


```
 read_byte() 
```

Membaca satu byte dari aliran dan memajukan posisi dalam aliran satu byte, atau mengembalikan -1 jika berada di akhir aliran.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Byte tak bertanda yang di-cast ke Int32, atau -1 jika berada di akhir aliran. |


### Method: save(destination_stream) {#save_destination_stream_4}


```
 save(destination_stream) 
```

Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) dan nilai [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Aliran untuk menyimpan data. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_5}


```
 save(destination_stream, buffer_size) 
```

Menyimpan (menyalin) semua data aliran ke aliran yang ditentukan. Menggunakan nilai [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Aliran untuk menyimpan data. |
| buffer_size | int | Buffer. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_6}


```
 save(destination_stream, buffer_size, length) 
```

Menyimpan (menyalin) data aliran ke aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Aliran untuk menyimpan data. |
| buffer_size | int | Ukuran buffer. Secara default nilai [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) digunakan. |
| length | long | Panjang data aliran yang akan disalin. Secara default panjang diatur ke nilai [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: save(file_path) {#save_file_path_7}


```
 save(file_path) 
```

Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan ukuran buffer default [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) dan nilai [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur file untuk menyimpan data aliran. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_8}


```
 save(file_path, buffer_size) 
```

Menyimpan (menyalin) data aliran ke aliran yang ditentukan. Menggunakan nilai aliran [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur file untuk menyimpan data aliran. |
| buffer_size | int | Ukuran buffer. Secara default nilai [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) digunakan. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_9}


```
 save(file_path, buffer_size, length) 
```

Menyimpan (menyalin) data aliran ke aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur file untuk menyimpan data aliran. |
| buffer_size | int | Ukuran buffer. Secara default nilai [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) digunakan. |
| length | long | Panjang data aliran yang akan disalin. Secara default panjang diatur ke nilai [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_10}


```
 seek(offset, origin) 
```

Menetapkan posisi dalam aliran saat ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| offset | long | Offset byte relatif terhadap parameter <paramref name="origin" />. Nilai ini mewakili offset dari posisi awal aliran yang diberikan dalam konstruktor StreamContainer. |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | Nilai bertipe SeekOrigin yang menunjukkan titik referensi yang digunakan untuk memperoleh posisi baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| long | Posisi baru dalam aliran saat ini. |


### Method: to_bytes() {#to_bytes__11}


```
 to_bytes() 
```

Mengonversi data aliran menjadi array int.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Data aliran yang dikonversi menjadi array int. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_12}


```
 to_bytes(position, bytes_count) 
```

Mengonversi data aliran menjadi array int.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| posisi | long | Posisi untuk memulai membaca byte. |
| bytes_count | long | Jumlah byte yang akan dibaca. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Data aliran yang dikonversi menjadi array int. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_13}


```
 write(buffer, offset, count) 
```

Menulis urutan byte ke aliran saat ini dan memajukan posisi saat ini dalam aliran ini sebesar jumlah byte yang ditulis.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| buffer | byte | Array byte. Metode ini menyalin <paramref name="count" /> byte dari <paramref name="buffer" /> ke aliran saat ini. |
| offset | int | Offset byte berbasis nol dalam <paramref name="buffer" /> di mana penyalinan byte ke aliran saat ini dimulai. |
| jumlah | int | Jumlah byte yang akan ditulis ke aliran saat ini. |

### Method: write(bytes) {#write_bytes_14}


```
 write(bytes) 
```

Menulis semua byte yang ditentukan ke aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| byte | byte | Byte yang akan ditulis. |

### Method: write_byte(value) {#write_byte_value_15}


```
 write_byte(value) 
```

Menulis satu byte ke posisi saat ini dalam aliran dan memajukan posisi dalam aliran sebesar satu byte.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | byte | Byte yang akan ditulis ke aliran. |

### Method: write_to(stream_container) {#write_to_stream_container_16}


```
 write_to(stream_container) 
```

Mengopi data yang terkandung ke [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) lain.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran tujuan penyalinan. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_17}


```
 write_to(stream_container, length) 
```

Mengopi data yang terkandung ke [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) lain.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran tujuan penyalinan. |
| panjang | long | Jumlah byte yang akan ditulis. |

