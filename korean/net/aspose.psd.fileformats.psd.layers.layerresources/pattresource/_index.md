---
title: "PattResource 클래스"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PattResource 클래스. PattResource 클래스. 패턴 데이터를 가진 리소스"
type: docs
weight: 3220
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---
{{< psd/tize >}}
## PattResource class

PattResource 클래스. 패턴 데이터를 포함하는 리소스

```csharp
public class PattResource : LayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PattResource](pattresource/#constructor)() | `PattResource` 클래스의 새 인스턴스를 초기화합니다. |
| [PattResource](pattresource/#constructor_1)(int, PattResourceData[]) | `PattResource` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/pattresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [Patterns](../../aspose.psd.fileformats.psd.layers.layerresources/pattresource/patterns/) { get; set; } | 패턴 데이터를 가져오거나 설정합니다; |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/pattresource/save/)(StreamContainer, int) | 리소스 블록 데이터를 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/pattresource/typetoolkey/) | 8비트용 'Patt' 유형 도구 정보 키입니다. |
| const [TypeToolKey2](../../aspose.psd.fileformats.psd.layers.layerresources/pattresource/typetoolkey2/) | 16비트용 'Pat2' 유형 도구 정보 키입니다. |
| const [TypeToolKey3](../../aspose.psd.fileformats.psd.layers.layerresources/pattresource/typetoolkey3/) | 32비트용 'Pat3' 유형 도구 정보 키입니다. |

### 또 보기

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


