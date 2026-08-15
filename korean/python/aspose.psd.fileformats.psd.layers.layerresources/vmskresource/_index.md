---
title: "VmskResource 클래스"
type: docs
weight: 1100
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/
---

**Summary:** Class VmskResource.<br/>            This resource contains information about vector layer mask

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VmskResource

**Inheritance:** IVectorPathData, VectorPathDataResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [VmskResource()](#VmskResource__1) | 새로운 [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) 클래스의 인스턴스를 초기화합니다. |
| [VmskResource(data)](#VmskResource_data_2) | 새로운 [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) 클래스의 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| is_disabled | bool | r/w | 이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| is_inverted | bool | r/w | 이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| is_not_linked | bool | r/w | 이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | 경로 레코드를 가져오거나 설정합니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
| version | int | r/w | 버전을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: VmskResource() {#VmskResource__1}


```
 VmskResource() 
```

새로운 [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) 클래스의 인스턴스를 초기화합니다.

### Constructor: VmskResource(data) {#VmskResource_data_2}


```
 VmskResource(data) 
```

새로운 [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) 클래스의 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 데이터 | byte | 리소스 데이터. |

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

