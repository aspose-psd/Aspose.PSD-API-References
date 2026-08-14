---
title: "ColorantCmyk クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.psd.xmp.types.complex.colorant](/psd/python-net/aspose.psd.xmp.types.complex.colorant/)

**Full Name:** aspose.psd.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | 新しい [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) クラスのインスタンスを初期化します。 |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | 新しい [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [static] | float | r | CMYK カラントの最大値です。 |
| COLOR_VALUE_MIN [static] | float | r | CMYK カラントの最小値です。 |
| 黒 | float | r/w | 黒コンポーネントの値を取得または設定します。 |
| color_type | [ColorType](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colortype) | r/w | 色のタイプを取得または設定します。 |
| シアン | float | r/w | シアンコンポーネントの値を取得または設定します。 |
| マゼンタ | float | r/w | マゼンタコンポーネントの値を取得または設定します。 |
| mode | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode) | r | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode/) を取得します。 |
| namespace_uri | string | r | デフォルトの名前空間 URI を取得します。 |
| プレフィックス | string | r | プレフィックスを取得します。 |
| swatch_name | string | r/w | スウォッチの名前を取得または設定します。 |
| 黄 | float | r/w | 黄コンポーネントの値を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | XMP 形式で含まれる文字列の値を取得します。 |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

新しい [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) クラスのインスタンスを初期化します。

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

新しい [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 黒 | float | 黒コンポーネントの値です。 |
| シアン | float | シアンカラーコンポーネントの値です。 |
| マゼンタ | float | マゼンタコンポーネントの値です。 |
| 黄 | float | 黄コンポーネントの値です。 |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

XMP 形式で含まれる文字列の値を取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | XMP 形式で含まれる文字列の値を返します。 |


