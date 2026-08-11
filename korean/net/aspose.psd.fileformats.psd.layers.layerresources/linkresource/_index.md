---
title: "클래스 LinkResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource 클래스. PSD 형식 이미지에서 연결되거나 포함된 파일에 대한 정보를 포함하는 LinkResource 클래스를 정의합니다. 링크 리소스는 파생 클래스에서 인덱서를 통해 액세스할 수 있는 여러 LinkDataSource 인스턴스를 포함할 수 있습니다."
type: docs
weight: 3010
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
{{< psd/tize >}}
## LinkResource class

PSD 형식 이미지에서 연결되거나 포함된 파일에 대한 정보를 포함하는 LinkResource 클래스를 정의합니다. 링크 리소스는 파생 클래스에서 인덱서를 통해 액세스할 수 있는 여러 [`LinkDataSource`](../linkdatasource/) 인스턴스를 포함할 수 있습니다.

```csharp
public abstract class LinkResource : LayerResource
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | 인덱서를 통해 접근할 수 있는 링크 데이터 소스의 개수를 가져옵니다. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | 이 링크 리소스 인스턴스가 비어 있는지 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | 지정된 인덱스에 있는 [`LinkDataSource`](../linkdatasource/)를 가져옵니다. 이는 링크 데이터 소스 고유 식별자입니다. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | PSD 전역 링크 리소스 길이를 바이트 단위로 가져옵니다. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | 리소스 블록 데이터를 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

### 또 보기

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


