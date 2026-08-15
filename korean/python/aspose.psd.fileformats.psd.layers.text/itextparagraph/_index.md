---
title: "ITextParagraph 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---

**Summary:** The interface to work with paragraph

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextParagraph

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| auto_hyphenate | bool | r/w | [automatic hyphenate]인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| auto_leading | double | r/w | 자동 리딩을 가져오거나 설정합니다. |
| burasagari | bool | r/w | 이 [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/)가 burasagiri인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| consecutive_hyphens | int | r/w | 연속 하이픈을 가져오거나 설정합니다. |
| end_indent | double | r/w | 끝 들여쓰기를 가져오거나 설정합니다. |
| every_line_composer | bool | r/w | [every line composer]인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| first_line_indent | double | r/w | 첫 줄 들여쓰기를 가져오거나 설정합니다. |
| glyph_spacing | double | r/w | 글리프 간격을 가져오거나 설정합니다. |
| hanging | bool | r/w | 이 [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/)가 hanging인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| hyphenated_word_size | int | r/w | 하이픈이 포함된 단어의 크기를 가져오거나 설정합니다. |
| justification | [JustificationMode](/psd/python-net/aspose.psd.fileformats.psd/justificationmode) | r/w | 정렬을 가져오거나 설정합니다. |
| kinsoku_order | int | r/w | 킨소쿠 순서를 가져오거나 설정합니다. |
| leading_type | [LeadingType](/psd/python-net/aspose.psd.fileformats.psd/leadingtype) | r/w | 리딩 유형을 가져오거나 설정합니다. |
| letter_spacing | double | r/w | 문자 간격을 가져오거나 설정합니다. |
| post_hyphen | int | r/w | 포스트 하이픈을 가져오거나 설정합니다. |
| pre_hyphen | int | r/w | 프리 하이픈을 가져오거나 설정합니다. |
| space_after | double | r/w | 공백 뒤를 가져오거나 설정합니다. |
| space_before | double | r/w | 공백 앞을 가져오거나 설정합니다. |
| start_indent | double | r/w | 시작 들여쓰기를 가져오거나 설정합니다. |
| word_spacing | double | r/w | 단어 간격을 가져오거나 설정합니다. |
| zone | double | r/w | 영역을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [apply(paragraph)](#apply_paragraph_1) | 지정된 단락을 적용합니다. |
| [is_equal(paragraph)](#is_equal_paragraph_2) | 지정된 단락이 같은지 여부를 결정합니다. |


### Method: apply(paragraph) {#apply_paragraph_1}


```
 apply(paragraph) 
```

지정된 단락을 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| paragraph | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | 단락. |

### Method: is_equal(paragraph) {#is_equal_paragraph_2}


```
 is_equal(paragraph) 
```

지정된 단락이 같은지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| paragraph | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | 단락. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 단락이 같은 경우 <c>true</c>; 그렇지 않으면 <c>false</c>. |


