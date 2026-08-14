---
title: "TiffDataType クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | タグデータを収めるのに 12 バイトでは足りない場合のために、追加のデータサイズ（バイト単位）を取得します。 |
| count | uint | r | 要素数を取得します。 |
| data_size | uint | r | タグデータを収めるのに 12 バイトでは足りない場合のために、追加のデータサイズ（バイト単位）を取得します。 |
| id | ushort | r | タグ ID の整数表現を取得します。 |
| is_valid | bool | r | タグデータが有効かどうかを示す値を取得します。有効なタグは保存できるデータを含みます。無効なタグは保存できません。 |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | タグ ID を取得します。 |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | タグのタイプを取得します。 |
| 値 | object | r/w | このデータ型が保持する値を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | 現在のインスタンスを同じ型の別のオブジェクトと比較し、現在のインスタンスが前にあるか、後にあるか、または同じ位置にあるかを示す整数を返します。 |
| [deep_clone()](#deep_clone__2) | このインスタンスのディープクローンを実行します。 |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | タグデータを読み取ります。 |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | 追加のタグデータを書き込みます。 |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | タグデータを書き込みます。 |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

現在のインスタンスを同じ型の別のオブジェクトと比較し、現在のインスタンスが前にあるか、後にあるか、または同じ位置にあるかを示す整数を返します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| obj | object | このインスタンスと比較するオブジェクトです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 比較されるオブジェクトの相対順序を示す 32 ビット符号付き整数です。戻り値の意味は次のとおりです:<br/>            値<br/>            意味<br/>            0 未満<br/>            このインスタンスは <paramref name="obj" /> 未満です。<br/>            0<br/>            このインスタンスは <paramref name="obj" /> と等しいです。<br/>            0 より大きい<br/>            このインスタンスは <paramref name="obj" /> より大きいです。 |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

このインスタンスのディープクローンを実行します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | 現在のインスタンスのディープクローンです。 |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

タグデータを読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | データストリームです。 |
| position | long | タグの位置です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | 読み取りタグです。 |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

追加のタグデータを書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | データストリームです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| long | 実際に書き込まれたバイト数です。 |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

タグデータを書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | データストリームです。 |
| additional_data_offset | long | 追加データを書き込むオフセットです。 |

