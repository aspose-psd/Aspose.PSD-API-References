---
title: "Класс ColorTranslator"
type: docs
weight: 840
url: /ru/python-net/aspose.psd/colortranslator/
---

**Summary:** Translates colors to and from GDI+ Color structures. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorTranslator

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [from_html(html_color)](#from_html_html_color_1) | Получает цвет из HTML‑цвета. |
| [from_ole(ole_color)](#from_ole_ole_color_2) | Получает цвет из OLE‑цвета. |
| [from_win32(win_32_color)](#from_win32_win_32_color_3) | Получает цвет из HTML‑цвета. |
| [to_html(c)](#to_html_c_4) | Создаёт HTML‑цвет из цвета. |
| [to_ole(c)](#to_ole_c_5) | Преобразует OLE‑цвет в цвет. |
| [to_win32(c)](#to_win32_c_6) | Преобразует цвет в win32‑цвет. |


### Method: from_html(html_color)  [static] {#from_html_html_color_1}


```
 from_html(html_color) 
```

Получает цвет из HTML‑цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| html_color | string | HTML цвет. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Цвет. |


### Method: from_ole(ole_color)  [static] {#from_ole_ole_color_2}


```
 from_ole(ole_color) 
```

Получает цвет из OLE‑цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ole_color | int | OLE цвет. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Цвет. |


### Method: from_win32(win_32_color)  [static] {#from_win32_win_32_color_3}


```
 from_win32(win_32_color) 
```

Получает цвет из HTML‑цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| win_32_color | int | Win32 цвет. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Цвет. |


### Method: to_html(c)  [static] {#to_html_c_4}


```
 to_html(c) 
```

Создаёт HTML‑цвет из цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| c | [Color](/psd/python-net/aspose.psd/color) | Класс цвета. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | HTML-строковый цвет. |


### Method: to_ole(c)  [static] {#to_ole_c_5}


```
 to_ole(c) 
```

Преобразует OLE‑цвет в цвет.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| c | [Color](/psd/python-net/aspose.psd/color) | Цвет. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | OLE цвет. |


### Method: to_win32(c)  [static] {#to_win32_c_6}


```
 to_win32(c) 
```

Преобразует цвет в win32‑цвет.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| c | [Color](/psd/python-net/aspose.psd/color) | Цвет. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Win32 цвет. |


