---
title: "AnimatedDataSectionResource 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/
---

**Summary:** The Animated Data Section Plug-In resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.AnimatedDataSectionResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady의 리소스 서명입니다. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | 일반 Photoshop 리소스 서명입니다. |
| animated_data_section | [AnimatedDataSectionStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/) | r | 애니메이션 데이터 섹션 구조를 가져오거나 설정합니다. |
| data_size | int | r | 리소스 데이터 크기를 바이트 단위로 가져옵니다. |
| id | short | r/w | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| key_name | 문자열 | r | 리소스 키 이름입니다. |
| minimal_version | int | r | 필요한 최소 PSD 버전을 가져옵니다. |
| name | 문자열 | r/w | 리소스 이름을 가져오거나 설정합니다. Pascal 문자열이며, 크기를 짝수로 맞추기 위해 패딩됩니다(널 이름은 0 두 바이트로 구성됩니다). |
| signature | int | r | 리소스 서명을 가져옵니다. 항상 '8BIM'이어야 합니다. |
| 크기 | int | r | 데이터를 포함한 리소스 블록 크기를 바이트 단위로 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream)](#save_stream_1) | 리소스 블록 데이터를 저장합니다. |
| validate_values() | 리소스 값을 검증합니다. |


### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

리소스 블록 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

