---
title: "TiffOptions.ColorMap"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "TiffOptions 속성. 색상 맵을 가져오거나 설정합니다."
type: docs
weight: 70
url: /ko/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
{{< psd/tize >}}
## TiffOptions.ColorMap property

색상 맵을 가져오거나 설정합니다.

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

색상 맵.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | 값 |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | 색상 맵은 픽셀당 샘플 수가 1인 경우에만 정의될 수 있습니다. 또는 샘플당 비트가 정의되지 않았습니다. |
| ArgumentOutOfRangeException | value; 배열 길이는 다음 수식에 맞아야 합니다: 3 * (2**BitsPerSample). |

### 또 보기

* class [TiffOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


