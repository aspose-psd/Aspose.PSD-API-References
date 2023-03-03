---
title: Class LayerResourcesRegistry
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry 수업. PSD 파일 로드를 위한 레이어 리소스 레지스트리를 정의합니다.
type: docs
weight: 3390
url: /ko/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
## LayerResourcesRegistry class

PSD 파일 로드를 위한 레이어 리소스 레지스트리를 정의합니다.

```csharp
public static class LayerResourcesRegistry
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | 등록된 설명자를 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | 지원되는 첫 번째 오프너 설명자를 가져옵니다. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | 형식 이름으로 지원되는 첫 번째 설명자를 가져옵니다. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | 로드[`LayerResource`](../layerresource/) 지정된 항목에 적합한 첫 번째 발견 오프너 사용*stream* . |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | 오프너를 등록합니다. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | 오프너 등록을 취소합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 집회 [Aspose.PSD](../../)


