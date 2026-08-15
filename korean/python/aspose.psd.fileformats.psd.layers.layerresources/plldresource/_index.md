---
title: "PlLdResource 클래스"
type: docs
weight: 820
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/
---

**Summary:** Defines the PlLdResource class that contains information about a placed layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.<br/>            It was replaced by SoLdResource in the Adobe� Photoshop� CS3

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlLdResource

**Inheritance:** IPlacedLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| anti_alias_policy | int | r/w | PSD 이미지에서 배치된 레이어의 안티앨리어싱 정책을 가져오거나 설정합니다. |
| 하단 | double | r/w | PSD 이미지에서 배치된 레이어의 하단 위치를 가져오거나 설정합니다. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD 파일에서 배치된 레이어의 경계를 가져오거나 설정합니다. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 수평 메쉬 포인트의 측정 단위를 가져오거나 설정합니다. |
| horizontal_mesh_points | double | r/w | PSD 파일에서 배치된 레이어의 수평 메쉬 포인트를 가져오거나 설정합니다. |
| is_custom | bool | r/w | 이 인스턴스의 워프 스타일이 사용자 지정인지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            true인 경우 메쉬 포인트를 포함합니다. false로 설정하면 메쉬 포인트를 지웁니다. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | 워프 항목을 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| left | double | r/w | PSD 파일에서 배치된 레이어의 왼쪽 위치를 가져오거나 설정합니다. |
| 길이 | int | r | PlLd 리소스의 길이를 바이트 단위로 가져옵니다. |
| page_number | int | r/w | PSD 파일에서 배치된 레이어의 페이지 번호를 가져오거나 설정합니다. |
| perspective | double | r/w | PSD 파일에서 배치된 레이어의 원근값을 가져오거나 설정합니다. |
| perspective_other | double | r/w | PSD 파일에서 배치된 레이어의 기타 원근값을 가져오거나 설정합니다. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | PSD 파일에서 배치된 레이어의 유형을 가져오거나 설정합니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| right | double | r/w | PSD 파일에서 배치된 레이어의 오른쪽 위치를 가져오거나 설정합니다. |
| signature | int | r | 서명을 가져옵니다. |
| top | double | r/w | PSD 이미지에서 배치된 레이어의 상단 위치를 가져오거나 설정합니다. |
| total_pages | int | r/w | PSD 파일에서 배치된 레이어의 전체 페이지 수를 가져오거나 설정합니다. |
| transform_matrix | double | r/w | PSD 파일에서 배치된 레이어의 변환 행렬을 가져오거나 설정합니다. |
| u_order | int | r/w | PSD 파일에서 배치된 레이어의 U 순서 값을 가져오거나 설정합니다. |
| unique_id | Guid | r/w | PSD 이미지에서 배치된 레이어의 전역 고유 식별자를 가져오거나 설정합니다. |
| v_order | int | r/w | PSD 파일에서 배치된 레이어의 V 순서 값을 가져오거나 설정합니다. |
| 값 | double | r/w | PSD 이미지에서 배치된 레이어의 워프 값을 가져오거나 설정합니다. |
| version | int | r | PSD 파일에서 배치된 레이어의 버전을 가져옵니다(보통 3). |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 수직 메쉬 포인트의 측정 단위를 가져오거나 설정합니다. |
| vertical_mesh_points | double | r/w | PSD 파일에서 배치된 레이어의 수평 메쉬 포인트를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | PlLD 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

PlLD 리소스를 지정된 스트림 컨테이너에 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |
| psd_version | int | PSD 버전. |

