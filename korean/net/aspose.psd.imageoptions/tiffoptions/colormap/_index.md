---
title: TiffOptions.ColorMap
second_title: .NET API 참조용 Aspose.PSD
description: TiffOptions 재산. 색상 맵을 가져오거나 설정합니다.
type: docs
weight: 70
url: /ko/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

색상 맵을 가져오거나 설정합니다.

```csharp
public ushort[] ColorMap { get; set; }
```

### 자산 가치

컬러 맵.

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 값 |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | 컬러 맵은 픽셀당 샘플이 1인 경우에만 정의될 수 있습니다. 또는 샘플당 비트가 정의되지 않습니다. |
| ArgumentOutOfRangeException | 값;배열 길이는 3 * (2**BitsPerSample) 공식과 일치해야 합니다. |

### 또한보십시오

* class [TiffOptions](../)
* 네임스페이스 [Aspose.PSD.ImageOptions](../../tiffoptions/)
* 집회 [Aspose.PSD](../../../)


