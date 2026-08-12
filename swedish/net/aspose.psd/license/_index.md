---
title: "Klass License"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.License klass. Tillhandahåller metoder för att licensiera komponenten"
type: docs
weight: 5540
url: /sv/net/aspose.psd/license/
---
{{< psd/tize >}}
## License class

Tillhandahåller metoder för att licensiera komponenten.

```csharp
public class License
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [License](license/)() | Initierar en ny instans av denna klass. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | Licensierar komponenten. |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | Licensierar komponenten. |

## Exempel

I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande sammansättningen, i mappen för startsammanställningen och sedan i de inbäddade resurserna för den anropande sammansättningen.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


