---
title: "IPartialRawDataLoader 클래스"
type: docs
weight: 1940
url: /ko/python-net/aspose.psd/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPartialRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **설명** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | 로드된 데이터를 처리합니다. |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | 로드된 데이터를 처리합니다. |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

로드된 데이터를 처리합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 데이터 사각형. |
| 데이터 | byte | 원시 데이터. |
| start | [Point](/psd/python-net/aspose.psd/point) | 시작 데이터 포인트입니다. (left,top)과 같지 않으면 전체 사각형이 아니라는 의미입니다. |
| end | [Point](/psd/python-net/aspose.psd/point) | 끝 데이터 포인트입니다. (right,bottom)과 같지 않으면 전체 사각형이 아니라는 의미입니다. |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

로드된 데이터를 처리합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 데이터 사각형. |
| 데이터 | byte | 원시 데이터. |
| start | [Point](/psd/python-net/aspose.psd/point) | 시작 데이터 포인트입니다. (left,top)과 같지 않으면 전체 사각형이 아니라는 의미입니다. |
| end | [Point](/psd/python-net/aspose.psd/point) | 끝 데이터 포인트입니다. (right,bottom)과 같지 않으면 전체 사각형이 아니라는 의미입니다. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 로드 옵션. |

