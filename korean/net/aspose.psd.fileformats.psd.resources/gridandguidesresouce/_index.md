---
title: "클래스 GridAndGuidesResouce"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Resources.GridAndGuidesResouce 클래스. 그리드 및 가이드 리소스를 나타냅니다."
type: docs
weight: 4200
url: /ko/net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---
{{< psd/tize >}}
## GridAndGuidesResouce class

그리드 및 가이드 리소스를 나타냅니다.

```csharp
public sealed class GridAndGuidesResouce : ResourceBlock
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [GridAndGuidesResouce](gridandguidesresouce/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/datasize/) { get; } | 리소스 데이터 크기를 바이트 단위로 가져옵니다. |
| [GridCycleX](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcyclex/) { get; set; } | 수평 그리드 주기를 가져오거나 설정합니다. 기본값은 576입니다. |
| [GridCycleY](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcycley/) { get; set; } | 수직 그리드 주기를 가져오거나 설정합니다. 기본값은 576입니다. |
| [GuideCount](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guidecount/) { get; } | 가이드 리소스 블록 수를 가져옵니다. |
| [Guides](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guides/) { get; set; } | 가이드를 가져오거나 설정합니다. |
| [HeaderVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/headerversion/) { get; set; } | 헤더 버전을 가져오거나 설정합니다. 이 값은 항상 1이어야 합니다. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/minimalversion/) { get; } | 필요한 최소 PSD 버전을 가져옵니다. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | 리소스 이름을 가져오거나 설정합니다. Pascal 문자열이며, 크기를 짝수로 맞추기 위해 패딩됩니다(널 이름은 0 두 바이트로 구성됩니다). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | 리소스 서명을 가져옵니다. 항상 '8BIM'이어야 합니다. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | 데이터를 포함한 리소스 블록 크기를 바이트 단위로 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 지정된 스트림에 리소스 블록을 저장합니다. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | 리소스 값을 검증합니다. |

### 또 보기

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


