---
title: "클래스 OSTypeStructuresRegistry"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructuresRegistry 클래스. OSTypeStructure 리소스 레지스트리를 나타냅니다."
type: docs
weight: 3200
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry class

[`OSTypeStructure`](../ostypestructure/) 리소스 레지스트리를 나타냅니다.

```csharp
public static class OSTypeStructuresRegistry
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registereddescriptors/) { get; } | 등록된 디스크립터를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/)(Stream) | 첫 번째 지원되는 오프너 디스크립터를 가져옵니다. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptorbytypename/)(string) | 유형 이름으로 첫 번째 지원되는 디스크립터를 가져옵니다. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/loadresourcebyfirstsupporteddescriptor/)(Stream) | 지정된 *stream*에 적합한 첫 번째 발견된 오프너를 사용하여 [`OSTypeStructure`](../ostypestructure/)를 로드합니다. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registeropener/)(IOSTypeStructureLoader) | 오프너를 등록합니다. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/unregisteropener/)(IOSTypeStructureLoader) | 오프너의 등록을 취소합니다. |

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


