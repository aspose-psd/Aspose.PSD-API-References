---
title: Enum StringFormatFlags
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.StringFormatFlags 열거형. 텍스트 문자열에 대한 표시 및 레이아웃 정보를 지정합니다.
type: docs
weight: 5680
url: /ko/net/aspose.psd/stringformatflags/
---
## StringFormatFlags enumeration

텍스트 문자열에 대한 표시 및 레이아웃 정보를 지정합니다.

```csharp
[Flags]
public enum StringFormatFlags
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| DirectionRightToLeft | `1` | 텍스트는 오른쪽에서 왼쪽으로 표시됩니다. |
| DirectionVertical | `2` | 텍스트가 세로로 정렬됩니다. |
| FitBlackBox | `4` | 문자의 일부가 문자열의 레이아웃 사각형을 넘어설 수 있습니다. 기본적으로 문자는 오버행을 피하기 위해 재배치됩니다. |
| DisplayFormatControl | `20` | 왼쪽에서 오른쪽 표시와 같은 제어 문자는 대표 글리프와 함께 출력에 표시됩니다. |
| NoFontFallback | `400` | 요청한 글꼴에서 지원되지 않는 문자에 대한 대체 글꼴로의 폴백이 비활성화됩니다. 누락된 문자는 글꼴 누락 글리프(일반적으로 열린 사각형)와 함께 표시됩니다. |
| MeasureTrailingSpaces | `800` | 각 줄 끝에 후행 공백을 포함합니다. 기본적으로 MeasureString 메서드에서 반환된 경계 사각형은 각 줄의 끝에 있는 공간을 제외합니다. 측정에 해당 공간을 포함하도록 이 플래그를 설정합니다. |
| NoWrap | `1000` | 사각형 내에서 서식을 지정할 때 줄 사이의 텍스트 줄 바꿈이 비활성화됩니다. 이 플래그는 사각형 대신 점이 전달되거나 지정된 사각형의 선 길이가 0인 경우 암시됩니다. |
| LineLimit | `2000` | 서식 지정 사각형에는 전체 줄만 배치됩니다. 기본적으로 레이아웃은 텍스트가 끝날 때까지 또는 클리핑으로 인해 더 이상 줄이 표시되지 않을 때까지 계속됩니다. 둘 중 먼저 발생하는 것이 적용됩니다. 기본 설정을 사용하면 마지막 줄이 줄 높이의 전체 배수. 전체 줄만 표시되도록 하려면 이 값을 지정하고 최소한 한 줄의 높이만큼 서식 사각형을 제공하도록 주의하십시오. |
| NoClip | `4000` | 글리프의 돌출된 부분과 서식 지정 사각형 외부에 도달하는 래핑되지 않은 텍스트가 표시될 수 있습니다. 기본적으로 서식 지정 사각형 외부에 도달하는 모든 텍스트 및 글리프 부분은 잘립니다. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


