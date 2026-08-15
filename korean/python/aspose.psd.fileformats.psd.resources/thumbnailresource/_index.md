---
title: "ThumbnailResource 클래스"
type: docs
weight: 250
url: /ko/python-net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---

**Summary:** The thumbnail resource block.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ThumbnailResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [ThumbnailResource()](#ThumbnailResource__1) | ThumbnailResource 클래스의 새 인스턴스를 초기화합니다 |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady의 리소스 서명입니다. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | 일반 Photoshop 리소스 서명입니다. |
| bits_pixel | short | r/w | 비트 픽셀을 가져오거나 설정합니다. |
| data_size | int | r | 리소스 데이터 크기를 바이트 단위로 가져옵니다. |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | 썸네일 데이터 형식을 가져오거나 설정합니다. |
| 높이 | int | r/w | 픽셀 단위의 썸네일 높이를 가져오거나 설정합니다. |
| id | short | r/w | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | JPEG 옵션을 가져오거나 설정합니다. 썸네일 리소스를 JPEG 파일 형식으로만 저장할 때 적합합니다. RAW 형식이 정의된 경우 이 옵션은 영향을 주지 않습니다. |
| minimal_version | int | r | 최소 요구되는 psd 버전을 가져옵니다. |
| name | 문자열 | r/w | 리소스 이름을 가져오거나 설정합니다. Pascal 문자열이며, 크기를 짝수로 맞추기 위해 패딩됩니다(널 이름은 0 두 바이트로 구성됩니다). |
| planes_count | short | r/w | 평면 수를 가져오거나 설정합니다. |
| signature | int | r | 리소스 서명을 가져옵니다. 항상 '8BIM'이어야 합니다. |
| 크기 | int | r | 데이터를 포함한 리소스 블록 크기를 바이트 단위로 가져옵니다. |
| size_after_compression | int | r | 압축 후 크기를 가져오거나 설정합니다. 일관성 검사를 위해 사용됩니다. |
| thumbnail_argb_32_data | int | r/w | 32비트 ARGB 썸네일 데이터를 가져오거나 설정합니다. |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | 썸네일 데이터를 가져오거나 설정합니다. |
| total_size | int | r | 전체 데이터 크기를 가져옵니다. |
| width | int | r/w | 픽셀 단위로 썸네일의 너비를 가져오거나 설정합니다. |
| width_bytes | int | r | 행 너비를 바이트 단위로 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream)](#save_stream_1) | 리소스 블록 데이터를 저장합니다. |
| validate_values() | 리소스 값을 검증합니다. |


### Constructor: ThumbnailResource() {#ThumbnailResource__1}


```
 ThumbnailResource() 
```

ThumbnailResource 클래스의 새 인스턴스를 초기화합니다

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

리소스 블록 데이터를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

