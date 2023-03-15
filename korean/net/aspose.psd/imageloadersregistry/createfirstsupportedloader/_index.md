---
title: ImageLoadersRegistry.CreateFirstSupportedLoader
second_title: .NET API 참조용 Aspose.PSD
description: ImageLoadersRegistry 방법. 지정된 대상에 적합한 첫 번째 발견된 로더를 생성합니다.stream 선택적으로loadOptions .
type: docs
weight: 30
url: /ko/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

지정된 대상에 적합한 첫 번째 발견된 로더를 생성합니다.*stream* 선택적으로*loadOptions* .

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 스트림. |
| loadOptions | LoadOptions | 로드 옵션. |

### 반환 값

지정된 것을 지원하는 로더*stream* 그리고*loadOptions* 또는 해당 로더가 없으면 null입니다.

### 비고

첫 번째 로더는 실제로 마지막으로 등록된 것입니다.

### 또한보십시오

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* 네임스페이스 [Aspose.PSD](../../imageloadersregistry/)
* 집회 [Aspose.PSD](../../../)


