---
title: "DataStreamSupporter 클래스"
type: docs
weight: 1030
url: /ko/python-net/aspose.psd/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataStreamSupporter

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | 객체의 데이터 스트림을 가져옵니다. |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| is_cached | bool | r | 객체의 데이터가 현재 캐시되어 있어 데이터 읽기가 필요 없는지를 나타내는 값을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| cache_data() | 데이터를 캐시하고 기본 [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/)에서 추가 데이터 로드가 수행되지 않도록 보장합니다. |
| save() | 객체의 데이터를 현재 [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/)에 저장합니다. |
| [save(file_path)](#save_file_path_1) | 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | 지정된 파일 위치에 객체의 데이터를 저장합니다. |
| [save(stream)](#save_stream_3) | 지정된 스트림에 객체의 데이터를 저장합니다. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

지정된 파일 위치에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 객체 데이터를 저장할 파일 경로. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

지정된 파일 위치에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | 문자열 | 객체 데이터를 저장할 파일 경로. |
| over_write | bool | 만약 <c>true</c> 로 설정하면 파일 내용을 덮어쓰고, 그렇지 않으면 추가됩니다. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

지정된 스트림에 객체의 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 객체 데이터를 저장할 스트림. |

