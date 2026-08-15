---
title: "CustomLineCap 클래스"
type: docs
weight: 1010
url: /ko/python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | 지정된 외곽선과 채우기를 사용하여 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 클래스를 새 인스턴스로 초기화합니다. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | 지정된 기존 [LineCap](/psd/python-net/aspose.psd/linecap/) 열거형과 지정된 외곽선 및 채우기를 사용하여 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 클래스를 새 인스턴스로 초기화합니다. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | 지정된 기존 [LineCap](/psd/python-net/aspose.psd/linecap/) 열거형과 지정된 외곽선, 채우기 및 삽입값을 사용하여 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | 이 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/)이 기반하는 [LineCap](/psd/python-net/aspose.psd/linecap/) 열거형을 가져오거나 설정합니다. |
| base_inset | float | r/w | 캡과 선 사이의 거리를 가져오거나 설정합니다. |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | 사용자 정의 캡의 채우기를 정의하는 개체를 가져오거나 설정합니다. |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | 이 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 객체를 구성하는 선들이 연결되는 방식을 결정하는 [LineJoin](/psd/python-net/aspose.psd/linejoin/) 열거형을 가져오거나 설정합니다. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | 사용자 정의 캡의 외곽선을 정의하는 개체를 가져오거나 설정합니다. |
| width_scale | float | r/w | 이 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 클래스 객체를 해당 객체의 너비에 비례하여 스케일링할 양을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | 이 사용자 정의 캡을 구성하는 선들의 시작 및 끝에 사용되는 캡을 가져옵니다. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | 이 사용자 정의 캡을 구성하는 선들의 시작 및 끝에 사용되는 캡을 설정합니다. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

지정된 외곽선과 채우기를 사용하여 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 클래스를 새 인스턴스로 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 개체로, 사용자 정의 캡의 채우기를 정의합니다. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 개체로, 사용자 정의 캡의 외곽선을 정의합니다. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

지정된 기존 [LineCap](/psd/python-net/aspose.psd/linecap/) 열거형과 지정된 외곽선 및 채우기를 사용하여 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 클래스를 새 인스턴스로 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 개체로, 사용자 정의 캡의 채우기를 정의합니다. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 개체로, 사용자 정의 캡의 외곽선을 정의합니다. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | 사용자 정의 캡을 생성할 기본 선 캡입니다. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

지정된 기존 [LineCap](/psd/python-net/aspose.psd/linecap/) 열거형과 지정된 외곽선, 채우기 및 삽입값을 사용하여 [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 개체로, 사용자 정의 캡의 채우기를 정의합니다. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 개체로, 사용자 정의 캡의 외곽선을 정의합니다. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | 사용자 정의 캡을 생성할 기본 선 캡입니다. |
| base_inset | float | 캡과 선 사이의 거리입니다. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

이 사용자 정의 캡을 구성하는 선들의 시작 및 끝에 사용되는 캡을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | 이 캡 내에서 선의 시작에 사용되는 [LineCap](/psd/python-net/aspose.psd/linecap/) 열거형입니다. |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | 이 캡 내에서 선의 끝에 사용되는 [LineCap](/psd/python-net/aspose.psd/linecap/) 열거형입니다. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

이 사용자 정의 캡을 구성하는 선들의 시작 및 끝에 사용되는 캡을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | 이 캡 내에서 선의 시작에 사용되는 [LineCap](/psd/python-net/aspose.psd/linecap/) 열거형입니다. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | 이 캡 내에서 선의 끝에 사용되는 [LineCap](/psd/python-net/aspose.psd/linecap/) 열거형입니다. |

