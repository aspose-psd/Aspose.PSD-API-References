---
title: Class Metered
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Metered class. Provides methods to set metered key
type: docs
weight: 5400
url: /net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

Provides methods to set metered key.

```csharp
public class Metered
```

## Constructors

| Name | Description |
| --- | --- |
| [Metered](metered/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | Determines whether the specified Object, is equal to this instance. |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | Gets the name of the product. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again. |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | Gets consumption credit |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | Gets consumption file size |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | Check whether metered is licensed |

## Examples

In this example, an attempt will be made to set metered public and private key

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


