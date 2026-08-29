---
title: "GifOptions.PixelAspectRatio"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "GifOptions 속성. GIF 픽셀 종횡비를 가져오거나 설정합니다"
type: docs
weight: 90
url: /ko/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
{{< psd/tize >}}
## GifOptions.PixelAspectRatio property

GIF 픽셀 종횡비를 가져오거나 설정합니다.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

GIF 픽셀 종횡비.

## 비고

Pixel Aspect Ratio - 원본 이미지에서 픽셀의 종횡비 근사값을 계산하는 데 사용되는 요소입니다. 필드 값이 0이 아니면, 다음 공식에 따라 종횡비 근사값을 계산합니다: 종횡비 = (Pixel Aspect Ratio + 15) / 64 Pixel Aspect Ratio는 픽셀의 너비를 높이로 나눈 값으로 정의됩니다. 이 필드의 값 범위는 가장 넓은 픽셀 4:1부터 가장 높은 픽셀 1:4까지 1/64 단위로 지정할 수 있습니다. 값: 0 - 종횡비 정보가 제공되지 않음. 1..255 - 계산에 사용되는 값.

### 또 보기

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


