---
title: "Classe License"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.License. Fournit des méthodes pour licencier le composant"
type: docs
weight: 5540
url: /fr/net/aspose.psd/license/
---
{{< psd/tize >}}
## License class

Fournit des méthodes pour licencier le composant.

```csharp
public class License
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [License](license/)() | Initialise une nouvelle instance de cette classe. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | Licence le composant. |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | Licence le composant. |

## Exemples

Dans cet exemple, une tentative sera effectuée pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée, puis dans les ressources incorporées de l'assembly appelant.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


