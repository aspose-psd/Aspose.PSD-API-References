---
title: "ColorRangeHsl 클래스"
type: docs
weight: 180
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | 새 인스턴스를 초기화합니다 [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) 클래스. |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | 새 인스턴스를 초기화합니다 [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| hue | short | r/w | hue를 가져오거나 설정합니다. |
| left_border | short | r/w | 왼쪽 경계를 가져오거나 설정합니다. |
| lightness | short | r/w | lightness를 가져오거나 설정합니다. |
| most_left_border | short | r/w | 가장 왼쪽 경계를 가져오거나 설정합니다. |
| most_right_border | short | r/w | 가장 오른쪽 경계를 가져오거나 설정합니다. |
| right_border | short | r/w | 오른쪽 경계를 가져오거나 설정합니다. |
| 채도 | short | r/w | 채도를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | 범위 계수를 가져옵니다. |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | 색조가 큰 범위에 있는지 여부를 결정합니다. |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | 색조가 작은 범위에 있는지 여부를 결정합니다. |
| [save(stream_container)](#save_stream_container_4) | 지정된 스트림 컨테이너에 데이터를 저장합니다. |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

새 인스턴스를 초기화합니다 [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) 클래스.

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

새 인스턴스를 초기화합니다 [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 색상 범위 데이터. |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

범위 계수를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| hue | double | 색조 값. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| double | 채도 범위 계수. |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

색조가 큰 범위에 있는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| hue | double | 색조 값. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 색조가 큰 범위에 있으면 <c>true</c>; 그렇지 않으면 <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

색조가 작은 범위에 있는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| hue | double | 색조 값. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 색조가 작은 범위에 있으면 <c>true</c>, 그렇지 않으면 <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

지정된 스트림 컨테이너에 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |

