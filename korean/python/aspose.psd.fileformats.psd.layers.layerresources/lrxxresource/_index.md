---
title: "LrXxResource 클래스"
type: docs
weight: 630
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/lrxxresource/
---

**Summary:** The lrXX resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LrXxResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | r/w | 레이어를 가져오거나 설정합니다. |
| 길이 | int | r | 이미지의 PSD 헤더 버전에 대한 리소스 길이를 가져옵니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| signature | int | r | 서명을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 레이어 레코드를 저장합니다. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

레이어 레코드를 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| psd_version | int | PSD 버전입니다. |

