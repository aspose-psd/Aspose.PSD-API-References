---
title: "IPsdColorPalette 클래스"
type: docs
weight: 1990
url: /ko/python-net/aspose.psd/ipsdcolorpalette/
---

**Summary:** The pasd color palette

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPsdColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 32비트 ARGB 구조체 배열을 가져옵니다. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | 구조체 배열을 가져옵니다 [Color](/psd/python-net/aspose.psd/color/) 구조체. |
| entries_count | int | r | 엔트리 수를 가져옵니다. |
| has_transparent_color | bool | r | 투명 색상이 존재하는지 여부를 나타내는 값을 가져옵니다. |
| is_compact_palette | bool | r | 컴팩트 팔레트가 사용되는지 여부를 나타내는 값을 가져옵니다. |
| raw_entries | byte | r | 원시 색상 팔레트 엔트리 데이터를 가져옵니다. |
| raw_entries_count | int | r | 원시 색상 팔레트 엔트리 수를 가져옵니다. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | 투명 색상을 가져옵니다. |
| transparent_index | short | r | 투명 색상의 인덱스를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | 인덱스로 32비트 ARGB 팔레트 색상을 가져옵니다. |
| [get_color(index)](#get_color_index_2) | 인덱스로 팔레트 색상을 가져옵니다. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | 가장 가까운 32-bit ARGB 색상의 인덱스를 가져옵니다. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | 가장 가까운 32-bit ARGB 색상의 인덱스를 가져옵니다. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


```
 get_argb_32_color(index) 
```

인덱스로 32비트 ARGB 팔레트 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | int | 32-bit ARGB 팔레트 색상 인덱스. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 색상 팔레트 항목은 <paramref name="index" />에 의해 지정됩니다. |


### Method: get_color(index) {#get_color_index_2}


```
 get_color(index) 
```

인덱스로 팔레트 색상을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | int | 팔레트 색상 인덱스. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 색상 팔레트 항목은 <paramref name="index" />에 의해 지정됩니다. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

가장 가까운 32-bit ARGB 색상의 인덱스를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| argb_32_color | int | 32-bit ARGB 색상. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 가장 가까운 색상의 인덱스. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

가장 가까운 32-bit ARGB 색상의 인덱스를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 가장 가까운 색상의 인덱스. |


