---
title: "BlwhResource 클래스"
type: docs
weight: 90
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | BlwhResource 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| black_and_white_preset_file_name | 문자열 | r/w | 흑백 프리셋 파일 이름을 가져오거나 설정합니다. |
| 블루 | int | r/w | 블루 값을 가져오거나 설정합니다. |
| bw_preset_kind | int | r/w | 흑백 프리셋 종류 값을 가져오거나 설정합니다. |
| 시안 | int | r/w | 시안 값을 가져오거나 설정합니다. |
| 그린 | int | r/w | 그린 값을 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| 마젠타 | int | r/w | 마젠타 값을 가져오거나 설정합니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| 레드 | int | r/w | reds 값을 가져오거나 설정합니다. |
| signature | int | r | 서명을 가져옵니다. |
| tint_color | int | r/w | Tint Color ARGB 값을 가져오거나 설정합니다. |
| use_tint | bool | r/w | [tint color]가 사용되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| yellows | int | r/w | yellows 값을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

BlwhResource 클래스의 새 인스턴스를 초기화합니다.

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

