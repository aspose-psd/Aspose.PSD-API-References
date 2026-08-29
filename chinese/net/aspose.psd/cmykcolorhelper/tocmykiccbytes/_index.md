---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Aspose.PSD for .NET API 参考"
description: "CmykColorHelper 方法。使用自定义 ICC 配置文件将 RGB 转换为 CMYK"
type: docs
weight: 120
url: /zh/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
{{< psd/tize >}}
## CmykColorHelper.ToCmykIccBytes method

使用自定义 ICC 配置文件将 RGB 转换为 CMYK。

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | Int32[] | RGB 颜色以 32 位整数值的形式呈现。 |
| startIndex | Int32 | RGB 颜色的起始索引。 |
| 长度 | Int32 | 要转换的 RGB 像素数量。 |
| rgbIccStream | 流 | RGB 配置文件流。 |
| cmykIccStream | 流 | CMYK 配置文件流。 |

### 返回值

CMYK 颜色以字节数组的形式呈现。

### 另请参阅

* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


