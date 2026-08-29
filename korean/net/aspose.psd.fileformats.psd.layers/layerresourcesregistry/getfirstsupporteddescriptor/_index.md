---
title: "LayerResourcesRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "LayerResourcesRegistry 메서드. 첫 번째 지원되는 오프너 디스크립터를 가져옵니다."
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

첫 번째 지원되는 오프너 디스크립터를 가져옵니다.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 스트림. |
| psdVersion | Int32 | PSD 버전입니다. |

### 반환 값

해당 스트림에 대해 지원되는 로더 디스크립터가 없으면 레이어 리소스 로더 디스크립터 또는 null을 반환합니다.

## 비고

첫 번째 로더는 실제로 마지막에 등록된 것이 됩니다.

### 또 보기

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


