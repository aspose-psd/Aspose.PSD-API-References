---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: .NET API 참조용 Aspose.PSD
description: 네임스페이스에는 PSD 파일 형식 레이어가 포함되어 있습니다.
type: docs
weight: 210
url: /ko/net/aspose.psd.fileformats.psd.layers/
---
네임스페이스에는 PSD 파일 형식 레이어가 포함되어 있습니다.

## 클래스

| 수업 | 설명 |
| --- | --- |
| [BlendRange](./blendrange/) | 혼합 범위입니다. |
| [ChannelInformation](./channelinformation/) | 채널 정보입니다. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | 글로벌 레이어 마스크 섹션. |
| [Layer](./layer/) | psd 레이어. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | 레이어 블렌딩 범위 데이터. |
| [LayerGroup](./layergroup/) | 그룹 레이어 class |
| [LayerHashCalculator](./layerhashcalculator/) | PSD 레이어용 해시 계산기. 다른 PSD 파일에서 같거나 다른 레이어를 찾는 데 사용할 수 있습니다 |
| [LayerMaskData](./layermaskdata/) | PSD 파일의 레이어 마스크 데이터에 대한 정보가 포함된 기본 LayerMaskData 클래스를 정의합니다. 프로그래밍 방식으로 Adobe® Photoshop® 파일을 수정하고 PSD 형식 편집을 자동화하는 데 도움이 될 수 있습니다. 레이어에 래스터 마스크만 있는 경우 ImageData에는 래스터가 포함됩니다. 마스크 데이터 바이트. 레이어에 벡터 마스크만 있는 경우 ImageData에는 래스터화된(캐시된) 벡터 마스크 데이터 바이트가 포함됩니다. 레이어에 레이어 마스크와 벡터 마스크가 모두 있는 경우 ImageData에는 래스터 마스크와 결합된 래스터화된 벡터 마스크가 포함됩니다. 그만큼[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)바이트 길이는 너비 * 높이와 같아야 합니다.[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properties. 채널이 업데이트되지 않기 때문에 LayerMaskData를 제거/추가/업데이트하는 것만으로는 올바른 saving 에 충분하지 않습니다. 올바른 렌더링을 제공할 수 있지만. [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) 방법을 사용해야 합니다. |
| [LayerMaskDataFull](./layermaskdatafull/) | 레이어에 레이어 마스크와 벡터 마스크가 모두 있는 경우 PSD 파일 layer 의 마스크 데이터에 대한 정보를 포함하는 LayerMaskDataFull 클래스를 정의합니다. 그렇지 않으면[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) ImageData에는 래스터 마스크와 래스터화된 벡터 마스크가 결합되어 있습니다. ImageData 바이트 길이는 MaskRectangle.Width * MaskRectangle.Height 속성과 같아야 합니다. |
| [LayerMaskDataShort](./layermaskdatashort/) | 레이어에 래스터 또는 벡터 마스크만 있고 둘 다 없는 경우 PSD 파일 layer 의 마스크 데이터에 대한 정보를 포함하는 LayerMaskDataShort 클래스를 정의합니다. 그렇지 않으면[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) 레이어에 래스터 마스크만 있는 경우 ImageData에는 래스터 마스크 데이터 바이트가 포함됩니다. 레이어에 벡터 마스크만 있는 경우 ImageData에는 벡터 마스크 래스터화된(캐시된) 데이터 바이트가 포함됩니다. The[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)바이트 길이는 너비 * 높이와 같아야 합니다.[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) 속성. |
| [LayerResource](./layerresource/) | 레이어 정보를 나타냅니다. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | PSD 파일 로드를 위한 레이어 리소스 레지스트리를 정의합니다. |
| [LinkedLayersManager](./linkedlayersmanager/) | 연결된 레이어 관리자 클래스. |
| [SectionDividerLayer](./sectiondividerlayer/) | 폴더의 경계를 표시하는 섹션 구분선 레이어(레이어 그룹). |
| [TextLayer](./textlayer/) | 텍스트 레이어 class |
## 인터페이스

| 상호 작용 | 설명 |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | 채우기 설정을 위한 기본 인터페이스 |
| [ILayerResourceLoader](./ilayerresourceloader/) | 레이어 리소스 로더. |
## 열거

| 열거 | 설명 |
| --- | --- |
| [LayerFlags](./layerflags/) | 레이어 flags |
| [LayerMaskFlags](./layermaskflags/) | 레이어 마스크 flags |


