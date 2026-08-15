---
title: "PhflResourceVersion2 클래스"
type: docs
weight: 800
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResourceVersion2

**Inheritance:** PhflResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PhflResourceVersion2()](#PhflResourceVersion2__1) | 새 인스턴스를 초기화합니다 [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) 클래스. |
| [PhflResourceVersion2(data)](#PhflResourceVersion2_data_2) | 새 인스턴스를 초기화합니다 [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| color_space | short | r | 색 공간을 가져옵니다. |
| component_a | short | r/w | 색상의 A 구성 요소를 가져오거나 설정합니다 |
| component_b | short | r/w | B 구성 요소를 가져오거나 설정합니다 |
| component_l | short | r/w | 색상의 L 구성 요소를 가져오거나 설정합니다 |
| density | int | r/w | 밀도를 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| preserve_luminosity | bool | r/w | 값을 가져오거나 설정하여 [preserve luminosity] 여부를 나타냅니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
| version | short | r | 버전을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | 색상을 가져옵니다. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | RGB 색상을 설정합니다. |


### Constructor: PhflResourceVersion2() {#PhflResourceVersion2__1}


```
 PhflResourceVersion2() 
```

새 인스턴스를 초기화합니다 [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) 클래스.

### Constructor: PhflResourceVersion2(data) {#PhflResourceVersion2_data_2}


```
 PhflResourceVersion2(data) 
```

새 인스턴스를 초기화합니다 [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 리소스의 데이터. |

### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

색상을 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | RGB 색상 |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

리소스를 지정된 스트림 컨테이너에 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |
| psd_version | int | PSD 버전. |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

RGB 색상을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | 색상. |

