---
title: Class LayerMaskDataShort
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort 수업. 레이어에 래스터 또는 벡터 마스크만 있고 둘 다 없는 경우 PSD 파일 layer 의 마스크 데이터에 대한 정보를 포함하는 LayerMaskDataShort 클래스를 정의합니다. 그렇지 않으면LayerMaskDataFull 레이어에 래스터 마스크만 있는 경우 ImageData에는 래스터 마스크 데이터 바이트가 포함됩니다. 레이어에 벡터 마스크만 있는 경우 ImageData에는 벡터 마스크 래스터화된캐시된 데이터 바이트가 포함됩니다. TheImageData바이트 길이는 너비  높이와 같아야 합니다.MaskRectangle 속성.
type: docs
weight: 2260
url: /ko/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

레이어에 래스터 또는 벡터 마스크만 있고 둘 다 없는 경우 PSD 파일 layer 의 마스크 데이터에 대한 정보를 포함하는 LayerMaskDataShort 클래스를 정의합니다. 그렇지 않으면[`LayerMaskDataFull`](../layermaskdatafull/) 레이어에 래스터 마스크만 있는 경우 ImageData에는 래스터 마스크 데이터 바이트가 포함됩니다. 레이어에 벡터 마스크만 있는 경우 ImageData에는 벡터 마스크 래스터화된(캐시된) 데이터 바이트가 포함됩니다. The[`ImageData`](../layermaskdata/imagedata/)바이트 길이는 너비 * 높이와 같아야 합니다.[`MaskRectangle`](../layermaskdata/maskrectangle/) 속성.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | 기본 생성자입니다. |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | 레이어 마스크 패딩을 가져오거나 설정합니다. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 올바른 레이어 마스크 위치를 가져오거나 설정합니다. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 최상위 레이어 마스크 위치를 가져오거나 설정합니다. |

### 또한보십시오

* class [LayerMaskData](../layermaskdata/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 집회 [Aspose.PSD](../../)


