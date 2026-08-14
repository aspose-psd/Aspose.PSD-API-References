---
title: "ColorantLab クラス"
type: docs
weight: 30
url: /ja/python-net/aspose.psd.xmp.types.complex.colorant/colorantlab/
---

**Summary:** Represents LAB Colorant.

**Module:** [aspose.psd.xmp.types.complex.colorant](/psd/python-net/aspose.psd.xmp.types.complex.colorant/)

**Full Name:** aspose.psd.xmp.types.complex.colorant.ColorantLab

**Inheritance:** IXmpType, ColorantBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ColorantLab()](#ColorantLab__1) | 新しい [ColorantLab](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantlab/) クラスのインスタンスを初期化します。 |
| [ColorantLab(a, b, l)](#ColorantLab_a_b_l_2) | 新しい [ColorantLab](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantlab/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| MAX_A [static] | int | r | A コンポーネントの最大値 |
| MAX_B [static] | int | r | A コンポーネントの最大値 |
| MAX_L [static] | float | r | A コンポーネントの最大値 |
| MIN_A [static] | int | r | A コンポーネントの最小値 |
| MIN_B [static] | int | r | B コンポーネントの最小値 |
| MIN_L [static] | float | r | L コンポーネントの最小値 |
| a | int | r/w | A コンポーネントを取得または設定します。 |
| b | int | r/w | B コンポーネントを取得または設定します。 |
| color_type | [ColorType](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colortype) | r/w | 色のタイプを取得または設定します。 |
| l | float | r/w | L コンポーネントを取得または設定します。 |
| mode | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode) | r | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode/) を取得します。 |
| namespace_uri | string | r | デフォルトの名前空間 URI を取得します。 |
| プレフィックス | string | r | プレフィックスを取得します。 |
| swatch_name | string | r/w | スウォッチの名前を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | XMP 形式で含まれる文字列の値を取得します。 |


### Constructor: ColorantLab() {#ColorantLab__1}


```
 ColorantLab() 
```

新しい [ColorantLab](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantlab/) クラスのインスタンスを初期化します。

### Constructor: ColorantLab(a, b, l) {#ColorantLab_a_b_l_2}


```
 ColorantLab(a, b, l) 
```

新しい [ColorantLab](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantlab/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| a | int | A コンポーネント。 |
| b | int | B コンポーネント。 |
| l | float | L コンポーネント。 |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

XMP 形式で含まれる文字列の値を取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | XMP 形式で含まれる文字列の値を返します。 |


