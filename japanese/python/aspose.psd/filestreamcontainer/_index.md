---
title: "FileStreamContainer クラス"
type: docs
weight: 1270
url: /ja/python-net/aspose.psd/filestreamcontainer/
---

**Summary:** Helper for file stream processing.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FileStreamContainer

**Inheritance:** StreamContainer

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | シーケンシャルに読み取る際の読み取りおよび書き込みバイト数を指定します。 |
| can_read | bool | r | ストリームが読み取りをサポートしているかどうかを示す値を取得します。 |
| can_seek | bool | r | ストリームがシークをサポートしているかどうかを示す値を取得します。 |
| can_write | bool | r | ストリームが書き込みをサポートしているかどうかを示す値を取得します。 |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| file_path | string | r | ファイルパスを取得します。 |
| is_created | bool | r | ストリームが明示的に作成されたかどうかを示す値を取得します。 |
| is_stream_disposed_on_close | bool | r | このストリームがクローズ時に破棄されるかどうかを示す値を取得します。 |
| is_temporal | bool | r/w | ストリームが一時的かどうかを示す値を取得または設定します。 |
| 長さを取得または設定します。 | long | r/w | ストリームの長さ（バイト単位）を取得または設定します。この値は、StreamContainer コンストラクタに渡された開始ストリーム位置によって減算されたものより小さいです。 |
| position | long | r/w | ストリーム内の現在位置を取得または設定します。この値は、StreamContainer コンストラクタに渡された開始ストリーム位置からのオフセットを表します。 |
| ストリーム | _io.BufferedRandom | r | データストリームを取得します。 |
| sync_root | object | r | 同期されたリソースへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [create_file_stream(file_location, is_temporal)](#create_file_stream_file_location_is_temporal_1) | 新しいファイルストリームを作成します。 |
| flush() | このストリームのすべてのバッファをクリアし、バッファされたデータを基礎となるデバイスに書き込みます。 |
| [open_file_stream(file_location)](#open_file_stream_file_location_2) | 既存のファイルストリームを開きます。ファイルストリームが存在しない場合、適切な例外がスローされます。 |
| [read(buffer, offset, count)](#read_buffer_offset_count_3) | 現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。 |
| [read(bytes)](#read_bytes_4) | 指定されたバイトバッファを埋めるためにバイトを読み取ります。 |
| [read_byte()](#read_byte__5) | ストリームから 1 バイトを読み取り、ストリーム内の位置を 1 バイト進めます。ストリームの末尾に達した場合は -1 を返します。 |
| [save(destination_stream)](#save_destination_stream_6) | ストリームのデータを指定されたストリームに保存（コピー）します。デフォルトのバッファサイズ [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) とストリーム [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) の値を使用します。 |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_7) | ストリームのすべてのデータを指定されたストリームに保存（コピー）します。ストリーム [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) の値を使用します。 |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_8) | ストリームのデータを指定されたストリームに保存（コピー）します。 |
| [save(file_path)](#save_file_path_9) | ストリームのデータを指定されたストリームに保存（コピー）します。デフォルトのバッファサイズ [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) とストリーム [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) の値を使用します。 |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_10) | 指定されたストリームにストリームのデータを保存（コピー）します。ストリームの [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 値を使用します。 |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_11) | ストリームのデータを指定されたストリームに保存（コピー）します。 |
| [seek(offset, origin)](#seek_offset_origin_12) | 現在のストリーム内の位置を設定します。 |
| seek_begin() | ストリームの位置をストリームの先頭に設定します。この値は、StreamContainer コンストラクタに渡された開始ストリーム位置からのオフセットを表します。 |
| [to_bytes()](#to_bytes__13) | ストリームデータを int 配列に変換します。 |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_14) | ストリームデータを int 配列に変換します。 |
| [write(buffer, offset, count)](#write_buffer_offset_count_15) | バイトのシーケンスを書き込み、書き込まれたバイト数だけ現在のストリーム内の位置を進めます。 |
| [write(bytes)](#write_bytes_16) | 指定されたすべてのバイトを書き込みます。 |
| [write_byte(value)](#write_byte_value_17) | ストリームの現在位置にバイトを書き込み、ストリーム内の位置を 1 バイト進めます。 |
| [write_to(stream_container)](#write_to_stream_container_18) | 含まれるデータを別の [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) にコピーします。 |
| [write_to(stream_container, length)](#write_to_stream_container_length_19) | 含まれるデータを別の [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) にコピーします。 |


### Method: create_file_stream(file_location, is_temporal)  [static] {#create_file_stream_file_location_is_temporal_1}


```
 create_file_stream(file_location, is_temporal) 
```

新しいファイルストリームを作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_location | string | ファイルの場所です。 |
| is_temporal | bool | <c>true</c> に設定すると、ファイルストリームコンテナは一時的になります。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer) | ファイルストリームコンテナです。 |


### Method: open_file_stream(file_location)  [static] {#open_file_stream_file_location_2}


```
 open_file_stream(file_location) 
```

既存のファイルストリームを開きます。ファイルストリームが存在しない場合、適切な例外がスローされます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_location | string | ファイルの場所です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer) | ファイルストリームコンテナです。 |


### Method: read(buffer, offset, count) {#read_buffer_offset_count_3}


```
 read(buffer, offset, count) 
```

現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| バッファ | byte | バイト配列です。このメソッドが返ると、バッファには指定されたバイト配列が含まれ、<paramref name="offset" /> から (<paramref name="offset" /> + <paramref name="count" /> - 1) までの値が現在のソースから読み取られたバイトで置き換えられます。 |
| offset | int | <paramref name="buffer" /> 内の、現在のストリームから読み取ったデータの格納を開始するゼロベースのバイトオフセットです。 |
| count | int | 現在のストリームから読み取る最大バイト数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | バッファに読み取られたバイト総数です。要求されたバイト数より少ない場合があります（そのバイト数が現在利用できない場合）、またはストリームの終端に達した場合は 0（ゼロ）になります。 |


### Method: read(bytes) {#read_bytes_4}


```
 read(bytes) 
```

指定されたバイトバッファを埋めるためにバイトを読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| バイト | byte | 埋めるバイトです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 読み取られたバイト数です。ストリームに十分なバイトがない場合、この値はバッファ内のバイト数より少なくなることがあります。 |


### Method: read_byte() {#read_byte__5}


```
 read_byte() 
```

ストリームから 1 バイトを読み取り、ストリーム内の位置を 1 バイト進めます。ストリームの末尾に達した場合は -1 を返します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | Int32 にキャストされた符号なしバイト、またはストリームの終端に達した場合は -1 です。 |


### Method: save(destination_stream) {#save_destination_stream_6}


```
 save(destination_stream) 
```

ストリームのデータを指定されたストリームに保存（コピー）します。デフォルトのバッファサイズ [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) とストリーム [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) の値を使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | データを保存するストリームです。 |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_7}


```
 save(destination_stream, buffer_size) 
```

ストリームのすべてのデータを指定されたストリームに保存（コピー）します。ストリーム [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) の値を使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | データを保存するストリームです。 |
| buffer_size | int | バッファです。 |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_8}


```
 save(destination_stream, buffer_size, length) 
```

ストリームのデータを指定されたストリームに保存（コピー）します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | データを保存するストリームです。 |
| buffer_size | int | バッファサイズです。デフォルトでは [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) の値が使用されます。 |
| length | long | コピーするストリームデータの長さです。デフォルトでは、長さは [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) の値に設定されています。 |

### Method: save(file_path) {#save_file_path_9}


```
 save(file_path) 
```

ストリームのデータを指定されたストリームに保存（コピー）します。デフォルトのバッファサイズ [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) とストリーム [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) の値を使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | ストリームデータを保存するファイルパスです。 |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_10}


```
 save(file_path, buffer_size) 
```

指定されたストリームにストリームのデータを保存（コピー）します。ストリームの [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) 値を使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | ストリームデータを保存するファイルパスです。 |
| buffer_size | int | バッファサイズです。デフォルトでは [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) の値が使用されます。 |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_11}


```
 save(file_path, buffer_size, length) 
```

ストリームのデータを指定されたストリームに保存（コピー）します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | ストリームデータを保存するファイルパスです。 |
| buffer_size | int | バッファサイズです。デフォルトでは [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) の値が使用されます。 |
| length | long | コピーするストリームデータの長さです。デフォルトでは、長さは [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) の値に設定されています。 |

### Method: seek(offset, origin) {#seek_offset_origin_12}


```
 seek(offset, origin) 
```

現在のストリーム内の位置を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| offset | long | <paramref name="origin" /> パラメーターに対するバイトオフセットです。この値は、StreamContainer コンストラクターで渡された開始ストリーム位置からのオフセットを表します。 |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | 新しい位置を取得するために使用される基準点を示す SeekOrigin 型の値です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| long | 現在のストリーム内の新しい位置です。 |


### Method: to_bytes() {#to_bytes__13}


```
 to_bytes() 
```

ストリームデータを int 配列に変換します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| byte | int 配列に変換されたストリームデータです。 |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_14}


```
 to_bytes(position, bytes_count) 
```

ストリームデータを int 配列に変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | バイトの読み取りを開始する位置です。 |
| bytes_count | long | 読み取るバイト数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| byte | int 配列に変換されたストリームデータです。 |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_15}


```
 write(buffer, offset, count) 
```

バイトのシーケンスを書き込み、書き込まれたバイト数だけ現在のストリーム内の位置を進めます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| バッファ | byte | バイト配列です。このメソッドは <paramref name="count" /> バイトを <paramref name="buffer" /> から現在のストリームへコピーします。 |
| offset | int | 現在のストリームへバイトのコピーを開始する <paramref name="buffer" /> 内のゼロベースのバイトオフセットです。 |
| count | int | 現在のストリームに書き込むバイト数です。 |

### Method: write(bytes) {#write_bytes_16}


```
 write(bytes) 
```

指定されたすべてのバイトを書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| バイト | byte | 書き込むバイトです。 |

### Method: write_byte(value) {#write_byte_value_17}


```
 write_byte(value) 
```

ストリームの現在位置にバイトを書き込み、ストリーム内の位置を 1 バイト進めます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 値 | byte | ストリームに書き込むバイトです。 |

### Method: write_to(stream_container) {#write_to_stream_container_18}


```
 write_to(stream_container) 
```

含まれるデータを別の [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) にコピーします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | コピー先のストリームコンテナです。 |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_19}


```
 write_to(stream_container, length) 
```

含まれるデータを別の [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) にコピーします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | コピー先のストリームコンテナです。 |
| 長さを取得または設定します。 | long | 書き込むバイト数です。 |

