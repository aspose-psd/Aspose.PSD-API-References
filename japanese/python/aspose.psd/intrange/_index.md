---
title: "IntRange クラス"
type: docs
weight: 2340
url: /ja/python-net/aspose.psd/intrange/
---

**Summary:** Class for representing sequence of elements

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IntRange

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [IntRange(range)](#IntRange_range_1) | [IntRange](/psd/python-net/aspose.psd/intrange/) クラスの新しいインスタンスを初期化します。 |
| [IntRange(start, count)](#IntRange_start_count_2) | [IntRange](/psd/python-net/aspose.psd/intrange/) クラスの新しいインスタンスを初期化します。 |
| [IntRange(start, count, delta)](#IntRange_start_count_delta_3) | [IntRange](/psd/python-net/aspose.psd/intrange/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| 範囲 | int | r/w | 範囲を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_array_one_item_from_index(index)](#get_array_one_item_from_index_index_1) | 指定されたインデックスから 1 要素の配列を返します。 |
| [get_range(start, count, delta)](#get_range_start_count_delta_2) | 開始位置からの整数要素のカウント範囲を取得します。 |


### Constructor: IntRange(range) {#IntRange_range_1}


```
 IntRange(range) 
```

[IntRange](/psd/python-net/aspose.psd/intrange/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 範囲 | int | 範囲です。 |

### Constructor: IntRange(start, count) {#IntRange_start_count_2}


```
 IntRange(start, count) 
```

[IntRange](/psd/python-net/aspose.psd/intrange/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 開始 | int | 開始です。 |
| count | int | カウントです。 |

### Constructor: IntRange(start, count, delta) {#IntRange_start_count_delta_3}


```
 IntRange(start, count, delta) 
```

[IntRange](/psd/python-net/aspose.psd/intrange/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 開始 | int | 開始です。 |
| count | int | カウントです。 |
| デルタ | int | デルタです。 |

### Method: get_array_one_item_from_index(index) {#get_array_one_item_from_index_index_1}


```
 get_array_one_item_from_index(index) 
```

指定されたインデックスから 1 要素の配列を返します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| index | int | 範囲インデックスです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 整数の配列 |


### Method: get_range(start, count, delta)  [static] {#get_range_start_count_delta_2}


```
 get_range(start, count, delta) 
```

開始位置からの整数要素のカウント範囲を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 開始 | int | 開始です。 |
| count | int | カウントです。 |
| デルタ | int | デルタです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| iter[int] | 項目の配列 |


