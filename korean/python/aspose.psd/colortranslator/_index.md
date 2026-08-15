---
title: "ColorTranslator 클래스"
type: docs
weight: 840
url: /ko/python-net/aspose.psd/colortranslator/
---

**Summary:** Translates colors to and from GDI+ Color structures. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorTranslator

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **설명** |
| :- | :- |
| [from_html(html_color)](#from_html_html_color_1) | HTML 색상에서 색상을 가져옵니다. |
| [from_ole(ole_color)](#from_ole_ole_color_2) | OLE 색상에서 색상을 가져옵니다. |
| [from_win32(win_32_color)](#from_win32_win_32_color_3) | HTML 색상에서 색상을 가져옵니다. |
| [to_html(c)](#to_html_c_4) | 색상으로부터 HTML 색상을 생성합니다. |
| [to_ole(c)](#to_ole_c_5) | OLE 색상을 색상으로 변환합니다. |
| [to_win32(c)](#to_win32_c_6) | 색상을 win32 색상으로 변환합니다. |


### Method: from_html(html_color)  [static] {#from_html_html_color_1}


```
 from_html(html_color) 
```

HTML 색상에서 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| html_color | 문자열 | HTML 색상. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 색상. |


### Method: from_ole(ole_color)  [static] {#from_ole_ole_color_2}


```
 from_ole(ole_color) 
```

OLE 색상에서 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| ole_color | int | OLE 색상. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 색상. |


### Method: from_win32(win_32_color)  [static] {#from_win32_win_32_color_3}


```
 from_win32(win_32_color) 
```

HTML 색상에서 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| win_32_color | int | Win32 색상. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 색상. |


### Method: to_html(c)  [static] {#to_html_c_4}


```
 to_html(c) 
```

색상으로부터 HTML 색상을 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| c | [Color](/psd/python-net/aspose.psd/color) | 색상 클래스. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | HTML 문자열 색상. |


### Method: to_ole(c)  [static] {#to_ole_c_5}


```
 to_ole(c) 
```

OLE 색상을 색상으로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| c | [Color](/psd/python-net/aspose.psd/color) | 색상. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | OLE 색상. |


### Method: to_win32(c)  [static] {#to_win32_c_6}


```
 to_win32(c) 
```

색상을 win32 색상으로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| c | [Color](/psd/python-net/aspose.psd/color) | 색상. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | Win32 색상. |


