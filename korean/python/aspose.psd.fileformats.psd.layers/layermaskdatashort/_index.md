---
title: "LayerMaskDataShort 클래스"
type: docs
weight: 990
url: /ko/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Summary:** Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer<br/>            when the layer has only raster or vector mask but not both. Otherwise, a [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) is used.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataShort

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [LayerMaskDataShort()](#LayerMaskDataShort__1) | LayerMaskDataShort 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| 하단 | int | r/w | 하단 레이어 마스크 위치를 가져오거나 설정합니다. |
| data_size | int | r | 레이어 마스크 데이터의 크기를 가져옵니다. |
| default_color | byte | r/w | 기본 색상을 가져오거나 설정합니다. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | 레이어 마스크 플래그를 가져오거나 설정합니다. |
| image_data | byte | r/w | PSD 파일에서 레이어 마스크 데이터(벡터 마스크가 있는 경우 결합/최종 마스크)를 가져오거나 설정합니다. |
| left | int | r/w | 왼쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD 파일에서 레이어 마스크의 마스크 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 가져오거나 설정합니다.<br/>            왼쪽, 오른쪽, 위, 아래 속성을 받아 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 생성합니다. |
| 패딩 | short | r/w | 레이어 마스크 패딩을 가져오거나 설정합니다. |
| right | int | r/w | 오른쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| top | int | r/w | 위쪽 레이어 마스크 위치를 가져오거나 설정합니다. |


### Constructor: LayerMaskDataShort() {#LayerMaskDataShort__1}


```
 LayerMaskDataShort() 
```

LayerMaskDataShort 클래스의 새 인스턴스를 초기화합니다.

