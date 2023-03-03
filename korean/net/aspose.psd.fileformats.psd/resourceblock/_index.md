---
title: Class ResourceBlock
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.ResourceBlock 수업. 리소스 블록.
type: docs
weight: 3610
url: /ko/net/aspose.psd.fileformats.psd/resourceblock/
---
## ResourceBlock class

리소스 블록.

```csharp
public abstract class ResourceBlock
```

## 속성

| 이름 | 설명 |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | 리소스 데이터 크기를 바이트 단위로 가져옵니다. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | 필요한 최소 PSD 버전을 가져옵니다. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | 리소스 이름을 가져오거나 설정합니다. 파스칼 문자열, 크기를 균일하게 만들기 위해 패딩됨(널 이름은 2바이트의 0으로 구성됨). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | 리소스 서명을 가져옵니다. 항상 '8BIM'이어야 합니다. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | 데이터를 포함하여 리소스 블록 크기를 바이트 단위로 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 리소스 블록을 지정된 스트림에 저장합니다. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | 리소스 값의 유효성을 검사합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | ImageReady. 의 리소스 서명 |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | 일반 Photoshop 리소스 서명입니다. |

## 다른 멤버들

| 이름 | 설명 |
| --- | --- |
| enum [ResourceBlockState](resourceblock.resourceblockstate/) | 리소스 블록 상태를 나타냅니다. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 집회 [Aspose.PSD](../../)


