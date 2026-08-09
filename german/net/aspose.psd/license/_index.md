---
title: "Klasse License"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.License Klasse. Stellt Methoden zur Lizenzierung der Komponente bereit."
type: docs
weight: 5540
url: /de/net/aspose.psd/license/
---
{{< psd/tize >}}
## License class

Stellt Methoden zur Lizenzierung der Komponente bereit.

```csharp
public class License
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [License](license/)() | Initialisiert eine neue Instanz dieser Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | Lizenziert die Komponente. |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | Lizenziert die Komponente. |

## Beispiele

In diesem Beispiel wird versucht, eine Lizenzdatei namens MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


