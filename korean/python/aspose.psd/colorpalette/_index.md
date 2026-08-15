---
title: "ColorPalette 클래스"
type: docs
weight: 800
url: /ko/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 클래스의 새 인스턴스를 초기화하고 IsCompactPalette는 false입니다. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 클래스의 새 인스턴스를 초기화합니다. |
| [ColorPalette(entries)](#ColorPalette_entries_3) | [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 클래스의 새 인스턴스를 초기화하고 IsCompactPalette는 false입니다. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 32비트 ARGB 구조체 배열을 가져옵니다. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | 구조체 배열을 가져옵니다 [Color](/psd/python-net/aspose.psd/color/) 구조체. |
| entries_count | int | r | 엔트리 수를 가져옵니다. |
| is_compact_palette | bool | r | 컴팩트 팔레트를 사용하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | 팔레트를 복사합니다. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | 팔레트를 복사합니다. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | 인덱스로 32비트 ARGB 팔레트 색상을 가져옵니다. |
| [get_color(index)](#get_color_index_4) | 인덱스로 팔레트 색상을 가져옵니다. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | 가장 가까운 색상의 인덱스를 가져옵니다. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | 가장 가까운 색상의 인덱스를 가져옵니다. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

[ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 클래스의 새 인스턴스를 초기화하고 IsCompactPalette는 false입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| argb_32_entries | int | 32비트 ARGB 색상 팔레트 항목. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

[ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| argb_32_entries | int | 32비트 ARGB 색상 팔레트 항목. |
| is_compact_palette | bool | 팔레트가 압축되는지 여부를 나타냅니다. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

[ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 클래스의 새 인스턴스를 초기화하고 IsCompactPalette는 false입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

[ColorPalette](/psd/python-net/aspose.psd/colorpalette/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | 팔레트가 압축되는지 여부를 나타냅니다. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

팔레트를 복사합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 색상 팔레트. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | 새로 생성되고 복사된 팔레트이며, null 팔레트가 전달된 경우 null을 반환합니다. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

팔레트를 복사합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 색상 팔레트. |
| use_compact_palette | bool | 팔레트가 압축되는지 여부를 나타냅니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | 새로 생성되고 복사된 팔레트이며, null 팔레트가 전달된 경우 null을 반환합니다. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


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


### Method: get_color(index) {#get_color_index_4}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

가장 가까운 색상의 인덱스를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| argb_32_color | int | 32-bit ARGB 색상. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 가장 가까운 색상의 인덱스. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

가장 가까운 색상의 인덱스를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 가장 가까운 색상의 인덱스. |


