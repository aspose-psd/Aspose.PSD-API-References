---
title: "LevlResource 클래스"
type: docs
weight: 490
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) 클래스의 새 인스턴스를 초기화합니다. |
| [LevlResource(bytes)](#LevlResource_bytes_2) | [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) 클래스의 새 인스턴스를 초기화합니다.<br/>            GrayScale, Duotone, RGB, CMYK, Lab 색상 모드에서 지원됩니다.<br/>            2 바이트 - 버전 (=2)<br/>            29 * 10 바이트 - 5개의 short 정수로 구성된 레벨 레코드 집합<br/>            4 바이트 - Lvls 헤더 (인덱스 292에서 시작)<br/>            2 바이트 - 버전 (=3)<br/>            2 바이트 - 전체 레벨 레코드 수<br/>            10 * (전체 수 - 29)<br/>            Lvls 리소스의 0 종료는 네 개에도 접어야 합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
| version | short | r | 버전을 가져옵니다. 기본값은 2입니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | 채널을 가져옵니다. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

[LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) 클래스의 새 인스턴스를 초기화합니다.

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

[LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) 클래스의 새 인스턴스를 초기화합니다.<br/>            GrayScale, Duotone, RGB, CMYK, Lab 색상 모드에서 지원됩니다.<br/>            2 바이트 - 버전 (=2)<br/>            29 * 10 바이트 - 5개의 short 정수로 구성된 레벨 레코드 집합<br/>            4 바이트 - Lvls 헤더 (인덱스 292에서 시작)<br/>            2 바이트 - 버전 (=3)<br/>            2 바이트 - 전체 레벨 레코드 수<br/>            10 * (전체 수 - 29)<br/>            Lvls 리소스의 0 종료는 네 개에도 접어야 합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 바이트 | byte | 바이트입니다. |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

채널을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| channel_index | int | 채널의 인덱스. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | 채널의 레벨 데이터 |


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

