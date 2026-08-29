---
title: "클래스 ShmdResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ShmdResource 클래스. 클래스 ShmdResource. 메타데이터 설정"
type: docs
weight: 3330
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/
---
{{< psd/tize >}}
## ShmdResource class

ShmdResource 클래스. 메타데이터 설정

```csharp
public class ShmdResource : LayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ShmdResource](shmdresource/#constructor)() | 새 `ShmdResource` 클래스의 인스턴스를 초기화합니다. |
| [ShmdResource](shmdresource/#constructor_1)(byte[]) | 새 `ShmdResource` 클래스의 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| [LayerCreatedDateTime](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/layercreateddatetime/) { get; set; } | 레이어 생성 시간을 가져오거나 설정합니다. 레이어 생성 시간이 지정되지 않으면 new DateTime(0)을 반환합니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |
| [SubResources](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/) { get; } | shmd 리소스의 하위 리소스를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/save/)(StreamContainer, int) | 지정된 스트림 컨테이너를 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [SubResourceHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresourceheaderlength/) | 하위 리소스 헤더 길이 |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/typetoolkey/) | 타입 툴 정보 키. |

### 또 보기

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


