---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ImageLoadersRegistry 메서드. 지정된 *stream*에 적합하고 선택적으로 *loadOptions*에 맞는 첫 번째 로더를 생성합니다"
type: docs
weight: 30
url: /ko/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

지정된 *stream*에 적합하고 선택적으로 *loadOptions*에 적합한 첫 번째 로더를 생성합니다.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 스트림. |
| loadOptions | LoadOptions | 로드 옵션. |

### 반환 값

지정된 *stream* 및 *loadOptions*를 지원하는 로더이며, 해당 로더가 없으면 null을 반환합니다.

## 비고

첫 번째 로더는 실제로 마지막에 등록된 것이 됩니다.

### 또 보기

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


