---
title: "Klass Metered"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Metered class. Tillhandahåller metoder för att ställa in metered key"
type: docs
weight: 5610
url: /sv/net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

Tillhandahåller metoder för att ställa in mätad nyckel.

```csharp
public class Metered
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Metered](metered/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | Bestämmer om det angivna objektet är lika med den här instansen. |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | Hämtar produktens namn. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | Sätter metered public and private key. Om du köper metered-licens, när du startar applikationen bör detta API anropas, normalt räcker detta. Men om uppladdning av konsumtionsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus; för att undvika sådant bör du regelbundet kontrollera licensstatusen, och om den är i utvärderingsstatus, anropa detta API igen. |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | Hämtar konsumtionskredit |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | Hämtar konsumtionsfilens storlek |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | Kontrollera om metered är licensierad |

## Exempel

I det här exemplet kommer ett försök att ställa in metered public and private key att göras

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


