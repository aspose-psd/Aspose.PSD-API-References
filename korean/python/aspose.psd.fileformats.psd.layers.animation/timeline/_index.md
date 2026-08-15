---
title: "Timeline 클래스"
type: docs
weight: 40
url: /ko/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Timeline()](#Timeline__1) | Timeline 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| active_frame_index | int | r | 활성 프레임 인덱스를 가져옵니다. |
| af_st | int | r/w | AFSt 값을 가져오거나 설정합니다. |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | 프레임 목록을 가져옵니다. |
| fs_id | int | r/w | FsID 값을 가져오거나 설정합니다. |
| loopes_count | ushort | r/w | 루프 수를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | 지정된 파일 위치에 지정된 형식으로 PsdImage와 Timeline 데이터를 저장 옵션에 따라 저장합니다. |
| [save(output_stream, options)](#save_output_stream_options_2) | 지정된 스트림에 지정된 형식으로 PsdImage와 Timeline 데이터를 저장 옵션에 따라 저장합니다. |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | 활성 프레임을 대상 프레임으로 전환합니다. |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

Timeline 클래스의 새 인스턴스를 초기화합니다.

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

지정된 파일 위치에 지정된 형식으로 PsdImage와 Timeline 데이터를 저장 옵션에 따라 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 파일 경로. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 옵션. |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

지정된 스트림에 지정된 형식으로 PsdImage와 Timeline 데이터를 저장 옵션에 따라 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | 출력 스트림. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 옵션. |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

활성 프레임을 대상 프레임으로 전환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| target_active_frame_index | int | 대상 프레임 인덱스. |

