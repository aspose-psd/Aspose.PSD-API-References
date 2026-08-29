---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ImageLoadersRegistry 메서드. 지정된 스트림에 적합하고 선택적으로 loadOptions에 맞는 첫 번째 지원되는 설명자를 가져옵니다"
type: docs
weight: 40
url: /ko/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

지정된 *stream*에 적합하고 선택적으로 *loadOptions*에 적합한 첫 번째 지원되는 설명자를 가져옵니다.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 스트림. |
| loadOptions | LoadOptions | 로드 옵션. |

### 반환 값

지정된 *stream* 및 *loadOptions*를 지원하는 로더 설명자 또는 해당 설명자를 찾을 수 없을 경우 null입니다.

## 비고

첫 번째 로더 설명자는 실제로 마지막에 등록된 것입니다.

### 또 보기

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


