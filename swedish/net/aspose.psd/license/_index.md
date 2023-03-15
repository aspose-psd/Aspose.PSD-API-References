---
title: Class License
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.License klass. Tillhandahåller metoder för att licensiera komponenten.
type: docs
weight: 5050
url: /sv/net/aspose.psd/license/
---
## License class

Tillhandahåller metoder för att licensiera komponenten.

```csharp
public class License
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [License](license/)() | Initierar en ny instans av den här klassen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | Licensierar komponenten. |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | Licensierar komponenten. |

### Exempel

I det här exemplet kommer ett försök att göras att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande assembly, i mappen och sedan entry i mappen de inbäddade resurserna för den anropande församlingen.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


