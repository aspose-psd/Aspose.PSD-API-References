---
title: "클래스 StringFormat"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.StringFormat 클래스. 정렬 방향 및 탭 정지와 같은 텍스트 레이아웃 정보를 캡슐화하고, 생략 부호 삽입, 국가별 숫자 대체, OpenType 기능과 같은 표시 조작을 포함합니다. 이 클래스는 상속할 수 없습니다."
type: docs
weight: 6170
url: /ko/net/aspose.psd/stringformat/
---
{{< psd/tize >}}
## StringFormat class

텍스트 레이아웃 정보(정렬, 방향 및 탭 정지와 같은)와 표시 조작(생략 부호 삽입 및 국가별 숫자 대체와 같은) 및 OpenType 기능을 캡슐화합니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class StringFormat : DisposableObject
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | 새 `StringFormat` 객체를 초기화합니다. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | 지정된 기존 `StringFormat` 객체에서 새 `StringFormat` 객체를 초기화합니다. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | 지정된 [`StringFormatFlags`](../stringformatflags/) 열거형 및 언어를 사용하여 새 `StringFormat` 객체를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | 일반 기본 `StringFormat` 객체를 가져옵니다. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | 일반 타이포그래픽 `StringFormat` 객체를 가져옵니다. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | 수직 평면에서 텍스트 정렬 정보를 가져오거나 설정합니다. |
| [CustomCharIdent](../../aspose.psd/stringformat/customcharident/) { get; set; } | 사용자 정의 문자 식별자를 가져오거나 설정합니다. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | 현지 숫자가 서양 숫자로 대체될 때 사용되는 언어를 가져오거나 설정합니다. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | 숫자 대체에 사용할 방법을 가져오거나 설정합니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | 텍스트 줄 시작과 첫 번째 탭 정지점 사이의 공백 수를 가져옵니다. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | 형식 정보를 포함하는 [`StringFormatFlags`](../stringformatflags/) 열거형을 가져오거나 설정합니다. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | 이 `StringFormat` 객체에 대한 [`HotkeyPrefix`](../hotkeyprefix/) 객체를 가져오거나 설정합니다. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | 수평면에서 라인 정렬을 가져오거나 설정합니다. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | `[`PageUnit`](../graphics/pageunit/)` 속성에서 지정한 단위로 탭 정지점 사이의 거리 배열을 가져옵니다. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | 이 `StringFormat` 객체에 대한 [`StringTrimming`](../stringtrimming/) 열거형을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | 이 `StringFormat` 객체의 깊은 복제본을 생성합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |
| override [Equals](../../aspose.psd/stringformat/equals/)(object) | 객체가 동일한지 확인합니다. |
| override [GetHashCode](../../aspose.psd/stringformat/gethashcode/)() | 현재 객체의 해시 코드를 가져옵니다. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | 이 `StringFormat` 객체에 대한 탭 정지점을 설정합니다. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | 이 `StringFormat` 객체를 사람이 읽을 수 있는 문자열로 변환합니다. |

### 또 보기

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


