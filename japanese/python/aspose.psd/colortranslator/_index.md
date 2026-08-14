---
title: "ColorTranslator クラス"
type: docs
weight: 840
url: /ja/python-net/aspose.psd/colortranslator/
---

**Summary:** Translates colors to and from GDI+ Color structures. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorTranslator

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [from_html(html_color)](#from_html_html_color_1) | HTML カラーから色を取得します。 |
| [from_ole(ole_color)](#from_ole_ole_color_2) | OLE カラーから色を取得します。 |
| [from_win32(win_32_color)](#from_win32_win_32_color_3) | HTML カラーから色を取得します。 |
| [to_html(c)](#to_html_c_4) | 色から HTML カラーを作成します。 |
| [to_ole(c)](#to_ole_c_5) | OLE カラーを色に変換します。 |
| [to_win32(c)](#to_win32_c_6) | 色を Win32 カラーに変換します。 |


### Method: from_html(html_color)  [static] {#from_html_html_color_1}


```
 from_html(html_color) 
```

HTML カラーから色を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| html_color | string | HTML カラー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 色。 |


### Method: from_ole(ole_color)  [static] {#from_ole_ole_color_2}


```
 from_ole(ole_color) 
```

OLE カラーから色を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ole_color | int | OLE カラー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 色。 |


### Method: from_win32(win_32_color)  [static] {#from_win32_win_32_color_3}


```
 from_win32(win_32_color) 
```

HTML カラーから色を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| win_32_color | int | Win32 カラー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 色。 |


### Method: to_html(c)  [static] {#to_html_c_4}


```
 to_html(c) 
```

色から HTML カラーを作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| c | [Color](/psd/python-net/aspose.psd/color) | カラー クラスです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | html 文字列の色です。 |


### Method: to_ole(c)  [static] {#to_ole_c_5}


```
 to_ole(c) 
```

OLE カラーを色に変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| c | [Color](/psd/python-net/aspose.psd/color) | 色。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | OLE カラーです。 |


### Method: to_win32(c)  [static] {#to_win32_c_6}


```
 to_win32(c) 
```

色を Win32 カラーに変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| c | [Color](/psd/python-net/aspose.psd/color) | 色。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | Win32 カラーです。 |


