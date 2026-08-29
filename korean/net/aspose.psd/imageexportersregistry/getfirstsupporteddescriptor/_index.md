---
title: "ImageExportersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ImageExportersRegistry 메서드. 지정된 저장 옵션 및 이미지에 적합한 첫 번째 지원되는 설명자를 가져옵니다"
type: docs
weight: 40
url: /ko/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageExportersRegistry.GetFirstSupportedDescriptor method

지정된 저장 옵션 및 이미지에 적합한 첫 번째 지원되는 설명자를 가져옵니다.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | Image | 내보낼 이미지. |
| 옵션 | ImageOptionsBase | 옵션. |

### 반환 값

지정된 이미지와 저장 옵션을 지원하는 내보내기 설명자이며, 해당 설명자를 찾을 수 없으면 null을 반환합니다.

## 비고

첫 번째 내보내기 설명자는 실제로 마지막에 등록된 것입니다.

### 또 보기

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


