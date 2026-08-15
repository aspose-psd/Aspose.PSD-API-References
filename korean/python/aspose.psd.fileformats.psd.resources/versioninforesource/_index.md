---
title: "VersionInfoResource 클래스"
type: docs
weight: 300
url: /ko/python-net/aspose.psd.fileformats.psd.resources/versioninforesource/
---

**Summary:** Version Info resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.VersionInfoResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [VersionInfoResource()](#VersionInfoResource__1) | VersionInfoResource 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady의 리소스 서명입니다. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | 일반 Photoshop 리소스 서명입니다. |
| data_size | int | r | 리소스 데이터 크기를 바이트 단위로 가져옵니다. |
| file_version | uint | r/w | 파일 버전을 가져오거나 설정합니다. |
| has_real_merged_data | bool | r/w | 이 인스턴스에 실제 병합 데이터가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| id | short | r/w | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| minimal_version | int | r | 필요한 최소 PSD 버전을 가져옵니다. |
| name | 문자열 | r/w | 리소스 이름을 가져오거나 설정합니다. Pascal 문자열이며, 크기를 짝수로 맞추기 위해 패딩됩니다(널 이름은 0 두 바이트로 구성됩니다). |
| reader_name | 문자열 | r/w | 리더의 이름을 가져오거나 설정합니다. |
| signature | int | r | 리소스 서명을 가져옵니다. 항상 '8BIM'이어야 합니다. |
| 크기 | int | r | 데이터를 포함한 리소스 블록 크기를 바이트 단위로 가져옵니다. |
| version | uint | r/w | 버전을 가져오거나 설정합니다. |
| writer_name | 문자열 | r/w | 라이터의 이름을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream)](#save_stream_1) | 지정된 스트림에 리소스 블록을 저장합니다. |
| validate_values() | 리소스 값을 검증합니다. |


### Constructor: VersionInfoResource() {#VersionInfoResource__1}


```
 VersionInfoResource() 
```

VersionInfoResource 클래스의 새 인스턴스를 초기화합니다.

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

지정된 스트림에 리소스 블록을 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 리소스 블록을 저장할 스트림입니다. |

