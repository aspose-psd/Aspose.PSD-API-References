---
title: "LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "LayerResourcesRegistry 메서드. 지정된 스트림에 적합한 첫 번째 발견된 오프너를 사용하여 LayerResource를 로드합니다."
type: docs
weight: 40
url: /ko/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

지정된 *스트림*에 적합한 첫 번째 발견된 오프너를 사용하여 [`LayerResource`](../../layerresource/)를 로드합니다.

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 스트림. |
| psdVersion | Int32 | PSD 버전입니다. |

### 반환 값

로드된 [`LayerResource`](../../layerresource/) 또는 오프너가 없으면 null을 반환합니다.

## 비고

첫 번째 오프너는 실제로 마지막에 등록된 것이 됩니다.

### 또 보기

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


