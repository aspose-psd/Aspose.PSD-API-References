---
title: Class LinkResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource 수업. PSD 형식 이미지에 링크되거나 포함된 파일에 대한 정보를 포함하는 LinkResource 클래스를 정의합니다. 링크 리소스에는 여러 개가 포함될 수 있습니다.LinkDataSource 모든 파생 클래스의 인덱서에서 액세스할 수 있는 인스턴스.
type: docs
weight: 2710
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
## LinkResource class

PSD 형식 이미지에 링크되거나 포함된 파일에 대한 정보를 포함하는 LinkResource 클래스를 정의합니다. 링크 리소스에는 여러 개가 포함될 수 있습니다.[`LinkDataSource`](../linkdatasource/) 모든 파생 클래스의 인덱서에서 액세스할 수 있는 인스턴스.

```csharp
public abstract class LinkResource : LayerResource
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | 인덱서에서 액세스할 수 있는 링크 데이터 소스의 수를 가져옵니다. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | 이 링크 리소스 인스턴스가 비어 있는지 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | 가져오기[`LinkDataSource`](../linkdatasource/) 링크 데이터 소스 고유 식별자인 지정된 인덱스에서.. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | PSD 전역 링크 리소스 길이를 바이트 단위로 가져옵니다. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | PSD 형식 버전을 가져옵니다. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | PSD 전역 링크 리소스 서명을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | 리소스 블록 데이터를 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

### 또한보십시오

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 집회 [Aspose.PSD](../../)


