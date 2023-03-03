---
title: ImageLoadersRegistry.GetFirstSupportedDescriptor
second_title: .NET API 참조용 Aspose.PSD
description: ImageLoadersRegistry 방법. 지정된 항목에 적합한 첫 번째로 발견된 지원 설명자를 가져옵니다.stream 선택적으로loadOptions .
type: docs
weight: 40
url: /ko/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

지정된 항목에 적합한 첫 번째로 발견된 지원 설명자를 가져옵니다.*stream* 선택적으로*loadOptions* .

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 스트림. |
| loadOptions | LoadOptions | 로드 옵션. |

### 반환 값

지정된 것을 지원하는 로더 설명자*stream* 그리고*loadOptions* 또는 해당 설명자가 없으면 null입니다.

### 비고

첫 번째 로더 설명자는 실제로 마지막으로 등록된 것입니다.

### 또한보십시오

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* 네임스페이스 [Aspose.PSD](../../imageloadersregistry/)
* 집회 [Aspose.PSD](../../../)


