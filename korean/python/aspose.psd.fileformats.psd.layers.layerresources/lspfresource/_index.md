---
title: "LspfResource 클래스"
type: docs
weight: 640
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Summary:** Layer protected settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LspfResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [LspfResource()](#LspfResource__1) | 새로운 [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) 클래스의 인스턴스를 초기화합니다. |
| [LspfResource(data)](#LspfResource_data_2) | 새로운 [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) 클래스의 인스턴스를 초기화합니다.<br/>            사용자 지정 또는 알 수 없는 값과 함께 |
| [LspfResource(is_transparency_protected, is_composite_protected, is_position_protected)](#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3) | 새로운 [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) 클래스의 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 형식 도구 정보 키 1819504742 |
| is_composite_protected | bool | r/w | 이 인스턴스가 복합 보호인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| is_position_protected | bool | r/w | 이 인스턴스가 위치 보호인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| is_transparency_protected | bool | r/w | 이 인스턴스가 투명도 보호인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| lock_type | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype) | r/w | 잠금 유형을 가져오거나 설정합니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: LspfResource() {#LspfResource__1}


```
 LspfResource() 
```

새로운 [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) 클래스의 인스턴스를 초기화합니다.

### Constructor: LspfResource(data) {#LspfResource_data_2}


```
 LspfResource(data) 
```

새로운 [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) 클래스의 인스턴스를 초기화합니다.<br/>            사용자 지정 또는 알 수 없는 값과 함께

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 리소스 데이터. |

### Constructor: LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) {#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3}


```
 LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) 
```

새로운 [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) 클래스의 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| is_transparency_protected | bool | 설정이 <c>true</c>이면 [투명도 보호됨]입니다. |
| is_composite_protected | bool | 설정이 <c>true</c>이면 [합성 보호됨]입니다. |
| is_position_protected | bool | 설정이 <c>true</c>이면 [위치 보호됨]입니다. |

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

