---
title: "类 Metered"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Metered 类。提供设置计量密钥的方法"
type: docs
weight: 5610
url: /zh/net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

提供设置计量密钥的方法。

```csharp
public class Metered
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Metered](metered/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | 确定指定的 Object 是否等于此实例。 |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | 获取产品名称。 |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | 设置计量的公钥和私钥。如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这就足够了。然而，如果始终无法上传使用数据且超过 24 小时，许可证将被设置为评估状态。为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。 |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | 获取消费积分 |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | 获取消费文件大小 |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | 检查计量是否已授权 |

## 示例

在此示例中，将尝试设置计量的公钥和私钥

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


