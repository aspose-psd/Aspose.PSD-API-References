---
title: "IText 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | 항목을 가져옵니다. |
| text | 문자열 | r | 텍스트를 가져옵니다. |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | 텍스트 방향을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | 텍스트 부분을 끝에 추가합니다 |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | 지정된 위치에 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)을 삽입합니다 |
| [produce_portion()](#produce_portion__3) | 기본 매개변수로 새로운 부분을 생성합니다 |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | 입력 매개변수 또는 기본 매개변수로 새로운 부분들을 생성합니다. |
| [remove_portion(index)](#remove_portion_index_5) | 지정된 인덱스의 부분을 제거합니다 |
| update_layer_data() | 레이어 데이터를 업데이트합니다. |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

텍스트 부분을 끝에 추가합니다

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | 해당 부분. |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

지정된 위치에 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)을 삽입합니다

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | 해당 부분. |
| index | int | 인덱스. |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

기본 매개변수로 새로운 부분을 생성합니다

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | 새로 생성된 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)에 대한 참조입니다. |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

입력 매개변수 또는 기본 매개변수로 새로운 부분들을 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| portions_of_text | string | 새로운 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)을 만들기 위한 텍스트 부분들. |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | null이 아닌 경우 새로운 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)에 적용되는 스타일이며, 그렇지 않으면 기본값이 됩니다. |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | null이 아닌 경우 새로운 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)에 적용되는 단락이며, 그렇지 않으면 기본값이 됩니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | 입력 매개변수를 기반으로 새로운 [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) 부분들을 반환합니다. |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

지정된 인덱스의 부분을 제거합니다

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | int | 인덱스. |

