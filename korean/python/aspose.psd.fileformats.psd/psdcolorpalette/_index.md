---
title: "PsdColorPalette 클래스"
type: docs
weight: 1750
url: /ko/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | 새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스. |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | 새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스. |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | 새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스. |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | 새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스이며 IsCompactPalette는 false입니다. |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | 새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스. |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | 새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스이며 IsCompactPalette는 false입니다. |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | 새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스. |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | 새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스이며 IsCompactPalette는 false입니다. |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | 새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스. |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | 새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스이며 IsCompactPalette는 false입니다. |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | 새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 32비트 ARGB 색상의 배열을 가져옵니다. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | 구조체 배열을 가져옵니다 [Color](/psd/python-net/aspose.psd/color/) 구조체. |
| entries_count | int | r | 엔트리 수를 가져옵니다. |
| has_transparent_color | bool | r | 투명 색상이 존재하는지 여부를 나타내는 값을 가져옵니다. |
| is_compact_palette | bool | r | 팔레트가 압축되었는지 여부를 나타내는 값을 가져옵니다. |
| raw_entries | byte | r | 원시 색상 팔레트 엔트리 데이터를 가져옵니다. |
| raw_entries_count | int | r | 원시 색상 팔레트 엔트리 수를 가져옵니다. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | 투명 색상을 가져옵니다. |
| transparent_index | short | r | 투명 색상의 인덱스를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | 팔레트를 복사합니다. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | 팔레트를 복사합니다. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | 인덱스로 32비트 ARGB 팔레트 색상을 가져옵니다. |
| [get_color(index)](#get_color_index_4) | 인덱스로 팔레트 색상을 가져옵니다. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | 가장 가까운 색상의 인덱스를 가져옵니다. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | 가장 가까운 색상의 인덱스를 가져옵니다. |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 색상 팔레트. |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 색상 팔레트. |
| transparent_index | short | 투명 색상 인덱스. |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_palette_argb_32_entries | int | 색상 팔레트 32비트 ARGB 항목. |
| is_compact_palette | bool | 팔레트가 압축되는지 여부를 나타냅니다. |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스이며 IsCompactPalette는 false입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | 색상 팔레트 항목. |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | 색상 팔레트 항목. |
| is_compact_palette | bool | 팔레트가 압축되는지 여부를 나타냅니다. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스이며 IsCompactPalette는 false입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | 색상 팔레트 항목. |
| transparent_index | short | 투명 색상 인덱스. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | 색상 팔레트 항목. |
| transparent_index | short | 투명 색상 인덱스. |
| use_compact_palette | bool | 팔레트가 압축되는지 여부를 나타냅니다. |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스이며 IsCompactPalette는 false입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| raw_entries_data | byte | 원시 항목 데이터. |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| raw_entries_data | byte | 원시 항목 데이터. |
| is_compact_palette | bool | 팔레트가 압축되는지 여부를 나타냅니다. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스이며 IsCompactPalette는 false입니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| raw_entries_data | byte | 원시 항목 데이터. |
| transparent_index | short | 투명 색상 인덱스. 참고로 이 인덱스는 원시 항목 인덱스가 아니라 변환된 색상 배열을 위한 것입니다. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

새 인스턴스를 초기화합니다 [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| raw_entries_data | byte | 원시 항목 데이터. |
| transparent_index | short | 투명 색상 인덱스. 참고로 이 인덱스는 원시 항목 인덱스가 아니라 변환된 색상 배열을 위한 것입니다. |
| use_compact_palette | bool | 팔레트가 압축되는지 여부를 나타냅니다. |

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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | 새로 생성되고 복사된 팔레트이며, null 팔레트가 전달된 경우 null을 반환합니다. |


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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | 새로 생성되고 복사된 팔레트이며, null 팔레트가 전달된 경우 null을 반환합니다. |


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


