---
title: ImageExportersRegistry.CreateFirstSupportedExporter
second_title: .NET API 참조용 Aspose.PSD
description: ImageExportersRegistry 방법. 지정된 저장 옵션 및 이미지에 적합한 첫 번째로 찾은 내보내기를 생성합니다.
type: docs
weight: 30
url: /ko/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
## ImageExportersRegistry.CreateFirstSupportedExporter method

지정된 저장 옵션 및 이미지에 적합한 첫 번째로 찾은 내보내기를 생성합니다.

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| image | Image | 내보낼 이미지입니다. |
| options | ImageOptionsBase | 내보내기에 사용할 저장 옵션입니다. |

### 반환 값

지정된 이미지 및 저장 옵션을 지원하는 내보내기 또는 해당 내보내기가 없는 경우 null입니다.

### 비고

첫 번째 수출자는 실제로 마지막으로 등록됩니다.

### 또한보십시오

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* 네임스페이스 [Aspose.PSD](../../imageexportersregistry/)
* 집회 [Aspose.PSD](../../../)


