---
title: Class GridAndGuidesResouce
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Resources.GridAndGuidesResouce 수업. 그리드 및 가이드 리소스를 나타냅니다.
type: docs
weight: 3730
url: /ko/net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---
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
| [GridCycleX](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcyclex/) { get; set; } | 수평 그리드 주기를 가져오거나 설정합니다. 기본값은 576. 입니다. |
| [GridCycleY](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcycley/) { get; set; } | 수직 그리드 주기를 가져오거나 설정합니다. 기본값은 576. 입니다. |
| [GuideCount](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guidecount/) { get; } | 가이드 리소스 블록 수를 가져옵니다. |
| [Guides](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guides/) { get; set; } | 가이드를 가져오거나 설정합니다. |
| [HeaderVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/headerversion/) { get; set; } | 헤더 버전을 가져오거나 설정합니다. 이 값은 항상 1. 여야 합니다. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/minimalversion/) { get; } | 최소한의 필수 psd 버전을 가져옵니다. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | 리소스 이름을 가져오거나 설정합니다. 파스칼 문자열, 크기를 균일하게 만들기 위해 패딩됨(널 이름은 2바이트의 0으로 구성됨). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | 리소스 서명을 가져옵니다. 항상 '8BIM'이어야 합니다. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | 데이터를 포함하여 리소스 블록 크기를 바이트 단위로 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 리소스 블록을 지정된 스트림에 저장합니다. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | 리소스 값의 유효성을 검사합니다. |

### 또한보십시오

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* 집회 [Aspose.PSD](../../)


