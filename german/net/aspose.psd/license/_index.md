---
title: Class License
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.License klas. Stellt Methoden zur Lizenzierung der Komponente bereit.
type: docs
weight: 5050
url: /de/net/aspose.psd/license/
---
## License class

Stellt Methoden zur Lizenzierung der Komponente bereit.

```csharp
public class License
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [License](license/)() | Initialisiert eine neue Instanz dieser Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | Lizenziert die Komponente. |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | Lizenziert die Komponente. |

### Beispiele

In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic in dem Ordner zu finden, der die Komponente enthält, in dem Ordner, der die aufrufende Assembly enthält, im Ordner des Eintrags Assembly und dann in die eingebetteten Ressourcen der aufrufenden Assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


