---
title: "열거형 TextRenderingHint"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.TextRenderingHint 열거형. 텍스트 렌더링 품질을 지정합니다."
type: docs
weight: 6200
url: /ko/net/aspose.psd/textrenderinghint/
---
{{< psd/tize >}}
## TextRenderingHint enumeration

텍스트 렌더링 품질을 지정합니다.

```csharp
public enum TextRenderingHint
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| SystemDefault | `0` | 각 문자는 해당 글리프 비트맵을 사용하여 그려지며, 시스템 기본 렌더링 힌트를 사용합니다. 텍스트는 사용자가 시스템에 선택한 폰트 스무딩 설정에 따라 그려집니다. |
| SingleBitPerPixelGridFit | `1` | 각 문자는 해당 글리프 비트맵을 사용하여 그려집니다. 힌팅은 줄기와 곡선에서 문자 모양을 개선하는 데 사용됩니다. |
| SingleBitPerPixel | `2` | 각 문자는 해당 글리프 비트맵을 사용하여 그려집니다. 힌팅은 사용되지 않습니다. |
| AntiAliasGridFit | `3` | 각 문자는 힌팅이 적용된 안티앨리어싱 글리프 비트맵을 사용하여 그려집니다. 안티앨리어싱으로 인해 품질이 크게 향상되지만 성능 비용이 더 높습니다. |
| AntiAlias | `4` | 각 문자는 힌팅 없이 안티앨리어싱 글리프 비트맵을 사용하여 그려집니다. 안티앨리어싱으로 인해 품질이 향상됩니다. 힌팅이 꺼져 있기 때문에 줄기 너비 차이가 눈에 띌 수 있습니다. |
| ClearTypeGridFit | `5` | 각 문자는 힌팅이 적용된 ClearType 글리프 비트맵을 사용하여 그려집니다. 최고 품질 설정이며, ClearType 폰트 기능을 활용하는 데 사용됩니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


