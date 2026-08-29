---
title: "열거형 InterpolationMode"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.InterpolationMode 열거형. InterpolationMode 열거형은 이미지가 확대 또는 회전될 때 사용되는 알고리즘을 지정합니다."
type: docs
weight: 5520
url: /ko/net/aspose.psd/interpolationmode/
---
{{< psd/tize >}}
## InterpolationMode enumeration

`InterpolationMode` 열거형은 이미지가 확대 또는 회전될 때 사용되는 알고리즘을 지정합니다.

```csharp
public enum InterpolationMode
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Invalid | `-1` | 잘못된 보간 모드입니다. |
| Default | `0` | 기본 모드를 지정합니다. |
| Low | `1` | 낮은 품질 보간을 지정합니다. |
| High | `2` | 높은 품질 보간을 지정합니다. |
| Bilinear | `3` | 양선형 보간을 지정합니다. 사전 필터링이 수행되지 않습니다. 이 모드는 이미지 크기를 원본의 50% 이하로 축소하는 데 적합하지 않습니다. |
| Bicubic | `4` | 삼차 보간을 지정합니다. 사전 필터링이 수행되지 않습니다. 이 모드는 이미지 크기를 원본의 25% 이하로 축소하는 데 적합하지 않습니다. |
| NearestNeighbor | `5` | 최근접 이웃 보간법을 지정합니다. |
| HighQualityBilinear | `6` | 고품질 양선형 보간법을 지정합니다. 고품질 축소를 보장하기 위해 사전 필터링이 수행됩니다. |
| HighQualityBicubic | `7` | 고품질 삼차 보간법을 지정합니다. 고품질 축소를 보장하기 위해 사전 필터링이 수행됩니다. 이 모드는 가장 높은 품질의 변환된 이미지를 생성합니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


