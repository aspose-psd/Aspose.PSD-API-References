---
title: "ITextStyle 클래스"
type: docs
weight: 40
url: /ko/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | 자동 커닝을 가져오거나 설정합니다. |
| auto_leading | bool | r/w | 자동 리딩 여부를 나타내는 값을 가져오거나 설정합니다. |
| baseline_shift | double | r/w | 기준선 이동. |
| contextual_alternates | bool | r/w | 문자를 연결하는 데 사용되는 문맥 대체 문자. |
| discretionary_ligatures | bool | r/w | 특히 스크립트 글꼴에서 문자들을 연결하는 데 사용되는 선택적 합자입니다. |
| faux_bold | bool | r/w | 가짜 faux bold가 활성화되는지 가져오거나 설정합니다. |
| faux_italic | bool | r/w | 가짜 faux bold가 활성화되는지 가져오거나 설정합니다. |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 채우기 색상을 가져오거나 설정합니다. |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | 글꼴 기준선입니다. |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | 글꼴 대문자 형태입니다. |
| font_index | int | r | 글꼴 인덱스를 가져옵니다. |
| font_name | 문자열 | r/w | 폰트 이름을 가져오거나 설정합니다. |
| font_size | double | r/w | 글꼴 크기를 가져오거나 설정합니다. |
| fractions | bool | r/w | 분수 기호를 특수 글리프로 교체할 수 있습니다. |
| hindi_numbers | bool | r/w | 값을 가져오거나 설정하여 [hindi numbers]인지 여부를 나타냅니다. |
| horizontal_scale | double | r/w | 수평 스케일입니다. |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | 표준 수직 로마 정렬을 가져오거나 설정합니다.<br/>            이 설정은 BaselineDirection 리소스 값을 기반으로 하며 텍스트 방향이 [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/)인 경우에만 적용됩니다. |
| kerning | int | r/w | 커닝을 가져오거나 설정합니다. |
| language_index | int | r | 언어 인덱스를 가져옵니다. |
| leading | double | r/w | 리딩을 가져오거나 설정합니다. |
| no_break | bool | r/w | no break 값을 가져오거나 설정합니다. |
| standard_ligatures | bool | r/w | 문자를 연결하기 위해 사용되는 표준 컨텍스트 합자입니다. |
| strikethrough | bool | r/w | 값을 가져오거나 설정합니다. 이는 [strikethrough]인지 여부를 나타냅니다. |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 획의 색상을 가져오거나 설정합니다. |
| tracking | int | r/w | 트래킹을 가져오거나 설정합니다. |
| underline | bool | r/w | 값을 가져오거나 설정합니다. 이는 [underline]인지 여부를 나타냅니다. |
| vertical_scale | double | r/w | 수직 스케일입니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [apply(style)](#apply_style_1) | 지정된 스타일을 적용합니다. |
| [is_equal(style)](#is_equal_style_2) | 지정된 스타일이 같은지 여부를 결정합니다. |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

지정된 스타일을 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | 스타일입니다. |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

지정된 스타일이 같은지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | 스타일입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <c>true</c> 지정된 스타일이 같은 경우; 그렇지 않으면 <c>false</c>. |


