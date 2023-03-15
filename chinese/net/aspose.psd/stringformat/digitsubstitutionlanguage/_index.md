---
title: StringFormat.DigitSubstitutionLanguage
second_title: Aspose.PSD for .NET API 参考
description: StringFormat 财产. 获取或设置本地数字替换西方数字时使用的语言
type: docs
weight: 50
url: /zh/net/aspose.psd/stringformat/digitsubstitutionlanguage/
---
## StringFormat.DigitSubstitutionLanguage property

获取或设置本地数字替换西方数字时使用的语言。

```csharp
public int DigitSubstitutionLanguage { get; set; }
```

### 适当的价值

国家语言支持 (NLS) 语言标识符，用于标识将本地数字替换为西方数字时将使用的语言。 您可以通过LCID的财产CultureInfo对象作为 NLS 语言标识符。 例如，假设您创建一个CultureInfo通过将字符串“ar-EG”传递给一个对象CultureInfoconstructor. 如果你通过LCID那的财产CultureInfo对象连同. Traditional到StringDigitSubstitute) method, 那么阿拉伯-印度数字将在显示时替换为西方数字。

### 评论

setter 是为过时的方法 SetDigitSubstitution 引入的。

### 也可以看看

* class [StringFormat](../)
* 命名空间 [Aspose.PSD](../../stringformat/)
* 部件 [Aspose.PSD](../../../)


