---
title: "클래스 LayerMaskDataShort"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort 클래스. 레이어에 래스터 또는 벡터 마스크만 있고 둘 다 없을 때 PSD 파일 레이어의 마스크 데이터에 대한 정보를 포함하는 LayerMaskDataShort 클래스를 정의합니다. 그렇지 않은 경우 LayerMaskDataFull이 사용됩니다. 레이어에 래스터 마스크만 있는 경우 ImageData는 래스터 마스크 데이터 바이트를 포함합니다. 레이어에 벡터 마스크만 있는 경우 ImageData는 벡터 마스크가 래스터화된 캐시 데이터 바이트를 포함합니다. ImageData 바이트 길이는 MaskRectangle 속성의 Width * Height와 같아야 합니다."
type: docs
weight: 2460
url: /ko/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

레이어에 래스터 또는 벡터 마스크만 있고 둘 다 없을 때 PSD 파일 레이어의 마스크 데이터에 대한 정보를 포함하는 LayerMaskDataShort 클래스를 정의합니다. 그렇지 않은 경우 [`LayerMaskDataFull`](../layermaskdatafull/)이 사용됩니다. 레이어에 래스터 마스크만 있는 경우 ImageData는 래스터 마스크 데이터 바이트를 포함합니다. 레이어에 벡터 마스크만 있는 경우 ImageData는 벡터 마스크가 래스터화된(캐시된) 데이터 바이트를 포함합니다. [`ImageData`](../layermaskdata/imagedata/) 바이트 길이는 [`MaskRectangle`](../layermaskdata/maskrectangle/) 속성의 Width * Height와 같아야 합니다.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | `LayerMaskDataShort` 클래스의 새 인스턴스를 초기화합니다. |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | 레이어 마스크 패딩을 가져오거나 설정합니다. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 오른쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 상단 레이어 마스크 위치를 가져오거나 설정합니다. |

### 또 보기

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


