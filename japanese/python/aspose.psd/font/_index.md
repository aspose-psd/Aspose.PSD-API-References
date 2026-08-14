---
title: "Font クラス"
type: docs
weight: 1340
url: /ja/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | 指定されたサイズを使用して新しい [Font](/psd/python-net/aspose.psd/font/) を初期化します。文字セットは [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) に、グラフィック単位は [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) に、フォントスタイルは [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) に設定されます。 |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | 指定されたサイズとスタイルを使用して新しい [Font](/psd/python-net/aspose.psd/font/) を初期化します。文字セットは [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) に、グラフィック単位は [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) に設定されます。 |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | 指定されたサイズ、スタイル、単位を使用して新しい [Font](/psd/python-net/aspose.psd/font/) を初期化します。 |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | 指定されたサイズ、スタイル、単位、文字セットを使用して新しい [Font](/psd/python-net/aspose.psd/font/) を初期化します。 |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | 指定されたサイズと単位を使用して新しい [Font](/psd/python-net/aspose.psd/font/) を初期化します。文字セットは [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) に、スタイルは [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) に設定されます。 |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | 指定された既存の [Font](/psd/python-net/aspose.psd/font/) と [FontStyle](/psd/python-net/aspose.psd/fontstyle/) 列挙体を使用する新しい [Font](/psd/python-net/aspose.psd/font/) を初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bold | bool | r | この [Font](/psd/python-net/aspose.psd/font/) が太字かどうかを示す値を取得します。 |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | この [Font](/psd/python-net/aspose.psd/font/) が使用する文字セットを指定するバイト値を取得します。 |
| italic | bool | r | この [Font](/psd/python-net/aspose.psd/font/) がイタリックかどうかを示す値を取得します。 |
| name | string | r | この [Font](/psd/python-net/aspose.psd/font/) のフォント名を取得します。 |
| size | float | r | この [Font](/psd/python-net/aspose.psd/font/) の em サイズを、[Font.unit](/psd/python-net/aspose.psd/font/) プロパティで指定された単位で測定して取得します。 |
| strikeout | bool | r | この [Font](/psd/python-net/aspose.psd/font/) がフォントに水平線を指定しているかどうかを示す値を取得します。 |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | この [Font](/psd/python-net/aspose.psd/font/) のスタイル情報を取得します。 |
| underline | bool | r | この [Font](/psd/python-net/aspose.psd/font/) が下線付きかどうかを示す値を取得します。 |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | この [Font](/psd/python-net/aspose.psd/font/) の測定単位を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | この [Font](/psd/python-net/aspose.psd/font/) の正確なディープコピーを作成します。 |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

指定されたサイズを使用して新しい [Font](/psd/python-net/aspose.psd/font/) を初期化します。文字セットは [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) に、グラフィック単位は [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) に、フォントスタイルは [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) に設定されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 名の文字列表現です。 |
| em_size | float | 新しいフォントの em サイズ（ポイント単位）です。 |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

指定されたサイズとスタイルを使用して新しい [Font](/psd/python-net/aspose.psd/font/) を初期化します。文字セットは [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) に、グラフィック単位は [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) に設定されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 名の文字列表現です。 |
| em_size | float | 新しいフォントの em サイズ（ポイント単位）です。 |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | 新しいフォントの [FontStyle](/psd/python-net/aspose.psd/fontstyle/) です。 |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

指定されたサイズ、スタイル、単位を使用して新しい [Font](/psd/python-net/aspose.psd/font/) を初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 名の文字列表現です。 |
| em_size | float | パラメーター <paramref name=\"unit\" /> で指定された単位での新しいフォントの em サイズです。 |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | 新しいフォントの [FontStyle](/psd/python-net/aspose.psd/fontstyle/) です。 |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 新しいフォントの [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) です。 |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

指定されたサイズ、スタイル、単位、文字セットを使用して新しい [Font](/psd/python-net/aspose.psd/font/) を初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 名の文字列表現です。 |
| em_size | float | パラメーター <paramref name=\"unit\" /> で指定された単位での新しいフォントの em サイズです。 |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | 新しいフォントの [FontStyle](/psd/python-net/aspose.psd/fontstyle/) です。 |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 新しいフォントの [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) です。 |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | このフォントで使用する文字セットです。 |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

指定されたサイズと単位を使用して新しい [Font](/psd/python-net/aspose.psd/font/) を初期化します。文字セットは [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) に、スタイルは [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) に設定されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 名の文字列表現です。 |
| em_size | float | パラメーター <paramref name=\"unit\" /> で指定された単位での新しいフォントの em サイズです。 |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 新しいフォントの [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) です。 |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

指定された既存の [Font](/psd/python-net/aspose.psd/font/) と [FontStyle](/psd/python-net/aspose.psd/fontstyle/) 列挙体を使用する新しい [Font](/psd/python-net/aspose.psd/font/) を初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 新しい [Font](/psd/python-net/aspose.psd/font/) を作成する元となる既存の [Font](/psd/python-net/aspose.psd/font/) です。 |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | 新しい [Font](/psd/python-net/aspose.psd/font/) に適用する [FontStyle](/psd/python-net/aspose.psd/fontstyle/) です。複数の [FontStyle](/psd/python-net/aspose.psd/fontstyle/) 列挙値は OR 演算子で組み合わせることができます。 |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

この [Font](/psd/python-net/aspose.psd/font/) の正確なディープコピーを作成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | このメソッドが作成する [Font](/psd/python-net/aspose.psd/font/) です。 |


