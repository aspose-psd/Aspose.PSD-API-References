---
title: "LayerGroupsEnabledResource 클래스"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Resources.LayerGroupsEnabledResource 클래스. 레이어 그룹 활성화 리소스"
type: docs
weight: 4260
url: /ko/net/aspose.psd.fileformats.psd.resources/layergroupsenabledresource/
---
{{< psd/tize >}}
## LayerGroupsEnabledResource class

Layer groups enabled 리소스

```csharp
public sealed class LayerGroupsEnabledResource : ResourceBlock
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LayerGroupsEnabledResource](layergroupsenabledresource/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/layergroupsenabledresource/datasize/) { get; } | 리소스 데이터 크기를 바이트 단위로 가져옵니다. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| [IDs](../../aspose.psd.fileformats.psd.resources/layergroupsenabledresource/ids/) { get; set; } | i ds를 가져오거나 설정합니다. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/layergroupsenabledresource/minimalversion/) { get; } | 필요한 최소 PSD 버전을 가져옵니다. |
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


