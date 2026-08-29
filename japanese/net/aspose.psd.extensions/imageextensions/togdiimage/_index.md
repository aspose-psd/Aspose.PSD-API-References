---
title: "ImageExtensions.ToGdiImage"
second_title: "Aspose.PSD for .NET API Reference"
description: "ImageExtensions メソッド。Image を Image に変換します。"
type: docs
weight: 10
url: /ja/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Image を Image に変換します。

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Image | 変換する Image。 |

### 戻り値

変換された Image。

## 備考

警告: GDI 画像は *image* の境界より小さくなる可能性があります。画像のすべての部分を取得するには、より安全な拡張メソッド ToGdiImageFull を使用してください。

### 関連項目

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


