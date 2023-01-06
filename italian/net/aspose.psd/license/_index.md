---
title: License
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Fornisce i metodi per concedere in licenza il componente.
type: docs
weight: 4980
url: /it/net/aspose.psd/license/
---
## License class

Fornisce i metodi per concedere in licenza il componente.

```csharp
public class License
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [License](license)() | Inizializza una nuova istanza di questa classe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense#setlicense)(Stream) | concede in licenza il componente. |
| [SetLicense](../../aspose.psd/license/setlicense#setlicense_1)(string) | concede in licenza il componente. |

### Esempi

In questo esempio, si tenterà di trovare un file di licenza denominato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e quindi in le risorse incorporate dell'assembly chiamante.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->