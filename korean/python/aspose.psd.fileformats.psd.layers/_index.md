---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /ko/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **Class** | **설명** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | 아트보드 레이어 클래스입니다. |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | 블렌드 범위입니다. |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | 채널 정보입니다. |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | 전역 레이어 마스크 섹션입니다. |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | 채우기 설정을 위한 기본 인터페이스 |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | 레이어 리소스 로더. |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | Shape 레이어의 속성을 설명합니다. |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | psd 레이어. |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | 레이어 블렌딩 범위 데이터입니다. |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | 그룹 레이어 클래스 |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | PSD 레이어용 해시 계산기. 서로 다른 PSD 파일에서 동일하거나 다른 레이어를 찾는 데 사용할 수 있습니다. |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | PSD 파일에서 레이어 마스크 데이터에 대한 정보를 포함하는 기본 LayerMaskData 클래스를 정의합니다.<br/>            이를 통해 Adobe® Photoshop® 파일을 프로그래밍 방식으로 수정하고 PSD 형식 편집을 자동화할 수 있습니다.<br/>            레이어에 래스터 마스크만 있는 경우 ImageData는 래스터 마스크 데이터 바이트를 포함합니다.<br/>            레이어에 벡터 마스크만 있는 경우 ImageData는 벡터 마스크를 래스터화(캐시)한 데이터 바이트를 포함합니다.<br/>            레이어에 레이어 마스크와 벡터 마스크가 모두 있는 경우 ImageData는 래스터 마스크와 래스터화된 벡터 마스크가 결합된 형태를 포함합니다.<br/>            [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) 바이트 길이는 [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) 속성의 Width * Height와 같아야 합니다.<br/>            단순히 LayerMaskData를 제거/추가/업데이트하는 것만으로는 채널이 업데이트되지 않아 올바른 저장이 보장되지 않으며, 렌더링은 정상일 수 있습니다.<br/>            이를 위해서는 [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 메서드를 사용해야 합니다. |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | 레이어에 레이어 마스크와 벡터 마스크가 모두 있는 경우 PSD 파일 레이어의 마스크 데이터 정보를 포함하는 LayerMaskDataFull 클래스를 정의합니다.<br/>            그렇지 않은 경우 [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/)이 사용됩니다.<br/>            ImageData는 래스터 마스크와 래스터화된 벡터 마스크가 결합된 형태를 포함합니다.<br/>            ImageData 바이트 길이는 MaskRectangle.Width * MaskRectangle.Height 속성과 같아야 합니다. |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | 레이어에 래스터 마스크 또는 벡터 마스크만 있고 둘 다 없는 경우 PSD 파일 레이어의 마스크 데이터 정보를 포함하는 LayerMaskDataShort 클래스를 정의합니다.<br/>            그렇지 않은 경우 [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/)이 사용됩니다.<br/>            레이어에 래스터 마스크만 있는 경우 ImageData는 래스터 마스크 데이터 바이트를 포함합니다.<br/>            레이어에 벡터 마스크만 있는 경우 ImageData는 벡터 마스크를 래스터화(캐시)한 데이터 바이트를 포함합니다.<br/>            [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) 바이트 길이는 [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) 속성의 Width * Height와 같아야 합니다. |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | 레이어 정보를 나타냅니다. |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | PSD 파일 로드를 위한 레이어 리소스 레지스트리를 정의합니다. |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | 연결된 레이어 관리자 클래스. |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | 폴더(레이어 그룹)의 경계를 표시하기 위한 섹션 구분자 레이어입니다. |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Shape 레이어. Shape 레이어와 관련 리소스 작업 로직을 캡슐화합니다. |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | 텍스트 레이어 클래스 |
## **Enumerations**
| **열거형** | **설명** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | 레이어 플래그 |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | 레이어 마스크 플래그 |
