---
title: Class ImageLoadersRegistry
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.ImageLoadersRegistry 수업. 이미지 로더 레지스트리를 나타냅니다.
type: docs
weight: 4780
url: /ko/net/aspose.psd/imageloadersregistry/
---
## ImageLoadersRegistry class

이미지 로더 레지스트리를 나타냅니다.

```csharp
public static class ImageLoadersRegistry
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | 등록된 설명자를 가져옵니다. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | 등록된 이미지 로딩 형식을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | 지정된 대상에 적합한 첫 번째 발견된 로더를 생성합니다.*stream* 선택적으로*loadOptions* . |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | 지정된 항목에 적합한 첫 번째로 발견된 지원 설명자를 가져옵니다.*stream* 선택적으로*loadOptions* . |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | 형식 이름으로 지원되는 첫 번째 파일 형식을 가져옵니다. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | 형식 이름으로 지원되는 첫 번째 설명자를 가져옵니다. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | 지정된 이미지 로더 설명자를 등록합니다. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | 로더를 등록합니다. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | 로더 등록을 취소합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


