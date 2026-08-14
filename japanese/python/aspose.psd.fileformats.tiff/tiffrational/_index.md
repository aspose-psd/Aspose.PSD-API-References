---
title: "TiffRational クラス"
type: docs
weight: 30
url: /ja/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | 新しい [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) クラスのインスタンスを初期化します。 |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | 新しい [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) クラスのインスタンスを初期化します。 |
| [TiffRational(value)](#TiffRational_value_3) | 新しい [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| EPSILON [static] | double | r | 分数計算用の epsilon |
| 分母 | uint | r | 分母を取得します。 |
| 分子 | uint | r | 分子を取得します。 |
| 値 | float | r | float 値を取得します。 |
| value_d | double | r | double 値を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | 提供された値を分数に近似します。 |
| [approximate_fraction(value)](#approximate_fraction_value_2) | 提供された値を分数に近似します。 |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | 提供された値を分数に近似します。 |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | 提供された値を分数に近似します。 |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

新しい [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) クラスのインスタンスを初期化します。

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

新しい [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 分子 | uint | 分子です。 |
| 分母 | uint | 分母です。 |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

新しい [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 値 | uint | 分子の値です。 |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

提供された値を分数に近似します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 値 | double | 値です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 誤差が [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 未満の有理数です。 |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

提供された値を分数に近似します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 値 | float | 値です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 誤差が [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 未満の有理数です。 |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

提供された値を分数に近似します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 値 | double | 値です。 |
| epsilon | double | 許容される誤差です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 誤差が <paramref name=\"epsilon\" /> 未満の有理数です。 |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

提供された値を分数に近似します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 値 | float | 値です。 |
| epsilon | double | 許容される誤差です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 誤差が <paramref name=\"epsilon\" /> 未満の有理数です。 |


