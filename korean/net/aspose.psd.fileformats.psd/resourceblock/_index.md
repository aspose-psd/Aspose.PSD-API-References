---
title: "클래스 ResourceBlock"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.ResourceBlock class. 리소스 블록"
type: docs
weight: 4070
url: /ko/net/aspose.psd.fileformats.psd/resourceblock/
---
{{< psd/tize >}}
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
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | 리소스 이름을 가져오거나 설정합니다. Pascal 문자열이며, 크기를 짝수로 맞추기 위해 패딩됩니다(널 이름은 0 두 바이트로 구성됩니다). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | 리소스 서명을 가져옵니다. 항상 '8BIM'이어야 합니다. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | 데이터를 포함한 리소스 블록 크기를 바이트 단위로 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 지정된 스트림에 리소스 블록을 저장합니다. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | 리소스 값을 검증합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | ImageReady의 리소스 서명. |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | 일반 Photoshop 리소스 서명. |

## 다른 멤버

| 이름 | 설명 |
| --- | --- |
| enum [ResourceBlockState](../../aspose.psd.fileformats.psd/resourceblock.resourceblockstate) | 리소스 블록 상태를 나타냅니다. |

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


