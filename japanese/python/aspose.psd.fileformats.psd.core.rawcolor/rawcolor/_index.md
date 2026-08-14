---
title: "RawColor クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) |  [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) クラスの新しいインスタンスを初期化します。 |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | 事前定義されたカラーモードを使用してピクセルデータ形式から [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| color_mode | short | r/w | 従うべきカラーのモードです。 |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | カラーのコンポーネントを取得します。各コンポーネントは個別のチャンネルであり、あまり一般的でない<br/>            カラースキームを使用する場合は、各チャンネルを個別に扱う方が良いです。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | 取得できる場合に、色を int として取得します。 |
| [get_as_long()](#get_as_long__2) | 取得できる場合に、色を long として取得します。 |
| [get_bit_depth()](#get_bit_depth__3) | Raw Color のビット深度を取得します。 <br/>            例として、各チャンネル/コンポーネントが 8 ビットの ARGB カラーの場合は 32 ビットです。<br/>            各チャンネル/コンポーネントが 16 ビットのフル ARGB カラーの場合は 64 ビットです。<br/>            ビット深度はチャンネルのビット深度の合計から算出されます。 <br/>            各チャンネルが異なるビット深度を持つ場合に可能です。 |
| [get_color_mode_name()](#get_color_mode_name__4) | カラー モードの名前を取得します。カラー モード名はチャンネル/コンポーネントの名前から構成されます。 |
| [set_as_int(value)](#set_as_int_value_5) | 可能な場合、int 引数からすべてのチャンネルにデータを設定します。 |
| [set_as_long(value)](#set_as_long_value_6) | 可能な場合、int 引数からすべてのチャンネルにデータを設定します。 |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

 [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | カスタム カラー コンポーネントです。 |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

事前定義されたカラーモードを使用してピクセルデータ形式から [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | ピクセル データ形式です。 |
| color_mode | short | 従うべきカラーのモードです。 |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

取得できる場合に、色を int として取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | チャンネル データは Int に格納されます。 |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

取得できる場合に、色を long として取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| long | チャンネル データは Int に格納されます。 |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Raw Color のビット深度を取得します。 <br/>            例として、各チャンネル/コンポーネントが 8 ビットの ARGB カラーの場合は 32 ビットです。<br/>            各チャンネル/コンポーネントが 16 ビットのフル ARGB カラーの場合は 64 ビットです。<br/>            ビット深度はチャンネルのビット深度の合計から算出されます。 <br/>            各チャンネルが異なるビット深度を持つ場合に可能です。

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | すべてのチャンネルのビット深度の合計です。 |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

カラー モードの名前を取得します。カラー モード名はチャンネル/コンポーネントの名前から構成されます。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | カラー モード名を含む文字列です。 |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

可能な場合、int 引数からすべてのチャンネルにデータを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 値 | int | コンポーネント データを含む int 値です。 |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

可能な場合、int 引数からすべてのチャンネルにデータを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 値 | long | コンポーネント データを含む int 値です。 |

