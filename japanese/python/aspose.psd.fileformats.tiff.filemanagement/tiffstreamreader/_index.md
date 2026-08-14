---
title: "TiffStreamReader クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | 新しいインスタンスを初期化します [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) クラス。 |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | 新しいインスタンスを初期化します [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) クラス。 |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | 新しいインスタンスを初期化します [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) クラス。 |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | 新しいインスタンスを初期化します [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) クラス。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| 長さを取得または設定します。 | long | r | リーダーの長さを取得します。 |
| throw_exceptions | bool | r/w | 不正なデータ処理（ストリームの読み取りまたは書き込み）時に例外がスローされるかどうかを示す値を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | ストリームからバイト値の配列を読み取ります。 |
| [read_bytes(position, count)](#read_bytes_position_count_2) | ストリームから符号なしバイト値の配列を読み取ります。 |
| [read_double(position)](#read_double_position_3) | ストリームから単一の double 値を読み取ります。 |
| [read_double_array(position, count)](#read_double_array_position_count_4) | ストリームから double 値の配列を読み取ります。 |
| [read_float(position)](#read_float_position_5) | ストリームから単一の float 値を読み取ります。 |
| [read_float_array(position, count)](#read_float_array_position_count_6) | ストリームから float 値の配列を読み取ります。 |
| [read_rational(position)](#read_rational_position_7) | ストリームから単一の有理数の値を読み取ります。 |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | ストリームから有理数値の配列を読み取ります。 |
| [read_s_byte(position)](#read_s_byte_position_9) | ストリームから符号付きバイトデータを読み取ります。 |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | ストリームから符号付きバイト値の配列を読み取ります。 |
| [read_s_long(position)](#read_s_long_position_11) | ストリームから符号付き整数値を読み取ります。 |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | ストリームから符号付き整数値の配列を読み取ります。 |
| [read_s_rational(position)](#read_s_rational_position_13) | ストリームから単一の符号付き有理数値を読み取ります。 |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | ストリームから符号付き有理数値の配列を読み取ります。 |
| [read_s_short(position)](#read_s_short_position_15) | ストリームから符号付きショート値を読み取ります。 |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | ストリームから符号付きショート値の配列を読み取ります。 |
| [read_u_long(position)](#read_u_long_position_17) | ストリームから符号なし整数値を読み取ります。 |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | ストリームから符号なし整数値の配列を読み取ります。 |
| [read_u_short(position)](#read_u_short_position_19) | ストリームから符号なしショート値を読み取ります。 |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | ストリームから符号なし整数値の配列を読み取ります。 |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | 基礎データをストリームコンテナに変換します。 |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

新しいインスタンスを初期化します [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) クラス。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | バイト配列データです。 |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

新しいインスタンスを初期化します [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) クラス。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | バイト配列データです。 |
| start_index | int | <paramref name=\"data\" /> の開始インデックスです。 |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

新しいインスタンスを初期化します [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) クラス。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | バイト配列データです。 |
| start_index | int | <paramref name=\"data\" /> の開始インデックスです。 |
| data_length | int | データの長さです。 |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

新しいインスタンスを初期化します [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) クラス。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ストリームコンテナです。 |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

ストリームからバイト値の配列を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 配列 | byte | 埋める配列です。 |
| array_index | int | 値を入れ始める配列インデックスです。 |
| position | long | 読み取り元のストリーム位置です。 |
| count | long | 読み取る要素数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| long | バイト値の配列です。 |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

ストリームから符号なしバイト値の配列を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |
| count | long | 要素数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| byte | 符号なしバイト値の配列です。 |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

ストリームから単一の double 値を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| double | 単一の double 値です。 |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

ストリームから double 値の配列を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |
| count | long | 要素数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| double | double 値の配列です。 |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

ストリームから単一の float 値を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| float | 単一の float 値です。 |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

ストリームから float 値の配列を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |
| count | long | 要素数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| float | float 値の配列です。 |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

ストリームから単一の有理数の値を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 有理数です。 |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

ストリームから有理数値の配列を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |
| count | long | 要素数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 有理数の配列です。 |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

ストリームから符号付きバイトデータを読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| sbyte | 符号付きバイト値です。 |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

ストリームから符号付きバイト値の配列を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |
| count | long | 要素数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| sbyte | 符号付きバイト値の配列です。 |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

ストリームから符号付き整数値を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 符号付き整数値です。 |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

ストリームから符号付き整数値の配列を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |
| count | long | 要素数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 符号付き整数値の配列です。 |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

ストリームから単一の符号付き有理数値を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 符号付き有理数です。 |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

ストリームから符号付き有理数値の配列を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |
| count | long | 要素数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 符号付き有理数の配列です。 |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

ストリームから符号付きショート値を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| short | 符号付きショート値です。 |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

ストリームから符号付きショート値の配列を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |
| count | long | 要素数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| short | 符号付きショート値の配列です。 |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

ストリームから符号なし整数値を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| uint | 符号なし整数値です。 |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

ストリームから符号なし整数値の配列を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |
| count | long | 要素数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| uint | 符号なし整数値の配列です。 |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

ストリームから符号なしショート値を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| ushort | 符号なしショート値です。 |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

ストリームから符号なし整数値の配列を読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| position | long | 読み取り位置です。 |
| count | long | 要素数です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| ushort | 符号なし整数値の配列です。 |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

基礎データをストリームコンテナに変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| start_position | long | 変換を開始する開始位置です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) に変換されたデータが含まれています。 |


