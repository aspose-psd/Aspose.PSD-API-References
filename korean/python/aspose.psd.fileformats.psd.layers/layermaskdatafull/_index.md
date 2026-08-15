---
title: "LayerMaskDataFull 클래스"
type: docs
weight: 980
url: /ko/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | LayerMaskDataFull 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| background_color | byte | r/w | 배경 색상을 가져오거나 설정합니다. |
| 하단 | int | r/w | 하단 레이어 마스크 위치를 가져오거나 설정합니다. |
| data_size | int | r | 레이어 마스크 데이터의 크기를 가져옵니다. |
| default_color | byte | r/w | 기본 색상을 가져오거나 설정합니다. |
| enclosing_bottom | int | r/w | PSD 이미지 레이어에서 둘러싸는 하단 래스터 마스크 위치를 가져오거나 설정합니다. |
| enclosing_left | int | r/w | PSD 파일 레이어에서 둘러싸는 왼쪽 래스터 마스크 위치를 가져오거나 설정합니다. |
| enclosing_right | int | r/w | PSD 파일 레이어에서 둘러싸는 오른쪽 래스터 마스크 위치를 가져오거나 설정합니다. |
| enclosing_top | int | r/w | PSD 이미지 레이어에서 래스터 마스크의 둘러싸는 상단 위치를 가져오거나 설정합니다. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | 레이어 마스크 플래그를 가져오거나 설정합니다. |
| image_data | byte | r/w | PSD 파일에서 레이어 마스크 데이터(벡터 마스크가 있는 경우 결합/최종 마스크)를 가져오거나 설정합니다. |
| left | int | r/w | 왼쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD 파일에서 레이어 마스크의 마스크 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 가져오거나 설정합니다.<br/>            왼쪽, 오른쪽, 위, 아래 속성을 받아 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 생성합니다. |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | 사용자/래스터 마스크에 사용되는 레이어 마스크 플래그를 가져오거나 설정합니다. 벡터 마스크의 경우 Flags 속성이 사용됩니다. |
| right | int | r/w | 오른쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| top | int | r/w | 위쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| user_mask_data | byte | r/w | PSD 파일의 레이어에 대한 사용자(래스터) 마스크 데이터를 가져오거나 설정합니다. (MaskData 속성에 래스터화된 벡터 마스크가 있습니다.) |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD 이미지 레이어에서 사용자 마스크(포함) 사각형을 가져오거나 설정합니다. |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

LayerMaskDataFull 클래스의 새 인스턴스를 초기화합니다.

