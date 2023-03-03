---
title: Enum TextRenderingHint
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.TextRenderingHint 열거형. 텍스트 렌더링 품질을 지정합니다.
type: docs
weight: 5700
url: /ko/net/aspose.psd/textrenderinghint/
---
## TextRenderingHint enumeration

텍스트 렌더링 품질을 지정합니다.

```csharp
public enum TextRenderingHint
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| SystemDefault | `0` | 각 문자는 시스템 기본 렌더링 힌트와 함께 글리프 비트맵을 사용하여 그려집니다. 텍스트는 사용자가 시스템에 대해 선택한 글꼴 다듬기 설정을 사용하여 그려집니다. |
| SingleBitPerPixelGridFit | `1` | 각 문자는 글리프 비트맵을 사용하여 그려집니다. 힌트는 줄기와 곡률의 문자 모양을 개선하는 데 사용됩니다. |
| SingleBitPerPixel | `2` | 각 문자는 글리프 비트맵을 사용하여 그려집니다. 힌트는 사용하지 않습니다. |
| AntiAliasGridFit | `3` | 각 문자는 힌트와 함께 앤티앨리어싱된 글리프 비트맵을 사용하여 그려집니다. 앤티앨리어싱으로 인해 품질이 훨씬 좋아졌지만 성능 비용이 더 많이 듭니다. |
| AntiAlias | `4` | 각 문자는 힌트 없이 앤티앨리어싱된 글리프 비트맵을 사용하여 그려집니다. 앤티 앨리어싱으로 인해 더 나은 품질. 힌팅이 꺼졌기 때문에 스템 너비 차이가 눈에 띌 수 있습니다. |
| ClearTypeGridFit | `5` | 각 문자는 힌트가 있는 문자 모양 ClearType 비트맵을 사용하여 그려집니다. 최고 품질 설정입니다. ClearType 글꼴 기능을 활용하기 위해 사용합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


