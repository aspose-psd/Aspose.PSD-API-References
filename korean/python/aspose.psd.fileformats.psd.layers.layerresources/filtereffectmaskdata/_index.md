---
title: "FilterEffectMaskData 클래스"
type: docs
weight: 310
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | 채널을 가져옵니다. |
| guid | 문자열 | r | GUID를 가져옵니다. |
| 길이 | int | r | 필터 마스크 데이터 길이를 바이트 단위로 가져옵니다. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 시트 마스크 사각형을 가져옵니다. |
| max_channels | int | r | 채널 수의 최대값을 가져옵니다. |
| pixels_depth | int | r | 픽셀 깊이를 가져옵니다. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 채널 사각형을 가져옵니다. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | 시트 마스크를 가져옵니다. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | 사용자 마스크를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

[FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| guid | 문자열 | 리소스 guid입니다. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 채널 사각형입니다. |
| pixels_depth | int | 픽셀 깊이입니다. |
| max_channels | int | 최대 채널 값입니다. |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | 채널입니다. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | 사용자 마스크. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 시트 마스크 사각형. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | 시트 마스크. |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

리소스를 지정된 스트림 컨테이너에 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |

