---
title: "TiffStreamWriter クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | 新しい [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| position | long | r/w | ストリーム位置を取得または設定します。 |
| sync_root | object | r | 同期されたリソースへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [write(data)](#write_data_1) | 指定されたデータを書き込みます。 |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | 指定されたデータを書き込みます。 |
| [write_double(data)](#write_double_data_3) | ストリームに単一の double 値を書き込みます。 |
| [write_double_array(data)](#write_double_array_data_4) | ストリームに double 値の配列を書き込みます。 |
| [write_float(data)](#write_float_data_5) | ストリームに単一の float 値を書き込みます。 |
| [write_float_array(data)](#write_float_array_data_6) | ストリームに float 値の配列を書き込みます。 |
| [write_rational(data)](#write_rational_data_7) | ストリームに単一の有理数値を書き込みます。 |
| [write_rational_array(data)](#write_rational_array_data_8) | ストリームに符号なし有理数値の配列を書き込みます。 |
| [write_s_byte(data)](#write_s_byte_data_9) | ストリームに単一の符号付きバイト値を書き込みます。 |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | ストリームに符号付きバイト値の配列を書き込みます。 |
| [write_s_long_array(data)](#write_s_long_array_data_11) | ストリームに整数値の配列を書き込みます。 |
| [write_s_rational(data)](#write_s_rational_data_12) | ストリームに単一の符号付き有理数値を書き込みます。 |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | ストリームに符号付き有理数値の配列を書き込みます。 |
| [write_s_short(data)](#write_s_short_data_14) | ストリームに単一の short 値を書き込みます。 |
| [write_s_short_array(data)](#write_s_short_array_data_15) | ストリームに short 値の配列を書き込みます。 |
| [write_slong(data)](#write_slong_data_16) | ストリームに単一の整数値を書き込みます。 |
| [write_u_byte(data)](#write_u_byte_data_17) | ストリームに単一のバイト値を書き込みます。 |
| [write_u_long(data)](#write_u_long_data_18) | ストリームに単一の符号なし整数値を書き込みます。 |
| [write_u_long_array(data)](#write_u_long_array_data_19) | ストリームに符号なし整数値の配列を書き込みます。 |
| [write_u_short(data)](#write_u_short_data_20) | ストリームに単一の符号なしショート値を書き込みます。 |
| [write_u_short_array(data)](#write_u_short_array_data_21) | ストリームに符号なしショート値の配列を書き込みます。 |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

新しい [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ストリームライター。 |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

指定されたデータを書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | 書き込むデータ。 |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

指定されたデータを書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | 書き込むデータ。 |
| offset | int | データのオフセット。 |
| data_length | int | 書き込むデータの長さ。 |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

ストリームに単一の double 値を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | double | 書き込む値。 |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

ストリームに double 値の配列を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | double | 書き込む配列。 |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

ストリームに単一の float 値を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | float | 書き込む値。 |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

ストリームに float 値の配列を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | float | 書き込む配列。 |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

ストリームに単一の有理数値を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 書き込む値。 |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

ストリームに符号なし有理数値の配列を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 書き込む配列。 |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

ストリームに単一の符号付きバイト値を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | sbyte | 書き込む値。 |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

ストリームに符号付きバイト値の配列を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | sbyte | 書き込む配列。 |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

ストリームに整数値の配列を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | int | 書き込む配列。 |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

ストリームに単一の符号付き有理数値を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 書き込む値。 |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

ストリームに符号付き有理数値の配列を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 書き込む配列。 |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

ストリームに単一の short 値を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | short | 書き込む値。 |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

ストリームに short 値の配列を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | short | 書き込む配列。 |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

ストリームに単一の整数値を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | int | 書き込む値。 |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

ストリームに単一のバイト値を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | 書き込む値。 |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

ストリームに単一の符号なし整数値を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | uint | 書き込む値。 |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

ストリームに符号なし整数値の配列を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | uint | 書き込む配列。 |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

ストリームに単一の符号なしショート値を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | ushort | 書き込む値。 |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

ストリームに符号なしショート値の配列を書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | ushort | 書き込む配列。 |

