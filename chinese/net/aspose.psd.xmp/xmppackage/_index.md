---
title: "类 XmpPackage"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Xmp.XmpPackage 类。定义 XmpPackage 类，表示 XMP 包的基础抽象"
type: docs
weight: 6770
url: /zh/net/aspose.psd.xmp/xmppackage/
---
{{< psd/tize >}}
## XmpPackage class

定义了 XmpPackage 类，该类表示 XMP 包的基础抽象。

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [Item](../../aspose.psd.xmp/xmppackage/item/) { get; set; } | 获取或设置具有指定键的 Object。 |
| virtual [Keys](../../aspose.psd.xmp/xmppackage/keys/) { get; } | 获取 XMP 包中的键。 |
| [NamespaceUri](../../aspose.psd.xmp/xmppackage/namespaceuri/) { get; } | 获取命名空间 URI。 |
| [Prefix](../../aspose.psd.xmp/xmppackage/prefix/) { get; } | 获取前缀。 |
| [XmlNamespace](../../aspose.psd.xmp/xmppackage/xmlnamespace/) { get; } | 获取 XML 命名空间。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [AddValue](../../aspose.psd.xmp/xmppackage/addvalue/)(string, string) | 添加该值。 |
| virtual [Clear](../../aspose.psd.xmp/xmppackage/clear/)() | 清除此实例。 |
| virtual [ContainsKey](../../aspose.psd.xmp/xmppackage/containskey/)(string) | 确定指定的键是否包含键。 |
| [GetEnumerator](../../aspose.psd.xmp/xmppackage/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| virtual [GetXmlValue](../../aspose.psd.xmp/xmppackage/getxmlvalue/)() | 将 XMP 值转换为 XML 表示形式。 |
| virtual [Remove](../../aspose.psd.xmp/xmppackage/remove/)(string) | 移除具有指定键的值。 |
| virtual [SetValue](../../aspose.psd.xmp/xmppackage/setvalue/)(string, IXmlValue) | 设置值。 |
| virtual [SetXmpTypeValue](../../aspose.psd.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | 设置 XMP 类型值。 |

### 另请参阅

* interface [IXmlValue](../ixmlvalue/)
* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


