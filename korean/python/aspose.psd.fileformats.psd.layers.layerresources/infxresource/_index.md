---
title: "InfxResource 클래스"
type: docs
weight: 420
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/
---

**Summary:** Class InfxResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.InfxResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [InfxResource()](#InfxResource__1) | [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) 클래스의 새 인스턴스를 초기화합니다. |
| [InfxResource(blend_interior_elements)](#InfxResource_blend_interior_elements_2) | [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) 클래스의 새 인스턴스를 초기화합니다. |
| [InfxResource(data)](#InfxResource_data_3) | [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) 클래스의 새 인스턴스를 초기화합니다.<br/>            사용자 지정 또는 알 수 없는 값과 함께 |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| blend_interior_elements | bool | r/w | [blend interior elements]인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 지정된 스트림 컨테이너를 저장합니다. |


### Constructor: InfxResource() {#InfxResource__1}


```
 InfxResource() 
```

[InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) 클래스의 새 인스턴스를 초기화합니다.

### Constructor: InfxResource(blend_interior_elements) {#InfxResource_blend_interior_elements_2}


```
 InfxResource(blend_interior_elements) 
```

[InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| blend_interior_elements | bool | 설정이 <c>true</c>이면 [blend interior elements]입니다. |

### Constructor: InfxResource(data) {#InfxResource_data_3}


```
 InfxResource(data) 
```

[InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) 클래스의 새 인스턴스를 초기화합니다.<br/>            사용자 지정 또는 알 수 없는 값과 함께

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 리소스 데이터. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

지정된 스트림 컨테이너를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| psd_version | int | PSD 버전. |

