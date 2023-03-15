---
title: Class StringFormat
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.StringFormat 수업. 텍스트 레이아웃 정보예 정렬 방향 및 탭 정지 디스플레이 조작예 줄임표 삽입 및 국가별 숫자 대체 및 OpenType 기능을 캡슐화합니다. 이 클래스는 상속될 수 없습니다.
type: docs
weight: 5670
url: /ko/net/aspose.psd/stringformat/
---
## StringFormat class

텍스트 레이아웃 정보(예: 정렬, 방향 및 탭 정지) 디스플레이 조작(예: 줄임표 삽입 및 국가별 숫자 대체) 및 OpenType 기능을 캡슐화합니다. 이 클래스는 상속될 수 없습니다.

```csharp
public sealed class StringFormat : DisposableObject
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | 새 항목을 초기화합니다.`StringFormat` object. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | 새 항목을 초기화합니다.`StringFormat` 지정된 기존의 객체`StringFormat` object. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | 새 항목을 초기화합니다.`StringFormat` 지정된 객체[`StringFormatFlags`](../stringformatflags/) 열거 및 언어. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | 일반 기본값을 가져옵니다.`StringFormat` object. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | 일반 타이포그래피를 가져옵니다.`StringFormat` object. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | 수직면의 텍스트 정렬 정보를 가져오거나 설정합니다. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | 지역 숫자가 서부 숫자로 대체될 때 사용되는 언어를 가져오거나 설정합니다. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | 숫자 대체에 사용할 메서드를 가져오거나 설정합니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | 텍스트 줄의 시작과 첫 번째 탭 정지 사이의 공백 수를 가져옵니다. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | 가져오거나 설정합니다.[`StringFormatFlags`](../stringformatflags/) 서식 정보를 포함하는 열거형. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | 가져오거나 설정합니다.[`HotkeyPrefix`](../hotkeyprefix/) 이에 대한 객체`StringFormat` object. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | 수평면의 선 정렬을 가져오거나 설정합니다. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | 에 의해 지정된 단위로 탭 정지 사이의 거리 배열을 가져옵니다.[`PageUnit`](../graphics/pageunit/) 속성. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | 가져오거나 설정합니다.[`StringTrimming`](../stringtrimming/) 이에 대한 열거`StringFormat` object. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | 이것의 딥 클론을 생성합니다.`StringFormat` object. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | 이에 대한 탭 중지를 설정합니다.`StringFormat` object. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | 이것을 변환`StringFormat` 사람이 읽을 수 있는 문자열에 대한 개체입니다. |

### 또한보십시오

* class [DisposableObject](../disposableobject/)
* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


