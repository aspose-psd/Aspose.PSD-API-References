---
title: "License.License"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur License. Initialise une nouvelle instance de cette classe"
type: docs
weight: 10
url: /fr/net/aspose.psd/license/license/
---
{{< psd/tize >}}
## License constructor

Initialise une nouvelle instance de cette classe.

```csharp
public License()
```

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

* class [License](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


