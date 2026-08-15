---
title: "CgEdResource 클래스"
type: docs
weight: 130
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | CgEdResource 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| auto | bool | r/w | 이 [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) 가 자동인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| 밝기 | int | r/w | 밝기를 가져오거나 설정합니다. |
| 대비 | int | r/w | 대비를 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| lab_color | bool | r/w | [lab color]가 사용되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| mean_value_for_brightness_and_contrast | int | r/w | 밝기와 대비의 평균 값을 가져오거나 설정합니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
| use_legacy | bool | r/w | [use legacy]가 사용되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| version | int | r/w | 버전을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

CgEdResource 클래스의 새 인스턴스를 초기화합니다.

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

리소스를 지정된 스트림 컨테이너에 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |
| psd_version | int | PSD 버전. |

