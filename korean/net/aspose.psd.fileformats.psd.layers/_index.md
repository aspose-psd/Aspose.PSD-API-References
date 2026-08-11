---
title: "Aspose.PSD.FileFormats.Psd.Layers"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "네임스페이스에는 PSD 파일 형식 레이어가 포함되어 있습니다"
type: docs
weight: 230
url: /ko/net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
네임스페이스에는 PSD 파일 형식 레이어가 포함되어 있습니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [ArtboardLayer](./artboardlayer/) | 아트보드 레이어 클래스. |
| [BlendRange](./blendrange/) | 블렌드 범위. |
| [ChannelInformation](./channelinformation/) | 채널 정보. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | 전역 레이어 마스크 섹션입니다. |
| [Layer](./layer/) | PSD 레이어입니다. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | 레이어 블렌딩 범위 데이터입니다. |
| [LayerGroup](./layergroup/) | 그룹 레이어 클래스 |
| [LayerHashCalculator](./layerhashcalculator/) | PSD 레이어용 해시 계산기. 서로 다른 PSD 파일에서 동일하거나 다른 레이어를 찾는 데 사용할 수 있습니다. |
| [LayerMaskData](./layermaskdata/) | PSD 파일에서 레이어 마스크 데이터에 대한 정보를 포함하는 기본 LayerMaskData 클래스를 정의합니다. 이를 통해 Adobe® Photoshop® 파일을 프로그래밍 방식으로 수정하고 PSD 형식 편집을 자동화할 수 있습니다. 레이어에 래스터 마스크만 있는 경우 `ImageData`는 래스터 마스크 데이터 바이트를 포함합니다. 레이어에 벡터 마스크만 있는 경우 `ImageData`는 벡터 마스크가 래스터화(캐시)된 데이터 바이트를 포함합니다. 레이어와 벡터 마스크가 모두 있는 경우 `ImageData`는 래스터 마스크와 래스터화된 벡터 마스크가 결합된 데이터를 포함합니다. [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) 바이트 길이는 [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) 속성의 Width * Height와 같아야 합니다. 단순히 LayerMaskData를 제거/추가/업데이트하는 것만으로는 채널이 업데이트되지 않아 올바른 저장이 보장되지 않으며, 렌더링은 정상일 수 있습니다. 이를 위해서는 [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) 메서드를 사용해야 합니다. |
| [LayerMaskDataFull](./layermaskdatafull/) | 레이어에 레이어 마스크와 벡터 마스크가 모두 있는 경우 PSD 파일 레이어의 마스크 데이터에 대한 정보를 포함하는 LayerMaskDataFull 클래스를 정의합니다. 그렇지 않은 경우 [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/)가 사용됩니다. ImageData는 래스터 마스크와 래스터화된 벡터 마스크가 결합된 데이터를 포함합니다. ImageData 바이트 길이는 MaskRectangle.Width * MaskRectangle.Height 속성과 같아야 합니다. |
| [LayerMaskDataShort](./layermaskdatashort/) | 레이어에 래스터 마스크 또는 벡터 마스크만 있고 둘 다 없는 경우 PSD 파일 레이어의 마스크 데이터에 대한 정보를 포함하는 LayerMaskDataShort 클래스를 정의합니다. 그렇지 않은 경우 [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/)가 사용됩니다. 레이어에 래스터 마스크만 있는 경우 ImageData는 래스터 마스크 데이터 바이트를 포함합니다. 레이어에 벡터 마스크만 있는 경우 ImageData는 벡터 마스크가 래스터화(캐시)된 데이터 바이트를 포함합니다. [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) 바이트 길이는 [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) 속성의 Width * Height와 같아야 합니다. |
| [LayerResource](./layerresource/) | 레이어 정보를 나타냅니다. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | PSD 파일 로드를 위한 레이어 리소스 레지스트리를 정의합니다. |
| [LinkedLayersManager](./linkedlayersmanager/) | 연결된 레이어 관리자 클래스. |
| [SectionDividerLayer](./sectiondividerlayer/) | 폴더(레이어 그룹)의 경계를 표시하기 위한 섹션 구분자 레이어입니다. |
| [ShapeLayer](./shapelayer/) | 쉐이프 레이어. 쉐이프 레이어와 관련 리소스 작업 로직을 캡슐화합니다. |
| [TextLayer](./textlayer/) | 텍스트 레이어 클래스 |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | 채우기 설정을 위한 기본 인터페이스 |
| [ILayerResourceLoader](./ilayerresourceloader/) | 레이어 리소스 로더입니다. |
| [IShapeLayer](./ishapelayer/) | 쉐이프 레이어의 속성을 설명합니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [LayerFlags](./layerflags/) | 레이어 플래그 |
| [LayerMaskFlags](./layermaskflags/) | 레이어 마스크 플래그 |


