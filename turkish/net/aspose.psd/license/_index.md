---
title: "Sınıf License"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.License sınıfı. Bileşeni lisanslamak için yöntemler sağlar."
type: docs
weight: 5570
url: /tr/net/aspose.psd/license/
---
{{< psd/tize >}}
## License class

Bileşeni lisanslamak için yöntemler sağlar.

```csharp
public class License
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [License](license/)() | Bu sınıfın yeni bir örneğini başlatır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | Bileşeni lisanslar. |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | Bileşeni lisanslar. |

## Örnekler

Bu örnekte, bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


