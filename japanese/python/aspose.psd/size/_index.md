---
title: "Size クラス"
type: docs
weight: 4080
url: /ja/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Size()](#Size__1) | Size クラスの新しいインスタンスを初期化します |
| [Size(point)](#Size_point_2) | 指定された [Point](/psd/python-net/aspose.psd/point/) から [Size](/psd/python-net/aspose.psd/size/) 構造体の新しいインスタンスを初期化します。 |
| [Size(width, height)](#Size_width_height_3) | 指定された寸法から [Size](/psd/python-net/aspose.psd/size/) 構造体の新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | [Size.width](/psd/python-net/aspose.psd/size/) と [Size.height](/psd/python-net/aspose.psd/size/) の値が 0 に設定された [Size](/psd/python-net/aspose.psd/size/) 構造体の新しいインスタンスを取得します。 |
| height | int | r/w | この [Size](/psd/python-net/aspose.psd/size/) の垂直成分を取得または設定します。 |
| is_empty | bool | r | この [Size](/psd/python-net/aspose.psd/size/) の幅と高さが 0 かどうかを示す値を取得します。 |
| width | int | r/w | この [Size](/psd/python-net/aspose.psd/size/) の水平成分を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | ある [Size](/psd/python-net/aspose.psd/size/) 構造体の幅と高さを別の [Size](/psd/python-net/aspose.psd/size/) 構造体の幅と高さに加算します。 |
| [ceiling(size)](#ceiling_size_2) | 指定された [SizeF](/psd/python-net/aspose.psd/sizef/) 構造体を、[Size](/psd/python-net/aspose.psd/size/) 構造体の値を次の整数に切り上げて [Size](/psd/python-net/aspose.psd/size/) 構造体に変換します。 |
| [round(size)](#round_size_3) | 指定された[SizeF](/psd/python-net/aspose.psd/sizef/)構造体を、[Size](/psd/python-net/aspose.psd/size/)構造体に変換します。変換は、[SizeF](/psd/python-net/aspose.psd/sizef/)構造体の値を最も近い整数に丸めることで行われます。 |
| [subtract(size1, size2)](#subtract_size1_size2_4) | ある[Size](/psd/python-net/aspose.psd/size/)構造体の幅と高さを、別の[Size](/psd/python-net/aspose.psd/size/)構造体の幅と高さから減算します。 |
| [truncate(size)](#truncate_size_5) | 指定された[SizeF](/psd/python-net/aspose.psd/sizef/)構造体を、[Size](/psd/python-net/aspose.psd/size/)構造体に変換します。変換は、[SizeF](/psd/python-net/aspose.psd/sizef/)構造体の値を次の低い整数に切り捨てることで行われます。 |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Size クラスの新しいインスタンスを初期化します

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

指定された [Point](/psd/python-net/aspose.psd/point/) から [Size](/psd/python-net/aspose.psd/size/) 構造体の新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | この[Size](/psd/python-net/aspose.psd/size/)を初期化するための[Point](/psd/python-net/aspose.psd/point/)です。 |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

指定された寸法から [Size](/psd/python-net/aspose.psd/size/) 構造体の新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| width | int | 新しい[Size](/psd/python-net/aspose.psd/size/)の幅コンポーネントです。 |
| height | int | 新しい[Size](/psd/python-net/aspose.psd/size/)の高さコンポーネントです。 |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

ある [Size](/psd/python-net/aspose.psd/size/) 構造体の幅と高さを別の [Size](/psd/python-net/aspose.psd/size/) 構造体の幅と高さに加算します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | 加算する最初の[Size](/psd/python-net/aspose.psd/size/)です。 |
| size2 | [Size](/psd/python-net/aspose.psd/size) | 加算する2番目の[Size](/psd/python-net/aspose.psd/size/)です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | 加算操作の結果となる[Size](/psd/python-net/aspose.psd/size/)構造体です。 |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

指定された [SizeF](/psd/python-net/aspose.psd/sizef/) 構造体を、[Size](/psd/python-net/aspose.psd/size/) 構造体の値を次の整数に切り上げて [Size](/psd/python-net/aspose.psd/size/) 構造体に変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 変換する[SizeF](/psd/python-net/aspose.psd/sizef/)構造体です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | このメソッドが変換する[Size](/psd/python-net/aspose.psd/size/)構造体です。 |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

指定された[SizeF](/psd/python-net/aspose.psd/sizef/)構造体を、[Size](/psd/python-net/aspose.psd/size/)構造体に変換します。変換は、[SizeF](/psd/python-net/aspose.psd/sizef/)構造体の値を最も近い整数に丸めることで行われます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 変換する[SizeF](/psd/python-net/aspose.psd/sizef/)構造体です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | このメソッドが変換する[Size](/psd/python-net/aspose.psd/size/)構造体です。 |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

ある[Size](/psd/python-net/aspose.psd/size/)構造体の幅と高さを、別の[Size](/psd/python-net/aspose.psd/size/)構造体の幅と高さから減算します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | 減算演算子の左側にある[Size](/psd/python-net/aspose.psd/size/)構造体です。 |
| size2 | [Size](/psd/python-net/aspose.psd/size) | 減算演算子の右側にある[Size](/psd/python-net/aspose.psd/size/)構造体です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | 減算操作の結果となる[Size](/psd/python-net/aspose.psd/size/)です。 |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

指定された[SizeF](/psd/python-net/aspose.psd/sizef/)構造体を、[Size](/psd/python-net/aspose.psd/size/)構造体に変換します。変換は、[SizeF](/psd/python-net/aspose.psd/sizef/)構造体の値を次の低い整数に切り捨てることで行われます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 変換する[SizeF](/psd/python-net/aspose.psd/sizef/)構造体です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | このメソッドが変換する[Size](/psd/python-net/aspose.psd/size/)構造体です。 |


