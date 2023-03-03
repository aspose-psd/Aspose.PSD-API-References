---
title: ImageExportersRegistry.GetFirstSupportedDescriptor
second_title: .NET API 참조용 Aspose.PSD
description: ImageExportersRegistry 방법. 지정된 저장 옵션 및 이미지에 적합한 첫 번째로 발견된 지원 설명자를 가져옵니다.
type: docs
weight: 40
url: /ko/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
## ImageExportersRegistry.GetFirstSupportedDescriptor method

지정된 저장 옵션 및 이미지에 적합한 첫 번째로 발견된 지원 설명자를 가져옵니다.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| image | Image | 내보낼 이미지입니다. |
| options | ImageOptionsBase | 옵션. |

### 반환 값

지정된 이미지 및 저장 옵션을 지원하는 내보내기 설명자 또는 해당 설명자가 없으면 null입니다.

### 비고

첫 번째 내보내기 설명자는 실제로 마지막으로 등록된 것입니다.

### 또한보십시오

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* 네임스페이스 [Aspose.PSD](../../imageexportersregistry/)
* 집회 [Aspose.PSD](../../../)


