---
title: ToCmykIccBytes
second_title: Aspose.PSD for .NET API 参考
description: 使用自定义 ICC 配置文件将 RGB 转换为 CMYK
type: docs
weight: 120
url: /zh/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
## CmykColorHelper.ToCmykIccBytes method

使用自定义 ICC 配置文件将 RGB 转换为 CMYK。

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pixels | Int32[] | RGB 颜色以 32 位整数值表示。 |
| startIndex | Int32 | RGB 颜色的起始索引。 |
| length | Int32 | 要转换的 RGB 像素数。 |
| rgbIccStream | Stream | RGB 配置文件流。 |
| cmykIccStream | Stream | CMYK 配置文件流。 |

### 返回值

CMYK 颜色呈现为字节数组。

### 也可以看看

* class [CmykColorHelper](../../cmykcolorhelper)
* 命名空间 [Aspose.PSD](../../cmykcolorhelper)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
