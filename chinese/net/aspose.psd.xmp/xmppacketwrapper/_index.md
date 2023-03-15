---
title: Class XmpPacketWrapper
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Xmp.XmpPacketWrapper 班级. 包含序列化的 xmp 包包括标题和尾部
type: docs
weight: 6290
url: /zh/net/aspose.psd.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

包含序列化的 xmp 包，包括标题和尾部。

```csharp
public class XmpPacketWrapper
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | 初始化一个新的实例`XmpPacketWrapper`类. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | 初始化一个新的实例`XmpPacketWrapper`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | 获取头处理指令。 |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | 获取 XMP 元数据。可选. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | 获取数组[`XmpPackage`](../xmppackage/)在 XMP. 里面 |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | 获取 XMP 结构内的包数量。 |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | 获取尾部处理指令。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | 添加包。 |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | 删除所有[`XmpPackage`](../xmppackage/)在 XMP. 里面 |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | 确定包是否存在于 xmp 包装器中。 |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | 通过命名空间 URI 获取包。 |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | 删除 XMP 包。 |

### 评论

由一对 XML 处理指令 (PI) 组成的包装器可以放置在 rdf:RDF 元素周围。

### 也可以看看

* 命名空间 [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* 部件 [Aspose.PSD](../../)


