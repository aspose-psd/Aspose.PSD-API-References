---
title: Class LayerMaskData
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData 수업. PSD 파일의 레이어 마스크 데이터에 대한 정보가 포함된 기본 LayerMaskData 클래스를 정의합니다. 프로그래밍 방식으로 Adobe Photoshop 파일을 수정하고 PSD 형식 편집을 자동화하는 데 도움이 될 수 있습니다. 레이어에 래스터 마스크만 있는 경우 ImageData에는 래스터가 포함됩니다. 마스크 데이터 바이트. 레이어에 벡터 마스크만 있는 경우 ImageData에는 래스터화된캐시된 벡터 마스크 데이터 바이트가 포함됩니다. 레이어에 레이어 마스크와 벡터 마스크가 모두 있는 경우 ImageData에는 래스터 마스크와 결합된 래스터화된 벡터 마스크가 포함됩니다. 그만큼ImageData바이트 길이는 너비  높이와 같아야 합니다.MaskRectangle properties. 채널이 업데이트되지 않기 때문에 LayerMaskData를 제거/추가/업데이트하는 것만으로는 올바른 saving 에 충분하지 않습니다. 올바른 렌더링을 제공할 수 있지만. AddLayerMask 방법을 사용해야 합니다.
type: docs
weight: 2240
url: /ko/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

PSD 파일의 레이어 마스크 데이터에 대한 정보가 포함된 기본 LayerMaskData 클래스를 정의합니다. 프로그래밍 방식으로 Adobe® Photoshop® 파일을 수정하고 PSD 형식 편집을 자동화하는 데 도움이 될 수 있습니다. 레이어에 래스터 마스크만 있는 경우 ImageData에는 래스터가 포함됩니다. 마스크 데이터 바이트. 레이어에 벡터 마스크만 있는 경우 ImageData에는 래스터화된(캐시된) 벡터 마스크 데이터 바이트가 포함됩니다. 레이어에 레이어 마스크와 벡터 마스크가 모두 있는 경우 ImageData에는 래스터 마스크와 결합된 래스터화된 벡터 마스크가 포함됩니다. 그만큼[`ImageData`](./imagedata/)바이트 길이는 너비 * 높이와 같아야 합니다.[`MaskRectangle`](./maskrectangle/) properties. 채널이 업데이트되지 않기 때문에 LayerMaskData를 제거/추가/업데이트하는 것만으로는 올바른 saving 에 충분하지 않습니다. 올바른 렌더링을 제공할 수 있지만. [`AddLayerMask`](../layer/addlayermask/) 방법을 사용해야 합니다.

```csharp
public abstract class LayerMaskData
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | 하단 레이어 마스크 위치를 가져오거나 설정합니다. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | 레이어 마스크 마스크 데이터의 크기를 가져옵니다. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | 기본 색상을 가져오거나 설정합니다. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | 레이어 마스크 플래그를 가져오거나 설정합니다. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD 파일의 레이어 마스크 데이터(또는 벡터 마스크가 있는 경우 결합/최종 마스크)를 가져오거나 설정합니다. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | 왼쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | 마스크를 가져오거나 설정합니다.[`Rectangle`](../../aspose.psd/rectangle/)PSD 파일에서 레이어 마스크의 왼쪽, 오른쪽, 위쪽, 아래쪽 속성을 가져와 생성합니다.[`Rectangle`](../../aspose.psd/rectangle/) |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 올바른 레이어 마스크 위치를 가져오거나 설정합니다. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 최상위 레이어 마스크 위치를 가져오거나 설정합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 집회 [Aspose.PSD](../../)


