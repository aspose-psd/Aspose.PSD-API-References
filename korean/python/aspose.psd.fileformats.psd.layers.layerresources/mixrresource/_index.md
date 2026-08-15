---
title: "MixrResource 클래스"
type: docs
weight: 680
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | 새 인스턴스를 초기화합니다 [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) 클래스.<br/>            PSD 형식 사양에는 다음 설명이 포함됩니다:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB 또는 CMYK 색상과 믹서 설정을 위한 상수가 포함됩니다. 색상 4 * 2 바이트와 상수 2 바이트. |
| [MixrResource(data)](#MixrResource_data_2) | 새 인스턴스를 초기화합니다 [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) 클래스.<br/>            PSD 형식 사양에는 다음 설명이 포함됩니다:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB 또는 CMYK 색상과 믹서 설정을 위한 상수가 포함됩니다. 색상 4 * 2 바이트와 상수 2 바이트. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| monochrome | bool | r/w | 이 [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/)가 단색인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
| version | short | r/w | 버전을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | 채널 정보 원시 데이터를 가져옵니다 |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | 채널 정보를 설정합니다. |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

새 인스턴스를 초기화합니다 [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) 클래스.<br/>            PSD 형식 사양에는 다음 설명이 포함됩니다:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB 또는 CMYK 색상과 믹서 설정을 위한 상수가 포함됩니다. 색상 4 * 2 바이트와 상수 2 바이트.

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

새 인스턴스를 초기화합니다 [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) 클래스.<br/>            PSD 형식 사양에는 다음 설명이 포함됩니다:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB 또는 CMYK 색상과 믹서 설정을 위한 상수가 포함됩니다. 색상 4 * 2 바이트와 상수 2 바이트.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 리소스의 데이터. |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

채널 정보 원시 데이터를 가져옵니다

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| channel_index | int | 채널의 인덱스. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| byte | 채널 정보의 원시 바이트 배열. |


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

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

채널 정보를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| channel_index | int | 채널의 인덱스. |
| 값 | byte | 값입니다. |

