---
title: CmykColorHelper.ToCmykIccBytes
second_title: Aspose.PSD for .NET API 参考
description: CmykColorHelper 方法. 使用自定义 ICC 配置文件将 RGB 转换为 CMYK
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
| pixels | Int32[] | RGB 颜色显示为 32 位整数值。 |
| startIndex | Int32 | RGB 颜色的起始索引。 |
| length | Int32 | 要转换的 RGB 像素数。 |
| rgbIccStream | Stream | RGB 配置文件流。 |
| cmykIccStream | Stream | CMYK 配置文件流。 |

### 返回值

以字节数组形式呈现的 CMYK 颜色。

### 也可以看看

* class [CmykColorHelper](../)
* 命名空间 [Aspose.PSD](../../cmykcolorhelper/)
* 部件 [Aspose.PSD](../../../)


