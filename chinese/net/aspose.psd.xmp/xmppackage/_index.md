---
title: Class XmpPackage
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Xmp.XmpPackage 班级. 定义表示 XMP 包基本抽象的 XmpPackage 类
type: docs
weight: 6270
url: /zh/net/aspose.psd.xmp/xmppackage/
---
## XmpPackage class

定义表示 XMP 包基本抽象的 XmpPackage 类。

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [Item](../../aspose.psd.xmp/xmppackage/item/) { get; set; } | 获取或设置Object使用指定的键. |
| virtual [Keys](../../aspose.psd.xmp/xmppackage/keys/) { get; } | 获取 XMP 包中的密钥。 |
| [NamespaceUri](../../aspose.psd.xmp/xmppackage/namespaceuri/) { get; } | 获取命名空间 URI。 |
| [Prefix](../../aspose.psd.xmp/xmppackage/prefix/) { get; } | 获取前缀。 |
| [XmlNamespace](../../aspose.psd.xmp/xmppackage/xmlnamespace/) { get; } | 获取 XML 命名空间。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [AddValue](../../aspose.psd.xmp/xmppackage/addvalue/)(string, string) | 添加值。 |
| virtual [Clear](../../aspose.psd.xmp/xmppackage/clear/)() | 清除此实例。 |
| virtual [ContainsKey](../../aspose.psd.xmp/xmppackage/containskey/)(string) | 判断指定的key是否包含key. |
| [GetEnumerator](../../aspose.psd.xmp/xmppackage/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| virtual [GetXmlValue](../../aspose.psd.xmp/xmppackage/getxmlvalue/)() | 将 XMP 值转换为 XML 表示。 |
| virtual [Remove](../../aspose.psd.xmp/xmppackage/remove/)(string) | 删除具有指定键的值。 |
| virtual [SetValue](../../aspose.psd.xmp/xmppackage/setvalue/)(string, IXmlValue) | 设置值。 |
| virtual [SetXmpTypeValue](../../aspose.psd.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | 设置 XMP 类型值。 |

### 也可以看看

* interface [IXmlValue](../ixmlvalue/)
* 命名空间 [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* 部件 [Aspose.PSD](../../)


