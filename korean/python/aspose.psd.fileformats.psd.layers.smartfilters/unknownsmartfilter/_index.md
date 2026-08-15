---
title: "UnknownSmartFilter 클래스"
type: docs
weight: 70
url: /ko/python-net/aspose.psd.fileformats.psd.layers.smartfilters/unknownsmartfilter/
---

**Summary:** The class to hold unknown smart filter data.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.UnknownSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | 블렌딩 모드를 가져오거나 설정합니다. |
| filter_id | int | r | 스마트 필터 유형 식별자를 가져옵니다. |
| is_enabled | bool | r/w | 스마트 필터의 활성화 상태를 가져오거나 설정합니다. |
| name | 문자열 | r | 스마트 필터 이름을 가져옵니다. |
| opacity | double | r/w | 스마트 필터의 불투명도 값을 가져오거나 설정합니다. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | 스마트 필터 데이터가 포함된 소스 디스크립터 구조입니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | 현재 필터를 입력 [RasterImage](/psd/python-net/aspose.psd/rasterimage/) 이미지에 적용합니다. |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | 현재 필터를 입력 [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 마스크 데이터에 적용합니다. |
| [clone()](#clone__3) | 현재 인스턴스의 멤버별 복제본을 생성합니다. |


### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

현재 필터를 입력 [RasterImage](/psd/python-net/aspose.psd/rasterimage/) 이미지에 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 래스터 이미지. |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

현재 필터를 입력 [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 마스크 데이터에 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 마스크 데이터가 포함된 레이어입니다. |

### Method: clone() {#clone__3}


```
 clone() 
```

현재 인스턴스의 멤버별 복제본을 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | 현재 인스턴스의 멤버별 복제본을 반환합니다. |


