---
title: Class TransparencyIndexResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Resources.TransparencyIndexResource 수업. 투명 인덱스 리소스 블록입니다.
type: docs
weight: 3920
url: /ko/net/aspose.psd.fileformats.psd.resources/transparencyindexresource/
---
## TransparencyIndexResource class

투명 인덱스 리소스 블록입니다.

```csharp
public sealed class TransparencyIndexResource : ResourceBlock
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TransparencyIndexResource](transparencyindexresource/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/transparencyindexresource/datasize/) { get; } | 리소스 데이터 크기를 바이트 단위로 가져옵니다. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/transparencyindexresource/minimalversion/) { get; } | 최소한의 필수 psd 버전을 가져옵니다. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | 리소스 이름을 가져오거나 설정합니다. 파스칼 문자열, 크기를 균일하게 만들기 위해 패딩됨(널 이름은 2바이트의 0으로 구성됨). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | 리소스 서명을 가져옵니다. 항상 '8BIM'이어야 합니다. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | 데이터를 포함하여 리소스 블록 크기를 바이트 단위로 가져옵니다. |
| [TransparencyIndex](../../aspose.psd.fileformats.psd.resources/transparencyindexresource/transparencyindex/) { get; set; } | 투명도 색상 인덱스를 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 리소스 블록을 지정된 스트림에 저장합니다. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | 리소스 값의 유효성을 검사합니다. |

### 또한보십시오

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* 집회 [Aspose.PSD](../../)


