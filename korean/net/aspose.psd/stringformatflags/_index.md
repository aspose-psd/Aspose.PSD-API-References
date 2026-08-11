---
title: "열거형 StringFormatFlags"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.StringFormatFlags 열거형. 텍스트 문자열에 대한 표시 및 레이아웃 정보를 지정합니다."
type: docs
weight: 6180
url: /ko/net/aspose.psd/stringformatflags/
---
{{< psd/tize >}}
## StringFormatFlags enumeration

텍스트 문자열에 대한 표시 및 레이아웃 정보를 지정합니다.

```csharp
[Flags]
public enum StringFormatFlags
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| DirectionRightToLeft | `1` | 텍스트가 오른쪽에서 왼쪽으로 표시됩니다. |
| DirectionVertical | `2` | 텍스트가 수직으로 정렬됩니다. |
| FitBlackBox | `4` | 문자 일부가 문자열 레이아웃 사각형을 넘어설 수 있습니다. 기본적으로 문자는 오버행을 방지하도록 재배치됩니다. |
| DisplayFormatControl | `20` | 왼쪽에서 오른쪽으로 표시 마크와 같은 제어 문자는 출력에 대표 글리프로 표시됩니다. |
| NoFontFallback | `400` | 요청된 글꼴에서 지원되지 않는 문자를 대체 글꼴로 대체하는 기능이 비활성화됩니다. 누락된 문자는 일반적으로 빈 사각형인 글꼴의 누락 글리프로 표시됩니다. |
| MeasureTrailingSpaces | `800` | 각 줄 끝의 후행 공백을 포함합니다. 기본적으로 MeasureString 메서드가 반환하는 경계 사각형은 각 줄 끝의 공백을 제외합니다. 이 플래그를 설정하면 측정에 해당 공백을 포함합니다. |
| NoWrap | `1000` | 사각형 내부에서 서식을 지정할 때 줄 사이의 텍스트 래핑이 비활성화됩니다. 이 플래그는 사각형 대신 점이 전달되었거나 지정된 사각형의 줄 길이가 0인 경우에 암시됩니다. |
| LineLimit | `2000` | 서식 사각형에는 전체 줄만 배치됩니다. 기본적으로 레이아웃은 텍스트 끝까지 또는 클리핑으로 인해 더 이상 보이는 줄이 없을 때까지, 둘 중 먼저 발생하는 시점까지 계속됩니다. 기본 설정에서는 줄 높이의 정수 배가 아닌 서식 사각형에 의해 마지막 줄이 부분적으로 가려질 수 있다는 점에 유의하십시오. 전체 줄만 보이도록 하려면 이 값을 지정하고, 최소한 한 줄 높이만큼 높은 서식 사각형을 제공하도록 주의하십시오. |
| NoClip | `4000` | 글리프의 돌출된 부분과 서식 사각형 밖으로 벗어나는 래핑되지 않은 텍스트는 표시될 수 있습니다. 기본적으로 서식 사각형 밖으로 벗어나는 모든 텍스트와 글리프 부분은 클리핑됩니다. |
| ExactAlignment | `8000` | 정확한 정렬, 올바른 패딩 GDI+ |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


