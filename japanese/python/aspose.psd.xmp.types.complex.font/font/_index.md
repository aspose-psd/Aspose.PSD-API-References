---
title: "Font クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.xmp.types.complex.font/font/
---

**Summary:** Represents XMP Font.

**Module:** [aspose.psd.xmp.types.complex.font](/psd/python-net/aspose.psd.xmp.types.complex.font/)

**Full Name:** aspose.psd.xmp.types.complex.font.Font

**Inheritance:** IXmpType, ComplexTypeBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Font()](#Font__1) | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font/) クラスの新しいインスタンスを初期化します。 |
| [Font(font_family)](#Font_font_family_2) | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| child_font_files | string | r/w | 複合フォントを構成するフォントのファイル名の配列を取得または設定します。 |
| font_face | string | r/w | フォントフェイスを取得または設定します。 |
| font_family | string | r/w | フォント ファミリを取得または設定します。 |
| font_file_name | string | r/w | フルパスなしのフォントファイル名を取得または設定します。 |
| font_name | string | r/w | PostScript フォント名を取得または設定します。 |
| font_type | string | r/w | フォントタイプを取得または設定します。 |
| is_composite | bool | r/w | このフォントが複合かどうかを示す値を取得または設定します。 |
| namespace_uri | string | r | デフォルトの名前空間 URI を取得します。 |
| プレフィックス | string | r | プレフィックスを取得します。 |
| version | string | r/w | フォントバージョンを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | XMP 形式で含まれる文字列の値を取得します。 |


### Constructor: Font() {#Font__1}


```
 Font() 
```

[Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font/) クラスの新しいインスタンスを初期化します。

### Constructor: Font(font_family) {#Font_font_family_2}


```
 Font(font_family) 
```

[Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| font_family | string | フォントファミリー。 |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

XMP 形式で含まれる文字列の値を取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | XMP 形式で含まれる文字列の値を返します。 |


