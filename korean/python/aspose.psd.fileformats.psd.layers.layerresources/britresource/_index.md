---
title: "BritResource 클래스"
type: docs
weight: 120
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [BritResource()](#BritResource__1) | 새 인스턴스를 초기화합니다 [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) 클래스. |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | 새 인스턴스를 초기화합니다 [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) 클래스. |
| [BritResource(bytes)](#BritResource_bytes_3) | 새 인스턴스를 초기화합니다 [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) 클래스.<br/>            PSD 형식 사양에는 다음 설명이 포함됩니다:<br/>            2 밝기<br/>            2 대비<br/>            2 밝기 및 대비의 평균값<br/>            1 Lab 색상만<br/>            현대 PSD(CS5 이상)에서는 CgEd가 사용됩니다. CgEd는 정보 속성을 저장합니다 |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| 밝기 | short | r/w | 밝기를 가져오거나 설정합니다. |
| 대비 | short | r/w | 대비를 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| lab_color | bool | r/w | 값을 가져오거나 설정합니다. [lab color] 여부를 나타냅니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| mean_value_for_brightness_and_contrast | short | r/w | 밝기와 대비의 평균 값을 가져오거나 설정합니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

새 인스턴스를 초기화합니다 [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) 클래스.

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

새 인스턴스를 초기화합니다 [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 밝기 | short | 밝기입니다. |
| 대비 | short | 대비입니다. |
| mean_value_for_brightness_and_contrast | short | 밝기와 대비의 평균값입니다. |
| lab_color | bool | 설정이 <c>true</c> [lab color]인 경우. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

새 인스턴스를 초기화합니다 [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) 클래스.<br/>            PSD 형식 사양에는 다음 설명이 포함됩니다:<br/>            2 밝기<br/>            2 대비<br/>            2 밝기 및 대비의 평균값<br/>            1 Lab 색상만<br/>            현대 PSD(CS5 이상)에서는 CgEd가 사용됩니다. CgEd는 정보 속성을 저장합니다

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 바이트 | byte | 바이트입니다. |

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

