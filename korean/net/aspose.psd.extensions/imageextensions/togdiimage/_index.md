---
title: "ImageExtensions.ToGdiImage"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ImageExtensions 메서드. Image를 Image로 변환합니다."
type: docs
weight: 10
url: /ko/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Image를 Image로 변환합니다.

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | Image | 변환할 Image. |

### 반환 값

변환된 Image.

## 비고

경고, GDI 이미지가 *image*보다 낮은 경계값을 가질 수 있습니다. 이미지의 모든 부분을 얻으려면 보다 안전한 확장 메서드 ToGdiImageFull을 사용하십시오.

### 또 보기

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


