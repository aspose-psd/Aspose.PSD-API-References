---
title: "类 XmpPacketWrapper"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Xmp.XmpPacketWrapper 类。包含序列化的 XMP 包，包括标头和尾部"
type: docs
weight: 6790
url: /zh/net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

包含已序列化的 xmp 包，包括头部和尾部。

```csharp
public class XmpPacketWrapper
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | 初始化 `XmpPacketWrapper` 类的新实例。 |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | 初始化 `XmpPacketWrapper` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | 获取标头处理指令。 |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | 获取 XMP 元数据。可选。 |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | 获取 XMP 中的 [`XmpPackage`](../xmppackage/) 数组。 |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | 获取 XMP 结构中包的数量。 |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | 获取尾部处理指令。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | 添加该包。 |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | 移除 XMP 中的所有 [`XmpPackage`](../xmppackage/)。 |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | 确定包是否存在于 XMP 包装器中。 |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | 按命名空间 URI 获取包。 |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | 移除 XMP 包。 |

## 备注

一个由一对 XML 处理指令（PI）组成的包装器可以放置在 rdf:RDF 元素周围。

### 另请参阅

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


