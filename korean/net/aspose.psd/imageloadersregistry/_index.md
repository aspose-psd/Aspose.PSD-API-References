---
title: "ImageLoadersRegistry 클래스"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.ImageLoadersRegistry 클래스. 이미지 로더 레지스트리를 나타냅니다."
type: docs
weight: 5270
url: /ko/net/aspose.psd/imageloadersregistry/
---
{{< psd/tize >}}
## ImageLoadersRegistry class

이미지 로더 레지스트리를 나타냅니다.

```csharp
public static class ImageLoadersRegistry
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | 등록된 디스크립터를 가져옵니다. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | 등록된 이미지 로딩 형식을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | 지정된 *stream*에 적합하고 선택적으로 *loadOptions*에 적합한 첫 번째 로더를 생성합니다. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | 지정된 *stream*에 적합하고 선택적으로 *loadOptions*에 적합한 첫 번째 지원되는 설명자를 가져옵니다. |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | 형식 이름으로 첫 번째 지원되는 파일 형식을 가져옵니다. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | 유형 이름으로 첫 번째 지원되는 디스크립터를 가져옵니다. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | 지정된 이미지 로더 설명자를 등록합니다. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | 로드러를 등록합니다. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | 로드러의 등록을 취소합니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


