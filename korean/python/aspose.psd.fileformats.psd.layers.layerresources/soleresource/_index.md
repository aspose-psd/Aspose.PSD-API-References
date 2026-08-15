---
title: "SoLeResource 클래스"
type: docs
weight: 940
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/
---

**Summary:** Defines the SoLeResource class that contains information about a smart object layer in a PSD file.<br/>            Is is used to support smart object layers with external file links in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SoLeResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, SmartObjectResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [SoLeResource()](#SoLeResource__1) | 새로운 [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) 클래스의 인스턴스를 초기화합니다. |
| [SoLeResource(unique_id, is_custom, has_comp_info)](#SoLeResource_unique_id_is_custom_has_comp_info_2) | 새로운 [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) 클래스의 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 형식 도구 정보 키: 'SoLE'. |
| anti_alias_policy | int | r/w | PSD 이미지에서 스마트 오브젝트 레이어 데이터의 안티앨리어스 정책을 가져오거나 설정합니다. |
| 하단 | double | r/w | PSD 이미지에서 배치된 레이어의 하단 위치를 가져오거나 설정합니다. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD 파일에서 배치된 레이어의 경계를 가져오거나 설정합니다. |
| comp | int | r/w | PSD 파일에서 스마트 오브젝트 레이어 데이터의 comp 값을 가져오거나 설정합니다.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">스마트 오브젝트의 레이어 컴프</see> |
| comp_id | int | r/w | 현재 선택된 컴프의 ID를 가져오거나 설정합니다. 자식 문서에 대해 선택된 것이 없으면 -1이 됩니다.<br/>            컴프는 디자이너가 만들 수 있는 페이지 레이아웃의 구성을 의미합니다. 레이어 컴프를 사용하면 단일 Adobe® Photoshop® 파일에서 레이아웃의 여러 버전을 만들고, 관리하고, 볼 수 있습니다.<br/>            레이어 컴프는 레이어 패널 상태의 스냅샷입니다. 레이어 컴프는 세 가지 유형의 레이어 옵션을 저장하지만, 이 속성은 PSD 파일의 스마트 오브젝트 레이어에 대한 레이어 컴프 선택 식별자를 가져옵니다.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">스마트 오브젝트의 레이어 컴프</see> |
| crop | int | r/w | PSD 이미지에서 스마트 오브젝트 레이어 데이터의 크롭을 가져오거나 설정합니다. |
| duration_denominator | int | r/w | 지속 시간 분모를 가져오거나 설정합니다. |
| duration_numerator | int | r/w | 지속 시간 분자를 가져오거나 설정합니다. |
| frame_count | int | r/w | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 프레임 수를 가져오거나 설정합니다. |
| frame_step_denominator | int | r/w | 프레임 단계 분모를 가져오거나 설정합니다. |
| frame_step_numerator | int | r/w | 프레임 단계 분자를 가져오거나 설정합니다. |
| 높이 | double | r/w | 높이를 가져오거나 설정합니다. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 수평 메쉬 포인트의 측정 단위를 가져오거나 설정합니다. |
| horizontal_mesh_points | double | r/w | PSD 파일에서 배치된 레이어의 수평 메쉬 포인트를 가져오거나 설정합니다. |
| is_custom | bool | r/w | 이 인스턴스의 워프 스타일이 사용자 지정인지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            true인 경우 메쉬 포인트를 포함합니다. false로 설정하면 메쉬 포인트를 지웁니다. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 디스크립터 항목을 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| left | double | r/w | PSD 파일에서 배치된 레이어의 왼쪽 위치를 가져오거나 설정합니다. |
| 길이 | int | r | 스마트 오브젝트 리소스 길이를 바이트 단위로 가져옵니다. |
| non_affine_transform_matrix | double | r/w | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 비선형 변환 행렬을 가져오거나 설정합니다. |
| original_comp_id | int | r | 현재 선택된 자식 문서의 Comp 원래 ID를 가져옵니다. 선택된 것이 없으면 -1이 됩니다.<br/>            이 속성은 PSD 파일의 스마트 오브젝트 레이어에 대한 원래 레이어 Comp 선택 식별자를 가져옵니다.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">스마트 오브젝트의 레이어 컴프</see> |
| page_number | int | r/w | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 페이지 번호를 가져오거나 설정합니다. |
| perspective | double | r/w | PSD 파일에서 배치된 레이어의 원근값을 가져오거나 설정합니다. |
| perspective_other | double | r/w | PSD 파일에서 배치된 레이어의 기타 원근값을 가져오거나 설정합니다. |
| placed_id | Guid | r/w | PSD 이미지의 이 스마트 오브젝트 레이어 데이터에 대한 고유 식별자를 가져오거나 설정합니다. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | PSD 파일의 스마트 오브젝트 레이어 데이터 유형을 가져오거나 설정합니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| resolution | double | r/w | PSD 파일의 스마트 오브젝트 레이어 데이터 해상도를 가져오거나 설정합니다. |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | PSD 파일의 스마트 오브젝트 레이어 데이터 해상도 측정 단위를 가져오거나 설정합니다. |
| right | double | r/w | PSD 파일에서 배치된 레이어의 오른쪽 위치를 가져오거나 설정합니다. |
| signature | int | r | 서명을 가져옵니다. |
| top | double | r/w | PSD 이미지에서 배치된 레이어의 상단 위치를 가져오거나 설정합니다. |
| total_pages | int | r/w | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 전체 페이지 수를 가져오거나 설정합니다. |
| transform_matrix | double | r/w | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 변환 행렬을 가져오거나 설정합니다. |
| u_order | int | r/w | PSD 파일에서 배치된 레이어의 U 순서 값을 가져오거나 설정합니다. |
| unique_id | Guid | r/w | PSD 이미지의 스마트 오브젝트 레이어 데이터 [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/)에 대한 전역 고유 식별자를 가져오거나 설정합니다. |
| v_order | int | r/w | PSD 파일에서 배치된 레이어의 V 순서 값을 가져오거나 설정합니다. |
| 값 | double | r/w | PSD 이미지에서 배치된 레이어의 워프 값을 가져오거나 설정합니다. |
| version | int | r | PSD 파일에 배치된 레이어의 버전을 가져옵니다. 일반적으로 3-5입니다. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 수직 메쉬 포인트의 측정 단위를 가져오거나 설정합니다. |
| vertical_mesh_points | double | r/w | PSD 파일에서 배치된 레이어의 수평 메쉬 포인트를 가져오거나 설정합니다. |
| width | double | r/w | 너비를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 스마트 객체 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: SoLeResource() {#SoLeResource__1}


```
 SoLeResource() 
```

새로운 [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) 클래스의 인스턴스를 초기화합니다.

### Constructor: SoLeResource(unique_id, is_custom, has_comp_info) {#SoLeResource_unique_id_is_custom_has_comp_info_2}


```
 SoLeResource(unique_id, is_custom, has_comp_info) 
```

새로운 [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) 클래스의 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| unique_id | Guid | 배치된 레이어 데이터 [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/)의 고유 식별자입니다. |
| is_custom | bool | 설정된 경우 <c>true</c> [is custom]. |
| has_comp_info | bool | 설정된 경우 <c>true</c> [has comp information]. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

스마트 객체 리소스를 지정된 스트림 컨테이너에 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |
| psd_version | int | PSD 버전. |

