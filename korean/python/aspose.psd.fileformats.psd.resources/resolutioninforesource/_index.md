---
title: "ResolutionInfoResource 클래스"
type: docs
weight: 230
url: /ko/python-net/aspose.psd.fileformats.psd.resources/resolutioninforesource/
---

**Summary:** The resolution info resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ResolutionInfoResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [ResolutionInfoResource()](#ResolutionInfoResource__1) | ResolutionInfoResource 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady의 리소스 서명입니다. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | 일반 Photoshop 리소스 서명입니다. |
| data_size | int | r | 리소스 데이터 크기를 바이트 단위로 가져옵니다. |
| h_dpi | [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal) | r/w | 수평 DPI. |
| h_res_display_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit/) | r/w | 수평 해상도의 표시 단위.  이는 사용자 인터페이스에만 영향을 미치며;<br/>            해상도는 여전히 PSD 파일에 저장됩니다;<br/>            픽셀/인치 단위로. |
| height_display_unit | [PhysicalUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/) | r/w | 높이 표시 단위를 가져오거나 설정합니다. |
| id | short | r/w | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| minimal_version | int | r | 필요한 최소 PSD 버전을 가져옵니다. |
| name | 문자열 | r/w | 리소스 이름을 가져오거나 설정합니다. Pascal 문자열이며, 크기를 짝수로 맞추기 위해 패딩됩니다(널 이름은 0 두 바이트로 구성됩니다). |
| signature | int | r | 리소스 서명을 가져옵니다. 항상 '8BIM'이어야 합니다. |
| 크기 | int | r | 데이터를 포함한 리소스 블록 크기를 바이트 단위로 가져옵니다. |
| v_dpi | [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal) | r/w | 수직 DPI. |
| v_res_display_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit/) | r/w | 수직 해상도의 표시 단위. |
| width_display_unit | [PhysicalUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/) | r/w | 너비 표시 단위를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream)](#save_stream_1) | 지정된 스트림에 리소스 블록을 저장합니다. |
| validate_values() | 리소스 값을 검증합니다. |


### Constructor: ResolutionInfoResource() {#ResolutionInfoResource__1}


```
 ResolutionInfoResource() 
```

ResolutionInfoResource 클래스의 새 인스턴스를 초기화합니다.

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

지정된 스트림에 리소스 블록을 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 리소스 블록을 저장할 스트림입니다. |

