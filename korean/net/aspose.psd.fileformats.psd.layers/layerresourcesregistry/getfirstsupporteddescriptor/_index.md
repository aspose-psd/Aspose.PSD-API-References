---
title: LayerResourcesRegistry.GetFirstSupportedDescriptor
second_title: .NET API 참조용 Aspose.PSD
description: LayerResourcesRegistry 방법. 지원되는 첫 번째 오프너 설명자를 가져옵니다.
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

지원되는 첫 번째 오프너 설명자를 가져옵니다.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 스트림. |
| psdVersion | Int32 | PSD 버전입니다. |

### 반환 값

계층 리소스 로더 설명자 또는 이러한 스트림에 대해 지원되는 로더 설명자가 없는 경우 null입니다.

### 비고

첫 번째 로더는 실제로 마지막으로 등록된 것입니다.

### 또한보십시오

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* 집회 [Aspose.PSD](../../../)


