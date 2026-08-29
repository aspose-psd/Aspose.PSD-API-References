---
title: "클래스 LayerMaskData"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData 클래스. PSD 파일의 레이어 마스크 데이터에 대한 정보를 포함하는 기본 LayerMaskData 클래스를 정의합니다. 이는 Adobe Photoshop 파일을 프로그래밍 방식으로 수정하고 PSD 형식 편집을 자동화하는 데 도움이 될 수 있습니다. 레이어에 래스터 마스크만 있는 경우 ImageData는 래스터 마스크 데이터 바이트를 포함합니다. 레이어에 벡터 마스크만 있는 경우 ImageData는 벡터 마스크가 래스터화된 캐시 데이터 바이트를 포함합니다. 레이어에 레이어 마스크와 벡터 마스크가 모두 있는 경우 ImageData는 래스터 마스크와 래스터화된 벡터 마스크가 결합된 데이터를 포함합니다. ImageData 바이트 길이는 MaskRectangle 속성의 Width * Height와 같아야 합니다. 채널이 업데이트되지 않기 때문에 LayerMaskData를 단순히 제거/추가/업데이트하는 것만으로는 올바른 저장이 보장되지 않으며, 올바른 렌더링을 제공할 수 있습니다. 이를 위해 AddLayerMask 메서드를 사용해야 합니다."
type: docs
weight: 2440
url: /ko/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

PSD 파일의 레이어 마스크 데이터에 대한 정보를 포함하는 기본 LayerMaskData 클래스를 정의합니다. 이는 Adobe® Photoshop® 파일을 프로그래밍 방식으로 수정하고 PSD 형식 편집을 자동화하는 데 도움이 될 수 있습니다. 레이어에 래스터 마스크만 있는 경우 ImageData는 래스터 마스크 데이터 바이트를 포함합니다. 레이어에 벡터 마스크만 있는 경우 ImageData는 벡터 마스크가 래스터화된(캐시된) 데이터 바이트를 포함합니다. 레이어에 레이어 마스크와 벡터 마스크가 모두 있는 경우 ImageData는 래스터 마스크와 래스터화된 벡터 마스크가 결합된 데이터를 포함합니다. [`ImageData`](./imagedata/) 바이트 길이는 [`MaskRectangle`](./maskrectangle/) 속성의 Width * Height와 같아야 합니다. LayerMaskData를 단순히 제거/추가/업데이트하는 것만으로는 채널이 업데이트되지 않아 올바른 저장이 보장되지 않으며, 올바른 렌더링을 제공할 수 있습니다. 이를 위해 [`AddLayerMask`](../layer/addlayermask/) 메서드를 사용해야 합니다.

```csharp
public abstract class LayerMaskData
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | 하단 레이어 마스크 위치를 가져오거나 설정합니다. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | 레이어 마스크 데이터의 크기를 가져옵니다. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | 기본 색상을 가져오거나 설정합니다. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | 레이어 마스크 플래그를 가져오거나 설정합니다. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD 파일에서 레이어 마스크 데이터(또는 벡터 마스크가 있는 경우 결합된/최종 마스크)를 가져오거나 설정합니다. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | 왼쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | PSD 파일의 레이어 마스크에 대한 마스크 [`Rectangle`](../../aspose.psd/rectangle/)을 가져오거나 설정합니다. left, right, top, bottom 속성을 받아서 [`Rectangle`](../../aspose.psd/rectangle/)을 생성합니다. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 오른쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 상단 레이어 마스크 위치를 가져오거나 설정합니다. |

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


