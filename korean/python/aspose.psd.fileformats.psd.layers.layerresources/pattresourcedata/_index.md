---
title: "PattResourceData 클래스"
type: docs
weight: 780
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | PattResourceData 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| 높이 | short | r | 높이를 가져옵니다. |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | 이미지 모드를 가져옵니다. |
| 길이 | int | r | 패턴의 길이를 가져옵니다. |
| name | 문자열 | r/w | 이름을 가져오거나 설정합니다. |
| pattern_data | int | r | 패턴 데이터를 가져옵니다. |
| pattern_id | 문자열 | r/w | 패턴 식별자를 가져오거나 설정합니다. |
| version | int | r | 버전을 가져옵니다. |
| width | short | r | 너비를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | 패턴 데이터를 저장합니다. |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | 패턴을 설정합니다. |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

PattResourceData 클래스의 새 인스턴스를 초기화합니다.

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

패턴 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

패턴을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pixels | int | 픽셀. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 경계. |

