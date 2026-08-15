---
title: "StringFormat 클래스"
type: docs
weight: 4260
url: /ko/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | 새로운 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체를 초기화합니다. |
| [StringFormat(format)](#StringFormat_format_2) | 지정된 기존 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체를 사용하여 새로운 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체를 초기화합니다. |
| [StringFormat(options)](#StringFormat_options_3) | 지정된 [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) 열거형 및 언어를 사용하여 새로운 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | 수직 평면에서 텍스트 정렬 정보를 가져오거나 설정합니다. |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | 사용자 정의 문자 식별자를 가져오거나 설정합니다. |
| digit_substitution_language | int | r/w | 현지 숫자가 서양 숫자로 대체될 때 사용되는 언어를 가져오거나 설정합니다. |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | 숫자 대체에 사용할 방법을 가져오거나 설정합니다. |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| first_tab_offset | float | r | 텍스트 줄의 시작과 첫 번째 탭 정지점 사이의 공백 수를 가져옵니다. |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | 포맷팅 정보를 포함하는 [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) 열거형을 가져오거나 설정합니다. |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | 일반 기본 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체를 가져옵니다. |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | 일반 타이포그래픽 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체를 가져옵니다. |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | 이 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체에 대한 [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) 객체를 가져오거나 설정합니다. |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | 수평 평면에서 라인 정렬을 가져오거나 설정합니다. |
| tab_stops | float | r | [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) 속성에서 지정한 단위로 탭 정지점 사이의 거리 배열을 가져옵니다. |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | 이 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체에 대한 [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) 열거형을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | 이 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체의 깊은 복제본을 생성합니다. |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | 이 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체에 대한 탭 정지점을 설정합니다. |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

새로운 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체를 초기화합니다.

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

지정된 기존 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체를 사용하여 새로운 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 새 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체를 초기화할 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체입니다. |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

지정된 [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) 열거형 및 언어를 사용하여 새로운 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | 새 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체에 대한 [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) 열거형입니다. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

이 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체의 깊은 복제본을 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | 현재 [StringFormat](/psd/python-net/aspose.psd/stringformat/)의 깊은 복제본입니다. |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

이 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 객체에 대한 탭 정지점을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| first_tab_offset | float | 텍스트 줄의 시작과 첫 번째 탭 정지점 사이의 공백 수입니다. |
| tab_stops | float | [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) 속성에서 지정한 단위로 탭 정지점 사이의 거리 배열입니다. |

