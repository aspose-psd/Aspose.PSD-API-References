---
title: "클래스 LayerResourcesRegistry"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry 클래스. PSD 파일 로드를 위한 레이어 리소스 레지스트리를 정의합니다."
type: docs
weight: 3790
url: /ko/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
{{< psd/tize >}}
## LayerResourcesRegistry class

PSD 파일 로드를 위한 레이어 리소스 레지스트리를 정의합니다.

```csharp
public static class LayerResourcesRegistry
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | 등록된 디스크립터를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | 첫 번째 지원되는 오프너 디스크립터를 가져옵니다. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | 유형 이름으로 첫 번째 지원되는 디스크립터를 가져옵니다. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | 지정된 *stream*에 적합한 첫 번째 발견된 오프너를 사용하여 [`LayerResource`](../layerresource/)을 로드합니다. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | 오프너를 등록합니다. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | 오프너의 등록을 취소합니다. |

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


