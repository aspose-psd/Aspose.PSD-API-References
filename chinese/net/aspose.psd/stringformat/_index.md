---
title: Class StringFormat
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.StringFormat 班级. 封装文本布局信息例如对齐方式方向和制表位显示操作例如省略号插入和国家数字替换和 OpenType 功能此类不能被继承
type: docs
weight: 5670
url: /zh/net/aspose.psd/stringformat/
---
## StringFormat class

封装文本布局信息（例如对齐方式、方向和制表位）显示操作（例如省略号插入和国家数字替换）和 OpenType 功能。此类不能被继承。

```csharp
public sealed class StringFormat : DisposableObject
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | 初始化一个新的`StringFormat`对象. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | 初始化一个新的`StringFormat`来自指定现有对象`StringFormat`对象. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | 初始化一个新的`StringFormat`具有指定对象[`StringFormatFlags`](../stringformatflags/)枚举和语言. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | 获取通用默认值`StringFormat`对象. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | 获取通用排版`StringFormat`对象. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | 获取或设置垂直平面上的文本对齐信息。 |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | 获取或设置本地数字替换西方数字时使用的语言。 |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | 获取或设置用于数字替换的方法。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | 获取文本行开头和第一个制表位之间的空格数。 |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | 获取或设置一个[`StringFormatFlags`](../stringformatflags/)包含格式信息的枚举。 |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | 获取或设置[`HotkeyPrefix`](../hotkeyprefix/)为此目的`StringFormat`对象. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | 获取或设置直线在水平面上的对齐方式。 |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | 获取制表位之间距离的数组，单位由[`PageUnit`](../graphics/pageunit/)财产. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | 获取或设置[`StringTrimming`](../stringtrimming/)枚举这个`StringFormat`对象. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | 创建一个深度克隆`StringFormat`对象. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | 为此设置制表位`StringFormat`对象. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | 转换这个`StringFormat`对象为人类可读的字符串。 |

### 也可以看看

* class [DisposableObject](../disposableobject/)
* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


