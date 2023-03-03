---
title: Class LayerMaskDataFull
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull 수업. 레이어에 레이어 마스크와 벡터 마스크가 모두 있는 경우 PSD 파일 layer 의 마스크 데이터에 대한 정보를 포함하는 LayerMaskDataFull 클래스를 정의합니다. 그렇지 않으면LayerMaskDataShort ImageData에는 래스터 마스크와 래스터화된 벡터 마스크가 결합되어 있습니다. ImageData 바이트 길이는 MaskRectangle.Width  MaskRectangle.Height 속성과 같아야 합니다.
type: docs
weight: 2250
url: /ko/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

레이어에 레이어 마스크와 벡터 마스크가 모두 있는 경우 PSD 파일 layer 의 마스크 데이터에 대한 정보를 포함하는 LayerMaskDataFull 클래스를 정의합니다. 그렇지 않으면[`LayerMaskDataShort`](../layermaskdatashort/) ImageData에는 래스터 마스크와 래스터화된 벡터 마스크가 결합되어 있습니다. ImageData 바이트 길이는 MaskRectangle.Width * MaskRectangle.Height 속성과 같아야 합니다.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | 배경색을 가져오거나 설정합니다. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | 하단 레이어 마스크 위치를 가져오거나 설정합니다. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | 레이어 마스크 마스크 데이터의 크기를 가져옵니다. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | 기본 색상을 가져오거나 설정합니다. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | PSD 이미지 레이어에서 둘러싸는 하단 래스터 마스크 위치를 가져오거나 설정합니다. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | PSD 파일 레이어에서 둘러싸는 왼쪽 래스터 마스크 위치를 가져오거나 설정합니다. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | PSD 파일 레이어에서 둘러싸는 오른쪽 래스터 마스크 위치를 가져오거나 설정합니다. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | PSD 이미지 레이어에서 래스터 마스크의 둘러싸는 상단 위치를 가져오거나 설정합니다. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | 레이어 마스크 플래그를 가져오거나 설정합니다. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | PSD 파일의 레이어 마스크 데이터(또는 벡터 마스크가 있는 경우 결합/최종 마스크)를 가져오거나 설정합니다. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | 왼쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | 마스크를 가져오거나 설정합니다.[`Rectangle`](../../aspose.psd/rectangle/)PSD 파일에서 레이어 마스크의 왼쪽, 오른쪽, 위쪽, 아래쪽 속성을 가져와 생성합니다.[`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | 사용자/래스터 마스크에 사용되는 레이어 마스크 플래그를 가져오거나 설정합니다. 벡터 마스크의 경우 Flags 속성이 사용됩니다. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | 올바른 레이어 마스크 위치를 가져오거나 설정합니다. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | 최상위 레이어 마스크 위치를 가져오거나 설정합니다. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | PSD 파일에 있는 레이어의 사용자(래스터) 마스크 데이터를 가져오거나 설정합니다. (MaskData 속성에 평가된 벡터 마스크가 있습니다). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | PSD 이미지 레이어에서 사용자 마스크(둘러싸는) 사각형을 가져오거나 설정합니다.. |

### 또한보십시오

* class [LayerMaskData](../layermaskdata/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 집회 [Aspose.PSD](../../)


