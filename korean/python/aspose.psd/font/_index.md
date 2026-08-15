---
title: "Font 클래스"
type: docs
weight: 1340
url: /ko/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | 지정된 크기를 사용하여 새 [Font](/psd/python-net/aspose.psd/font/)를 초기화합니다. 문자 집합은 [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)으로, 그래픽 단위는 [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/)으로, 글꼴 스타일은 [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/)으로 설정됩니다. |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | 지정된 크기와 스타일을 사용하여 새 [Font](/psd/python-net/aspose.psd/font/)를 초기화합니다. 문자 집합은 [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)으로, 그래픽 단위는 [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/)으로 설정됩니다. |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | 지정된 크기, 스타일 및 단위를 사용하여 새 [Font](/psd/python-net/aspose.psd/font/)를 초기화합니다. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | 지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새 [Font](/psd/python-net/aspose.psd/font/)를 초기화합니다. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | 지정된 크기와 단위를 사용하여 새 [Font](/psd/python-net/aspose.psd/font/)를 초기화합니다. 문자 집합은 [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)으로, 스타일은 [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/)으로 설정됩니다. |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | 지정된 기존 [Font](/psd/python-net/aspose.psd/font/) 및 [FontStyle](/psd/python-net/aspose.psd/fontstyle/) 열거형을 사용하는 새 [Font](/psd/python-net/aspose.psd/font/)를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| bold | bool | r | 이 [Font](/psd/python-net/aspose.psd/font/)이 굵게 표시되는지 여부를 나타내는 값을 가져옵니다. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | 이 [Font](/psd/python-net/aspose.psd/font/)이 사용하는 문자 집합을 지정하는 바이트 값을 가져옵니다. |
| italic | bool | r | 이 [Font](/psd/python-net/aspose.psd/font/)이 이탤릭인지 여부를 나타내는 값을 가져옵니다. |
| name | string | r | 이 [Font](/psd/python-net/aspose.psd/font/)의 글꼴 이름을 가져옵니다. |
| size | float | r | 이 [Font](/psd/python-net/aspose.psd/font/)의 em-크기를 [Font.unit](/psd/python-net/aspose.psd/font/) 속성에서 지정한 단위로 측정하여 가져옵니다. |
| strikeout | bool | r | 이 [Font](/psd/python-net/aspose.psd/font/)이 글꼴에 가로선을 지정하는지 여부를 나타내는 값을 가져옵니다. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | 이 [Font](/psd/python-net/aspose.psd/font/)에 대한 스타일 정보를 가져옵니다. |
| underline | bool | r | 이 [Font](/psd/python-net/aspose.psd/font/)에 밑줄이 있는지 여부를 나타내는 값을 가져옵니다. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | 이 [Font](/psd/python-net/aspose.psd/font/)의 측정 단위를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | 이 [Font](/psd/python-net/aspose.psd/font/)의 정확한 깊은 복사본을 생성합니다. |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

지정된 크기를 사용하여 새 [Font](/psd/python-net/aspose.psd/font/)를 초기화합니다. 문자 집합은 [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)으로, 그래픽 단위는 [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/)으로, 글꼴 스타일은 [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/)으로 설정됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 이름의 문자열 표현입니다. |
| em_size | float | 새 글꼴의 em-size(포인트 단위)입니다. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

지정된 크기와 스타일을 사용하여 새 [Font](/psd/python-net/aspose.psd/font/)를 초기화합니다. 문자 집합은 [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)으로, 그래픽 단위는 [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/)으로 설정됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 이름의 문자열 표현입니다. |
| em_size | float | 새 글꼴의 em-size(포인트 단위)입니다. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | 새 글꼴의 [FontStyle](/psd/python-net/aspose.psd/fontstyle/)입니다. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

지정된 크기, 스타일 및 단위를 사용하여 새 [Font](/psd/python-net/aspose.psd/font/)를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 이름의 문자열 표현입니다. |
| em_size | float | 새 글꼴의 em-size이며, <paramref name="unit" /> 매개변수에 지정된 단위로 표시됩니다. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | 새 글꼴의 [FontStyle](/psd/python-net/aspose.psd/fontstyle/)입니다. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 새 글꼴의 [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/)입니다. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새 [Font](/psd/python-net/aspose.psd/font/)를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 이름의 문자열 표현입니다. |
| em_size | float | 새 글꼴의 em-size이며, <paramref name="unit" /> 매개변수에 지정된 단위로 표시됩니다. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | 새 글꼴의 [FontStyle](/psd/python-net/aspose.psd/fontstyle/)입니다. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 새 글꼴의 [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/)입니다. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | 이 글꼴에 사용할 문자 집합입니다. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

지정된 크기와 단위를 사용하여 새 [Font](/psd/python-net/aspose.psd/font/)를 초기화합니다. 문자 집합은 [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)으로, 스타일은 [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/)으로 설정됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 이름의 문자열 표현입니다. |
| em_size | float | 새 글꼴의 em-size이며, <paramref name="unit" /> 매개변수에 지정된 단위로 표시됩니다. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 새 글꼴의 [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/)입니다. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

지정된 기존 [Font](/psd/python-net/aspose.psd/font/) 및 [FontStyle](/psd/python-net/aspose.psd/fontstyle/) 열거형을 사용하는 새 [Font](/psd/python-net/aspose.psd/font/)를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 새 [Font](/psd/python-net/aspose.psd/font/)을 생성할 기존 [Font](/psd/python-net/aspose.psd/font/)입니다. |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | 새 [Font](/psd/python-net/aspose.psd/font/)에 적용할 [FontStyle](/psd/python-net/aspose.psd/fontstyle/). [FontStyle](/psd/python-net/aspose.psd/fontstyle/) 열거형의 여러 값을 OR 연산자로 결합할 수 있습니다. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

이 [Font](/psd/python-net/aspose.psd/font/)의 정확한 깊은 복사본을 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 이 메서드가 생성하는 [Font](/psd/python-net/aspose.psd/font/)입니다. |


