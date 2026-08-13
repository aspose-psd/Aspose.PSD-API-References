---
title: "Sınıf Metered"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Metered sınıfı. Ölçümlü anahtarı ayarlamak için yöntemler sağlar"
type: docs
weight: 5640
url: /tr/net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

Ölçülen anahtarı ayarlamak için yöntemler sağlar.

```csharp
public class Metered
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Metered](metered/)() | Varsayılan yapıcı. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | Belirtilen Nesnenin bu örnek ile eşit olup olmadığını belirler. |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | Ürünün adını alır. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | Ölçümlü genel ve özel anahtarı ayarlar. Ölçümlü lisans satın alırsanız, uygulamayı başlattığınızda bu API çağrılmalıdır, genellikle bu yeterlidir. Ancak, tüketim verileri yüklenemediği ve 24 saati aştığı sürece lisans değerlendirme durumuna ayarlanır; böyle bir durumu önlemek için lisans durumunu düzenli olarak kontrol etmelisiniz, eğer değerlendirme durumundaysa bu API'yi tekrar çağırın. |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | Tüketim kredisini alır |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | Tüketim dosya boyutunu alır |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | Ölçümlünün lisanslı olup olmadığını kontrol edin |

## Örnekler

Bu örnekte, ölçümlü genel ve özel anahtarın ayarlanması denenecek

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


