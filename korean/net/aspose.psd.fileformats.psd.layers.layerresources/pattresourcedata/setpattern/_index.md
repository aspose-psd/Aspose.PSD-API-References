---
title: "PattResourceData.SetPattern"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PattResourceData 메서드. 패턴 픽셀 버퍼와 대상 크기를 설정하고 Width / Height를 업데이트하며 기본 압축 모드 0을 사용하여 저장할 데이터를 저장합니다"
type: docs
weight: 110
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/setpattern/
---
{{< psd/tize >}}
## PattResourceData.SetPattern method

패턴 픽셀 버퍼와 대상 크기를 설정하고, [`Width`](../width/) / [`Height`](../height/)를 업데이트하며, 기본 압축 모드 (0)을 사용하여 저장할 데이터를 저장합니다.

```csharp
public void SetPattern(int[] pixels, Rectangle bounds)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 픽셀 | Int32[] | `0xAARRGGBB` 형식의 32비트 픽셀. |
| bounds | Rectangle | 패턴의 픽셀 경계. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | 픽셀 배열 길이는 경계 영역과 같아야 합니다. |

### 또 보기

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [PattResourceData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


